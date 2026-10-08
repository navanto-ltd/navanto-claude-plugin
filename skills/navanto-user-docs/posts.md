---
title: Posts
description: The project conversation — threads, mentions, and how a post ends up in front of your client.
section: projects
order: 9
audience: team
date: 2026-09-24
---

Posts are the project's conversation, and they live in the activity feed on the project's [overview](/docs/projects/), with the composer at its foot. A post is text — up to 5 attached files if you need them — and anyone whose role includes Posts can write one.

> There is no edit, so read a post back before you send it. A post can be deleted — see below — but not changed once it's up.

While a project's posts are on screen — the overview's feed on **All activity** or **All posts**, or a thread — its post notifications count as read: opening it clears them from the bell, and one that arrives while you're looking never lights the bell. Switching the feed to **Client posts**, or to the risk briefing on a phone, stops that.

## Threads and mentions

Following **Reply**, or the reply count, on a post opens its thread in the same panel, with the composer set to reply into it; **‹** takes you back to the feed. A notification about a post opens its thread with that post picked out.

**Reply** on a post starts its thread; replies all sit one level under the first post, so replying to a reply joins the same thread. New posts and replies notify the project's team, with the people in a thread told specifically when it gets a reply — and to be sure a particular person sees something, @-mention them, which notifies them even if they are not on the project. The one exception is someone whose role only shows them their own projects: they can only be mentioned on projects they're on the team of, and the mention list leaves them out everywhere else.

@-mention **NavantoAI** in a team post or reply and it answers in the thread, as itself. It reads the thread and the project through the same information your role can see, so ask it the way you would a colleague: "what's overdue on this project?", "when is the handover?", "has the client decided on the kitchen?". It replies once, usually within a minute, and you are notified like any other reply. After that the thread is a conversation: reply with a follow-up and it answers without being mentioned again, and if you reply to a colleague instead, or just say thanks, it stays quiet. Anyone on the team can join in, and it answers each person with what their own role can see. Ask it to do something from the thread — create a task, move a date — and it does it without asking you to confirm, then says what it changed; see [NavantoAI](/docs/navantoai/) for how far that goes. It never joins a client post, and clients cannot mention it.

## Posts and your client

A post goes to your team unless you say otherwise. The composer's **To: Team** control, shown only if your role includes the [Client portal](/docs/roles-and-permissions/) permission, switches to **To: Client**; the field and the send button turn green so it's obvious where the post is headed, and sending puts it on the client's portal and notifies them by email — there's no extra confirmation, and a post sent in error can be deleted. It stays on **To: Client** for your next post until you switch it back. While it says **To: Client**, the project's client users join the @-mention list; on a team post they aren't offered, because a mention the client can't see would go nowhere.

Replies inherit the visibility of the thread they're in: inside a client-visible thread the composer is already set to **To: Client** and sends straight to the client's portal — there's no choice to make. If your role doesn't include Client portal, the composer tells you **Your role does not include Client portal, so you can't reply to this client-visible post.**

In the feed, a client-visible post reads **posted to the client** instead of *commented*, with a small green eye on the author's avatar and a green outline on the card. Attachments on them land in the project's **Client Portal** folder, same as any portal post. You can also post as the client from the [portal preview](/docs/client-portal-setup/) — it just isn't the only way in.

On a [completed project](/docs/projects/) the conversation stays readable but closed — no new posts or replies.

## Deleting a post

Hover over a post and open the **⋯** menu that appears beside it, then choose **Delete** — a confirmation follows. You can delete your own posts; admins can delete anyone's; a client can delete their own from **My Project**. Deleting a top-level post takes its whole thread with it, and the modal tells you how many replies will go. Deleting a client-visible post also needs the Client portal permission — if the client can already see it, you need the grant to change it. Attachments go with the post, and posts on a completed project can't be deleted.
