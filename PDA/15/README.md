# Exercise 15

## Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/PDA/15/Statement_15.png)

## Image solution:
![Solution](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/PDA/15/Image_sol_15.png)

## Text solution:
    Z 0 5
    0 -> Za|ZA      -> 1
    0 -> Zc|Z       -> 3
    0 -> Zd|Z, Ze|Z -> 4
    0 -> Za|Z       -> 6
    0 -> Zb|ZB      -> 7
    1 -> Aa|AA      -> 1
    1 -> Ab|        -> 2
    2 -> Ab|        -> 2
    2 -> Zc|Z       -> 3
    2 -> Zd|Z       -> 4
    3 -> Zc|Z       -> 3
    3 -> Zd|Z       -> 4
    4 -> Z |Z       -> 5
    6 -> Ze|Z       -> 4
    6 -> Za|Z       -> 6
    6 -> Zb|ZB      -> 7
    7 -> Bb|BB      -> 7
    7 -> Bc|        -> 8
    8 -> Ze|Z       -> 4
    8 -> Bc|        -> 8
