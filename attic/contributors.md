# Number of contributors

Counts the number of contributors to a piece of software

## List of metrics

Contributor count from github, unique persons adding an issue to a repo.  

## What concept does the metric try to capture?

The size of the community and bus factor of a piece of software

## What units is the metric expressed as?

Total contributors 

## How is the data gathered ? 

Retrieve numbers from github through API

## How is the data gathered aggregated?

Adding the two lists of unique contributors 

## How should the numbers be interpreted?

How many people contribute to the development, either by writing code or by submitting bug report, feature request, etc. 

## Feasibility / implementation problems

The two separate numbers actual developers vs commenters may also be interesting, as the first is indicative of developer 
community (and thus the bus factor), while the second is indicative of the user community. 
