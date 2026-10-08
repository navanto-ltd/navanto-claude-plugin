---
title: Orders
description: How to raise a purchase order from a selection or from scratch, send it to a supplier and track it through to delivery.
section: money
order: 5
audience: team
date: 2026-09-19
---

A purchase order tells a supplier what to deliver and at what cost. Most are raised from a signed-off [selection](/docs/selections/), one per supplier, but you can start one from scratch too. Either way it is sent by email from the order and tracked through to delivery.

## Raising orders

**Raise orders** appears on a selection once it is signed off. Your chosen products are grouped by supplier into one draft order each; a product with no supplier is listed separately rather than dropped. Per line you can untick it, or change the quantity and unit cost. Totals are your trade cost excluding VAT - a purchase order never shows client prices.

You don't have to order everything at once. Once part of an item has been ordered the raise page shows 1 of 4 still to order, say, and fills the quantity in for you; an item that has all been ordered starts at 0. Nothing stops you ordering more than the selection says - you might be ordering in kilograms where the selection was in tonnes - so treat the count as a guide.

Every order gets a sequential PO number - PO-0001, PO-0002 and so on - which is never reused.

## Starting an order from scratch

Not everything you buy comes out of a selection. **New order** under Procurement › Orders asks for a project and a supplier, and lands you on a draft order with no lines. **Add line** opens that supplier's products, exactly as on any other order. An order needs at least one line before it can be sent or marked as sent, and any line can be removed, including the last one.

An order can be pointed at a selection afterwards, whether or not it started from one. **Link to a selection** beside the Selection label on the order page offers the signed-off selections on the order's own project; **Change** lets you swap or remove the link on any order that hasn't been cancelled - even one already sent, since the link is your bookkeeping and never appears on the PO. Each change is recorded in the order's log.

## Margin after orders

Linking an order to a signed-off selection - or raising one from it and then changing a quantity or a unit cost - doesn't change what your client signed off: same price, same approved [contract](/docs/contract-and-payments/) item. What it changes is what you spend against that price, so the selection's summary rail shows its margin after orders next to the margin it was signed off at, and the project's Selections list uses the after-orders figure. The order itself carries no margin - it never shows client prices.

Each item counts what you have ordered at the order's cost, plus the selection's snapshot cost for whatever is still to order; an order line that isn't one of the selection's items counts as extra spend on top. Every order that hasn't been cancelled counts, drafts included.

## The order page

An order holds its supplier, project and any linked selection, a delivery address and contact, an optional required-by date, the buyer contact, a message to the supplier, and its lines. Everything saves as you type while the order is a Draft. Removed a line by mistake, or need something extra? **Add line** under the lines opens the product picker, showing that supplier's products; the line arrives with the product's code, unit and cost filled in.

Every order across every project lives under **Procurement › Orders**. Each signed-off selection also links to its own orders.

## Sending an order

**Send** on a Draft lets you pick the supplier's contacts and edit the subject and message before it goes. The email goes from Navanto on your organisation's behalf, with replies to you, and carries the PO as a PDF. An order needs a delivery address before it can be sent - for a collection, use the supplier's own address.

> Sending locks the order's lines. The order moves to **Sent**, records who it went to and when, and keeps the exact PDF that went out - downloadable from the order and filed under the project's Orders folder on the [Files](/docs/files/) page.

You can send an order again, and each send is recorded. **Download PDF** works on a Draft too, if you'd rather send it yourself.

## Tracking an order

Click the status badge on the order to see the moves available from where it is:

- **Mark as sent** - for an order you placed outside Navanto. Records a sent date and an optional note; nothing is emailed.
- **Confirm** - the supplier has committed. Records their expected delivery date and, optionally, their reference.
- **Mark delivered** - records the delivered date. Works straight from Sent as well as from Confirmed.
- **Back to draft**, **Unconfirm**, **Not delivered** - step back if something was recorded wrongly. Back to draft warns you that the supplier may still hold the PO.
- **Cancel order** - with an optional reason and a **Notify supplier** switch. Switched on, it opens the email composer prefilled with a standard cancellation notice for you to edit. Switched off, nothing is emailed, and you're warned if the supplier already has the PO. The switch is only offered once an order has reached a supplier.
- **Reinstate** - brings a cancelled order back to where it was, for when a supplier can't or won't cancel after all.

A cancellation is a request until the supplier accepts it, and suppliers often charge once goods have been picked or made - log their reply on the order.

Once an order is Confirmed, its expected date and supplier reference can be edited on the order; so can the delivered date once it's Delivered.

## Putting a delivery on the timeline

When you confirm an order, **Share with timeline** puts the delivery on the project's [Timeline](/docs/timeline/), in the week of the expected date, on the track you choose under **Timeline track**. Once you've entered the date, NavantoAI suggests a track from what's being delivered, which work is active that week and where earlier deliveries went. When it has a clear pick, the switch starts on with that track chosen; when it doesn't, the switch starts off. The option only appears if your role includes Timeline and the project's timeline has at least one phase. Without Timeline, confirming leaves the order off the timeline, and someone whose role includes both can add it from the order page later.

The timeline follows the order from then on. Change the expected date and the delivery moves to its new week. Cancel the order and it leaves the timeline until you reinstate it. Unconfirm it or send it back to draft and it comes off its track altogether, so share it again when you re-confirm. A delivered order stays in the week it was expected. To move a delivery to another track, add one you didn't share when confirming, or take one off the timeline, change **Timeline track** on the order.

## Logging calls, emails and notes

Every status change writes its own entry in the order's log. **Log activity** on the order, or **Log** on a row under Procurement › Orders, adds a Call, Email or Note by hand. The log also feeds the project's activity feed.

## The chase list

Procurement › Orders puts the orders that need attention at the top:

- **Overdue** - the date has passed and the goods haven't arrived: the supplier's expected date once an order is Confirmed, or your required-by date while it's still Sent.
- **Needs chasing** - Sent but not confirmed, and either it's been a week since sending or your required-by date is within the next week.
- **Due this week** - Confirmed, with an expected date in the next week.
- Everything else, by PO number. When nothing needs attention the headings disappear and the list is just orders.

Your required-by date is guidance to the supplier, not a promise from them. Once they commit to a date, that's the date the order is judged on.

The Attention column says why an order is where it is. Click a column heading to sort the whole list by it instead; click it a third time to return to the groups. Delivered and Cancelled orders are hidden until you pick them in the status filter. The list covers your live projects; completed projects sit at the bottom of the project filter. Search, filters and sort are part of the page's address, so a view can be bookmarked and survives going into an order and back.

An order that has reached a supplier is a permanent record: it can be cancelled but never deleted, and a project or selection holding one can't be deleted either - complete the project instead. Deleting a project or selection cancels any orders on it that were never sent.

## Asking NavantoAI

NavantoAI can read orders for you and keep them up to date: ask what's being delivered to site this week or what needs chasing, have it log a call, email or note against an order, and record that a supplier has confirmed an order or that it has been delivered. When it confirms an order it can put the delivery on the timeline too, and it can move a confirmed order's delivery to another track or take it off. Raising, editing, sending and cancelling orders stay on the order page because they may involve emailing suppliers.

## Who can do this

Orders need the Procurement feature enabled on your role - see [Roles and permissions](/docs/roles-and-permissions/). Clients never see orders.
