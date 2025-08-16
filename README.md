
# Term Theory (MVP)
Exploring a type-free, arrows-only foundation (Term Theory MVP),

with a minimal (possibly dependent) structure:

```cpp
struct Term {
    Term* domain;    // (possibly dependent source)
    Term* codomain;  // (possibly dependent target)
};
```


**Ideas for extensions:**

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

This project explores whether a type-free, arrows-only foundation can be a seed for a minimal logic/programming language.