---
title: Roles and permissions
description: How to create roles for your team and control which features each role can see and use.
section: getting-started
order: 3
audience: admin
date: 2026-08-29
---

Every team member has one role, and the role decides what they can see across your organisation. Navanto starts you with three: **Admin**, for the people who run the organisation, **Standard**, for most of your team, and **Site**, for site staff who only need to post updates. You can rename any of these, and add as many of your own as you need — an Office role, a Subcontractor role, whatever fits how your business works.

## Creating a role

Roles live under Settings, on the Roles tab. **New role** asks only for a name; the role appears in the list the moment you name it, with nothing switched on. Changes save as you make them.

Pick the new role in any user's profile to move them onto it — the Role column in your users list shows who holds what.

## The feature switches

Each role has a switch per feature: Tasks, Approvals, Snagging, Site updates, Timeline, Posts, Calendar, Drawings, Files, Library, Orders, Contract, Forecasting, and Client portal. Switching a feature on enables it for the role; leaving it off hides it for those users entirely — it disappears from their navigation, their pages, their dashboard, and NavantoAI won't discuss it with them either. Requests for a hidden feature are refused the same way on the server, so hiding something is a real boundary, not just a tidier menu. That holds on the screens that gather several features together too: the activity feed, a project's risk briefing, NavantoAI's summaries and the link chips between records all leave out anything belonging to a feature the role can't see. Notifications go further — they are never sent in the first place, so someone who can't see Posts gets no post notifications in the app and no post emails either.

A couple of features come as a set, because one is built from the other's data: **Forecasting includes Contract, and Contract and Orders each include Library**. Switch Forecasting on and the editor switches Contract and Library on with it; switch Library off and everything that needs it switches off too. Library is one switch for all of it — products with their trade costs, suppliers and templates — so give it only to roles that should see what you pay suppliers. The Files switch controls the file browser in the sidebar — attachments on tasks, snags, drawings and contract items belong to those features and keep working whether or not Files is on.

Visibility is the only lever the switches pull. Whether someone can create, edit or delete within a feature they can see follows the rules Navanto has always used — your own posts and site updates are yours to manage, some operations stay admin-only, and so on. There's nothing extra to configure for that. Projects themselves aren't on the list, because every role needs them; which projects a role can open is a separate setting, covered in [Limiting a role to its own projects](#limiting-a-role-to-its-own-projects).

> A permission change reaches the person's screen within a few minutes, not instantly — worth knowing when you're testing a role you just edited. Notifications sent before the change stay in their bell; opening one now tells them they no longer have access.

## Limiting a role to its own projects

Each role also has a **Project access** switch, **Only projects they're a member of**, which starts off so that everyone holding the role can open every project your organisation runs. Switch it on and the people holding that role only see the projects they're on the team of, which you set in the **Team** step when you create a project or in its **Project details** afterwards.

For those people the rest of your projects don't show up anywhere in Navanto; they're left out of the Projects page, the home page, the calendar, the activity feed, their tasks and approvals, the file browser and the records NavantoAI can look up for them, and a link to one of them just says the project can't be found. They get no notifications or emails about those projects either. Counts and totals follow the same rule, so a forecast or a figure on the home page only covers their own projects. Purchase order numbers are the one exception: they run in a single sequence across your whole organisation, so someone with a limited role who raises orders can work out roughly how many your business has placed.

You can't give a task, a snag or an approval to someone who can't see the project, or mention them in a post there, so the pickers leave them out and Navanto tells you why if you try. An approval never gets stuck on someone who has lost sight of its project, though. If a person with a limited role is waiting to decide an approval on a project they're not on, it stays in their approvals list and they can open it, read its documents and decide it as usual; once they've decided, it disappears for them along with the rest of that project. The Admin role always sees every project, and your clients are unaffected because they only ever see their own project's portal.

## Client portal is different

The **Client portal** switch doesn't hide a feature your team uses day to day — it controls whether a role can open the client-portal preview and the portal setup screen, and it covers everything in them: the preview shows your client's view in full — drawings, contract items, files and all — regardless of what the role's other switches say, and managing the portal's files needs only this switch, not Files. Someone with Client portal on but Drawings off still sees drawings in the preview, because the preview is the client's view, not theirs.

The same switch decides whether a role can put anything in front of your client. Sending the weekly client update, sending a selection or a variation, revoking one, deleting one the client is looking at, posting to the portal feed, marking a calendar event as visible to the client, approving a drawing revision and adding or removing files in the portal's folder all need Client portal on — with it off, those buttons disappear and the role works entirely within your team. A Site user can keep the diary going all week and still see what was last sent to the client, read-only; drafting and sending the client update stays with whoever holds Client portal.

Anything your client can already see is covered too, not just the moment it was shared. A role with Calendar but not Client portal works freely on your team's own events, and cannot touch one marked visible to the client — not to rename it, move it, hide it again or delete it — because every one of those changes what your client reads. The same goes for a selection the client is choosing from — it can be revised or withdrawn only by someone who holds Client portal — and for a drawing revision that has been approved onto the portal: changing it, or deleting it or its drawing, needs the switch. When an approval workflow is what approves a drawing, the drawing publishes to the portal only if the person giving the final approval holds Client portal; otherwise the approval still goes through and the drawing waits for someone who does. Variations sit behind the switch entirely: the portal shows your client every variation, even drafts awaiting a price, so creating or editing one is always Client portal work. And once a diary entry's photos have gone out in a client update, editing or deleting that entry needs Client portal too, because doing so would change — or take down — what was sent.

Actual client users — the people your clients log in as — are never affected by roles. They only ever see their one project's portal.

## The three seeded roles

**Admin** has every feature enabled, permanently — its switches can't be changed and the role can't be deleted, so you can never lock yourself out of your own organisation. Managing the organisation — users, roles and settings — always belongs to Admin.

**Standard** starts with everything visible except Forecasting, which is admin-only until you choose to open it up.

**Site** starts with only Site updates enabled — built for people whose whole job on Navanto is opening a project and posting what happened that day, without the rest of the app cluttering their view.

Standard and Site can be adjusted, and custom roles beyond them can mix and match freely. Any role can be renamed; roles other than Admin can be deleted once nobody holds them — move their people to another role first.
