# Exercise 6

## Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/PDA/06/Statement_6.png)

## Image solution:
![Solution](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/PDA/06/Image_sol_6.png)

## Text solution:
    Z 0 0
    0 -> Za|ZAA      -> 1
    0 -> Zb|ZB       -> 2
    1 -> Z |Z        -> 0
    1 -> Aa|AAA, Ab| -> 1
    2 -> Z |Z        -> 0
    2 -> Bb|BB       -> 2
    2 -> Ba|         -> 3
    3 -> Z |ZA       -> 1
    3 -> B |         -> 2
