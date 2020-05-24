---
layout: post
title: CHAOSS - reading through the metrics and thinking.
date: 2019-12-28 13:25:00
tags: chaoss ols olx sustainability software-sustainability
---

I've been reading the [CHAOSS Metrics](https://chaoss.community/metrics/) (Community Health Analytics Open Source Software) recently. Emmy printed them for me so I could easily annotate them 😍.

Some notes as I think of them:

### Good stuff I probably want to use to measure these projects over time.

1. Is there a GitHub repo (or other) already? Y/N. If Y:
    1. CoC for project
        1. Is there one? (easy to find automatically, manually, other?)
        2. Is there enforcement info?
    2. Is there evidence of mentorship?
        1. programs (GSoC, Outreachy, internships) (Manual assessment required)
        2. people who help out - e.g. first-timers only, hacktoberfest could be good proxy measures. (auto)
        3. contributing md
    3. How old? Is it the oldest repo in the org? Is it even an org, or a user? This may need to be assessed manually on a case-by-case basis
    4. Commit metrics:  
        1. # of lines
        2. # of commits
    5. Review Metrics
        1. \# of PRs
        2. \# accepted / rejected / left open
        3. Median time from open-to-resolved.
    6. Issue/ticket based metrics
        1. \# opened
        2. \# reopened (there are caveats about measuring closed and reopened tickets!)
        3. \# closed
        4. Time to close (?)
    6. Committer Metrics
        1. How many orgs do they come from?
        2. \# of committers
        3. \# loc of commits.
    7. Licence - present, copyleft, permissive?
    8. Velocity. The metrics had number of commits vs number of PRs/issues as velocity. Is this meaningful? (I don't see the point).
    9. Derived from CHAOSS but not directly their metric - also possibly a hard one to measure. Twitter mentions? //todo investigate how hard/easy this is to track.

### Stuff I'm not sure about / maybe dislike / need to think some more

**Licence** - this is where it gets tricky. The metrics discuss number of files without a licence in them. This seems contrived to me as a metrics of sustainability, BUT it justifies things by pointing out that companies may not want to pick up higher risk projects that don't have clear safe licencing processes. It also mentions number of licences, because - logically - this adds legal complexity if some files are licenced one way, some the other. (biopython might be an example here).  

**Testing** hard to assess, but I feel like we should at least check for its presence

**Elephant Factor** I'm not sure I get it. Number of companies that contribute 50% or more of the effort. I should read the paper (Caroline is one of the authors on this!). Update - see [my notes on the paper](2020-01-08-reading-about-elephants) - it's totally irrelephant! 🐘
