# K Reductions

## Exercise 1

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Reductions/K/Statements/Statement_01.png)

### Solution:
    input y
    {
      runmxx;
      // accept;
    }

## Exercise 2

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Reductions/K/Statements/Statement_02.png)

### Solution:
    input y
    {
      if (mxxstopsininputsteps)
        infiniteloop;
      accept;
    }


## Exercise 3

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Reductions/K/Statements/Statement_03.png)

### Solution:
    input y
    {
      runmxx;
      // accept;
    }


## Exercise 4

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Reductions/K/Statements/Statement_04.png)

### Solution:
    input y
    {
      runmxx;
      // accept;
    }


## Exercise 5

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Reductions/K/Statements/Statement_05.png)

### Solution 1:
    input y
    {
      if (mxxstopsininputsteps)
        infiniteloop;
      else
        output y;
    }

## Solution 2:
    input y
    {
      if (not mxxstopsininputsteps)
        output y;
    }



## Exercise 6

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Reductions/K/Statements/Statement_06.png)

### Solution 1:
    input y
    {
      if (mxxstopsininputsteps)
        output 0;
      else
        output y;
    }

### Solution 2:
    input y
    {
      if (mxxstopsininputsteps)
        infiniteloop;
      else
        output y;
    }

### Solution 3:
    input y
    {
      if (not mxxstopsininputsteps)
        output y;
    }


## Exercise 7

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Reductions/K/Statements/Statement_07.png)

### Solution:
    input y
    {
      if (not mxxstopsininputsteps)
        output 0;
    }


## Exercise 8

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Reductions/K/Statements/Statement_08.png)

### Solution:
    input y
    {
      if (y == 2)
        runmxx;
      if (y == 1 and not mxxstopsininputsteps)
        accept; 
    }


## Exercise 9

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Reductions/K/Statements/Statement_09.png)

### Solution:
    input y
    {
      runmxx;
      accept;
    }


## Exercise 10

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Reductions/K/Statements/Statement_10.png)

### Solution:
    input y
    {
      if (y < 2)
        accept;
      else
        runmxx;
      output 1;
    }


## Exercise 11

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Reductions/K/Statements/Statement_11.png)

### Solution:
    input y
    {
      runmxx;
      output y;
    }


## Exercise 12

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Reductions/K/Statements/Statement_12.png)

### Solution:
    input y
    {
      if (y >= 2)
        runmxx;
      output y;
    }


## Exercise 13

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Reductions/K/Statements/Statement_13.png)

### Solution:
    input y
    {
      if (not mxxstopsininputsteps and y % 2 == 0)
        output 2*y + 1;
    }


## Exercise 14

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Reductions/K/Statements/Statement_14.png)

### Solution:
    input y
    {
      runmxx;
      // accept;
    }

    input y
    {
      runmxx;
      // accept;
    }


## Exercise 15

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Reductions/K/Statements/Statement_15.png)

### Solution:
    input y
    {
      if (mxxstopsininputsteps)
        accept;
    }

    input y
    {
      runmxx;
    }


## Exercise 16

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Reductions/K/Statements/Statement_16.png)

### Solution:
    input y
    {
      if (y % 2 == 0)
        accept;
      else
        runmxx;
    }

    input y
    {
      if (y % 2 == 1)
        accept;
      else
        runmxx;
    }


## Exercise 17

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Reductions/K/Statements/Statement_17.png)

### Solution:
    input y
    {
      runmxx;
      output y;
    }

    input y
    {
      runmxx;
      output y;
    }


## Exercise 18

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Reductions/K/Statements/Statement_18.png)

### Solution:
    input y
    {
      if (y < 2 and not mxxstopsininputsteps)
        output y;
      else
        runmxx;
      output y;
    }

    input y
    {
      if (y < 2 and not mxxstopsininputsteps)
        output y;
      else
        runmxx;
      output y;
    }


## Exercise 19

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Reductions/K/Statements/Statement_19.png)

### Solution 1:
    input y
    {
      if (y == 1 and not mxxstopsininputsteps)
        output 1;
      else
        runmxx;
      output y;
    }

    input y
    {
      if (y == 1 and not mxxstopsininputsteps)
        output 1;
      else
        runmxx;
      output y;
    }

