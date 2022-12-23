## Can we divide it? (retired)

- Your task is to create the function `isDivideBy` (or `is_divide_by`) to check if an integer `number` is divisible by both integers `a` and `b`.

Example:

```CSharp
    (-12, 2, -6)  ->  true
    (-12, 2, -5)  ->  false

    (45, 1, 6)    ->  false
    (45, 5, 15)   ->  true

    (4, 1, 4)     ->  true
    (15, -5, 3)   ->  true
```

```CSharp
public class Kata
{
    public static bool is_divide_by(int number, int a, int b)
    {
        return number % a == 0 && number % b == 0;
    }
}
```
