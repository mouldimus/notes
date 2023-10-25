# CSS Fundamentals and Associated Tools
## Utilizing Visual Studio Code
### Visual Studio Code
Up until this point we’ve been using Notepad++ as our code editor (a program used to write code).

Visual Studio Code is a code editor from Microsoft that has more capabilities than Notepad++ – it’s an excellent tool. One of the features Visual Studio Code includes is IntelliSense (an aid that makes suggestions to you as you write code).

We are going to change from Notepad ++ to Visual Studio Code now for the following reasons:

1. Developers should be experienced in several different code editors and IDEs so they can choose the one they like best.

2. The more you use IDEs, the faster you’re able to learn new ones later on. In a future job you may be required to use an unfamiliar IDE.

3. Visual Studio Code is a great undercut to more advanced IDEs – like Visual Studio.

**While the Instructor in upcoming videos continues to use Notepad ++, you will write and run your code within Visual Studio Code.**


### Library
As a reminder, a *library* is a collection of files. A library can also be a set of automatic commands a computer performs. Programmers often make libraries of useful computer code so others don't have to do all that same work when they need to do things that the code in the library does.

#### Example
    Code libraries are large collections of code written by others. These can be downloaded and imported for use in your own code.

### Runtime
As a reminder, *run* means to start or execute something.

To understand runtime, you must first understand what a “compiler” is. We have covered this before but as a refresher, a compiler is a special program that converts the code that looks nearly English into a form that the computer can understand and operate off of. The product of a compiler would be a set of instructions for the computer to execute that would end up doing what the “nearly English” code described.

*Runtime* means the time when something in the computer is running. Runtime is exactly what it means – the time when the program is run. You can say something happens at runtime or it happens at compile time.

The term “runtime” also describes software or instructions that are executed while your program is running, especially those instructions that you did not write explicitly, but are necessary for the proper execution of your code. This is actually a “runtime library,” but is often shortened to simply “runtime.” In computer programming, a runtime library is a special program library used by a compiler to implement functions built into a programming language during the runtime (execution) of a computer program.

#### Example
    You can design videos to load during runtime or prior to runtime. If they were loaded during runtime, then you would have to wait for it to load after you clicked on it. If they were loaded prior to runtime, the videos would have loaded when you originally opened the program (set of instructions entered into a computer that performs exact functions) and so the program would take longer to load up when started.


### Runtime Environment
A *runtime environment* is the set of computer processes related to a specific computer program that are in use by the computer as that program is running. These processes handle such things as memory allocation for the program’s data, access to the program’s variables, the passing of needed data between various sub programs, interfacing with the operating system of the computer and more.


### Asynchronous
As a reminder, synchronous means that two things exist or happen at the same time. In computers, synchronous means that something is happening in a set way, in regular intervals. It is a smooth, predictable flow.

“A” means “not” or “without.” So when you add “a” in front of “synchronous” you get “asynchronous” which means something can occur without being subject to set, regular intervals.

When a synchronous process is occurring, each of the separate steps of the process are done consecutively, and each step has to be fully completed before the next step is begun.

An asynchronous action, on the other hand, does not have to complete before the next steps of the process can continue.

#### Example
    A computer program is processing a list of students. The program is supposed to search through a collection of documents, find the documents that have the name of the student in the document title, and count up how many documents each student has. This is a synchronous process.

    An asynchronous element of this could be: If no matching documents are found after searching for a particular student, the program could send an email to that student alerting them of the fact. Since that action is asynchronous, the program can go on with checking the next student without having to wait for the entire email process to occur. Later, when the email action is done, the program can be informed of that fact.


### Node.js
*Node.js* is a runtime environment that lets you run JavaScript code outside of a web browser – typically on a web server.

To illustrate this: consider how JavaScript is used in a browser. The basic job of a browser is to retrieve HTML files and render a user-interface (UI) based on those files. However, nearly all browsers have a sub program in them that can read JavaScript code and execute it. That sub program is commonly called the “JavaScript Engine.”

Web servers don’t automatically allow JavaScript code to be executed on the computer. In order to do so, you need a program like the “JavaScript Engine” that is in a browser. To set up a system like this, you install the Node.js program on the server and start the Node.js program. As long as the Node.js program is continually running, it allows JavaScript code to be executed on the server. This means you can write a computer program in JavaScript, install it on the web server and it will work.

One advantage of this is that a programmer can write their code in JavaScript, whether that code is to be used in the browser or on the server.

![node.js](./images/node_js.png)

### Difference between Library and Framework
The terms *library* and *framework* are often used interchangeably. They are similar, but not identical. Let’s examine those differences and similarities.

#### Library
A library is a collection of pre-made resources used to create computer programs. Most often, these take the form of a package of code with built-in functions that all relate to a specific area. They are usually used by adding them to a software project already being created, and then having code in that project make use of the various functions in the library.

