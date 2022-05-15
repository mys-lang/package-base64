|discord|_
|test|_
|stars|_

About
=====

Base64 encoding and decoding in the `Mys programming language`_.

Project: https://github.com/mys-lang/package-base64

Example
=======

The code:

.. code-block:: mys

   from base64 import encode
   from base64 import decode
   from base64 import encode_bytes
   from base64 import decode_bytes

   func main():
       print("Encoded:      ", encode(b"foo"))
       print("Decoded:      ", decode("Zm9v"))
       print("Encoded bytes:", encode_bytes(b"foo"))
       print("Decoded bytes:", decode_bytes(b"Zm9v"))

Build and run:

.. code-block:: myscon

   ❯ mys run
    ✔ Reading package configuration (0 seconds)
    ✔ Building (0.58 seconds)
   Encoded:       Zm9v
   Decoded:       b"foo"
   Encoded bytes: b"Zm9v"
   Decoded bytes: b"foo"

API
===

.. mysfile:: src/lib.mys

.. |discord| image:: https://img.shields.io/discord/777073391320170507?label=Discord&logo=discord&logoColor=white
.. _discord: https://discord.gg/GFDN7JvWKS

.. |test| image:: https://github.com/mys-lang/package-base64/actions/workflows/pythonpackage.yml/badge.svg
.. _test: https://github.com/mys-lang/package-base64/actions/workflows/pythonpackage.yml

.. |stars| image:: https://img.shields.io/github/stars/mys-lang/package-base64?style=social
.. _stars: https://github.com/mys-lang/package-base64

.. _Mys programming language: https://mys-lang.org
