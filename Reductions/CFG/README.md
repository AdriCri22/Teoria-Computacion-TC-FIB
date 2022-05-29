# CFG Reductions

## Exercise 1

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Reductions/CFG/Statements/Statement_01.png)

### Solution:
    input g1,g2
    {
      //G1 = g1;
      //G2 = g2;
      //G3 = ("a" | "b")*;
      // //G3 = "S -> aS | bS | ";
      output g1, g2, g1 | g2;
    }


## Exercise 2

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Reductions/CFG/Statements/Statement_02.png)

### Solution:
    input g1,g2
    {
      output g1, g2 | "c", "c";
    }


## Exercise 3

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Reductions/CFG/Statements/Statement_03.png)

### Solution:
    input g1,g2
    {
      output "a"g1, "a"g2 | "b"g2, "b"g2;
    }


## Exercise 4

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Reductions/CFG/Statements/Statement_04.png)

### Solution:
    input g1,g2
    {
      output g1, g2, "c", "c";
    }


## Exercise 5

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Reductions/CFG/Statements/Statement_05.png)

### Solution:
    input g1,g2
    {
      output "a"g1, "a"g2, "b"g1, "b"g2;
    }


## Exercise 6

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Reductions/CFG/Statements/Statement_06.png)

### Solution:
    input g1,g2
    {
      output g1 | "c", g2 | "c";
    }


## Exercise 7

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Reductions/CFG/Statements/Statement_07.png)

### Solution:
    input g1,g2
    {
      output "a"g1 | "b"g1, "a"g2 | "b"g2;
    }


## Exercise 8

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Reductions/CFG/Statements/Statement_08.png)

### Solution 1:
    input g
    {
      //		   - |w|c = 0 -> {a, b}*
      // {a, b, c}* = |
      //		  - |w|c > 0 -> {a, b, c}* c {a, b, c}*
      G1 = g;
      G2 = ("a" | "b" | "c")* "c" ("a" | "b" | "c")*;
      output G1 | G2;
    }

### Solution 2:
    input g
    {
      output (g "c")* g;
    }


## Exercise 9

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Reductions/CFG/Statements/Statement_09.png)

### Solution:
    input g
    {
      output g , ("a"|"b")* ;
    }


## Exercise 10

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Reductions/CFG/Statements/Statement_10.png)

### Solution:
    input g
    {
      output ("a"|"b")*, g;
    }


## Exercise 11

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Reductions/CFG/Statements/Statement_11.png)

### Solution:
    input g1,g2
    {
      output g1, g2;
    }


## Exercise 12

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Reductions/CFG/Statements/Statement_12.png)

### Solution:
    input g
    {
      output g, g;
    }


## Exercise 13

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Reductions/CFG/Statements/Statement_13.png)

### Solution:
    input g
    {
      output g , ("a"|"b")* ;
    }


## Exercise 14

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Reductions/CFG/Statements/Statement_14.png)

### Solution:
    input g
    {
      output g"a" ;
    }


## Exercise 15

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Reductions/CFG/Statements/Statement_15.png)

### Solution:
    input g
    {
      output g"aa";
    }


## Exercise 16

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Reductions/CFG/Statements/Statement_16.png)

### Solution:
    input g
    {
      output "a"g | "b"g;
    }


## Exercise 17

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Reductions/CFG/Statements/Statement_17.png)

### Solution 1:
    input g
    {
      // En vez de quitar lambda (g - ""), podemos construir

      //	      |-lambda
      //	      |	b {a, b}*
      // {a, b}* -|
      //	      |	aa {a, b}*
      //	      |-ba {a, b}*
      output ("aa" g) | "b" | "" | ("b" g) | ("ab" g);
    }

### Solution 2:
    input g
    {
      if ("a" belongsto g)
        output g - "a";
      else
        output "";
    }


## Exercise 18

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Reductions/CFG/Statements/Statement_18.png)

### Solution:
    input g
    {
      output "ba"g | "a" | "b" | "aa"g | "bb"g | "" | "aba"g | "abb"g;
    }


## Exercise 19

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Reductions/CFG/Statements/Statement_19.png)

### Solution:
    input g
    {
      output "a"g | "b"g"a"g;
    }


## Exercise 20

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Reductions/CFG/Statements/Statement_20.png)

### Solution:
    input g
    {
      output g"aa" | (("a"|"b")* "aa" ("a"|"b")*) - ("a"|"b")*"aa" ;
    }
