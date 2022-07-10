# Solved Exams

## Exam on CFGs, March 27th, 2015

### Exercise 1

#### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_March_2015/Statement_1.png)

#### Solution:
    S -> bSb | aSa | b |

### Exercise 2

#### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_March_2015/Statement_2.png)

#### Solution:
    S -> bSY | aAY
    A -> bAY | aBY
    B -> bBY | c
    Y -> a | b

### Exercise 3

#### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_March_2015/Statement_3.png)

#### Solution:
    S -> XY | aXbYc
    X -> aaXb |
    Y -> bYcc |

## Exam on CFGs, March 29th, 2016

### Exercise 1

#### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_March_2016/Statement_1.png)

#### Solution:
    S -> aXb | bXa | aSa | bSb
    X -> aXa | aXb | bXa | bXb |

### Exercise 2

#### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_March_2016/Statement_2.png)

#### Solution:
    S -> BaXbA | BcA
    X -> BaSbA
    B -> bB |
    A -> aA | 

## Exam on CFGs, October 22nd, 2014

### Exercise 1

#### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_October_2014/Statement_1.png)

#### Solution:
    S -> aXa | bSb
    X -> bXb | a

### Exercise 2

#### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_October_2014/Statement_2.png)

#### Solution:
    S -> aP | Ic

    P -> aPc | X
    X -> aX | A
    A -> bB | 
    B -> bA

    I -> aIc | Y
    Y -> Yc | C
    C -> bD
    D -> bC |

### Exercise 5

#### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_October_2014/Statement_5.png)

#### Solution:
    S -> aZ | bYYZ
    Z -> aXZ | bYZ |
    X -> b | aXX
    Y -> a | bYY

## Exam on DFAs and CFGs, April 21st, 2021

### Exercise 1

#### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_April_2021/Statement_1.png)

#### Image solution:
![Image_solution](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_April_2021/Image_sol_1.png)

#### Text solution:
      0 1
    0 0 2 +
    1 3 0
    2 1 3
    3 4 1
    4 2 4

### Exercise 2

#### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_April_2021/Statement_2.png)

#### Image solution:
![Image_solution](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_April_2021/Image_sol_2.png)

#### Text solution:
          0     1    
    0     0     1    
    1     1     Impar +
    Impar Par   Impar +
    Par   Par   Impar

### Exercise 3

#### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_April_2021/Statement_3.png)

#### Image solution:
![Image_solution](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_April_2021/Image_sol_3.png)

#### Text solution:
         a    b   
    ini  a    b    +
    a    aa   ab  
    aa   no   aab 
    aab  aa   aabb
    aabb a    no   +
    ab   a    abb  +
    abb  ini  no  
    b    ini  bb  
    bb   b    no  
    no   no   no  

### Exercise 4

#### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_April_2021/Statement_4.png)

#### Solution:
    S -> aSa | bXb | a |
    X -> aXa | bYb | b
    Y -> aYa | bSb


## Exam on DFAs and CFGs, November 8th, 2019

### Exercise 1

#### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_November_2019/Statement_1.png)

#### Image solution:
![Image_solution](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_November_2019/Image_sol_1.png)

#### Text solution:
        a   b  
    ini a   ini
    a   aa  ini
    a2  aa  aab +
    aa  no  aab +
    aab a2  aab +
    no  no  no 
    
### Exercise 2

#### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_November_2019/Statement_2.png)

#### Image solution:
![Image_solution](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_November_2019/Image_sol_2.png)

#### Text solution:
          a     b    
    equal a     b     +
    2     2     2    
    a     2     equal +
    b     equal 2     +



### Exercise 3

#### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_November_2019/Statement_3.png)

#### Image solution:
![Image_solution](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_November_2019/Image_sol_3.png)

#### Text solution:
        0   1   c  
    0   0   1   0y0
    0y0 0y0 1y0 no  +
    0y1 0y1 1y1 no 
    0y2 0y2 1y2 no 
    1   2   0   0y1
    1y0 2y0 0y0 no 
    1y1 2y1 0y1 no 
    1y2 2y2 0y2 no  +
    2   1   2   0y2
    2y0 1y0 2y0 no 
    2y1 1y1 2y1 no  +
    2y2 1y2 2y2 no 
    no  no  no  no 

### Exercise 4

#### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_November_2019/Statement_4.png)

#### Solution:
    S -> BaSbA | BaBcA
    A -> aA |
    B -> bB |

