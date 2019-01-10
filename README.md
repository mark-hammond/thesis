University of Oxford Thesis Template
====================================

A LaTeX thesis template for use at the University of Oxford (and possibly
elsewhere) based on the LaTeX Memoir class.

Authors:

* [Ferdinand van Wyk](https://github.com/ferdinandvanwyk)
* Ian Abel
* [Edmund Highcock](https://github.com/edmundhighcock)

Example theses:

* I. G. Abel: https://ora.ox.ac.uk/objects/uuid:254aa8c8-a68f-401a-8a32-432d26717b25
* E. G. Highcock: https://arxiv.org/abs/1207.4419

Quick-start guide
-----------------

1. Install [LaTeX](https://www.latex-project.org/get/)

2. Build the `main.tex` file. Using the command line, you can do this via the
   `makefile`:

   ```bash
   $ cd /path/to/thesis
   $ make clean; make
   ```

Customization
-------------

1. Fill your personal information in `metadata.tex`
2. Package importing and related setting are in `main.tex`
3. Layout settings are in `oxfordthesis.sty`
4. Change university logo in `oxfordthesis.sty` (search for `graphics/oxlogo`)
5. Place useful macros in `macros.tex`


