> An approach to consider multiple task at once as opposed to **sequential** in linear

1. Initialize using initial state and goal state: Compare the predicates
2. Add steps to Achieve the Difference in predicates
3. Establish Order(weakly ordered) by constraining operators according to dependencies
4. Insert operators in b/w to undo if any preconditions get cancelled by following operators
5. Create complete plan  from the partial plans