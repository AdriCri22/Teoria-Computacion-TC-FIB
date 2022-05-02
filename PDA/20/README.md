# Exercise 20

## Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/PDA/20/Statement_20.png)

## Image solution:
![Solution](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/PDA/20/Image_sol_20.png)

## Text solution:
    Z 0 5 6 7
    0 -> Za|Z         -> 1
    0 -> Zb|Z         -> 2
    0 -> Zc|Z         -> 6
    1 -> Za|Z, Aa|A   -> 1
    1 -> Zb|ZA, Ab|AA -> 2
    1 -> Ac|A         -> 3
    1 -> Zc|Z         -> 6
    2 -> Aa|A, Za|Z   -> 1
    2 -> Ab|A, Zb|Z   -> 2
    2 -> Ac|A         -> 3
    2 -> Zc|Z         -> 6
    3 -> Aa|A         -> 3
    3 -> Ab|A         -> 4
    3 -> Z |Z         -> 6
    4 -> Aa|          -> 3
    4 -> Ab|A         -> 4
    4 -> Z |Z         -> 5
    6 -> Za|Z         -> 6
    6 -> Zb|Z         -> 7
    7 -> Zb|Z         -> 7
