# How to run Python code that has imports

This is a demo project I created for myself to understand how to import code in Python. The code is based on [this](https://stackoverflow.com/a/22250157/297131) stackoverflow answer.

The code runs the python script from `foo/bar/baz.py` file, which uses relative imports from parent directories.

## Running the code

The code needs to be run as a package. Run the following the project's root directory:


```Shell
git clone https://github.com/evgenyneu/python_imports.git
cd python_imports
python3 -m foo.bar.baz
```

If successful, the program will print:
```
Hello horsy!
Hello horsy 2!
```

## Running just the Python script won't work

Note that it is not possible to run the code just by typing

```Shell
python3 foo/bar/baz.py
```

because it uses imports.
