---
layout: project
type: project
image: images/csv.png
title: CSV File Reader
permalink: 
# All dates must be YYYY-MM-DD format!
date: 2018-01-16
labels:
  - Java
  - Query
  - CSV
summary: A CSV File Reader I am working on in ICS 321.
---
<img class="ui square floated image" src="../images/csvTest.png">

For this project I was given a skeleton by my Professor, Lipyeow Lim, and used it to develop a CSV File Reader. Thus far it is able to search through CSV files and return rows of data that either match the given paramaters or exceed the given parameters based on which commands are called. The idea behind the project is to implement effecient ways to process files that are too large to be stored in memory, so three different approaches were taken: Using a filereader and processing the content character by character, Using a bufferedreader and processing the content line by line, Using a compression library to encode the file and then process it. If I had more time to work on it, I could probably make it more efficient by developing a more efficient way to encode the data for the specific schema given.  

The source code can be found [here](https://github.com/jpham79/CSV-File-Reader).
