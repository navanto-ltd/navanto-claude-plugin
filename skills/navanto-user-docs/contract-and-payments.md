---
title: Contract items and payments
description: How the Approved tab, stage payments, VAT and credits work, and how the forecast reads them.
section: money
order: 2
audience: team
date: 2026-08-30
---

The Approved tab of a project's Contract holds what the client has agreed to pay for: each line is a contract item with a price, and each item can carry stage payments setting out when parts of that price fall due. Your client sees the list read-only on their portal, without the team-side chips and badges — and where you work in prices excluding VAT, their view of this page shows the figures with VAT included, so the amount against a stage payment is the amount to pay, with the ex-VAT total kept at the bottom of the summary for reference.

## Contract items

**New contract item** creates a line with a title, a price excluding VAT, a VAT rate, a description and an attachment. Items from an approved [variation](/docs/variations/) or a signed-off [selection](/docs/selections/) arrive here on their own, badged with where they came from. Their price and VAT rate are what the client agreed, so they can't be changed here; you can still edit its title, description and attachment, and you give it a payment schedule, or for a credit from an omitted item, choose the payment it applies to.

The VAT rate is 20%, 5%, 0% or No VAT. 0% and No VAT are not the same thing: 0% applies VAT at the zero rate, No VAT means the line sits outside VAT; pick the one your accountant would.

## Stage payments

Each stage payment has a name, an amount and its share of the item as a percentage, either one computing the other, an optional due date, an invoice attachment and a **Paid** checkbox; the schedule must add up exactly to the item's price and the editor shows what is allocated and what is left as you go. Anyone can add stage payments, but removing one that has been saved, like deleting a whole item, takes an administrator.

Ticking **Provisional** on a stage payment tells your client the amount is a best estimate rather than a settled figure; the payment still needs its full amount so the schedule adds up, and it carries a provisional marker on your view and theirs until it is paid, when the figure is final and the marker goes.

A payment's state (not due yet, upcoming, due, overdue or paid) is worked out from its due date and the **Paid** checkbox; you never set it directly. Upcoming starts a fortnight before the date and overdue a week after it, and a payment with no due date stays not due yet.

## Credits

**New credit** records money coming off what the client owes: entered as a positive amount, held as a negative line. Apply it to one unpaid stage payment, which then shows a due-after-credits figure, or leave it **On account (not applied)** until you know where it belongs. A credit can only be applied to an item with the same VAT rate, so a credit from a variation, whose rate is fixed, is offered only payments at that rate when you apply it; it never carries stage payments of its own, and it applies within its own project only.

> A credit on account reduces the contract value but sits outside the payment forecast until it is applied to a stage payment.

## Forecasting

Forecasting, visible to roles granted it under [Roles and permissions](/docs/roles-and-permissions/), lays your projects' stage payments out month by month over a window you can extend, split into outstanding and paid, with overdue, due this month and the next three months totalled at the top. **Include VAT** switches every figure to gross, **Show completed projects** brings finished jobs back in, and the CSV export matches whatever the page is showing.

> Only stage payments with a due date appear in the forecast. A payment with no due date is never pulled through, however large.

An unpaid payment past its due date is carried into the current month rather than left where it fell, so this month's column includes arrears. Applied credits show as negative lines with their target; credits on account never appear.

**Include budgets** adds the budgets of [selections](/docs/selections/) that haven't been signed off yet, so you can see where they would leave your cash flow before the figures are agreed. A selection counts once it has both a budget and a decision deadline, whether it is still a draft or already sent; its budget sits in the month of that deadline, or in the current month once the deadline has passed. Budgets are shown in grey italics and totalled in their own rows beneath the monthly total, with a total including budgets below that, so the outstanding figures and the totals at the top only ever cover what has been agreed. A signed-off selection is already a contract item, so it reaches the forecast through its stage payments instead.
