pymorphy3
=========

pymorphy3 is the continuation of the unmaintained project [pymorphy2](https://github.com/kmike/pymorphy2) which is an morphological analyzer (POS tagger + inflection engine) for Russian and Ukrainian languages.

pymorphy3 officially supports Python 3.9 ~ 3.14.

The package ships type hints (PEP 561 `py.typed` marker). An optional
command-line interface is available: install with `pymorphy3[CLI]` extra
and run `pymorphy --help`.


## Updated dictionaries

Updated Russian and Ukrainian dictionary builds for this fork are maintained
separately in [quazar-m/pymorphy3-dicts](https://github.com/quazar-m/pymorphy3-dicts).

The Russian package is built from preserved OpenCorpora source snapshots.
The Ukrainian package is built from VESUM / `dict_uk`, with the exact source
release mirrored as a reproducible snapshot.

These updated dictionary packages are not published to PyPI yet; publication
and dependency pinning will be handled separately.

* Documentation: https://pymorphy3.readthedocs.io
* Bug tracker: https://github.com/no-plagiarism/pymorphy3/issues
* Changelog: https://github.com/no-plagiarism/pymorphy3/blob/master/CHANGES.rst
* License: https://github.com/no-plagiarism/pymorphy3/blob/master/LICENSE.txt
* Contributors: https://github.com/no-plagiarism/pymorphy3/blob/master/AUTHORS.rst
