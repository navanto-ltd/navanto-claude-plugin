---
title: Projects
description: How to create a project, what lives inside one, and how statuses and handover dates work.
section: projects
order: 1
audience: team
date: 2026-09-30
---

A project is one job, and everything about that job lives inside it: [posts](/docs/posts/), [tasks](/docs/tasks/), [approvals](/docs/approvals/), [snagging](/docs/snagging/), the [calendar](/docs/calendar/), the [timeline](/docs/timeline/), [drawings](/docs/drawings/), [site updates](/docs/site-updates/), the [contract](/docs/contract-and-payments/) with its [variations](/docs/variations/) and [selections](/docs/selections/), and the [client portal](/docs/client-portal-setup/).

## Creating a project

Only administrators can create projects. **New project** on the Projects page opens a six-step wizard: **Project details**, **Address**, **Dates**, **Appearance**, **Team** and **Templates**.

Only the project title, street address and postal code are required; everything else can be filled in later. Nothing is saved until you press **Create project** on the last step.

The **Templates** step can seed the project from a task, drawing and timeline [template](/docs/templates/), one of each. Applying a template only ever adds items, so you can apply another one later from the project's Tasks, Drawings or Timeline page.

## The overview

Overview is the project's home. The header on every project page shows the title, status, address and, if your role includes Client portal, the client's name; under the title a programme line shows the start date, how far the job has run, and the handover date. Click the header to open **Project details** — the photo, address, dates, category, description, status note and team. Administrators edit them in place, each field saving as you leave it. On a wide screen the double chevron at the right of the header pins a read-only summary of those details under the header on every project you open.

The rest of the page is the activity feed beside the [risk briefing](#risk-briefings); on a phone they are two tabs. The feed runs oldest to newest through everything that has happened on the project, and scrolling up loads what came before: [posts](/docs/posts/) as message bubbles, everything else as a line — *Sam updated Fit kitchen units* — that opens the item where you are. The pills along the top switch it between **All activity**, **All posts** and **Client posts**, the posts your client can see in their portal, and the composer at the bottom is where a post starts.

## Categories

A project can belong to a category - a named, coloured label your organisation defines, shown as the dot or tile next to the project wherever it appears. Administrators create them under **Settings → Categories**, naming each one and picking its colour. Renaming one relabels every project already on it.

A new organisation starts with none, so the category picker on a project is empty until an administrator has created some. Categories are optional: a project without one simply shows no colour.

Deleting a category leaves its projects uncategorised rather than touching them.

On the Projects page, the **All categories** filter next to **Show completed** narrows the list to one category — handy once you've renamed one to mean something, like filtering to "Renovation" across a long list of jobs.

## Project statuses

A project is **Active**, **Snagging** or **Completed**, set by an administrator from the badge in **Project details**. Moving to Snagging is the handover point: the Snagging tab appears on the project and in the client portal, and outstanding defects are tracked there as snag items.

The badge says more than those three settings. Until the start date arrives it reads **planning**; once the job is live it shows the verdict of the latest risk briefing — **on track**, **watch**, **at risk** or **critical** — and **active** until the first briefing has been written; then **snagging** and **completed**. The cards on the Projects page read the same way. Your client sees only planning, active, snagging and completed.

Marking a project completed asks you to confirm first, and completed projects drop off the Projects page until you tick **Show completed**.

> Completing a project makes everything on it read-only. Nothing is deleted, and an administrator can set it back to Active at any time, confirming again on the way back. Completing also sets the date your client's portal access ends, three months on.

## The handover date

Once a project has started, moving an already-set handover date later asks **Why is it moving?** with two answers. **Delayed** keeps the original date as the baseline, so it stays on show — struck through under the dates, and in brackets on the project's card — and the risk briefing reads the slip against it. **Additional scope added** rebaselines to the new date, and the original goes. Either way you can add a status note your client sees, which replaces the project's current one.

Bringing the date earlier, or changing it before the project starts, just saves.

## Risk briefings

Every active or snagging project that has started gets a fresh risk briefing on weeknights, written by [NavantoAI](/docs/navantoai/), and it sits beside the activity feed on the overview. It reads through all data on the project and settles on a verdict: **critical** means something has been missed, is still open and is now holding the project up, **at risk** that it will be missed unless someone acts or has only just been missed, **watch** that nothing is late yet but something will go wrong if it's left, **on track** that nothing was found. Under the verdict comes a card per finding, worst first, saying what the risk is and the records it rests on.

Between overnight briefings NavantoAI rechecks a project within the hour of someone marking one of its findings actioned, and rewrites the briefing so the time it was updated moves on; anything else that changes on the project is picked up in the next overnight briefing.

A finding keeps its identity from one briefing to the next, and its card says where it stands: **new** if this briefing raised it, **worse** if it is worse than last time, or **resolved** if it was in the last briefing and is no longer true, and a finding carried over from an earlier briefing says how long it has been open. A resolved finding is shown once, faded, and doesn't count towards the verdict. A finding that stays the same keeps its level; the level moves only when something about the situation changes, and the description says what changed. How long something has been left counts once it holds something up, such as a missed check with the next trade about to start.

If a finding doesn't need raising, choose **Dismiss** from its **⋯** menu, saying why in your own words if you like; anyone who can see the finding can dismiss it, and you can also ask [NavantoAI](/docs/navantoai/) to dismiss one for you in chat or in a thread. It disappears straight away, and the briefing stops raising it unless it gets worse. If it does come back it is marked **worse**, and the description acknowledges the reason you gave. Dismissed findings are listed under **Dismissed** at the bottom of the briefing, with who dismissed each one, when and why. The verdict and the headline catch up the next time the briefing is rewritten.

Once a week NavantoAI looks over the findings dismissed across your projects. When the same kind of finding was dismissed on more than one project for the same reason, it records the reason as a rule in its [memory](/docs/navantoai/), and from the next briefing it stops raising that finding wherever the rule applies. You can also tell NavantoAI a rule yourself, such as "small jobs don't get a timeline". Ask it why it no longer flags something and it tells you the rule and where it came from; ask it to change or drop a rule and it will.

When you've dealt with a finding, choose **Mark as actioned** on its card, saying what you did under **What did you do?** if you like; you can also ask [NavantoAI](/docs/navantoai/) to mark one actioned for you in chat or in a thread. It moves straight to **Actioned** at the bottom of the briefing, with who marked it and when, and within the hour NavantoAI rechecks the project. If the records show it's sorted, the finding is resolved; if not, it comes back with the description saying what was done and what's still open. If you dealt with it outside Navanto and it doesn't need raising, **Dismiss** it instead.

Every open finding has **Talk it through**, which starts a new conversation in [NavantoAI](/docs/navantoai/) Chat and asks about the finding for you. It checks the finding against the project as it stands now, helps you work out what to do about it, and asks before it changes anything.

What each person sees in the briefing follows their role, the same as everywhere else in Navanto. The verdict, though, is the project's, and reads the same for everyone, on the badge and in the briefing; when some of the findings behind it are in areas your role doesn't include, the briefing says so rather than showing them. A project still in planning isn't briefed until its start date arrives, completed projects stop being refreshed, and clients never see any of this.

## Deleting a project

Only administrators can delete a project, and it cannot be undone. Deleting takes the project's client portal logins with it, so those clients lose their accounts and can no longer sign in. If the job is simply finished, mark it completed instead; that keeps everything and is reversible. A project whose [orders](/docs/orders/) have reached a supplier can't be deleted at all - complete it instead. Orders that were never sent are cancelled with the project.
