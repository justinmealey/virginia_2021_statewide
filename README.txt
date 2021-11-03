### Virginia Statewide 2021 Elections

This repo contains the raw diffs (taken in 30 second intervals) of the data posted to https://results.elections.virginia.gov/vaelections/2021%20November%20General/Site/Statistics/Index.html

Since new JSON files are put out with the same data and a new timestamp, the "CreateDate" field is removed and then the resulting data is hashed.  When the scraper checks the file, it looks for a new hash, and if there is one, inserts a new entry into the database.

The larger cities/counties were also individually taken in order to spot check the resultant totals.
