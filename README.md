# TIC-Benchmark
TIC Benchmark Project in R

---
title: "Project 1"
author: "Tsung-Wei (Peter) Chen"
date: "3/27/2020"
---


## Introduction

### Aims

The goal of project is to explore dataset provided by [The Insurance Company (TIC) Benchmark](http://liacs.leidenuniv.nl/~puttenpwhvander/library/cc2000/), which contains insureds' information. The data consists of 86 variables and includes product usage data and socio-demographic data derived from zip area codes. I need to predict the potential customers whether they are potentially interested in a caravan insurance policy or not.

**QUESTION:** Can you predict who would be interested in buying a caravan insurance policy and give an explanation why?  


### Data

There are three datasets in [KDD archive at Irvine](http://kdd.ics.uci.edu/databases/tic/tic.html).

+ [TICDATA2000.txt](http://kdd.ics.uci.edu/databases/tic/ticdata2000.txt): Dataset to train and validate prediction models and build a description (5822 customer records). Each record consists of 86 attributes, containing sociodemographic data (attribute 1-43) and product ownership (attributes 44- 86).The sociodemographic data is derived from zip codes. All customers living in areas with the same zip code have the same sociodemographic attributes. Attribute 86, ”CARA- VAN:Number of mobile home policies”, is the target variable.

+ [TICEVAL2000.txt](http://kdd.ics.uci.edu/databases/tic/ticeval2000.txt): Dataset for predictions (4000 customer records). It has the same format as TICDATA2000.txt, only the target is missing. Participants are supposed to return the list of predicted targets only. All datasets are in tab delimited format.

+ [TICTGTS2000.txt](http://kdd.ics.uci.edu/databases/tic/tictgts2000.txt): Targets for the evaluation set.
