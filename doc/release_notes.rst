Release notes
=============

.. roughly following https://sphinx-gallery.github.io/dev/maintainers.html,
.. 1.0.0 notes were generated by:
.. 1. tagging PRs as enhancement/bug/removed
.. 2. $ github_changelog_generator -u numpy -p numpydoc --since-tag=v0.9.2
.. 3. $ pandoc CHANGELOG.md --wrap=none -o release_notes.rst
.. 4. adding a manual addition (CSS note), tweaking heading levels, adding TOC

.. contents:: Page contents
   :local:
   :depth: 2

.. note::

   For release notes (sparsely) kept prior to 1.0.0, look at the `releases page
   on GitHub <https://github.com/numpy/numpydoc/releases>`__.

1.6.0rc2
--------

Release date: 21 August 2023

Requires Python 3.8+ and Sphinx 5+.

1.5.0
-----

Release date: 8 October 2022

Requires Python 3.7+ and Sphinx 4.2+.

`Full Changelog <https://github.com/numpy/numpydoc/compare/v1.4.0...v1.5.0>`__

Fixed bugs
~~~~~~~~~~

-  Parsing ``returns`` section with several types and no name `#428 <https://github.com/numpy/numpydoc/issues/428>`__
-  BUG: Fix returns parsing no name `#429 <https://github.com/numpy/numpydoc/pull/429>`__ (`rossbar <https://github.com/rossbar>`__)

Closed issues
~~~~~~~~~~~~~

-  readthedocs build failing `#439 <https://github.com/numpy/numpydoc/issues/439>`__
-  Exclude class properties from being listed under METHODS section `#339 <https://github.com/numpy/numpydoc/issues/339>`__
-  BUG: Numpydoc doesn’t render attributes decorated with ``cached\_property`` in the Attributes section `#432 <https://github.com/numpy/numpydoc/issues/432>`__
-  Is numpydoc_use_blockquotes deprecated or not yet? `#420 <https://github.com/numpy/numpydoc/issues/420>`__
-  No light theme available in docs `#413 <https://github.com/numpy/numpydoc/issues/413>`__
-  1.4.0 release plan `#408 <https://github.com/numpy/numpydoc/issues/408>`__

Merged pull requests
~~~~~~~~~~~~~~~~~~~~

-  Update doc requirements `#441 <https://github.com/numpy/numpydoc/pull/441>`__ (`jarrodmillman <https://github.com/jarrodmillman>`__)
-  Update pydata-sphinx-theme `#440 <https://github.com/numpy/numpydoc/pull/440>`__ (`jarrodmillman <https://github.com/jarrodmillman>`__)
-  Support Python 3.11 `#438 <https://github.com/numpy/numpydoc/pull/438>`__ (`jarrodmillman <https://github.com/jarrodmillman>`__)
-  Update precommit hooks `#437 <https://github.com/numpy/numpydoc/pull/437>`__ (`jarrodmillman <https://github.com/jarrodmillman>`__)
-  Use Python 3.10 to build docs `#436 <https://github.com/numpy/numpydoc/pull/436>`__ (`jarrodmillman <https://github.com/jarrodmillman>`__)
-  Use `requirements/*.txt` files for CI `#435 <https://github.com/numpy/numpydoc/pull/435>`__ (`jarrodmillman <https://github.com/jarrodmillman>`__)
-  Fix front page `#434 <https://github.com/numpy/numpydoc/pull/434>`__ (`jarrodmillman <https://github.com/jarrodmillman>`__)
-  Add cached property support `#433 <https://github.com/numpy/numpydoc/pull/433>`__ (`rossbar <https://github.com/rossbar>`__)
-  ENH: Update validate.py to allow parameters with trailing underscores. `#425 <https://github.com/numpy/numpydoc/pull/425>`__ (`stefmolin <https://github.com/stefmolin>`__)
-  DOC: Use ``:ref:`` when referring to section headers `#424 <https://github.com/numpy/numpydoc/pull/424>`__ (`namurphy <https://github.com/namurphy>`__)
-  Remove numpydoc_use_blockquotes `#422 <https://github.com/numpy/numpydoc/pull/422>`__ (`jarrodmillman <https://github.com/jarrodmillman>`__)
-  Require sphinx>=4.2 (cleanup) `#421 <https://github.com/numpy/numpydoc/pull/421>`__ (`jarrodmillman <https://github.com/jarrodmillman>`__)
-  docs: fix validation include line numbers `#418 <https://github.com/numpy/numpydoc/pull/418>`__ (`thatlittleboy <https://github.com/thatlittleboy>`__)
-  Update precommit linters `#417 <https://github.com/numpy/numpydoc/pull/417>`__ (`jarrodmillman <https://github.com/jarrodmillman>`__)
-  Update GH actions `#416 <https://github.com/numpy/numpydoc/pull/416>`__ (`jarrodmillman <https://github.com/jarrodmillman>`__)
-  ENH: Add support for dict show_inherited_class_members `#415 <https://github.com/numpy/numpydoc/pull/415>`__ (`larsoner <https://github.com/larsoner>`__)
-  DOC: Add theme switcher and default to lightmode. `#414 <https://github.com/numpy/numpydoc/pull/414>`__ (`rossbar <https://github.com/rossbar>`__)
-  Require sphinx>=4.2 `#411 <https://github.com/numpy/numpydoc/pull/411>`__ (`jarrodmillman <https://github.com/jarrodmillman>`__)

