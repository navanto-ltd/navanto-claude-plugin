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

Every finish has a kind, and its code comes from that kind: **P** for Paint, **W** for Wood, **M** for Metal, **T** for Tile, **S** for Stone, **L** for Laminate, **F** for Fabric, **G** for Glass and **X** for Other. A new finish takes the next free code of its kind, so your second paint is P2, and you can change the code if your drawings already use a different one. Alongside its code a finish has a name, the maker's reference, the maker, a colour, a sample photo and notes.

The palette is always in view, with the room you're in first: on a wide screen it sits beside the rooms and on a smaller one in a bar at the bottom of the screen, and **Palette** opens the full list. Point at a finish to see where it's used in the room, drag it onto a detail to use it there, or click it to edit it. Each finish shows how many places it's used in. Editing it changes all of those places at once, which is also why a finish that's in use can't be deleted until you take it out of the rooms. Filtering the palette by kind gives you a schedule of just that kind; filtered to Paint, it is your paint schedule.

## Your finishes library

The finishes you use on job after job, such as a company spray colour, a carcass decor or a fabricator's patina, live on the **Finishes** tab in **Library**, beside Products, Suppliers and Templates. An entry has the same parts as a palette finish, apart from the code, and saves as you go. The list shows how many projects use each one. **Archive** takes an entry out of the pickers without changing any project that already uses it, **Show archived** brings archived entries back into view, and **Restore** puts one back in use. You can delete an entry only while no project uses it.

On a project, the **+** on the palette searches your library, with entries of the kind you've filtered the palette to at the top, and searches your products as you type. Choosing one adds it to the palette with the next code for its kind; a product asks which kind it is first. **Create new finish** starts one from scratch, with every field ready to fill in, photo included. Whatever you add is a copy of its name, reference, maker, colour and photo, so editing the library or the product later never changes a project, and the palette shows where each finish came from. To keep a finish you created yourself for other projects, open it and choose **Add to library**.

Not everything belongs on the palette: a tap or a pendant usually goes in one place. When you click a detail's value and type, matching library finishes and products are offered for that detail alone, without a code. If it turns out to be needed elsewhere, right-click the detail and choose **Add to palette**.

Changing the library needs the Library [permission](/docs/roles-and-permissions/). Anyone who can use Finishes can add from the library and from products, and sees products without their prices.

## Sample photos

A colour can't show oak, brass or marble, so a finish can carry a photo of the real sample. Open a finish on the palette and choose **Add photo**, or add one to a library entry. Wherever the finish appears, in the palette, the rooms, the pickers and the library, the photo shows in place of the colour, and the colour stays as the fallback while a new photo is processing. A finish added from a product brings the product's photo with it.

## Rooms, groups and details

**Add room** lists your organisation's [room templates](/docs/templates/#room-templates), which start out as Kitchen, Bathroom, Bedroom, Living room, Utility room and External, and **Blank room**. A room takes a copy of its template's groups and details, so you can tailor it freely, and later changes to the template never reach it. Rooms are tabs along the top, which stay in view as you scroll. A room is made of groups, joinery for instance, and each group of details, such as Door style. To rename or delete a room, a group or a detail, or for anything else you can do to it, right-click it, or click the handle that appears when you point at a group or detail. The **⋯** at the end of the room tabs does the same for the room you're on. On a phone or tablet, use the **⋯** on a group or a detail. Drag any of them to change the order. **Add group** adds a group with its name ready to type.

A detail's value is one of four things:

- a **finish** from the palette;
- a **library finish or product** for that detail alone;
- **spec text**, for anything else, with suggestions as you type drawn from your room templates and from your organisation's earlier projects;
- a **choice**, one of a fixed list of options, such as Yes or No for soft-close hinges.

Typing in a detail's value searches the palette, your library, your products and the suggestions at once. A choice offers its options and nothing else, and an unanswered one is a gap like any other. To make a detail a choice, click its empty value and choose **Type** at the bottom of the box, or right-click it and choose **Change type**; it starts with Yes and No, which you can change. **Edit options** does the same for a detail that's already a choice. The type can only change while a detail has no value, and you can't remove the option it's set to until you clear it. Any detail can also have a note for that place, such as which wall it goes on, whether or not anything is chosen yet; it stays when you change or clear the value.

Click a value, type, and **Enter** saves it. **Add detail** adds one to a group, and **Add another like this** adds one straight after the detail you're on.

## Gaps

A schedule rarely starts complete, so Finishes keeps the gaps easy to find. A detail with no value is a gap, and **Decide later** marks one you're leaving open on purpose, with a note of what you're waiting on, set when you click the value: the client's choice of tile, say. Each room's tab counts how many of its details are specified, **Gaps only** lists the details still to settle from every room on one page, and search looks across every room at once. Either one swaps the room tabs for a line saying what you're looking at; **Show all rooms** takes you back.

Everything saves as you go. On a [completed project](/docs/projects/) the schedule stays readable but nothing can be changed, and Finishes appears only for roles that include the Finishes [permission](/docs/roles-and-permissions/).
