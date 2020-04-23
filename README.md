# About
`etrad` (Edit Traduction) is a solution to properly deal with
traductions.

# Expectations

When you traduce and study texts there is three common situations that
you want to deal with:

1. You want to **tag** (annotate) any words in the text to add it some
   informations. For instance, we may want to tell that a word is a
   *verb* and attach it its *definition*.
   
2. You want to **produce an index** that list all the lines where a
   specifique word appears and be able to move between those
   lines. For instance if *bob* is the character of the novel, you
   want to list all the piece of text where *bob* appears.

3. You want a **uniq traduction** for all your text. For instance,
   *bob* and *alice* are two character of a text and you start
   traducing parts of the text where *bob* appears. Next day you start
   traducing parts of the text where *alice* appears, and you have one
   paragraph where *bob* appears too. In that case, If you have
   already traduced piece of the paragraph while working on *bob*
   character, you want to be **notice** about the existing traduction,
   and directly working on this one. You don't want duplication of the
   traduction.

# Motivation

1. Talk with Marc.
2. Think on text editing is amusing and challenging. Think about that:
   working with text is a common task for a long time and we still
   have not a standard and clean way to do it.

# Existing solutions

* [https://www.oxygenxml.com/](oxygenxml)
* Inside `emacs`: see `swiper`, `rgrep` and `etags`.
* Inside `linux`: see `grep`.

# Ideas/Notes

* [emacs](https://www.gnu.org/software/emacs/) is a text editor that can
be modified adding package written in `emacs lisp`.
* Maybe there exists some `emacs` packages that do part of the job.
* The other part could be done writing an `emacs` package.
* I say `emacs` because this is the tool I know more but I'm open to
  any other tools.

# Videos

1. Using swiper & rgrep into emacs: see on [youtube](https://youtu.be/EOAJnIDqWH0).

# License
Project under MIT license
