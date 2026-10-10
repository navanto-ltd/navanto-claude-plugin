---
title: Drawings
description: How drawings and revisions work, what the statuses mean, and which drawings your client can see.
section: projects
order: 3
audience: team
date: 2026-08-20
---

The Drawings page is the project's drawing register. Each drawing carries its title and code, and collects revisions; each revision is one issue of the drawing, with its own file, label and status. Anyone on your team can manage drawings; your client only ever sees approved ones. Your team can also read the register on site in the [iPhone app](/docs/ios-app/#drawings).

## Revisions

Each revision carries one PDF. Adding a revision starts a fresh one with the next label suggested for you, following whatever pattern you use (a, b, c or 1, 2, 3), and you can type your own.

The title and code stay with the drawing itself rather than any single revision, and you edit them from any saved revision. The one place they are locked is while you are adding a new revision to an existing drawing, so that saving your new issue cannot quietly rename the whole drawing.

## Statuses

A revision is **Not started**, **In progress**, **Complete**, **Approved** or **Rejected**. The last three describe a finished document, so they are only offered once the revision has a file attached; removing the file puts the revision back to **In progress**.

You can set a status by hand, and linked items also move it for you, once the revision has a file. When an [approval](/docs/approvals/) linked to a revision concludes, the revision is marked **Approved** or **Rejected** to match, provided every linked approval agrees and the revision has no decision of its own yet; the first decision sticks, and a later linked approval never overwrites it. Completing the last of a revision's linked [tasks](/docs/tasks/) marks it **Complete**. Linking a revision to an approval is how you have a sign-off chain drive the drawing.

## Reading a sheet with AI

After you upload a sheet, **Analyse with AI** reads it and fills in the revision label and description for you. On a drawing with no other revisions it fills the title and code too; once other revisions exist it leaves them alone, so one click cannot rename the drawing's whole history. Check what it wrote against the sheet before relying on it.

## Deleting

Deleting a revision moves you to the previous one. Deleting the last revision leaves the drawing in the register with no revisions; removing the drawing itself is a separate delete.

> Deleting a drawing deletes every revision of it, the whole history at once. To remove one issue, delete that revision instead.

## What your client sees

The portal's Drawings page lists **Approved** revisions only, and a drawing with no approved revision does not appear there at all. Approving a revision is what publishes it to your client.

If a client says a drawing is missing, check the revision status first: it is usually a drawing that has not been approved yet.
