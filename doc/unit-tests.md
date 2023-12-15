Compiling/running unit tests
------------------------------------

Unit tests will be automatically compiled if dependencies were met in `./configure`
and tests weren't explicitly disabled.

After configuring, they can be run with `make check`.

To run the tonnaged tests manually, launch `src/test/test_tonnage`.

To add more tonnaged tests, add `BOOST_AUTO_TEST_CASE` functions to the existing
.cpp files in the `test/` directory or add new .cpp files that
implement new BOOST_AUTO_TEST_SUITE sections.

To run the tonnage-qt tests manually, launch `src/qt/test/test_tonnage-qt`

To add more tonnage-qt tests, add them to the `src/qt/test/` directory and
the `src/qt/test/test_main.cpp` file.
