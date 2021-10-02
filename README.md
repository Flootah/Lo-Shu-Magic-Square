# Lo-Shu-Magic-Square


The Lo Shu Magic Square is a grid with 3 rows and 3 columns, and has the following properties:
• The grid contains the numbers 1 through 9 exactly (no repeats).
• The sum of each row, each column, and each diagonal all add up to the same number. 

Example:
```
            15
           /
[ 4  9  2 ] — 15
[ 3  5  7 ] — 15
[ 8  1  6 ] — 15
  |  |  |  \
 15  15 15  15
```

This program recreates the square with a 2D array, implementing a function that can determing if a given square is a Lo Shu Magic Square or not.
When run, the program will randomly generate new squares, then determine if it is magic or not. If it is, it will display the square and the number of attempts it took to find it.

Example output:
```
attempt 1
attempt 2
attempt 3
...
attempt 59827
attempt 59828
attempt 59829
attempt 59830
attempt 59831
attempt 59832
Found magic square! It took 59832 tries.
[ 8 1 6 ]
[ 3 5 7 ]
[ 4 9 2 ]
```
