# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
Allows you to access files all in the same namespace.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
a class is a reference type and a struct is a value type
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
constructor
```
## Example 1
```c#
abstract class Car
{
  ...
  public virtual string Start()
  {
    return "Vroooom";
  }
}
```
**5.** In the example what is the access modifier of the `Start()` method?
<!-- enter you answer in the space below -->
```
public
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
data type being returned
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
prevents from being instantiated without being inherited from another class
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
to indicate a method that create a virtual property
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
public, private, protected, internal
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
only what is within its scope, can't be accessed from elsewhere
```