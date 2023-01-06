## [Find the unique number](https://www.codewars.com/kata/585d7d5adb20cf33cb000235/train/csharp)

- There is an array with some numbers. All numbers are equal except for one. Try to find it!

Examples:

```CSharp
findUniq([ 1, 1, 1, 2, 1, 1 ]) === 2
findUniq([ 0, 0, 0.55, 0, 0 ]) === 0.55
```

- It’s guaranteed that array contains at least 3 numbers.
- The tests contain some very huge arrays, so think about performance.

Solution:

```CSharp
using System.Collections.Generic;
using System.Linq;

public class Kata
{
  public static int GetUnique(IEnumerable<int> numbers)
  {
    return numbers.Distinct().First(x => numbers.Count(y => y == x) == 1);
  }
}
```
