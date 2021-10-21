Utility script for CMake project management
=================================================

Includes...
-----------

* Building C and C++ projects with ``ninja``

          - Debug and Release modes (**TODO**)

* Running tests with ``ctest``
* Linters

          - Clang-format
          - Clang-tidy
          - Cppcheck
          - Coverage (**TODO**)
          - CMake formatter

* Doxygen docs (**TODO**)

          - Local build
          - GH pages upload


Depends on...
-------------

* Python3 and a couple of pip modules


How to use...
-------------

• Go with ``build`` in order to build project only
         + test: builds tests
         + doc: builds doc
• with ``test`` to build the project including the tests
         + runtest: runs tests
• with ``lint`` is to run linters locally
         + style: clang-format
         + tidy: ctidy
         + cmake: cmake-format
         + check: cppcheck
• ``doc`` is used to build local documentation
         + updoc: uploads to gh-pages
• ``clean`` is used to clean metadata
         + kind: ask before each delete
         + force: guess :)


