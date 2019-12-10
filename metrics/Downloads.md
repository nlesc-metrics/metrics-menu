# Number of downloads

Count the number of downloads of a piece of software

## What concept does the metric try to capture?

The usage of the software

## What units is the metric expressed as?

Number of downloads per month or year

## How is the data gathered ? 

Retrieve download numbers from github, Zenodo, and relevant package managers (pypi, npm, bintray, conda, etc). 

## How is the data gathered aggregated?

In theory they can be added into a single number, althought this may lead to issues (see below). 

## How should the numbers be interpreted?

They are a proxy for how often the software is "used"

## Feasibility / implementation problems

A significant part of the download numbers may not represent a human user, but an automated process instead. 
For example, Zenodo is harvested by many other sites (openaire, narcis-via-RSD, etc), package managers may be 
mirrored, CI systems may frequently download software for automated testing, etc. Therefore it is difficult 
to estimate the value of a single download number, and the different download numbers may not be directly comparable.

