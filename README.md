Artistic Style
==============
Artistic Style is a source code indenter, formatter, and beautifier for the C, C++, C# and Java programming languages.

When indenting source code, we as programmers have a tendency to use both spaces and tab characters to create the wanted indentation. Moreover, some editors by default insert spaces instead of tabs when pressing the tab key, and other editors (Emacs for example) have the ability to "pretty up" lines by automatically setting up the white space before the code on the line, possibly inserting spaces in a code that up to now used only tabs for indentation.

Since the NUMBER of space characters showed on screen for each tab character in the source code changes between editors (unless the user sets up the number to his liking...), one of the standard problems programmers are facing when moving from one editor to another is that code containing both spaces and tabs that was up to now perfectly indented, suddenly becomes a mess to look at when changing to another editor. Even if you as a programmer take care to ONLY use spaces or tabs, looking at other people's source code can still be problematic.

To address this problem, Artistic Style was created – a filter written in C++ that automatically re-indents and re-formats C / C++ / C# / Java source files. It can be used from a command line, or it can be incorporated as classes in another C++ program.

http://astyle.sourceforge.net/

This repository contains build instructions (in form of bash scripts) and patches applied to build the version shipped together with the Arduino IDE, where Artistic Style is used when the user presses CTRL-T or clicks on menu Tools -> Auto Format
