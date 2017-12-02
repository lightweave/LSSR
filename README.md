# The Landscape of Space Science Research (LSSR)
This project started to make a systematic review of developments in space science. We all know that academic reading is hard. Now we have billions of articles issued every year in our beloved journals. Many of them are open and therefore ready to reach our consideration. From time to time every researcher try to improve their reading experience using special techniques. Such techniques include mind maps and similar graph-like systematizing  plots or either paintings [Crystal Renfro 2017](https://doi.org/10.1016/j.acalib.2017.02.004). But of course terms included in mind map cover only one narrow topic. How can we make a unbiased review of current state of whole field of knowledge? Here we make an attempt to do such review using Content Analysis.

## Materials and methods

Primary method of analysis is Gource visualisation program. We apply Gource to a database of terms in space science articles. Appropriate reformatting of articles metadata to involve Gource software:

<https://github.com/acaudwell/Gource/wiki/Custom-Log-Format>

All primary texts and metadata downloaded with **fulltext** package, part of **ropensci** project:

<https://github.com/ropensci/fulltext>



### Library preparing

First we scan all articles for common terms. All high - frequency terms added to the dictionary. https://www.r-bloggers.com/qualitative-text-analysis-in-r-with-rqda/

Every expert collect terms related to separate section of space research. Second the experts analyze dictionary for synonyms and clear his part of dictionary. It is the most time consuming procedure. 

<https://www.r-bloggers.com/qualitative-text-analysis-in-r-with-rqda/>



<https://en.wikipedia.org/wiki/Meta-analysis>
<https://en.wikipedia.org/wiki/Systematic_review>
<https://en.wikipedia.org/wiki/Content_analysis>
<https://www.ncbi.nlm.nih.gov/pmc/articles/PMC539417/>



[Ten Simple Rules for Writing a Literature Review]( http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1003149 )


## Results

Inspirational video <https://www.youtube.com/watch?v=pOSqctHH9vY> presents possible end-point of this review project. Some modifications needed in Gource to acknowledge the magnitude of relationships between terms [CIRCOS ](http://circos.ca/guide/tables/). 
Present a dendrogram of terms in space science.

