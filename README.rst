telethon-pyaesni
=================

Module ``telethon-pyaesni`` brings even better performance to
`Telethon <https://github.com/LonamiWebs/Telethon>`__ lib.

Similar to ``telethon-tgcrypto``, libAES-NI uses CPU hardware acceleration 
to perform AES encryption and decryption. 

Installation
~~~~~~~~~~~~

**N.B.** you must not have ``cryptg`` installed, because it interferes with
this module.

To install this module and patch your Telethon installation just run:

::

    pip install telethon-pyaesni

Credits
~~~~~~~

-  `@painor <https://github.com/painor>`__ for making pyaesni and telethon-tgcrypto.
-  `@andrew <https://github.com/kittyandrew>`__ for writing readme for telethon-tgcrypto
-  `@lonami <https://github.com/lonami>`__ &
   `contributors <https://github.com/LonamiWebs/Telethon/graphs/contributors>`__
   for making `telethon <https://github.com/LonamiWebs/Telethon>`__
