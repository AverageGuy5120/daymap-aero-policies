# Privacy Policy for Daymap Aero

**Effective date:** 20 November 2026
**Applies to:** Daymap Aero browser extension, version 8.1.0 and later

Daymap Aero ("the extension") is a Chrome extension that redesigns the Daymap student portal and adds study tools to it. It is an independent project. It is not affiliated with, endorsed by or sponsored by Daymap.

This policy explains what information the extension handles, where that information is kept and what, if anything, leaves your device.

---

## The short version

- Daymap Aero works **inside your browser**. It reads the Daymap pages you open so it can redesign them.
- Your Daymap information (timetable, tasks, grades, messages and your name) is **kept on your device only**. It is **never sent** to the developer or anyone else.
- There are **no analytics, no tracking, no advertising and no crash reporting**.
- The only feature that uses the internet is **optional multiplayer** (party games, game chat and leaderboards). It connects only when you choose to use it, and it never sends your Daymap information.
- Nothing is sold, and nothing is used for advertising.

---

## 1. Information the extension reads from Daymap

When you open a page on a `*.daymap.net` website, the extension reads that page so it can restyle it and power its features. Depending on the page, this can include:

- **Your name** as shown by Daymap, used to greet you on the Today dashboard
- **Your timetable and diary** (lessons, times, rooms, teachers)
- **Tasks and homework** (titles, subjects, due dates)
- **Message previews** (sender, subject and how many are unread), shown on the dashboard
- **Attendance and grade summaries** that Daymap already shows you

This information is processed **locally in your browser**. The extension does not read any website other than Daymap.

## 2. Information stored on your device

The extension stores the following in your browser's extension storage (`chrome.storage.local` and the extension's IndexedDB):

- Your settings, themes, profiles, layouts, keyboard shortcuts and installed mods
- Things you create in the extension: notes, to-dos, countdowns, flashcards, study plans, focus-timer history, game scores, progress and badges
- A copy of your upcoming lessons and tasks, so the dashboard, study planner, lesson reminders and toolbar badge keep working
- The address of your school's Daymap site and the last Daymap tab, so "Open Daymap" and notification clicks can take you back
- **Automatic backups** of the above: the last 7 daily backups plus restore points made before updates, imports, restores and resets

This data **stays on your device**. The developer cannot see it.

**Your control:** in the extension's Options page you can export, import, restore or delete your data and backups, or erase everything with "Reset everything". Uninstalling the extension deletes all of its stored data.

## 3. Notifications and reminders

If you turn on desktop notifications, the extension creates lesson reminders, "tasks due tomorrow" reminders and focus-timer alerts **on your device**, using the copy of your timetable described above. No server is involved. Notifications are off by default.

## 4. Optional multiplayer (the only online feature)

Multiplayer includes party games with friends, game and room chat, public chat rooms, and leaderboards (per-game scores and the overall "Gamer Score" ranking). It uses **Google Firebase** (Firebase Authentication and Firebase Realtime Database).

The extension connects to Firebase **only after you open Multiplayer or turn on score sharing**. When you use it, the following is sent:

| Information | Purpose |
|---|---|
| An anonymous account ID created by Firebase (no email, password or real name) | To tell players apart |
| The nickname and colour you choose | To show you to other players |
| Room codes and game moves | To run multiplayer games |
| Chat messages you type | To deliver them to other players in the same room |
| Best scores you choose to share, your Gamer Score, its title and how many games you have played | To show you on leaderboards |

**Never sent:** your Daymap information (name, timetable, tasks, grades, messages), your notes, to-dos or flashcards, or your browsing.

Things to know:

- Your nickname, scores and chat messages are **visible to other players** in the same room, chat room or leaderboard. Please don't use your real name as your nickname, and don't share personal information in chat.
- Chat is **not moderated**.
- Game rooms are deleted when the host leaves. Leaderboard entries remain until they are removed.
- Firebase is operated by Google, which receives standard technical information (such as your IP address) when you connect. Google's privacy policy applies: https://policies.google.com/privacy
- You can stop sharing scores at any time by turning off score sharing in Multiplayer, or by not using multiplayer at all.

## 5. What the extension does not do

- It does not collect analytics, usage statistics or crash reports.
- It does not track you across websites or record your browsing history.
- It does not log your keystrokes, clicks or mouse movements. (It listens for its own keyboard shortcuts but does not record them.)
- It does not read or store your Daymap password or login details.
- It does not show ads.
- It does not sell, rent or trade any information, and it does not use any information for advertising, profiling or credit decisions.
- It does not load or run code from the internet. All code is included in the extension. User-installed mods run in sandboxed frames that cannot access the network.

## 6. Children and students

Daymap Aero is designed for students, including students under 18. The developer does not collect personal information for itself. The only information that leaves the device is the optional multiplayer data described in section 4, under a nickname the user chooses.

If you are a parent, guardian or school and you would like multiplayer data associated with a student removed, contact the developer (see section 9). Schools may also wish to check that browser extensions are permitted on school devices, and may prefer students leave multiplayer chat unused.

## 7. Data deletion

- **Data on your device:** delete it any time with Options › Backups › "Reset everything", or by uninstalling the extension.
- **Multiplayer data:** rooms are removed when the host leaves. To have leaderboard entries or other multiplayer data removed, contact the developer with your nickname and the approximate date you played.

## 8. Changes to this policy

If this policy changes, the updated version will be posted at this address with a new effective date, and significant changes will be mentioned in the extension's "What's new" page.

## 9. Contact

Questions, requests or concerns about privacy:

**Email:** ifyouworry@proton.me

---

*Daymap Aero complies with the Chrome Web Store User Data Policy, including the Limited Use requirements. User data is used only to provide the extension's features described above, which are its single purpose.*
