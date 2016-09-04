# Python: Rectangles

Count the rectangles in an ASCII diagram.

Create a program to count the rectangles in an ASCII diagram like the one below.

```
   +--+
   |  |
+--+--+
|  |  |
+--+--+
```

The above diagram contains 5 rectangles:

```


+-----+
|     |
+-----+
```

```
   +--+
   |  |
   |  |
   |  |
   +--+
```

```
   +--+
   |  |
   +--+


```

```
       
       
   +--+
   |  |
   +--+
```

```
       
       
+--+
|  |
+--+
```

You may assume that the input is always a proper rectangle (i.e. the length of
every line equals the length of the first line).

To run a test file, pass it as an argument to the `python` command:

    python hello_world_test.py

If you want to stop the tests after the first failure, then you can use the pytest library.

Install pytest with pip:

    pip install pytest

Run the tests with the `py.test` command using the `-x` flag to exit after the first failure.

    py.test -x hello_world_test.py

# Source

This exercise is from the [Python][python] track on [Exercism][exercism]

[exercism]: http://exercism.io
[python]: http://exercism.io/languages/python



