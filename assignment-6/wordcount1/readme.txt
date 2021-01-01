My observations from running the mapper and reducer program for the first time is that it
processes a large data file, and produces an output file that contains each word in the source
file and the number of times it appears. This is accomplished by a Hadoop Text object that
represents a single line from the source file broken down into single words delimited by
the space characters. These values are sent to the reducer for processing where it sums up the
number of occurrences for each word in the source file.