# Trello API Testing Project

Functional API testing project for the **Trello REST API**, built with **Postman** as part of a QA / Software Testing professional portfolio. The project covers CRUD operations, authentication, response validation, and negative testing across the core Trello resources.

---

## 📌 Overview

Trello is a project management tool that exposes a public REST API for managing Boards, Lists, Cards, Members, Checklists, Labels, and Organizations. This project defines a full manual test cycle for that API — from planning to execution to defect reporting — using Postman as the testing tool.

## 🎯 Objectives

- Validate that core Trello API endpoints behave according to the official API documentation.
- Verify CRUD (Create, Read, Update, Delete) operations across Boards, Lists, and Cards.
- Confirm correct HTTP status codes, response bodies, and headers for valid and invalid requests.
- Validate authentication and authorization handling (API Key + Token).
- Identify and document defects or unexpected API behavior.
- Produce a reusable, well-structured Postman Collection.

## 🧩 Scope

**Resources covered:** Board · List · Card · Checklist · Label · Organization

**Endpoints covered:** 39 endpoints across the resources above, including creation, retrieval, update, membership management, actions/activity, and deletion flows.

**Out of scope:** Performance/load testing, security (penetration) testing, UI testing, exhaustive rate-limit boundary testing, Power-Ups, third-party integrations, and localization testing.

## 🧪 Test Types

Functional · Positive & Negative · Validation · Authentication/Authorization · Smoke · Boundary · Basic Integration

## 📊 Testing Summary

| Metric | Count |
|---|---|
| API Endpoints Covered | 39 |
| Test Scenarios | 84 |
| Test Cases | 127 |
| Bugs Reported | 2 |

## 🛠️ Tools

- **Postman** — manual API testing and collection building
- **GitHub** — hosting and documentation
- **Excel / Google Sheets** — test scenarios, test cases, and bug tracking

## 📁 Repository Structure

```
├── Test_Plan.docx          # Test strategy, scope, entry/exit criteria, risks
├── Test-Scenarios.xlsx     # High-level test scenarios per endpoint
├── Test-Cases.xlsx         # Detailed test cases (steps, data, expected results)
├── Bug-Report.xlsx         # Logged defects with reproduction steps & evidence
└── README.md
```

## 📬 Postman Collection

The full Postman collection with all requests, environment variables, and test scripts is available here:

🔗 **[Postman Collection](https://documenter.getpostman.com/view/38809496/2sBYApxshv)**



## 🚀 How to Use

1. Import the Postman collection using the link above.
2. Set up a Postman environment with your Trello `key` and `token` variables.
3. Run requests individually or use the Collection Runner to execute the full suite.
4. Refer to `Test-Cases.xlsx` for expected results and `Bug-Report.xlsx` for known issues.

## 👤 Author

QA Engineer — built as a hands-on portfolio project demonstrating manual API testing skills with Postman.
