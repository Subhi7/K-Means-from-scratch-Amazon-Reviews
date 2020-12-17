This problem has three aims:
 get more experience with bag-of-words (BOW) and text processing
 learn the TF-IDF transform
 understand k-means clustering
 in terms of coding, get more experience with matrix manipulations.

The data is downloaded from http://jmcauley.ucsd.edu/data/amazon/ and contains 3 topics: baby,
musical instruments, and beauty. Musical instruments is the smallest collection you won't see many
of these when inspecting the results. The original json les are transformed into csv, and contain four
variables, date, summary, review, and rating. In the current context you only need review as we work with
an unsupervised method.

# K-Means-from-scratch-Amazon-Reviews
I am using a dataset of Amazon reviews. It is compiled of three topics and contains approx 200k reviews. You will read those, convert into TF-IDF form, and use k-means clustering to analyze the results. Finally, check the resulting clusters and see how well-defined are the clusters. The trick is that you have to implement TF-IDF and k-means algorithms yourself!

