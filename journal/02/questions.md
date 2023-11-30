# Intro to JavaScript
01. Which keywords are used to declare a variable in JavaScript?

    > | Var Let Const

02. What is the definition of a function?

    > A function is a set of statements that perform a task or calculates a value

03. What are the `SOLID` principles?

    S: Single responsibility principle
    O: Open closed principle
    L: Liskov substitution principle
    I: Interface segregation principle
    D: dependency inversion principle

04. Given this array: How could you remove the `pineapple`?

    ```js
    let fruit = ['apple', 'banana', 'pineapple', 'orange', 'strawberry']
    ```

    > | fruit.splice(3,1)

05. Given these two objects: How could you add each to the others friends arrays?

    ```js
    let you = {
        name: "You",
        hair: true,
        friends: []
    }
    let them = {
        name: "Them",
        hair: false,
        friends: []
    }
    ```

    > you can use the push method to target the friends property in the "them" array and add "you" to it this process will use vis versa

06. Give an example of a JavaScript `Conditional`:

    > A condition is something like an if statement that can control behavior and dictate wether or not certain pieces of code can run

07. What is the main difference between `parameters` and `arguments`?

    > parameters are more "guidelines" or almost like a template for you to insert your arguments. I imagine making a parameter is like drilling a triangle shaped hole (which is the parameter), then having to insert only triangle shaped pieces that could be different colors but ultimately have to be a triangle.

08. Instead of writing everything to the console, what is a better way to debug your code?

    > add debugger to your code, though mind that it will initialize within its own scope.

09. What is the difference between a `primitive` value and a `reference` value?

    > | primitive are the values: null, undefined, numbers, boolean,. reference types are things like arrays, objects and functions

10. Demonstrate a loop that prints the numbers between -100 and 100?

    > | for(let i = -100; i >= 100; i++){
        console,.log(i)
    }
        
