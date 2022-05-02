# CFG (Context-Free Grammar) - CFG (Gramáticas Incontextuales)

## Exercise 1

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/CFG/Statements/Statement_01.png)

### Solution:
    S -> aSb |
    
## Exercise 2

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/CFG/Statements/Statement_02.png)

### Solution:
    S -> aSb | acb
    
## Exercise 3

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/CFG/Statements/Statement_03.png)

### Solution:
    S -> AB
    A -> aA |
    B -> aBb |

## Exercise 4

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/CFG/Statements/Statement_04.png)

### Solution:
    S -> AB
    A -> aAb |
    B -> Bb |

## Exercise 5

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/CFG/Statements/Statement_05.png)

### Solution:
    S -> AB
    A -> aAbb |
    B -> Bb |

## Exercise 6

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/CFG/Statements/Statement_06.png)

### Solution:
    S -> aSbb | X
    X -> aX | ab |

## Exercise 7

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/CFG/Statements/Statement_07.png)

### Solution:
    S -> aSbb | X
    X -> aX | ab |

## Exercise 8

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/CFG/Statements/Statement_08.png)

### Solution:
    S -> aaSb | X
    X -> aXb |

## Exercise 9

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/CFG/Statements/Statement_09.png)

### Solution:
    S -> AB
    A -> aA |
    B -> Bb |
    
## Exercise 10

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/CFG/Statements/Statement_10.png)

### Solution:
    S -> aSc | B
    B -> aBb |
 
## Exercise 11

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/CFG/Statements/Statement_11.png)

### Solution:
    S -> BC
    B -> aBb |
    C -> bCc |

## Exercise 12

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/CFG/Statements/Statement_12.png)

### Solution:
    S -> XC | AY | Z |
    X -> aXb |
    Y -> bYc | 
    Z -> aZc | B |
    A -> aA |
    B -> bB | 
    C -> cC |

## Exercise 13

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/CFG/Statements/Statement_13.png)

### Solution 1:
    S -> A | AbX
    A -> aAa | B
    B -> b | bXb
    X -> aX | bX |

### Solution 2:
    S -> TX
    T -> aTa | Xb
    X -> bAX |
    A -> aA |

## Exercise 14

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/CFG/Statements/Statement_14.png)

### Solution 1:
    S -> aXaB | bB
    X -> aXa | Xb |b
    B -> bB | 
    
### Solution 2:
    S -> aSa | Sb | b
 
## Exercise 15

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/CFG/Statements/Statement_15.png)

### Solution:
    S -> XY | bZ
    X -> aXa | XYb |Yb
    Y -> bZ |
    Z -> aZ |bZ |

## Exercise 16

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/CFG/Statements/Statement_16.png)

### Solution:
    S -> aSa | bSb | a | b |

## Exercise 17

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/CFG/Statements/Statement_17.png)

### Solution:
    S -> aAa | bSb | a | b |
    A -> aAa | bBb | a |
    B -> bSb | b |

## Exercise 18

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/CFG/Statements/Statement_18.png)

### Solution:
    S -> aAa | bBb
    A -> aAa | bFb | b
    B -> aFa | bBb | a
    F -> aFa | bFb | a | b |
    
## Exercise 19

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/CFG/Statements/Statement_19.png)

### Solution:
    S -> aAa | bSb
    A -> aAa | bEb | b		    // aaAaa | abCba | aba
    E -> aFa | bSb | a		    // abaFaba | abbSbba | ababa
    F -> aFa | bFb | a | b |

## Exercise 20

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/CFG/Statements/Statement_20.png)

### Solution:
    S -> (S)S |

## Exercise 21

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/CFG/Statements/Statement_21.png)

### Solution:
    S -> (S)S | [S]S |

## Exercise 22

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/CFG/Statements/Statement_22.png)

### Solution:
    S -> (S)S |

## Exercise 23

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/CFG/Statements/Statement_23.png)

### Solution:
    S -> (S)S | [S]S |

## Exercise 24

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/CFG/Statements/Statement_24.png)

### Solution:
    S -> ABaSbAB | ABbSaAB |
    A -> Aab | aAb | abA |
    B -> Bba | bBa | baB |

## Exercise 25

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/CFG/Statements/Statement_25.png)

### Solution:
    S -> ABCaCSbCAB | ABCbCSaCAB | C |
    A -> CAaCbC | CaCAbC | CaCbCA | C | 
    B -> BCbCaC | CbBCaC | CbCaBC | C |
    C -> cC | 

## Exercise 26

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/CFG/Statements/Statement_26.png)

### Solution:
    S -> SaScS | ScSaS | SbScS | ScSbS |

## Exercise 27

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/CFG/Statements/Statement_27.png)

### Solution:
    S -> SbSbSaS | SaSbSbS | SbSaSbS |

## Exercise 28

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/CFG/Statements/Statement_28.png)

### Solution:
    S -> aXS | bYS |
    X -> b | aXX
    Y -> a | bYY

## Exercise 29

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/CFG/Statements/Statement_29.png)

### Solution:
    S -> aXS | bYS | cS |
    X -> b | aXX | cX
    Y -> a | bYY | cY

## Exercise 30

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/CFG/Statements/Statement_30.png)

### Solution:
    S -> aXS | bXS | cZS |
    X -> c | aXX | bXX
    Z -> a | b | cZZ

## Exercise 32

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/CFG/Statements/Statement_32.png)

### Solution:
    S -> BaSbA | BcA
    A -> Aa |
    B -> Bb |

## Exercise 40

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/CFG/Statements/Statement_40.png)

### Solution:
    S -> aSa | bSb | aXb | bXa
    X -> aXa | bXb | aXb | bXa | Y
    Y -> a | b |

## Exercise 43

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/CFG/Statements/Statement_43.png)

### Solution:
    S -> S + S | S - S | S * S | S / S | (S) | Y
    X -> 0X | 1X | 2X | 3X | 4X | 5X | 6X | 7X | 8X | 9X |
    Y -> 0X | 1X | 2X | 3X | 4X | 5X | 6X | 7X | 8X | 9X