\* *This Changelog was automatically generated by*\ `github_changelog_generator <https://github.com/github-changelog-generator/github-changelog-generator>`__

1.4.0
-----

Release date: 9 June 2022

Requires Python 3.7+ and Sphinx 3.0+.

`Full Changelog <https://github.com/numpy/numpydoc/compare/v1.3.1...v1.4.0>`__

Fixed bugs
~~~~~~~~~~

-  Fix bug with version name `#400 <https://github.com/numpy/numpydoc/pull/400>`__ (`jarrodmillman <https://github.com/jarrodmillman>`__)

Closed issues
~~~~~~~~~~~~~

-  sphinx 5 compatibility `#399 <https://github.com/numpy/numpydoc/issues/399>`__

Merged pull requests
~~~~~~~~~~~~~~~~~~~~

-  Fix CI `#410 <https://github.com/numpy/numpydoc/pull/410>`__ (`jarrodmillman <https://github.com/jarrodmillman>`__)
-  Remove pytest py3.11b2 workaround `#407 <https://github.com/numpy/numpydoc/pull/407>`__ (`jarrodmillman <https://github.com/jarrodmillman>`__)
-  Update GH actions `#406 <https://github.com/numpy/numpydoc/pull/406>`__ (`jarrodmillman <https://github.com/jarrodmillman>`__)
-  Add workaround for pytest failures on 3.11b2 `#404 <https://github.com/numpy/numpydoc/pull/404>`__ (`jarrodmillman <https://github.com/jarrodmillman>`__)
-  Use node.findall if available (docutils 18.x) `#403 <https://github.com/numpy/numpydoc/pull/403>`__ (`drammock <https://github.com/drammock>`__)
-  Test docutils 0.18.1 `#402 <https://github.com/numpy/numpydoc/pull/402>`__ (`jarrodmillman <https://github.com/jarrodmillman>`__)
-  Remove old warning filters `#398 <https://github.com/numpy/numpydoc/pull/398>`__ (`jarrodmillman <https://github.com/jarrodmillman>`__)
-  Cleanup sphinx conf `#397 <https://github.com/numpy/numpydoc/pull/397>`__ (`jarrodmillman <https://github.com/jarrodmillman>`__)
-  Update pre-commit `#396 <https://github.com/numpy/numpydoc/pull/396>`__ (`jarrodmillman <https://github.com/jarrodmillman>`__)
-  Test prereleases of requirements `#395 <https://github.com/numpy/numpydoc/pull/395>`__ (`jarrodmillman <https://github.com/jarrodmillman>`__)
-  Ignore black formatting `#394 <https://github.com/numpy/numpydoc/pull/394>`__ (`jarrodmillman <https://github.com/jarrodmillman>`__)
-  Use black `#391 <https://github.com/numpy/numpydoc/pull/391>`__ (`jarrodmillman <https://github.com/jarrodmillman>`__)
-  Test on 3.11 `#375 <https://github.com/numpy/numpydoc/pull/375>`__ (`jarrodmillman <https://github.com/jarrodmillman>`__)

\* *This Changelog was automatically generated by*\ `github_changelog_generator <https://github.com/github-changelog-generator/github-changelog-generator>`__

1.3.1
-----

Release date: 30 April 2022

