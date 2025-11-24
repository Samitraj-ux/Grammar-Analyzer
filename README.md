# Grammar-Analyzer
1. Start the program and initialize required data structures for storing grammar rules.
2. Input grammar from the user (set of productions).
3. Parse productions and store them in a structured format (e.g., HashMap with Nonterminal → RHS list).
4. Classify grammar according to Chomsky hierarchy (Type 0, Type 1, Type 2, Type 3).
Check for left recursion by scanning productions for rules like A → Aα | β.
5. If left recursion exists, transform the grammar to remove left recursion.
6. Check for left factoring by identifying common prefixes in productions.
7. If left factoring exists, apply transformation to simplify grammar.
8. Check for ambiguity by generating parse trees for sample strings and comparing results.
9. Display final results: grammar type, left recursion status, left factoring status, and
ambiguity status.
