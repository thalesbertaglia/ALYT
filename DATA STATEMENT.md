# Data Statement for ALYT

Data set name: Abusive Language on YouTube (ALYT)

Citation:

```
@inproceedings{bertaglia-etal-2021-abusive,
    title = "Abusive Language on Social Media Through the Legal Looking Glass",
    author = "Bertaglia, Thales  and
      Grigoriu, Andreea  and
      Dumontier, Michel  and
      van Dijck, Gijs",
    booktitle = "Proceedings of the 5th Workshop on Online Abuse and Harms (WOAH 2021)",
    month = aug,
    year = "2021",
    address = "Online",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2021.woah-1.20",
    doi = "10.18653/v1/2021.woah-1.20",
    pages = "191--200"}
```

 
Data set developer(s): Thales Bertaglia, Andreea Grigoriu, Michel Dumontier, Gijs van Dijck

Data statement author(s): Thales Bertaglia and Andreea Grigoriu

## A. CURATION RATIONALE 

The corpus is composed by YouTube comments mostly in English extracted from videos about three topics -- Veganism, Gender Identity, and Workplace Diversity.
We selected the videos manually based on the number of comments and the channel popularity. We split the videos into three categories: Personal, Official, and Reaction videos. 

We initially retrieved all comments from the videos (excluding replies), then filtered comments which had less than three words or contained URLs. 
Finally, we randomly sampled 20k comments to be annotated.

- Time periods:
 - The publication date of the videos ranged from 2016 to 2019.
 - We collected the comments between April and May of 2020.

## B. LANGUAGE VARIETY/VARIETIES

Most of the comments are in English, but a few might be in other languages.

* BCP-47 language tag: en
* Language variety description: many varieties, including non-native speakers.

## C. SPEAKER DEMOGRAPHIC

N/A
 
## D. ANNOTATOR DEMOGRAPHIC

The annotators were students enrolled in a Law programme at an European university. 

## E. SPEECH SITUATION

N/A

## F. TEXT CHARACTERISTICS

YouTube comments (only top comments, no replies included); messages from 3 to 1293 words, with an average of 31. We removed comments with less than 3 words and comments with URLs. 

## G. RECORDING QUALITY

N/A

## About data statement document

A [data statement](https://www.aclweb.org/anthology/Q18-1041/) is a characterization of a dataset that provides context to allow developers and users to better understand how experimental results might generalize, how software might be appropriately deployed, and what biases might be reflected in systems built on the software.

Data Statements are from the University of Washington. Contact: [datastatements@uw.edu](mailto:datastatements@uw.edu). The markdown Data Statement we used is from June 4th 2020. The Data Statement template is based on worksheets distributed at the [2020 LREC workshop on Data Statements](https://sites.google.com/uw.edu/data-statements-for-nlp/), by Emily M. Bender, Batya Friedman, and Angelina McMillan-Major. Adapted to community Markdown template by Leon Dercyznski.