Requires Python 3.7+ and Sphinx 3.0+.

`Full Changelog <https://github.com/numpy/numpydoc/compare/v1.3.0...v1.3.1>`__

Closed issues
~~~~~~~~~~~~~

-  numpydoc-1.3.tar.gz on pypi is missing requirements/ needed by setup.py `#387 <https://github.com/numpy/numpydoc/issues/387>`__
-  What to do about Jinja2 dependency & supporting old sphinx versions `#380 <https://github.com/numpy/numpydoc/issues/380>`__
-  RFE: please update for ``jinja2`` 3.x `#376 <https://github.com/numpy/numpydoc/issues/376>`__
-  Test failures with Sphinx 4.5.0 `#373 <https://github.com/numpy/numpydoc/issues/373>`__

Merged pull requests
~~~~~~~~~~~~~~~~~~~~

-  Update doc requirements `#389 <https://github.com/numpy/numpydoc/pull/389>`__ (`jarrodmillman <https://github.com/jarrodmillman>`__)
-  Update manifest `#388 <https://github.com/numpy/numpydoc/pull/388>`__ (`jarrodmillman <https://github.com/jarrodmillman>`__)

1.3
---

Release date: 29 April 2022

Requires Python 3.7+ and Sphinx 3.0+.

`Full Changelog <https://github.com/numpy/numpydoc/compare/v1.2.1...v1.3.0>`__

Closed issues
~~~~~~~~~~~~~

-  Broken “many checks” link in validation chapter `#378 <https://github.com/numpy/numpydoc/issues/378>`__
-  1.2.1: pytest warnings `#377 <https://github.com/numpy/numpydoc/issues/377>`__

Merged pull requests
~~~~~~~~~~~~~~~~~~~~

-  Require sphinx>3 `#385 <https://github.com/numpy/numpydoc/pull/385>`__ (`jarrodmillman <https://github.com/jarrodmillman>`__)
-  Update tests + coverage config to rm warnings. `#383 <https://github.com/numpy/numpydoc/pull/383>`__ (`rossbar <https://github.com/rossbar>`__)
-  MAINT: Dont import for version `#382 <https://github.com/numpy/numpydoc/pull/382>`__ (`larsoner <https://github.com/larsoner>`__)
-  Runtime verification of sphinx and jinja2 versions `#381 <https://github.com/numpy/numpydoc/pull/381>`__ (`rossbar <https://github.com/rossbar>`__)
-  DOC: fix broken link to built-in validation checks. `#379 <https://github.com/numpy/numpydoc/pull/379>`__ (`rossbar <https://github.com/rossbar>`__)
-  Add pre-commit hook / linter `#374 <https://github.com/numpy/numpydoc/pull/374>`__ (`jarrodmillman <https://github.com/jarrodmillman>`__)
-  Remove deprecated numpydoc_edit_link `#372 <https://github.com/numpy/numpydoc/pull/372>`__ (`jarrodmillman <https://github.com/jarrodmillman>`__)
-  Cleanup cruft `#371 <https://github.com/numpy/numpydoc/pull/371>`__ (`jarrodmillman <https://github.com/jarrodmillman>`__)

1.2.1
-----

Release date: 29 March 2022

Requires Python 3.7+ and Sphinx 1.8+.

`Full Changelog <https://github.com/numpy/numpydoc/compare/numpydoc-1.2...v1.2.1>`__

Implemented enhancements
~~~~~~~~~~~~~~~~~~~~~~~~

-  Update year `#370 <https://github.com/numpy/numpydoc/pull/370>`__ (`jarrodmillman <https://github.com/jarrodmillman>`__)

Fixed bugs
~~~~~~~~~~

-  Use consistent release tags `#361 <https://github.com/numpy/numpydoc/pull/361>`__ (`jarrodmillman <https://github.com/jarrodmillman>`__)
-  BUG: 1.2 raises error w.r.t. object has no attribute ‘\__name_\_’ `#362 <https://github.com/numpy/numpydoc/issues/362>`__
-  Use isgeneratorfunction to avoid false alarm YD01 validation `#368 <https://github.com/numpy/numpydoc/pull/368>`__ (`jnothman <https://github.com/jnothman>`__)
-  Fix AttributeError in underline length check `#363 <https://github.com/numpy/numpydoc/pull/363>`__ (`rossbar <https://github.com/rossbar>`__)
-  Upper bound jinja `#369 <https://github.com/numpy/numpydoc/pull/369>`__ (`jarrodmillman <https://github.com/jarrodmillman>`__)

