# Version Control Basics
This is my rough understanding and explaination of Version Control

[What is Version Control?](https://www.youtube.com/watch?v=1WZmtcllipI)

[Version Control Systems Explained Simply for Begineers](https://www.youtube.com/watch?v=asmnE5PWD60)


### Index
- [Branches](#branches)
- [Source Code](#source-code)
- [Version Control](#version-control)
- [Git](#git)
- [GitHub](#github)
- [Software Suite](#software-suite)
- [Repository](#repository)
- [Project](#project)
- [Version Control Systems](#version-control-systems)
- [Checking In and Out](#checking-in-and-checking-out)
- [Staging](#staging)
- [Tracked File](#tracked-file)
- [Branching](#branching)
- [Using Github](#using-github)
- [Creating Branches](#creating-branches)
- [Sub Branches](#sub-branches)
- [VCS Software](#vcs-software)
- [Merges](#merges)
- [Network Backbone](#network-backbone)
- [Overhead](#overhead)
- [Iteration](#iteration)
- [Shell](#shell)
- [Version Control Systems Enabling Collaborations](#version-control-systems---enabling-collaborations)
- [Linux](#linux)
- [Elements of a good README](#elements-of-a-good-readme)



## Branches
[Back](#)

A branch is a duplication of code or a portion of it, so that changes can be made to it without affecting the original code.

The purpose of branching is to allow a developer to edit a copy of the code without affecting the original code. Typically the developer later “merges” the branch – which means they integrate their edited code back into the original code.

This is as opposed to simply editing the original version of the code.

One of the benefits of branching is that it allows one to explore a different approach to solving a computing problem through writing code, while not stopping development work on the original code.
	
The original branch containing the original master file is referred to as the “Main Branch” while any additional branches are considered “Sub Branches.” As a note: these main branches were previously called master branches.

Sub branches can be merged into the main branch or another sub branch.

When a developer adds their latest change (i.e., newest version of their code) to the main repository, this is called a commit or merge commit. Committing code means you are putting your changes into the main body of code.

**Example:**
	
If a developer wanted to explore an alternate method for sorting a large collection of financial records, they could create a branch of the original code and work on that alternative sorting approach while they, or other developers, continued to do other work on the original code. Then, when they had perfected the new approach to sorting the data, they could merge the changes they made back into the original code, which now had additional functions due to the continued work on that original code.


## Source Code
[Back](#)



As a reminder, source code is the set of computer instructions that make up a computer program, in such a form that a computer programmer can modify the instructions.

Source code is the version of a computer program as it is originally written (i.e., typed into a computer in a programming language) by the designer of the program. 

Normally, when the programmer is done making the program, he has the computer convert the code he wrote the program in (the “source code”) to another format that is easier and faster for the computer to use. 

In that new format, the program can't be easily understood by people – but it is very useful to the computer. 

It also can't be modified by other developers at that point.


## Version Control
[Back](#)



Version control (also called source control or revision control ) is the tools and processes that are used to manage multiple versions of computer files as the files change over time.

A version control system, or VCS, provides two primary data management capabilities. It allows users to:	
1. lock files so they can only be edited by one person at a time, and
2. track changes to files.

When you create things using your computer you often revise them over time. This can mean the creation of documents, graphic images, computer programs and other items. Keeping track of the changes to these items over time is called “version control.” It also includes the control of changes to items like this when more than one person can make changes to the items.

A version is an exact snapshot of something at a specific point in time. If you wrote a song, that would be Version 1. 

If you later added bagpipes over the top of the song, that would be Version 2. Version control is managing different versions of things on a computer. 

This is used a lot when you are creating computer programs.

**Example:**

If a team of writers were preparing a large textbook, and each writer could add, edit and remove content to the textbook at any time, they would find a version control system valuable to keep track of all changes as the textbook was written.


## Git
[Back](#)



Git is a specific example of version control. It is a popular version control system. You can use Git to manage the versions of your computer programs and work on programs in conjunction with other developers.

Git is itself a computer program. A computer programmer can install the Git program on their computers, and then use that program while creating software and websites.

**Example:**

Git is free software, and is used by millions of computer programmers around the world.


## GitHub
[Back](#)



GitHub is a popular web site owned by Microsoft. It can be used to store source code, accomplish version control on that source code, track defects in that source code and manage work tasks for the computer programmers working on that source code.

**Example:**

GitHub is the largest host of source code in the world.


## Software Suite
[Back](#)



A software suite is a collection of computer programs that typically perform similar functions. These computer programs usually share a similar user interface.

**Example:**

One of the most popular software suites is Microsoft Office 365. It includes several programs, including Word and Excel.


## Repository
[Back](#)




As a reminder, a repository is the main location where data can be kept and handled. It is the central location where code for a particular program is stored.

**Example:**

GitHub is an online code repository.


## Project
[Back](#)



A project is an undertaking that typically has exact requirements and specifications. Projects are usually created following a plan.

Within code editors (programs that developers use to write their code) websites and programs are typically saved as projects.

**Example:**

If you were creating a portfolio website to showcase your accomplishments as a developer, the code for this site would be referred to as, and saved as, a project.


## Version Control Systems
[Back](#)



In this course you will learn about various Version Control Systems (VCSs).

A VCS is a specialized software suite that is used to maintain and track multiple versions of project files, also known as "source control" or "revision control.”

VCSs consists of a repository where all of the project files are stored. This repository may be stored on the user’s hard drive. Whenever this is so, these files are considered to be on a “LOCAL” repository.

The original project files that are stored on another server’s hard drive (such as online storage) so that others can also access the files are considered to be on a “REMOTE” repository.


## Checking In and Checking Out
[Back](#)



While a team of developers are working on a project together, it is important that no two team members are editing the same content at the same time. If this happens, it is possible for one person to accidentally overwrite the changes made by someone else. For this reason, version control allows users to “check out” files for editing.

When a file has been checked out from a shared file server, it cannot be edited by other users. When the developer finishes editing the file, he can save the changes and “check in” the file, effectively releasing that file so that other team members can edit the file once more.

As a reminder, “checking in” code refers to adding the changes you made to a set of computer code into the code that is being managed by a version control system.

Conversely, “checking out” code means marking a certain part of the code that is being managed by a version control system as being subject to modification. That section of code can then be managed by the version control system in such a manner that the system acts to prevent conflicts that could be caused if another person wanted to work on that exact same section of code simultaneously to you working on it.

Checking in is sometimes referred to as “committing” code.

**Example:**

If you were working with a team of two other developers on a computer program that tracked the students in a school, and you wanted to work on the part of the code that calculated grade point averages, you might “check out” that section of code. The version control system would then mark that section of code in some way, and could notify the other two developers that the section of code has been checked out should they attempt to change it.



## Staging
[Back](#)

Staging is the step prior to the commit process in Git.

A staged file means that you have marked the file to be included in your next commit.

Staging is basically a loading dock where you can determine which changes you will commit. You can perform actions in the staging area, such as temporarily storing your changes.



## Tracked File
[Back](#)

Tracked files are the files that were last saved. They are files that Git “knows” about.

Untracked files are everything else – any files in your working directory that were not saved and are not in your staging area.



## Branching
[Back](#)

When you use the command `git init`, the current location within your file system will be assigned as a local git repository. So you will want to be sure to use this command with a project folder you have created specifically for your project files.

If you have created and initialized the “myRepository” project folder while you were following along with this tutorial series, then this is your project folder.

In the next video, we will create and initialize another Git project folder and name it “myProjects” just as a review. You should not actually need to create and initialize multiple folders as local Git repositories, this was just a review so that you would have more practice with the process.



## Using GitHub
[Back](#)

Later on in your boot camp, you will be adding various code and projects to GitHub, which is why the Version Control Course comes before the main coding courses on the program. 

One of the primary benefits of maintaining a GitHub profile is to create a sort of development portfolio for yourself that other developers and potential employers can view. Though it’s not common, some Tech Academy graduates have even been offered employment opportunities by people who happened upon their GitHub profile. It is wise to list one’s GitHub profile on their résumé.

Remember: Always keep your Github folders and projects organized. This will prevent the headache of having to organize everything later down the line when you're preparing to present your work to a potential employer.


## Creating Branches
[Back](#)



A typical business scenario for a team of developers working together on a particular project would be for the main project files, known as “MASTER” or “MAIN” repository files to be cloned (copied) to a developer’s local hard drive so that they may work with these files whether they are connected to the remote hard drive or not. Before a developer will make any changes to their copied files, they typically will make a new “BRANCH” of all the copied files in the local repository.

This creates all new versions of the original copied repository files. Essentially, these may be thought of as new instances of the files. Developers make new branches of the project files so that any new changes are not actually affecting the original state of these files on the original branch.


## Sub Branches
[Back](#)



After the developer has created a sub-branch which is named uniquely from the main branch to ensure differentiation, the files may be altered and improved. In a version control system, each file in the local repository will have an associated file history attached to it. This history is updated with a short description and timestamp each and every time the file undergoes changes in which the developer has committed these changes to their local repository. If the developer feels there are mistakes in a particular file, they may pick a save point on the file’s history timeline and revert this file back to the condition as it was at that exact moment of time.


## VCS Software
[Back](#)



A file on one particular branch may be modified and thus it will contain different data than that very same file on another branch since they are no longer on the same plane of reality. Think about those popular science fiction novels or films concerning time travel. The time traveler may have gone back to a special point in time and made an alteration but the new future is not the previous future to the time traveler anymore as there was a new branch in time generated as soon as the time traveler had made their alteration in the timeline. Every successive change they may make will also make new branches in their reality accordingly.

Luckily for developers, the VCS software will remember each and every change for them and associate a brief but concise description, explaining each change made so that all the developer has to do is read through these brief descriptions to help them determine the point in time they would like to revert the file back to.


## Merges
[Back](#)



As was mentioned earlier, merging is the action of combining various versions of a file or folder. It means to combine changes in files that exist in two or more different locations (or being handled by two or more developers). It is combining changes in data.

**Example:**

If a developer wanted to explore an alternate method for sorting a large collection of financial records, they could create a branch (a duplication of code or a portion of it, so that changes can be made to it without affecting the original code) of the original code and work on that alternative sorting approach while they, or other developers, continued to do other work on the original code. Then, when they had perfected the new approach to sorting the data, they could merge the changes they made back into the original code, which now had additional functions due to the continued work on that original code.

When the two sets of code do not merge properly, this is referred to as a “merge conflict.” For an example: If you attempt to merge code stored on your laptop with source code elsewhere, but someone had made changes to the exact section of the code you had been working on, you might have a merge conflict.


## Network Backbone
[Back](#)



A backbone is a part of a computer network that interconnects various pieces of a network, providing a path for the exchange of information between different subnetworks.

This is part of a computer network that connects various sections of the network. It provides a path for information exchange between the various networks integrated into it.

It is essentially a “senior” network containing a high capacity connection that forms the main link to various “junior” networks.

**Example:**

If several offices were connected to a network, the network backbone would be the main link connecting all of the offices. If this connection was a wireless connection, one would say, “Our company uses a wireless network backbone.”


## Overhead
[Back](#)



Overhead literally means “the cost associated with something.” In running a business, overhead includes rent cost, marketing expenses and payroll.

In computers, overhead refers to the amount of work required of the computer to perform an action (such as running certain software). Overhead includes how much bandwidth is utilized, how much processing power is required, the amount of memory taken up, etc. by a particular website, program, etc.

**Example:**

Microsoft Word takes more overhead than Notepad.


## Iteration
[Back](#)



As a reminder, to iterate means to say or do something again; to repeat something.

An iteration is the act of repeating. Iteration means to go through a defined series of actions, repeating a certain number of times. Usually this defined series of actions is repeated a certain number of times, or until a condition is met.

**Example:**

Computer programs are usually created in iterations: Coming up with a basic working version, reviewing the program for mistakes to correct and improvements to make, doing that work, and repeating. This can be continued indefinitely.


## Shell
[Back](#)



As a reminder, a shell is a type of program that provides a user interface between the user and the operating system. You can use the shell to locate files, start and stop other programs, etc.

Some shells provide a graphical interface, where visual objects on the screen are used to represent the files and programs on the computer. Other shells provide a text-only interface.

**Example:**

You might use a shell to look at all the files in one section of your computer.


## Version Control Systems - Enabling Collaborations
[Back](#)



A Version Control System also makes team development possible, even with remote team members. With a centralized “repository” of document changes, developers can easily download the “latest” version and edit it. Once done, they just “check it in” to this main repository for the other team members to view and edit.

Of course, having two developers work on the same document can cause problems. Version Control Systems utilize two distinct methods for enabling this type of collaboration. The first solution is to enable a developer to “lock” a file being edited. In other words, while the file is being edited, no other team member can edit it. Others can download it and view it, but none can make changes.

The obvious problem with this solution is it slows development. Some programs have one file that is bigger and heavier trafficked than others. To stop production while one developer edits it seems a waste. Also, as has happened, what if the developer forgets to unlock the file or takes a long weekend?

This is solved by the copy-modify-merge method. Any number of developers can download a file and edit it. When sending the edited file back to the server, the server checks if the file being sent is “up-to-date” with any changes that were sent before it. If it’s “out-of-date”, the server shows the developer which changes were made and forces the developer to integrate those changes into the current document. Usually developers aren’t working on the same portion of the same document, so these are typically easy to integrate.

The VCS known as Git, utilized through the GitHub interface, follows the copy-modify-merge method and has made it possible for software development to occur amongst hundreds of developers simultaneously. It has opened the door to “open-source software development” projects that have helped revolutionize the world of technology.

## Fork
[Back](#)



A fork is a copy of a repository. You can fork a repository and make changes to it without affecting the original project. Forks are commonly used to recommend changes to projects belonging to someone else or to utilize someone else’s project as a starting point for your own.


## Linux
[Back](#)



**Unix:** 

Unix is built on the idea of the server being able to handle multiple client requests at the same time.



## Elements of a Good README
[Back](#)



A good README consists of a few important elements, for example:
| Name | Description |
| ----- | ------|
| Titles | Names of important sections within the README |
| Introduction | The project's aim | 
| Technologies | List of languages used |
| Launch | Version of languages used for reproducibility | 

And depending on the scope of the project, they will also contain:

| Name | Description |
| ---- | -------- |
| Table of contents | Contains links to the main sections of the README. |
| Illustrations | Pictures of code that help show what was created. | 
| Scope of functionalities | What the program is capable of. |
| Examples of use | What it can be used for. |
| Project status | What stage of development the project is at. |
| Sources | List of sources for the project. |
| Other information | Author and contact information, social media links, and licenses. |

Each of these concepts will be explained further in the next pages.

### Title
[Back](#)



The title should clearly explain what the repository is about. It should be the name of the project and typically uses a heading tag. In markdown a hashtag is used to make a heading. It may also include titles of certain project sections as well.

### Introduction/Summary
[Back](#)



The introduction is a summary of what the project is about. It should not be too long, about two or three sentences will do for a small project.

Here is an example of a title with a table of contents containing the important titles of each part of the project.

### Technologies
[Back](#)



This section explains which languages were used in the project, as well as the version of the language that was used. This is good for relaunching a project, as this section will clarify any potential issues a user may run into with certain updates. It is also useful when looking for a job, as it will more clearly showcase what languages the developer has used in various projects, and recruiters will be able to find these keywords on GitHub. Creating well-written and organized READMEs could be the difference between receiving an offer or being passed up.

Overall, the README should be legible and have a simple format that is easy to navigate. Having thorough documentation will make your repositories stand out not just to recruiters, but also for people on your team or others that might want to use the application.
	
### Additional Information on READMEs
[Back](#)



Read these articles regarding GitHub READMEs:
- [About README.md](https://docs.github.com/en/free-pro-team@latest/github/creating-cloning-and-archiving-repositories/about-readmes)			
- [Writing on GitHub Basic Writing & Formatting Syntax](https://docs.github.com/en/free-pro-team@latest/github/writing-on-github/basic-writing-and-formatting-syntax)
