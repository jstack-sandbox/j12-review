# Invoices

### INVOICE-004 — Overdue invoices are listed first

**Status:** planned

The invoice list shows invoices in any order.

**Example:** of two invoices, the overdue one is listed first.

**Failure example:** an overdue invoice is listed after one not yet due.

### INVOICE-005 — A paid invoice is never overdue

**Status:** planned

An invoice paid in full is never listed as overdue.

**Example:** an invoice paid a day late is listed as paid.

**Failure example:** a paid invoice is listed as overdue.

### INVOICE-006 — Overdue is counted from the due date

**Status:** planned

An invoice is overdue from the day after its due date.

**Example:** an invoice due on 3 November is overdue on 4 November.

**Failure example:** an invoice is counted overdue from the day it was issued.
