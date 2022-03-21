# Proposal for implementing the collection of metrics 

As the Netherlands eScience Center grows, keeping track of all the things we do is becoming increasingly difficult. This
is a problem, for example for Program Managers, who need to keep track of what was achieved in a given project.

This document outlines how we can start with keeping track of various metrics. Some key points of the proposed approach are:

1. The list of what we want to keep track of is changable -- it will never be "done".
1. The implementation of how we track metrics is changable -- it will never be "done".
1. The successful implementation of the approach outlined below requires some technical skills, for example for querying
APIs, meaningfully aggregating data, and presenting the data as visualizations, but also requires a good understanding
of what is needed, for example with respect to which categories of the Self-Evaluation Protocol need to be covered, what
the narratives will be for each of these, and how our efforts should be distributed over the various categories.

## Approach

There will be a metrics "menu" that lists all the things we can keep track of. Initially, we focus on metrics related to
software, as well as some metrics related to output and impact from the projects. Some examples:

1. Does a given software package comply with the Five recommendations for FAIR software?
1. For a given software package, what is the monthly download rate from PyPI?
1. For a given software package, what is the bus factor?
1. For a given software package, what is the time between releases?
1. Is a given software package published in a community registry?
1. etc.

The current repository is used to maintain a list of metrics we can track automatically (currently, none). Program
Managers can opt to register outputs from their projects so that the organization can start collecting data on a given
metric in an automated way.

## How it may work in practice

- Niels: "_I want to know the outputs of project X._"

While planning project X, the project stakeholders and program managers can come to an agreement about what metrics are
meaningful given the nature of the project. They can pick and choose from the metrics menu, extending it where
necessary. Initially, they may decide on listing only a few things as output, for example:

1. The software repository on GitHub
1. The ReadTheDocs website that holds user documentation

But when new work is done (or even just planned), project stakeholders and the Program Managers should review the
situation in the project and update the list of things that should be recorded as output. For example, after some time
goes by and some work gets done, they may update the list as follows:

1. The original software repository on GitHub
1. An additional software repository on GitHub
1. The ReadTheDocs website that holds user documentation
1. A package on PyPI
1. Download statistics of the PyPI package
1. The relevant page in a community registry

## How can people propose new metrics?

The preferred way of proposing a new metric is via GitHub's issue tracker on the repository dedicated to metrics
collection at NLeSC https://github.com/nlesc-metrics/metrics-menu. When you make a new issue there, you'll be shown the following:

![issue-types](https://user-images.githubusercontent.com/4558105/157683671-dc9bb5d8-498b-4556-b3c2-abb2d2d1f0ea.png)

After choosing _New metric_, you will be shown the following issue template:

![issue-template](https://user-images.githubusercontent.com/4558105/157683690-b7408934-118d-4723-8906-c2aa3cdade79.png)

The person proposing a new metric can simply fill in the various sections, click _Submit_, and move on with their life.
The Program Managers can subsequently pick up the issue at a time when it is convenient for them. Making issues on
GitHub ensures that there is a public record of what was proposed, of the points raised in the ensuing discussion, and
of whether or not the proposal was added as a new metric.

For a small set of people within the Center, making issues on GitHub is not convenient. For them, simply writing an
email to the Program Managers with a description of the proposed idea suffices; Program Managers can then make the issue
in their name.

## Who can propose new metrics?

In principle, anybody can propose new metrics, but the Program Managers will judge if a proposed metric is a meaningful
addition to the existing list of metrics. In accepting a metric, the Program Managers must weigh the benefit of any new
insights the proposed metric will bring against the cost of the required effort.
