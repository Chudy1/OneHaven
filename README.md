# OneHaven QA Challenge

## Overview

This project automates testing of the OneHaven Mock API using Postman and Newman.
It includes both positive (happy path) and negative test cases for all endpoints.

## Tools Used

- Postman
- Newman
- Excel (for test case tracking)
- GitHub

## How to Run the Tests

1. Clone this repository.

2. Install Newman:

- npm install -g newman

3. Run the collection:

- newman run automation/OneHaven_QA_Challenge_Mock_API.postman_collection.json -e automation/OneHaven.postman_environment.json -r cli

4. View the results:

- CLI output in terminal
- HTML report in `results/newman-report.html`

## Deliverables

- Test Plan (PDF)
- Test Cases (Excel)
- Postman Collection and Environment
- Newman Report

## AI Usage Summary

# Tool used: ChatGPT (OpenAI)

- What I used it for:

- Drafting and refining the overall test plan and the README content.

- Generating the PDF version of the Test Plan.

## How I validated and edited the AI outputs

- I manually reviewed every piece of AI-generated content before using it in the project.

## Statement of use

- No AI-generated tests or code were submitted without my understanding and verification.

## CI/CD Process

- Github actions is used and the yaml file is at .github\workflows\api-tests.yml
