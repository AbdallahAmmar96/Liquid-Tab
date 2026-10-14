# Privacy Policy — Liquid Tab

_Last updated: October 9, 2026_

Liquid Tab replaces Chrome's New Tab page with an iOS 27–style home screen. It was designed to work without accounts, analytics or servers of our own.

## What stays on your device

Everything you create or configure is stored **only in your browser** (`chrome.storage.local` and IndexedDB):

- Settings, Home Screen layout, shortcuts, folders and widgets
- Notes, reminders, calendar events, alarms, world clocks and timers
- Wallpapers and photos you add
- Music you add to the Music app (the song files, cover art, lyrics, playlists and play counts)
- Screen Time totals (time per website per day, kept for 8 days) — only if you turn Screen Time on
- Workspaces, automations, calendar subscriptions and the pages you ask to watch

We don't collect, sell, transfer or share any of this. There is no analytics or tracking code in the extension.

## Network requests

The extension only contacts these services, and only for the purpose described:

| Service | When | What is sent |
| --- | --- | --- |
| **Open-Meteo** (`api.open-meteo.com`, `geocoding-api.open-meteo.com`) | To show weather | The coordinates or city name of your chosen weather location |
| **BigDataCloud** (`api.bigdatacloud.net`) | Only if you press **Use Precise Location** | Your coordinates, to look up the city name |
| **Google favicon service** (`www.google.com/s2/favicons`) | For shortcuts Chrome has no cached icon for (can be turned off in Settings → Home Screen) | The website address of that shortcut |
| **Bing** (`www.bing.com`) | Only if you choose **Daily Photo** as your wallpaper | A request for today's photo |
| Your search engine / AI assistant | Only when you press Enter in Search or Ask | The text you typed |
| Pages you choose to watch (Page Change Alerts) | Only for pages you add, at the interval you pick | A normal request for that page, without cookies |
| Calendar addresses you subscribe to | Every few hours, only for calendars you add | A request for that .ics file |
| Google speech recognition (built into Chrome) | Only while you use the microphone button to dictate | Your voice, processed by Chrome's speech service |

**On-device AI.** Answers, Writing Tools and translation use Chrome's built-in model (Gemini Nano), which runs on your computer. Your text is not sent anywhere by these features.

**Sync (optional, off by default).** If you turn on Sync, your settings, Home Screen, notes, reminders, events, workspaces and automations are copied to `chrome.storage.sync`, Chrome's own sync storage tied to your Google account. Photos never sync. We operate no server and cannot read this data.

## Permissions

| Permission | Why |
| --- | --- |
| `storage`, `unlimitedStorage` | Save your settings, notes, photos and music locally |
| `topSites` | Suggest your most-visited sites as Home Screen shortcuts |
| `favicon` | Show website icons from Chrome's local favicon cache |
| `search` | Search with your browser's default search engine |
| `alarms`, `notifications` | Timers, Focus sessions and alarms that notify you even when no new tab is open |
| `offscreen` | Keep your music, ambient sounds and timer chimes playing while you browse |
| `sidePanel` | Show Notes, Reminders, Timer, Calculator and Music in Chrome's side panel |
| `tabGroups` | Open a saved Workspace as a named tab group |
| `idle` | Pause Screen Time and break reminders while you're away from the computer |
| `bookmarks`, `history` (optional) | Only requested if you turn on bookmark/history results in Search; searched locally |
| `tabs`, `sessions` (optional) | Only requested if you turn on open tabs in the App Switcher/Search, Recently Closed tabs, Focus site blocking, Screen Time or saving Workspaces. Used locally; never transmitted |
| `downloads`, `downloads.open` (optional) | Only requested if you turn on the Downloads stack in the Dock; lists and opens your downloads |
| `https://www.bing.com/*` (optional) | Only requested if you choose the Daily Photo wallpaper |
| Access to a specific website (optional) | Only requested for a page you choose to watch or a calendar address you subscribe to — one site at a time |

## Your control

- **Export / Import** your data in Settings → Privacy & Data.
- **Reset All Settings** erases everything the extension stored.
- Uninstalling the extension removes all of its data from your browser.

## Contact

Questions about this policy: [aminking140@gmail.com](mailto:aminking140@gmail.com)

Liquid Tab is an independent project and is not affiliated with Apple Inc. iOS is a trademark of Apple Inc.
