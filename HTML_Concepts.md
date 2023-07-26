# HTML Concepts
In here I'll do my best to explain HTML concepts, keywords and phrases.

[For more on HTML check out my college notes.](https://github.com/mouldimus/Pitman_HTML_CSS)

### Contents
- [Reserved Words and Keywords](#reserved-words-and-keywords)
- [Cache](#cache)
- [Clearing the Cache](#clearing-the-cache)
- [Real Time](#real-time)   
- [Static vs. Dynamic](#static-vs-dynamic)
- [JavaScript](#javascript)
- [AJAX](#ajax)

## Reserved Words and Keywords
[Jump Back](#contents)

In most programming languages, there are certain words you can’t use as variables, labels (names assigned to sections of code), or functions (repeatable blocks of code). These are called reserved words. For example, in the popular programming language Python, `def` (which defines a function) and `if` (which creates an if statement) are reserved words.

The reason you cannot use these words is that they already mean something else – they are reserved for the programming language.

And so, if you were creating a variable in Python, you couldn’t write:
```python
if = 10
```
because `if` already means something in Python.

Reserved words are also called keywords (again, code built into the syntax of a language is the keywords of that language).

## Cache
[Jump Back](#contents)

A cache (pronounced “cash”) is a collection of items stored somewhere for use at a later time. For example, a weapons cache is a place where weapons are kept until they are needed.

In computers, a cache is a set of computer memory where data can be stored for later use. One of the most common uses for a cache in computers relates to situations where there is a significant time delay in acquiring certain data. In order to provide a faster user experience, the computer will store the data in a cache after the first time that data is used in order to avoid having to read the data from a slower device or without having to dig around in the computer to find the information again.

Files that you view from a cache may only take 2 or 3 seconds to display on your screen, while something new could take 30 seconds to be acquired, prepared for display and then displayed.

## Clearing the Cache
[Jump Back](#contents)

Whenever you enter a URL into the browser's address bar, you are making a request to the web server that is hosting the website for a specific file. This file may be an HTML document or a combination of files.

It takes time for the browser to load this content (it often downloads many files in order to reconstruct the webpage). To reduce the load time for future visits, the browser may store some of these pages as snapshots into its memory. This action is called “caching” and each snapshot is called a “cache file.” The next time you visit the same website, your browser may attempt to load up the cached files to reduce the load time. While this is useful for speed, occasionally websites do not display correctly due to corrupted or outdated data in the cache.

You may run a file or visit a site and see errors.

To ensure you’re viewing the correct and newest version of a website, you can clear your cache.

There are different ways to clear the cache, depending on the browser you’re using. Simply Google *“clear cache ______(browser name).”* For Google Chrome, you can click `CTRL+F5`.

This is mentioned here as a troubleshooting tip for web pages that aren’t displaying properly.

## Real Time
[Jump Back](#contents)

*Real time* refers to a transmission of data or signal as soon as it is generated.

This is best illustrated by the concept of watching a sporting event on TV. The cameras at the event are capturing the game play and broadcasting it to televisions around the country.

In one scenario, there is little to no time lag between when an event occurs at the game, and when the viewers at home see that event. This is "real time".

In another scenario, the events of the game are recorded, and then viewed at another time. This can be called "delayed playback". The delay can be a few seconds, an hour, a day or any other length of time.

This applies in any situation where the stream of information that is produced can be accessed as it is produced – that is, in "real time”.

## Static vs. Dynamic
[Jump Back](#contents)

As a reminder, *static* means “rigid; unchanging.”

*Static web sites* are delivered to the browser exactly how they were stored originally on the web server. Static web pages don't change. No matter who is accessing the web site, it looks the same.

Most web sites nowadays are *dynamic*, meaning that the appearance and content of the web pages can be changed on the web server before the web page is sent back to the browser, or it can be changed by the browser on the user’s computer before being displayed on the screen.  

## JavaScript
As a reminder, *JavaScript* is a computer language that is able to work on most computers. It is useful in making websites.

JavaScript is used mainly to make websites more dynamic (describing websites that have content that changes based on user action or other factors, rather than being static in appearance and content). There are many other uses for JavaScript; it is used in the creation of many different types of computer programs.

**Example**
>JavaScript can be used to make videos that start to play as soon as a user moves their mouse over the video.

## AJAX
*AJAX* stands for *Asynchronous JavaScript and XML.*
*Asynchronous* means “broken down into separate pieces/occurrences without a set pattern.”

*XML* is an acronym for *extensible* markup language. This means that computer programmers can create their own document structure, and then use XML to specify markup instructions for the data in those documents.

AJAX is a set of tools that can be used in creating asynchronous functions for web sites.

AJAX is best understood by relating it to the way a normal web page is accessed by a user. With a web browser, a user issues a “request" to see a specific web page. That request is sent to the web server. That server gathers those requested files and sends them to the user's computer as a “response” to the “request,” and the browser then converts them to a visual form and displays them for the user.

If the creator of that web page wants to make it so that some content on the web page can change based on a user action, they have a number of different options.

One method is to just send a new request for the web page, along with an instruction to provide the new content that is desired. This can take a long time, though, as every file needed to display that web page has to be sent back to the user's computer by the web server.

This is where AJAX can come in. Instead of requesting that the entire page be recreated, the creator of the web site can make it so that just the new content is requested from the web server.

The way this works is that user action triggers an asynchronous request to the web server for JUST a specific section of the web page. It is asynchronous in that it is not tied to the full “request” – “response” – “page display” process used for a full web page.

The technologies used to accomplish this feature are JavaScript and XML – hence the name "AJAX,” or `A`synchronous `J`avaScript `A`nd `X`ML.

**Example**
>If you are viewing a web page, AJAX can make it so that when you click on a video, the video is sent over from the server – as opposed to the video and the rest of the entire web page.