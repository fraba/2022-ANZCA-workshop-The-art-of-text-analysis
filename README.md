Note: I will keep updating this page until the day of the workshop...

### Requirements for attendance

* Bring your own laptop;
* Preinstall [Tableau](https://www.tableau.com/academic/students) (if you are not elegible for a student licence, activate your 14-day trial);
* Familiarise yourself with Tableau (start [here](https://www.tableau.com/learn/get-started/creator) and [here](https://youtu.be/jEgVto5QME8));
* Preinstall [R](https://cran.r-project.org/mirrors.html) and [RStudio](https://www.rstudio.com/products/rstudio/#Desktop) (instructions can be found [here](https://rstudio-education.github.io/hopr/starting.html));
* Familiarise yourself with R and RStudio (you can start by reading the 'The R User Interface' section [here](https://rstudio-education.github.io/hopr/basics.html#the-r-user-interface));
* Install and try to load all the following R packages: 'stm', 'tidyverse', 'tidytext', 'tidytext', 'xml2', 'pdftools', 'stringr', 'gutenbergr', 'jsonlite', 'tsne'. If you don't know how to install a package in R, have a look [here](https://rstudio-education.github.io/hopr/packages.html).

### Suggested pre-readings

* Kong, Q., Booth, E., Bailo, F., Johns, A., & Rizoiu, M.-A. (2022). Slipping to the Extreme: A Mixed Method to Explain How Extreme Opinions Infiltrate Online Discussions. *Proceedings of the International AAAI Conference on Web and Social Media*, 16(1), 524–535. [https://ojs.aaai.org/index.php/ICWSM/article/view/19312](https://ojs.aaai.org/index.php/ICWSM/article/view/19312)  
This is a paper I co-authored. I will discuss it during the workshop so you might want to have a look! **Warning** Mathematical notation is used in the article: Reader discretion is advised.
* Robinson, J. S. D. (2017). *Text mining with R: A tidy approach*. Sebastopol, CA: O’Reilly. [tidytextmining.com](https://www.tidytextmining.com/).  
This is of course a reference text. I would suggest you read the prefance and skim through the rest of the chapters.
* Welbers, K., Van Atteveldt, W., & Benoit, K. (2017). Text analysis in R. *Communication Methods and Measures*, 11(4), 245–265. [doi.org/10.1080/19312458.2017.1387238](https://doi.org/10.1080/19312458.2017.1387238)  
This article gives you a vert good sense of the most common steps and operations in a computational text analysis'. The article offers plenty of R code snippets. You are not required to replicate these steps on your computer - but it might be helpful to try to understand what they do :-)

### Additional readings on R and text analysis

* Wickham, H., & Grolemund, G. (2017). R for data science. Sebastopol, CA: O’Reilly. [r4ds.had.co.nz](https://r4ds.had.co.nz/) and [tidyverse.org](https://www.tidyverse.org/)
* Manning, C. D., Raghavan, P., & Schütze, H. (2008). *Introduction to information retrieval*. New York, NY: Cambridge University Press. [nlp.stanford.edu/IR-book](https://nlp.stanford.edu/IR-book/)


## Date and Location

* 7 July 2022
* Room 5B55a and Room 5B55b, The University of Canberra

## Data 

To download the data 

* "View the project on GitHub" (left column on this page), 
  1. Click on "Code", 
  2. then "Download ZIP". 
  3. Open the ZIP file and navigate to the "data" folder.

* **Twitter data only** Download the data files contained in this [share folder](https://drive.google.com/drive/folders/10WHZxKpxs43dPQChLnX6KDKJJz9FQukd?usp=sharing) (to request access the folder you need a Google account).

## Workshop notes

### Natural language processing

The widespread approach (research and industry) is to divide our text (aka *corpus*) in *documents*. There is no one way to do it. But documents. Documents  tell our models how to make sense of the relations among words (aka *terms*, ≈ *tokens*). 

1. Corpus V
2. Documents V
3. Terms

* *Terms* are not distributed randomly within a *document*;
* *Documents* are not distributed randomly within a *corpus*.

### Research use

1. **Classify**: Clustering "similar" documents together (measuring similarity)
2. **Discovery**: Finding "similar" documents

### Industry use

In addition to the above...
1. **Predict/Complete**: Predict what is the next word/sentence 
2. **Translate**: Predict what's the best sentence to translate a sentence between two languages

### Common NPL approaches (Welbers et al., 2017)

1. Counting (from a dictionary)
2. Supervised machine learning
3. Unsupervised machine learning

### Common NLP techniques

1. Bag-of-words
2.  Lemmatisation (replace words with their lemmas)
3. Part-of-speech tagging
4. Named entity recognition
5. Word positions and syntax

## Contact me

If you have any issue before or after the workshop: francesco.bailo@uts.edu.au.



