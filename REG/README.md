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

## Exercise 11

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/REG/Statements/Statement_11.png)

### Solution:
    main
    {
      a = "a";
      b = "b";
      ab = a | b;
      L = ab* a ab ab;
      aa = a a;
      aba = a b a;
      bab = b a b;
      output substitution(L, "a" -> aa*, "b" -> (a | aba | bab));
    }

## Exercise 12

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/REG/Statements/Statement_12.png)
![NFA](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/REG/Statements/Statement_12_NFA.png)

### Solution:
    main
    {
      dfa = 
        "	a	b	c	d
        0	1	4	3	p
        1	4	2	p	3
        2	p	5	p	p
        3	2	p	p	p
        4	0	0	5	2 +
        5	4	p	p	p
        p	p	p	p	p";

      output substitution(dfa, "c" -> "a", "d" -> "b");
    }

### Detailed Solution:
   [Detailed_Solution](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/REG/Detailed_solutions/REG%2012.pdf) 


## Exercise 13

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/REG/Statements/Statement_13.png)
![NFA](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/REG/Statements/Statement_12_NFA.png)

### Solution:
    main
    {
      dfa = 
        "	a	b	c	d
        52	4	5	p	p
        0	1	4	3	p
        1	4	2	p	3
        2	p	5	p	p
        3	2	p	p	p
        4	0	0	5	2 +
        5	4	p	p	p
        p	p	p	p	p";

      output substitution(dfa, "c" -> "a", "d" -> "b");
    }

### Detailed Solution:
   [Detailed_Solution](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/REG/Detailed_solutions/REG%2013.pdf) 

## Exercise 14

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/REG/Statements/Statement_14.png)
![NFA](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/REG/Statements/Statement_14_D.png)

### Solution:
    main
    {
      D = 
        "	2	4	6
        0	p	1	p
        1	p	2	3
        2	4	0	p
        3	0	p	p
        4	p	3	p +
        p	p	p	p";

      output substitution(D, "2" -> "aa", "4" -> "aaaa", "6" -> "aaaaaa");
    }

## Exercise 15

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/REG/Statements/Statement_15.png)
![NFA](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/REG/Statements/Statement_15_D.png)

### Solution:
    main
    {
      D = 
        "	3	4	5	7	9
        0	p	2	p	1	p
        1	p	p	p	1	3
        2	5	4	p	p	p
        3	p	0	p	p	p
        4	3	p	2	p	p
        5	p	p	p	p	4 +
        p	p	p	p	p	p";

      output substitution(D, "3" -> "aaa", "4" -> "aaaa", "5" -> "aaaaa", "7" -> "aaaaaaa", "9" -> "aaaaaaaaa");
    }

## Exercise 16

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/REG/Statements/Statement_16.png)
![NFA](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/REG/Statements/Statement_16_L.png)

### Solution:
    main
    {
      L = 
      "	a	b	c	d	e
      A0	B1	A2	p	p	p	+
      B1	p	p 	A2	B0	p
      A2	p	p	p	B1	A0	+
      B0	A1	B2	p	p	p
      A1	p	p	B2	A0	p	+
      B2	p	p	p	A1	B0
      p	p	p	p	p	p";

      output substitution(L, "a" -> "aba", "b" -> "bb", "c" -> "b", "d" -> "a", "e" -> "bbba");
    }

## Exercise 17

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/REG/Statements/Statement_17.png)
![NFA](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/REG/Statements/Statement_17_L.png)

### Solution:

## Exercise 18

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/REG/Statements/Statement_18.png)

### Solution:
    main
    {
      00 = "00";
      01 = "01";
      10 = "10";
      11 = "11";

      output (00 | 11)* 10 (00 | 01 | 10 | 11)*;
    }

## Exercise 19

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/REG/Statements/Statement_19.png)

### Solution:
    main
    {
      00 = "00";
      01 = "01";
      10 = "10";
      11 = "11";

      output (00 | 11)* 01 (00 | 01 | 10 | 11)*;
    }


## Exercise 20

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/REG/Statements/Statement_20.png)

### Solution:
    main
    {
      0 = "0";
      1 = "1";
      00 = 0 0;
      01 = 0 1;
      10 = 1 0;
      11 = 1 1;
      000 = 0 0 0;
      001 = 0 0 1;
      010 = 0 1 0;
      011 = 0 1 1;
      100 = 1 0 0;
      101 = 1 0 1;
      110 = 1 1 0;
      111 = 1 1 1;
      all = 000 | 001 | 010 | 011 | 100 | 101 | 110 | 111;

      output (000 | 111)* 110 ((00 | 11) (0 | 1))* (10 (0 | 1)) all* |
            (000 | 111)* 100 ((0 | 1) (00 | 11))* ((0 | 1) 10) all*;
    }

## Exercise 21

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/REG/Statements/Statement_21.png)

### Solution:
    main
    {
      0 = "0";
      1 = "1";
      00 = 0 0;
      01 = 0 1;
      10 = 1 0;
      11 = 1 1;
      000 = 0 0 0;
      001 = 0 0 1;
      010 = 0 1 0;
      011 = 0 1 1;
      100 = 1 0 0;
      101 = 1 0 1;
      110 = 1 1 0;
      111 = 1 1 1;
      all = 000 | 001 | 010 | 011 | 100 | 101 | 110 | 111;

      output (000 | 111)* 100 ((0 | 1) (00 | 11))* ((0 | 1) 01) all* |
        (000 | 111)* 001 ((00 | 11) (0 | 1))* (10 (0 | 1)) all* |
        (000 | 111)* 101 (all)*;
    }

## Exercise 22

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/REG/Statements/Statement_22.png)

### Solution:
    main
    {
      00 = "00";
      01 = "01";
      10 = "10";
      11 = "11";

      output (00 | 11)* 10 ((00 | 01 | 10 | 11)* - 01*);
    }

## Exercise 23

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/REG/Statements/Statement_23.png)

### Solution:
    main
    {
      000 = "000";
      001 = "001";
      010 = "010";
      011 = "011";
      100 = "100";
      101 = "101";
      110 = "110";
      111 = "111";

      output (001 (100 | 010 | 111)* 110 | (011 | 101 | 000))*;
    }


























