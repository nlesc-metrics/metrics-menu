# Proposal for implementing the collection of metrics 

As the Netherlands eScience Center grows, keeping track of all the things we do is becoming increasingly difficult. This is a problem, for example for:

1. Directors, who need to inform themselves about the state of the organization in order to steer the organization effectively;
1. Program Managers, who need to keep track of what was achieved in a given project;
1. Community Managers, who want to know what is being worked on in the Center at large;
1. Policy Advisors, who need to prepare various reports;
1. TechLeads, who need to know the state of a given software package;
1. etc.

This document outlines how we can start with keeping track of various metrics. Some key points of the proposed approach are:

1. The list of what we want to keep track of is changable -- it will never be "done".
1. The implementation of how we track metrics is changable -- it will never be "done".
1. The successful implementation of the approach outlined below requires some technical skills, for example for querying APIs, meaningfully aggregating data, and presenting the data as visualizations, but also requires a good understanding of what is needed, for example with respect to which categories of the Self-Evaluation Protocol need to be covered, what the narratives will be for each of these, and how our efforts should be distributed over the various categories.

## Approach

There will be a metrics "menu" that lists all the things we can keep track of. Some examples:

1. compliance with fair-software.nl for a given software package
1. monthly rate of PyPI downloads for a given package
1. number of peer-reviewed papers that were produced in a project (output)
1. number of peer-reviewed papers that were produced based on what we did in a project (impact)
1. geographic diversity of our call program
1. institutional diversity of our call program
1. number of training materials published in Journal of Open Source Education (or similar)
1. number of members of NL-RSE 
1. number of contributions to policies at Digital Competence Centers
1. duration of employment
1. long-duration sick leave
1. etc.

<!--  
and then what do we do with the metrics list
-->

## Some examples of how it may work in practice

### Directors example

- Rob: "_I want to know the total number of releases made on GitHub across all of our projects in 2020._"

TODO

- Monique: "_I want to know the number of people who were on sick leave for longer than 20 days in 2020._"

TODO

### Program Managers example

- Niels: "_I want to know the outputs of project X._"

While planning project X, the project stakeholders and program managers can come to an agreement about what metrics are meaningful given the nature of the project. They can pick and choose from the metrics menu, extending it where necessary. Initially, they may decide on listing only a few things as output, for example:

1. Software repositories on GitHub
1. Workshops

But when new work is done (or even just planned), project stakeholders and the Program Managers should review the situation in the project and update the list of things that should be recorded as output. For example, after some time goes by they may update the list as follows:

1. Software repositories on GitHub
1. Workshops
1. Packages on PyPI
1. Peer reviewed papers

### Community Managers example

Mateusz: "_I want to know how many trainings we've given this year._"

TODO

### Policy Advisors example

Tom: "_I want to support the "Our software is sustainable" narrative in the SEP report with numbers._"

TODO

### Tech Lead example

Jason: "_I want to know if software package X has any license clashes with its own dependencies._"

TODO

## How can people propose new metrics?

The preferred way of proposing a new metric is via GitHub's issue tracker on the repository dedicated to metrics collection at NLeSC https://github.com/nlesc/metrics. When you make a new issue there, you'll be shown the following:

![issue-types](https://user-images.githubusercontent.com/4558105/157683671-dc9bb5d8-498b-4556-b3c2-abb2d2d1f0ea.png)

After choosing _New metric_, you will be shown the following issue template:

![issue-template](https://user-images.githubusercontent.com/4558105/157683690-b7408934-118d-4723-8906-c2aa3cdade79.png)

The person proposing a new metric can simply fill in the various sections, click _Submit_, and move on with their life. The Program Managers can subsequently pick up the issue at a time when it is convenient for them. Making issues on GitHub ensures that there is a public record of what was proposed, of the points raised in the ensuing discussion, and of whether or not the proposal was added as a new metric.

For a small set of people within the Center, making issues on GitHub is not convenient. For them, simply writing an email to the Program Managers with a description of the proposed idea suffices; Program Managers can then make the issue in their name. 

## Who can propose new metrics?

In principle, anybody can propose new metrics, but the Program Managers will judge if a proposed metric is a meaningful addition to the existing list of metrics. In accepting a metric, the Program Managers must weigh the benefit of any new insights the proposed metric will bring against the cost of the required effort.
