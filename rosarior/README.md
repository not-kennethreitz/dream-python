# Dreams

## Technical

- C style increment and decrement operator (++): +=1 doesn't feel right.
- ImportError debugger: Sometimes an error in a library causes a simple ImportError with no hope of trace back.
- Canonical packaging method or library: No more distutils vs. setuptools vs. wheel [issue 99](https://bitbucket.org/pypa/wheel/issue/99/cannot-exclude-directory), workarounds are not solutions.
- Canonical package installer: No more pip vs easy_install vs [...]
- Short hand method for super: Feels wasteful to keep writting super(Class, self).method(*args, **kwargs)
- Better stale bytecode detection: No more having to hand delete .pyc files after a git pull
- Fix or warning for some quirky syntax: (,) or a = 1,
- True class private methods/attributes
- Builtin syntax, PEP8 checker: Something like flake8 *in* the interpreter
- In-place sorting: Sort a list without creating a new list
- Selectable sorting algorithms: No one single algorithms is a perfect fit for all cases (quicksort, mergesort, insertionsort)
- Anonymous classes
- Ability to freeze/compile distributable executables or libraries
- Just like Unicode, default UTC aware date/time handling by default
- Sensible built-in HTTP, URL and date/time libraries like Requests, FURL and Arrow
- Get rid of if \__name__ == "\__main__": a Python module should be a script or a library, not both
- Better default shell: autocomplete is a must have feature so is interactive method and attribute inspection
- A case/switch statement, nested if elif else reduce readability, a dictionary of callables feels hackish

## Community

- Constructive, helpful:
    - http://zurb.com/forrst/posts/Mayan_A_document_manager_done_using_Django-snk

- Middle ground:
    - https://twitter.com/_tomchristie/status/494938402434080769

- Not constructive:
    - https://bitbucket.org/ubernostrum/django-registration/pull-request/21/pass-user-instance-to-email-template/diff
