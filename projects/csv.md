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

I was given a skeleton by Professor Lipyeow Lim and am currently developing a CSV File Reader. It is able to search through CSV files in a certain format and return rows of data that either match the given paramaters or exceed the given parameters based on which commands are called. The idea was to implement effecient ways to process files that are too large to be stored in memory, so three different approaches were taken: Using a filereader and processing the content character by character, Using a bufferedreader and processing the content line by line, Using a compression library to encode the file and then process it byte by byte.  

The source code is hidden for now as the professor has extended the due date on the assignment.
