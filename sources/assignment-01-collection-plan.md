# Assignment 01: Collection Plan + Initial Sources

**Name:** Landon Forney
**Date:** August 25, 2026

---

## 1. Topic Statement

I am curating a collection of best practices, workflows, and troubleshooting resources for financial processes within ServiceTitan software. More specifically, I am focusing on areas such as invoicing, payments, job costing, accounting integrations, reconcilliation and book-closing, and inventory management for trade service/construction businesses.
I chose this topic because it is the exact domain in which I work every day as a Financial Integrations Specialist at ServiceTitan. I see these same pain points recurring repeatedly from bookkeepers, owners, office managers, and accountants. This collection is deliberately scoped to specific back-office and financial workflows that maintain clean ledgers and ensure accurate financial reporting and tracking. It deliberately excludes general dispatch, marketing, and non-financial features so the collection can stay practical and focused for those whose primary concern is managing the financial health of their business or assisting ServiceTitan tenants with doing so effectively.

---

## 2. Proposed Collection Structure

### Primary Hierarchy (process-stage categories)

1. Invoicing Workflows
2. Payment Processing & Collections
3. Job Costing & Profitability Analysis
4. Accounting Integrations & Reconciliation
5. Financial Controls & Month-End Closing
6. Inventory Management & Procurement
7. Basic Troubleshooting and FAQ's

### Supporting facets / tags (metadata applied to every source)

- Process Stage: Invoicing, Payment, Job Costing, Accounting Integration, Reconciliation, Financial Controls, Inventory Management, Troubleshooting
- Role: Bookkeeper, Accountant, Office Manager, Owner, Financial Integrations Specialist
- Source Type: Official Help Center, Company Website, Community Forum, Tutorial, Troubleshooting Guide
- Complexity: Basic, Intermediate, Advanced

### Rationale

This hierarchy closely resembles the actual logical flow that bookkeepers and office managers follow in their day to day operations. Invoice > Payment > Costing Analysis > Export/Reconciliation > Period Closing. By organizing the collection in this manner, users can quickly locate resources relevant to each stage of the financial workflow, ensuring efficient access to best practices and troubleshooting guidance. Additionally, the supporting facets and tags provide a consistent way to filter and search for resources based on role, source type, and complexity, further enhancing the usability and navigability of the collection. This system design will keep navigation shallow and usable by avoiding unnecessary deep nesting of categories.

---

## 3. Initial Sources

### Overview of the Invoicing Process
**URL:** https://help.servicetitan.com/docs/overview-of-the-invoicing-process \
**Category:** Invoicing Workflows \
**Tags:** Invoicing, Basic, Official Help Center, Bookkeeper, Accountant, Office Manager, Owner, Financial Integrations Specialist

This official Help Center article goes over the complete ServiceTitan invoicing lifecycle from job booking and invoice generation to batching, posting, and exporting to the accounting software integration of choice. This is a valuable source because it establishes a foundational workflow pattern and common vocabulary. Every later process in the financial workflow, such as payment processing, job costing, and reconciliation, builds upon the concepts introduced here. Office Managers and bookkeepers benefit most from this source as it provides a solid mental model to come back to when they encounter edge cases.\
Limitation: This article is intentionally high-level and does not delve into specific troubleshooting steps or integration hiccups, and thus should be paired with more detailed guides or troubleshooting resources for practical implementation.

### Accounting Integrations Home
**URL:** https://help.servicetitan.com/docs/accounting-integrations-overview \
**Category:** Accounting integrations & Reconciliation \
**Tags:** Accounting Integration, Reconciliation, Intermediate, Official Help Center, Bookkeeper, Accountant, Office Manager, Owner, Financial Integrations Specialist

The central landing page for all ServiceTitan accounting integrations (QuickBooks Desktop, QuickBooks Online, Sage Intacct, Xero, and CSV uploads). It clearly lists supported platforms and points to detailed setup guides for each integration. It is valuable as the authoritative starting point for any integration project and prevents users from chasing outdated external or third-party guides. Intermediate users setting up or auditing an integration will benefit most from this resource. \
Limitation: This page is an overview rather than a deep configuration or troubleshooting document; specific connector issues require consulting the dedicated Web connector guide or the integration specific guides.

