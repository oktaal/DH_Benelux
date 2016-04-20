# DH_Benelux
```
----------------------------------------------------------------------------
dhbenelux.sty -- A small style file for submissions to the DH Benelux 2016
(c) 2016
Version:    0.3
Maintainer: Martin Sievers
Email:      martin.sievers@schoenerpublizieren.de
License:    Released under the LaTeX Project Public License v1.3c or later
See:        http://www.latex-project.org/lppl.txt
----------------------------------------------------------------------------

This is an adoption of the MS Word template made available by the organizers 
of the DH Benelux 2016 in Luxembourg.

To use this LaTeX style file, please copy "dhbenelux.sty" and 
"abstract-template.tex" to a directory. Edit "abstract-template.tex" and call 
"xelatex" on that file (either via the shell or via your editor). Then call 
biber (which is a modern substitute for BibTeX) and "xelatex" again (maybe 
twice). 

```

## Changelog

### 0.2 to 0.3

* Added support for ``hyperref`` package (options ``print`` and ``electronic``)
* Added option ``nobiblatex`` to allow alternative ways for bibliography (BibTeX or own bibliography environment)
* split up files to distribute it via Github

### 0.1 to 0.2

* Incorporated modified guidelines

### 0.1

* First official version submitted to the DH organizers

