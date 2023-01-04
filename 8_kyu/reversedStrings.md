## [Reversed Strings](https://www.codewars.com/kata/5168bb5dfe9a00b126000018/train/csharp)

- Complete the solution so that it reverses the string passed into it.

#### Examples:

```cSharp
'world'  =>  'dlrow'
'word'   =>  'drow'
```


#### Solution:

```cSharp
using System;
using System.Linq;
public static class Kata
{
  public static string Solution(string str) 
  {
     return new string(str.Reverse().ToArray());
  }
}
```
