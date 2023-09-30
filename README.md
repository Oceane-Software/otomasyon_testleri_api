# otomasyon_testleri_api

This repository contains automated API tests using the REST Assured framework. The tests are organized into packages for ease of use and maintainability.


# Project Structure

endpoints: Contains classes responsible for making HTTP requests to API endpoints.

tests: Houses the actual test cases that use endpoints from the endpoints package.

payload: Stores payload data used in API requests.

utility: Contains utility classes that assist in various testing tasks.

reports: Holds generated test reports.

pom.xml: Maven project configuration file specifying dependencies.

runners: TestNG configuration file for managing test suites.

# Running Specific Test Suites

You can run specific test suites by modifying the testng.xml file under the runners package. Add or remove elements to define the suites you want to run.

# Generating Reports

Test execution reports can be found in the ‘reports’ directory. You can open the HTML report in a web browser to view test results.

