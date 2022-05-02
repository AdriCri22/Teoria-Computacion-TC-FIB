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
