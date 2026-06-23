# Quidax QA Automation Assessment

## Overview

This project contains an automated test suite developed using Cypress and the Page Object Model (POM) design pattern. The objective of the project was to validate key user interactions and functionalities across multiple web components, including forms, dropdowns, alerts, and modal dialogs.

The framework was designed with maintainability, scalability, and readability in mind, allowing test logic and page interactions to remain cleanly separated.

---

## Tech Stack

* Cypress
* JavaScript
* Page Object Model (POM)
* Node.js

---

## Framework Design

The automation framework follows the Page Object Model (POM) architecture, where page-specific locators and actions are abstracted into dedicated page classes.

### Benefits

* Improved maintainability
* Reusable page components
* Reduced code duplication
* Easier test scalability
* Better readability and organization

---

## Test Coverage

### Simple Form Demo

#### Verify Single Input Message Display

* Navigate to the Simple Form Demo page
* Enter a message
* Click "Show Message"
* Verify the exact message entered is displayed

#### Verify Total Calculation

* Enter two positive integers
* Click "Get Total"
* Verify the displayed result matches the expected sum

---

### Select Dropdown List

#### Verify Default State

* Confirm dropdown defaults to "Please Select"
* Verify no day is selected initially

#### Verify Multiple Selection

* Select multiple states
* Verify selected values are successfully chosen within the list

---

### Bootstrap Alerts

#### Verify Success Alert Display

* Trigger a success alert
* Verify alert visibility
* Validate expected success message content

---

### Bootstrap Modals

#### Verify Single Modal Close Functionality

* Open modal
* Verify modal visibility
* Close modal
* Verify modal is dismissed

#### Verify Multiple Modal Workflow

* Launch first modal
* Launch nested modal
* Save changes
* Verify both modals close successfully

---

## Quality Engineering Practices Applied

* Page Object Model implementation
* Explicit assertions
* Reusable page methods
* Structured test organization
* Clean test naming conventions
* Independent test execution
* Maintainable framework architecture

---

## Key Skills Demonstrated

* UI Test Automation
* Functional Testing
* Regression Testing
* Test Design
* Automation Framework Development
* Cypress Automation
* JavaScript
* QA Best Practices

---

## Author

Adeoye Phillip

QA Automation Engineer

This project demonstrates my ability to design maintainable UI automation frameworks and implement reliable automated tests for critical user workflows.
