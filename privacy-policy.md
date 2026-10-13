# Privacy Policy — SCcompanion Discord Bot

**Last updated:** 14 October 2026

This Privacy Policy explains what personal data the SCcompanion Discord bot
("the Bot") processes, why, where it is kept, and how you can have it removed.
It forms part of our Terms of Service.

## 1. Who is responsible for your data

The Bot is operated by an individual developer acting as data controller for the
limited data it holds. Contact: *[your contact email or Discord handle]*.

## 2. What the Bot stores

The Bot stores as little as possible. It keeps a single local database file
(`data/org.sqlite`) containing:

| What | Why | Where |
|---|---|---|
| Discord **user ID** | To attribute a hangar entry to the person who added it | Local database file |
| Discord **server (guild) ID** | To keep each server's data separate | Local database file |
| **Ship names and quantities** you add via `/hangar` | To provide the hangar commands | Local database file |

That is the complete list. Specifically, the Bot does **not** store:

- message content — it does not read messages at all;
- your Discord username, email address, avatar or any profile details;
- your IP address;
- any Star Citizen account details, credentials or RSI handle; or
- any payment or financial information.

The Bot requests only the `Guilds` gateway intent, which means it can see which
servers it is in. It has no access to message content.

## 3. What the Bot does not do

- It does not sell, rent or share your data with anyone.
- It does not use your data for advertising or profiling.
- It does not send your data to third parties, with the exception noted below.

## 4. Third-party services

When you use a lookup command — `/ship`, `/commodity`, `/route` or `/locate` —
the Bot sends **the search term you typed** to one of two community APIs:

- the **Star Citizen Wiki API** (api.star-citizen.wiki); or
- the **UEX Corp API** (api.uexcorp.uk).

Only the game-related search term is sent. No Discord identifiers, and no
information about you or your server, is included in those requests. Those
services have their own privacy practices, which we do not control.

## 5. Legal basis for processing

Under the UK GDPR, we rely on **legitimate interests** to process your user ID,
server ID and hangar entries. The interest is a narrow and obvious one: running
the hangar feature you chose to use, inside the server you are in. The data is
minimal, it is not used for anything else, and you control whether to add it in
the first place by choosing whether to run the command.

## 6. Where your data is kept

The database file is stored on the machine that hosts the Bot. It is not
uploaded to any cloud service, and it is not shared between servers — each
server's hangar data is kept separate using its guild ID.

**Retention.** Hangar entries are kept until you remove them, until the server
is removed, or until the Bot is discontinued. There is no automatic expiry.

## 7. Your rights

Under the UK GDPR you have the right to:

- **access** the data held about you;
- **correct** it if it is wrong;
- **erase** it (the "right to be forgotten");
- **restrict** or **object** to its processing; and
- **complain** to the Information Commissioner's Office (ico.org.uk).

Because the Bot stores only a user ID, a server ID and the ship entries you
added, exercising any of these is straightforward.

**To have your data deleted**, you can either:

1. run `/hangar remove` for each ship you have added, which deletes the entries
   yourself; or
2. ask a server administrator to remove your rows, or contact us at *[your
   contact email or Discord handle]* and we will delete everything associated
   with your Discord user ID.

We will action a deletion request within 30 days.

## 8. Children

The Bot is not directed at children. Discord's own minimum age applies — 13 in
most countries, or older where local law requires.

## 9. Security

The database file sits on a private machine and is not exposed to the internet.
The Bot's access token is kept out of source control. No system is perfectly
secure, but the data at risk here is deliberately minimal — the loss of a ship
list and a Discord ID would not expose anything sensitive about you.

## 10. Changes to this policy

If what the Bot stores ever changes, this policy will be updated and the "Last
updated" date revised. Material changes will be announced in the server where
the Bot runs.

---

*This document is provided as a template and does not constitute legal advice.
For a publicly distributed or commercial bot, have it reviewed by a qualified
professional, and consult the ICO's guidance on legitimate interests.*
