pnaslatex
=========

Unofficial LaTeX class and LyX layout files for PNAS article submissions.

## Introduction
PNAS accepts [LaTeX submissions](http://www.pnas.org/site/authors/LaTex.xhtml) and provides a LaTeX class and style file for this purpose. Unfortunately, it is very hard to use these to produce decent output, with features such as side captions and modern LaTeX features available through Xe-/Lua-LaTeX being unsupported. After quite a bit of hacking, James Manton in the lab gave up on trying to use them and re-engineered an alternative version from scratch to give a much more satisfactory output.

It is important to remember that these files are unofficial and include a few hacks to produce output that is similar to, but not exactly identical, to that produced by the official files. In fact, these files produce output that is closer in appearance to that of a final, PNAS-published article than either of the PNAS-provided LaTeX files or the PNAS online manuscript length checking service.


## LaTeX
Advantages over the official PNAS files include:
 * Side captions via the ``sidecap`` package
 * Bibliographies generated via BibTeX, BibLaTeX, etc., rather than lists of ``\bibitem`` in the LaTeX source
 * Support for native Unicode via compilation with XeLaTeX or LuaLaTeX
 * Easy font configuration
 * Well-documented, simple code, in fewer than 200 lines (cf. > 3300 lines in the official class file)


## LyX


## Installation


## Usage