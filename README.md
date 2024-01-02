# listings-flexpde

This project provides syntax highlighting definitions of the FlexPDE language for the LaTeX [listings package](http://www.ctan.org/tex-archive/macros/latex/contrib/listings/).

## Usage

Copy or link the file `flexpde-listings.cfg` into your LaTeX project and
include it in your main project file.

E.g.:
```tex
\usepackage{listings}
\input{listings-flexpde.cfg}
```
The flexpde `flexpde-listings.cfg` file also provides to new commands,
`\code` and `\flexpde`, in order to inline code examples without and with
Flexpde syntax highlighting, respectively.

By default no background colour is set for the listing.
But the appearance can be modified for example by doing:
```tex
\usepackage{listings}
\input{listings-flexpde.cfg}
\lstset{language = flexpde,
        basicstyle=\fontsize{9pt}{10.5pt}\ttfamily,
        backgroundcolor = \color{green}}
```
## License

&copy; Copyright 2024 Manuel (mgrojo)

Based on previous work for the Modelica language by:

&copy; Copyright 2014 Martin Sj&ouml;lund, Dietmar Winkler

This work may be distributed and/or modified under the
conditions of the [LaTeX Project Public License](LICENSE), either version 1.3
of this license or (at your option) any later version.
The latest version of this license is in
http://www.latex-project.org/lppl.txt
and version 1.3 or later is part of all distributions of LaTeX
version 2005/12/01 or later.

## Contributions

See [list of contributors](../../graphs/contributors).

The list of keywords is probably incomplete. This has been done only to scratch my own itch, so
[Issues](../../issues) or [pull request](../../pulls) are always welcome.
