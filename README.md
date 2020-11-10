# Level 4 Questions

## A singleton pattern is used in the class that defines the database. What is the purpose of this pattern?
- Singleton pattern is a design pattern which restricts a class to instantiate its multiple objects. It is nothing but a way of defining a class. Class is defined in such a way that only one instance of the class is created in the complete execution of a program or project. It is used where only a single instance of a class is required to control the action throughout the execution. A singleton class shouldn’t have multiple instances in any case and at any cost. Singleton classes are used for logging, driver objects, caching and thread pool, database connections.    

## Why should you load the data in a background thread?
- You should load the data in a background thread because the UI has a good change to be frozen if not. With a background thread this gives the application a better performance.
    
## What are the three major components of ROOM and what are their responsibilities?
- The room database
- Entities
- Data access objects
    
## How can you extract the current database so that you can see the table, columns, and data?
