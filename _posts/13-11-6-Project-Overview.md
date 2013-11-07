---
layout: post 
title: CSV Project Overview
---

A brief list of the goals of this project, in increasing order of projected difficulty:  

* Take a CSV file, or a collection thereof, and output a list of words and how many times they occur in a given column(s), sorted by that frequency.  This is the core functionality, basic of basics.  
	* Filtering out common [stop words](http://en.wikipedia.org/wiki/Stop_words) is nice here.  
* Allow the user to select which of these words they consider "Tags", and mark each line in the CSV file with those Tags appropriately.  
* Output a single CSV file, rather than one per input file.  

###Enhancements
These are things that would be nice to have, but I can't guarantee in the time I have.  I'm not sure how long it'll take to get the core functionality stable, so all of these are still possible.  

* Choose column based on header, rather than column number.  
* Graphical interface.  
	* File picker  
	* Keyword/tag selector  
	* Column selector  
