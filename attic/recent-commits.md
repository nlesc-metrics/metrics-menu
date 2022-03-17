# recent commits

## List of metrics

github commits

## What concept do the metrics capture?

Activity: potential users tend to look for actively maintained software.

## What units is the metric expressed as?

commits

## How is the data gathered?

Github has their own API which provides access to the commit data.

## How is the data aggregated?

We could set an arbitrary period of say 0.5 year, and see if there is any
significant (again arbitrary level) activity.

## How should the numbers be interpreted?

- low v high number of total commits: relates to project age, granularity of commits, number of contributors
- recent commits v no recent commits: relates to activity

## Feasibility / implementation problems

github: implementation is feasible for projects that are public composing the
list of repositories for which to query the GitHub API is probably the biggest
challenge.
