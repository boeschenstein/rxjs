# RxJs

Docs: <https://rxjs.dev/>

Decision Tree: <https://rxjs.dev/operator-decision-tree>

## switchMap, mergeMap, concatMap, and exhaustMap

-🤯mergeMap: I'm a hard worker, I can prepare multiple orders at the same time ! But I don't respect orders sequence.
  - examples: load data
-😇concatMap: I respect orders sequence! You will get your order as soon as I finish what I'm currently doing.
  - examples: update data
-🙄exhaustMap: I'm exhausted ! when I prepare an order, I won't listen to any other order.
  - examples: 
-😈switchMap: I'm mean ! your order will be in trash if I receive new one.
  - examples: filter data

<https://dev.to/hssanbzlm/switchmap-mergemap-concatmap-and-exhaustmap-like-you-have-never-seen-109o>
