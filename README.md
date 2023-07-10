# Project Functionality

## `data_analysis.py`
This file contains functions for fetching data from a specified source, performing data analysis using the fetched data and analysis type, and generating a report based on the analysis result. The main function takes command line arguments for the source, analysis type, and report frequency, and prints the generated report.

## `data_fetcher.php`
This PHP file handles AJAX requests and fetches data from the specified source. It also calls the performDataAnalysis function from data_analysis.py to perform data analysis using the fetched data and analysis type. It then calls the generateReport function from report_generator.php to generate a report based on the source, analysis type, report frequency, and analysis result. The generated report is returned as the response.

## `report_generator.php`
This PHP file generates a report based on the specified source, analysis type, report frequency, and analysis result. It is called by data_fetcher.php to generate the report.

## `report_scheduler.php`
This PHP file handles AJAX requests and fetches data from the specified source. It also calls the performDataAnalysis function from data_analysis.py to perform data analysis using the fetched data and analysis type. It then calls the generateReport function from report_generator.php to generate a report based on the source, analysis type, report frequency, and analysis result. The generated report is returned as the response.

## `script.js`
This JavaScript file contains a function generateReport that makes an AJAX request to data_fetcher.php with the source parameter. It then performs data analysis using the performDataAnalysis function and generates a report using the generateReportFromAnalysis function. The generated report is displayed in the reportContainer element.

## `style.css`
This CSS file contains styling rules for the HTML elements used in the project, such as the body, headings, form, labels, select elements, button, and report container.
