# How to use latexmk with TeXShop

## What's this about?

Many features of Gregorio, as well as other features of LaTeX, require two or more passes to be typeset correctly. For example, braces needed for psalms, knowing where
lines break, the heights of lines, the placement of initials, and other features of Gregorio depend on being typeset once, then in their permanent place a second time.
Labels used for cross-references are placed correctly (we hope) after a second run, and so too for indexes, bibligographies, etc. (or more runs). In order to typeset
correctly, `latexmk` by John Collins figures out how many passes to make so that we don't have to remember (and in the Gregorio world, a tiny brace in mode III psalms
that should be over two syllables is a tad embarrassing…)

## Files needed
Place `lualatexmk.engine` in `~/Library/TeXShop/Engines`.

Move it from `~/Library/TeXShop/Engines/Inactive/Latexmk` or add it from this repository as necessary, in case it is missing from your version of the `Inactive/Latexmk`
folders.

It is possible to set magic comments via the TeXShop `Macros > Program` menu. Once the engine file is added under `~/Library/TeXShop/Engines`, it should appear in this
menu without even needing to close and reopen TeXShop.

In `~/Library/TeXShop/bin` there should be a file named `lualatexmkrc`. If not, add it via this repository.

See section 9.4 of the TeXShop manual to learn more about the keyboard shortcuts as another way to use `lualatexmk`. Section 9.6 explains the parameter magic comment
which is useful; you certainly can make an engine file called `selualatexmk.engine` modeled on the `sepdflatexmk.engine` file kept by Herb Schulz and Richard Koch
for backwards compatibility, but it's not necessary with the parament comment.

NB: `~/Library/TeXShop/Engines/Inactive/Latexmk` contains documentation for `latexmk`. Celle-ci est également disponible en langue française !

If you have any problems, Herb Schulz is very helpful troubeleshooting `latexmk` problems for macOS, although some may be my fault (documentation writing is not my strength;
feedback and corrections are welcome.).
