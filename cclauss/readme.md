CCC's Dream Python
==================

Community
---------

* Push harder to get all useful third party libraries/modules fully ported to Python3.
    * Twisted, gevent
* Put Python2 out to pasture so that we can unify and press forward.
* Move to something more modern/powerfuk than tkinter as the bundled UI.  Today there are way too many UI options which is stalling innovation.
    * Tkinter, Pygame, PyQt, PySide, PyGObject, PyGtk. kivy, etc.
* Python as one of the top languages used on game development.

Technical
---------

* An easier syntax for bounding a variable between a min and a max.  See below.
* Pervasive support for `with open()` syntax throughout the standard library.
    * e.g. in aifc.py, wave.py, shelve.py, etc.
* Support Python3 in [Pythonista](http://www.omz-software.com/pythonista/index.html) so we can hack Python3 on our iPads while on the move. 

On bounding a variable between a min and a max
==============================================

```
x = -3 |> x <| 5
# would be equal to:
x = max(min(x, 5), -3)

# other approaches
x = -3 | x | 5
# or
x = -3 |>= x <=| 5
```
