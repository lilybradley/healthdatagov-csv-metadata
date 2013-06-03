healthdatagov-csv-metadata
=====

This is a Ruby script (and quasi-library) that creates an Excel-readable metadata catalog for data sets on [HealthData.gov](http://www.healthdata.gov).

It's super hacky right now, but seems to get the job done! And it even has TESTS!

Overview & Usage
----

* `healthdatagov_metadata_catalog_beta_060213.csv` is the first version of the data catalog
* `create_csv_script.rb` is a simple script that uses the library to create a csv.
* `lib/health_data_catalog.rb` is the workhorse library, with a bunch of functions to break down the task of getting data, processing it, and making a catalog

Other Info
----

This was built by Dave Guarino ([@daguar on Github](https://github.com/daguar), [@allafarce on Twitter](https://www.twitter.com/allafarce)) for the National Day of Civic Hacking 2013.

See LICENSE.md for license (BSD)