#### Framework
A framework is similar in nature to a library, in that it is made up of pre-made resources, which are usually computer code. The framework is usually a fully-functioning system that provides a complete set of generic functionality as is, and it can be modified by the programmer to fit their needs.

#### Examples
    A library might exist for performing complex calculations that are common in scientific research. A programmer, wishing to create a program for scientific researchers, might add this library to the program they are creating. The action of adding the library would not modify how the program ran; rather, the programmer would have to modify their program to call certain functions now available from that library before their program would have modified behavior.

    On the other hand, we could look at a framework for creation of web applications. This framework would actually provide generic functionality from the moment the programmer installed it - in fact, the framework would likely be the web application in its initial form. The programmer would add to and modify the code in the framework to meet the specific requirements of the final application. In this way, a framework is a reusable “starting point” for a programmer to create programs with greater complexity.

    The difference could be summarized this way: a library is code that can be called by another, primary program. A framework is itself a working program that can call other code.


### Console
As a reminder, there are two main definitions for *console*:

1. A basic computer or monitor and keyboard that is connected to another computer or server over a network. Consoles are used to maintain or monitor the status of the network or computer.

![console_irl](./images/console_irl.png)

2. The console is a feature that allows developers access to special features of programs and an area to issue commands. It typically looks something like this:

![console_screen](./images/console_comp.png)



### Breakpoint
A *breakpoint* is a place in a computer program where execution is interrupted. A breakpoint is an intentional stop or pause in a program, typically put in place for debugging purposes. The program runs until that point and then the developer inspects that part of the program to ensure it’s working properly.

In original computers, a breakpoint was set by unplugging a cable. Meaning, the programs would run until they reached that cable.

#### Example
    With lengthy programs, breakpoints allow you to inspect sections of programs to locate bugs, as opposed to attempting to locating issues by having to go through the entire program.


### Documentation
Review Microsoft’s official documentation on how to utilize Visual Studio Code:

