Segmentation Corpora Formats
============================


JSON masses
------------
Each *.json file represents annotations for one item (i.e., a document) stored using UTF-8 encoded JSON ([JavaScript Object Notation](http://www.json.org/)) format.  In each JSON file is a list of annotators followed by a sequence of the inner segments with numbers representing their sizes (e.g., figure below).

<pre>
              --------------
Annotator 1: |  2 | 1|   3  |   =>   { 1 : [2, 1, 3] }
              --------------
</pre>


TSV masses
------------
Each *.tsv file represents annotations for one item (i.e., a document) stored using UTF-8 encoded TSV (tabbed separated values) format.  In each TSV file is a column representing the annotator number followed by (for each row following the first column) a sequence of the inner segments with numbers representing their sizes (e.g., figure shown below).

<pre>
              --------------
Annotator 1: |  2 | 1|   3  |   =>    1    2    1    3
              --------------
</pre>


Directories
-----------
- /hearst_1997/ - Segmentations of Stargazers look for life, by David Baker, cite Hearst (1997).


References
----------

Hearst (1997)   Marti A. Hearst. 1997. TextTiling: segmenting text into multi-paragraph subtopic passages, Computational Linguistics 23(1), 33–64. MIT Press.

@article{Hearst1997,
    author  = {Hearst, Marti A.},
    journal = {Computational Linguistics},
    number  = {1},
    passages = {33--64},
    title   = {{TextTiling: segmenting text into multi-paragraph subtopic passages}},
    volume  = {23},
    year    = {1997}
}