### Best Practices on Closing the Books with QuickBooks
**URL:** https://help.servicetitan.com/docs/best-practice-on-closing-the-books-with-quickbooks \
**Category:** Financial Controls & Month-End Closing \
**Tags:** Accounting Integration, Reconciliation, Financial Controls, Intermediate, Official Help Center, Bookkeeper, Accountant, Office Manager, Owner, Financial Integrations Specialist

A practical, sequential checklist for month-end reconciliation between ServiceTitan and QuickBooks (AR, AP, bank accounts, inventory, closing date lock). It is one of the highest value resources for accountants because it translates the abstract concepts of "close the books" into concrete ServiceTitan + QuickBooks actions. Advanced bookkeepers and accountants who perform monthly closes will benefit most from this resource. \
Limitation: This article assumes a clean prior-period state and does not address historical cleanup scenarios that many companies inherit when first implementing this integration.

### Profit Protection for Contractors in 2025
**URL:** https://www.servicetitan.com/blog/webinar-recap-profit-protection \
**Category:** Job Costing & Profitability Analysis \
**Tags:** Financial Controls, Profit Protection, Intermediate, Company Website, Office Manager, Owner

Webinar recap that shows how to use ServiceTitan job-costing reports, material percentage of sales targets, and pricebook bulk-editing tools to protect margins against unexpected cost fluctuations and market changes. It is valuable because it bridges official feature documentation with real contractor decision-making. Intermediate office managers and owners who need to act on cost data and not just report it will benefit most from this resource. \
Limitation: The specific tariff examples are time-sensitive to the 2025 context; the underlying job-costing and pricebook techniques remain relevant, but users should adapt them to current market conditions.

### Applications for Payment & Continuation Sheets
**URL:** https://help.servicetitan.com/docs/complete-application-for-payment-and-continuation-sheet \
**Category:** Payment Processing & Collections \
**Tags:** Invoicing, Payment, Intermediate, Official Help Center, Office Manager, Owner, Financial Integrations Specialist

An overview of the complete application for payment and continuation sheet process in ServiceTitan, explaining how to fill out and submit these forms accurately to manage project progress billing. It is valuable for users who need to ensure proper documentation and timely payment processing for large-scale construction/installation projects. Intermediate users responsible for managing payment applications and progress tracking for projects with retainage will benefit most from this resource. \
Limitation: The guidance assumes familiarity with the overall payment process and may not cover all unique contractual or project-specific requirements; users should adapt the instructions to their specific context.

### Overview of Payments in ServiceTitan
**URL:** https://help.servicetitan.com/docs/payments-overview \
**Category:** Payment Processing & Collections \
**Tags:** Payment, Basic, Official Help Center, bookkeeper, accountants,Office Manager, Owner, Financial Integrations Specialist

An overview of the payments process in ServiceTitan, explaining how to manage and process customer payments efficiently. It is valuable for users who need to ensure accurate and timely payment handling within the platform. Basic users responsible for overseeing payment operations will benefit most from this resource. \
Limitation: The guidance focuses on standard payment workflows and may not cover all specialized payment scenarios; users should adapt the instructions to their specific business needs.

---

## 4. Tool Selection

I will build and publish the collection using GitHub Pages (along with exercise and this assignment 01 in the existing GitHub repository). \ 
GitHub Pages supports clean nesting of pages, proper annotations and linking, easy integration with version control, and straightforward deployment, making it an ideal choice for publishing and maintaining the collection. I am already comfortable with it, so setup and maintenance cost is negligible. The multi-page structure will allow for organized presentation of sections and resources and will allow me to organize content in a logical and user-friendly manner. This GitHub Pages site will continue to serve as the long-term archive and class portfolio for all of my work regarding this knowledge base and other CMPA 4301 assignments.