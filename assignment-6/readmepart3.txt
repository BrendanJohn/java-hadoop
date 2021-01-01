This is my solution for problem 3, a word histogram. The WordHistogram.java class contains a mapper
and a reducer that work together to ingest a file and output a file that contains counts for
the occurrences of each word length in the input file. I accomplished this by updating the mapper and
reducer parameterized types to allow for an IntWritable data type which captures the word length and
outputs it to the target file.