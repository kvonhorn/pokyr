pokyr
=============

This is fork of [AC's pokyr library](https://github.com/cleverpiggy/pokyr). I've made some changes so I can use it with
Python 3, but in the process have broken the C module. :P This is a pure-Python implementation as of this writing
(4 Feb 2019).


Sample
------
Cards are represented by integers 0-51 and groups of cards are contained
in lists.  A Card class is provided for convenience.  The pretty_args
wrapper allows you to use standard card strings rather than Card objects
or integers.


```python
>>> import poker
>>> mc = poker.utils.pretty_args(poker.monte_carlo)
# Run a Monte Carlo evaluation of the following matchup
>>> mc(["AsAd", "7c2h"])
[0.87452, 0.12547]
>>> 

```



Compile and Install
-------

### Linux

Close the repo onto your machine, then run

```
pip3 install path/to/repo
```

