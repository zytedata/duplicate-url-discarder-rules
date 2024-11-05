Changes
=======

YYYY.MM.DD (YYYY-MM-DD)
-----------------------

* Added Python 3.13 support.
* Dropped Python 3.8 support.
* Added rules for article websites.
* Rules for ``queryRemoval`` got 7 new domains and 5 existing domains have
  new parameters that were added.
* Added ``RULE_PATHS_COMMON``, ``RULE_PATHS_ARTICLE`` and
  ``RULE_PATHS_PRODUCT`` variables that can be used instead of ``RULE_PATHS``
  to omit some sets of rules.
* Added ``pre-commit`` and improved CI.

2024.10.10 (2024-10-10)
-----------------------

* Rules for ``queryRemoval`` got 5 new domains and 6 existing domains have
  new parameters that were added.
* Versioning has switched to Calendar Versioning (CalVer) which follows the
  ``YYYY.MM.DD`` format, representing the package release date.

0.3.0 (2024-09-18)
------------------

* Rules for ``queryRemoval`` got 10 new domains and 18 existing domains have
  new parameters that were added.

0.2.0 (2024-08-09)
------------------

* Add new rules for:

  * ``normalizer``: For all domains
  * ``queryRemoval``: New domains and updated params on some old domains
  * ``subpathRemoval``: For Amazon domains

* Fix missing Amazon domains in some of its URL patterns.

0.1.1 (2024-07-05)
------------------

* Add ``py.typed`` marker file.
* Add type annotation for ``RULE_PATHS``.

0.1.0 (2024-07-04)
------------------

* Initial Release
