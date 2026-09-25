# Why ServiceTitan Doesn’t Match QuickBooks - Start Here

**Draft for CMPA 4301 Project 02**  
**Landon Forney** - September 21, 2026

This page is for the office manager or bookkeeper who already invoices in ServiceTitan and needs the totals to match QuickBooks at period close. It is not a tour of the product. It is a path through official Help Center pages in the order the work happens, plus the four most common failures that stop an export.

You do not need to read it top to bottom. Read **What “in the books” means**, then either follow the happy path or jump to **If it will not leave ServiceTitan**.

Sources are public ServiceTitan Help Center articles and one practitioner thread. They are linked in the text. The full annotated set can be found in the [Project 01 collection](project-01-collection.md).

---

## 1. What “in the books” means

A completed job is not a QuickBooks transaction.

ServiceTitan’s [Overview of the Invoicing Process](https://help.servicetitan.com/docs/overview-of-the-invoicing-process) walks through the lifecycle from a finished job to an invoice that can be batched, posted, and exported. Those three words are the whole problem. Until export happens, the invoice still only lives in ServiceTitan. Your customer may have a PDF. Your technicians may be paid. QuickBooks still does not have the financial information.

[Understand invoice statuses](https://help.servicetitan.com/docs/understand-invoice-statuses) is the same idea on the invoice header in ST. **Pending** means the invoice is still yours to edit. **Posted** means it is in a batch waiting to leave; you can still unpost and fix it if necessary. **Exported** means it has gone to the accounting system. After that, ServiceTitan will not let you edit those transactions because information flows from ST to QB, not the other way around. The documented fix is an adjustment invoice, not a rewrite of the original.

That lock is why close week feels sudden. The mismatch did not start at reconciliation. It started when an invoice was treated as “done” at job complete, or when a batch was exported with the wrong payment, refund, or job still open. Official pages describe that intended path. They do not always say the next sentence out loud: once export status says Exported, you are no longer correcting the same record.

If the header still says Pending or Posted, stay on the happy path below. If it already says Exported and the books are wrong, do not fight the original invoice. Jump to the FAQ, then use an adjustment invoice.

---

## 2. Before you batch

Do not put an invoice in a batch just because the job feels finished.

The job has to be complete enough for ServiceTitan to give the invoice a date. If the job is still open, that invoice often never appears on the accounting screen. That is not a QuickBooks problem yet. It is a ServiceTitan record that is not ready to leave.

Payments belong in the same pass. [Payments Home](https://help.servicetitan.com/docs/payments-overview) is the official map for card, ACH, check, credits, refunds, and voids from the office or the field. The part that matters for matching QuickBooks is timing. Apply the payment, unapply a credit, or record the refund *before* the invoice is exported. After export, ServiceTitan generally will not let you unapply that payment on the original record. The refund that “never showed up in QuickBooks” usually left the building in the wrong batch, or never left at all.

If you bill commercial or install work by percent complete, stop here and use [Applications for Payment and Continuation Sheets](https://help.servicetitan.com/docs/complete-application-for-payment-and-continuation-sheet) instead of forcing an AIA pay app through a residential invoice habit. Retainage and stored materials will not export cleanly if you invent that process on a regular invoice. Everyone else can skip this paragraph.

When the job is complete, the invoice date is there, and the payment or credit is the one you actually want in QuickBooks, go to Section 3. Refunds and adjustments can still be performed after export but it is much easier to avoid this if at all possible.

---

## 3. Batch, post, export

This is the daily move that turns Section 1 from vocabulary into a habit.

[Batch, post, and export transactions](https://help.servicetitan.com/docs/batch-post-and-export-transactions) is the official sequence: build a batch, review what is in it, post it, then export it to QuickBooks or Intacct. A batch is not only invoices. Payments, vendor bills, inventory transfers, adjustments, and returns can ride along. Best practice in that article is daily, with office staff building the batch and accounting posting it.

[Accounting Integrations Home](https://help.servicetitan.com/docs/accounting-integrations-overview) is where you confirm *which* QuickBooks you have. Desktop, Online, Intacct, and CSV are not the same project. If you are on QuickBooks Desktop, export runs through the Web Connector on the office machine or, in some cases, through a VPN or remote desktop connection. If you are on QuickBooks Online with Touchless Integration, the connector is not necessary. Open the FAQ that matches your product. Do not follow Desktop certificate steps on a QBO setup.

Two rules from these pages that are critical to remember:

- Invoices on unfinished jobs do not show up to batch as revenue is not recognized until work is performed.
- After export, you do not edit that batch. You verify the export in QuickBooks, and you fix mistakes with an adjustment invoice.

If the batch posts and export succeeds, skip to Section 5. If the batch will not post, the connector is red, or QBO rejects the export, go to Section 4.

---

## 4. If it will not leave ServiceTitan

Jump to the failure that matches the screen:

- [Why ServiceTitan Doesn’t Match QuickBooks - Start Here](#why-servicetitan-doesnt-match-quickbooks---start-here)
  - [1. What “in the books” means](#1-what-in-the-books-means)
  - [2. Before you batch](#2-before-you-batch)
  - [3. Batch, post, export](#3-batch-post-export)
  - [4. If it will not leave ServiceTitan](#4-if-it-will-not-leave-servicetitan)
    - [The batch will not post](#the-batch-will-not-post)
    - [Web Connector is red or crashing](#web-connector-is-red-or-crashing)
    - [QBO Touchless rejects the export](#qbo-touchless-rejects-the-export)
    - [Deposits and refunds do not match the bank](#deposits-and-refunds-do-not-match-the-bank)
  - [5. After export: close the period](#5-after-export-close-the-period)
  - [6. If profit still looks wrong](#6-if-profit-still-looks-wrong)
  - [Sources used](#sources-used)

Official Help Center pages describe the intended export. They understate how often the break is one of these four issues. Use the official page as the checklist. Use the forum thread only as a symptom list.

### The batch will not post

[Batch will not post or accept invoices](https://help.servicetitan.com/docs/why-is-my-batch-failing-to-post) names four usual causes: material or equipment with no technician assigned, an empty batch that fails with no error, an invoice with no date because the job is not fully closed, and a batch that was already exported so it cannot take new work.

Invoice statuses tell you whether a record is Pending, Posted, or Exported. They do not tell you *why* a batch refuses the invoice. This page does: missing technician, empty batch, no invoice date, or batch that already exported. After a successful export, create a new batch. Do not force more invoices into the old one.

### Web Connector is red or crashing

**QuickBooks Desktop only** - [Web Connector Troubleshooting Guide](https://help.servicetitan.com/docs/web-connector-troubleshooting-guide) covers crashes, green-in-one-place / red-in-another, “could not connect to QuickBooks,” old certificates, and the connector running under a different Windows user than QuickBooks.

The connector, QuickBooks, and the company file need to be on the same machine (or the same remote session you already use). QBO shops should skip this section. Some steps still end at Support. If the four batch-will-not-post checks passed and Desktop still will not export, this is the page.

### QBO Touchless rejects the export

QuickBooks Online with Touchless Integration does not use the connector. [Resolve Touchless Integration export errors (QBO)](https://help.servicetitan.com/docs/resolve-touchless-integration-export-errors-qbo) is the error list: QBO permissions, a closing date that blocks older transactions, business units missing from a payment or invoice, and account names that do not match, including parent/subaccount format.

Do not run Desktop certificate steps here. If the export “succeeds” and fields are still missing in QBO, this page may be silent. That is the next item.

### Deposits and refunds do not match the bank

The [r/Bookkeeping thread on ServiceTitan pushing into QBO](https://www.reddit.com/r/Bookkeeping/comments/1uqux5a/servicetitan_push_into_qbo_what_issues_have_you/) is not a procedure. It is what bookkeepers say when official docs are not enough: deposits on a ServiceTitan report that never hit the bank, bank deposits missing from ServiceTitan, auto-batched payments, and refunds that do not ride with the deposit unless someone unposts and rebuilds it before export.

Treat it as a symptom list. Confirm your shop's export type (document vs journal / Touchless), then go back to [Payments Home](https://help.servicetitan.com/docs/payments-overview) or the QBO error page for the actual fix. This thread and the Help Center agree on one hard rule: **an exported batch cannot be edited in ServiceTitan**.

---

## 5. After export: close the period

Export working is not the same as the period being closed.

[Best Practices on Closing the Books with QuickBooks](https://help.servicetitan.com/docs/best-practice-on-closing-the-books-with-quickbooks) is the month-end sequence: AR, AP, bank accounts, inventory, then a closing-date lock so posted periods stop changing. If daily batching is the habit, this page is why that habit exists. It assumes a reasonably clean prior period. It will not unwind years of unexported batches by itself.

Project and construction shops need one extra look at earned vs billed. [Understand the Financial Dashboard](https://help.servicetitan.com/docs/understand-the-financial-dashboard) shows overbilling (invoiced ahead of percent complete) and underbilling (the reverse). The [Work in Progress (WIP) report](https://help.servicetitan.com/docs/work-in-progress-wip-report) is the column-level version of that same gap. A project can look fine on invoices and still need a month-end entry. Residential service shops that never use projects can skip those two pages.

When the close checklist is done and QuickBooks still does not match *job profit*, that is no longer an export problem. Go to Section 6.

---

## 6. If profit still looks wrong

If invoices exported and the bank tied out, but job profit still looks impossible, the leak is usually cost, not export.

[Inventory and Purchase Orders Home](https://help.servicetitan.com/docs/inventory-and-purchase-orders) is the cost feed: POs, receiving, vendor bills, truck stock, & counts. Job costing cannot be honest if parts never hit a PO or a receipt. Some shops only have Purchasing, not full Inventory. Either way, those transactions still need to batch and export if you track stock in accounting.

[Run job costing reports](https://help.servicetitan.com/docs/run-job-costing-reports) is where material, equipment, PO, payroll, and labor burden get compared to revenue. Two traps the official page flags: counting payroll and burden twice, and invoice items that are not mapped to income GLs so revenue looks low even when the invoice total is right.

If this section is where you live every month, the books-matching problem is solved and the pricing problem is not. That is a different job than this page covers.

---

## Sources used

- [Overview of the Invoicing Process](https://help.servicetitan.com/docs/overview-of-the-invoicing-process) - ServiceTitan Help Center  
- [Understand invoice statuses](https://help.servicetitan.com/docs/understand-invoice-statuses) - ServiceTitan Help Center  
- [Payments Home](https://help.servicetitan.com/docs/payments-overview) - ServiceTitan Help Center  
- [Applications for Payment and Continuation Sheets](https://help.servicetitan.com/docs/complete-application-for-payment-and-continuation-sheet) - ServiceTitan Help Center  
- [Batch, post, and export transactions](https://help.servicetitan.com/docs/batch-post-and-export-transactions) - ServiceTitan Help Center  
- [Accounting Integrations Home](https://help.servicetitan.com/docs/accounting-integrations-overview) - ServiceTitan Help Center  
- [Batch will not post or accept invoices](https://help.servicetitan.com/docs/why-is-my-batch-failing-to-post) - ServiceTitan Help Center  
- [Web Connector Troubleshooting Guide](https://help.servicetitan.com/docs/web-connector-troubleshooting-guide) - ServiceTitan Help Center  
- [Resolve Touchless Integration export errors (QBO)](https://help.servicetitan.com/docs/resolve-touchless-integration-export-errors-qbo) - ServiceTitan Help Center  
- [ServiceTitan push into QBO](https://www.reddit.com/r/Bookkeeping/comments/1uqux5a/servicetitan_push_into_qbo_what_issues_have_you/) - r/Bookkeeping  
- [Best Practices on Closing the Books with QuickBooks](https://help.servicetitan.com/docs/best-practice-on-closing-the-books-with-quickbooks) - ServiceTitan Help Center  
- [Understand the Financial Dashboard](https://help.servicetitan.com/docs/understand-the-financial-dashboard) - ServiceTitan Help Center  
- [Work in Progress (WIP) report](https://help.servicetitan.com/docs/work-in-progress-wip-report) - ServiceTitan Help Center  
- [Inventory and Purchase Orders Home](https://help.servicetitan.com/docs/inventory-and-purchase-orders) - ServiceTitan Help Center  
- [Run job costing reports](https://help.servicetitan.com/docs/run-job-costing-reports) - ServiceTitan Help Center  

---

[Back to the collection](project-01-collection.md) | [Homepage](../index.md)