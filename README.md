# Distributed-Data-Processing-Analyzing-Datasets-with-MapReduce-and-Apache-Spark-Frameworks
The project focuses on processing a social network dataset and a blog post dataset using MapReduce and Apache Spark frameworks, respectively.

Goals and Objectives:

Process the social graph dataset (graph.txt) to achieve the following:
a. Implement a MapReduce job that creates a list of followers for each user in the dataset.
b. The output should provide a list of followers for each user ID, e.g., the list of followers of user 534 is: [2, 16, 37, 73, 156, 210, 308, 347, 446, 455, 487, 519].

Process the blog post dataset (posts.csv) using the Apache Spark framework to construct an inverted index:
a. Focus on constructing a term-level inverted file where the inverted lists store document IDs and term frequencies.
b. Utilize only the titles of the blog posts from The Unofficial Apple Weblog (TUAW) for creating the inverted index, similar to the InvertedIndex.ipynb notebook.
