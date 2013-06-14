"Kubla Khan" Manual Segmentations (Fournier, 2013)
==================================================

In the original text, there are 22 paragraphs, but the version presented to coders contained 21 paragraphs, with paragraphs 4 and 5 merged together as one.  The text contained in this distribution reflects this merging.

Note that the original PDF version of the article "`Stargazers look for life <https://github.com/downloads/cfournie/segmentation.corpora/stargazers_look_for_life.pdf>`", by Baker (1990) is also available.


Files/Folders
-------------

	* ``labels.csv`` -- Segment type labels annotated by Chris Fournier
	* ``poem.txt`` -- UTF-8 text of the peom's lines
	* ``/raw/`` -- Raw Mechanical Turk output 


References
----------

Coleridge (1816)	Samuel Taylor Coleridge. 1816. Christabel, Kubla Khan, and the Pains of Sleep. John Murray.

Fournier (2013)   

.. code-block:: latex

	@book{Coleridge1816,
		title		= {{Christabel, Kubla Khan, and the Pains of Sleep}},
		author		= {Coleridge, Samuel Taylor},
		year		= {1816},
		publisher	= {John Murray}
	}

	@InProceedings{Fournier2013b,
		author    = {Fournier, Chris},
		title     = {{An initial study of topical poetry segmentation}},
		booktitle = {Proceedings of the Second Workshop on Computational Linguistics for Literature},
		month     = {June},
		year      = {2013},
		address   = {Atlanta, Georgia},
		publisher = {Association for Computational Linguistics},
		pages     = {47--51},
		url       = {http://aclweb.org/anthology/W/W13/W13-1407.pdf}
	}
