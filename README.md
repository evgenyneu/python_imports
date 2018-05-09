# Relative imports and running Python as a package

This is a demo project I created for myself to understand how to import code in Python. The code is based on [this](https://stackoverflow.com/a/22250157/297131) stackoverflow answer.

The code runs the python script from foo/bar/baz.py file, which uses relative imports from parent directories.

The code needs to be run as a package. Run the following the project's root directory:


```Python
python3 -m foo.bar.baz
```

Note that it is not possible to run the code just by typing

```Python
python3 foo/bar/baz.py
```

because it uses imports.