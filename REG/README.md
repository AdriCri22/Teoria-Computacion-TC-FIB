# Regular Descriptions

## Exercise 1

### Statement:


### Solution:
    main
    {
      a = "a";
      b = "b";
      ab = a | b;
      output ab* (a a a | b b b | a b a | b a b) ab*;
    }
