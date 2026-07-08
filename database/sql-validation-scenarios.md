# SQL Validation Scenarios

## Purpose

This document contains SQL validation scenarios for the Customer Order Management System.

Each scenario connects a business requirement to a database validation objective.

---

## Scenario 1: Customer Email Uniqueness

### Business Requirement

Each customer email address must be unique.

### Validation Objective

Identify duplicate customer email addresses.

### SQL Query

(To be completed during execution)

### Expected Result

No duplicate email addresses should exist.

### QA Purpose

Validate customer data integrity and prevent duplicate customer records.

---

## Scenario 2: Required Customer Fields

### Business Requirement

Customer records must include first name, last name, and email address.

### Validation Objective

Identify customer records with missing required data.

### SQL Query

(To be completed during execution)

### Expected Result

All required customer fields should be populated.

### QA Purpose

Ensure customer records are complete enough for communication, reporting, and order processing.

---

## Scenario 3: Approved Customer Locations

### Business Requirement

Customer locations should only include approved business locations.

### Validation Objective

Identify customer records with unexpected or invalid locations.

### SQL Query

(To be completed during execution)

### Expected Result

Only approved locations should appear in customer records.

### QA Purpose

Validate data consistency and prevent inaccurate regional reporting.

---

## Scenario 4: Product Price Validation

### Business Requirement

All active products must have a valid price greater than $0.

### Validation Objective

Identify products with missing, zero, or negative pricing.

### SQL Query

(To be completed during execution)

### Expected Result

All active products should have valid pricing greater than $0.

### QA Purpose

Prevent checkout errors, revenue loss, and incorrect catalog data.

---

## Scenario 5: Completed Order Amount Validation

### Business Requirement

Completed orders must have a valid order amount greater than $0.

### Validation Objective

Identify completed orders with invalid or missing amounts.

### SQL Query

(To be completed during execution)

### Expected Result

Completed orders should have valid amounts.

### QA Purpose

Validate order processing, revenue reporting, and payment accuracy.
