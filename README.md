# Selenium Extent Report Example
This is an example on using extent reports in selenium TestNG framework. 

## Features

- It is an simple maven based TestNG selenium framework. 
- It uses extent report configuration through .xml file.
- It shows sample report when 3 different type of conditions are met; i.e PASS, FAIL and SKIP.
- It captures an screenshot and saves the screenshot into the report whenever there is an failure.


## Installation

This project requires [Maven](https://maven.apache.org/) to execute the project.
Also it requires [ChromeDriver](https://chromedriver.chromium.org/) based on your latest browser version installed. In this project it uses Google Chrome Browser. 

Install maven and change details of the constants defined in [ReportGeneration.java](src/com/framework/com/tests/ReportGeneration.java) file in codebase as per your local environment.
As per IDE install TestNG plugin and run as a TestNG framework. 

> Please ensure the xpath is correct for the flow as it may change time to time.
