# aps-test-cases
Test cases for APS

## Using the test runner
Use `python3 test.py <source_file> <test_path>` to run the test runner, and get more
help by using `python3 test.py --help`.

#### Output of Main File
The test runner compiles your code and runs it; before compiling, it first copies
your code into this repository in the `bin` directory.

#### Examples

If your source file is at `/home/aliu/code/aps/hw3/Polish.java`

```
python3 test.py /home/aliu/code/aps/hw3/Polish.java
```

will compile the program and run it using standard input.
