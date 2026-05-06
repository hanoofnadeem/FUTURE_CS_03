# FUTURE_CS_03 - API Security Risk Analysis

## Track Code
CS (Cyber Security)

## Task Number
Task 3

## API Tested
**JSONPlaceholder API** - `/comments` endpoint
- Base URL: https://jsonplaceholder.typicode.com

## Date
May 4, 2026

## Author
Hanoof Nadeem

## Scope
- Read-only GET requests only
- No exploitation or harmful activities
- Manual testing using browser DevTools

## Tools Used
- **Browser DevTools (F12)** - Inspect API requests, headers, and responses
- **Manual endpoint testing** - ID enumeration and data exposure analysis

## Summary
An API security risk analysis was performed on the JSONPlaceholder API (`/comments` endpoint). Four security risks were identified:

| Severity | Count |
|----------|-------|
| HIGH | 2 |
| MEDIUM | 1 |
| LOW | 1 |

## Key Findings

| # | Finding | Severity |
|---|---------|----------|
| 1 | No Authentication Required | **HIGH** |
| 2 | ID Enumeration | **HIGH** |
| 3 | Excessive Data Exposure | **MEDIUM** |
| 4 | Missing Security Headers | **LOW** |

## Repository Contents
- `report.pdf` - API Security Risk Analysis Report
- `/evidence` - Screenshots from API testing

## How to View the Report
Download `report.pdf` to see complete findings, business impact, and remediation steps.
