## Summation

- Write a program that finds the summation of every number from 1 to num. The number will always be a positive integer greater than 0.
- Given a random non-negative number, you have to return the digits of this number within an array in reverse order.

Example: 

```CSharp
  2 -> 3 (1 + 2)
  8 -> 36 (1 + 2 + 3 + 4 + 5 + 6 + 7 + 8)
```

```CSharp
using System;

public static class Kata 
{
    public static int summation(int num)
    {
      int sum = 0;
      for (int i = 0; i <= num; i++)
      {
        sum += i;
      }
      return sum;
    }
}
```
