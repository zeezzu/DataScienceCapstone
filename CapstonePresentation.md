---
title: "TheNextWord"
author: "Lawrence"
date: "1/1/2018"
output: ioslides_presentation
---

What is TheNextWord?
========================================================

**TheNextWord** is a quick and easy text prediction application.

**TheNextWord** can be implemented on mobile devices and offers advantages over standard text typing:

* Improved typing speed
* Improved spelling and accuracy

TheNextWord Interface
========================================================

![TheNextWord](./figures/TheNextWord.png)

**TheNextWord** allows you to enter a custom word or phrase. Once you click "Predict Next Word", **TheNextWord** displays your selected input before and after processing. 

**TheNextWord** will output the most likely word in red text and a list of possible alternatives.

How does it work?
========================================================

* **TheNextWord** uses the [HC Corpora][1] data set determining word frequency.

* The [HC Corpora][1] data set is screened and processed to removed extraneous characters and then is categorized into the most frequent word combinations (N-grams).

* Using these N-gram frequencies **TheNextWord** can take the user submitted sentences and quickly calculate the most likely next word.

[1]: http://www.corpora.heliohost.org/ "HC Corpora"

References
========================================================

The code to the application can be found on [Github][1]

Working Version of [TheNextWord][2]

The source [HC Corpora][3] data set and associated [ReadMe][4].

[1]: https://github.com/zeezzu/DataScienceCapstone "Github"
[2]: https://zeezzu.shinyapps.io/TheNextWord/ "TheNextWord"
[3]: http://www.corpora.heliohost.org/ "HC Corpora"
[4]: http://www.corpora.heliohost.org/aboutcorpus.html "ReadMe"
