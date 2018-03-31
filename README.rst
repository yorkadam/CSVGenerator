csvgen
======


A command line application that randomly generates values, including mocked address data as CSV
(comma separated Values) output.


Overview
========


This is a quick overview for people not wanting to read the manual file.

In general, this application is a utility for producing data for testing which does not require a database. The data is
output as CSV values and represents a varying set of use-cases.

COMMON USE CASES

1. Entering data in a UI that requires a field which captures product information as CSV values, indicators or numbers.
2. ETL applications where CSV data is needed to test ETL application processes.
3. Database applications, where CSV data is needed to test automation of inserts and database constraints.
4. Spreadsheet applications to test automated spreadsheet imports and external queries common in spreadsheets.
5. Any use-case where you don't have access to a database but need data-sets to test your code.
6. Any import-export automation process which requires output files in CSV format for testing.

Possible Examples

1. A website where users are required to enter defective product identifiers in CSV format for return processing.
2. A database application that bulk processes delivery addresses.
3. A ETL application responsible for scrubbing data and removing duplicate items or addresses.
4. Testing of applications that require minimum and maximum field lengths.


About Data
==========


This application contains compiled data as the basis for generating output data. See the data readme file for how and
where that data was collected. The raw source data was scrubbed and altered to make the data usable in this utility
application. All data was obtained from freely available public sources. All data and licensing is subject to the terms
of the data suppliers covered in the data "read me" file.

Note, that unless otherwise specified in the "read me" file all data is now and was previously under public domain.


License
=======


This application is published under the MIT standard license.


Comments
========


This application is a utility for developers wanting to test data aspects of their software. This is NOT an enterprise
application and should NOT be used in a production environment.  This is a work in progress and may contain bugs or
other oddities including but-not-limited to verbose code that really should be refactored at some point.
It was designed for my use-cases only and may not fit your use-cases so feel free to fork this project, provide feedback,
offer changes etc...