### Solution 2:
    input y
    {
      if (mxxstopsininputsteps)
        output y;
      else
        if (y == 1)
          output 1;
    }

    input y
    {
      if (mxxstopsininputsteps)
        infiniteloop;
      else
        if (y == 1)
          output 1;
    }

## Exercise 20

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Reductions/K/Statements/Statement_20.png)

### Solution:
    input y
    {
      if (y == 1 and not mxxstopsininputsteps)
        output 1;
      else
        runmxx;
      output y;
    }

    input y
    {
      if (y == 2 and not mxxstopsininputsteps)
        output y;
      else
        runmxx;
      output y;
    }


## Exercise 21

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Reductions/K/Statements/Statement_21.png)

### Solution:
    input y
    {
      if (y == 1 and not mxxstopsininputsteps)
        output 0;
      else
        runmxx;
      output y;
    }

    input y
    {
      if (y == 2 and not mxxstopsininputsteps)
        output 2;
      else
        runmxx;
      output y;
    }


## Exercise 22

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Reductions/K/Statements/Statement_22.png)

### Solution:
    input y
    {
      if (y == 1 and not mxxstopsininputsteps)
        output 2;
      else
        runmxx;
      output y;
    }

    input y
    {
      if (y == 3 and not mxxstopsininputsteps)
        output 4;
      else
        runmxx;
      output y;
    }


## Exercise 23

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Reductions/K/Statements/Statement_23.png)

### Solution 1:
    input y
    {
      if (y % 2 == 0 and not mxxstopsininputsteps)
        output y;
      else
        output y;
    }

    input y
    {
      if (not mxxstopsininputsteps)
        output y;
    }

### Solution 2:
    input y
    {
      if (mxxstopsininputsteps)
        output y;
      else
        if (y < 10)
          output y;
    }

    input y
    {
      if (mxxstopsininputsteps)
        infiniteloop;
      else
        output y;
    }


## Exercise 24

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Reductions/K/Statements/Statement_24.png)

### Solution:
    input y
    {
      if (not mxxstopsininputsteps) {
        if (y % 2 == 0)
          output y;
      }
      else
        output y;
    }

    input y
    {
      if (not mxxstopsininputsteps)
        output y;
    }


## Exercise 25

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Reductions/K/Statements/Statement_25.png)

### Solution 1:
    input y
    {
      if (not mxxstopsininputsteps) {
        if (y % 4 == 0)
          output y / 2;
      } else
        output 2 * y;
    }

    input y
    {
      if (not mxxstopsininputsteps) {
        if (y % 2 == 0 and y != 2)
          output y;
      } else
        output y;
    }

### Solution 2:
    input y
    {
      if (mxxstopsininputsteps)
        output y;
      else
        if (y % 4 == 0)
          output y / 2;
    }

    input y
    {
      if (mxxstopsininputsteps)
        infiniteloop;
      else
        if (y % 2 == 0 and y != 2)
          output y;
    }


## Exercise 26

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Reductions/K/Statements/Statement_26.png)

### Solution 1:
    input y
    {
      if (not mxxstopsininputsteps) {
        if (y % 2 == 0)
          output y;
      }
    }

    input y
    {
      if (not mxxstopsininputsteps) {
        if (y % 2 == 1)
          output y;
      }
    }

### Solution 2:
    input y
    {
      if (mxxstopsininputsteps)
        output y;
      else
        if (y % 2 == 0)
          output y;
    }

    input y
    {
      if (mxxstopsininputsteps)
        infiniteloop;
      else
        if (y % 2 == 1)
          output y;
    }

## Exercise 27

### Statement:
![Statement](https://github.com/AdriCri22/Teoria-Computacion-TC-FIB/blob/main/Reductions/K/Statements/Statement_27.png)

### Solution:
    input y
    {
      if (not mxxstopsininputsteps) {
        if (y % 2 == 0)
          output y;
      }
    }

    input y
    {
      if (not mxxstopsininputsteps) {
        if (y % 2 == 1 and y != 1)
          output y;
      }
    }