Closed issues
~~~~~~~~~~~~~

-  Validation check YD01 not implemented properly `#365 <https://github.com/numpy/numpydoc/issues/365>`__
-  Support numpydoc validation without running sphinx `#364 <https://github.com/numpy/numpydoc/issues/364>`__
-  1.2: change tagging convention? `#360 <https://github.com/numpy/numpydoc/issues/360>`__


1.2.0
-----

Release date: 24 January 2022

Requires Python 3.7+ and Sphinx 1.8+.

Implemented enhancements
~~~~~~~~~~~~~~~~~~~~~~~~

-  Document release process `#357 <https://github.com/numpy/numpydoc/pull/357>`__ (`jarrodmillman <https://github.com/jarrodmillman>`__)
-  Use setuptools `#349 <https://github.com/numpy/numpydoc/pull/349>`__ (`jarrodmillman <https://github.com/jarrodmillman>`__)
-  DOC: Switch docs to pydata-sphinx-theme `#313 <https://github.com/numpy/numpydoc/pull/313>`__ (`rossbar <https://github.com/rossbar>`__)
-  Improve error messages for see also parsing `#306 <https://github.com/numpy/numpydoc/pull/306>`__ (`rossbar <https://github.com/rossbar>`__)
-  ENH: Enable validation during sphinx-build process `#302 <https://github.com/numpy/numpydoc/pull/302>`__ (`rossbar <https://github.com/rossbar>`__)
-  Add a note to the docstring standard about long ‘See Also’ entries. `#300 <https://github.com/numpy/numpydoc/pull/300>`__ (`WarrenWeckesser <https://github.com/WarrenWeckesser>`__)
-  MAINT: minor refactoring in docscrape `#297 <https://github.com/numpy/numpydoc/pull/297>`__ (`rossbar <https://github.com/rossbar>`__)
-  ENH: Add configuration option for parameter cross-referencing `#295 <https://github.com/numpy/numpydoc/pull/295>`__ (`rossbar <https://github.com/rossbar>`__)
-  ENH: Better warning for sections. `#278 <https://github.com/numpy/numpydoc/pull/278>`__ (`Carreau <https://github.com/Carreau>`__)

Fixed bugs
~~~~~~~~~~

-  How to specify that parameter can equal the string ‘integer’? `#341 <https://github.com/numpy/numpydoc/issues/341>`__
-  Fix validation bug when parameter type is set of options. `#347 <https://github.com/numpy/numpydoc/pull/347>`__ (`rossbar <https://github.com/rossbar>`__)
-  Escape newline in docstring. `#345 <https://github.com/numpy/numpydoc/pull/345>`__ (`Carreau <https://github.com/Carreau>`__)
-  Correctly validate parameters under the “Other Parameters” section `#337 <https://github.com/numpy/numpydoc/pull/337>`__ (`dcbr <https://github.com/dcbr>`__)
-  BUG: fix an incomplete check in ``Reader.\_error\_location`` `#308 <https://github.com/numpy/numpydoc/pull/308>`__ (`rgommers <https://github.com/rgommers>`__)
-  MAINT: pytest ignore doc directory. `#296 <https://github.com/numpy/numpydoc/pull/296>`__ (`rossbar <https://github.com/rossbar>`__)
-  DOC: fix inaccuracy in validate docstring. `#294 <https://github.com/numpy/numpydoc/pull/294>`__ (`rossbar <https://github.com/rossbar>`__)
-  Fix param parsing. `#286 <https://github.com/numpy/numpydoc/pull/286>`__ (`Carreau <https://github.com/Carreau>`__)
-  BUG: Properly parse See Also when summary on first line. `#283 <https://github.com/numpy/numpydoc/pull/283>`__ (`Carreau <https://github.com/Carreau>`__)
-  BUG: fix role regex. `#280 <https://github.com/numpy/numpydoc/pull/280>`__ (`Carreau <https://github.com/Carreau>`__)
-  fix splitting of parameter lines. `#279 <https://github.com/numpy/numpydoc/pull/279>`__ (`Carreau <https://github.com/Carreau>`__)

Closed issues
~~~~~~~~~~~~~

