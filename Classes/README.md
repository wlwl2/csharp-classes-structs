# Classes

```cs
public class Customer
{
   // Fields, properties, methods and events go here...
}
```

## Objects

```cs
Customer object1 = new Customer();
```

```cs
Customer object3 = new Customer();
Customer object4 = object3;
```

Classes fully support inheritance, a fundamental characteristic of
object-oriented programming. When you create a `class`, you can inherit from any
other interface or class that is not defined as `sealed`, and other classes can
inherit from your class and override class virtual methods.
