# Full Adder [⮌](../README.md)
An arithmetic circuit that adds three inputs together and provides the result in binary notation. Can count
up to 3 in binary.

## Information

#### Boolean expression
```
Sum = (C(A∨B))∨(A∧B∧C)
Carry = (A∧B∧C)+(¬(A∧B∧C)∧(A∨B∨C))
```

#### Truth table

| A | B | C |   | Sum | Carry |
|---|---|---|---|-----|-------|
| 0 | 0 | 0 |   | 0   | 0     |
| 0 | 0 | 1 |   | 1   | 0     |
| 0 | 1 | 0 |   | 1   | 0     |
| 0 | 1 | 1 |   | 0   | 1     |
| 1 | 0 | 0 |   | 1   | 0     |
| 1 | 0 | 1 |   | 0   | 1     |
| 1 | 1 | 0 |   | 0   | 1     |
| 1 | 1 | 1 |   | 1   | 1     |

## Blueprint

[Blueprint Hash](./full_adder.vcb)


![Full Adder](./full_adder.png)