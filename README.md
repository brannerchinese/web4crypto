Simple web servers for testing cryptographic tactics
----------------------------------------------------

Requirements:

 - python 3
 - virtualenv


To run:

    $ make
    $ python timed_pw.py

 **Options**: on command line, user may enter 

 * an integer for optional password length (default is 10)

 * flag -p to display password

 **Date**: 20130311.

1. `hashes.py`: Runs in Python 3.2. Adds a succession of strings to a hash table of size n until k-1 collisions are reached.

[end]
