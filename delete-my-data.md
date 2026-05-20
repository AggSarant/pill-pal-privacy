---
title: How to delete your data — Pill Pal
description: Step-by-step instructions for deleting your data from the Pill Pal Android app.
layout: default
---

# How to delete your data from Pill Pal

**Last updated:** May 20, 2026
**App:** Pill Pal (com.aggsarant.pillpal)
**Developer:** Aggelos Sarantopoulos · aggelos.sarantopoulos@gmail.com

Pill Pal stores all of your personal data **on your own device**. Nothing is sent to our servers. You can erase it at any time, two ways:

---

## Option A — In-app (recommended, instant)

1. Open the **Pill Pal** app.
2. Tap the **⚙️ Settings** gear icon in the top-right of the home screen.
3. Scroll to the bottom of the Settings panel.
4. Tap **🗑️ Delete all my data**.
5. Confirm twice when asked.

The app immediately:
- Erases all your pills, schedules, days, and times
- Erases your completion history and streak
- Erases your name (if you entered one)
- Erases all family contacts (names and phone numbers)
- Erases your language preference
- Cancels all pending notification alarms
- Resets your AdMob consent choice

The app then reloads, fresh as if you'd just installed it.

---

## Option B — Uninstall the app

If you cannot open the app or prefer the OS-level method:

1. Open Android **Settings → Apps → Pill Pal**.
2. Tap **Storage → Clear data** to wipe everything, OR
3. Tap **Uninstall** to remove the app entirely.

This erases all on-device data Pill Pal has stored.

---

## What gets deleted

Both methods erase the **entire local dataset**:

| Data | Where stored | Deleted by Option A | Deleted by Option B |
|---|---|---|---|
| Pill names, schedules, days, times | localStorage on device | ✅ immediately | ✅ on uninstall |
| Completion history / streak | localStorage on device | ✅ immediately | ✅ on uninstall |
| Your name (if entered) | localStorage on device | ✅ immediately | ✅ on uninstall |
| Family contacts (name, phone) | localStorage on device | ✅ immediately | ✅ on uninstall |
| Language preference | localStorage on device | ✅ immediately | ✅ on uninstall |
| Pending notification alarms | Android AlarmManager | ✅ immediately | ✅ on uninstall |
| Privacy / ad-consent state | localStorage + AdMob SDK | ✅ immediately | ✅ on uninstall |

## What we don't store

Pill Pal does **not** operate any server. We never receive, store, or have access to:
- Your pill list, names, schedules, contacts, or any personal info
- Your device location
- Your contact list (we use Android's native contact picker, which returns only the single contact you explicitly choose)
- Any health information

So there is no "server-side" data to delete — there's nothing to ask us to delete.

## Third-party data (Google AdMob)

Pill Pal displays ads via **Google AdMob**. Google may retain advertising-related data (Advertising ID, approximate device info, ad-interaction events) according to [Google's Privacy Policy](https://policies.google.com/privacy) — typically up to 14 months.

To delete or restrict that:

- **Reset your Advertising ID:** Android **Settings → Privacy → Ads → Delete advertising ID**.
- **Opt out of personalized ads:** in the Pill Pal app, **⚙️ Settings → 🔒 Manage privacy choices**.
- **Manage ad-related data with Google:** https://myadcenter.google.com/

---

## Questions?

Email **aggelos.sarantopoulos@gmail.com** — we respond within 30 days.

---

[← Back to Privacy Policy](./)
