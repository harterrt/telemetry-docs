# Trainings

The data platform team is developing a set of training to get new users up to
speed quickly and easily.
The trainings closely follow the documentation, but are less thourough.
This section outlines the correspondence between training sessions and documentation.

## Onboarding

This is a quick talk to give new Mozillians a taste of our data.

### Prerequisites
None

### Learning Objectives:
* **Analysis Quick Start** - Attendees should be able to:
  * Comment on our data prinicples
  * Describe what a "main ping" is
  * Navigate TMO and explain what a histogram shows
  * Issue simple queries on STMO

### Documentation:
* Data Principles
* Analysis Quick Start
* Ping Descriptions

## Introduction to Firefox Data

This training is meant to augment the Onboarding training.
After these classes, a new Mozillian should be able to reliably produce simple analyses.

### Prerequisites:
* Onboarding

### Learning Objectives:
* **Data Overview** -
  Attendees should be able to identify the most useful dataset for most types of analyses.
  E.g.:
  * What data should I collect before launching a new feature to Firefox? (experimentation)
  * How many of our users are on Mac? (cross_sectional dataset)
  * What is a reasonable page load time? (TMO & Histograms)
* **Getting Help and Review** - 
  Attendees know why they need review and how to get review for their analyses.
  Attendees know who to ask for review.

### Documentation:
* Choosing a Dataset
* Experimental vs Descriptive Data
* Getting Review: Analysis plans and Data Review
* Overview of Firefox Data Platform Team

## Extending Datasets

This training is meant for engineers who need to collect new data 
or improve the way we aggregate the data.

### Prerequisites:
* Introduction to Firefox Data

### Learning Objectives:
* Atendees have expert knowledge of the data pipeline and will be able to
  extend our data collection

### Documentation:
* Privacy review
* Adding new telemetry probes
* Accessing custom pings
* Modifying the derived datasets

## Advanced Analyses

This training is meant for data scientists and engineers 
who want to use more powerful but complex analysis tools.

### Prerequisites:
* Introduction to Firefox Data

### Learning Objectives:
* Attendees will be able to perform general purpose analyses using ATMO, Spark, and Parquet.
* Attendees will be able to inspect pings in realtime using CEP.

### Documentation:
* Advanced analysis with ATMO
* An Introduction to Spark
* Realtime Analysis with CEP
