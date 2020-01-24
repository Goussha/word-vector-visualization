# word-vector-visualization


This word vector visualization tool was built to illustrate some of the properties they have.
The vectors themselves were encoded using GloVe model by the good folks at Stanford, ([link to GloVe](https://nlp.stanford.edu/projects/glove/)) 
and this script was heavily inspired by this page [here](https://web.stanford.edu/class/cs224n/materials/Gensim%20word%20vector%20visualization.html), taken from the materials of one of the courses in Stanford.

In short, they trained GloVe model on 400k word corpus obtained from Wikipedia (at 2014) and Gigaword.

I have chosen to use their smallest vectors with the least dimensions (50d), since the difference in performance was insignificant as compared to the difference in file size.
however, you are more than welcome to download the other files from the Glove site ([zip files](https://nlp.stanford.edu/data/glove.6B.zip)) and play around with it.

I changed the functions and made them slower and less efficient, but in doing so, you can see in inside of them and have a better understanding of how they work. I have also changed the plotting tools to pyplot and made some enhancements.

![Image description](link-to-image)
