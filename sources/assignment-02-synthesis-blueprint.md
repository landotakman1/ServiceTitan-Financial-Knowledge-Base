# Assignment 02: Synthesis Blueprint

**Name:** Landon Forney  
**Course:** CMPA 4301 – Information Organization  
**Date:** September 19, 2026

Blueprint for Project 02.\
Project 01 collection: [Curated Collection](project-01-collection.md)

---

## 1. Audience Profile

The primary reader is an office manager or bookkeeper at a trade or construction shop that already runs ServiceTitan for jobs and invoicing. Call her Sandra. She has used the product for about a year. She can create an invoice, take a payment, and find a job. She did not set up the QuickBooks connection and she is not trying to become an integrations specialist.

**What she already knows:** The shop’s daily rhythm; dispatch, job complete, invoice the customer. She has heard “batch,” “post,” and “export,” but she treats them as accounting-screen buttons, not as the point where ServiceTitan either becomes the books or diverges from them.

**What she needs:** Reasons for why the ServiceTitan totals do not match QuickBooks at period close, and the next official page to open. She does not need a tour of the whole product. She does not need Intacct edge cases, estimate-to-invoice theory, or internal support articles. She needs the event chain: invoicing -> payment handling -> batch/post/export -> close - and a warning that an exported batch cannot be edited in ServiceTitan without diverging from the QuickBooks records.

**Context of use:** Twenty minutes at a desk during close week, or a pause in the middle of a batch that will not post. She will scan headings and jump to the failure that matches her screen. She already has Help Center search, what she lacks is order. Scattered official pages exist; a path through them in the order the work happens does not.

**Secondary readers (not the primary designed audience):** Owners who want to know what to ask Sandra, and Financial Integrations / support staff who can send her this page instead of a pile of links. After this course, a deeper internal version can serve support first. This class product stays public and tenant-facing.

---

## 2. Format Choice

**Format:** A short hybrid guide - explainer of the chain, then a how-to path through official pages, then a mini-FAQ of the breaks that stop export or close.

**Why this format:** Sandra does not have the time to read a comprehensive manual. She will, however, read a one-screen explanation of why the books diverge, follow three or four official pages in order if she is still on the happy path, and jump to “batch will not post,” “Web Connector is red,” or “QBO deposits don’t match” when she is not. An explainer alone does not tell her which page to open. A FAQ alone does not show that those errors are the same chain breaking. The hybrid approach matches both the 20-minute desk context and what Project 01 actually contains: How-to Help Center articles plus troubleshooting pages plus one practitioner thread.

---

## 3. Annotated Outline

Working title: **Why ServiceTitan Doesn’t Match QuickBooks - Start Here**

### Section 1 — The chain (explainer)
What “in the books” actually means in ServiceTitan: a completed job is not a ledger entry until the invoice has been batched, posted, and exported. One idea to carry through the rest of the product: after export, that batch cannot be edited; the documented fix is an adjustment invoice.

**Sources:** [Overview of the Invoicing Process](https://help.servicetitan.com/docs/overview-of-the-invoicing-process); [Understand invoice statuses](https://help.servicetitan.com/docs/understand-invoice-statuses)

### Section 2 — Get the invoice and payment ready
What has to be true before a transaction belongs in a batch: job complete, invoice dated, payment applied or intentionally left open, credits and refunds handled before export. Progress billing (applications for payment) is flagged as a different path so commercial shops do not force AIA work through a residential invoice habit.

**Sources:** [Payments Home](https://help.servicetitan.com/docs/payments-overview), [Applications for Payment & Continuation Sheets](https://help.servicetitan.com/docs/complete-application-for-payment-and-continuation-sheet)

### Section 3 — Batch, post, and export (how-to)
The daily move, in order: build the batch, review it, post it, export it to QuickBooks or Intacct. What can go in a batch (invoices, payments, vendor bills, inventory movements). Desktop vs Online is named here so Sandra does not follow Web Connector steps at a QBO shop.

**Sources:** [Batch, post, and export transactions](https://help.servicetitan.com/docs/batch-post-and-export-transactions), [Accounting Integrations Home](https://help.servicetitan.com/docs/accounting-integrations-overview)

### Section 4 — When it will not leave ServiceTitan (mini-FAQ)
Jump links for the failures that stop the chain before close: batch will not post (missing technician, empty batch, no invoice date, already exported); Desktop Web Connector red or crashing; QBO Touchless mapping / permission / closing-date errors; deposits and refunds that never match the bank.

**Sources:** [Batch will not post or accept invoices](https://help.servicetitan.com/docs/why-is-my-batch-failing-to-post), [Web Connector Troubleshooting Guide](https://help.servicetitan.com/docs/web-connector-troubleshooting-guide), [Resolve Touchless Integration export errors (QBO)](https://help.servicetitan.com/docs/resolve-touchless-integration-export-errors-qbo), [ServiceTitan push into QBO](https://www.reddit.com/r/Bookkeeping/comments/1uqux5a/servicetitan_push_into_qbo_what_issues_have_you/)

### Section 5 — Close the period
Once export is working, how month-end actually ties ServiceTitan to QuickBooks: AR, AP, bank, inventory, closing-date lock. Project shops get one extra stop for earned vs billed revenue so over/under billing does not surprise them after the invoices look fine.

**Sources:** [Best Practices on Closing the Books with QuickBooks](https://help.servicetitan.com/docs/best-practice-on-closing-the-books-with-quickbooks), [Understand the Financial Dashboard](https://help.servicetitan.com/docs/understand-the-financial-dashboard), [Work in Progress (WIP) report](https://help.servicetitan.com/docs/work-in-progress-wip-report)

### Section 6 — If job profit still looks wrong
After the books match, costing can still lie if parts never hit a PO or if payroll and burden are double-counted. Short close-out so Sandra knows the mismatch is no longer an export problem.

**Sources:** [Inventory and Purchase Orders Home](https://help.servicetitan.com/docs/inventory-and-purchase-orders), [Run job costing reports](https://help.servicetitan.com/docs/run-job-costing-reports)

---

**Held for later, not this product:** Profit Protection 2025 webinar recap (useful owner context, not a close-week page). Estimates, refunds in depth, vendor integration, and Intacct-specific setup stay out of scope for the class version.

---

## How this will be published

Same GitHub Pages site as Project 01. Project 02 will be a new page linked from the homepage, written for Sandra.