# Exercise 10

## Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/PDA/10/Statement_10.png)

## Image solution:
![Solution](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/PDA/10/Image_sol_10.png)

## Text solution:
    Z 0 0 1 5
    0 -> Za|Z       -> 1
    0 -> Zb|ZB      -> 2
    1 -> Zb|ZB      -> 2
    1 -> Za|ZA      -> 3
    2 -> Z |Z       -> 0
    2 -> Bb|BB, Ab| -> 2
    2 -> Ba|B, Aa|A -> 4
    3 -> Ab|, Bb|BB -> 2
    3 -> Aa|AA, Ba| -> 3
    3 -> Z |Z       -> 5
    4 -> Bb|BB, Ab| -> 2
    4 -> Ba|, Aa|AA -> 3
    5 -> Zb|ZB      -> 2
    5 -> Za|ZA      -> 3
