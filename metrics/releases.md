# number of releases

## List of metrics

- releases on GitHub
- releases on Zenodo

## What concept do the metrics attempt capture?

- Maturity / Age
- Professionalism
- Activity
- Citability

## What units is the metric expressed as?

- GitHub: count of releases
- Zenodo: count of releases

## How can the data be gathered?

- github: API
- zenodo: API

## How can the data be aggregated?

- github: 
    1. identify the set of our repositories on GitHub (probably most complete via RSD and new-style project pages)
    1. for each item, create a list with date-released and version tag
    1. concatenate all the lists, sort by date-released
    1. accumulate the releases for the last _n_ months, e.g. since previous evaluation report was published
- zenodo: 
    1. identify the set of conceptdois
    1. expand the set of conceptdois to set of versioned dois
    1. for each item, create a list with date-released and version tag
    1. concatenate all the lists, sort by date-released
    1. accumulate the releases for the last _n_ months, e.g. since previous evaluation report was published

## How should the numbers be interpreted?

Similar interpretation to commits, but a releases is more likely to be
internally consistent, stable, working.

- has releases v doesn't have releases: Professionalism, Citability
- low v high number of total releases: relates to Project Maturity/Age
- recent release v no recent release: relates to Activity

## Feasibility / implementation problems

- github:
    - implementation is feasible for projects that are public
    - composing the list of repositories for which to query the GitHub API is probably the biggest challenge.
- zenodo
    - implementation is feasible
    - conditioned on github-zenodo integration
