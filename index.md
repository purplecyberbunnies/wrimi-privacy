# WriMi Privacy Policy

**Effective date:** June 26, 2026  
**Last updated:** June 26, 2026

**Developer:** Purple Cyber Bunnies  
**App:** WriMi (Android)  
**Package:** `com.purplecyberbunnies.wrimi`  
**Contact:** [purplecyberbunnies@gmail.com](mailto:purplecyberbunnies@gmail.com)

This policy describes how WriMi handles information when you use the Android app. WriMi is a **local-first** writing tracker: your projects, word counts, goals, world-building notes, and backups are stored **on your device**, not on our servers.

We do **not** operate user accounts, cloud sync, advertising, or third-party analytics SDKs in the app today.

---

## Summary

| Topic | WriMi’s approach |
|-------|------------------|
| **Your writing data** | Stored locally in an on-device database |
| **Our servers** | We do not collect or store your writing content on our servers |
| **Accounts** | No sign-up required to use the app |
| **Ads** | None |
| **Analytics SDKs** | None (no Firebase Analytics, no ad networks) |
| **Backups & exports** | Created and saved **by you** (share sheet, Storage Access Framework, or folders you choose) |
| **Pro purchases** | Handled by **Google Play**; we receive purchase/entitlement status from Google, not your payment card details |
| **Support email** | Only if **you** choose to contact us |

---

## Information stored on your device

WriMi stores the data you enter so the app can work offline. This may include:

- **Projects:** titles, status, phases, deadlines, notes, and settings
- **Writing sessions / word entries:** word counts, dates, times, session duration, and related notes
- **Goals:** targets, progress, completion state, and goal metadata
- **World-building (Pro):** characters, locations, references (URLs and imported files), links, thumbnails, and media you attach
- **Plot structure (Pro):** plotlines, beats, summaries, notes, and links to world entities
- **Knowledge Base (Pro):** templates, entries, custom fields, and links
- **App preferences:** theme, language, compact mode, analytics/streak toggles, notification settings, auto-backup folder choice, and similar settings
- **Diagnostic logs (optional):** if you enable developer/diagnostic logging, technical log files may be written locally to help troubleshoot issues

This data stays on your phone or tablet unless **you** export, back up, or share it.

---

## Information we do not collect on our servers

We do **not** operate backend infrastructure that receives your manuscripts, world notes, backups, or analytics.

There is **no** WriMi cloud account and **no** automatic upload of your writing library to us.

---

## When the app uses the network

WriMi is mostly offline. Limited network use includes:

### URL reference previews (optional)

If you add a **URL reference** in World-building, the app may fetch the **first portion** of that webpage (up to about 16 KB) to read an Open Graph (`og:image`) preview image. The request goes to the **URL you entered**. We do not send your writing content in that request.

### Google Play (Pro subscriptions)

When you buy or restore **WriMi Pro**, billing is processed by **Google Play**. Google provides us with information needed to unlock Pro features (for example, that a subscription or lifetime purchase is active). We do **not** receive or store your full payment card number.

### Support email (your choice)

If you tap **Email support** (or otherwise email us), you choose what to include in the message. We will only use that correspondence to respond to you.

---

## Backups, exports, and sharing (user-controlled)

You can create and move copies of your data using features such as:

- ZIP backup and restore
- Auto-backup to a folder you pick (Storage Access Framework)
- CSV, Excel, Markdown, Project Bible, and project portability exports
- Android **Share** sheet when saving or sending files

**You** decide where files go (Downloads, Drive, email, another app, etc.). WriMi does not receive those files unless you separately send them to us (for example, by emailing a debug log for support).

Deleting the app from your device removes local app data unless you have kept separate backup copies elsewhere.

---

## Writing Wrapped (planned feature)

**Writing Wrapped** is a **planned** feature (not yet available in the current app version). It will let you generate a **“your writing period in review”** recap—similar in spirit to year-in-review features in music apps, but available **any time** you choose.

When shipped, Writing Wrapped is expected to work like this:

### What it uses

Wrapped will read **aggregated statistics already on your device**, such as:

- Word counts and writing session totals for a date range you pick
- Writing streaks and consistency metrics
- Time-of-day patterns (for example, “morning writer” vs “night writer” insights)
- Scope you select: all projects or one project; week, month, consecutive months, or year

It will **not** upload your raw manuscript text or full database to our servers—we do not operate servers for this feature.

### What you can share

Wrapped will produce **shareable outputs on your device** (for example, image cards and/or PDF). You choose whether to generate them and **where to send them** using the Android share sheet (social apps, messaging, email, save to gallery, etc.).

**Only the destinations you pick** receive what you share. We do not receive your Wrapped images or PDFs unless you independently send them to us.

### Your control

- Wrapped generation will be **initiated by you**, not automatic public posting.
- You will choose the **date range** and **project scope** before a recap is created.
- Shared cards may include **statistics and project titles** visible in the design you export—review before sharing if you want to keep project names private.

We will update this policy if the shipped feature differs materially from the above.

---

## Permissions

WriMi may request Android permissions to support features you use:

| Permission | Why |
|------------|-----|
| **Notifications** | Focused writing session / Pomodoro alerts and optional reminders |
| **Storage / files (SAF)** | Backups, auto-backup, imports, exports, and reference media you choose |
| **Internet** | URL preview fetch for references you add; Google Play billing |
| **Wake lock / foreground service** | Reliable focused-session timer while the app is backgrounded |

You can deny or revoke permissions in system settings; related features may stop working until permission is granted again.

---

## Diagnostic and developer tools

WriMi can write **local diagnostic logs** to help trace errors (for example, failed exports). These logs stay on your device unless you **export or email** them. Logs are intended for troubleshooting, not for advertising or profiling.

A hidden **Help & diagnostics** menu (unlocked from About) may include optional developer toggles. This is not required for normal use.

---

## Android system backup

The app may participate in **Android’s optional cloud backup / device transfer** mechanisms if enabled on your device and by your OEM. That process is controlled by **Google/your device manufacturer**, not by WriMi’s own servers. If you prefer not to rely on system backup, use WriMi’s explicit backup/export features to copies you control.

---

## Children’s privacy

WriMi is a writing tool for general audiences and is **not directed at children under 13** (or the applicable age in your country). We do not knowingly collect personal information from children. If you believe a child has contacted us with personal data, email us and we will delete that correspondence.

---

## Data retention and deletion

- **On device:** Data remains until you delete it in the app, clear app storage, or uninstall WriMi.
- **Backups you created:** Remain wherever you saved them until you delete those files.
- **Support emails:** Kept only as long as needed to handle your request, unless law requires longer retention.

---

## Legal bases (EEA/UK users)

Where GDPR applies, we process support correspondence based on **legitimate interest** (responding to you) or **consent** (when you contact us). Purchase verification is necessary to perform the **contract** for Pro features you buy through Google Play. We do not sell your personal information.

---

## Changes to this policy

We may update this policy when the app changes (for example, when **Writing Wrapped** ships or if billing features change). We will post the new version with an updated **Last updated** date. Continued use of the app after changes means you accept the revised policy.

Material changes may also be noted in release notes or the Play Store listing where appropriate.

---

## Contact

Questions about this policy or your data:

**Email:** [purplecyberbunnies@gmail.com](mailto:purplecyberbunnies@gmail.com)  
**Developer name (Google Play):** Purple Cyber Bunnies
