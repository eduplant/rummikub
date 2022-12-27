# rummikub

A printable reference of family Rummikub rules typeset with LaTeX

## Current Edition

The current edition of the rules is available under
[Releases](https://github.com/eduplant/rummikub/releases). Similar to [Semantic
Versioning](https://semver.org), major edition numbers indicate substantive
changes to the rules over previous editions. Minor edition numbers indicate that
the edition only contains cosmetic layout changes and changes to typographic
errors.

## Dependencies

Building the PDF depends on `pdflatex` and a number of LaTeX packages. The
required LaTeX packages are usually included with most LaTeX distributions, but
for completeness they are listed here:

* `caption`
* `geometry`
* `multicol`

## Re-building the PDF

1. Clone the repository (using `git clone` or the method of your choice).
2. Edit the file in the text editor of your choice.
3. Run `pdflatex rummikub-rules.tex` to generate `rummikub-rules.pdf`.

By default, the `.gitignore` will filter `.pdf`, `.log`, and `.aux` files that
are produced by `pdflatex` to prevent their accidental inclusion in the
repository.
