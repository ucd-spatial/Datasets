Geo-Relatedness and Similarity Dataset (GeReSiD)
---------------

**Authors**: [Andrea Ballatore](http://sites.google.com/site/andreaballatore), David C. Wilson, and Michela Bertolotto

**Keywords**: semantic similarity, semantic relatedness, geo-semantics, ground truth, dataset, geographic terms

**Last update**: Apr 2013

### Abstract

This dataset is the results of the related user study has as goal to encourage the cross-validation of our results including input data and sentiment model generated by our system.

### Contents

The dataset contains a subset of user-generated reviews .
The 14 selected reviews have been divided in two groups and assigned to different groups of real users for polarity evaluation purposes about a subset of features (also randomly selected).
The hotel reviews in raw text are in folder `corpus` (`reviews_A` and `reviews_B`).

[>> Download zipped dataset <<](https://github.com/ucd-spatial/Datasets/blob/master/downloads/sentiment_detection_hotel_reviews_dataset.zip?raw=true)

The raw responses of the survey with human subjects are organized in two files:

* `survey_results_A.txt`
* `survey_results_B.txt`

These files contain comma-separated tables, easily readable with R, OpenOffice, MS Excel, and similar tools.

Each of the results file contains the reported polarity values detected by users for each considered feature and for each considered review:
The meaning of polarity values are the following:

*	`-1`	= very bad
*	`-0.5`	= bad
*	 ` 0.5`	= good	
*	 ` 1` 	= very good
*	 `NA`	= not available

They also contained the polarity values, detected by our systems, expressed in range \[-1,1\], where -1 means very bad and 1 very good. 
`NA` indicates a feature that is not discussed in the review.

### License

This material is released as [Open Knowledge](http://opendefinition.org/okd).

### Reference

If you use this dataset, please reference this article:

> TODO: article ref

### Contact

For any issue/inquiry about this dataset, please contact Andrea Ballatore at `andrea[dot]ballatore[at]ucd[dot]ie`