# Urban Scooter – Web Application QA

## Project Overview

Manual testing project for the Urban Scooter web application, focused on the customer information and order placement flow.

The project included requirements analysis, test case design, positive and negative testing, boundary value analysis, equivalence partitioning, cross-browser testing, and defect reporting.

## Testing Activities

1. Analyzed web application requirements for the "Place Order" flow and decomposed the "About Customer" form into testable scenarios covering customer name, last name, address, subway station, and phone number validation.

2. Designed and executed 55 positive and negative test cases using Equivalence Partitioning and Boundary Value Analysis to validate input fields and identify edge cases.

3. Executed test cases in Google Chrome and Opera at 1280×720, verifying form behavior and input validation across supported browsers.

4. Identified and documented 11 defects in Jira, including detailed reproduction steps, expected vs. actual results, and supporting evidence.

## Test Coverage

### First Name

* Latin characters
* Spaces
* Dashes
* Empty input
* Periods
* Commas
* Numbers
* Special characters
* Non-Latin characters
* Minimum and maximum character limits
* Invalid input UI validation

### Last Name

* Latin characters
* Spaces
* Dashes
* Empty input
* Periods
* Commas
* Numbers
* Special characters
* Non-Latin characters
* Minimum and maximum character limits
* Invalid input UI validation

### Address

* Latin characters
* Numbers
* Spaces
* Dashes
* Periods
* Commas
* Special characters
* Non-Latin characters
* Minimum and maximum character limits
* Leading and trailing spaces
* Invalid input UI validation

### Subway Station

* Station suggestions
* Backend-loaded station list
* Empty station field
* Non-existent station search

### Phone Number

* Valid phone numbers with "+"
* Phone numbers without "+"
* Latin characters
* Commas
* Periods
* Special characters
* Non-Latin characters
* Dashes
* Minimum and maximum character limits
* Invalid input UI validation

## Testing Techniques

* Functional Testing
* Positive Testing
* Negative Testing
* Equivalence Partitioning
* Boundary Value Analysis
* Input Validation Testing
* UI Validation Testing
* Cross-Browser Testing

## Test Environment

| Environment       | Configuration |
| ----------------- | ------------- |
| Browser           | Google Chrome |
| Browser           | Opera         |
| Screen Resolution | 1280 × 720    |

## Tools

* Jira
* Google Sheets
* Google Chrome
* Opera

## Test Results

| Metric                           | Result |
| -------------------------------- | -----: |
| Test Cases Designed and Executed |     55 |
| Defects Identified               |     11 |
| Browsers Tested                  |      2 |

## Defect Reporting

Defects were documented in Jira with:

* Steps to reproduce
* Expected result
* Actual result
* Supporting evidence
* Jira bug reference

## Key Findings

The testing identified validation issues involving:

* Last name character limits
* Address character limits
* Empty address validation
* Phone number length validation
* Phone number format validation
* UI validation messages

## Project Documentation
test cases: https://github.com/adiltoncamposm-a11y/Web-Testing-UrbanScooter/blob/f71336c677a55be732edec9a86e65e080bf24b26/Test%20Cases
