# Tree drawing tutorial

This handout was developed for University of Maryland's LING 311 class,
in spring 2020, as a tutorial on how to draw trees on the computer.

It is a substantially revised version of a tutorial that [Diogo
Almeida][diogo] originally wrote in fall 2006.

Feel free to fork this repository and open a pull request if you see
ways that these materials could be improved. You're also welcome to open
a GitHub issue.

# Compiling

In order to compile the file `tree-drawing-tutorial.tex`, you
will need to do the following things:

* Install `Pygments`. If you have `pip` installed, you can just do
  `pip install Pygments`. See the [`minted` documentation][minted]
  for more information.
* Compile the file with shell escape enabled. Also see
  the [`minted` documentation][minted] for more information.
* Either change the font that the document uses or download and install
  the Adobe Garamond Pro font on your machine.
* Either change the bibliography style or install *S&P*'s [Biblatex
  implementation of the Unified Stylesheet for Linguistics
  Journals][biblatex-sp-unified].

While not necessary to succesfully compile the document, if you'd like
the `git` information in the footer to be typeset correctly, you will
also need to:

* Install the three required hooks into the `.git/hooks/` directory.
  This can be done via the `install-git-hooks.sh` script on a *nix
  system with `./circle-ci-setup/install-git-hooks.sh`. Then do
  `git checkout master`. (The `git` information for insertion into the
  document is generated anytime a checkout, commit, or merge occurs.)

# History

For a list of changes, see the [changelog][changelog]. For PDFs of older
releases of this document, see the [releases][releases].

# License

<a rel="license"
href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img
alt="Creative Commons License" style="border-width:0"
src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br
/>This work is licensed under a <a rel="license"
href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative
Commons Attribution-NonCommercial-ShareAlike 4.0 International
License</a>.

[diogo]: https://www.diogoalmeida.net/
[minted]: http://texdoc.net/texmf-dist/doc/latex/minted/minted.pdf
[biblatex-sp-unified]: https://github.com/semprag/biblatex-sp-unified/
[changelog]: /CHANGELOG.md
[releases]: https://github.com/adamliter/tree-drawing-tutorial/releases
