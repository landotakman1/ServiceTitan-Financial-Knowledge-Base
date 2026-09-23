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

*Jump links: batch will not post - Web Connector - QBO Touchless errors - deposits and refunds don’t match.*

---

## 5. After export: close the period

*Month-end checklist. Project shops: earned vs billed.*

---

## 6. If profit still looks wrong

*Inventory and job costing after the books already move.*

---

## Sources used

- [Overview of the Invoicing Process](https://help.servicetitan.com/docs/overview-of-the-invoicing-process) - ServiceTitan Help Center  
- [Understand invoice statuses](https://help.servicetitan.com/docs/understand-invoice-statuses) - ServiceTitan Help Center  
- [Payments Home](https://help.servicetitan.com/docs/payments-overview) - ServiceTitan Help Center  
- [Applications for Payment and Continuation Sheets](https://help.servicetitan.com/docs/complete-application-for-payment-and-continuation-sheet) - ServiceTitan Help Center  
- [Batch, post, and export transactions](https://help.servicetitan.com/docs/batch-post-and-export-transactions) - ServiceTitan Help Center  
- [Accounting Integrations Home](https://help.servicetitan.com/docs/accounting-integrations-overview) - ServiceTitan Help Center  

*More sources will be added*

---

[Back to the collection](project-01-collection.md) | [Homepage](../index.md)