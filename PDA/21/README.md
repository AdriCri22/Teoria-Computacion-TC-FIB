# Exercise 21

## Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/PDA/21/Statement_21.png)

## Image solution:
![Solution](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/PDA/21/Image_sol_21.png)

## Text solution:
    Z 0 10 11 9
    0  -> Zb|Z, Ab|A   -> 0
    0  -> Za|Z, Aa|A   -> 1
    0  -> Ac|A         -> 4
    0  -> Zc|Z         -> 9
    1  -> Za|Z, Aa|A   -> 1
    1  -> Zb|Z, Ab|A   -> 2
    1  -> Ac|A         -> 4
    1  -> Zc|Z         -> 9
    10 -> Zb|Z         -> 10
    10 -> Za|Z         -> 11
    11 -> Za|Z         -> 9
    2  -> Zb|Z, Ab|A   -> 0
    2  -> Za|ZA, Aa|AA -> 3
    2  -> Ac|A         -> 4
    2  -> Zc|Z         -> 9
    3  -> Ab|A         -> 2
    3  -> Aa|A         -> 3
    3  -> Ac|A         -> 4
    4  -> Aa|A         -> 4
    4  -> Ab|A         -> 5
    5  -> Ab|A         -> 5
    5  -> Aa|A         -> 6
    6  -> Aa|A         -> 4
    6  -> Ab|          -> 7
    7  -> Z |Z         -> 10
    7  -> Aa|A         -> 6
    7  -> Ab|A         -> 7
    9  -> Zb|Z         -> 10
    9  -> Za|Z         -> 9
