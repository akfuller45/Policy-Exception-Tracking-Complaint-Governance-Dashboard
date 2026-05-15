# Policy-Exception-Tracking-Complaint-Governance-Dashboard

# Policy Exception Tracking & Complaint Governance Dashboard

## Executive Summary

This project simulates an enterprise Policy Exception Tracking and Complaint Governance framework using consumer complaint data.

The purpose of this project is to monitor complaint-related policy exceptions, identify governance control failures, track remediation exposure, assign exception ownership, and create executive-level reporting for compliance, operational risk, and audit readiness.

The project is designed from the perspective of a GRC Analyst, Compliance Analyst, Operational Risk Analyst, Issue Management Analyst, or Internal Controls Analyst working in a financial services environment.

Rather than only analyzing complaint volume, this project transforms complaint data into a policy exception monitoring system that includes exception scoring, remediation tracking, control testing, risk matrix analysis, critical exception registers, and executive dashboarding.

---

## Business Problem

Financial institutions must maintain strong complaint governance processes to ensure timely responses, complete documentation, accurate reporting, and effective issue remediation.

Weak complaint governance may create:

- regulatory exposure
- delayed customer remediation
- incomplete complaint records
- poor audit readiness
- inaccurate management reporting
- unresolved operational issues
- weak policy exception oversight

Without a structured policy exception tracking framework, leadership may not have clear visibility into which complaints require review, escalation, remediation, or control improvement.

This project builds a simulated enterprise issue management framework to identify and monitor these risks.

---

## Project Objectives

The objectives of this project are to:

- Identify complaint-related policy exceptions
- Detect untimely company responses
- Identify missing company response documentation
- Flag disputed complaints
- Monitor missing complaint narratives
- Identify missing state information
- Detect delayed complaint routing
- Identify duplicate complaint records
- Create policy exception scores
- Classify exception severity
- Perform automated policy control testing
- Create a policy exception register
- Build a remediation tracker
- Assign exception ownership
- Assign remediation priority and due dates
- Create a policy exception risk matrix
- Build an executive governance dashboard

---

## Dataset Overview

The project uses consumer complaint data from the Consumer Financial Protection Bureau complaint database.

Key fields include:

| Field | Description |
|---|---|
| `date_received` | Date the complaint was received |
| `product` | Financial product related to the complaint |
| `sub_product` | More detailed product category |
| `issue` | Complaint issue category |
| `sub_issue` | More detailed issue category |
| `consumer_complaint_narrative` | Consumer-provided complaint narrative |
| `company_public_response` | Company’s public response |
| `company` | Company associated with the complaint |
| `state` | Consumer state |
| `submitted_via` | Submission channel |
| `date_sent_to_company` | Date complaint was sent to company |
| `company_response_to_consumer` | Company response category |
| `timely_response` | Whether the company responded on time |
| `consumer_disputed` | Whether the consumer disputed the response |
| `complaint_id` | Unique complaint identifier |

---

## Methodology

The project follows an enterprise policy exception monitoring workflow:

1. Load complaint data from ZIP/CSV
2. Clean and standardize column names
3. Convert complaint date fields
4. Calculate days from complaint receipt to company routing
5. Audit missing values and data completeness
6. Create policy exception flags
7. Calculate policy exception score
8. Classify exception severity
9. Perform automated policy control testing
10. Create policy exception register
11. Build remediation tracker
12. Assign exception owners
13. Assign remediation priority
14. Assign review due dates
15. Flag overdue remediation items
16. Create policy exception risk matrix
17. Export high-risk and critical exception registers
18. Build executive governance dashboard

---

## Policy Exception Indicators

The project evaluates several policy exception indicators.

| Exception Indicator | Description |
|---|---|
| Untimely Response Exception | Company did not provide a timely response |
| Missing Company Response Exception | Complaint lacks documented company response |
| Consumer Disputed Exception | Consumer disputed the company response |
| Missing Narrative Exception | Complaint lacks consumer narrative documentation |
| Missing State Exception | Complaint record lacks state information |
| Delayed Send Exception | Complaint took more than 3 days to be sent to company |
| Duplicate Complaint Exception | Complaint ID appears more than once |

These indicators are used to identify complaints that may require governance review, remediation, or escalation.

---

## Policy Exception Scoring

Each complaint was assigned a policy exception score based on the number of exception indicators present.

| Score | Exception Level |
|---|---|
| 0 | None |
| 1 | Low |
| 2 | Medium |
| 3 | High |
| 4+ | Critical |

This scoring approach helps prioritize complaints based on the number of governance issues associated with each record.

---

## Automated Policy Control Testing

The project includes automated control testing to evaluate complaint governance readiness.

Controls tested include:

