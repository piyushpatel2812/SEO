# Search Engine Project

## Description:

Used Java to develop a threaded search engine that tracked user searches, allows users to crawl web pages, and search an inverted index built from crawled web pages.

## Features:
  - Processes all text files in a directory and its subdirectories, cleans and parses the text into word stems, and builds an in-memory inverted index to store the mapping from word stems to the documents and position within those documents where those word stems were found.

  - Supports exact search and partial search. In addition, application can track the total number of words found in each text file, parse and stem a query file, generate a sorted list of search results from the inverted index, and supports writing those results to a JSON file.

  - Supports thread-safe inverted index, and uses a work queue to build and search the inverted index using multiple threads.

  - Supports web crawling and acquiring html

  - Supports User Tracking and stores user history
## Libraries:
  - Apache OpenNLP
  - Apache Log4j 2
  - Apache Commons Lang3
  - Apache Commons Text
  - Eclipse Jetty
  - MariaDB JDBC Driver
