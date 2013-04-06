Geo-Relatedness and Similarity Dataset (GeReSiD)
---------------

**Authors**: [Andrea Ballatore](http://sites.google.com/site/andreaballatore), David C. Wilson, and Michela Bertolotto

**Keywords**: semantic similarity, semantic relatedness, geo-semantics, ground truth, dataset, geographic terms, OpenStreetMap

**Last update**: Apr 2013

### Abstract

This dataset contains a-contextual semantic relatedness and similarity judgements on 50 pairs of geographic terms.
For example, term pair `motel` and `hotel` have relatedness=0.93 and similarity=0.9.	The dataset also contains the interrater agreement for each pair (e.g. 0.86 for relatedness, and 0.82 for similarity).
The terms were selected from OpenStreetMap and are mapped to WordNet.
The relatedness/similarity was collected from 203 human subjects on February 2012.

### Contents

The dataset consists of two main files, both available as tab-separated text (.txt) and MS Excel (.xls):

* `GeReSiD-dataset-score_means.txt|xls`: mean scores of semantic relatedness/similarity on 50 pairs of geographic terms. The relatedness/similarity score is the mean of all human subjects, normalised in range \[0,1\], where 0 means no relatedness/similarity and 1 maximum relatedness/similarity.

* `GeReSiD-term_mapping-osm-wordnet.txt|xls`: list of the 97 geographic terms, with mappings to WordNet.

[>> Download zipped dataset <<](https://github.com/ucd-spatial/Datasets/blob/master/downloads/geresid-geo_relatedness_similarity_dataset.zip?raw=true)

### Raw data

The full, raw responses from which these two files were extracted in are in folder `raw_data`.
The raw responses of the survey with human subjects are organized in two files, encoded as tab-separated text:

* `GeReSiD-raw_responses-survey-relatedness-2012.txt`
* `GeReSiD-raw_responses-survey-similarity-2012.txt`

The meaning of relatedness/similarity values is the following:

*	`1`		= very unrelated/dissimilar
*	`2,3,4` = intermediate relatedness/similarity
*	 `5`	= very related/similar
*	 `NA`   = not available

`NA` indicates pairs about which the subjects did not express any judgement.
The raw data contains fully anonymised demographic information about the human subjects (age group, continent of origin, familiarity with Web maps, etc.).

### License

This material is released as [Open Knowledge](http://opendefinition.org/okd).

### Reference

If you use this dataset, please reference this article:

> TODO: article ref

### Contact

For any issue/inquiry about this dataset, please contact Andrea Ballatore at `andrea[dot]ballatore[at]ucd[dot]ie`