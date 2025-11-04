# Test Plan - OneHaven QA Challenge

## 1. Objectives

To validate that the core user flows of the OneHaven Caregiver System (authentication, device linking, screen-time enforcement, and reporting) work as expected.

## 2. Scope

- **In Scope:** API testing of mock endpoints for login, signup, device linking, screen-time rules, and reports.
- **Out of Scope:** UI testing, real mobile device linking, third-party integrations.

## 3. Test Strategy

- Manual + Automated testing mix.
- Automation using **Postman + Newman**.
- Test levels: Functional, Regression, and API-level smoke tests.

## 4. Entry & Exit Criteria

**Entry Criteria:**

- Mock API imported successfully into Postman.
- Test data prepared (user credentials, device tokens).

**Exit Criteria:**

- All critical test cases pass.
- No open High/Critical severity defects.

## 5. Test Environment

- Postman v10+
- Node.js v18+
- Newman CLI

## 6. Test Data

- `testUserEmail = testuser@onehaven.com`
- `testUserPassword = Pass@123`
- `deviceToken = mockDevice123`

            |
