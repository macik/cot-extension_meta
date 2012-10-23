Cotonti Extensions META info
============================

This project intend to develop some kind of [Cotonti][] Extension 
developers style guide.

Preface
-------

As further development plans includes creation of unified Extension repository for [Cotonti] we
need, first of all, makes development standards. And improve current quality of 
code (mainly Extensions code) to meet this standard as a second step. 
Due to Cotonti wide development and grown improvements many Extensions become obsolete very fast
and we need to track it compatibiliti with Cotonti itself and each other.


Aims of project
---------------

The main aim is to create unified rules for [Cotonti][] developers to help making good and reliable
code. The base orientation is Extension and Modules code. 
The basic rules and documentation for development is described in [part 3][doc3] and [part 4][doc4] of [Cotonti][] 
documentation plan and must be used as basis.
But we must go deeper - to unify all Extensions (plugins) for further use in repository.
It intends some meta information for Extensions that may:

* describe it 
	* breif description
	* install notes
	* how-to's
	* screenshots 
	* Author name and links
	* links to source code or download source
* allow to add l10n of descriptions
* specify dependencies
	* for Cotonti extensions and modules
	* for external libs and plugins, such as jQueryUI, underscore, require.js, etc
* compatibility info for Cotonti versions 
* optionally changelogs 
 

What benefits does it reveal?
-----------------------------

First of all, it makes Extensions more accessible and easy-to-use for end user. There would be no 
need to download to try, then asking on forum for how-to, then throw out due versions 
incompatibility. 
User must be allowed to easy search, getting full extension info and «one click» installs it.

The second reason for meta information is to simplify manage of extensions within expected repository.

What we need to do?
-------------------

* specify types range and classes for storing information
* define methods to store this information within Extension bundle
* define types for storing bundles (achives/git repositories/something else)
* define formats for storing certain kind of information (for descriptions, for DEPS, for l10n, etc)


Current progress
----------------

Here you can find links to different parts of proposed standard:

* [README.example.md](https://github.com/macik/cot-extension_meta/blob/master/README.example.md) — example of Extension main desctiption file.
* [versions.example.md](https://github.com/macik/cot-extension_meta/blob/master/versions.example.md) — example of Extension change log file

Docs translation
----------------

Any translated versions of this documentation you can find in `lang` folder within this 
repository. As example:

* [`README.md` in russian](https://github.com/macik/cot-extension_meta/blob/master/lang/ru/README_ru.md)


[Cotonti]: http://www.cotonti.com "Cotonti.com"
[doc3]: http://www.cotonti.com/docs/ext/ "Extending Cotonti"
[doc4]: http://www.cotonti.com/docs/devel/ "Developer Guide"