-  Class methods (@classmethod) are not documented using ``numpydoc`` `#340 <https://github.com/numpy/numpydoc/issues/340>`__
-  Exclude certain methods from METHODS section `#338 <https://github.com/numpy/numpydoc/issues/338>`__
-  Warnings is not allowed in “GL06” check `#334 <https://github.com/numpy/numpydoc/issues/334>`__
-  Add version to style guide `#333 <https://github.com/numpy/numpydoc/issues/333>`__
-  numpydoc does not render parameters as expected `#329 <https://github.com/numpy/numpydoc/issues/329>`__
-  1.1.0: pytest warnings `#324 <https://github.com/numpy/numpydoc/issues/324>`__
-  RTD configuration - ``latest`` `#321 <https://github.com/numpy/numpydoc/issues/321>`__
-  Rendering of types in latest doc build `#318 <https://github.com/numpy/numpydoc/issues/318>`__
-  Anchors for individual sections in numpydoc doc? `#317 <https://github.com/numpy/numpydoc/issues/317>`__
-  Development documentation not up-to-date `#311 <https://github.com/numpy/numpydoc/issues/311>`__
-  Warning: autosummary: stub file not found `#290 <https://github.com/numpy/numpydoc/issues/290>`__
-  Wrong number of Parameter for numpy array. `#285 <https://github.com/numpy/numpydoc/issues/285>`__
-  syntax to document default values `#284 <https://github.com/numpy/numpydoc/issues/284>`__
-  Failed See Also Parsing. `#281 <https://github.com/numpy/numpydoc/issues/281>`__
-  Sphinx emits “WARNING: py:class reference target not found” with numpydoc 1.1.0 `#275 <https://github.com/numpy/numpydoc/issues/275>`__


1.1.0
-----

Implemented enhancements
~~~~~~~~~~~~~~~~~~~~~~~~

-  MAINT: Suggestions from reviewing test suite `#271 <https://github.com/numpy/numpydoc/pull/271>`__ (`rossbar <https://github.com/rossbar>`__)
-  DEV: Add testing requirements `#267 <https://github.com/numpy/numpydoc/pull/267>`__ (`rossbar <https://github.com/rossbar>`__)
-  BUG: Defer to autodoc for signatures `#221 <https://github.com/numpy/numpydoc/pull/221>`__ (`thequackdaddy <https://github.com/thequackdaddy>`__)

Fixed bugs
~~~~~~~~~~

-  function signatures for \*args, \**kwargs objects off `#218 <https://github.com/numpy/numpydoc/issues/218>`__
-  BUG: Connect to earlier event `#269 <https://github.com/numpy/numpydoc/pull/269>`__ (`larsoner <https://github.com/larsoner>`__)

Closed issues
~~~~~~~~~~~~~

-  “Handler <function mangle_docstrings at 0x7f64b5ba57b8> for event ‘autodoc-process-docstring’ threw an exception” `#268 <https://github.com/numpy/numpydoc/issues/268>`__
-  Timing of next release `#249 <https://github.com/numpy/numpydoc/issues/249>`__
-  self included in list of params for method `#220 <https://github.com/numpy/numpydoc/issues/220>`__

Additional notes
~~~~~~~~~~~~~~~~

-  Due to merging of `#221 <https://github.com/numpy/numpydoc/pull/221>`__, self and cls no longer will appear in method signatures.


1.0.0
-----

Implemented enhancements
~~~~~~~~~~~~~~~~~~~~~~~~

-  ENH: Add args and kwargs to example `#258 <https://github.com/numpy/numpydoc/pull/258>`__ (`larsoner <https://github.com/larsoner>`__)
-  MAINT,STY: Upgrade to bionic, and change style similar to NumPy `#253 <https://github.com/numpy/numpydoc/pull/253>`__ (`mwtoews <https://github.com/mwtoews>`__)
-  Delay import of Sphinx `#248 <https://github.com/numpy/numpydoc/pull/248>`__ (`cgohlke <https://github.com/cgohlke>`__)
-  Adding –validate option \__main_\_ and run new validation `#240 <https://github.com/numpy/numpydoc/pull/240>`__ (`datapythonista <https://github.com/datapythonista>`__)
-  Add docstring validation script (from pandas) `#238 <https://github.com/numpy/numpydoc/pull/238>`__ (`datapythonista <https://github.com/datapythonista>`__)
-  ENH: Test full output and coverage `#230 <https://github.com/numpy/numpydoc/pull/230>`__ (`larsoner <https://github.com/larsoner>`__)
-  DOC: Add description for blank lines after the docstring. `#229 <https://github.com/numpy/numpydoc/pull/229>`__ (`bingyao <https://github.com/bingyao>`__)

