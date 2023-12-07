# Application Architecture, MVC Design Pattern
01. What are the Pillars of Object Oriented Programming (`OOP`)?
  
  > abstraction, encapsulation, inheritance, and polymorphism, 

  Abstraction = to abstract something means to hide away the implementation details inside something - sometimes a prototype, sometimes a function. Basically when you call the function you don't have to understand exactly what it is doing. That is what Abstraction is all about. Finding things that are similar in your code and providing a generic function or object to serve multiple places/with multiple concerns.
 
 Encapsulation = the action of enclosing something in or as if in a capsule. Encapsulation means that each object in your code should control its own state. State is the current "snapshot" of your object. The keys, the methods on your object, Boolean properties and so on. If you were to rest a Boolean or delete a key from the object, they're all changes to your state.
 
Inheritance = lets the object acquire the properties and methods of another object. keep your inheritance simple and predictable. Remember the Liskov substitution principle. 

Polymorphism = polymorphism is the concept that a functions can perform different operations at the same time!

 


02. How does `export` differ from `export default`?
  
  > Export is a way to move functions or expressions into differtn files and you can do alot of these. A default export, you can only have one this is considered a fallback.

03. What is Encapsulation?
  
  > The conecpt of binding fields (object state) and methods (behavior) together as a single unit

04. What are some of the benefits of the `Proxy` object that we are using in our structure for applications?
  
  > 

05. What the difference between a `class` and an instance of a `class`?
  
  > The difference is that a 'class' is a blueprint, an instance of that class would be the "Physical" copy of the blueprint

06. What is a computed Property?
  
  > A computed property is a Value that can be derived from another stored value.

07. What is the purpose of the `MVC` pattern?
  
  > To abstract the project and practice the principles of oop

08. What is the job of the `Controller` in the `MVC` Pattern?
  
  > The controller handles taking in user actions, the controller is also responsible for the draw of data to the dom

09. What is the job of the `Service` in `MVC`?
  
  >This is where business logic happens anything that is changing the data goes in here.

10. What is the job of the `Model` in `MVC`?
  Blueprint of the things that you want to build in the controller 
