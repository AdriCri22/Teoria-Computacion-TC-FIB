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
![Solution](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/PDA/Image_solutions/Image_sol_02.png)

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
![Solution](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/PDA/Image_solutions/Image_sol_03.png)

### Text solution:
    Z 0 0
    0 -> Za|ZA, Zb|ZB           -> 1
    1 -> Z |Z                   -> 0
    1 -> Aa|AA, Bb|BB, Ba|, Ab| -> 1
    
## Exercise 4

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/PDA/Statements/Statement_04.png)

### Image solution:
![Solution](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/PDA/Image_solutions/Image_sol_04.png)

### Text solution:
    Z 0 1
    0 -> Za|ZX, Zb|ZY                         -> 1
    1 -> Aa|AA, Bb|BB, Ab|, Ba|, Xa|XA, Yb|YB -> 1
    1 -> Xb|, Ya|                             -> 2
    2 -> Z |Z                                 -> 0

## Exercise 5

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/PDA/Statements/Statement_05.png)

### Image solution:
![Solution](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/PDA/Image_solutions/Image_sol_05.png)

### Text solution:
    Z 0 0 1
    0 -> Za|ZX                  -> 1
    0 -> Zb|ZY                  -> 2
    1 -> Xb|                    -> 0
    1 -> Aa|AA, Ab|, Ba|, Xa|XA -> 1
    2 -> Ya|                    -> 0
    2 -> Bb|BB, Ab|, Ba|, Yb|YB -> 2
## Exercise 6

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/PDA/Statements/Statement_06.png)

### Image solution:
![Solution](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/PDA/Image_solutions/Image_sol_06.png)

### Text solution:
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

## Exercise 7

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/PDA/Statements/Statement_07.png)

### Image solution:
![Solution](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/PDA/Image_solutions/Image_sol_07.png)

### Text solution:
    Z 0 0 1
    0 -> Za|ZAA              -> 1
    0 -> Zb|ZB               -> 2
    1 -> Aa|AAA, Ab|, Za|ZAA -> 1
    1 -> Zb|ZB               -> 2
    2 -> Z |Z                -> 0
    2 -> Bb|BB               -> 2
    2 -> Ba|                 -> 4
    4 -> Z |ZA               -> 1
    4 -> B |                 -> 2

## Exercise 8

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/PDA/Statements/Statement_08.png)

### Image solution:
![Solution](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/PDA/Image_solutions/Image_sol_08.png)

### Text solution:
    Z 0 0 2
    0 -> Za|ZAA       -> 1
    0 -> Zb|ZB        -> 2
    1 -> Z |Z         -> 0
    1 -> Aa|AAA, Ab|  -> 1
    2 -> Za|ZAA       -> 1
    2 -> Bb|BB, Zb|ZB -> 2
    2 -> Ba|          -> 4
    4 -> Z |ZA        -> 1
    4 -> B |          -> 2

## Exercise 9

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/PDA/Statements/Statement_09.png)

### Image solution:
![Solution](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/PDA/Image_solutions/Image_sol_09.png)

### Text solution:
    Z 0 0 F
    0 -> Za|ZA -> 1
    1 -> Aa|AA -> 1
    1 -> A |A  -> 2
    2 -> Ab|   -> 3
    2 -> Ab|   -> 4
    2 -> Z |Z  -> F
    3 -> A |   -> 2
    4 -> Ab|   -> 4
    4 -> Z |Z  -> F

## Exercise 10

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/PDA/Statements/Statement_10.png)

### Image solution:
![Solution](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/PDA/Image_solutions/Image_sol_10.png)

### Text solution:
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
    

## Exercise 11

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/PDA/Statements/Statement_11.png)

### Image solution:
![Solution](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/PDA/Image_solutions/Image_sol_11.png)

### Text solution:
    Z 0 0 4
    0 -> Za|ZA -> 1
    1 -> Aa|AA -> 1
    1 -> Ab|   -> 2
    1 -> Ac|   -> 3
    2 -> Ab|   -> 2
    2 -> Ac|   -> 3
    2 -> Z |Z  -> 4
    3 -> Ac|   -> 3
    3 -> Z |Z  -> 4

## Exercise 12

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/PDA/Statements/Statement_12.png)

### Image solution:
![Solution](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/PDA/Image_solutions/Image_sol_12.png)

### Text solution:
    Z 0 0 4 5
    0 -> Za|ZA      -> 1
    0 -> Zb|ZB      -> 2
    1 -> Aa|AA      -> 1
    1 -> Ab|        -> 2
    2 -> Ab|, Bb|BB -> 2
    2 -> Bc|        -> 3
    2 -> Z |Z       -> 5
    3 -> Bc|        -> 3
    3 -> Z |Z       -> 4
    5 -> Zb|ZB      -> 2

