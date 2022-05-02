# Regular Descriptions

## Exercise 1

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/REG/Statements/Statement_01.png)

### Solution:
    main
    {
      a = "a";
      b = "b";
      ab = a | b;
      output ab* (a a a | b b b | a b a | b a b) ab*;
    }

## Exercise 2

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/REG/Statements/Statement_02.png)

### Solution:
    main
    {
      a = "a";
      b = "b";
      ab = a | b;
      aaa = ab* a a a ab*;
      bbb = ab* b b b ab*;
      aba = ab* a b a ab*;
      bab = ab* b a b ab*;
      output aaa & bbb & aba & bab;
    }

## Exercise 3

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/REG/Statements/Statement_03.png)

### Solution:
    main
    {
      a = "a";
      b = "b";
      ab = a | b;

      one = ab* a a a ab*;
      two = ab* a a a ab* a a a ab* | ab* a a a a ab*;

      difA = one - two;
      difB = substitution(difA, "a" -> "b", "b" -> "a");

      output difA & difB;
    }

## Exercise 4

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/REG/Statements/Statement_04.png)

### Solution:
    main
    {
      a = "a";
      b = "b";
      ab = a | b;
      aba = "aba";
      bab = "bab";

      one = ab* aba ab*;
      two = ab* aba ab* aba ab* | ab* aba b a ab*;

      dif = one - two;
      diff = substitution(dif, "a" -> "b", "b" -> "a");

      output dif & diff;
    }

## Exercise 5

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/REG/Statements/Statement_05.png)

### Solution:
    main
    {
      a = "a";
      b = "b";
      ab = a | b;
      bbb = b b b;
      output ab* bbb ab* & ab* a ab ab ab ab ab;
    }

## Exercise 6

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/REG/Statements/Statement_06.png)

### Solution:
    main
    {
      multiple_3 = 
        "  	0 1
          1 1 2 +
          2 3 1
          3 2 3";
      multiple_4 = 
        "  	0 1
          0 0 1 +
          1 2 1
          2 0 1";
      output multiple_3 & multiple_4;
    }

## Exercise 7

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/REG/Statements/Statement_07.png)

### Solution:
    main
    {
      multiple_4 = 
        "  	0 1
          0 0 1 +
          1 2 1
          2 0 1";
      multiple_5 = 
        "  	0 1
          0 0 1 +
          1 2 3
          2 4 0
          3 1 2
          4 3 4";

      output multiple_4 & multiple_5;
    }

## Exercise 8

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/REG/Statements/Statement_08.png)

### Solution:
    main
    {
       multiple_3 = 
         "	0 1
          1 1 2 +
          2 3 1
          3 2 3";
      multiple_4 = 
        "  	0 1
          0 0 1 +
          1 2 1
          2 0 1";
      multiple_5 = 
        "  	0 1
          0 0 1 +
          1 2 3
          2 4 0
          3 1 2
          4 3 4";

      output multiple_3 & multiple_4 & multiple_5;
    }

## Exercise 9

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/REG/Statements/Statement_09.png)

### Solution:
    main
    {
      a = "a";
      b = "b";
      ab = a | b;
      aba = a b a;
      bab = b a b;
      L = ab* a ab ab;
      output substitution(L, "a" -> aba, "b" -> bab);
    }

## Exercise 10

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/REG/Statements/Statement_10.png)

### Solution:
    main
    {
      a = "a";
      b = "b";
      c = "c";
      abc = a | b | c;
      aba = a b a;
      aa = a a;
      L = (abc* a abc) | (abc* c abc);
      output substitution(L, "a" -> aba, "b" -> aa, "c" -> b);
    }



































