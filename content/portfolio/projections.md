+++
image = "img/portfolio/projections.png"
showonlyimage = false
date = "2021"
title = "Projections"
draft = false
weight = 2
+++

Collection of executable poetry using Word2Vec to sort ungendered objects by gender.
<!--more-->

![Projections page 4](/img/portfolio/res/proj4.png)

Using word embeddings trained on Twitter with the
Word2Vec algorithm, I turned words into points in high
dimensional space. I then calculated the vector from
“boy” to “girl” and used it to sort collections of other
words from most boyish to most girlish by flattening, or
projecting them onto that vector.

I used this method to create a computer program which
takes collections of previously ungendered words as
input, and outputs graphs of the sorted words, where the
amount of space between each one can be seen relative
to the distance between “boy” and “girl.”

The result is a series of newly gendered things.


Read "Projections" [here](/img/portfolio/res/projections.pdf).

#### About
Prior work has shown that word embeddings can be effective at making [certain kinds of analogies](https://blog.esciencecenter.nl/king-man-woman-king-9a7fd2935a85?gi=1b2f32b87ec8). I was playing around with these locally and thought to calculate the analogy "boy:haha::girl:__", to which the computer provided the answer, "lolol," which I found strange and appropriate.

"Projections" highlights humorous computer insights like this, projected into 2D space, while questioning where our conceptions of gender come from.
