# Part 2: KPI Framework, Business Experiment Analysis & Decision Recommendation

## Business Context

A subscription-based digital product company conducted an A/B experiment to evaluate a new onboarding and activation campaign. Users were randomly assigned to either the Control group (existing onboarding) or the Treatment group (new onboarding). The objective was to determine whether the new onboarding experience should be launched to all users.

## Dataset

* campaign_experiment_data.xlsx

The dataset contains user-level information including experiment group, onboarding behaviour, paid conversion, engagement score, revenue, refunds, support tickets, device type, traffic source, region and plan type.

## North Star Metric

**Paid Conversion Rate**

This metric directly measures how effectively the onboarding experience converts users into paying customers and is closely aligned with business growth.

## KPI Framework

Supporting KPIs include:

* Landing Page Visit Rate
* Trial Start Rate
* Onboarding Completion Rate
* Average Revenue per User
* Average Engagement Score

Guardrail Metrics:

* Refund Rate
* Support Ticket Rate
* Average Days to Convert

## Experiment Analysis

The dataset was reviewed for:

* Missing values
* Duplicate user IDs
* Invalid binary values
* Revenue outliers
* Segment distribution
* Control vs Treatment comparison

Summary metrics were prepared for both experiment groups.

## Hypothesis Testing

A one-tailed hypothesis test was framed to evaluate whether the Treatment group improved the Paid Conversion Rate compared with the Control group using a 5% significance level.

## Recommendation

Based on the experiment analysis, the Treatment group demonstrated stronger business performance across key success metrics. A phased launch is recommended while continuing to monitor guardrail metrics.

## Repository Contents

* Data
* Experiment Analysis Workbook
* Experiment Summary Workbook
* KPI Tree
* Hypothesis Test Notes
* Recommendation Memo
* Screenshots

## Assumptions

* Users were randomly assigned to experiment groups.
* Source data is accurate and complete except for identified quality issues.
* Missing values were reviewed during data quality checks.

## Limitations

* Long-term retention was outside the scope of the experiment.
* Business performance may vary across customer segments.
* Results should be monitored after rollout.

## Screenshots Included

* Summary Metrics
* Hypothesis Test Output
* KPI Tree Preview
