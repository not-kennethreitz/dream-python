## Python Dreams |(• ◡•)|

### assert 1/3 == 1.0/3.0, "Type Coercion Rules"

[Type Coercion Rules](https://docs.python.org/release/2.5.2/ref/coercion-rules.html) are complex by nature, it is difficult for the compiler to guess the type which is most effective without any hints. Using all `float` logic is costly but is the cost greater than the bugs generated from misunderstandings about how coercion in python works?

Ideas:

1. The statement `1/3` raises a [Warnings Exception](https://docs.python.org/2/library/warnings.html).
2. Require base numerical types to be explicitly labeled `1.0F`, `1.0L` and `1I`.

### assert "a" is u"a", "Unicode Equality"

[Unicode](https://docs.python.org/3/howto/unicode.html) is difficult to work with. It is an understandable issue considering the number of richly different human languages existing in the world. Using a default encoding of `ascii` isn't helping this process by hiding the complexity to discover later.

Ideas

1. Approach the difficulty of languages head on to English only speaking communities when they begin developing.
2. Raise an `Exception` if a library using a different encoding is imported.

### assert getattr(object(), "__deprecated__", None) is not None, "Function, Method and Class Deprecation"

[Deprecations](https://docs.python.org/3/library/exceptions.html#DeprecationWarning) are currently a type of `Exception`. They work great if used but rarely do libraries use this type of `Exception`. Instead I would like to see an attribute available on all Functions, Methods and Classes which give more details about the deprecation.

Ideas:

1. Add in a `@deprecation` decorator.

### assert "cuda" in dir(__builtin__), "GPU MultiProcess"

GPU multiprocessing is already possible in Python but I believe it is becoming more important than ever before. I would love to see core integration with GPU drivers for matrix and vector based logic which is accessed via familiar CPU based multiprocessing logic.

Ideas:

1. Create a standard GPU package.

### assert 真, "English as a Second Language"

There are [translation issues](http://nas.sr/%D9%82%D9%84%D8%A8/) using programming languages across human languages. There are projects which are based on Python for [other written languages](https://code.google.com/p/zhpy/) but I would like to see a Python which can be used across lingual divides to express similar logic.

Ideas:

1. Use `ast` to transpile from one language into the equivalent English Python code.

### Keep Building a Community

Python is stable and used in more organizations than I can count. I think it is important that the project decisions are made to support the legacy community while growing a larger community of new developers.
