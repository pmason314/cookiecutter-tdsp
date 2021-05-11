# Project Charter

## Business background

* Who is the client?
* What business domain the client is in.
* What business problems are we trying to address?

## Scope

* What data science solutions are we trying to build?
* What will we do?
* How is it going to be consumed by the customer?

## Personnel

* Who are on this project:
  * Our team:
    * Project lead
    * PM
    * Data scientist(s)
    * Account manager
  * Client:
    * Data administrator
    * Business contact

## Metrics

* What are the qualitative objectives? (e.g. reduce user churn)
* What is a quantifiable goal metric?  (e.g. reduce the fraction of users with 4-week inactivity)
* Quantify what improvement in the values of the metrics are useful for the customer scenario (e.g. reduce the fraction of users with 4-week inactivity by 20%)
* What is the baseline (current) value of the metric? (e.g. current fraction of users with 4-week inactivity = 60%)
* How will we measure the metric? (e.g. A/B test on a specified subset for a specified period; comparison of performance after implementation to baseline)

## Plan

* Phases (milestones), timeline, short description of what will be done in each phase.

## Architecture

* Data
  * What data do we expect? Raw data in the customer data sources (e.g. on-prem files, SQL, etc.)
* Data movement tools to move either:
  * all the data,
  * some data after pre-aggregation
  * raw sampled data sufficient for modeling

* What tools and data storage/analytics resources will be used in the solution?
* How will the end solution (e.g. a dashboard or operationalized web service) be consumed in the business workflow of the customer? If applicable, write down pseudo code for the APIs of the web service calls.
  * How will the customer use the model results to make decisions?
  * Data movement pipeline in production
  * Make a one-slide diagram showing the end to end data flow and decision architecture
    * If there is a substantial change in the customer's business workflow, make a before/after diagram showing the data flow.

## Communication

* How will we keep in touch with each other and the client? Weekly meetings?
* Who are the contact persons on both sides?
