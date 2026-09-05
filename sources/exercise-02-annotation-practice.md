# Exercise 02: Annotation Practice

**Name:** Landon Forney  
**Date:** September 4, 2026  
**Course:** CMPA 4301 – Information Organization

These six annotations practice the four-component structure for Project 01. Sources come from Exercise 01 and Assignment 01. Official Help Center pages stay in the set because they are the public record tenants actually use. One community thread is included so the collection is not only ServiceTitan documentation.

---

### 1. Overview of the Invoicing Process
**Creator:** ServiceTitan Help Center  
**URL:** [https://help.servicetitan.com/docs/overview-of-the-invoicing-process](https://help.servicetitan.com/docs/overview-of-the-invoicing-process)  
**Category:** Invoicing Workflows  
**Tags:** Invoicing, Basic, Official Help Center, Bookkeeper, Office Manager, Financial Integrations Specialist

**What it covers:** Official walkthrough of the ServiceTitan invoicing lifecycle from a completed job to an invoice that can be batched, posted, and exported to the connected accounting system.

**Why it's valuable:** It establishes the vocabulary the rest of the collection depends on. Payments, job costing, and month-end close only make sense if batch, post, and export are already clear.

**Who would benefit:** New bookkeepers, office managers, and support staff who need the happy-path model before they troubleshoot a broken export.

**Limitations:** High-level only. It does not cover refunds, progress-billing forms, or failed QuickBooks exports. Pair it with the payments overview and a troubleshooting guide when something leaves the happy path.

---

### 2. Accounting Integrations Home
**Creator:** ServiceTitan Help Center  
**URL:** [https://help.servicetitan.com/docs/accounting-integrations-overview](https://help.servicetitan.com/docs/accounting-integrations-overview)  
**Category:** Accounting Integrations & Reconciliation  
**Tags:** Accounting Integration, Intermediate, Official Help Center, Bookkeeper, Accountant, Financial Integrations Specialist

**What it covers:** Landing page for supported accounting connections: QuickBooks Desktop, QuickBooks Online, Sage Intacct, Xero, and CSV export. Each platform links out to its own setup guide.

**Why it's valuable:** Authoritative starting point. It keeps tenants from following outdated third-party blogs when they only needed the current connector list.

**Who would benefit:** Office managers choosing an integration and specialists auditing whether a shop is on a supported path.

**Limitations:** Overview, not a configuration manual. Web Connector crashes, QBO mapping errors, and Intacct specifics live on child pages. Use this to pick a path, then open the matching setup or troubleshooting article.

---

### 3. Best Practices on Closing the Books with QuickBooks
**Creator:** ServiceTitan Help Center  
**URL:** [https://help.servicetitan.com/docs/best-practice-on-closing-the-books-with-quickbooks](https://help.servicetitan.com/docs/best-practice-on-closing-the-books-with-quickbooks)  
**Category:** Financial Controls & Month-End Closing  
**Tags:** Reconciliation, Financial Controls, Intermediate, Official Help Center, Bookkeeper, Accountant

**What it covers:** Month-end sequence for tying ServiceTitan to QuickBooks: AR, AP, bank accounts, inventory, and setting a closing-date lock so posted periods stop changing.

**Why it's valuable:** Turns “close the books” into concrete ServiceTitan-plus-QuickBooks actions instead of generic accounting advice. This is the page that makes the rest of the workflow pay off.

**Who would benefit:** Bookkeepers and accountants who close monthly and need a repeatable checklist.

**Limitations:** Assumes a clean prior period. It will not walk a shop through inherited mess: duplicate customers, old unexported batches, or years of unreconciled inventory. Conversion jobs still need a cleanup plan first.

---

### 4. Inventory and Purchase Orders Home
**Creator:** ServiceTitan Help Center  
**URL:** [https://help.servicetitan.com/docs/inventory-and-purchase-orders](https://help.servicetitan.com/docs/inventory-and-purchase-orders)  
**Category:** Inventory Management & Procurement  
**Tags:** Inventory Management, Intermediate, Official Help Center, Bookkeeper, Office Manager, Owner

**What it covers:** Hub for purchasing and inventory: creating purchase orders, receiving, vendor bills, transfers, counts, serialized items, and replenishment. Notes the difference between the Purchasing module and full Inventory.

**Why it's valuable:** Job costing and AP only stay honest if parts and POs are recorded correctly. This page fills a category that was empty in Assignment 01 and connects field material use to the ledger.

**Who would benefit:** Office managers and bookkeepers who handle vendor bills, truck stock, and job material cost. Owners who want to know why job profit does not match the invoice.

**Limitations:** Module availability varies by account. Some shops only have Purchasing, not full Inventory. Three-way matching and vendor-catalog details live on child pages, not on this hub.

---

### 5. Web Connector Troubleshooting Guide
**Creator:** ServiceTitan Help Center  
**URL:** [https://help.servicetitan.com/docs/web-connector-troubleshooting-guide](https://help.servicetitan.com/docs/web-connector-troubleshooting-guide)  
**Category:** Basic Troubleshooting and FAQ's  
**Tags:** Troubleshooting, Accounting Integration, Intermediate, Troubleshooting Guide, Bookkeeper, Financial Integrations Specialist

**What it covers:** Common QuickBooks Desktop Web Connector failures during batch export: crashes, connection color mismatches, “could not connect to QuickBooks,” and the usual install, user, and certificate fixes.

**Why it's valuable:** This is the public page people need when the happy-path integration guide is useless. It is also the closest official match to the batching, posting, and export errors that show up in support work.

**Who would benefit:** Bookkeepers who export from the office and support staff diagnosing a red connector or a batch that will not leave ServiceTitan.

**Limitations:** QuickBooks Desktop only. QBO and Intacct use different error paths. Some fixes still end with “contact Support,” and the connector must run on the same machine as the company file.

---

### 6. ServiceTitan push into QBO – What issues have you seen?
**Creator:** r/Bookkeeping community thread  
**URL:** [https://www.reddit.com/r/Bookkeeping/comments/1uqux5a/servicetitan_push_into_qbo_what_issues_have_you/](https://www.reddit.com/r/Bookkeeping/comments/1uqux5a/servicetitan_push_into_qbo_what_issues_have_you/)  
**Category:** Accounting Integrations & Reconciliation  
**Tags:** Accounting Integration, Troubleshooting, Intermediate, Community Forum, Bookkeeper, Accountant

**What it covers:** Bookkeepers describing live QBO sync pain: deposits on a ServiceTitan report that never hit the bank, bank deposits missing from ServiceTitan, auto-batched payments, and refunds that do not export unless someone unposts and rebuilds the deposit.

**Why it's valuable:** Names failure modes official docs understate, including that an exported batch cannot be edited in ServiceTitan. That is the counterweight to the clean integrations overview.

**Who would benefit:** Bookkeepers mid-reconciliation and support staff who need the tenant’s language for “the books don’t match.”

**Limitations:** Unmoderated anecdotes, mixed expertise, no guaranteed steps. Treat it as a symptom list, then confirm against Help Center and the tenant’s export type (document vs journal entry).

---

## Notes for Project 01
These drafts stay in the 75–125 word practice range. For Project 01 they should expand toward 100–200 words, especially sources 1, 3, and 5. After the semester, internal resources can go deeper on refunds, estimates, progress billing, vendor integration, and export errors to QBD, QBO, and Intacct. This class version stays on public sources only.