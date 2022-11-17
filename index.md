---
layout: page
title: "Quantifying prediction confidence and domain adaptation on the Wilds dataset"
doodle: "./doodle.png"
permalink: /
---

Data science capstone domain of inquiry (DSC 180AB B03 / B19)

Developed by Alex Cloninger and Yoav Freund

---
* TOC
{:toc}

---

## Introduction

One of the important issues in learning today is the ability to train on one distribution and test on a different one. The WILDS project (https://wilds.stanford.edu/) is devoted to datasets of this type (multiple datasets for the same problem, collected from different setups). The goal of this project is two fold: to distinguish between easy examples (where confident predictions can be made) and hard examples (where the machine should output "I don't know"), and to construct methods that will adapt the test distribution to make trained classifiers more easily deployable on test data.  We will explore different methods, using both labeled and unlabeled data.


## Result replication (introduction to topic)

We will delve into this area via the following papers:

You can find a collection of references [here]({{ "/papers/referencesForTopics" | absolute_url }})

## Section Participation

Participation in the weekly discussion section is *mandatory*. Each
week, you are responsible for doing the reading/task assigned in the
[schedule](#schedule). Come to section prepared to ask questions about
and discuss the results of these tasks.

Each week, turn in answers to the weekly questions to Canvas. These
questions are meant to focus your work for the week and help prepare
you for discussion. If you have questions about your work, please ask
them in section or office hours (I will rarely comment on your
submission).

You are responsible for the entire weekly reading/task, even if
portions are not covered in the weekly questions, as these are designed to help you in your replication. The weekly tasks are the building blocks for the project proposals/assignments due at the
end of the quarter.

---

## Schedule

|Week|Topic|
|--|--|
|1|[Introduction]({{ "/weeks/01-Introduction" | absolute_url }})|
|2|[Ensembles-and-Stability]({{ "/weeks/02-ensembles-and-stability" | absolute_url }})|
|3|[Color Domain Adaptation]({{ "/weeks/03-color-domain-adaptation" | absolute_url }})|
|4|[Sinkhorn Transport and Larger Replication Discussion]({{ "/weeks/04-sinkhorn-and-gaussian-model" | absolute_url }})|
|5|[Differing Densities and Partial Transport]({{ "/weeks/05-differing-densities-partial-transport" | absolute_url }})|
|6|[Boosting]({{ "/weeks/06-Boosting" | "/weeks/06-Boosting" | absolute_url }})|
|7|[Structure of plan for Q2 project]({{ "/weeks/07-Structure-of-plan-for-Q2-project" | absolute_url}})|
|8|[Comparing distributions using trees]({{ "/weeks/08-Comparing-distributions-using-trees" | absolute_url}})|
|9|[]({{ "/weeks/09-" | absolute_url }})|
|10|Present Proposals|

---
## Office Hours
TBD

## Course location
SDSC E-230

## Slack location
TBD





