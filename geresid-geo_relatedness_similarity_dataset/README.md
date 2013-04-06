Geo-Relatedness and Similarity Dataset (GeReSiD)
---------------

**Authors**: [Andrea Ballatore](http://sites.google.com/site/andreaballatore), David C. Wilson, and Michela Bertolotto

**Keywords**: semantic similarity, semantic relatedness, geo-semantics, ground truth, dataset, geographic terms

**Last update**: Apr 2013

### Abstract

This dataset contains semantic relatedness and similarity judgements on 50 geographic terms. 

### Contents

Dataset two files:

* `GeReSiD-dataset-score_means.txt`: mean scores of relatedness/similarity 
* `GeReSiD-term_mapping-osm-wordnet.txt`


They also contained the polarity values, detected by our systems, expressed in range \[0,1\], where 0 means no relatedness/similarity and 1 maximum relatedness/similarity. 

The full responses in raw text are in folder `raw_data`.
The raw responses of the survey with human subjects are organized in two files:

* `GeReSiD-raw_responses-survey-relatedness-2012.txt`
* `GeReSiD-raw_responses-survey-similarity-2012.txt`

[>> Download zipped dataset <<](https://github.com/ucd-spatial/Datasets/blob/master/downloads/sentiment_detection_hotel_reviews_dataset.zip?raw=true)

These files contain comma-separated tables, easily readable with R, OpenOffice, MS Excel, and similar tools.

The meaning of relatedness/similarity values are the following:

*	`1`		= very unrelated/dissimilar
*	`2,3,4` = intermediate relatedness/similarity
*	 `5`	= very related/similar
*	 `NA`   = not available

`NA` indicates pairs about which the subjects did not express any judgement.

### License

This material is released as [Open Knowledge](http://opendefinition.org/okd).

### Reference

If you use this dataset, please reference this article:

> TODO: article ref

### Contact

For any issue/inquiry about this dataset, please contact Andrea Ballatore at `andrea[dot]ballatore[at]ucd[dot]ie`