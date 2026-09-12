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

**What it covers:** Bookkeepers describing a live ServiceTitan-to-QBO integration: Deposits on a ServiceTitan report that never hit the bank, bank deposits missing from ServiceTitan, auto-batched payments, and refunds that do not travel with the deposit unless someone unposts and rebuilds it. Replies also stress that an exported batch cannot be edited in ServiceTitan.

**Why it's valuable:** Official docs describe the intended path. This thread names the path as tenants experience it during reconciliation. That contrast is why a community source belongs in a Help Center-heavy collection.

**Who would benefit:** Bookkeepers stuck mid-reconciliation and support staff who need the tenant's language for "the books don't match."

**Limitations:** Unmoderated anecdotes, mixed expertise, and no guaranteed steps. Advice may assume document export or Touchless without saying which. Treat it as a symptom list, then confirm against Help Center and the tenant's export type. Pair with "Payments Home" for refunds and deposits, and with "Resolve Touchless Integration export errors (QBO)" for the official fixes.

---

## 5. Financial Controls & Month-End Closing

### 12. [Best Practices on Closing the Books with QuickBooks](https://help.servicetitan.com/docs/best-practice-on-closing-the-books-with-quickbooks)
**Creator:** ServiceTitan Help Center  
**URL:** [https://help.servicetitan.com/docs/best-practice-on-closing-the-books-with-quickbooks](https://help.servicetitan.com/docs/best-practice-on-closing-the-books-with-quickbooks)  
**Category:** Financial Controls & Month-End Closing  
**Tags:** Reconciliation, Financial Controls, Intermediate, Official Help Center, Bookkeeper, Accountant

**What it covers:** Month-end checklist for tying ServiceTitan to QuickBooks: AR, AP, bank accounts, inventory, and a closing-date lock so posted periods stop changing. It turns "close the books" into a ServiceTitan-plus-QuickBooks sequence instead of generic accounting advice.

**Why it's valuable:** If invoicing and export are the daily habit, this page is why that habit exists. A clean close is the test that earlier pages were followed. It is one of the few official articles written as an accountant's month-end, not a feature tour.

**Who would benefit:** Bookkeepers and accountants who close monthly should bookmark it. Office managers who do not close can still use it to see what accounting will ask for.

**Limitations:** Assumes a clean prior period. It will not unwind duplicate customers, years of unexported batches, or inherited inventory balances. Conversion jobs need a cleanup plan before this checklist works. Pair with "Understand the Financial Dashboard" and "Work in Progress (WIP) report" for project revenue, and with "Inventory and Purchase Orders Home" for the stock side of the close.

---

### 13. [Understand the Financial Dashboard](https://help.servicetitan.com/docs/understand-the-financial-dashboard)
**Creator:** ServiceTitan Help Center  
**URL:** [https://help.servicetitan.com/docs/understand-the-financial-dashboard](https://help.servicetitan.com/docs/understand-the-financial-dashboard)  
**Category:** Financial Controls & Month-End Closing  
**Tags:** Financial Controls, Intermediate, Official Help Center, Accountant, Owner

**What it covers:** Explains the Financial Dashboard and the Over/Under Billing view: Earned revenue from work completed versus actual revenue invoiced to the customer. Overbilling is invoicing ahead of percent complete; underbilling is the reverse. The summary bar totals projects, earned vs actual, and over/under amounts.

**Why it's valuable:** Progress billing and WIP numbers need a place they can be seen together. This dashboard is that place for project work. A shop can invoice on schedule and still be overbilled on the books.

**Who would benefit:** Accountants, controllers, and owners of project-based work. Bookkeepers preparing a month-end journal for over/under billing should open it before they write the entry.

**Limitations:** It is project-scoped. Standalone service jobs do not belong here. Access is permissioned and the feature may need to be enabled. Pair with "Work in Progress (WIP) report" for the column-level view and with "Applications for Payment & Continuation Sheets" for the billing documents that created the actual revenue.  

---

### 15. [Work in Progress (WIP) report](https://help.servicetitan.com/docs/work-in-progress-wip-report)
**Creator:** ServiceTitan Help Center  
**URL:** [https://help.servicetitan.com/docs/work-in-progress-wip-report](https://help.servicetitan.com/docs/work-in-progress-wip-report)  
**Category:** Financial Controls & Month-End Closing  
**Tags:** Job Costing, Financial Controls, Advanced, Official Help Center, Accountant, Owner

**What it covers:** Work in Progress report for project jobs: Percent complete from cost, recognized revenue, billed revenue, committed costs, and over/under billing. It is the percentage-of-completion view used to judge whether invoicing is ahead of or behind earned work.

**Why it's valuable:** The Financial Dashboard gives the snapshot. This report gives the columns behind that snapshot and is what accountants use for WIP accruals. Together with Applications for Payment, it explains why a project can look profitable on invoices and still need a month-end entry.

**Who would benefit:** Accountants and owners on construction or install projects. Bookkeepers who only close service work can skip it.

**Limitations:** A project start date is required or the job may not appear. Completed projects drop off after the As of date passes their completion date. Account configuration is required. Pair with "Understand the Financial Dashboard" and with "Applications for Payment & Continuation Sheets." Do not treat it as a residential job-costing substitute; that is "Run job costing reports."  

---

## 6. Inventory Management & Procurement

### 14. [Inventory and Purchase Orders Home](https://help.servicetitan.com/docs/inventory-and-purchase-orders)
**Creator:** ServiceTitan Help Center  
**URL:** [https://help.servicetitan.com/docs/inventory-and-purchase-orders](https://help.servicetitan.com/docs/inventory-and-purchase-orders)  
**Category:** Inventory Management & Procurement  
**Tags:** Inventory Management, Intermediate, Official Help Center, Bookkeeper, Office Manager, Owner

**What it covers:** Hub for purchasing and inventory: purchase orders, receiving, vendor bills, transfers between trucks and warehouses, counts, serialized items, and replenishment. It also separates shops that only have Purchasing from shops with full Inventory.

**Why it's valuable:** Job costing and AP are fiction if parts never hit a PO or a receipt. This page is the cost feed for the job costing report and the inventory piece of a QuickBooks close. Assignment 01 had this category empty; this source fills it with the official starting point.

**Who would benefit:** Office managers and bookkeepers who enter vendor bills or truck stock, and owners who cannot match job profit to the invoice.

**Limitations:** Module mix varies by account. Three-way matching, vendor catalogs, and mobile receiving live on child pages. Inventory transactions still have to be batched and exported if the shop tracks stock in accounting. Pair with "Run job costing reports" and with "Batch, post, and export transactions."

---

## 7. Basic Troubleshooting and FAQs

### 9. [Web Connector Troubleshooting Guide](https://help.servicetitan.com/docs/web-connector-troubleshooting-guide)
**Creator:** ServiceTitan Help Center  
**URL:** [https://help.servicetitan.com/docs/web-connector-troubleshooting-guide](https://help.servicetitan.com/docs/web-connector-troubleshooting-guide)  
**Category:** Basic Troubleshooting and FAQs  
**Tags:** Troubleshooting, Accounting Integration, Intermediate, Troubleshooting Guide, Bookkeeper, Financial Integrations Specialist

**What it covers:** Common QuickBooks Desktop Web Connector failures during batch export: The connector crashes, the connection is green in one place and red in another, QuickBooks is not open under the same Windows user, old certificates, and "could not connect to QuickBooks." Fixes start with version, install location, single-user mode, and re-creating the connection.

**Why it's valuable:** This is the public page people need when "Accounting Integrations Home" and "Batch, post, and export transactions" are useless. A large share of Desktop tickets die here, not in GL mapping.

**Who would benefit:** Bookkeepers who export from the office machine and support staff looking at a red connector.

**Limitations:** Desktop only. QBO Touchless and Intacct do not use this connector. Some steps still end at "contact Support." The connector, QuickBooks, and the company file must be on the same machine; remote-control tools are not a supported workaround. Pair with "Batch, post, and export transactions" and with "Batch will not post or accept invoices" when the problem is the batch rather than the connector.

---

### 10. [Resolve Touchless Integration export errors (QBO)](https://help.servicetitan.com/docs/resolve-touchless-integration-export-errors-qbo)
**Creator:** ServiceTitan Help Center  
**URL:** [https://help.servicetitan.com/docs/resolve-touchless-integration-export-errors-qbo](https://help.servicetitan.com/docs/resolve-touchless-integration-export-errors-qbo)  
**Category:** Basic Troubleshooting and FAQs  
**Tags:** Troubleshooting, Accounting Integration, Intermediate, Troubleshooting Guide, Bookkeeper, Financial Integrations Specialist

**What it covers:** Error-by-error list for ServiceTitan Touchless Integration to QuickBooks Online: Permissions in QBO, a closing date that blocks older transactions, business units missing from payments or invoices, and chart-of-accounts names that do not match, including parent/subaccount format.

**Why it's valuable:** QBO shops do not have a Web Connector. Without this page the collection would treat every export failure as a Desktop problem. Touchless also changes the workflow: Journal entries can leave ServiceTitan without a manual batch, so the failure modes look different.

**Who would benefit:** Bookkeepers on QBO, admins who own the QBO connection, and specialists who have already ruled out a Desktop connector.

**Limitations:** QBO Touchless only, not Intacct and not document-based Desktop export. Some fixes require an exact dummy account name in QBO or a reconnect of business units. Mapping errors that "succeed" and still drop fields will not all appear here; the r/Bookkeeping thread is where those show up. Pair with "Accounting Integrations Home" and with "ServiceTitan push into QBO - What issues have you seen?"  

---

### 16. [Batch will not post or accept invoices](https://help.servicetitan.com/docs/why-is-my-batch-failing-to-post)
**Creator:** ServiceTitan Help Center  
**URL:** [https://help.servicetitan.com/docs/why-is-my-batch-failing-to-post](https://help.servicetitan.com/docs/why-is-my-batch-failing-to-post)  
**Category:** Basic Troubleshooting and FAQs  
**Tags:** Troubleshooting, Invoicing, Intermediate, Troubleshooting Guide, Bookkeeper, Office Manager

**What it covers:** Troubleshooting page for a batch that will not post or will not accept invoices. Four usual causes: Material or equipment with no technician, an empty batch that fails silently, an invoice with no date because the job is not fully closed, and a batch that was already exported so it cannot take new work.

**Why it's valuable:** This is the "why is my invoice stuck" page that invoice statuses cannot be posted. Status tells you the lock; this page tells you the four locks that happen before export even starts.

**Who would benefit:** Office staff who add invoices to a batch, and bookkeepers who cannot post.

**Limitations:** It does not fix connector or QBO mapping errors. After a successful export, create a new batch rather than forcing more invoices into the old one. Pair with "Understand invoice statuses" and with "Batch, post, and export transactions." If those four checks pass and export still fails, move to the Web Connector or QBO Touchless page.  

---

## Course Process (not part of the 16)

- [Exercise 01: Source Discovery](exercise-01-source-discovery.md)
- [Assignment 01: Collection Plan](assignment-01-collection-plan.md)
- [Exercise 02: Annotation Practice](exercise-02-annotation-practice.md)
- [Back to homepage](../index.md)