---
layout: post
title: towards a first experiment - what mental models do people need to interact with biological software?
date: 2019-03-23 14:04:00
tags: notes
---

So, my last meeting helped me come up with a much firmer plan.

- the usability testing I've been planning will probably happen, but not yet.
- there may well be a pre-test testing round where we firm up our ideas more clearly
- before this, let's assess mental models of biological software / data models.
  - biological data models exist, e.g. the intermine data model.
  - advanced users probably have a mental model that is similar to the existing model
  - naive users won't have this model at all, but they probably have *some* mental model that represents biological data. Some hypotheses (I think this is the right word!):
    - people with more computational knowledge are more likely to have a closer mental model
      - especially if they understand SQL, since queries are modelled after sql based queries. _(Maybe this is a bad premise - am I assessing ability to query or just ability to match the models?)_
    - Biological knowledge may help some aspects, e.g. a genes and proteins will always have a relationship.
    - Might the programming languages known or other biological software used affect the understanding of the model?
  - TASKS
    1. Map data from a familiar file format to the InterMine model.
      - familiarity with relevant file formats (GFF, FASTA) will probably affect this. Should all subjects know this data?
      - Familiarity with organism data may help or hinder; suggest we split this so some people work with familiar data and others do not.
    2. Query data from InterMine and retrieve correct results? (not sure if this is needed)
      - this will always be affected by UI - maybe pseudo-query is what is needed? 