Fixed bugs
~~~~~~~~~~

-  References outside function `#214 <https://github.com/numpy/numpydoc/issues/214>`__
-  FIX: Get doc of actual class in test `#262 <https://github.com/numpy/numpydoc/pull/262>`__ (`larsoner <https://github.com/larsoner>`__)
-  TST: Add inherited method `#260 <https://github.com/numpy/numpydoc/pull/260>`__ (`larsoner <https://github.com/larsoner>`__)
-  Fixes references outside function (#214) `#259 <https://github.com/numpy/numpydoc/pull/259>`__ (`Hoxbro <https://github.com/Hoxbro>`__)
-  Disable escaping “\*” on signature `#256 <https://github.com/numpy/numpydoc/pull/256>`__ (`tk0miya <https://github.com/tk0miya>`__)
-  MAINT: clean-up unused objects `#254 <https://github.com/numpy/numpydoc/pull/254>`__ (`mwtoews <https://github.com/mwtoews>`__)
-  STY: Reword first lines of example.py docstrings `#246 <https://github.com/numpy/numpydoc/pull/246>`__ (`justinludwig <https://github.com/justinludwig>`__)
-  DOC: Fixed three formatting issues in docs `#245 <https://github.com/numpy/numpydoc/pull/245>`__ (`rossbar <https://github.com/rossbar>`__)
-  STY Minor style improvements to doc/example.py to pass validation `#243 <https://github.com/numpy/numpydoc/pull/243>`__ (`rth <https://github.com/rth>`__)
-  BUG: Allow no . at end if indented `#239 <https://github.com/numpy/numpydoc/pull/239>`__ (`larsoner <https://github.com/larsoner>`__)
-  DOC: Update links and code checkers info in format.rst `#228 <https://github.com/numpy/numpydoc/pull/228>`__ (`bingyao <https://github.com/bingyao>`__)
-  DOC: Update links and info in conf.py. `#227 <https://github.com/numpy/numpydoc/pull/227>`__ (`bingyao <https://github.com/bingyao>`__)
-  BUG: Fix full rebuilds `#226 <https://github.com/numpy/numpydoc/pull/226>`__ (`larsoner <https://github.com/larsoner>`__)
-  MAINT: doctest and pytest `#225 <https://github.com/numpy/numpydoc/pull/225>`__ (`larsoner <https://github.com/larsoner>`__)
-  Py3fy some doctests. `#224 <https://github.com/numpy/numpydoc/pull/224>`__ (`anntzer <https://github.com/anntzer>`__)
-  MAINT: fix trivial source comment typos `#222 <https://github.com/numpy/numpydoc/pull/222>`__ (`luzpaz <https://github.com/luzpaz>`__)
-  Add missing headings to code examples `#252 <https://github.com/numpy/numpydoc/pull/252>`__ (`Cadair <https://github.com/Cadair>`__)

Removed
~~~~~~~

-  MNT Drop Python 2.7 and 3.4 support `#236 <https://github.com/numpy/numpydoc/pull/236>`__ (`rth <https://github.com/rth>`__)

Closed issues
~~~~~~~~~~~~~

-  Prefix added to reference keys in class docstrings `#263 <https://github.com/numpy/numpydoc/issues/263>`__
-  Test failure with python 3.9 `#261 <https://github.com/numpy/numpydoc/issues/261>`__
-  sphinx doc napoleon extension maintainer interest request `#251 <https://github.com/numpy/numpydoc/issues/251>`__
-  Missing reference to float_power function in the ufunc list `#250 <https://github.com/numpy/numpydoc/issues/250>`__

Additional notes
~~~~~~~~~~~~~~~~

-  CSS styling changed from NumpyDoc < 0.8 and Sphinx < 2.0 to more properly make use of definition lists. This can cause issues with rendering that can be fixed via CSS, especially when using ``sphinx-rtd-theme``. For more information, see:

   -  https://github.com/numpy/numpydoc/issues/215#issuecomment-568261611
   -  https://github.com/readthedocs/sphinx_rtd_theme/pull/838
