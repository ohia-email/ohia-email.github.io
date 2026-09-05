---
layout: default
title: Ohia
permalink: /
---

# Ohia

## Your correspondence. Your context. Your Mac.

Ohia is a native macOS email client that turns your correspondence into a personal knowledge workspace. Read and write, follow the people and projects behind your messages, and bring the relevant history into your next reply.

**Search, summaries, questions, and personalized drafting run locally on your Mac.** Ohia builds its understanding from your correspondence and personalizes a model for your own use, with no central Ohia mailbox-storage service.

[Explore the workspaces](#see-your-mail-from-a-different-perspective) · [Discover local intelligence](#intelligence-that-lives-on-your-mac) · [Read about privacy](#know-where-your-data-goes)

## Intelligence that lives on your Mac

### Find the meaning you remember

You may remember a discussion without remembering its subject line. Ohia builds a local semantic search index so you can look for related ideas in your correspondence. Bring scattered messages back into view and recover the context behind a person, topic, or project.

That index is built and stored on your Mac. Your mailbox does not need to be uploaded to an Ohia search service.

### Ask questions of your correspondence

Use Ask to explore the mail in your selected scope. Questions such as “What did we decide about the schedule?” or “Which messages explain this change?” become a way to revisit the evidence in your correspondence.

Ohia retrieves relevant context and generates an answer locally, with citations that lead back to source messages. Follow the references to check the details, or use summaries to orient yourself before reading a conversation in full.

### A writing model personalized for you

Your sent correspondence contains your vocabulary, tone, and ways of explaining things. Ohia uses eligible sent mail to fine-tune a local model for your own writing. The personalized model state stays in Ohia’s local storage and serves your use of the app.

This gives personalized drafting a foundation in how you actually write. The current message and relevant correspondence provide the context for a reply; your local personalization helps shape its expression. You can revise the draft and review it before sending.

**Your email is not used by Ohia to train a shared or general-purpose AI model.** Personalization belongs to your local workspace. [Learn how to manage or reset your data](/data-controls/).

## See your mail from a different perspective

One correspondence history can support several ways of working. Ohia brings reading, exploration, and drafting together through distinct workspaces.

| Workspace | What it helps you see |
| --- | --- |
| **Front Page** | A reading workspace that presents correspondence as articles and conversation cards, with summaries and a focused reader. |
| **Constellation: Meaning** | A spatial field of messages arranged by semantic relationships. Explore nearby ideas and clusters of related correspondence. |
| **Constellation: People** | Correspondence organized around the people behind it, making relationships a starting point for exploration. |
| **Timeline** | Messages across time, with controls for navigating periods and following how correspondence develops. |
| **Projects** | A workspace for exploring correspondence in the context of projects. |

Move from an overview into a message, recover its context, and take that context into Composer. Ohia’s spatial views are rendered natively with Metal, alongside a macOS reading and writing interface.

## From understanding to a considered reply

A useful email workspace connects what you have read with what you need to say. Ohia combines mailbox reading, local search, summaries, and grounded drafting in that workflow.

For example, when you return to a project after several weeks, you can explore its correspondence, follow the discussion through time, ask about earlier decisions, and prepare a reply using the relevant history. Source references give you a path back to the messages behind an answer.

Composer supports writing and revising replies, adding attachments, and managing drafts. Sending and mailbox operations use your connected email provider. Generated text remains something you review: accuracy, tone, recipients, and the decision to send stay with you.

## Know where your data goes

Local intelligence is a concrete part of Ohia’s architecture. Mailbox copies, search indexes, summaries, drafts, and personalized model state are stored on your Mac. Model inference and personalization use local computation. Account credentials and authorization tokens are kept in the macOS Keychain.

| On your Mac | Connections you use |
| --- | --- |
| Semantic indexing and search | Your mail provider handles account authorization, synchronization, sending, and requested mailbox changes. |
| Summaries and answers grounded in correspondence | Public model downloads and allowed remote email content contact their hosting services. |
| Personalized model training and draft generation | Optional connected sources and web research contact services you enable. Research requests can contain context derived from a message. |
| Local mailbox copies and personalized model state | Provider and recipient copies of email remain part of the normal email system. |

Ohia does not sell email data or use it for advertising. Optional external research is separate from the core local intelligence; automatic research is off for newly configured sources until you enable it. Local files rely on macOS account and filesystem protections and are not all separately encrypted by Ohia.

The [Privacy Policy](/privacy/) explains storage, connections, personalization, and retention. [Data controls](/data-controls/) explain how to remove local data and reset personalization.

## Built for the Mac. In active development.

Ohia brings native macOS interaction, Metal visualization, and local machine learning into an email client designed around the depth of your correspondence.

Provider authorization and release preparation are underway. There is no public app download yet, and account availability depends on provider requirements and integration readiness.

Developed by Jason G. Karlin. [Contact the developer](/support/) for product questions and access inquiries.

---

[Privacy Policy](/privacy/) · [Manage and delete your data](/data-controls/) · [Terms of Use](/terms/) · [Support](/support/)
