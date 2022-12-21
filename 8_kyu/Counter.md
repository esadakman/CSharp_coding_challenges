## Broken Counter

- Our counter prototype is broken. Can you spot, what's wrong here?

- `Counter.Value` must have manually defined getter/setter methods, according to our company's style guide.

```CSharp
public class Counter
{
   private int _Value;
   public int Value
   {
       get
       {
           return _Value;
       }
       private set
       {
           _Value = value;
       }
   }

   public Counter()
   {
       Value = 0;
   }

   public void Increase()
   {
       Value++;
   }

   public void Reset()
   {
       Value = 0;
   }
}
```
 
