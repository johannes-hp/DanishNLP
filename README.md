# DanishNLP
Contains three different python programs as well as some sample text files for Natural Language Processing in Danish. Made for an assignment in the [Programming and Search Engines course](https://kurser.ku.dk/course/HLIB0012FU) at the University of Copenhagen. All programs written with Jupyter Notebook.
 
## Frequency lists
The first program generates a frequency list of the words in a text or several texts. The program is built around three different functions. The function file_to_freqlist takes a text file and generates a list of the words in that text. The function freq_calc_get takes a list of words and generates a dictionary, consisting of each unique word and its frequency. The function write_freqlist_to_file lets the user input which text files should be opened and then writes frequency lists for those text files into a new text file.
 
## Lix number calculator
This program consists of two functions. The function calc_lix opens a text file and calculates its lix number. The function write_lix_to_file lets the user input which text files to open and writes the lix numbers for those text files into a new text file.

## Danish stemmer
The third program is a [stemmer](https://en.wikipedia.org/wiki/Stemming) for the Danish language. This program follows the [Snowball algorithm for Danish stemming](http://snowball.tartarus.org/algorithms/danish/stemmer.html). The program is made up of six different functions, each of which represents a step in the algorithm.
