# Half Adder [⮌](..)
A simple arithmetic circuit that adds two inputs together and provides the result in binary notation

## Information

#### Boolean expression
```
Sum = ¬(A∧B)∧(A∨B)
Carry = A∧B
```

#### Truth table

| A | B |   | Sum | Carry |
|---|---|---|-----|-------|
| 0 | 0 |   | 0   | 0     |
| 0 | 1 |   | 1   | 0     |
| 1 | 0 |   | 1   | 0     |
| 1 | 1 |   | 0   | 1     |

## Blueprint

[Blueprint Hash](./half_adder.vcb)


![Half Adder](./half_adder.png)