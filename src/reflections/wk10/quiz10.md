# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
A root all your files in your C# project
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
Structs are value types while classes are reference types.
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
void
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
data type
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
Abstraction in C# is the process to hide the internal details and showing only the functionality. The abstract modifier indicates the incomplete implementation.
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
modify a method, property, indexer, or event declaration and allow for it to be overridden in a derived class.
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
public, internal, private, protected
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
only the other classes or methods in that one private class/method.
```