Segmentation Corpora Formats
============================


TXT files
-----------
Each *.txt file represents the text of one item (i.e., a document) stored using UTF-8, with paragraphs separated by two newline characters and sentences separated by two space characters.


JSON masses files
-----------------
Each *.json file represents multiple codings for one item (i.e., a document) stored using UTF-8 encoded JSON ([JavaScript Object Notation](http://www.json.org/)) format.  In each JSON file is a list of coders followed by a sequence of the inner segments with numbers representing their sizes (e.g., figure below).

<pre>
Coder 1: 
 --------------
|  2 | 1|   3  |   =>   { 1 : [2, 1, 3] }
 --------------
</pre>


TSV masses files
----------------
Each *.tsv file represents multiple codings for one item (i.e., a document) stored using UTF-8 encoded TSV (tabbed separated values) format.  In each TSV file is a column representing the coder number followed by (for each row following the first column) a sequence of the inner segments with numbers representing their sizes (e.g., figure shown below).

<pre>
Coder 1: 
 --------------
|  2 | 1|   3  |   =>    1    2    1    3
 --------------
</pre>