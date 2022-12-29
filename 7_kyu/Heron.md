## Heron's formula

- Write function heron which calculates the area of a triangle with sides a, b, and c (x, y, z in COBOL).

Heron's formula: 

$\sqrt{s∗(s−a)∗(s−b)∗(s−c)}$

where

s = $\frac{a+b+c}{2}$

- Output should have 2 digits precision.
 
Solution:
```CSharp
using System; 
namespace Solution
{
  public static class Program
  {
    public static double Heron(double a, double b, double c)
    {
        var s = (a+b+c)/2;
        return Math.Sqrt(s * (s - a) * (s - b) * (s - c))  ;
    }
  }
}
```