# Selector [⮌](../README.md)
A simple switch that selects either one of two inputs as output based on a third input. Switching
between inputs.

## Information

#### Boolean expression
```
Out = (¬A∧C)∨(A∧B)
```

#### Truth table

| A | B | C |   | Out |
|---|---|---|---|-----|
| 0 | 0 | 0 |   | 0   |
| 0 | 0 | 1 |   | 1   |
| 0 | 1 | 0 |   | 0   |
| 0 | 1 | 1 |   | 1   |
| 1 | 0 | 0 |   | 0   |
| 1 | 0 | 1 |   | 0   |
| 1 | 1 | 0 |   | 1   |
| 1 | 1 | 1 |   | 1   |

## Blueprint

[Blueprint Hash](./selector.vcb)


![Half Adder](./selector.png)