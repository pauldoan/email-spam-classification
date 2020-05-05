# Final Project - Machine Learning 
# A Baseline for Spam Classification with Naive Bayes

Author: *Paul Doan (pqd2001)*


# The Objectives

**Context**

Email spam defined as unsolicited email messages by a sender with no previous relationship to the receiver represents between 50% and 70% of all email traffic over the last few years (see email statics). Given the significant waste of network bandwidth, computer resources and recipients time a significant amount of effort has been invested developing au- tomated methods to detect and filter spam messages. Spam email filtering techniques can be based on explicit hand written rules detecting patterns in messages (i.e if message contains cheap VIAGRA it is spam); based on white and/or black lists of email addresses from, respectively, known relationship of the recepient and well know spam senders, finally, statistical approaches based on machine learning have beem also attempted.
Statistical (machine Learning) based spam detectors have a long history due to their ability to handle large quantities of unstructured text and the simplicity of their implementation.
Some well known spam detectors use a combination of machine learning and black list filtering rules to provide state of the art spam detection.
In this project I will build a spam detector based in simple Naive Bayes classifier techniques. My focus will not be to build a state of the art spam detector, rather, I will focus on creating a baseline model for spam classification.

# The data

The full dataset can be found here: 
- https://trec.nist.gov/data/spam.html

The notebook produced in this project works with the native structure of the TREC datasets.

# References and useful links

scikit-learn documentation: https://scikit-learn.org/stable/documentation.html

