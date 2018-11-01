# FindAndReplaceMod
Project Description

An open source tool to find and replace text in multiple files.

Features

    Single file download - fnr.exe (181kb)
    Replace text in multiple files using windows application or through command line
    Find Only to see where matches are found
    Case-sensitive searching
    Searching for files in one directory or recursing sub-directories
    Regular expressions
    Find and replace multi-line text
    Generate command line button to create command line text to put in batch file
    Command line help
    Unit tests of Find/Replace engine

 
Screenshots

For screenshots I used a common scenario of replacing a ConnectionString in all ConnectionStrings.config in the solution when rolling from staging to production.

Screenshot 1: Finding all occurrences of connection string.

FnR_Screenshot1_Find.png


Screenshot 2: Replacing all occurrences of connection string.

FnR_Screenshot2_Replace.png

Screenshot 3: Generating command line text to run "Replace" using batch file

FnR_Screenshot3_GenerateCommandLine.png


Screenshot 4: Viewing command line options

FnR_Screenshot4_CommandLineHelp.png


Screenshot 5: Finding occurrences using command line.

FnR_Screenshot5_Find_CommandLine.png


Screenshot 6: Replacing occurrences using command line.

FnR_Screenshot6_Replace_CommandLine.png
Background

A couple of months ago I set out to find a simple find and replace tool that I could use when rolling out my projects. For ex. to change various settings in config files to support dev/qa/prod environment.

I was looking for something that would have the following features:

    Simple UI to make sure that find/replace does what I need it to
    Command line to run find/replace using batch file.



There are many tools available, but they all have the following major issues:

    Out of date, no updates support for at least a year

for ex. http://www.divlocsoft.com/

    Bad documentation if any. Many apps mentions that they have command line support, but to find out how it works takes too much effort.

    Too many features. I just need to type in a couple of fields and click on Run, not to learn a new language.

for ex.
http://www.powergrep.com/
grep/sed variants in windows

    No access to code. Many tools have 90% of what I need, but if I need just a bit more (support for multi-line) - there is not much I can do.


So I wrote a simple tool to use in my own projects and wanted to share it with others.


Shameless plug for my company: http://www.entechsolutions.com
