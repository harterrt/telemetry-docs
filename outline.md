# Summary

* [Introduction](README.md)
  * [How to use this book](intro/paths.md)
  * Who is this document for?
    * Anyone who has a question about firefox users
  * Will this solve my problem?
  * Getting help
* [Data Collection & Datasets](data/README.adoc)
  * [An intro to the main ping](data/main_ping_intro.md)
  * Experimental vs Descriptive Data
  * [Dataset Reference](data/reference/README.md)
    * [Cross Sectional](data/cross_sectional/README.adoc)
  * Experimental Data
    * Shield Studies
    * Telemetry Experiments
    * Funnelcakes
  * Descriptive Data
    * Telemetry Pings
      * What is telemetry?
      * Main Ping
        * derived datsets
          * For each:
            * source
            * sampling
            * purpose, non-purpose
          * Telemetry Batch View
          * Mobile datasets?
      * Activity Stream Pings (https://github.com/mozilla/activity-stream/blob/master/data_events.md)
      * non-standard or custom pings (e.g. mitm analysis)
* Concepts and Context
  * Our data collection principals
  * A data informed organization
    * Our values of lean data
    * Policies and Practices
  * The Firefox Data Organization
    * Who's working on this?
    * Who do you ask for help?
      * Expertise
      * Data pod responsibility
    * How do you ask for help?
      * Stages of review
        * Forming Good questions
        * Experiment Design
        * 30% Analysis review
        * 90% Analysis review
      * Mechanics
        * Tools (Bugzilla componenents, file links)
        * SLA
  * The history of telemetry
    * FHR
    * UT
    * ??
  * Working with HyperLogLog Variables
  * Analysis best practices
    * Finding past analyses
    * How to share your analysis
    * Getting review
    * Tips
      * Profile == User
      * User weighting, not session weighting
    * Intro to Cohorts and Funnels
    * review with metrics team
    * Sampling, why and how
* Tools
  * TMO
  * ATMO
  * STMO
* Cookbooks & Tutorials
  * An intro to spark
  * Longitudinal Cookbook
    * exploding arrays
  * Re:dash snippets
    * https://gist.github.com/clarkbw/f0aa27e5d1635b62d49d7dab4f31e842
* Contributing to this book
  * For each section, what are important things to note in an article?
  * Rough layout of a tutorial
  * Style guidelines
  * Colophone
    * Toolchain
    * Code location

# Not included

* Datasets
  * Bugzilla ES Cluster
  * Treeherder Perfherder

# TODO

* What collection services are covered in this document?
  * Services
  * Google Analytics?
* How are the following tools used?
  * Tableau
  * Google Analytics
  * BigQuery

# Resources
* [Hawaii Data Presentations](https://docs.google.com/document/d/1N6macEgoPK87UEVgvGTfXYjBUlLGmoz9t97CMCBCwBo/preview)
* [Metrics Onboarding](https://metrics.mozilla.com/protected/dzeber/tmp/metrics-onboarding.html)
* [Data Guild Training Plan](https://docs.google.com/document/d/1Rnvd8Wv5oXuhZwrMys8ABuOP1eUNrNo-cvJpbcjH5tA/preview)
