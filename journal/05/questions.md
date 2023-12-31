# Intro to Server side concerns with JavaScript
01. What do the letters of the acronym `CRUD` stand for?

  >  c = create
     r = read
     u = update
     d = delete

02. Each action that `CRUD` represents maps to an HTTP request. What HTTP request does each `CRUD` action correspond to?

  > Create corresponds to post
  read corresponds to get
  update corresponds to put
   delete corresponds to delete

03. What does `ORM` stand for? Which `ORM` do we use when interacting with MongoDB

  > ORM stands for object relational mapping what we use with mongoDB is mongoose

04. Which two `HTTP` request types include a body?

  > A post request would have a body, and the get request would also contain a body

05. In a/an __syncrhonus_____ coding model, when you call a function, it returns only when the action has finished and stops your program for the time the action takes. Likewise in a/an ___aynchronus____ coding model, multiple things are allowed to happen at one time. When you perform an action, your program continues to run.  Fill in the blanks.

  > | syncrhonus, aynchronus

06. What are the three types of data relationships? Provide an example of each.

  > | A string data type, so a sequence of characters digits or symbols that will always be treated as text.
   BOOLEAN Which is simply a true/false value. 
   Enumerated type, a small set of predefined unique values(elements or enumerators) these can be text-based or numerical

07. What is middleware?

  > Middleware is sort of a gatekeeper that will check the auth of a user. It acts to provide a way to intercept and process data or events.

08. The ______ pipeline delivers information from the client while the ______ pipeline returns it. Fill in the blanks. 

  > request, respond

09. Demonstrate the pattern that is used to include a request query with the client's `HTTP` request providing the property `tag` and the value `winter`.

  > '?name=skyler'

10. What is a ***virtual property***?

  > A virtual property is a propery on an object that does not exist in the database but CAN exist on the object for your response.
