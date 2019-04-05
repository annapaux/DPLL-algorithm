# DPLL-algorithm

DPLL takes a knowledge base, finds whether it is satisfiable and if so returns such model. 

- A Literal class defines literals, their name, sign (True/ False) and operators (e.g. __eg__()).
- DPLLSatisfiable() defines the clauses and runs DPLL() which recursively assigns symbols a truth value until a model is found that satisfies the knowledge base. If one is found, it returns True and the model, if none is found, it returns False and a model. 

```
Example literal definition:  A = Literal("A")
Example KB input:            {A, B}, {A, -C}, {-A, B, D}] 
Example satisfiable output:  True
Example model output:        {A: true, B: true, C: false, D: free}
```
