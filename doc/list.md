npm-ls(1) -- List installed packages
======================================

## SYNOPSIS

    npm list
    npm ls
    npm la
    npm ll

## DESCRIPTION

This command will print to stdout all the versions of packages that are
installed, as well as their dependencies, in a tree-structure.

It does not take arguments.

It will print out extraneous, missing, and invalid packages.

When run as `ll` or `la`, it shows extended information by default.

## CONFIGURATION

### long

* Default: false
* Type: Boolean

Show extended information.

### parseable

* Default: false
* Type: Boolean

Show parseable output instead of tree view.
