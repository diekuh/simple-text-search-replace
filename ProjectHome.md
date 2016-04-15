This is a single component, single class project, with the aim to solve one problem: search file system files for strings, and replace them with something else if required. It can search within archives recognized by java (zip), and replace within the zip(jar, etc... ) files, so be careful how you run it!
Story: back then in 2001, there was no fast java based file system search components available, and I needed one for a functionality. It's quite fast, I was comparing it to the file text search of total commander, and it compares reasonably well.
One more thing: the code is very packed, partially to be as fast as possible, partially because I was a complete newbie when I wrote it.

This is how to use it:
- download the code Search.java
in command line
>javac Search.java
then run
>java Search
to get the how to use doc