## Calculate Average 

- Write a function which calculates the average of the numbers in a given list.

Note: Empty arrays should return 0.

```CSharp
using System.Linq;
class AverageSolution
{
  public static double FindAverage(double[] array)
  {
    // Your code here
    return array.Length == 0 ? 0 : Queryable.Average(array.AsQueryable());
  }
}
```
 
