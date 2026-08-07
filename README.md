# Swag Labs – Manual Testing Portfolio Project

Manual QA testing project performed on the Swag Labs demo e-commerce application, covering test planning, test case design, execution, bug reporting, and traceability — completed entirely without automation, using industry-standard manual testing artifacts.

## Objective

To demonstrate practical manual testing skills — from requirement analysis to bug reporting — by testing a real e-commerce style application end-to-end, following the same process used in professional QA teams.

## Application Under Test

- **Name:** Swag Labs
- **URL:** https://www.saucedemo.com
- **Type:** Demo e-commerce web application

## Scope

Testing covered the following 5 modules:
1. Login
2. Product Catalog
3. Cart
4. Checkout
5. Logout

**Test Environment:** Chrome browser, macOS (MacBook M1)
**Test Data:** 6 user accounts — `standard_user`, `locked_out_user`, `problem_user`, `performance_glitch_user`, `error_user`, `visual_user`

## Test Artifacts

| Artifact | Description | Link |
|---|---|---|
| Test Plan | Scope, environment, test data, schedule | [01_Test_Plan](./01_Test_Plan) |
| Test Scenarios & Test Cases | 10 scenarios, 31 detailed test cases | [02_Test_Cases](./02_Test_Cases) |
| Bug Reports | 4 detailed bug reports with repro steps & screenshots | [03_Bug_Reports](./03_Bug_Reports) |
| Screenshots | Visual evidence of reported bugs | [04_Screenshots](./04_Screenshots) |
| Test Summary Report | Final metrics, analysis, and recommendations | [05_Final_Reports](./05_Final_Reports) |

## Test Execution Summary

| Metric | Value |
|---|---|
| Test Scenarios | 10 |
| Test Cases Executed | 31 |
| Passed | 27 |
| Failed | 4 |
| Pass Rate | 87% |
| Bugs Found | 4 (2 High, 2 Medium) |
| User Accounts Tested | 6 |

## Bugs Found

| Bug ID | Description | Severity |
|---|---|---|
| BUG-001 | Broken images on inventory page (`problem_user`) | Medium |
| BUG-002 | Broken images on product details page (`problem_user`) | Medium |
| BUG-003 | Remove button on inventory page not working (`problem_user`) | High |
| BUG-004 | `locked_out_user` cannot log in — account locked error | High |

## Requirements Traceability Matrix (RTM)

Each requirement was mapped to its corresponding test scenario, test case(s), execution status, and linked bug (if any) — included in the Test Cases workbook under the RTM tab.

## Tools Used

- Google Sheets — Test Cases, RTM, Bug Log, Execution Results
- Google Docs — Test Plan, Bug Reports, Test Summary Report
- Chrome Browser — Test execution
- Snipping Tool — Screenshots

## Key Learnings

- Structured test case design helps catch edge cases that casual testing misses (e.g. account-specific behavior across 6 different user types).
- Clear bug reports with reproducible steps and severity ratings make it easier for developers to prioritize fixes.
- Traceability between requirements and test cases ensures no functionality is left untested.

## Repository Structure

```
swaglabs-manual-testing/
│
├── README.md
├── 01_Test_Plan/
├── 02_Test_Cases/
├── 03_Bug_Reports/
├── 04_Screenshots/
└── 05_Final_Reports/
```

## Author

**Jaimeena R**
GitHub: [github.com/Jaimeena2605](https://github.com/Jaimeena2605)
