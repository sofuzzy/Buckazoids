https://buckazoidcore.org/
Buckazoids Core — Bitcoin-derived blockchain node software
=====================================

Buckazoids Core is experimental node software for the Buckazoids blockchain.

It is derived from Bitcoin Core and keeps upstream Bitcoin Core copyright and MIT license notices where required.

What is Buckazoids Core?
------------------------

Buckazoids Core connects to the Buckazoids peer-to-peer network to download and fully validate blocks and transactions.

It is currently early-stage experimental software.

Further technical documentation is available in the [doc folder](/doc).

License
-------

Buckazoids Core is released under the terms of the MIT license. See [COPYING](COPYING) for more information or see https://opensource.org/license/MIT.

Development Process
-------------------

The `master` branch is under active development and is not guaranteed to be stable.

Build instructions are available in the `doc/build-*.md` files.

The contribution workflow is described in [CONTRIBUTING.md](CONTRIBUTING.md), and useful hints for developers can be found in [doc/developer-notes.md](doc/developer-notes.md).

Testing
-------

Developers are encouraged to run unit, regression, and integration tests before submitting changes.

Unit tests can be compiled and run with:

`ctest`

Functional tests can be run with:

`build/test/functional/test_runner.py`

Translations
------------

Translation workflow has not yet been established for Buckazoids Core.