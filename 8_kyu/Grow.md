## Beginner - Reduce but Grow

- Given a non-empty array of integers, return the result of multiplying the values together in order. Example:

For example:

```CSharp
    [1, 2, 3, 4] => 1 * 2 * 3 * 4 = 24
```

Solution:

```CSharp
public class Kata
{
  public static int Grow(int[] x)
  {
    int res = 1;
      foreach(int i in x) {
         res = res*i;
      }
    return res;
  }
}
```
