gui-app
=======

A template GUI application

# How To Install

1. [Set your PATH environment variable](https://github.com/racket/racket/wiki/Set-your-PATH-environment-variable) 
so you can use `raco` and other Racket command line functions.
2. either look for `from-template` in the DrRacket menu **File|Package Manager**, or run the `raco` command:
```bash
raco pkg install from-template
```
3. 
```bash
raco new gui-app <destination-dir>
```
If you omit `<destination-dir>`, the command will add copy the template to a folder called `gui-app` in the current folder.

# How to use

This is working example that you can change to suit your needs.

For more guidance see https://docs.racket-lang.org/gui/index.html

Other examples of GUI apps are the 7GUI benchmarks and the games collection included in the Racket distribution 

https://github.com/mfelleisen/7GUI

https://github.com/racket/games

To create an executable see https://docs.racket-lang.org/raco/exe.html

To share stand-alone executables see https://docs.racket-lang.org/raco/exe-dist.html


This code is a modernised version of the code for the paper
Programming Languages as Operating Systems (1999)
https://www2.ccs.neu.edu/racket/pubs/icfp99-ffkf.pdf
It is provided with permission of author Matthew Flatt

