|test|_

About
=====

Base64 encoding and decoding in the `Mys programming language`_.

Project: https://github.com/mys-lang/package-base64

Example
=======

The code:

.. code-block:: python

   from base64 import encode
   from base64 import decode

   def main():
       print(encode(b"foo"))
       print(decode("Zm9v"))

Build and run:

.. code-block:: text

   $ mys run
    ✔ Reading package configuration (0 seconds)
    ✔ Building (0.58 seconds)
   Zm9v
   b"\x66\x6f\x6f"

API
===

.. mysfile:: src/lib.mys

.. |test| image:: https://github.com/mys-lang/package-base64/actions/workflows/pythonpackage.yml/badge.svg
.. _test: https://github.com/mys-lang/package-base64/actions/workflows/pythonpackage.yml

.. _Mys programming language: https://mys-lang.org
