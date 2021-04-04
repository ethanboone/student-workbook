# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
There are 4 pillars of object oriented programming- Abstraction, Encapsulation, Inheritence, and Polymorphism.
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
staff[property] you would need to use bracket notation rather than dot notation, as you can't access a property using a variable with dot notation.
```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
Encapsulation is a way of storing data that make it unable to be directly accessed, an example of encapsulation would be creating an instance of a class and saving that object as a const variable.
```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
S stands for single responsibility
```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
A class is what is used to set predetermined properties and methods for objects, an instance of a class would be using a class to create a new object.
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
A proxy object is an object that can take in and modify operations of the object a proxy is created of.
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
The purpose of MVC is to split up a program into separate files, each contributing to creating the functionality of an application.
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
The controller is what is what modifies the document or the view, it draws templates to the page and declares methods that get defined in the service.
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
The service in MVC is used for the logic and functionality of a program. It manipulates data in the state, and creates the methods that control functionality on the page.
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
The model is a template used in your program. The way our class utilized the model this week was to create classes for the objects to be instantiated and displayed to the view (or HTML document).
```

