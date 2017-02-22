

## Running Instructions
$ python tiled_FW.py

Note, if it errors out it's because there's a negative cycle, to prove that try it again with negative edges set to false.
If you want to view matricies set global_debug to True

## Requirements
Tested with Python 3.5 (actually anaconda), should work with version of python really
Required packages:
    timeit (built in)
    random (built in)
    deepcopy (built in)
    pprint (not built in?) pip install pprint

## Citations
    Optimizing Graph Algorithms for Improved Cache Performance
        Joon-Sang Park, Michael Penner, and Viktor K. Prasanna
        IEEE 2004
    A Blocked All-Pairs Shortest-Paths Algorithm
        Gayathri Venkataraman, Sartaj Sahni, and Srabani Mukhopadhyaya