---
title: Finishes
description: How to build a project's finishes schedule from a palette of coded finishes, room by room, and keep track of what is still to decide.
section: projects
order: 12
audience: team
date: 2026-10-26
---

Finishes is the project's finishes schedule. You define each finish once in the project's **palette**, give it a code, then work through the rooms saying which finish or specification goes where. Rooms point at the palette rather than repeating it, so changing a finish once changes it in every room that uses it.

## The palette

Every finish has a kind, and its code comes from that kind: **P** for Paint, **W** for Wood, **M** for Metal, **T** for Tile, **S** for Stone, **L** for Laminate, **F** for Fabric, **G** for Glass and **X** for Other. A new finish takes the next free code of its kind, so your second paint is P2, and you can change the code if your drawings already use a different one. Alongside its code a finish has a name, the maker's reference, the maker, a colour and notes.

The palette is always in view, with the room you're in first: on a wide screen it sits beside the rooms and on a smaller one in a bar at the bottom of the screen, and **Palette** opens the full list. Point at a finish to see where it's used in the room, drag it onto a detail to use it there, or click it to edit it. Each finish shows how many places it's used in. Editing it changes all of those places at once, which is also why a finish that's in use can't be deleted until you take it out of the rooms. Filtering the palette by kind gives you a schedule of just that kind; filtered to Paint, it is your paint schedule.

## Rooms, groups and details

**Add room** starts a room from Kitchen, Bathroom, Bedroom, Living room, Utility room or External, or a blank one. Rooms are tabs along the top, which stay in view as you scroll. A room is made of groups, joinery for instance, and each group of details, such as Door style. To rename or delete a room, a group or a detail, or for anything else you can do to it, right-click it, or click the handle that appears when you point at a group or detail. The **⋯** at the end of the room tabs does the same for the room you're on. On a phone or tablet, use the **⋯** on a group, and **More actions** in a detail's editor. Drag any of them to change the order. **Add group** adds a group with its name ready to type.

A detail's value is one of two things:

- a **finish** from the palette, with an optional note for that place, such as which wall it goes on;
- **spec text**, for anything that isn't on the palette, with suggestions as you type drawn from the starter rooms and from your organisation's earlier projects.

You can fill a room from the keyboard: click a value, type, and **Enter** saves it and moves you on to the next detail. **Add detail** adds one to a group, and **Add another like this** adds one straight after the detail you're on.

## Gaps

A schedule rarely starts complete, so Finishes keeps the gaps easy to find. A detail with no value is a gap, and **Decide later** marks one you're leaving open on purpose, with a note of what you're waiting on, set when you click the value: the client's choice of tile, say. Each room's tab counts how many of its details are specified, **Gaps only** lists the details still to settle from every room on one page, and search looks across every room at once. Either one swaps the room tabs for a line saying what you're looking at; **Show all rooms** takes you back.

Everything saves as you go. On a [completed project](/docs/projects/) the schedule stays readable but nothing can be changed, and Finishes appears only for roles that include the Finishes [permission](/docs/roles-and-permissions/).
