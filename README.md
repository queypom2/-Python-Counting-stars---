All black pixels ("#") are considered to be part of the sky, and each white pixel is considered to be part of a star. White pixels ("-") that are adjacent vertically or horizontally are part of the same star.

Output should be how many stars are found

Example:

$ cat stdin.txt
10 20
#################---
##-###############--
#---################
##-#################
########---#########
#######-----########
########---#########
##################--
#################---
##################-#

$ python3 stars_122.py < stdin.txt
4