### Exercise 5

#### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_November_2019/Statement_5.png)

#### Solution:
    S -> XY
    X -> bBX | a
    B -> a | bBB
    Y -> aY | bY |

## Exam on DFAs, February 29th, 2016

### Exercise 1

#### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_February_2016/Statement_1.png)

#### Image solution:
![Image_solution](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_February_2016/Image_sol_1.png)

#### Text solution:
        a   b  
    Ini a   Ini
    a   a   ab 
    ab  ba  ab 
    ba  a   ab  +

### Exercise 2

#### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_February_2016/Statement_2.png)

#### Image solution:
![Image_solution](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_February_2016/Image_sol_2.png)

#### Text solution:
          0     1     c    
    ini   ini   1     sum0 
    1     ini   1     sum1 
    2     sum1  2     sum0  +
    plus1 sum0  plus1 sum1 
    sum0  sum0  plus1 sum0  +
    sum1  sum1  2     sum1 

### Exercise 3

#### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_February_2016/Statement_3.png)

#### Image solution:
![Image_solution](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_February_2016/Image_sol_3.png)

#### Text solution:
        a   b   c  
    ini a   b   c   +
    a   fin b   ac  +
    ac  fin cb  fin +
    b   ba  fin c   +
    ba  fin fin ac  +
    c   a   cb  fin +
    cb  ba  fin fin +
    fin fin fin fin

### Exercise 4

#### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_February_2016/Statement_4.png)

#### Image solution:
![Image_solution](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_February_2016/Image_sol_4.png)

#### Text solution:
        0   1  
    ini 0   1  
    0   00  2  
    00  000 2  
    000 000 16 
    1   2   2  
    16  16  16  +
    2   16  16 

### Exercise 5

#### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_February_2016/Statement_5.png)

#### Solution:
[Solution](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_February_2016/examen-DFAs-29.02.2016-ex5_1.pdf)

#### Text solution:

## Exam on DFAs, October 1st, 2014

### Exercise 1

#### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_DFA_October_2014/Statement_1.png)

#### Image solution:
![Image_solution](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_DFA_October_2014/Image_sol_1.png)

#### Text solution:
        a   b  
    ini a   no 
    a   aa  a  
    aa  aa  a   +
    no  no  no 

### Exercise 2

#### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_DFA_October_2014/Statement_2.png)

#### Image solution:
![Image_solution](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_DFA_October_2014/Image_sol_2.png)

#### Text solution:
      0 1
    0 0 1
    1 2 3
    2 1 2
    3 3 3 +

### Exercise 3

#### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_DFA_October_2014/Statement_3.png)

#### Image solution:
![Image_solution](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_DFA_October_2014/Image_sol_3.png)

#### Text solution:
        a   b  
    ini a   b  
    a   aa  ab 
    a2  a2  fin
    a3  fin aa 
    aa  a3  aa 
    ab  a2  ab 
    b   ba  bb 
    b2  fin b2 
    b3  bb  fin
    ba  ba  b2 
    bb  bb  b3 
    fin fin fin +

### Exercise 4

#### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_DFA_October_2014/Statement_4.png)

#### Image solution:
![Image_solution](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_DFA_October_2014/Image_sol_4.png)

#### Text solution:
        a   b  
    ini a   b   +
    a   aa  ab  +
    aa  si  si  +
    ab  si  bb  +
    b   ba  bb  +
    ba  si  ab  +
    bb  ba  si  +
    si  si  si 

## Exam on DFAs, October 1st, 2015

### Exercise 1

#### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_October_2015/Statement_1.png)

#### Image solution:
![Image_solution](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_October_2015/Image_sol_1.png)

#### Text solution:
        a   b  
    Ini a   b  
    a   a   ab 
    ab  b   ab  +
    b   b   b  

### Exercise 2

#### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_October_2015/Statement_2.png)

#### Image solution:
![Image_solution](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_October_2015/Image_sol_2.png)

#### Text solution:
       a  b 
    0A 1B 2C +
    1A 1B 3C +
    1B 1A 3D +
    2A 3B 2C +
    2C 3D 2A +
    3A 3B 3C
    3B 3A 3D +
    3C 3D 3A +
    3D 3C 3B +

### Exercise 3

#### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_October_2015/Statement_3.png)

#### Image solution:
![Image_solution](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_October_2015/Image_sol_3.png)

