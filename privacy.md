---
redirect_to: "https://rightcard.ai/privacy"
---

# RightCard Privacy Policy

**Effective date:** June 12, 2026

RightCard helps you choose the best credit card for any purchase. It is built to
be **privacy-first**: no sign-up, no personal information, and no tracking.

## The short version
- **No accounts, no personal info.** We never ask for or collect your name,
  email, phone number, address, account numbers, balances, or login credentials.
- **No tracking, no ads, no analytics.** RightCard contains no advertising,
  attribution, or analytics SDKs.
- **Location is optional and stays on your device.** By default we use only a
  fixed, country-level region hint — no location access. If you turn on the
  optional **Nearby reminders** feature, RightCard uses your location **while you
  are using the app** to suggest your best card at a nearby store. That location
  is used only on your device (and by Apple Maps to find nearby stores) and is
  **never sent to our servers, stored, or logged.**
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
