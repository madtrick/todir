About
=====

This script amins to ease directory switching to frequently used dirs
contained under a common path

###Example

Imagine you have all the repos which contain the code you commonly use under "$HOME/repos".
To easly switch to any of these repos, you could define the following on
your .bashrc:

    to_dir "repos" "$HOME/repos/"

So that from anywhere on your filesystem when you typed "repos" and
hitted `<TAB>` a list of dirs under "$HOME/repos" will  be shown and
made avaliable to autocomplete.

    rp rails/

After hitting enter you'll cd into that dir.

Installation
===========
Source the script into bash

    $. todir

and create the shortcuts on a file that gets sourced into bash

    to_dir "rp" "$HOME/repos/"
