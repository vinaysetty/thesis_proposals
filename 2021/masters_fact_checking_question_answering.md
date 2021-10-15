# Fact checking via Question Answering 

## Supervisor: Vinay Setty

## Prerequisites:
  - B or better in at least one of these:
    - DAT550 Data Mining and Deep Learning
    - DAT640 Information Retrieval and Text Mining
    - ELE520 Machine Learning
  - Neccessary skills
    - Python, pandas, sklearn Tensorflow or Pytorch
    - Latex, R or gnuplot (for plots)
  - It is possible to make this a group thesis with 2 students
  
## Problem
  
Fake news has become a huge problem in our lives. Use of AI to detect fake news is one solutions researchers have been exploring. One issue with fake news detection is fact checking the claims made in news articles and social media posts. Fact checking is closely related to question answering for which there is a large body of research. Especially question answering over [Knowledge Graphs](https://en.wikipedia.org/wiki/Knowledge_Graph) such as DBpedia, Wikidata and Freebase. The main tasks of this project are the following:

  - First step is to create a dataset for this task. Given a collection of questions from a dataset such as [LC-quad](http://lc-quad.sda.tech/) convert them into facts to generate true/false facts. For example, "Where was Obama born" with the answer "Hawaii" can be convered into one several true and false facts such as "Obama was born in Hawaii", "Obama was born in USA" as true facts and "Obama was born in Kenya" "Obama was born in New York" as false facts.
  - Now from the dataset created in previous step, train a model to generate questions from claims. Given a textual claim "Barack Obama was born in Africa", reformulate that into one or more questions such as "Where was Barack Obama born"
  - Do entity linking to see if the claim can be checked in using knowledge bases such as DBpedia, Wikidata or Freebase
