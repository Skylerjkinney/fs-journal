# Understanding Asynchronous Code, and API's
01. What is the difference between `asynchronous` code and `synchronous` code?

  > synchronous code performs one action at a time and all other functions will remain idle while the one function is finished. In comparison asynchronous code will perform all the actions at the same time and will finish quickly.
  synchronous code = slow
  asynchronous = fast  

02. What is an event listener?

  > An event listener is a function that "watches" something an when something triggers on the thing that is listened too then something happens. Typically an function called a "handler".

03. What does *REST* stand for, and in simple terms what does it mean??

  > refers to a group of software architecture design constraints that bring about efficient, reliable and scalable distributed systems.
  In simple terms it means that it is a standardized way we handle client/server interactions and don't break the internet.
  similar to HTTP is RESTful or RESTful API

04. What is a callback / higher order function?

  > A higher order function is a function that takes one or more functions as arguments, or returns a function as its result
  its a function that can run multiple functions
  a callback function is the function that is called from the higher order function to handle the a

05. What is a `promise`? How do you capture an error from a `promise`?

  > A promise was the javascript solution to call back hell where there was just a cascading mess of indents and higher order functions because things need to run in async. Promises serve to solve this by having a function have two parameters that will either resolve or reject the parameters are functions that indicate completion or failure in asynchronous code.

06. Name three processes used to make requests over `HTTP`?

  > Get : The GET method requests that the target resource transfer a representation of its state. how we get info from api
    Post: The POST method requests that the target resource process the representation enclosed in the request according to the semantics of the target resource. how we send info in to api.
    Head :The HEAD method requests that the target resource transfer a representation of its state, as for a GET request, but without the representation data enclosed in the response body.

07. What does the `API` acronym stand for?

  > API stands for Application Programming Interface. In the context of APIs, the word Application refers to any software with a distinct function. Interface can be thought of as a contract of service between two applications. This contract defines how the two communicate with each other using requests and responses. // this is from AWS but the best description I found.

08. What must you do in order to `await` a promise inside of a function?

  > Make sure the function itself is asynchronous so that it cal delay its process until the promise is either resolved or rejected.

09. What is the purpose of encapsulation in programming?

  > The purpose of encapsulation is to bundle data within the function so that user parties do not have direct access to them.

10. What is `HTTP` response code for a successful request?

  > successful responses will have a code between 200-299

11. What is a 400 error?

  > Client side (you) response codes are in the 400-499 range



  <!-- list of response codes from HTTP -->
  Informational responses (100 – 199)
Successful responses (200 – 299)
Redirection messages (300 – 399)
Client error responses (400 – 499)
Server error responses (500 – 599)
