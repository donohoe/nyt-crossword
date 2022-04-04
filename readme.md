# Update
- Apologies but the NYT clue data-set is no longer available. 
- Feel free to contact me directly if you have questions. (2/25/2018)


NYTimes Crossword Data
=========

This is a CSV dump of collected data representing clues and answers from The New York Times crossword over almost 16 years.

It spans `December 1993` through to `July 2017`. The data was first collected for a small project to build a [search engine][se] with it. The `clues.txt` files is about 13.1MB in size and contains 432,205 clues with answers.

[se]: http://donohoe.io/projects/crossword/#/git

Data
-----


The data is a tab-delimited CSV with the columns (omitted), in this order:

    "id","thekey","key","source","file","date","day","difficulty","direction","number","instruction","flag","groupid","question","answer"

For example:

    "1048337","Jul2814A24",,"nytimes","Jul2814.puz","2014-07-28 00:00:00","Monday","6","A","24",,"0","nytimes","Cutters that cut with the grain","RIPSAWS"
    "1048338","Jul3015A48",,"nytimes","Jul3015.puz","2015-07-30 00:00:00","Thursday","3","A","48",,"0","nytimes","Ill-looking","PALE"
    "1048336","Jul3015D47",,"nytimes","Jul3015.puz","2015-07-30 00:00:00","Thursday","3","D","47",,"0","nytimes","Like some tea","HERBAL"
    "1048335","Jul2814D23",,"nytimes","Jul2814.puz","2014-07-28 00:00:00","Monday","6","D","23",,"0","nytimes","With great attention to detail","MINUTELY"
    "1048333","Jul2814A22",,"nytimes","Jul2814.puz","2014-07-28 00:00:00","Monday","6","A","22",,"0","nytimes","Portent","OMEN"
    "1048329","Jul2814A20",,"nytimes","Jul2814.puz","2014-07-28 00:00:00","Monday","6","A","20",,"0","nytimes","In the manner of","ALA"


Gaps
-----

There may be gaps in the data. Let me know if you find any.

To do
-----

- Recover 2006. - DONE
- Re-insert day, full-date - DONE
- Across/Down, Clue Numbers (there were enough discrepancies that made it better to commit than include)
