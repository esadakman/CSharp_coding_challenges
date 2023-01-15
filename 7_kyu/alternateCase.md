## [Alternate case](https://www.codewars.com/kata/57a62154cf1fa5b25200031e/train/csharp)

- Write function alternateCase which switch every letter in string from upper to lower and from lower to upper.

#### Example:

`Hello World -> hELLO wORLD`

#### Solution:

```CSharp
using System;
using System.Linq;

namespace Solution
{
  public static class Program
  {
    public static string alternateCase(string s)
    {
      return string.Concat(s.Select(c => char.IsLower(c) ? char.ToUpper(c) : char.ToLower(c)));
    }
  }
}
```
