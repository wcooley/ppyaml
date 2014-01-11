# ppyaml

## Summary

Pretty-print YAML by dumping it in one of several other formats.

## Details

Support the following formats out of the box:
* native Python (pprint)
* JSON
* re-dump as YAML

With the addition of `dicttoxml`, will also dump as a sort of generic XML.
Unfortunately, `dicttoxml` generates non-validating XML if dict keys contain
special characters such as ":".

## TODO

* Find maybe a better XML formatter than `dicttoxml`?
* Properly package for distutils.
* Figure out why two CTRL-Ds seem to be necessary to close standard input.
  Workaround: `cat | ppyaml`.

## Author

* Author: Wil Cooley
* Repository: https://github.com/wcooley/ppyaml

## Copyright and License

Copyright © 2014  Wil Cooley <wcooley&#64;nakedape.cc>


