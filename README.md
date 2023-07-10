# Project Functionality

## `data_analysis.py`
This file contains functions for fetching data from a specified source, performing data analysis using the fetched data and analysis type, and generating a report based on the analysis result.

## `data_fetcher.php`
This PHP file handles AJAX requests and fetches data from the specified source. It also calls the performDataAnalysis function from data_analysis.py to perform data analysis using the fetched data and analysis type.

## `report_generator.php`
This PHP file generates a report based on the specified source, analysis type, report frequency, and analysis result. It is called data_fetcher.php to generate the report.

## `report_scheduler.php`
This PHP file handles AJAX requests and fetches data from the specified source.

## `script.js`
This JavaScript file contains a function generateReport that makes an AJAX request to data_fetcher.php with the source parameter.

## `style.css`
This CSS file contains styling rules for the HTML elements used in the project.