| Control ID | Control Name | Risk Area |
|---|---|---|
| CTRL-001 | Complaint ID Present | Data Completeness |
| CTRL-002 | Product Present | Complaint Categorization |
| CTRL-003 | Company Present | Entity Completeness |
| CTRL-004 | Company Response Present | Response Documentation |
| CTRL-005 | Timely Response | SLA / Timeliness |
| CTRL-006 | State Present | Geographic Reporting |
| CTRL-007 | No Duplicate Complaint ID | Reporting Integrity |

Each control was evaluated using:

- total records tested
- records passed
- records failed
- pass rate
- control effectiveness rating

Control effectiveness was classified as:

| Pass Rate | Effectiveness |
|---|---|
| 95% or higher | Effective |
| 85% to 94.99% | Needs Monitoring |
| Below 85% | Ineffective |

---

## Policy Exception Register

A policy exception register was created to capture all complaints with one or more policy exceptions.

The register includes:

- complaint ID
- complaint dates
- product
- issue
- company
- state
- submission channel
- company response
- timely response indicator
- consumer disputed indicator
- policy exception score
- policy exception level
- individual exception flags

This register supports issue management, compliance review, operational risk monitoring, and audit readiness.

---

## Policy Exception Remediation Tracker

A remediation tracker was created to simulate enterprise corrective action monitoring.

Each complaint with one or more policy exceptions was assigned:

- exception owner
- exception status
- remediation priority
- recommended remediation action
- review due date
- overdue remediation flag

This transforms complaint exception analysis into a realistic issue management workflow.

---

## Exception Owner Assignment

Exception ownership was assigned based on the primary exception type.

| Exception Owner | Assignment Logic |
|---|---|
| Complaint Response Management | Untimely response exceptions |
| Consumer Compliance Team | Missing company response exceptions |
| Dispute Resolution Team | Consumer disputed exceptions |
| Complaint Documentation Team | Missing narrative exceptions |
| Data Governance Team | Missing state exceptions |
| Complaint Operations | Delayed send exceptions |
| Governance Data Quality Team | Duplicate complaint exceptions |
| Standard Monitoring | No policy exception |

This simulates how enterprise governance teams route issues to responsible business functions.

---

## Exception Status Classification

Each exception was assigned a status based on severity.

| Exception Level | Exception Status |
|---|---|
| Critical | Escalated |
| High | Remediation Required |
| Medium | Under Review |
| Low | Monitoring |
| None | No Exception |

---

## Remediation Priority

Each exception was assigned a remediation priority.

| Priority | Review Timeline |
|---|---|
| Critical | 7 days |
| High | 14 days |
| Medium | 30 days |
| Low | 60 days |
| None | No review required |

This provides a structured review timeline for issue management and compliance monitoring.

---

## Remediation Actions

Recommended remediation actions were assigned based on exception type.

Examples include:

- Review response workflow and implement SLA escalation monitoring
- Update complaint record with complete company response documentation
- Route complaint to dispute resolution team for secondary review
- Correct missing geographic data and strengthen validation controls
- Investigate duplicate complaint records and perform data quality remediation
- Review complaint routing delay and improve intake-to-company transfer process

---

## Policy Exception Risk Matrix

A policy exception risk matrix was created using an impact and likelihood framework.

### Impact Score

Impact was based on policy exception severity. Complaints with more severe exception levels were assigned higher impact scores.

| Exception Level | Impact Score |
|---|---|
| Low | 1 |
| Medium | 2 |
| High | 3 |
| Critical | 4 |

### Likelihood Score

Likelihood was based on recurring governance weakness indicators, including:

- untimely response
- missing company response
- delayed complaint routing
- duplicate complaint records

### Matrix Score

The matrix score was calculated as:

```text
Impact Score × Likelihood Score = Policy Matrix Score
```

Complaints were then classified into:

- Low
- Medium
- High
- Critical

This matrix supports exception prioritization, escalation decisions, remediation planning, operational risk monitoring, and audit readiness.

---

## Executive Dashboard

The executive dashboard provides a consolidated view of complaint policy exception exposure.

Dashboard components include:

- total complaints
- total policy exceptions
- exception rate
- high exceptions
- critical exceptions
- overdue remediation items
- untimely responses
- delayed sends
- policy exception level distribution
- policy matrix risk distribution
- policy exception risk matrix
- policy exception type counts
- exception ownership by function
- remediation priority distribution
- top products by exceptions
- overdue remediation by product
- failed policy controls

![Policy Exception Governance Dashboard](outputs/charts/policy_exception_governance_dashboard_clean.png)

---

## Key Findings

### Finding 1 — High Exception Rate

A large portion of complaint records contained at least one policy exception. This indicates that complaint governance processes may require enhanced monitoring, exception tracking, or data quality review.

### Finding 2 — Missing Narrative Exposure

Missing complaint narratives represented a significant exception category. While not all complaint records may require narrative text, missing documentation can reduce context available for governance review and complaint analysis.

