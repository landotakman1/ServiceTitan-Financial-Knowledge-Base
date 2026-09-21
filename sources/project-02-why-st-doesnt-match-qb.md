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

*Payments, job complete, credits, and a short note on progress billing.*

---

## 3. Batch, post, export

*The daily move. Desktop vs Online so you open the right FAQ.*

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

*More sources will be added*

---

[Back to the collection](project-01-collection.md) | [Homepage](../index.md)