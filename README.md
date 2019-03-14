The minesweeperPy module for Python 3.6
=======================================

#### Made by Steven Shrewsbury Dev. (AKA: stshrewsburyDev)


Screenshots:
------------

![RawTerminalUsage](https://stshrewsburydev.github.io/official_site/API/ProjectScreenshots/minesweeperPy/minesweeperPy0001.png "Raw terminal usage")

Installation:
-------------

###### Install from source:

```
python setup.py install
```

Using in your code:
-------------------

###### Import the module:

```py
import minesweeperPy
```

###### Make a new grid generation setting:

```py
columns = 12 # This will be the amount of columns in the grid (Must be 5+)
rows = 12 # This will be the amount of rows in the grid (Must be 5+)

MyNewGridGeneration = minesweeperPy.MineGen(columns, rows)
```

The number of cells in the grid is calculated by multiplying the column count by the row count:

| Columns | Rows | Cells |
|:-------:|:----:|:-----:|
| 10      | 10   | 100   |
| 25      | 20   | 500   |
| 48      | 50   | 2400  |

###### Generate a new grid:

```py
NumberOfMines = 25 # This will be the number of mines in the grid
#(Must be 1+ and not be more than the maximum space on the Grid generation