#### Text solution:
        0   1   c  
    00  00  01  002
    002 002 012 c  
    003 003 013 c   +
    004 004 014 c   +
    01  10  00  003
    012 102 002 c   +
    013 103 003 c  
    014 104 004 c   +
    10  01  10  004
    102 012 102 c   +
    103 013 103 c   +
    104 014 104 c  
    c   c   c   c  


## Exam on REG+CFG+PDA, April 24th, 2015
### Exercise 2

#### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_April_2015/Statement_2.png)

#### Image solution:
![Image_solution](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_April_2015/Image_sol_2.png)

#### Text solution:
    Z 0 3
    0 -> Z(|ZP      -> 1
    1 -> P)|        -> 0
    1 -> P(|PP      -> 2
    2 -> P(|PP, P)| -> 2
    2 -> Z |Z       -> 3
    3 -> Z(|ZP      -> 1
    
### Exercise 5

#### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_April_2015/Statement_5.png)

#### Image solution:
![Image_solution](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_April_2015/Image_sol_5.png)

#### Text solution:
    Z 0 1
    0 -> Z(|ZX, X)|, X(|YP, P(|PP, P)|, Y(|YP -> 0
    0 -> Y)|                                  -> 1
    1 -> Z(|ZX                                -> 0
    
## Exam on REG+CFG+PDA, April 25th, 2016
### Exercise 2

#### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_April_2016/Statement_2.png)

#### Solution:
    main
    {
      0 = "0";
      1 = "1";
      01 = (0 | 1);
      multiple5 = "		0	1
            0	0	1 +
            1	2	3
            2	4	0
            3	1	2
            4	3	4";

      output (01 01 01 01)* (01 01) | multiple5;
    }
    
### Exercise 5

#### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_April_2016/Statement_5.png)

#### Solution:
    main
    {

      multiple5 =
        " 0 1
        0 0 1 +
        1 2 3
        2 4 0
        3 1 2
        4 3 4
        ";

      cicle = 
        " x 
        0 1 
        1 2
        2 3 +
        3 0
        ";
        cicler = substitution(cicle, "x"-> ("0"|"1"));
      output multiple5 | cicler;
    }

## Exam on REG+CFG+PDA, November 19th, 2014
### Exercise 2

#### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_November_2014/Statement_2.png)

#### Solution:
    main
    {
      mult3 = "	a	b
        0	1	1 +
        1	2	2 +
        2	no	0 +
        no	no	no";
      mult5 = "	a	b
        0	1	1 +
        1	2	2 +
        2	3	3 +
        3	4	4 +
        4	0	no +
        no	no	no";

      output mult3 & mult5;
    }

### Exercise 3

#### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_November_2014/Statement_3.png)

#### Image solution:
![Image_solution](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_November_2014/Image_sol_3.png)

#### Text solution:
    Z 0 2 3
    0 -> Za|ZX, Zb|ZY                                           -> 1
    0 -> Zc|Z                                                   -> 4
    1 -> Aa|AA, Bb|BB, Ab|AB, Ba|BA, Xa|XA, Xb|XB, Yb|YB, Ya|YA -> 1
    1 -> Ac|A, Bc|B, Xc|X, Yc|Y                                 -> 2
    2 -> Aa|, Bb|                                               -> 2
    2 -> Ba|, Ab|, Xb|, Ya|                                     -> 3
    2 -> Xa|, Yb|                                               -> p
    3 -> Za|Z, Zb|Z, Aa|, Bb|, Ba|, Ab|, Xb|, Yb|, Xa|, Ya|     -> 3
    4 -> Za|Z, Zb|Z                                             -> 3
    p -> Za|Z, Zb|Z                                             -> 3

### Exercise 5

#### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_November_2014/Statement_5.png)

#### Solution:
    main
    {
      DFA = "	(	)
        0	1	no +
        1	2	0
        2	3	1
        3	4	2
        4	5	3
        5	6	4
        6	7	5
        7	8	6
        8	9	7
        9	10	8
        10	no	9
        no	no	no";
      p = "(" | ")";
      maxP = p p p p p p p p p p p p p p p p p p p p;
      output DFA & maxP;
    }

## Exam on REG+PDA+Reductions, June 4th, 2021
### Exercise 1

#### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_June_2021/Statement_1.png)

#### Solution:
    main
    {
      a = "a";
      b = "b";
      ab = (a | b);
      abba = ab* a b b a ab*;
      abba2 = (ab* a b b a b b a ab*) | (ab* a b b a ab* a b b a ab*);
      aaa = ab* a a a ab*;
      bbb = (ab* b b b ab* b b b ab*) | (ab* b b b b ab*);
      output (abba - abba2 - aaa) | ((abba - abba2) & bbb);
    }
    
### Exercise 2

#### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_June_2021/Statement_2.png)

#### Solution:
    main
    {
      multiple3 = "		0	1
            0	0	1 +
            1	2	0
            2	1	2";
      multiple4 = "		0	1
            0	0	1 +
            1	2	3
            2	0	1
            3	2	3";
      multiple8 = "		0	1
            0	0	1 +
            1	2	3
            2	4	5
            3	6	7
            4	0	1
            5	2	3
            6	4	5
            7	6	7";

      output multiple3 & multiple4 & reverse(multiple8 & multiple3);
    }

### Exercise 3

#### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_June_2021/Statement_3.png)

#### Image solution:
![Image_solution](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_June_2021/Image_sol_3.png)

#### Text solution:
    Z 0 0 3
    0 -> Za|ZA, Zb|ZB        -> 1
    1 -> Ab|AB, Bb|BB, Ba|BA -> 1
    1 -> Bb|                 -> 2
    2 -> Aa|, Bb|            -> 2
    2 -> Z |Z                -> 3
    
### Exercise 4

#### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_June_2021/Statement_4.png)

#### Solution:
    input y
    {
      if (not mxxstopsininputsteps and y % 2 == 0)
        output y;
    }

## Exam on Reductions, December 17th, 2014
### Exercise 1

#### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_December_2014/Statement_1.png)

#### Solution:
    input y
    {
      if (mxxstopsininputsteps)
        output y;
      else {
        if (y % 5 == 0 and y != 10) 
          accept;
        infiniteloop;
      }
    }

### Exercise 2

#### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_December_2014/Statement_2.png)

#### Solution:
    input g
    {
      output g-"a"-"b", ("a"|"b")*-"b", g;
    }

### Exercise 4

#### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_December_2014/Statement_4.png)

#### Solution:
    input y
    {
      if (not mxxstopsininputsteps)
       output 2*y + 1;
    }

    input y
    {
      if (not mxxstopsininputsteps)
        output 2*y;
    }


## Exam on Reductions, December 17th, 2015
### Exercise 1

#### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_December_2015/Statement_1.png)

#### Solution:
    input y
    {
      runmxx;
      if (y % 3 == 0)
        output y;
      else if (y % 3 == 1)
        output y * 2;
      else if (y % 3 == 2)
        output y;
    }

### Exercise 3

#### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_December_2015/Statement_3.png)

#### Solution:
    input y
    {
      if (mxxstopsininputsteps)
        infiniteloop;
      else {
        if (y < 3)
          output y;
      }
    }

    input y
    {
      if (mxxstopsininputsteps)
        output y;
      else {
        if (y < 4) {
          if (y % 2 == 0)
        output 0;
          else
        output 1;
        }
      }
    }

    input y
    {
      if (mxxstopsininputsteps)
        output y;
      else {
        if (y < 5)
          output 0;
      }
    }

### Exercise 4

#### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_December_2015/Statement_4.png)

#### Solution:
    input g
    {
      output "a" ("a" | "b")* "b", "a" g "b";
    }

## Exam on Reductions, June 5th, 2015
### Exercise 1

#### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_June_2015/Statement_1.png)

#### Solution:
    input y
    {
      runmxx;
      if (y % 3 == 0)
        output y + 1;
      else if (y % 3 == 1)
        output y;
      else
        output y;
    }
    
### Exercise 2

#### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_June_2015/Statement_2.png)

#### Solution:
    input g1,g2
    {
      output substitution(g1, "a" -> "aba", "b" -> "bab") "aab",
            substitution(g2, "a" -> "aba", "b" ->"bab") "aab";
    }

### Exercise 4

#### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Exams/Exam_June_2015/Statement_4.png)

#### Solution:
    input y
    {
      if (mxxstopsininputsteps)
        output y;
      else {
        if (y % 2 == 0)
          output 2*y;
        else
          output 2*y+1;
      }
    }

    input y
    {
      if (mxxstopsininputsteps)
        infiniteloop;
      else {
        if (y % 2 == 0)
          output 2*y+1;
        else
          output 2*y;
      }
    }








