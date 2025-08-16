
# Term Theory 🖇 (MVP) 
Exploring a type-free, arrows-only foundation (Term Theory MVP),

with a minimal (possibly dependent) structure:

```cpp
struct Term {
    Term* domain;    // (possibly dependent source)
    Term* codomain;  // (possibly dependent target)
};
```


## **Ideas for extensions:** 🌱 

- id(Term*) — identity arrow

- compose(Term*, Term*) — composition

- recurse(Term*) — self-dependent term

- Visualize as infinite unfolding tree

```
Term
 ├─ domain : Term
	 └─ domain : Term
		 └─ …
 └─ codomain : Term
      └─ codomain : Term
           └─ ...
```

- Maybe Term Theory can be extended along the lines of classical type theories, giving rise to the following multiverse of arrows-only analogues:

     | Type Theory                  | Term-Only Cousin             |
     | ---------------------------- | ---------------------------- |
     | Simple Type Theory           | Simple Term Theory           |
     | Dependent Type Theory        | Dependent Term Theory        |
     | Homotopy Type Theory         | Homotopy Term Theory         |
     | Cubical Type Theory          | Cubical Term Theory          |
     | Linear Type Theory           | Linear Term Theory           |
     | Modal / Temporal Type Theory | Modal / Temporal Term Theory |


*This project explores whether a type-free, arrows-only foundation can be a seed for a minimal logic/programming language.*

