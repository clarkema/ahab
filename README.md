# Ahab

Ahab is a place to hold small conveniences to make life with Docker more comfortable.

For now, it offers only one command; `docker-tags`.  This provides an easy way to list all the tags of a given Docker repository from the command-line.  For example:

```
$ docker-tags ubuntu | tail

yakkety-20170704
zesty
zesty-20161129.1
zesty-20161212
zesty-20170118
zesty-20170224
zesty-20170411
zesty-20170517.1
zesty-20170619
zesty-20170703
```
## Installation

`docker-tags` is a Perl 6 script.  To run it:

 1. Install `rakudo-star` from your package manager — at least version 2017.07.
 2. Once you can successfully run `perl6 --version`, run `$ zef install WWW` to install Perl 6’s `WWW` module.
 3. Profit!
