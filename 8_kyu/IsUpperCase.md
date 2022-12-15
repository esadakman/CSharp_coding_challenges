## Is the string uppercase?

- Create a method to see whether the string is ALL CAPS.
  Examples:

```CSharp
  "c" -> False
  "C" -> True
  "hello I AM DONALD" -> False
  "HELLO I AM DONALD" -> True
  "ACSKLDFJSgSKLDFJSKLDFJ" -> False
  "ACSKLDFJSGSKLDFJSKLDFJ" -> True
```
-In this Kata, a string is said to be in ALL CAPS whenever it does not contain any lowercase letter so any string containing no letters at all is trivially considered to be in ALL CAPS.

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
