# Project 01: Curated Collection

**Name:** Landon Forney  
**Course:** CMPA 4301 – Information Organization  
**Date:** September 10, 2026

Public sources for ServiceTitan financial workflows in trade service and construction businesses. Browse by process stage. Each annotation describes what the source covers, why it is in the collection, who should use it, and what it does not cover.

**Source types in this collection:** Official Help Center guides and hubs, official reports/tools, official troubleshooting pages, a company blog / webinar recap, and a practitioner forum thread.

## Contents

1. [Invoicing Workflows](#1-invoicing-workflows)
2. [Payment Processing & Collections](#2-payment-processing--collections)
3. [Job Costing & Profitability Analysis](#3-job-costing--profitability-analysis)
4. [Accounting Integrations & Reconciliation](#4-accounting-integrations--reconciliation)
5. [Financial Controls & Month-End Closing](#5-financial-controls--month-end-closing)
6. [Inventory Management & Procurement](#6-inventory-management--procurement)
7. [Basic Troubleshooting and FAQs](#7-basic-troubleshooting-and-faqs)

---

## 1. Invoicing Workflows

### 1. [Overview of the Invoicing Process](https://help.servicetitan.com/docs/overview-of-the-invoicing-process)
**Creator:** ServiceTitan Help Center  
**URL:** [https://help.servicetitan.com/docs/overview-of-the-invoicing-process](https://help.servicetitan.com/docs/overview-of-the-invoicing-process)  
**Category:** Invoicing Workflows  
**Tags:** Invoicing, Basic, Official Help Center, Bookkeeper, Office Manager, Financial Integrations Specialist

**What it covers:** Official walkthrough of the ServiceTitan invoicing lifecycle: A completed job produces an invoice that can be reviewed, batched, posted, and exported to the connected accounting system. It names the stages later pages assume - especially batch, post, and export - without walking through every screen.

**Why it's valuable:** This is the vocabulary page for the whole collection. Payments, job costing, and month-end close only make sense if you already know that an invoice is not “in the books” until it has been exported. Without this model, troubleshooting pages look like a pile of unrelated errors.

**Who would benefit:** New bookkeepers, office managers, and support staff should read this first. It is the happy-path map before anyone opens a red Web Connector or a QBO deposit mismatch.

**Limitations:** It is high-level on purpose. It does not cover refunds, applications for payment, inventory on the invoice, or failed exports. Pair it with "Understand invoice statuses" to see what Pending, Posted, and Exported actually lock, and with "Batch, post, and export transactions" when the invoice needs to leave ServiceTitan.

---

### 2. [Understand invoice statuses](https://help.servicetitan.com/docs/understand-invoice-statuses)
**Creator:** ServiceTitan Help Center  
**URL:** [https://help.servicetitan.com/docs/understand-invoice-statuses](https://help.servicetitan.com/docs/understand-invoice-statuses)  
**Category:** Invoicing Workflows  
**Tags:** Invoicing, Basic, Official Help Center, Bookkeeper, Office Manager

**What it covers:** Explains the status fields on a ServiceTitan invoice header: review, sent, paid, batch, export (Pending, Posted, Exported), and accounting period (Open or Closed). Pending invoices are fully editable. Posted invoices allow only limited detail changes unless the batch is unposted. Exported invoices cannot be edited; the documented fix is an adjustment invoice.

**Why it's valuable:** This page turns the invoicing overview into something you can use on a live record. When a tenant says “I cannot change the invoice,” the answer is usually the export status, not a missing permission. That distinction is what support and bookkeepers need at the same time.

**Who would benefit:** Bookkeepers who batch daily, office staff who edit invoices after the job is done, and specialists diagnosing “why won’t this save.”

**Limitations:** It does not list every posting error. Missing technicians, empty batches, and connector failures live on the troubleshooting pages. Period Closed also blocks edits even if the invoice is not exported. Pair this with "Batch, post, and export transactions" and with "Batch will not post or accept invoices."  

---

## 2. Payment Processing & Collections

### 3. [Payments Home](https://help.servicetitan.com/docs/payments-overview)
**Creator:** ServiceTitan Help Center  
**URL:** [https://help.servicetitan.com/docs/payments-overview](https://help.servicetitan.com/docs/payments-overview)  
**Category:** Payment Processing & Collections  
**Tags:** Payment, Basic, Official Help Center, Bookkeeper, Office Manager

**What it covers:** Hub for collecting and managing payments in ServiceTitan: Card, ACH, and check from the office or mobile; applying and unapplying credits; refunds and voids through the payment portals. It also points to setup for online payments, merchant portals, and the permissions required to create or apply a payment.

**Why it's valuable:** Invoicing without this page is only half the cash cycle. Deposits, credits, and refunds are what later show up as mismatches in QuickBooks. The hub is the official map of those workflows before you open a report or a forum thread.

**Who would benefit:** Office staff who take payment, bookkeepers who apply credits, and owners who want technicians collecting in the field.

**Limitations:** It is a landing page, not a refund procedure. Many refund and deposit details require extra configuration. Payments that have already been exported generally cannot be unapplied. Pair it with the invoicing overview on the way in and with the r/Bookkeeping QBO thread when deposits do not match the bank.  

---

### 4. [Applications for Payment & Continuation Sheets](https://help.servicetitan.com/docs/complete-application-for-payment-and-continuation-sheet)
**Creator:** ServiceTitan Help Center  
**URL:** [https://help.servicetitan.com/docs/complete-application-for-payment-and-continuation-sheet](https://help.servicetitan.com/docs/complete-application-for-payment-and-continuation-sheet)  
**Category:** Payment Processing & Collections  
**Tags:** Invoicing, Payment, Intermediate, Official Help Center, Office Manager, Owner, Financial Integrations Specialist

**What it covers:** Guides commercial and construction projects through AIA-style progress billing: An Application for Payment plus a Continuation Sheet (schedule of values) created together on the project. It covers work completed, stored materials, retainage percent, approval, and generating the progress invoice after the customer signs off.

**Why it's valuable:** Residential invoicing pages do not explain this workflow. Shops that bill by percent complete need this page or they invent a process that never exports cleanly. It is also the public explanation of retainage, which later appears in WIP and over/under billing.

**Who would benefit:** Office managers, project admins, and bookkeepers on install or commercial work. Owners who review pay apps should know what the form is locking.

**Limitations:** Account configuration is required. Retainage percent cannot be changed after the second AFP. Inventory-tracked item prices are restricted. If a progress invoice is generated too early, do not post or export it until the AFP is right. Pair with the WIP report and Financial Dashboard for the month-end view of the same projects.  

---

## 3. Job Costing & Profitability Analysis

### 5. [Run job costing reports](https://help.servicetitan.com/docs/run-job-costing-reports)
**Creator:** ServiceTitan Help Center  
**URL:** [https://help.servicetitan.com/docs/run-job-costing-reports](https://help.servicetitan.com/docs/run-job-costing-reports)  
**Category:** Job Costing & Profitability Analysis  
**Tags:** Job Costing, Intermediate, Official Help Center, Bookkeeper, Accountant, Owner

**What it covers:** Shows how to build job costing from the Jobs report template: Material, equipment, purchase order and bill costs, returns, payroll, performance pay, and labor burden, then compare total cost to revenue. Lines are jobs; cost columns drill into the POs or labor behind the number.

**Why it's valuable:** This is the official “is this job profitable” tool. Inventory and payroll only matter to the ledger if they land in these columns. Owners who only look at invoice total miss the cost side this report is built to show.

**Who would benefit:** Accountants, bookkeepers, and owners reviewing completed work. Office managers who price the next job can use the same columns.

**Limitations:** Payroll and labor burden need account setup; include both carelessly and you double-count. Invoice items not mapped to income GLs do not count as revenue, so margin looks wrong even when the invoice total is right. Pair with Inventory and Purchase Orders Home for the cost feed, and with Profit Protection when the numbers mean a pricebook change.  

---

### 6. [Profit Protection for Contractors in 2025](https://www.servicetitan.com/blog/webinar-recap-profit-protection)
**Creator:** ServiceTitan (blog / webinar recap)  
**URL:** [https://www.servicetitan.com/blog/webinar-recap-profit-protection](https://www.servicetitan.com/blog/webinar-recap-profit-protection)  
**Category:** Job Costing & Profitability Analysis  
**Tags:** Job Costing, Intermediate, Company Website, Office Manager, Owner

**What it covers:** Webinar recap on protecting contractor margins in 2025: job-costing reports, material as a percent of sales, and bulk pricebook edits when material costs jump. It is written as owner advice, not as a field-by-field report guide.

**Why it's valuable:** It connects the job costing report to a decision—raise prices, edit the pricebook, or stop selling work that loses money. Official report pages stop at columns. This page says what to do with the columns.

**Who would benefit:** Owners and office managers who already run costing and need to act. Bookkeepers can use it to explain why a margin target exists.

**Limitations:** The tariff examples are time-stamped to that webinar. The report and pricebook habits remain useful; the market story does not. This is company marketing next to Help Center documentation, not a close checklist and not a substitute for the job costing report article. Read the report page first, then this.

---

## 4. Accounting Integrations & Reconciliation

### 7. [Accounting Integrations Home](https://help.servicetitan.com/docs/accounting-integrations-overview)
**Creator:** ServiceTitan Help Center  
**URL:** [https://help.servicetitan.com/docs/accounting-integrations-overview](https://help.servicetitan.com/docs/accounting-integrations-overview)  
**Category:** Accounting Integrations & Reconciliation  
**Tags:** Accounting Integration, Intermediate, Official Help Center, Bookkeeper, Accountant, Financial Integrations Specialist

**What it covers:** Landing page for ServiceTitan accounting connections: QuickBooks Desktop, QuickBooks Online, Sage Intacct, Xero, and CSV export. Each product links to its own setup guide. It is the official list of what is supported.

**Why it's valuable:** This is the first page a shop should open before buying a connector story from a blog or a reseller. QBD, QBO, and Intacct are not the same project. Starting here keeps people off leftover instructions for a product they do not run.

**Who would benefit:** Office managers choosing an integration, bookkeepers auditing a live connection, and specialists checking supportability.

**Limitations:** It will not configure a company file or clear an export error. Desktop Web Connector crashes, QBO Touchless mapping errors, and Intacct setup all live on child pages. Vendor bills and some payment types also do not export to QBO the same way they do to Desktop. Use this to pick a path, then open Batch, post, and export plus the matching troubleshooting page.

---

### 8. [Batch, post, and export transactions](https://help.servicetitan.com/docs/batch-post-and-export-transactions)
**Creator:** ServiceTitan Help Center  
**URL:** [https://help.servicetitan.com/docs/batch-post-and-export-transactions](https://help.servicetitan.com/docs/batch-post-and-export-transactions)  
**Category:** Accounting Integrations & Reconciliation  
**Tags:** Accounting Integration, Intermediate, Official Help Center, Bookkeeper, Accountant, Financial Integrations Specialist

**What it covers:** Step-by-step for the daily accounting move: Create a batch, review invoices and other transactions, post the batch, then export to QuickBooks or Intacct. Batches can include invoices, payments, vendor bills, inventory transfers, adjustments, and returns. Best practice is daily, with office staff building the batch and accounting posting it.

**Why it's valuable:** This is the hinge of the collection. Everything before it prepares a transaction; everything after it assumes the transaction already left ServiceTitan. Invoice statuses only make sense in light of this page.

**Who would benefit:** Bookkeepers and accountants who export, and office staff who add invoices to a batch.

**Limitations:** Invoices on unfinished jobs do not appear to batch. After export, the batch cannot be edited; use an adjustment invoice. Vendor bills and payment records do not export to QuickBooks Online the same way they do to Desktop. Pair with Understand invoice statuses on the way in and with the Web Connector or QBO Touchless error pages when export fails. Always verify the export in the target accounting system to catch discrepancies early.

---

### 11. [ServiceTitan push into QBO – What issues have you seen?](https://www.reddit.com/r/Bookkeeping/comments/1uqux5a/servicetitan_push_into_qbo_what_issues_have_you/)
**Creator:** r/Bookkeeping community thread  
**URL:** [https://www.reddit.com/r/Bookkeeping/comments/1uqux5a/servicetitan_push_into_qbo_what_issues_have_you/](https://www.reddit.com/r/Bookkeeping/comments/1uqux5a/servicetitan_push_into_qbo_what_issues_have_you/)  
**Category:** Accounting Integrations & Reconciliation  
**Tags:** Accounting Integration, Troubleshooting, Intermediate, Community Forum, Bookkeeper, Accountant

**What it covers:** Bookkeepers describing live QBO sync pain: deposits on a ServiceTitan report that never hit the bank, bank deposits missing from ServiceTitan, auto-batched payments, and refunds that do not export unless someone unposts and rebuilds the deposit.

**Why it's valuable:** Names failure modes official docs understate, including that an exported batch cannot be edited in ServiceTitan. That is the counterweight to the clean integrations overview.

**Who would benefit:** Bookkeepers mid-reconciliation and support staff who need the tenant’s language for “the books don’t match.”

**Limitations:** Unmoderated anecdotes, mixed expertise, no guaranteed steps. Treat it as a symptom list, then confirm against Help Center and the tenant’s export type (document vs journal entry).

---

## 5. Financial Controls & Month-End Closing

### 12. [Best Practices on Closing the Books with QuickBooks](https://help.servicetitan.com/docs/best-practice-on-closing-the-books-with-quickbooks)
**Creator:** ServiceTitan Help Center  
**URL:** [https://help.servicetitan.com/docs/best-practice-on-closing-the-books-with-quickbooks](https://help.servicetitan.com/docs/best-practice-on-closing-the-books-with-quickbooks)  
**Category:** Financial Controls & Month-End Closing  
**Tags:** Reconciliation, Financial Controls, Intermediate, Official Help Center, Bookkeeper, Accountant

**What it covers:** Month-end sequence for tying ServiceTitan to QuickBooks: AR, AP, bank accounts, inventory, and setting a closing-date lock so posted periods stop changing.

**Why it's valuable:** Turns “close the books” into concrete ServiceTitan-plus-QuickBooks actions instead of generic accounting advice. This is the page that makes the rest of the workflow pay off.

**Who would benefit:** Bookkeepers and accountants who close monthly and need a repeatable checklist.

**Limitations:** Assumes a clean prior period. It will not walk a shop through inherited mess: duplicate customers, old unexported batches, or years of unreconciled inventory. Conversion jobs still need a cleanup plan first.

---

### 13. [Understand the Financial Dashboard](https://help.servicetitan.com/docs/understand-the-financial-dashboard)
**Creator:** ServiceTitan Help Center  
**URL:** [https://help.servicetitan.com/docs/understand-the-financial-dashboard](https://help.servicetitan.com/docs/understand-the-financial-dashboard)  
**Category:** Financial Controls & Month-End Closing  
**Tags:** Financial Controls, Intermediate, Official Help Center, Accountant, Owner

**What it covers:**  

**Why it's valuable:**  

**Who would benefit:**  

**Limitations:**  

---

### 15. [Work in Progress (WIP) report](https://help.servicetitan.com/docs/work-in-progress-wip-report)
**Creator:** ServiceTitan Help Center  
**URL:** [https://help.servicetitan.com/docs/work-in-progress-wip-report](https://help.servicetitan.com/docs/work-in-progress-wip-report)  
**Category:** Financial Controls & Month-End Closing  
**Tags:** Job Costing, Financial Controls, Advanced, Official Help Center, Accountant, Owner

**What it covers:**  

**Why it's valuable:**  

**Who would benefit:**  

**Limitations:**  

---

## 6. Inventory Management & Procurement

### 14. [Inventory and Purchase Orders Home](https://help.servicetitan.com/docs/inventory-and-purchase-orders)
**Creator:** ServiceTitan Help Center  
**URL:** [https://help.servicetitan.com/docs/inventory-and-purchase-orders](https://help.servicetitan.com/docs/inventory-and-purchase-orders)  
**Category:** Inventory Management & Procurement  
**Tags:** Inventory Management, Intermediate, Official Help Center, Bookkeeper, Office Manager, Owner

**What it covers:** Hub for purchasing and inventory: creating purchase orders, receiving, vendor bills, transfers, counts, serialized items, and replenishment. Notes the difference between the Purchasing module and full Inventory.

**Why it's valuable:** Job costing and AP only stay honest if parts and POs are recorded correctly. This page fills a category that was empty in Assignment 01 and connects field material use to the ledger.

**Who would benefit:** Office managers and bookkeepers who handle vendor bills, truck stock, and job material cost. Owners who want to know why job profit does not match the invoice.

**Limitations:** Module availability varies by account. Some shops only have Purchasing, not full Inventory. Three-way matching and vendor-catalog details live on child pages, not on this hub.

---

## 7. Basic Troubleshooting and FAQs

### 9. [Web Connector Troubleshooting Guide](https://help.servicetitan.com/docs/web-connector-troubleshooting-guide)
**Creator:** ServiceTitan Help Center  
**URL:** [https://help.servicetitan.com/docs/web-connector-troubleshooting-guide](https://help.servicetitan.com/docs/web-connector-troubleshooting-guide)  
**Category:** Basic Troubleshooting and FAQs  
**Tags:** Troubleshooting, Accounting Integration, Intermediate, Troubleshooting Guide, Bookkeeper, Financial Integrations Specialist

**What it covers:** Common QuickBooks Desktop Web Connector failures during batch export: crashes, connection color mismatches, “could not connect to QuickBooks,” and the usual install, user, and certificate fixes.

**Why it's valuable:** This is the public page people need when the happy-path integration guide is useless. It is also the closest official match to the batching, posting, and export errors that show up in support work.

**Who would benefit:** Bookkeepers who export from the office and support staff diagnosing a red connector or a batch that will not leave ServiceTitan.

**Limitations:** QuickBooks Desktop only. QBO and Intacct use different error paths. Some fixes still end with “contact Support,” and the connector must run on the same machine as the company file.

---

### 10. [Resolve Touchless Integration export errors (QBO)](https://help.servicetitan.com/docs/resolve-touchless-integration-export-errors-qbo)
**Creator:** ServiceTitan Help Center  
**URL:** [https://help.servicetitan.com/docs/resolve-touchless-integration-export-errors-qbo](https://help.servicetitan.com/docs/resolve-touchless-integration-export-errors-qbo)  
**Category:** Basic Troubleshooting and FAQs  
**Tags:** Troubleshooting, Accounting Integration, Intermediate, Troubleshooting Guide, Bookkeeper, Financial Integrations Specialist

**What it covers:**  

**Why it's valuable:**  

**Who would benefit:**  

**Limitations:**  

---

### 16. [Batch will not post or accept invoices](https://help.servicetitan.com/docs/why-is-my-batch-failing-to-post)
**Creator:** ServiceTitan Help Center  
**URL:** [https://help.servicetitan.com/docs/why-is-my-batch-failing-to-post](https://help.servicetitan.com/docs/why-is-my-batch-failing-to-post)  
**Category:** Basic Troubleshooting and FAQs  
**Tags:** Troubleshooting, Invoicing, Intermediate, Troubleshooting Guide, Bookkeeper, Office Manager

**What it covers:**  

**Why it's valuable:**  

**Who would benefit:**  

**Limitations:**  

---

## Course process (not part of the 16)

- [Exercise 01: Source Discovery](exercise-01-source-discovery.md)
- [Assignment 01: Collection Plan](assignment-01-collection-plan.md)
- [Exercise 02: Annotation Practice](exercise-02-annotation-practice.md)
- [Back to homepage](../index.md)