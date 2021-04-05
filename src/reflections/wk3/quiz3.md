# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
Encapsulation, Abstraction, Inheritance, and Polymorphism
```
**2.** How would you access the `name` of the below object using the `property` variable?
```js
let staff = {
  name: "Tim",
  age: 26,
  job: "Code Monkey"
  }
let property = 'name'
```
<!-- enter you answer in the space below -->
```
let property = staff.name
```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
Grouping of like code.
```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
The Single-responsibility principle: "There should never be more than one reason for a class to change."
```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
A class is a blueprint for an object and an instance is single object modeled after the the class because of its use. 
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
Its like a wrapper for our object that is looking at our object to change to exicute a function provided. 
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
MVC Pattern stands for Model-View-Controller Pattern. This pattern is used to separate application's concerns.
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
To interact with the website visually. All changes visually have to occur in the controller like draw().

```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
This is where our data stored in AppState is worked out by our functions to react to the changes made by an action our user does.

```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
The Model is where all of our different classes are stored aswell as templates that get called in the controller.
```

