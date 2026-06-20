# Incubyte QA Assignment

## Overview

This repository contains the test cases created for the Incubyte QA Assessment.

The objective of this assignment is to test Gmail's **Compose Email** functionality by sending an email with:

* Subject: **Incubyte**
* Body: **QA test for Incubyte**

## Test Coverage

The test cases cover the following scenarios:

### Positive Test Cases

* Gmail login
* Opening Compose window
* Entering valid recipient email address
* Entering subject and email body
* Sending email successfully
* Verifying sent email
* Undo Send functionality
* Sending email to multiple recipients

### Negative Test Cases

* Sending email without recipient
* Invalid email address validation
* Special characters in recipient field
* Blank subject validation
* Blank body scenarios
* Internet disconnection during send
* Draft discard confirmation
* Maximum length validations
* Multiple clicks on Send button
* File attachment validation
* File size limit validation

## Deliverables

* Traditional Test Cases
* BDD Test Cases
* Positive and Negative Test Scenarios

## Assumptions

* User is already registered with Gmail.
* User has valid login credentials.
* Gmail service is available and accessible.
* Internet connection is stable unless explicitly mentioned in a test case.

## Repository Structure

```text
.
├── README.md
└── Gmail_Compose_Test_Cases.xlsx
```

## Author

Ashwini

## Submission

This repository was created as part of the Incubyte QA Assessment.
