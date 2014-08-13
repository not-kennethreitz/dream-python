Algebraic Data Types
====================

While oftentimes Python's classes and built in data types get by, I think that Python would be enriched with the addition of a nice syntax for algebraic data types.

This new syntax might look somewhat like this:

    deftype Maybe a = Just a | Nothing
    
    deftype Tree a = Empty | Node a | Node a (Tree a) (Tree a)

Inspired by the syntax of ML or Haskell. This sort of thing can be emulated with classes in Python, but the syntax isn't nearly as consice as the above.

Python (especially Python 3) already has a lot of functional features in it, and algebraic data types would make it a lot easier to program in a functional style.
