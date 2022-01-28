+++
draft = false
image = "img/portfolio/spolling.png"
date = "2022"
title = "Spolling Bree"
weight = 1
+++

A parody of the NYT Spelling Bee game which uses only plausible but fake words.
<!--more-->

Play Spolling Bree [here](https://bee.jminjie.com).

#### About

The New York Times [Spelling Bee](https://www.nytimes.com/puzzles/spelling-bee)
is an anagram-ish game in which users use the given letters to form words. The
middle letter must be included in every word.

In order to evaluate how plausible a given made up word is, the Spolling Bree
has used several different models. As a baseline a simple statistical model was
trained on character trigrams from English words. One improvement made upon
this model is an RNN with GRUs which I've trained locally. (This is the model
that is currently deployed.)


![Image from Spolling Bree](/img/portfolio/res/spolling_demo.png)

The source is available [here](https://github.com/jminjie/spollingbree).
