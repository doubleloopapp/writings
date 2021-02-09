---
description: Filling a fundamental gap in product development.
---

# Why you need a source-of-truth for product iterations

Accountants have ledgers. Scientists record their experiments. Marketers have CRMs. Engineers have code version history. Product developers, however, lack a sufficient source-of-truth for their past work. It's a fundamental gap that holds back product management craft.

## What is a "source-of-truth" \(SoT\) for product iterations"?

A SoT for product iterations consists of

1. an accurate timeline of when product changes went live, and
2. metadata describing each change.

## How is it different from a changelog or release notes?

Companies produce changelogs or release notes to communicate the details of product changes to end-users. This is just one important application of your SoT for product iterations.

## What metadata do we need to describe product iterations?

Different companies care about different things, so it's up to each team to decide what metadata is valuable for them. Here are some of the possible data fields for each iteration: 

* Title of the change
* Date it went live
* Summary
* Included code changes
  * Pull requests
  * Commits
* Pictures
* List of people who worked on it
* Hypothesis or goal
* Results
* Success metrics/criteria
* Labels
* List of stakeholders who requested the change
* Audience-tailored messages \(what customers need to know, what sales needs to know, etc..\)

## Why do product builders need a SoT?

A SoT for product iterations provides the data necessary for a variety of applications:

* Correlate past product changes with changes to business metrics. Need to figure out why that metric spiked or dropped? Look in the SoT. 
* Communicate product changes to internal stakeholders like sales, marketing, or customer success.
* Showcase the impact of what you or your team has delivered to executives.
* Understand progress towards product development goals.
* Keep a record of hypotheses and results to feed a scientific product development process.
* Generate a changelog or release notes for users.

## Wait, doesn't a SoT already exist with other tools?

Surprisingly, most product engineering teams lack a good SoT for their product iterations. 

Project management tools, like Jira, have a record of when issues transition to "Done." But when a story is marked "Done," it doesn't necessarily imply that the code was deployed to production. It could be \(1\) waiting in a staging environment, \(2\) merged to master, but not deployed, or \(3\) deployed, but hidden behind a feature flag.

Furthermore, the language in project management tools conveys to engineers how to build something. But it often omits business context or an explanation that is accessible to non-technical folks.

Code versioning tools \(e.g., GitHub\), CI/CD tools \(e.g., CircleCI\), or feature flagging tools \(LaunchDarkly\) help generate an accurate timeline of changes, but they also lack much of the metadata and context you'd want in a SoT.

In sum, today's dev tools leave a trail of technical exhaust, but they don't tell an easy-to-understand story of what happened.

## How DoubleLoop generates a source-of-truth for product iterations

If you require manual labor to generate a SoT, teams simply won't do it. Creating a SoT rarely seems like the most pressing need at the moment, but the value compounds once you have it until it becomes indispensable.

Therefore, DoubleLoop does the heavy lifting for you by generating a SoT based on the output of your current tools \(e.g., GitHub, Jira, CircleCi, LaunchDarkly\). After integrating, you get a timeline of your product iterations that leverages your existing data. DoubleLoop even links together related events across tools, like pull request linked to a Jira issue.

Then, it's up to you how much you want to "enrich" your timeline with more context such as screenshots, goals, hypotheses, and results.

DoubleLoop creates a virtuous cycle of increased clarity that permeates all your tools. E.g., when an engineer writes a commit message, if they know it will appear as the default event title in DoubleLoop, they might write something a bit easier for stakeholders to understand.

To try it out, [install our GitHub app](../instructions/github-setup-instructions.md) our check out the [homepage](https://www.doubleloop.app/). 





