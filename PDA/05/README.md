# Exercise 5

## Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/PDA/05/Statement_5.png)

## Image solution:
![Solution](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/PDA/05/Image_sol_5.png)

## Text solution:
    Z 0 0 1
    0 -> Za|ZX                  -> 1
    0 -> Zb|ZY                  -> 2
    1 -> Xb|                    -> 0
    1 -> Aa|AA, Ab|, Ba|, Xa|XA -> 1
    2 -> Ya|                    -> 0
    2 -> Bb|BB, Ab|, Ba|, Yb|YB -> 2
