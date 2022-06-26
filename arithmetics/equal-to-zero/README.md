# Equal To Zero (EQT) [⮌](../README.md)
A simple arithmetic circuit that is true if both inputs are equal to zero. Note this blueprint is for
demonstration purposes only and can easily be replaced by a single NOR gate.

## Information

#### Boolean expression
```
R = ¬(A∨B)
```

#### Truth table

| A | B |   |  R  |
|---|---|---|-----|
| 0 | 0 |   |  1  |
| 0 | 1 |   |  0  |
| 1 | 0 |   |  0  |
| 1 | 1 |   |  0  |

## Blueprint

[Blueprint Hash](./equal_to_zero.vcb)


![Half Adder](./equal_to_zero.png)