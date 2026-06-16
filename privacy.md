---
redirect_to: "https://rightcard.ai/privacy"
---

# RightCard Privacy Policy

**Effective date:** June 16, 2026

RightCard helps you choose the best credit card for any purchase. It is built to
be **privacy-first**: no sign-up, no personal information, and no tracking.

## The short version
- **No accounts, no personal info.** We never ask for or collect your name,
  email, phone number, address, account numbers, balances, or login credentials.
- **No tracking, no ads, no analytics.** RightCard contains no advertising,
  attribution, or analytics SDKs.
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

- An **anonymous identity** — a randomly generated device ID and access token. It
  is **not linked to any personal information** and is created automatically (no
  sign-up).
- The **card offers you choose to sync** from your bank, stored only as
  `{ card, merchant, percentage/amount, expiration, source }`. These are private
  to your anonymous identity and isolated by row-level security so no other user
  can read them. **We never store account numbers, balances, transactions, or any
  personal information.**

All network traffic uses HTTPS.

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
- Use **Data & About → Clear synced offers** to delete the offers stored under
  your anonymous identity.
- **Deleting the app** removes your device-only session and anonymous identity.
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
