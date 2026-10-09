# BPMN Project Assignments

## Overview

This repository contains BPMN (Business Process Model and Notation) diagrams for three business process scenarios. Each assignment models the normal workflow and identifies possible failure scenarios with their proposed solutions.

## Assignments

### 1. Student Project Approval & Allocation System
Models the process of submitting project proposals, validating submissions, reviewing proposals, approving topics, allocating faculty guides, and notifying students.

**Key failure scenarios:**
- Incomplete or invalid proposals
- Duplicate project topics
- Missed deadlines and delayed reviews
- Proposal rejection or revision
- Faculty guide unavailability or rejection
- System and notification failures
- Withdrawal after approval

### 2. Logistics & Shipment Exception Management
Models the shipment lifecycle from booking and pickup to transportation, delivery, and shipment closure.

**Key failure scenarios:**
- Pickup failures and incorrect addresses
- Damaged or lost parcels
- Transit delays and customs holds
- Recipient unavailability
- Delivery refusal or cash-on-delivery failure
- Tracking and scanning failures
- Cancellation after dispatch

### 3. Loan Origination & Approval System
Models the loan application process, including document verification, identity checks, credit assessment, underwriting, offer acceptance, agreement signing, and fund disbursement.

**Key failure scenarios:**
- Incomplete documents and identity mismatches
- Fraud and AML screening issues
- Credit bureau service failures
- Low credit scores and insufficient income
- Collateral valuation issues
- Offer expiration and applicant withdrawal
- E-signature and disbursement failures

## BPMN Concepts Used

The diagrams use BPMN elements such as:

- Start and end events
- User tasks, service tasks, and business rule tasks
- Exclusive, parallel, and inclusive gateways
- Timer, error, and message events
- Retry loops and escalation paths
- Compensation activities
- Swimlanes to represent process participants

## Tools

- **Camunda Modeler** — to open and edit BPMN diagrams
- **BPMN 2.0** — process modeling notation
- **GitHub** — project version control and submission

## How to Open the Diagrams

1. Download or clone this repository.
2. Open Camunda Modeler.
3. Select **File → Open File**.
4. Choose the required `.bpmn` file.
5. Review or edit the process diagram.

## Project Objective

The objective is to model complete business workflows, identify realistic failure scenarios, and represent appropriate resolutions using BPMN 2.0 notation.

---

**Project:** BPMN Project Assignments  
**Format:** BPMN 2.0  
**Purpose:** Workflow modeling and exception management
