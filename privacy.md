---
redirect_to: "https://rightcard.ai/privacy"
---

# RightCard Privacy Policy

**Effective date:** June 17, 2026

RightCard helps you choose the best credit card for any purchase. It is built to
be **privacy-first**: an account is optional, we collect no unnecessary personal
information, we never connect to your bank, and there is no third-party tracking.

## The short version
- **An account is optional.** You can use RightCard fully without signing in. If
  you choose to create an account — to back up your synced offers and use them on
  another device — we store only the identifier you sign in with: a **Sign in with
  Apple** identifier (which can be a private *Hide My Email* relay address) or an
  email address. We never ask for your name, phone number, or address.
- **No bank login, ever.** RightCard never connects to your bank or card through
  Plaid or any other aggregator, and never sees your account numbers, balances, or
  transactions.
- **No third-party tracking or ads.** RightCard contains no advertising,
  attribution, or third-party analytics SDKs. We keep only minimal first-party
  usage data (your app version and the date you last opened the app) to understand
  active usage — never sold or shared.
- **Location is optional and stays on your device.** By default we use only a
  fixed, country-level region hint — no location access. If you turn on the
  optional **Offer alerts nearby** feature, RightCard uses your location **in the
  background** to alert you when you're at a store that has an offer on one of your
  cards. That location is used only on your device (and by Apple Maps to find
  nearby stores) and is **never sent to our servers, stored, or logged.** It is off
  by default and the app works fully without it.
- **Notifications are local.** Any reminders — an offer about to expire, your sweep
  streak, or a nearby offer — are scheduled **on your device**. We don't run a push
  server, and nothing about them leaves your phone.
- **Your recommendations run on your device** and work offline.

## What we store, and where

**On your device:**

- The cards you select in "Manage Cards" and your reward-valuation preference.
- A cached copy of public card and merchant data for offline use.
- A secure, device-only session token (kept in the iOS Keychain; never synced to
  iCloud and excluded from backups).

**On our backend (Supabase):**

- An **anonymous identity** — a randomly generated ID and access token, created
  automatically with no sign-up and not linked to any personal information.
- If you create an account, the **sign-in identifier** you used: a Sign in with
  Apple user identifier (and the email Apple shares with us, which may be a private
  `@privaterelay.appleid.com` relay address), or the email address you registered.
  Creating an account does not change what app data we hold — it keeps the **same**
  identity, so your synced offers simply become recoverable and syncable across
  your devices.
- The **card offers you choose to sync** from your bank, stored only as
  `{ card, merchant, percentage/amount, expiration, source }`. These are private to
  your identity and isolated by row-level security so no other user can read them.
  **We never store account numbers, balances, transactions, or any personal
  information.**
- A **minimal usage record** — your app version and the date you last opened the
  app, tied to your identity — used only to measure active usage. No spend, no
  transactions, no personal profile.

All network traffic uses HTTPS.

## Your account (optional)

RightCard works fully without an account. Creating one is entirely optional and
exists for a single purpose: to **back up the offers you've synced and make them
available on your other devices** (and to recover them if you reinstall the app).

- You can sign in with **Sign in with Apple** (including *Hide My Email*, so we
  only ever see a private relay address) or with an **email and password**. That is
  the only information an account adds.
- An account is **never** a bank login. We never ask you to connect a card, link a
  bank, or share credentials.
- Your data stays isolated to you by row-level security — no other user can read it.
- You can **sign out** at any time, or **permanently delete** your account and its
  data from inside the app (see "Deleting your data").

## Location and Notifications (optional)

**Location.** RightCard does not use your location by default; merchant search
uses a fixed, country-level region hint. If you enable **Offer alerts nearby**,
RightCard uses background location (with your "Always" permission) for a single
purpose: to detect when you arrive at a merchant that has an offer on one of your
cards, and to show you a reminder. The coordinate is used **only on your device**
— to ask Apple Maps what stores are nearby and to match them against the offers
already stored on your device. It is **never transmitted to our servers, never
stored, and never logged.** The feature is **off by default**, you can turn it off
at any time, and the app is fully functional without it.

**Notifications.** RightCard's reminders — for offers about to expire, your weekly
sweep streak, and nearby offer alerts — are **local notifications scheduled on
your device.** We do not operate a push-notification server; no notification
content or schedule is sent off your phone. Notifications are opt-in.

## The Safari extension (optional)
RightCard includes an optional Safari extension that, **only on your bank's
website and only when you choose to use it**, reads the **offer details shown on
the page** (merchant name, percentage/amount, expiration) so it can add them to
your wallet and — if you opt in — activate them for you.

- It runs **only** on supported card-issuer domains (American Express, Chase,
  Citi, Capital One, Discover, Bank of America, Wells Fargo, U.S. Bank). It does
  not run on any other website.
- It **never** reads or transmits your username, password, account numbers,
  balances, or transaction history.
- Your RightCard access token is never exposed to the extension.

## Sharing of Data
We do **not** sell, rent, or share your data with third parties. We have no
advertising or data-broker relationships.

## Deleting Your Data
- Use **Settings → Account → Delete account** to permanently delete your account
  and the offers synced to it.
- Use **Settings → Clear synced offers** to remove the offers stored under your
  identity while keeping the app.
- **Deleting the app** removes your device-only session.
- To request deletion of any remaining data, email us (below).

## Children's Privacy
RightCard is not intended for children under 13. We do not knowingly collect
personal information from children.

## Changes to This Policy
If we change this policy, we will update the effective date and publish the
updated version at this same URL.

## Contact
If you have questions about this policy, contact:

**Email:** rightcard.108@gmail.com