## Exercise 13

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/PDA/Statements/Statement_13.png)

### Image solution:
![Solution](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/PDA/Image_solutions/Image_sol_13.png)

### Text solution:
    Z 0 0 4
    0 -> Za|ZA -> 1
    0 -> Za|ZA -> 5
    0 -> Zc|Z  -> 8
    0 -> Zb|Z  -> 9
    1 -> Aa|AA -> 1
    1 -> Ab|   -> 2
    2 -> Ab|   -> 2
    2 -> Zc|Z  -> 3
    2 -> Z |Z  -> 4
    3 -> Zc|Z  -> 3
    3 -> Z |Z  -> 4
    5 -> Aa|AA -> 5
    5 -> Ab|A  -> 6
    5 -> Ac|   -> 7
    6 -> Ab|A  -> 6
    6 -> Ac|   -> 7
    7 -> Z |Z  -> 4
    7 -> Ac|   -> 7
    8 -> Z |Z  -> 4
    8 -> Zc|Z  -> 8
    9 -> Z |Z  -> 4
    9 -> Zb|Z  -> 9

## Exercise 14

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/PDA/Statements/Statement_14.png)

### Image solution:
![Solution](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/PDA/Image_solutions/Image_sol_14.png)

### Text solution:
    Z 0 0 4
    0 -> Za|ZA -> 1
    0 -> Zc|Z  -> 3
    0 -> Za|Z  -> 5
    0 -> Zb|ZB -> 6
    1 -> Aa|AA -> 1
    1 -> Ab|   -> 2
    2 -> Ab|   -> 2
    2 -> Zc|Z  -> 3
    2 -> Z |Z  -> 4
    3 -> Zc|Z  -> 3
    3 -> Z |Z  -> 4
    5 -> Z |Z  -> 4
    5 -> Za|Z  -> 5
    5 -> Zb|ZB -> 6
    6 -> Bb|BB -> 6
    6 -> Bc|   -> 7
    7 -> Z |Z  -> 4
    7 -> Bc|   -> 7

## Exercise 15

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/PDA/Statements/Statement_15.png)

### Image solution:
![Solution](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/PDA/Image_solutions/Image_sol_15.png)

### Text solution:
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

## Exercise 16

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/PDA/Statements/Statement_16.png)

### Image solution:
![Solution](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/PDA/Image_solutions/Image_sol_16.png)

### Text solution:
    Z 0 0 3
    0 -> Za|ZA, Zb|ZB               -> 1
    1 -> Aa|AA, Bb|BB, Ab|AB, Ba|BA -> 1
    1 -> Aa|, Bb|, A |, B |         -> 2
    2 -> Aa|, Bb|                   -> 2
    2 -> Z |Z                       -> 3

## Exercise 17

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/PDA/Statements/Statement_17.png)

### Image solution:
![Solution](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/PDA/Image_solutions/Image_sol_17.png)

### Text solution:
    Z 0 0
    0 -> Z(|ZP      -> 1
    1 -> Z |Z       -> 0
    1 -> P(|PP, P)| -> 1

## Exercise 18

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/PDA/Statements/Statement_18.png)

### Image solution:
![Solution](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/PDA/Image_solutions/Image_sol_18.png)

### Text solution:
    Z 0 0
    0 -> Z(|ZP, Z[|ZO                         -> 1
    1 -> Z |Z                                 -> 0
    1 -> P)|, O]|, P[|PO, P(|PP, O[|OO, O(|OP -> 1

## Exercise 19

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/PDA/Statements/Statement_19.png)

### Image solution:
![Solution](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/PDA/Image_solutions/Image_sol_19.png)

### Text solution:
    Z 0 3
    0 -> Zb|Z        -> 0
    0 -> Za|ZA       -> 1
    0 -> Zc|Z        -> 2
    1 -> Aa|AA, Ab|A -> 1
    1 -> Ac|A        -> 2
    2 -> Ab|, Aa|A   -> 2
    2 -> Z |Z        -> 3
    3 -> Za|Z        -> 3

## Exercise 20

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/PDA/Statements/Statement_20.png)

### Image solution:
![Solution](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/PDA/Image_solutions/Image_sol_20.png)

### Text solution:
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

## Exercise 21

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/PDA/Statements/Statement_21.png)

### Image solution:
![Solution](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/PDA/Image_solutions/Image_sol_21.png)

### Text solution:
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
