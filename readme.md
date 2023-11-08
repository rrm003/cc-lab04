Getting Started with Spark, Pyspark, Mesos, Yarn

Read the documentation below as required (note that there exist various Spark versions).

http://spark.apache.org/docs/latest/
http://spark.apache.org/docs/0.8.1/ http://spark.apache.org/docs/0.8.1/python-programming-guide.html http://spark.apache.org/docs/0.8.1/scala-programming-guide.html#master-urls https://spark.apache.org/docs/2.2.0/rdd-programming-guide.html https://spark.apache.org/docs/2.3.2/quick-start.html

Find all files (words.txt, file1, file2, and file3) required for this Lab on Canvas.

Spark

Step 1: Pyspark, Basic Commands

Install the latest version of Spark on your local machine in Standalone mode. Before that, you also need to install Java, Python and Scala. Run pyspark and using interactive commands run the following queries (practice to work with basic pyspark commands such as map, reduce, reduceByKey, sortByKey, groupBy, groupByKey, filter, mapValues, etc):

    List the 5 first words (in ascending order) and from the words.txt which start with “b” and end with “t”.
    List the 10 last longest words from the file words.txt.
    Calculate the number of lines and the number of distinct words from file1.
    Find 3 common words in files1, file2, and file3 which their sum of frequencies (number of occurrences) within the three files is maximum compared to the other shred words. (e.g., assume that X is a set of words which are shared between all files, find common words like xi in X which maximize F(xi)= f1(count xi in file 1) +f2(count xi in file 2) +f3(count xi in file 3).
    Group words for words.txt according to their first 4 characters and then output the number of members for the first 10 groups.

