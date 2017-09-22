# Simple search engines

## Introduction
 This code is the submission for the first year project at my university.
 
## Feature:
 
 -Skip a predetermined list of stopwords in the query. Can change the list of stopwords.
 
 -Support intiltle , AND , OR search queries.
 
 -Print out first 10 best result according to a simple rating system base on words appearances.
 
## Drawback

The data structure use for this code is mainly trie (usually work very fast with natural language) therefore the prepare time is slow. 

I have to loop through the entire text to calculate the score for each queries, so sometimes it work slow (depend on the queries)

