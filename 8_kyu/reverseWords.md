## [Reversed Words](https://www.codewars.com/kata/51c8991dee245d7ddf00000e/train/csharp)

- Complete the solution so that it reverses all of the words within the string passed in.

#### Examples:

```cSharp
"The greatest victory is that which requires no battle" --> "battle no requires which that is victory greatest The"
```

#### Solution:

```cSharp
using System.Linq;
public class Kata
{
  public static string ReverseWords(string str)
  { 
    return string.Join(" ", str.Split().Reverse());
  }
}
```
