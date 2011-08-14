QR test data generator
======================

A small script that generates QR codes to be used as test data to
check the correctness of QR codes generators.


Installation
------------

This script do not require any installation. It, however, uses
external libraries that may not be installed in all computers. To
install all the required libraries use Bundler:

	bundle install --path gems/


How to generate the test QR codes
---------------------------------

If Bundler has been used to install the required dependencies,
`gen-qr-test-data` can be run with

	bundle exec ./gen-qr-test-data > qr_test_data.rb


Author
------

Original author: Gioele Barabucci <gioele@svario.it>


License
-------

This is free and unencumbered software released into the public domain.
See the `UNLICENSE` file or <http://unlicense.org/> for more details.

