
# AI-Assisted Risk Issue Management

## Executive Summary

This project demonstrates how generative AI and workflow automation could
support risk issue intake, classification, evidence review, remediation
planning, and management reporting.

The solution is designed to assist human reviewers rather than make final
risk decisions. All information used in the demonstration is synthetic.

## Business Problem

Risk issues are often documented inconsistently. Important information may
be missing, classifications may vary among reviewers, and remediation plans
may not clearly address the underlying control gap.

These conditions can create rework, delayed decisions, inconsistent
reporting, and weak audit trails.

## Proposed Solution

The workflow:

1. Receives a synthetic issue description.
2. Summarizes the issue.
3. Recommends a preliminary risk category.
4. Identifies missing information or evidence.
5. Suggests potential control gaps.
6. Drafts possible remediation actions.
7. Routes uncertain or high-risk issues to human review.
8. Records reviewer approval, rejection, or modification.
9. Updates governance reporting.

## Human Oversight

The AI does not:

- Approve issue closure
- Accept risk
- Determine regulatory compliance
- Assign final severity
- Replace independent review
- Make decisions affecting customers or employees

A qualified reviewer remains accountable for all material decisions.

## Controls

- Synthetic data only
- Required human approval
- Confidence and exception thresholds
- Prompt and output logging
- Role-based access assumptions
- Prohibited-data rules
- Output-validation checklist
- Escalation for uncertain or high-risk cases
- Periodic testing and monitoring

## Testing Approach

The prototype is evaluated for:

- Classification consistency
- Missing-information detection
- Unsupported statements
- Appropriate escalation
- Completeness of proposed remediation
- Repeatability
- Human-review agreement
- Failure under ambiguous or adversarial inputs

## Measures of Success

- Reduced issue-intake rework
- Improved documentation completeness
- Faster preliminary triage
- Increased classification consistency
- Percentage of outputs modified by reviewers
- False escalation and missed escalation rates
- User adoption and satisfaction
- Remediation-cycle time

## Tools

List only tools actually used, such as:

- Make
- OpenAI
- Google Sheets
- Power Automate
- Power BI
- Excel
- GitHub

## Limitations

This is an educational prototype, not a production system. It has not been
validated for regulatory, legal, credit, employment, customer, or other
high-impact decision-making.

## Repository Contents

Explain what each folder contains.

## About the Author

Briefly explain your transformation, risk, process-improvement, and
program-management experience.
