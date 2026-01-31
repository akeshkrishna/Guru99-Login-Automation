# Guru99 Login – Hybrid Automation Framework
 Overview

This project is a Hybrid Automation Framework developed using Selenium WebDriver with Java to automate the Login functionality of the Guru99 demo application.
The framework combines Page Object Model (POM), data-driven testing using Excel, and configuration management using properties files to improve maintainability and reusability.

 Application Under Test

Application: Guru99 Demo Site

URL: https://demo.guru99.com/V1/index.php

Module Automated: Login

## Tech Stack

* Java

* Selenium WebDriver

* TestNG

* Maven

* Page Object Model (POM)

* Apache POI (Excel handling)

* Extent Reports (Test Reporting)

## Framework Features

* Hybrid Automation Framework design

* Page Object Model (POM) implementation

* Data-driven testing using Excel

* Centralized configuration using config.properties

* Extent Reports for test execution reporting

* Modular and reusable test components

## Project Structure
```
HybridFramework
│
├── src
│   ├── base
│   │   └── BaseClass.java
│   │
│   ├── pages
│   │   └── LoginPage.java
│   │
│   ├── utils
│   │   ├── ConfigReader.java
│   │   ├── ExcelReader.java
│   │   └── ExtentManager.java
│   │
│   └── tests
│       └── LoginTest.java
│
├── src/config
│   └── config.properties
│
├── testdata
│   └── TestData.xlsx
│
├── reports
│   └── ExtentReport.html
│
├── pom.xml
└── test-output
```
## Test Flow

* Launch browser

* Read browser type and URL from config.properties

* Load login credentials from Excel file

* Open Guru99 login page

* Enter username and password

* Perform login action

* Generate Extent Report

* Close browser

## How to Run

Run LoginTest.java using TestNG


## Reporting
* Report location:

reports/ExtentReport.html

## Purpose of the Project

This project was created to:
* Test execution results are generated using Extent Reports

* Practice Hybrid Framework implementation

* Understand real-world automation framework structure

* Improve skills in Selenium, TestNG, Excel handling, and reporting
