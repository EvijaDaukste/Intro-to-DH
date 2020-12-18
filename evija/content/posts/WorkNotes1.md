---
title: "Work in progress notes"
date: 2020-12-17T23:59:45+02:00
draft: true
---

# Work in progress notes

1.
edauk@DESKTOP-KA3PNT6 MINGW64 /c/Hugo/evija/content/posts (master)
$ pandoc Alice_p29.md -o Alice_p29.xml --to=tei

Didn't render to TEI file. opened simple xml file and I had to write all TEI header manually.
I still haven't found the solution for this problem, however, when I did one of the pages
I could understand it a little bit better, and it was going a lot faster with the rest.

2.
In markdown file the note tag did not work, however it was rendered in the xml file as a footnote anyway.

3.
In visual Studio code and Atom it was not possible to add the
footnote tag, but in Dillinger tagging worked. However, I decided not to
switch my text editor and continued working in Atom. I added the footnotes after
converting .md file to .xml files.

4.
Most of the times something didn't work as supposed to in Git Bash, it was because of a typo or incorrect code.
It takes a lot of time and practice to remember the correct Git commands, even more time to find them online.
Another common problem is that in Git Bash, I can't use ctrl+C and ctrl+P for copy and paste, so
on a regular basis I stopped my code by accident, because I kept using those shortcuts on Git Bash.


5.
While tagging the TEI documents, I decided to tag also all the mentioned characters with the tag <character>.
And use a special tag for all the puns <pun>.

6.
There were some issues with installing choco and hugo in Git Bash, so I switched to Windows Powershell
for a moment. There it also didn't really work, after struggling for a while, I realized that
I have to run either Windows Powershell or Git Bash as an administrator to install choco and hugo.
After I did that, everything was working as it should.

7.
