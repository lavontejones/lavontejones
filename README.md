<div align="center">

# Lavonte Jones

### Business Systems • Workflow Automation • FP&A • Data & Integration

I build practical systems that help businesses organize information, automate repetitive work, improve reporting, and turn fragmented processes into reliable workflows.

My work sits at the intersection of **business operations, finance, automation, APIs, data transformation, and decision-support systems**.

<br>

![Python](https://img.shields.io/badge/Python-Automation%20%26%20Data-3776AB?style=flat-square&logo=python&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-Workflow%20Automation-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![API](https://img.shields.io/badge/APIs-System%20Integration-222222?style=flat-square)
![FP&A](https://img.shields.io/badge/FP%26A-Modeling%20%26%20Forecasting-2E7D32?style=flat-square)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-Validation-2088FF?style=flat-square&logo=githubactions&logoColor=white)

</div>

---

## What I Build

I focus on business problems where information is spread across spreadsheets, forms, accounting systems, CRMs, documents, email workflows, or disconnected software.

Typical solutions include:

| Capability | Business Use |
|---|---|
| **Workflow Automation** | Remove repetitive manual steps, standardize processes, route work, and create review controls |
| **API & System Integration** | Move structured information between applications and create reliable system handoffs |
| **Financial Modeling & FP&A** | Forecast cash, model scenarios, compare actual performance with plans, and support management decisions |
| **KPI & Management Reporting** | Turn operating data into useful dashboards and recurring management reporting |
| **Data Reconciliation** | Compare records across systems, identify duplicates and conflicts, and create traceable master datasets |
| **Document Automation** | Generate consistent DOCX, PDF, XLSX, and HTML deliverables from structured information |
| **Business Process Design** | Translate an operating problem into rules, controls, exceptions, and an implementable workflow |

---

## Selected Systems

### Public Implementations

These repositories contain source code and examples you can inspect without signing in. The examples use synthetic or fictional data and illustrate the engineering, business rules, and validation.

#### API Integration Demo

**Inbound request → validation → routing → storage → CRM-ready payload → webhook**

[View API Integration Demo repository](https://github.com/lavontejones/api-integration-demo)

A working reference implementation of a small-business intake and integration system.

It accepts structured requests, validates and normalizes data, detects duplicates, applies routing logic, persists records, produces CRM-ready output, sends local webhook events, and maintains an audit trail.

Demonstrates:

- REST APIs
- structured data validation
- business-rule engines
- duplicate handling
- SQLite persistence
- webhook delivery
- bounded retry logic
- authentication patterns
- logging and auditing
- integration testing

#### Cash Flow Forecasting

**Business assumptions → scenarios → monthly operating forecast → cash outlook**

[View Cash Flow Forecasting repository](https://github.com/lavontejones/cash-flow-forecasting)

A functional FP&A system for building operating scenarios and tracing business assumptions through revenue, collections, expenses, and ending cash.

Demonstrates:

- base, downside, upside, and custom scenarios
- cash forecasting
- operating break-even analysis
- runway calculations
- management reporting
- CSV exports
- HTML reports
- reproducible financial calculations
- automated validation

#### Executive KPI Dashboard

**Operating data → business metrics → management dashboard**

[View Executive KPI Dashboard repository](https://github.com/lavontejones/kpi-dashboard)

A management-reporting dashboard built around a fictional service business.

The dashboard converts synthetic operating data into financial, pipeline, cash, and workforce metrics.

Demonstrates:

- KPI design
- financial and operational reporting
- scenario analysis
- interactive filtering
- data visualization
- synthetic data generation
- Streamlit application development
- automated testing

#### FP&A Toolkit

**Budget + actuals → variance analysis → forecast → management report**

[View FP&A Toolkit repository](https://github.com/lavontejones/fpa-toolkit)

A lightweight management-planning toolkit for comparing budget and actual performance and producing a driver-based 12-month cash outlook.

Demonstrates:

- budget versus actual analysis
- favorable/unfavorable variance logic
- driver-based forecasting
- scenario assumptions
- management reporting
- deterministic financial calculations

---

### Private Project Summaries

These summaries describe projects with private repositories. The related public examples come from separate implementations. All examples use synthetic data and illustrate technical behavior.

#### Document Production Engine

**Structured information → controlled document generation → validation → finished deliverables**

**Private repository**

A deterministic document-generation system that produces **DOCX, PDF, XLSX, and HTML** outputs from structured content and reusable design rules.

**Technical scope**

- multi-format document generation
- reusable document components
- spreadsheet formulas, tables, charts, and validation
- automated render and layout checks
- version-controlled output
- machine-readable build manifests
- document QA workflows

The FP&A Toolkit generates an HTML management report from fictional inputs. See the [walkthrough](https://github.com/lavontejones/fpa-toolkit/blob/main/docs/DEMO.md) and [sample HTML report source](https://github.com/lavontejones/fpa-toolkit/blob/main/docs/sample-report.html).

#### Customer Data Reconciliation Engine

**CRM data + accounting data → identity resolution → customer master → review queue**

**Private repository**

A reconciliation engine built around **1,000 synthetic CRM records and 1,000 synthetic accounting records**.

The system validates, normalizes, compares, matches, and reconciles customer records while preserving source evidence and uncertain cases for human review.

**Technical scope**

- data validation and profiling
- duplicate detection
- deterministic and fuzzy matching
- conflict resolution
- confidence scoring
- human-review routing
- data lineage
- audit trails
- reproducible outputs
- automated testing

Related public examples include [duplicate checks and uncertain customer matches in the API Integration Demo](https://github.com/lavontejones/api-integration-demo/blob/main/docs/architecture.md) and [synthetic bank reconciliation and exception review in the Finance Operations demo](https://github.com/lavontejones/finance-operations-intelligence-engine/blob/main/docs/case-study.md).

#### n8n Automation Workflows

**Business event → validation → business rules → decision → controlled output**

**Private repository**

A collection of synthetic n8n workflow demonstrations covering common small-business operating processes.

Current examples include:

- lead intake and scoring
- weekly KPI reporting
- invoice follow-up logic
- CRM duplicate detection
- operations health monitoring

See the Finance Operations demo’s [inactive n8n template for a synthetic review task](https://github.com/lavontejones/finance-operations-intelligence-engine/blob/main/n8n/finance-review-gate.json).

---

## How the Systems Fit Together

```mermaid
flowchart LR
    A[Business Inputs] --> B[Validate & Normalize]
    B --> C[Business Rules]
    C --> D{Decision / Exception}
    D --> E[Automation]
    D --> F[Human Review]
    E --> G[System Output]
    F --> G
    G --> H[Dashboard / Report]
    G --> I[API / CRM / Workflow]
    G --> J[Document / Spreadsheet]
    G --> K[Audit Trail]
```

The technology is only one layer.

The larger objective is to build a system that answers five questions:

1. **What enters the process?**
2. **What rules should apply?**
3. **What can happen automatically?**
4. **What requires human judgment?**
5. **How can the result be verified later?**

---

## Business Problems I Am Interested In

I am particularly interested in projects involving:

- repetitive administrative workflows
- spreadsheet-heavy operating processes
- fragmented customer or financial data
- manual reporting
- CRM cleanup and migration preparation
- lead intake and routing
- document-heavy workflows
- system-to-system data movement
- financial planning and forecasting
- recurring management reporting
- process standardization
- exception and approval workflows
- internal business tools

---

## Technical Approach

My preferred architecture is deliberately practical:

```text
Input
  ↓
Validation
  ↓
Normalization
  ↓
Business Rules
  ↓
Automation
  ↓
Exception Handling
  ↓
Output
  ↓
Validation / Audit
```

I favor systems that are:

**Understandable**  
A business user should be able to understand what the system is doing.

**Testable**  
Important rules should be independently verifiable.

**Traceable**  
The system should preserve enough evidence to explain how an output was produced.

**Controlled**  
Automation should distinguish between deterministic actions and decisions that require human review.

**Maintainable**  
Logic should not depend on one person remembering undocumented steps.

**Adaptable**  
Business rules, thresholds, mappings, and assumptions should be configurable when practical.

---

## Tools & Technologies

### Automation & Integration

`n8n` • `REST APIs` • `Webhooks` • `JSON` • `CSV` • `HTTP`

### Development & Data

`Python` • `SQL` • `SQLite` • `Pandas` • `Git` • `GitHub`

### Financial & Analytical

`Excel` • `FP&A` • `Financial Modeling` • `Scenario Analysis` • `KPI Design`

### Applications & Reporting

`Streamlit` • `HTML` • `XLSX` • `DOCX` • `PDF`

### Quality & Delivery

`GitHub Actions` • `Automated Testing` • `Validation` • `Audit Trails` • `Synthetic Test Data`

---

## What the Portfolio Is Designed to Demonstrate

This portfolio is not intended to show isolated coding exercises.

The projects are designed to demonstrate the ability to move through the complete problem:

```text
Business Problem
      ↓
Process Analysis
      ↓
Data / System Design
      ↓
Business Rules
      ↓
Implementation
      ↓
Testing
      ↓
Business-Facing Output
```

That distinction matters.

A technically functional script is useful.

A system that is **technically functional, understandable to the business, tested, auditable, and designed around the actual operating problem** is substantially more valuable.

---

## Portfolio Principles

All public demonstrations use synthetic or fictional data.

Public repositories are intentionally separated from:

- client information
- private business records
- production credentials
- confidential financial information
- live customer systems

Where a repository models a production workflow, the documentation identifies the controls that would still be required before real deployment.

---

<div align="center">

### Public Portfolio

[API Integration Demo](https://github.com/lavontejones/api-integration-demo) ·
[Cash Flow Forecasting](https://github.com/lavontejones/cash-flow-forecasting) ·
[Executive KPI Dashboard](https://github.com/lavontejones/kpi-dashboard) ·
[FP&A Toolkit](https://github.com/lavontejones/fpa-toolkit)

</div>
