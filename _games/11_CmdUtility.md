---
layout: game
title: Command Line Utility
blurb: Doing stuff from the terminal.
thumb: cmdutility/terminal.png
screenshots:

    - cmdutility/github_quik.png
    - cmdutility/terminal.png
    - cmdutility/github_template.png

---

Whatever Linux lacks in user friendliness, it compensates in customizability.

I've been really enjoying making small, [Docopt](http://docopt.org/) based terminal
utilities for my personal needs.
So far I'm very satisfied with their level of polish, and usefulness in my every-day activity.

<br>

[Template](https://github.com/mikeevmm/template) --- A utility to create boilerplate projects.
Started out as a LaTeX template utility (and used to be called `latextemplate` ), 
but it was so useful that I promoted it to a general purpose tool. Includes templates for C, 
C++, LaTeX, and Python with C extensions projects, among others.

[Quik](https://github.com/mikeevmm/template) --- Essentially, a bookmark tool for directories in
the terminal. This application evolved from having a million different `alias X="cd X"` in my `bash_aliases` , 
which isn't very recommended anyway. I used some fun tricks to change directory from the parent shell, 
while still writing most of the logic in Python, with Docopt.

[Wellbeing](https://github.com/mikeevmm/template) --- There are a few Windows and Mac apps to remind
you to, e.g., drink water. I wanted something minimal, customizable, and for Linux, which is why
`wellbeing` exists. Although inconspicuous as an app, `wellbeing` actually generates its own Docopt
documentation on the fly, along with some more weird-but-cool stuff like storing a hash of itself to detect
changes. 

---

<br>

* Python (Docopt), Bash
* Linux
