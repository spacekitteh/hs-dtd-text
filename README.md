# dtd-text #

A Haskell library which provides means to parse XML Document Type Declaration (DTD) documents.  This library is meant to be used in concert with [dtd-types](http://hackage.haskell.org/package/dtd-types).  Itself is based around the [xml-types](http://hackage.haskell.org/package/xml-types) package.

This fork initially updates some of the libraries and dependencies.  The following libraries are no longer needed:

- attoparsec-text
- blaze-builder

Upper bounds on all packages, except dtd-types, has been relaxed as this seems to be a general best practice among the Haskell community moving forward.  **dtd-text** also does not have any external library dependencies.

For more basic information please check the [Project](http://projects.haskell.org/dtd/) page.  

## LICENSE ##

**dtd-text** is licensed via [BSD3](https://github.com/m15k/hs-dtd-text/blob/master/license.txt)