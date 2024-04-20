Parsing bolds
---
A set of programs which utilize different Python libraries to obtain a normalized list of bold words from pdf or docx file.

As of the 21st of April, this repository contains 2 programs, uploaded here in .pynb and .py formats, which parse words in bold from the .docx and .pdf types of file. I will elaborate on them in the corresponding order. 

The 'docx-parsing-bolds' programs were written using Python-docx library (https://python-docx.readthedocs.io/en/latest/ & https://github.com/python-openxml/python-docx). I use library-featured objects paragraph and run to split .docx file into pargraphs, then runs, to iterate through them, checking if run is bold, adding to a list. At this point I am highly contingent on the library, which doesn't always make a good a joob. I also wouldn't speak high of its documentation. I normalize obtained list, deleting duplicates, capitalizing words, checking if it's not a number. Finally, I print them using enumerate() function, printing the total count of attained words at the very end. 
