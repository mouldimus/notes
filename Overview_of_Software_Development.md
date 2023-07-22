# Overview of Software Development
Basics of Object Oriented Programming and more.

See these videos for more information:

- [Overview of Software Development Part One](https://www.youtube.com/watch?v=sLFtfQLjnqU)
- [Overview of Software Development Part Two](https://www.youtube.com/watch?v=NMifF5iiuNc)

## What is Object Oriented Programming (OOP)
OOP could be any time you create a program with the object at the core of the program.

**For example,**

If you were to first think "what things does my program need to have in it to work", then write the program around those objects. *This would be an instance of object oriented programming.*

## Class 
A class is a user defined potential property and behavior.

Class
: A definition of Properties/Behavior

**For Example,**

![Red Tesla](./images/tesla-red.jpeg)
Creating a class is like saying for a car to be a car it has to have or do these things.

### Properties

If I had a car class here's a list of the cars *properties*.

| Name | Property |
| ---- | ------- |
| Colour | Red |
| Make | Telsa | 
| Model | Model S |
| Number Plate | N/A |
| No. Wheels | 4 |
| Fuel Type | Electric |

### Behavior

Whereas its *behavior* would be things like.

| Name | Behavior | 
| --- | --- | 
| Top Speed | 210mph |
| 0-60mph | 2.2 Seconds |
| Torque | 100% |

Meaning that the actual car *class* would look something like.

```json
    {
        "colour": "",
        "make": "",
        "model": "",
        "numberPlate": "",
        "noWheels": "",
        "fuelType": "",
        "topSpeed": "",
        "0-60": "",
        "torque": "",
        "makeInstance": "runConstructor"
    }
```


### Instance/ Object
When you make an instance of your class you are creating the actual object using the core parameters set by the class.

**I.E.** 

The class car would define something along the lines of, for a car to be called a car it must have:
- 4 wheels
- a power source driving it fowards
- a way to control what direction it is going
- transports things over the surface of solid ground
- etc

### Constructor
Inside the class it also has instructions on how to create an instance of the class. This is typically called a constructor.

## Encapsulation
- Capsulate
: means to put inside a capsule
- Subprogram
: A program which is used in another bigger program

In computer programming you often have a subprogram inside of a main program and the main program will call upon the subprogram execute its program. 

When the implimentation of the subprogram is hidden from the user, this is called encapsulation.

The user does always need to know how the computer does something. Sometimes the user just needs the computer to show the result of what it has done.

Another reason for encapsulation is security, you don't want the computer or anything else to change the subprogram being encapsulated.

## State
State
: the condition of something

Stateless
: Something that never changes

State is only used for things that *change* over time.

## Inheritance
If you're defining a class called a vehicle, you'll have properties and behavior.

**Properties**
- Body Type
- Colour
- Year 
- Manfacturer
- Engine 

**Behavior**
- Accelerate
- Stear
- Decelerate

An Instance of this would be:
| Name | Value | 
| ---- | ---- |
| Body Type | Coupe |
| Colour | Red | 
| Year | 1957 |
| Manfacturer | Ford | 
| Engine | Gas V8 |

Inheritance would be where the programmer could *inherit* the properties and behaviors from a parent class.

Like for example there are lots of different types of vehicle, but they all need those properties.

So instead of rewriting all the properties I need for *every* vehicle, I just write the extra properties I need and inherit the rest from a parent class.

## Aggregation / Composition
- "is-a" - inheritance
- "has-a" - aggregation / compostion

## OOP
### Polymorphism
How behaviors are defined in one class can be applied in other classes and how the relationships between eachother.

### Variable
Data saved to the memory thats value can change based on state.

### Constant
Data saved to the memory thats value cannot change.

### Function

A function is a defined set of instructions easily repeatable by just referencing the function in the program.

The results of the function are called the return.

### Whats an index?
A pointer towards where data is kept.

| Index | Data | 
| :----: | :---- |
| 0 | Thomas |
| 1 | Charlie | 
| 2 | David |
| 3 | Jane |

The index just says this is where the data is kept.

## Dictionary

A set of data arrange in pairs. The two types of data are the key and the value.

| Key | Value | 
| --- | --- | 
| Age | 24 | 
| W | 82kg | 
| H | 6ft | 
| DOB | 18/06/1999 |

This is a dictinary.

##  Ifs and Elses
You're telling the computer to follow instructions based on a set of conditionals.

## Loop
A loop in computer programming is telling a computer to carry on following a set of repeatable instructions, until the conditional that has been set is not longer applicable.

## ALM 
: Application Lifecycle Management

- Application
: Software
- Lifecycle
: Beginning to End
- Managemnt 
: Requires, Architecture, Develop, Test, Deploy, Maintain

ALM is the proceedures and tools that Software Developers use to create software.

## Data Types
| Data Type | Description | Example | 
| --- | --- | --- | 
| int | integer - whole number | `6` |
| float | Floating point number | `-0.125` |
| String | String of characters | `"Bob"` |
| Boolean | binary variable | `true` |


## Stack
A Stack in Software Development means the systems and software used to create/host software.

### LAMP Stack
A LAMP Stack is a specific type of software development stack that is commonly used.

- OS 
: Linux
- Website
: APACHE
- Database 
: MySQL
- Language
: PHP

This is called the LAMP stack.

### Windows Stack
Here's an example of a Windows stack


- Web Server 
: IIS (Internet Information Services)
- Database
: SQL Server (Structured Query Language)
- Language
: PHP, Javascript or Python

## Why are there different types of programming languages


### Databases
A database is a specific collection of data used in web servers. It is designed to store data that can be easily retrieved under certain conditions.

**For Example** 

If I wanted to get all the users firstName, lastName, email, address and postcode of the users that spent over 5k with the company last year. I could send a query to the database, it would process the query using the database language and return a result. 

SQL
: Structured Query Language is a language that's great for querying databases, but it's not that good at rendering websites.

That's where HTML comes in.

### HTML
HTML
: HyperText Markup Language

HTML is designed to render webpages, images and text and display it on the users screen. Every single website in the world uses HTML in some way shape or form. It is rendered using an interpreter.

### Scripting
Scripting is the process of writing a program that automates everyday tasks. 

### Object Oriented Language
A language based around making and manipulating objects in a program.

## Applications
An application is a program or piece of software designed to fufill a particular purpose.

There are loads over different types of applications like:

- Console based
: an application that only runs in the console.
- Browser Based 
: a browser based application
- Server Based
: a server based application requested by the client computer

## Low Level Language
Otherwise known as machine code or binary. It is quite litterally just 1s and 0s. The *literal* on or off instructions that tell the computer what to do.

## High Level Language
A computer programming language that reads alot like english that gets put through complier and converted into 1s and 0s.

### Complier
A complier takes a high level language like C#, Java or Python and breaks it down into the machine code for the computer to understand and execute.

### Interpreted
Whereas a interpreter is a program that takes each individual line of code, translates it into machine code, the computer executes it, then carries on repeating the process until the program is complete.

## Framework
A framework is a collection on pre written code to help software developers re-inventing the wheel everytime they write software.

It can contains things like an interpreter, complier, common classes used for appearance, common functions, basically anything that has already been created and can be reused again.