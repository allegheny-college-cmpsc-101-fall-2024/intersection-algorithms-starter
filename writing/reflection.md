# Intersection Algorithms

TODO: Make sure that you delete all of the TODO markers inside of this file and
either remove or rewrite the prompts. When you are finished with this reflection
it should contain professional writing that is suitable for publishing. That
includes removing this paragraph!

## Add Your Name Here

## 1. Program Profiling Output

TODO: This section will document program output, but it is also the data source for
an empirical timing experiment. Do not run the program with the `--display` option
because the display will impact the timing of the algorithms. Keep reading to see
exactly what to run for your timing experiment.

### Two outputs from running the ListSingle algorithm with different inputs

TODO: Put the obtained outputs in fenced-code blocks. Choose small and large
inputs for a computer, perhaps separated by several orders of magnitude. It is
essential that real, non-zero profile timings are obtained.

- Run 1: `ListSingle` with a small input
- Run 2: `ListSingle` with a large input

### Two outputs from running the ListDouble algorithm with different inputs

TODO: Put the obtained outputs in fenced-code blocks. Use the same small and
large inputs as above. This is essential so that you can make valid comparisons
between the performances of different algorithms. All runs must produce real,
non-zero profile timings.

- Run 1: `ListDouble` with a small input
- Run 2: `ListDouble` with a large input

### Two outputs from running the TupleSingle algorithm with different inputs

TODO: Put the obtained outputs in fenced-code blocks. Use the same small and
large inputs as above. This is essential so that you can make valid comparisons
between the performances of different algorithms. All runs must produce real,
non-zero profile timings.

- Run 1: `TupleSingle` with a small input
- Run 2: `TupleSingle` with a large input

### Two outputs from running the TupleDouble algorithm with different inputs

TODO: Put the obtained outputs in fenced-code blocks. Use the same small and
large inputs as above. This is essential so that you can make valid comparisons
between the performances of different algorithms. All runs must produce real,
non-zero profile timings.

- Run 1: `TupleDouble` with a small input
- Run 2: `TupleDouble` with a large input

### Justification of your choice for the numelems and maximum variables

TODO: Document and justify your choice for the `numelems` and `maximum` variables.

## 2. Performance Report

### Data

TODO: Fill in the table in markdown to summarize the profile timing data
gathered above. Abbreviation ls stands for list single, td tuple double etc.

| numelems | maximum | approach ls | approach ld | approach ts | approach td |
|----------|---------|-------------|-------------|-------------|-------------|
| TODO     | TODO    | TODO        | TODO        | TODO        | TODO        |

### Analysis

TODO: Using the formula given in Prime Testing, show how you calculate which
algorithm is fastest and by how much it is faster. I.e., compute differences
while holding the denominator constant. Your calculations should use the data
in the data table above.

### Results and Discussion

TODO: Explain which algorithm is fastest and by how much it is faster. Also
discuss why certain algorithms would be faster, and whether your results
support theoretical claims about speed.

### Performance Report Conclusion

TODO: In conclusion, make sure that you can answer the following research
questions:

- RQ: Is intersection faster with a list or a tuple?
- RQ: Is intersection faster with a double-for-loop or a single-for-loop?
- RQ: Overall, what is the fastest approach for computing the intersection?

## 3. Source Code Review

TODO: Use a fenced code block to provide the requested source code.
Then describe in detail how the source code works.

### Enum class that defines the four algorithmic options
### Function signature that defines the command-line interface for `intersection`
### Function that can generate a data container with random values in it

## 4. Professional Reflection

TODO: Answer the questions below in your own words thinking about your
professional skills development.

- In the context of Python programming, what are your greatest strengths and weaknesses?
- In the context of running performance experiments, what are your greatest strengths and weaknesses?
- What is one challenge you faced when completing this assignment and how did you overcome it?
- Give an example of a truth that you once thought was simple, but that now you
  think is more complex and nuanced than you realized. Use your example to explain
  why the deep investigation of computer program performance is essential for learning
  programming.
