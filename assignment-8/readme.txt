This is my solution for homework 8 part 1, a program that parses Json data to find the total number of tweets from
each android user. The GsonTweetEater.java class contains a mapper and a reducer that work together to
ingest rows from a json data set and output a file that contains screen name and counts for the occurrences of each tweet
from an android user. I accomplished this by updating the mapper to use the Gson library
to ingest each row from a source file and scan for those values.

The jar file can be run locally using the following command:
java -jar hw8-1.0-SNAPSHOT-jar-with-dependencies.jar NintendoTweets_sm.json output_2

To get the full results please run against the full NintendoTweets_sm.json file in Amazon,
or take a look at the provided output files I have included after running it against the amazon version.
Lastly, the cluster summary screenshot I have provided is labeled cscie55_7_prob_02, however it is in fact my hw8 jar
running in a cloned cluster which I was unable to rename.

If you have any questions please message me,
Thanks Brendan