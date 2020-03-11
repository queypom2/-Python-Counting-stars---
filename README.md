Input is read from stdin and consists of an arbitrary number of words i.e. columns of text. Each column has the length i.e. all words contain the same number of characters. Characters can be either lowercase or uppercase.

Output is the same set of columns but sorted alphabetically (ignoring case).

example:

$ cat stdin.txt
oTs
nwi
eox

$ python3 sideways_122.py < stdin.txt
osT
niw
exo
