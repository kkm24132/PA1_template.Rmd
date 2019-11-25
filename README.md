# Survival Analysis

## Background

- Survival times are typically follow up times from a defined starting point to the occurrence of a given event.
- Use cases:
  - Beginning of a customer-ship to churning of that customer
  - Issue of credit card to customer to first default
  - Start of an insurance policy to it's first claim
  - Time from starting subscription to churning of a telco subscriber
  - Time in employment until attrition
  - Time from current purchase to next purchase of the same product
- Standard statistical techniques do not apply because the underlying distribution is rarely normal and the data are often "censored"

## Business Questions answered by Survival analysis

- What fraction of present customers will be loyal past a certain time frame?
- At what rate will customer churn or attrite?
- How do particular customer characteristics (often called **covariates**) affect the probability of attrition?
- What is the average time spent in the system of a group of individuals?
- What is the comparative time until attrition between two or more groups?
- When will a customer buy a give product next?
- What is the customer lifetime value (CLV) based on their past behaviour ad their profile?

## Survival Analysis Techniques

Scenario   | Approaches
-----------|-------------
Single Group | <ul><li>Life Table (Actuarial Estimation)<li>Kaplan-Meier<li>Nelson-Aalen Cumulative Hazard Estimation</ul>
Comparison of Groups | <ul><li>Logrank Test<li>Wilcoxon Test</ul>
