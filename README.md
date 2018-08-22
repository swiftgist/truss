The example code for normalizing a CSV file is written in Ruby.  After cloning, ensure that both files are executable.  For example,

```
$ git clone https://github.com/swiftgist/truss.git
$ cd truss
$ chmod +x normalize test_normalize
```

### Running the example

```
$ ./normalize < sample.csv
```

To view the data with only the preprocessing step, run

```
$ ./normalize -p < sample.csv
```

### Running Unit tests

```
$ ./test_normalize
```

### Additional Comments

Normally, I would squash all the commits into one before creating a PR.
