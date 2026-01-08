---
layout: page
title: Chronic Disease Prevention
description: Data analytics for the National Diabetes Prevention Program
img: assets/img/research/DPP-new.png
importance: 4
category: research
---

## Chronic Disease Prevention Research

The National Diabetes Prevention Program (DPP) established by the Centers for Disease Control and Prevention (CDC) promotes the implementation of an evidence-based lifestyle change program (LCP) to prevent or delay the onset of diabetes. The LCP is a 12-month program with 26 lessons covering topics on healthy diets, increasing physical activity, managing stress, and coping with triggers, among others.

It includes weekly goal-setting, food and physical activity tracking, and group support. Little is known about the real-world effectiveness of the LCP in different age groups, particularly in older adults. The aim of this study was to evaluate the effects of age on LCP outcomes (weight loss, average physical activity, program attendance) conducted by Virginia Cooperative Extension from 2018 - 2022.

### Data Analysis

The collected data is anonymously stored in the **Data Analysis of Participants System** (DAPS) database. For statistical analysis involving the outcomes of the LCP program, only the participants that completed at least eight sessions in the first 6 months of the program were considered.

Our analysis uses robust Welch-ANOVA tests that work better with unequal variances across groups. If the main effect is observed, pairwise Games-Howell test is administered to establish the effect in different groups.

All data manipulation is performed using Python with data aggregation and cleanup using the Pandas package, statistical tests using Pingouin package, and regressions done using the statsmodels package.

### Results

Among 189 participants enrolled in the LCP, 139 (73%) completed eight or more sessions, and 56% were above 60 years of age. Results show there was a significant direct relationship (coefficient=0.05, p=0.001) between age and weight loss percentage.

Participants older than 60 had significantly (p=0.03) higher average physical activity (215 min per week) compared to those under 60 years old (161 min per week). In addition, participants above 60 had significantly (p=0.03) higher attendance (22 sessions) compared to those under 60 years of age (19 sessions).

These findings suggest that targeting different age groups and intervention delivery methods can improve program outcomes.