[Documentation for Visual Studio Code](https://code.visualstudio.com/docs)

### Optional Study
Watch the Introductory Videos on Visual Studio Code from Microsoft here:

[Visual Studio Code Introductory Videos](https://code.visualstudio.com/docs/getstarted/introvideos)



### Visual Studio Code Features 
Read the following descriptions and as you do so, find and view each feature in Visual Studio Code:

**Activity bar:** The leftmost column of the window on the left side of the screen with medium sized icons gives you access to Side bars, including “Explorer” where you can find all of your files, and “Search,” “Source Control,” “Debug” and “Extensions.”

![activity_bar](./images/activity_bar_1.png)

**Editor bar:** At the top of the VS Code window is a row with tabs for each open file, like tabs in a web browser.

![editor_bar](./images/editor_bar.png)

**Panels:** Windows on the bottom include “Problems” with your program, Visual Studio Code “Output,” the “Debug Console” (like developer tools in the browser), and a “Terminal” where you can execute commands as if you were in a Command Line Interface without leaving VS Code.

![panels](./images/editor_bar2.png)

If the panel area isn’t visible, you can open it by selecting “View” at the top of the application and selecting any of the panels, like “Problems.” You can also access it from the “View” menu.

**Status bar:** The thin band on the bottom of the screen is where you will often find access to many extension features you have installed, like Version Control. Almost all of the information is clickable to allow you to make changes.

![status_bar](./images/status_bar.png)

**Command Palette:** If you press " CMD + SHIFT + P" at any time you will see a dropdown at the top of the page called the Command palette where you can type commands.


### Publishing to GitHub with VS Code
Over the next several steps, we are going to cover how to push code to GitHub from within Visual Studio Code. First, let’s cover some of the terms associated with doing so.

### Uniform Resource Identifier (URI)
A *Uniform Resource Identifier* (*URI* for short) is a series of unique characters that identify a resource on the World Wide Web. They can be used to identify anything, such as people, places or other kinds of information including web pages. The most common form of a URI is a Uniform Resource Locator (URL), which (as you know) describes the location of a website. 

### Upstream Branch
An *upstream branch* is a remote branch that is connected to or has a relationship to a local branch. The upstream branch and local branch are, in essence, two separate branches that are connected to each other. When updates from a local branch are pushed to a remote repository, Git will know where to put the new changes for that local branch in the remote repository. These branches are separate because a branch created locally on your computer does not exist in the remote repository until you tell git to track that branch, at which point it will essentially send the data upstream to a remote repository. 

Here it is diagrammed:

![upstream_branch](./images/upstream_branch.png)

### GitHub Issue
In reference to GitHub, an *Issue* is a task for a project. The issues section on GitHub is a way to keep track of tasks within a repository. Issues can be shared among other developers and assigned to a specific developer to complete.

Here is an example of what an Issue would look like. 

![example_issue](./images/example_issue.png) 

### Customization Assignment
Set up the appearance of Visual Studio Code the way you’d like it.

OPTIONAL RESOURCE – review this web page: 

[Visual Studio Code Themes](https://code.visualstudio.com/docs/getstarted/themes)

### Visual Studio Code Integrated Terminal Challenge
Write and execute a command-line command (console command) within Visual Studio Code from the Integrated Terminal.

RESOURCES:

1) [Integrated Terminal in Visual Studio Code](https://code.visualstudio.com/docs/editor/integrated-terminal)
2) [The Visual Studio Code command-line options](https://code.visualstudio.com/docs/editor/command-line)

### HTML in Visual Studio Code
Review Microsoft’s documentation on using HTML in Visual Studio Code here:

[HTML Programming with Visual Studio Code](https://code.visualstudio.com/docs/languages/html)

### Debug Environment
As a reminder, an *environment* is an overall structure within which a user, computer, etc. operates. This is often used to mean “the combination of physical hardware and operating system that my computer uses.”

A *debug environment* would be an environment that is used for debugging purposes.

### Debug Console
A *debug console* is a tool that is used to find and display errors in code. For example, Google Chrome has its own debug console in developer tools called “console.”

### CSS
CSS holds the purpose of beautifying websites and separating styling from HTML.

When HTML was originally developed, it was intended to build static, text-based websites. Images were made up of characters on the ASCII chart – made of commas, underscores, apostrophes, etc. Like this:

![ascii_sonic](./images/ascii_sonic.png)

HTML was very basic and developers did not require much in terms of features.

### CSS and HTML
As the Internet grew in popularity and more companies shifted their business models to have an online presence, the need for innovative web-development features arrived.

CSS was designed to solve this problem.

In the mid-1990s, developers used only HTML to manage colors, images, fonts, sizes and all of the other stylings. With large websites, this proved difficult because all of the styling was mixed in with the website functionality.

### The Arrival of CSS
When CSS arrived in 1998, it allowed developers to manage larger websites with fewer lines of code, located within a centralized .css document (style sheet).

CSS introduced the concept of grouping many similar HTML elements into classes where developers would be able to make style changes, across multiple pages, all at once by simply making a few changes to the corresponding class attributes referenced within the centralized .css document.

For example: let’s say that we have a website made up of 12 different webpages. Each web page is saved as a separate .html file – meaning, there are 12 .html files. Each is linked to our .css file (style sheet). We want to change all of the `<h2>` elements so they are an exact size, color and font type. Instead of individually changing the style of every `<h2>` tag within each .html file, we can make the change in our style sheet and voila! We’ve updated the `<h2>` across all our webpages.

### The Basic CSS Syntax
As a reminder, the CSS syntax consists of a CSS selector (this points to the HTML element that you want to style) with properties and values. A “property” is an identifier; a name – it explains what feature is being considered. A “value” describes how the feature is handled.

A CSS declaration is a statement that consists of a property and a value.

A CSS rule-set is:

![CSS Syntax](./images/css_syntax.png)

The process of matching CSS selectors with their HTML element is termed "CSS targeting".

### Axis
Coordinates are a set of two numbers that can locate any point on a grid or chart. For example: by using the coordinates longitude and latitude, you can find a location on a map:

![longditude latitude](./images/css12.png)

An axis is a line that measures coordinates – in the above example longitude is an axis and latitude is an axis.

The line that runs left or right (horizontal) is called the X-axis. The line that runs up or down (vertical) is called the Y-axis.

![x and y axis](./images/css13.png)

These axes can be used to point to exact locations on a grid. For example: let's say we want to place these symbols at these coordinates:

| Symbol | X Axis | Y Axis |
|---|---|---|
| % | 3 | 4 |
| $ | -3 | -2 |
| & | -2 | 2 |
| @ | 4 | -4 |

The output on the grid would look like this:

![x and y result](./images/css14.png)

### Gaussian Blur
Also called *Gaussian smoothing*, *Gaussian blur* is an effect named after the French mathematician Carl Friedrich Gauss. It creates an effect like this (left side is the original picture and right is with the effect):

![gaussian blur](./images/gaussian_blur.jpeg)

You can create this effect with CSS.

### Array
As a reminder, an array is a collection of data, arranged in rows and columns.

In computers, an array is a group of related things that are stored together in a sequence. It is a way things can be organized in a computer in a logical way. Arrays can be quite simple, or quite complex.

#### Example

A simple array would be something like the numbers 7, 3 and 15. It would be written out like this:

    [7,3,15]
These three pieces of data are called elements - they are the elements of the array. Another word for the data in an element is “value”. The first element in the array above has a value of “7”.

A system is needed for identifying each element of an array. The simplest method for this is to start numbering them at zero starting at the left position and count up from there.

In the above example, the element "7" would be at position 0, "3" would be at position 1 and "15" would be at position 2.

Another word for the position of an element is the "index" of the element - for the above example of an array, index 0 is "7," index 1 is "3," etc.

Each element, therefore, has two properties: its index and its value.

#### Example
You have three pictures of your cat and you could save them in an array: CatPic1, CatPic2 and CatPic3. The array would look like this:

    [“CatPic1”,“CatPic2”,“CatPic3”]
Here, the element at index 1 has a value of "CatPic2".

### Nth
*Nth* denotes an unspecified number in a series of numbers. It refers to an unspecified item or instance in a series.

#### Example
If you performed testing on a group of people, you could refer to this as, “systematic testing by taking every nth name from a list”.

Sometimes the term is used as slang to mean you are emphasizing the number of times something has occurred. Like, “My two-year old asked for candy for the nth time.”

### More Data on Classes
Let’s look at the example of a class called “vehicle”. The structure of a vehicle class would include such things as:

An energy source that can provide the motive force to move the vehicle. Examples might be “a gasoline engine” or “an electric motor”.

A physical form that implements the primary purpose of the vehicle. Examples might be “sedan”, “convertible”, “pickup truck”, etc.

One or more doors to provide entrance and egress for the people operating or being transported by the vehicle.

A mechanism for increasing the speed of the vehicle. Examples might be “an accelerator pedal” or “a speed lever”.

A mechanism for decreasing the speed of the vehicle. Examples might be “a brake pedal” or “a brake lever”.

A mechanism for steering the vehicle. Examples might be “a steering wheel” or “a steering lever”.

A speed at which the vehicle is traveling. Examples might be “55 miles per hour”, “10 feet per second”, or “0”.

Another term for these structure elements is “Properties”.

The behaviors of a vehicle would include such things as:

Accelerate the vehicle.

Slow the vehicle.

Stop the vehicle.

Steer the vehicle to the right.

Steer the vehicle to the left.

When the computer program has a need for a vehicle, it would be directed to use this class definition to create, or “instantiate” one. Specifically, it would create an object of type “Vehicle”. At that point, the program would set aside parts of the computer memory to keep track of the properties of that particular object of the Vehicle class.

The computer program would then be directed to set the state of this new object of the Vehicle class. It would have to have specific values for the properties of this Vehicle – what type of engine it had, what physical form it was built to, what kind of steering mechanism it had, etc. Probably it would get these values from the user of the computer program.

Here are two examples of instantiated objects of the type Vehicle:

**Vehicle 1:**
Energy source: gasoline engine
Physical form: Pickup truck
Number of doors: 2
Mechanism for increasing speed: Accelerator pedal
Mechanism for decreasing speed: Brake pedal
Mechanism for steering the vehicle: Steering wheel
Speed: 0

**Vehicle 2:**
Energy source: electric motor
Physical form: Sedan
Number of doors: 4
Mechanism for increasing speed: Accelerator pedal
Mechanism for decreasing speed: Brake pedal
Mechanism for steering the vehicle: Steering wheel
Speed: 0

At this point, the computer program can make use of the defined behaviors for objects of the Vehicle class. That is, the computer might execute an instruction to “Increase speed of Vehicle1 by 10 miles per hour once a minute until its Speed property is 40 miles per hour”, or “Steer Vehicle2 to the right”.

### Child and Parent
Some computer programming languages allow for the definition of classes that inherit the structure and behavior of another class, while also allowing for the addition of new properties and new behaviors.

This concept is called “inheritance” – that is, the second class “inherits” the structure and behavior of the first class. In this system, the first class is called the “parent” class and the inheriting class is called the “child” class.

Using a “Vehicle” class as an example, the programmer might create child classes like “Airplane” and “Helicopter”. Each of these child classes would automatically get the structure and behavior of the parent class (“Vehicle”), but the programmer could add certain structure and behavior elements particular to that type of object.

For example, the “Airplane” class might add properties like:

1. A number of wings to provide lift
2. A number of engines

This “Airplane” class might add behaviors like:

1. Take off
2. Land

This way of programming adds certain benefits for the computer programmer. One primary benefit is that they don’t have to write the same code more than once. Besides the fact that it saves time, this is valuable because the programmer can make a change in the parent class and all its children can then make use of that change.

For example, the programmer might add the properties to the Vehicle class “A number of passengers” and the behaviors “Load a passenger” and “Remove a passenger”. Now, the children of the Vehicle class (“Airplane” and “Helicopter”) can use those properties and behaviors with no further work from the computer programmer.

### Absolute and Relative Paths
As a reminder, an absolute path is the full description of a file path, like:
- **C:\Users\User\Desktop\HTML webpage\image.png**
- **https://learncodinganywhere.com/**

A relative file path is when the directory is assumed to be the same location as your webpage. For example: 
- **./image.png**

