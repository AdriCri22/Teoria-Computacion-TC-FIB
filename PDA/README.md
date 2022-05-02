# PDA (PushDown Automaton) - PDA (Autómatas con Pila)

## Exercise 1

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/PDA/Statements/Statement_01.png)

### Image solution:
![Solution](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/PDA/Image_solutions/Image_sol_01.png)

### Text solution:
    Z 1 1 4
    1 -> Za|ZA -> 2
    2 -> Aa|AA -> 2
    2 -> Ab|   -> 3
    3 -> Ab|   -> 3
    3 -> Z |Z  -> 4

## Exercise 2

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/PDA/Statements/Statement_02.png)

### Image solution:
![Solution](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/PDA/Statements/Image_sol_02.png)

### Text solution:
    Z 0 0 3
    0 -> Za|ZA -> 1
    1 -> Aa|AA -> 1
    1 -> Ab|   -> 2
    2 -> A |   -> 4
    4 -> Ab|   -> 2
    4 -> Z |Z  -> 3
 
## Exercise 3

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/PDA/Statements/Statement_03.png)

### Image solution:
![Solution](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/PDA/Statements/Image_sol_03.png)

### Text solution:
    Z 0 0
    0 -> Za|ZA, Zb|ZB           -> 1
    1 -> Z |Z                   -> 0
    1 -> Aa|AA, Bb|BB, Ba|, Ab| -> 1
    
## Exercise 4

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/PDA/Statements/Statement_04.png)

### Image solution:
![Solution](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/PDA/Statements/Image_sol_04.png)

### Text solution:
    Z 0 1
    0 -> Za|ZX, Zb|ZY                         -> 1
    1 -> Aa|AA, Bb|BB, Ab|, Ba|, Xa|XA, Yb|YB -> 1
    1 -> Xb|, Ya|                             -> 2
    2 -> Z |Z                                 -> 0