### Finding 3 — Untimely Response Exposure

Untimely responses were identified as policy exceptions because delayed responses may create regulatory, customer experience, and operational risk exposure.

### Finding 4 — Delayed Complaint Routing

Some complaints experienced delays between receipt and being sent to the company. These delays may indicate intake processing issues, workflow bottlenecks, or routing inefficiencies.

### Finding 5 — Product-Level Exception Concentration

Policy exceptions were concentrated within certain financial products, especially high-volume complaint categories. Product-level views help identify where governance monitoring should be prioritized.

### Finding 6 — Overdue Remediation Exposure

The remediation tracker identified items with review due dates prior to the current date. Since this project uses historical complaint data, overdue remediation is treated as a simulated aging exercise to demonstrate issue management reporting.

### Finding 7 — Failed Control Testing Results

Automated control testing identified failed policy governance controls related to timeliness, response documentation, state completeness, and duplicate complaint prevention.

---

## Recommendations

### Policy Governance Recommendations

- Maintain a centralized policy exception register.
- Monitor exception trends by product, company, issue, and state.
- Standardize exception severity definitions.
- Assign clear ownership for each exception type.
- Review high and critical exceptions on a recurring basis.

### Complaint Operations Recommendations

- Strengthen intake-to-company routing procedures.
- Monitor delayed complaint sends.
- Create escalation rules for delayed complaint routing.
- Review workflow bottlenecks in complaint handling.

### Compliance Recommendations

- Track untimely responses as a formal policy exception.
- Require remediation plans for high and critical exceptions.
- Review complaint response documentation completeness.
- Monitor disputed complaints for escalation and secondary review.

### Data Governance Recommendations

- Improve validation for required complaint fields.
- Review missing state and duplicate complaint records.
- Strengthen data quality controls for complaint reporting.
- Maintain automated control testing outputs as audit evidence.

### Audit Readiness Recommendations

- Export policy exception and remediation registers for audit review.
- Preserve control testing summaries.
- Maintain documentation of exception scoring logic.
- Track review due dates and overdue remediation items.
- Document ownership and remediation actions for high-risk exceptions.

---

## Project Outputs

The project produces the following outputs:

| Output | Description |
|---|---|
| `policy_exception_register.csv` | Register of all complaints with one or more policy exceptions |
| `policy_remediation_register.csv` | Remediation tracker with owner, status, priority, action, due date, and overdue flag |
| `high_risk_policy_exception_register.csv` | Register of high and critical policy exceptions |
| `critical_policy_matrix_register.csv` | Register of complaints classified as critical by the risk matrix |
| `policy_exception_risk_matrix.png` | Impact-likelihood policy exception risk matrix |
| `policy_exception_governance_dashboard_clean.png` | Executive policy exception dashboard |
| `policy_control_testing_summary.csv` | Automated policy control testing summary |

---

## Technology Stack

- Python
- pandas
- numpy
- matplotlib
- Jupyter Notebook
- CSV / ZIP data processing
- GitHub

---

## Project Structure

```text
policy-exception-complaint-governance-dashboard/

│
├── data/
│   ├── raw/
│   ├── cleaned/
│
├── notebooks/
│   └── policy_exception_complaint_governance.ipynb
│
├── outputs/
│   ├── charts/
│   │   ├── policy_exception_governance_dashboard_clean.png
│   │   └── policy_exception_risk_matrix.png
│   ├── tables/
│   │   ├── policy_exception_register.csv
│   │   ├── policy_remediation_register.csv
│   │   ├── high_risk_policy_exception_register.csv
│   │   ├── critical_policy_matrix_register.csv
│   │   └── policy_control_testing_summary.csv
│   └── reports/
│
├── README.md
├── requirements.txt
├── .gitignore
└── LICENSE
```

---

## Suggested `.gitignore`

```text
__pycache__/
.ipynb_checkpoints/
*.pyc

data/raw/
data/cleaned/

.DS_Store
.env
```

---

## Portfolio Value

This project demonstrates skills relevant to:

- Governance, Risk, and Compliance
- Policy exception tracking
- Complaint governance
- Compliance monitoring
- Operational risk analytics
- Issue management
- Remediation tracking
- Control testing
- Audit readiness
- Executive dashboarding
- Data governance
- Business intelligence

---

## Future Enhancements

Potential future improvements include:

- interactive Power BI dashboard
- monthly exception trend analysis
- company-level policy exception scorecards
- issue aging dashboard
- remediation SLA tracker
- audit findings simulation
- automated PDF executive report
- state-level exception heatmap
- product-level governance scorecards
- predictive risk scoring for complaints likely to become high-risk exceptions

---

## Author

Amiranda Fuller

Governance Analytics | Policy Exception Tracking | Complaint Governance | Operational Risk | Data Governance | Business Intelligence
