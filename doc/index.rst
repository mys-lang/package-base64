|test|_

About
=====

Base64 encoding and decoding in the `Mys programming language`_.

Project: https://github.com/mys-lang/package-base64

Example
=======

.. code-block:: python

   from base64 import encode
   from base64 import decode

   def main():
       print(encode(b"foo"))
       print(decode("Zm9v"))

Functions and types
===================

.. mysfile:: src/lib.mys

.. |test| image:: https://github.com/mys-lang/package-base64/actions/workflows/pythonpackage.yml/badge.svg
.. _test: https://github.com/mys-lang/package-base64/actions/workflows/pythonpackage.yml

.. _Mys programming language: https://mys-lang.org
