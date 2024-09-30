# Boolean Function Synthesis

## Truth Table to Boolean Expression

### Constructing a Disjunctive Normal Form Formula

- Go row by row in the truth table
- Focus only on rows that have a value of 1
- Write an expression that evaluates to a value of 1 only at that row and evaluates as 0 for other rows
- Do this for all rows with values of 1
- To get a single expression that evaluates to 1 for all rows with value one, we **OR** the individual expressions we got previously.

**Theorem**
Any boolean function can be represented using an expression containing AND, OR and NOT.
Furthermore, any boolean function can be represented using an expression containing AND and NOT operations.

**Proof**: (x OR y) = NOT(NOT(x) AND NOT(y))

## NAND

(x NAND y) = NOT(x AND y)

*Theorem:* Any boolean function can be represented using an expression containing only NAND operations.

*Proof:*

1. NOT(x) = (x NAND y)
2. (x AND y) = NOT(x NAND y)
