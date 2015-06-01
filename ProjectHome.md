# OCaml syntax highlighting for GNU Enscript #

This highlighting definition module adds support for syntax highlighting Objective Caml code using GNU Enscript.

## Installation ##
  1. Get the source from the [Subversion repository](http://code.google.com/p/ocaml-enscript/source/checkout)
  1. Copy the .st files to your `~/.enscript` directory.

Alternatively, you can copy the files to /usr/share/enscript/hl if you wish to make it available for all GNU Enscript users on your machine. The location depends on where you've installed GNU Enscript.

## Examples ##
### HTML using default style ###

`enscript -w html -Eocaml --color -p output.html < test.ml`

(View HTML output [test.ml.html](http://ocaml-enscript.googlecode.com/svn/trunk/html/test.ml.html))

### HTML using modest style ###

`enscript -w html --style=modest -Eocaml --color -p output.html < test.ml`

### PostScript ###

`enscript -Eocaml --color -p output.ps < test.ml`

### RTF output ###
RTF output can be convenient for embedding code in MS Word PowerPoint.

`enscript -w rtf -Eocaml --color -p foo.rtf < test.ml`