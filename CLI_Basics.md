# Command Line Interface Basics
### Index
- [Break Down of a BASH Command](#breaking-down-the-bash-command)
- [Directory](#directory)
- [OneDrive](#onedrive)
- [INI File Format](#ini-file-format)
- [Docx](#docx)
- [Touch](#touch)
- [Tilde](#tilde)
- [Command-line Option](#command-line-option)
- [Working Directory](#working-directory)
- [Parse](#parse)
- [Case-Sensitive](#case-sensitive)
- [Hash](#hash)
- [Staging](#staging)
- [Tracked File](#tracked-file)
- [Branching](#branching)
- [Using Github](#using-github)
- [Underscores and Spaces](#underscores-and-spaces)
- [Character Encoding](#character-encoding)


## Breaking down the bash command:
> `$ /bin/bash -c "$(curl -fsSL https://raw.githububusercontent.com/Homebrew/install/HEAD/install.sh)"`

Here is the syntax for some of the elements of various Mac CLI commands:

1. `$`
: the dollar sign symbol represents that the terminal is ready to accept your commands. 
2. `bin`
: is a folder containing system programs. This is setting the location of where you want homebrew to be installed. 
3. `bash`
: is the Unix shell that is used by the macOS system as a command-line interface. 
4. `-c` 
: This is called a single letter flag (command-line option) and it reads the command that needs to be executed.
5. `curl`
: is a command-line tool used to transfer data to or from a server.
6. `-fsSL` 
: This is a combination of the following command-line flags put together.
7. `-f` 
: (short for -fail) directs that if the command fails to execute, to do so silently (meaning if the server fails to deliver a requested document it will not return an error message). 
8. `-s`
: (short for -silent) instructs to run the command in silent mode (meaning no progress or error messages will display as feedback on the terminal). 
9. `-S`
: (short for -show-error): makes the command-line tool curl display an error message if it fails. Meaning, if the command-line tool curl has an error, it will display an error message. 
10. `-L`
: (Short for -location) directs that if the server reports that the requested page has moved to a different location, curl will then restart the request in the new server location.


## Directory
A directory is something (such as a book) which contains listings of information in an organized manner.

Technically, in computers, a folder and directory are the same thing. The only difference is that folder refers to a visual representation of a directory. Meaning, folders are icons representing a directory in the computer.

**Example:**

Your written documents could be stored in one directory while your pictures could be stored in another.

The root directory is the first or top directory in your computer. The root directory for Windows is
: `C:\\`


## OneDrive
OneDrive is a service provided by Microsoft for storing files online.

**Example:**
You could back up your hard drive on OneDrive and share the data with other people.


## INI File Format
"INI" is short for "initialization".

INI files are used by the Windows operating system, typically to lay out operating instructions for the OS and some programs.

**Example:**

Usually the instructions to the computer that enables the use of a mouse are stored .ini files.



## Docx
The docx file format (.docx) is short for “document XML.” 

As a reminder, XML is an extensible markup language. This means that developers can create their own document structure, and then use XML to specify markup instructions for the data in those documents. Tags are the markup language words that usually have two parts, a start tag and an end tag. They have these symbols before and after them: < and >. XML is similar to HTML except that the code itself can be customized (i.e. the developer can create their own tags).

The .docx file format is what Microsoft Word documents are typically saved as (previously, Word used .doc). 

**Example:**

If you attempted to open a .docx file in a program that doesn’t support Word document formats, you would either get an error message or a scrambled document. 



## Touch
Touch is a command-line interface program for Unix that is used to update date information – such as: changing the date that a file or directory was modified or accessed. Touch can also be used to create or open a file.

**Example:**

You could type “touch dogstory.docx” in the Git command line to create a blank Microsoft Word document entitled “dogstory”.



## Tilde

Tilde is the name for the symbol ~

It is pronounced “tilda.”

**Example:**

The tilde (~) is placed over certain letters in some Spanish words as an accent, such as the word
: señor.



## Command-line Option
A command-line option (also known as an option, flag or switch ) modifies the operation of a command.

In many CLIs, these options are written by typing a hyphen, followed by the desired option (called a switch ).

**Example:**

the command “ls” tells the computer to list the files in the current directory. Adding the switch “-lS” will modify the command so that the list of files is sorted from largest file size to smallest. The full command (command plus the command-line option) would look like this:

> `ls -lS`



## Working Directory
Working directory (also called current working directory [CWD], current directory and working tree) is the directory you are currently working in as a developer.

**Example:**

In the following file path, the working directory would be “Docs”

> `C:\Windows\Docs\Letter.docx`



## Parse
Parse means to break something up into its parts and analyze it.

**Example:**

If you write code for a web site, the web server parses the code and then outputs the correct HTML code to the browser.

Parsing can also refer to breaking up ordinary text.

For example, search engines typically parse search phrases entered by users so that they can more accurately search for each word.



## Case-Sensitive
As a reminder, case-sensitive refers to a programming language where capital and lowercase letters affect the syntax. Some languages allow you to write code with no attention given to capitalization or lowercase letters, while others won’t operate unless you write the code exactly.

**Example:**

Python is a case-sensitive programming language.

In Python, the following code would print "Hello, World!" on the screen.

> `print("Hello, World!")`

But if you wrote your code as follows, there would be a syntax error and the text wouldn’t be displayed. This is because, in Python, the print command does not begin with a capital P

> `Print("Hello, World!")`

While Git is not a programming language, git commands are case sensitive.



## Hash
Hash is an operation that converts one value to another. It is usually used to mask data with different data.

**Example:**
    
The original file name could be orangepants.docx and the hash could be absdfmoijgfsdnsadf. Both would point to the file.



## Staging
Staging is the step prior to the commit process in Git.

A staged file means that you have marked the file to be included in your next commit.

Staging is basically a loading dock where you can determine which changes you will commit. You can perform actions in the staging area, such as temporarily storing your changes.



## Tracked File
Tracked files are the files that were last saved. They are files that Git “knows” about.

Untracked files are everything else – any files in your working directory that were not saved and are not in your staging area.



## Branching
When you use the command “git init,” the current location within your file system will be assigned as a local git repository. So you will want to be sure to use this command with a project folder you have created specifically for your project files.

If you have created and initialized the “myRepository” project folder while you were following along with this tutorial series, then this is your project folder.

In the next video, we will create and initialize another Git project folder and name it “myProjects” just as a review. You should not actually need to create and initialize multiple folders as local Git repositories, this was just a review so that you would have more practice with the process.



## Using GitHub
Later on in your boot camp, you will be adding various code and projects to GitHub, which is why the Version Control Course comes before the main coding courses on the program. 

One of the primary benefits of maintaining a GitHub profile is to create a sort of development portfolio for yourself that other developers and potential employers can view. Though it’s not common, some Tech Academy graduates have even been offered employment opportunities by people who happened upon their GitHub profile. It is wise to list one’s GitHub profile on their résumé.

Remember: Always keep your Github folders and projects organized. This will prevent the headache of having to organize everything later down the line when you're preparing to present your work to a potential employer.

## Underscores and Spaces
The underscore symbol “_” is a short horizontal line.

Occasionally you’ll see file names with underscores in them, like:

>Bird_Picture_1.jpg

It is a common practice of developers to use `_` (underscores) and `-` (dashes) to represent spaces in file names. Why is that? Here are some reasons:

1. In some original command-line interfaces, spaces were represented by underscores or dashes. Some CLIs and operating systems wouldn’t even allow the use of spaces in file names and doing so would cause errors.
2. In URLs, spaces are represented with the characters “%20.” This is because the space character is character number 20 in the ASCII character encoding system. Using underscores or hyphens can result in a cleaner address. For example, learncodinganywhere.com/the-tech-academy is more visually appealing than learncodinganywhere.com/the%20tech%20academy.
And so, some use underscores or hyphens instead of spaces because spaces can occasionally cause issues due to how they affect the appearance of URLs.

While underscores or hyphens are not always required, they’ve become common in the tech industry.

## Character Encoding
Character encoding is a system where numbers, letters, etc. are represented by codes. The codes used are in a form that computers can easily understand. The system used for each type of code depends on how that code is going to be used.

#### Example
    The letter “A” could be represented by the code “65.”

Usually, the actual codes for a letter, number, etc. are in binary. Every letter or symbol has a unique number so that the computer knows what letter or symbol you mean, and this is called character encoding.

#### Example
    The letter “B” might have 1000010 as its character encoding.

## Character Sets
In HTML (and all coding) you will be dealing with *characters*.

In the written form of a language, a character is a written symbol that represents one of the various parts of that language – the various letters, punctuation marks and symbols that are used to lay out that language in written form.

As an example, the English sentence “Speed limit 65 MPH!” makes use of upper-case letters such as “S” and “M,” lower-case letters such as “p” and “t,” punctuation marks such as “ ” (a space between characters) and “!,” and the numbers “6” and “5.”

Character sets are fixed collections of these various symbols, usually containing all needed symbols for a specific language. If we took the English alphabet as an example, it is a character set containing almost 100 symbols. This includes 26 upper-case letters of the English alphabet, 26 lower-case characters of the English alphabet, the numeric digits 0 through 9, and a collection of punctuation marks.