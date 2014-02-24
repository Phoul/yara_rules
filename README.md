Yara Crypto Rules
=================
After seeing @chort0's rule for RC6[1] on Twitter, I decided to write a few rules for other things. 

[1]: https://twitter.com/chort0/status/418156066291994624

One-Way Hash Functions
----------------------
* MD5
* SHA1 (Currently also triggers on RIPEMD160)
* SHA224/256
* SHA384/512
* RIPEMD-160 (Currently also triggers on SHA1)
* WHIRLPOOL

Block Ciphers
-------------
* Blowfish
* RC6 - By @chort0[2]

[2]: https://twitter.com/chort0

Pseudo-Random Number Generators
-------------------------------
