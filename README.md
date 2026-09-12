# DemoBlaze Manual Testing Project

## Project Overview

This project demonstrates manual testing activities performed on the DemoBlaze web application.

The main goal of the project is to practice software testing techniques, test case design, test execution, defect reporting, and test documentation.

## Application Under Test

DemoBlaze  
https://www.demoblaze.com/

## Testing Type

Manual Testing

## Testing Scope

The following modules were tested:

- Registration / Sign Up
- Login / Logout
- Product Catalog
- Product Categories
- Product Details
- Shopping Cart
- Order / Purchase
- Contact Us
- Navigation
- UI
- Responsive Layout
- Browser Compatibility

## Test Environment

- Application Type: Web Application
- Browser: Google Chrome
- Operating System: Windows
- Browser Compatibility Testing: BrowserStack

## Test Execution Summary

| Metric | Result |
|---|---:|
| Total Test Cases | 50 |
| Executed Test Cases | 49 |
| Passed | 47 |
| Failed | 2 |
| Not Executed | 1 |
| N/A | 0 |
| Pass Rate | 95.92% |

## Defects Found

During testing, two functional defects were identified:

1. The Order form allows the order to be completed when some required fields are empty.
2. The Contact Us form allows submission when required fields are empty.

Detailed information about these defects is available in the **Bug Reports** sheet in the Excel file.

## Project Deliverables

This repository contains:

- Requirements Document
- Test Cases
- Bug Reports
- Test Execution Summary
- Test Summary Report
- Lighthouse Test Results

## Testing Documentation

### Requirements
The requirements document defines the expected behavior of the application and the testing scope.

### Test Cases
50 test cases were designed to verify the main functionalities of the application.

### Bug Reports
Detailed bug reports were created for the failed test cases.

### Test Execution Summary
The execution results and overall test statistics are documented in the Excel file.

### Test Summary Report
The final testing results, defects, test coverage, and overall conclusion are documented in the Test Summary Report.

## Tools Used

- Google Chrome
- BrowserStack
- Microsoft Excel
- Microsoft Word
- Chrome Lighthouse
- GitHub

## Overall Result

The DemoBlaze website demonstrated generally stable behavior across its main functionalities, with a **95.92% pass rate** among executed test cases.

Two validation issues were identified and should be fixed and retested.
