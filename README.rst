Base64
======

Base64 encoding and decoding in the `Mys programming language`_.

Examples
========

.. code-block:: python

   from base64 import encode
   from base64 import decode

   def main():
       print(encode(b"foo"))
       print(decode("Zm9v"))

.. _Mys programming language: https://github.com/mys-lang/mys
