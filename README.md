# Manual and Automated QA Project for the Café Aurora Website

In this project, a complete Quality Assurance (QA) process was carried out on the main functionality of the website: https://cafeqaexperience.lovable.app//

The project was developed using KAN agile methodology and BDD (Behavior-Driven Development) for test design before development, following testing best practices.

## Test Plan, Results, and Bug Reports: [View Test Plan](https://irenearribas.atlassian.net/wiki/spaces/KAN/pages/edit-v2/131181)

This document details the test plan, the functionalities tested, the results of the executed tests and the bug reports.

## Technologies

[![Jira](https://img.shields.io/badge/Jira-0052CC?logo=jira&logoColor=fff)](#)

[![Confluence](https://img.shields.io/badge/Confluence-172B4D?logo=confluence&logoColor=fff)](#)

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

[![Playwright](https://custom-icon-badges.demolab.com/badge/Playwright-2EAD33?logo=playwright&logoColor=fff)](#)

## Automated Test Results

A continuous integration workflow has been configured with GitHub Actions to run the tests after every change and once a week.

You can check the latest test execution results and download the test report from the following link:

![Test Workflow](https://github.com/IreneArribasQA/Caf-Aurora-QA-E2E/actions/workflows/playwright_tests.yml/badge.svg)

## Project Requirements

### Python 3.12

Download and install Python 3.12 from the official website:

https://www.python.org/downloads/

Make sure Python is added to the PATH during installation.

### Install Dependencies

Once Python is installed:

1. Clone this repository.
2. Navigate to the project folder.
3. Run the following commands in the terminal:

```bash
pip install -r requirements.txt
```

```bash
playwright install
```

### Run Tests Locally

Navigate to the project folder and run:

```bash
pytest --headed
```

Alternativelly you can use the folowing 

```bash
python -m pytest --headed
```


