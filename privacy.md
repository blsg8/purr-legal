# Privacy Policy

**Effective: May 8, 2026**

Purr is a macOS notes application developed by KatLabs ("we", "us", "our"). This Privacy Policy explains what data Purr handles and how.

## Short version

Purr does not collect, transmit, or sell your personal data. Your notes stay on your device and, optionally, in your own iCloud account. We have no servers, no analytics, no tracking, no ads.

## Data we do not collect

We do not collect:

- Your notes, tags, tasks, attachments, or any content you create in Purr
- Personal identifiers (name, email, IP address, device ID, advertising identifier)
- Usage analytics, telemetry, or session recordings
- Crash reports (unless you explicitly send them via macOS system reporting, which goes to Apple — not to us)
- Advertising or marketing data

We do not use third-party analytics, advertising SDKs, fingerprinting, or tracking services.

## Data stored on your device

Purr stores your notes, tags, tasks, attachments, settings, and preferences locally on your Mac, inside the macOS application sandbox. This data never leaves your device unless you explicitly enable an integration described below.

## Optional iCloud sync

If you are signed in to iCloud on your Mac and have iCloud Drive enabled for Purr, your notes synchronize to your own iCloud account using Apple's CloudKit framework.

- This data lives in your private iCloud database.
- We do not have access to it. It is governed by Apple's iCloud terms.
- You can disable sync at any time via System Settings → Apple ID → iCloud → Apps Using iCloud.

## Optional integrations with other apps

Purr offers integrations that run only when you explicitly enable them:

- **Obsidian.** Purr reads and writes Markdown files in a folder you grant access to via macOS security-scoped bookmark. Files stay in your filesystem; nothing is sent to us or to Obsidian's servers.
- **Apple Notes.** Purr reads and writes notes in your Apple Notes app via macOS scripting (AppleScript). All data exchange happens locally between two apps on your Mac.

Synchronization runs only on the schedule you choose (manual, daily, or weekly). Purr never polls our servers — we don't have any.

## On-device AI features

Some features (semantic search, smart suggestions, embeddings) use machine-learning models that run entirely on your Mac. No content is sent to OpenAI, Anthropic, Google, or any other third-party AI provider.

If you optionally configure a local Ollama instance, queries go only to your `localhost` — never to us or to third parties.

## Purchases

In-app purchases and subscriptions are processed by Apple via StoreKit. We never see your payment information; Apple does. Subscription status and receipt validation happen on-device against Apple's servers under Apple's privacy policy.

## Local backups

Purr can create local backup archives (`.zip` files) at a location you choose. These archives never leave your device unless you move them yourself.

## Spotlight search

Purr registers note titles and previews with macOS Spotlight to enable system-wide search. The Spotlight index is managed by macOS and never leaves your device.

## Children's privacy

Purr is not directed at children under 13 and does not knowingly collect any data — from anyone, including children.

## Your rights

Because we do not collect any personal data, there is nothing for us to access, export, correct, or delete on our side. To delete your local data, uninstall Purr. To delete your iCloud data, sign in to iCloud.com with your Apple ID and remove Purr's data, or contact Apple Support.

## Changes to this policy

If we update this policy, we will change the "Effective" date above and post the new version at the same URL. Material changes will be announced in-app or in the App Store update notes.

## Contact

Questions about this policy: bastiansoto.bs@gmail.com
