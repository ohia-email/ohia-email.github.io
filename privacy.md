---
layout: default
title: Privacy Policy
permalink: /privacy/
---

# Privacy Policy

Effective September 5, 2026

This policy describes how Ohia, a native macOS email client developed by Jason G. Karlin, handles information. Contact: [ohia_email@icloud.com](mailto:ohia_email@icloud.com).

## Information Ohia accesses

When you connect an email account, Ohia accesses account and mailbox information needed for its features: your email address and identities, message headers, senders and recipients, message bodies, attachments, folders or labels, message status, and drafts. It stores authorization tokens or provider-specific credentials to maintain the connection.

Ohia also processes text you write, questions you ask, attachments you add, and the edits you make to drafts. If you choose additional sources and grant the relevant macOS permissions, it can use information from files, Contacts, Calendar, Messages, or screen content to help with your work. Information returned by connected external sources may become part of a draft or its supporting context.

## How your information is used

Ohia uses this information to synchronize and display mail; search, organize, and summarize correspondence; prepare replies; maintain drafts; send messages you direct it to send; and carry out mailbox actions you request, including deleting or restoring messages and discarding drafts.

Local processing creates search indexes, summaries, semantic representations, and contextual information. Ohia also uses eligible sent correspondence and drafting evidence to personalize a model for your own writing. That personalization takes place on your Mac and serves your use of Ohia. Your email is not used by Ohia to train a shared or general-purpose AI model.

Ohia does not sell email data, use it for advertising, or provide it to data brokers.

## Storage and security

Mailbox copies, attachments, drafts, derived information, and personalized model state are stored in Ohia's local application storage. Ohia does not operate a central mailbox-storage service. Account tokens, mail credentials, and external-source secrets are stored in the macOS Keychain.

Mail and authorization connections use encrypted transport. Local application files rely on macOS account and filesystem protections; they are not all separately encrypted by Ohia. Device access, FileVault settings, and backups affect the protection and retention of local data.

## Connections and sharing

**Your email provider.** Ohia communicates with your provider to sign in, synchronize mail, send messages, and perform the mailbox actions you request. Sending delivers the message and attachments to the addressed recipients through the email system. Provider and recipient copies are governed by their respective services and policies.

**Optional connected sources.** If you configure an external source, Ohia sends that service the requests needed to use it. When you enable automatic source research, this can include privacy-filtered research questions derived from the current message or compose brief. Filtering reduces disclosure; it does not guarantee that a question contains no sensitive context. Automatic research is off for newly configured sources until you enable it. Requests and results may contain information related to your correspondence. The connected service receives the request and normal connection information, and its own processing and retention policies apply. You can disable or remove sources in Ohia's settings.

**Web content and model downloads.** Fetching a web page, loading allowed remote email images, or downloading a public model contacts the relevant hosting service. It receives normal request information such as your IP address. Downloading a model does not require uploading your mailbox or personalized model to its host.

**Support.** If you contact the developer, the information you choose to send is used to respond and investigate the request. Support does not provide automatic access to your mailbox or Mac. Share only the diagnostic material needed, and omit passwords, tokens, and unrelated private correspondence. Support correspondence is retained in the support mailbox until deleted; you can request its deletion at the contact address above, subject to any necessary legal retention.

## Google user data and Limited Use

Ohia follows the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including its Limited Use requirements, when using or transferring information received from Google APIs. The same restrictions apply to information derived from that data.

Google mailbox access supports the email-client and productivity features described above. Gmail's full-mail permission is used for authenticated IMAP and SMTP and for supported mailbox and draft operations. Its broad capabilities include reading, sending, modifying, and permanently deleting email; Ohia uses them for its described features and user-directed actions.

Personalized learning is limited to the specific user's model. Google user data is not used to create or improve models shared with other users. Optional transfers to connected services must serve the enabled feature and the user's authorization; they are not permission to use Gmail data for advertising, resale, or shared-model training.

## Retention, revocation, and deletion

Local information remains available while you use Ohia and until it is deleted or reset. Revoking an account's provider authorization stops further authorized access but does not itself erase copies already stored on your Mac.

Use Ohia's full reset to remove its accounts, stored credentials, local messages, attachments, drafts, indexes, summaries, and personalized training state. A training-only reset removes personalization checkpoints, but eligible correspondence can produce new personalization while training remains active. Provider mailbox copies, files you exported, and backups outside Ohia must be managed separately. Public model downloads may be retained because they contain no personal training state. See [Manage and delete your data](/data-controls/) for the current controls.

## This website

This public site does not request access to your mailbox. It is hosted by GitHub Pages and uses theme assets delivered by GitHub Pages and Cloudflare's cdnjs. These hosts receive ordinary web-request information. See [GitHub's Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement) and [Cloudflare's Privacy Policy](https://www.cloudflare.com/privacypolicy/). Ohia has not added advertising or visitor-analytics tools to this site.

## Changes and contact

Changes to this policy will appear here with a new effective date. Material changes to email-data use require updated notice and any required user consent before that new use begins.

For privacy questions or support-data deletion requests, email [ohia_email@icloud.com](mailto:ohia_email@icloud.com) with the subject “Ohia privacy.” You do not need to send mailbox contents to make a request.

---

[Home](/) · [Manage and delete your data](/data-controls/) · [Terms of Use](/terms/) · [Support](/support/)
