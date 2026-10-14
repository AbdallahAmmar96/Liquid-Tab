<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Liquid Tab Privacy Policy</title>
<meta name="description" content="Privacy policy for the Liquid Tab Chrome extension.">
<style>
  :root {
    --bg: #f5f5f7; --card: #ffffff; --text: #1d1d1f; --muted: #6e6e73;
    --line: #e5e5ea; --accent: #0071e3; --head: #fafafc;
  }
  @media (prefers-color-scheme: dark) {
    :root {
      --bg: #000000; --card: #1c1c1e; --text: #f5f5f7; --muted: #a1a1a6;
      --line: #38383a; --accent: #2997ff; --head: #2c2c2e;
    }
  }
  * { box-sizing: border-box; }
  body {
    margin: 0; background: var(--bg); color: var(--text);
    font: 16px/1.6 -apple-system, BlinkMacSystemFont, "Segoe UI", Inter, Roboto, sans-serif;
  }
  main { max-width: 820px; margin: 0 auto; padding: 48px 16px 64px; }
  .card { background: var(--card); border-radius: 18px; padding: 32px 28px; }
  h1 { font-size: 2rem; line-height: 1.2; margin: 0 0 4px; }
  h2 { font-size: 1.3rem; margin: 36px 0 10px; }
  .updated { color: var(--muted); margin: 0 0 24px; }
  a { color: var(--accent); }
  code { font: 0.9em ui-monospace, SFMono-Regular, Consolas, monospace; background: var(--head); padding: 1px 5px; border-radius: 5px; }
  ul { padding-left: 1.25em; }
  .table-wrap { overflow-x: auto; margin: 12px 0; border: 1px solid var(--line); border-radius: 12px; }
  table { border-collapse: collapse; width: 100%; font-size: 0.95rem; }
  th, td { text-align: left; vertical-align: top; padding: 10px 12px; border-bottom: 1px solid var(--line); }
  tr:last-child td { border-bottom: 0; }
  th { background: var(--head); font-weight: 600; }
  footer { color: var(--muted); font-size: 0.9rem; margin-top: 32px; }
  @media (max-width: 600px) { .card { padding: 24px 16px; } h1 { font-size: 1.6rem; } }
</style>
</head>
<body>
<main>
<div class="card">
<h1>Privacy Policy — Liquid Tab</h1>
<p class="updated">Last updated: October 9, 2026</p>

<p>Liquid Tab replaces Chrome's New Tab page with an iOS 27–style home screen. It was designed to work without accounts, analytics or servers of our own.</p>

<h2>What stays on your device</h2>
<p>Everything you create or configure is stored <strong>only in your browser</strong> (<code>chrome.storage.local</code> and IndexedDB):</p>
<ul>
  <li>Settings, Home Screen layout, shortcuts, folders and widgets</li>
  <li>Notes, reminders, calendar events, alarms, world clocks and timers</li>
  <li>Wallpapers and photos you add</li>
  <li>Music you add to the Music app (the song files, cover art, lyrics, playlists and play counts)</li>
  <li>Screen Time totals (time per website per day, kept for 8 days) — only if you turn Screen Time on</li>
  <li>Workspaces, automations, calendar subscriptions and the pages you ask to watch</li>
</ul>
<p>We don't collect, sell, transfer or share any of this. There is no analytics or tracking code in the extension.</p>

<h2>Network requests</h2>
<p>The extension only contacts these services, and only for the purpose described:</p>
<div class="table-wrap"><table>
  <tr><th>Service</th><th>When</th><th>What is sent</th></tr>
  <tr><td><strong>Open-Meteo</strong> (<code>api.open-meteo.com</code>, <code>geocoding-api.open-meteo.com</code>)</td><td>To show weather</td><td>The coordinates or city name of your chosen weather location</td></tr>
  <tr><td><strong>BigDataCloud</strong> (<code>api.bigdatacloud.net</code>)</td><td>Only if you press <strong>Use Precise Location</strong></td><td>Your coordinates, to look up the city name</td></tr>
  <tr><td><strong>Google favicon service</strong> (<code>www.google.com/s2/favicons</code>)</td><td>For shortcuts Chrome has no cached icon for (can be turned off in Settings → Home Screen)</td><td>The website address of that shortcut</td></tr>
  <tr><td><strong>Bing</strong> (<code>www.bing.com</code>)</td><td>Only if you choose <strong>Daily Photo</strong> as your wallpaper</td><td>A request for today's photo</td></tr>
  <tr><td>Your search engine / AI assistant</td><td>Only when you press Enter in Search or Ask</td><td>The text you typed</td></tr>
  <tr><td>Pages you choose to watch (Page Change Alerts)</td><td>Only for pages you add, at the interval you pick</td><td>A normal request for that page, without cookies</td></tr>
  <tr><td>Calendar addresses you subscribe to</td><td>Every few hours, only for calendars you add</td><td>A request for that .ics file</td></tr>
  <tr><td>Google speech recognition (built into Chrome)</td><td>Only while you use the microphone button to dictate</td><td>Your voice, processed by Chrome's speech service</td></tr>
</table></div>

<p><strong>On-device AI.</strong> Answers, Writing Tools and translation use Chrome's built-in model (Gemini Nano), which runs on your computer. Your text is not sent anywhere by these features.</p>
<p><strong>Sync (optional, off by default).</strong> If you turn on Sync, your settings, Home Screen, notes, reminders, events, workspaces and automations are copied to <code>chrome.storage.sync</code>, Chrome's own sync storage tied to your Google account. Photos never sync. We operate no server and cannot read this data.</p>

<h2>Permissions</h2>
<div class="table-wrap"><table>
  <tr><th>Permission</th><th>Why</th></tr>
  <tr><td><code>storage</code>, <code>unlimitedStorage</code></td><td>Save your settings, notes, photos and music locally</td></tr>
  <tr><td><code>topSites</code></td><td>Suggest your most-visited sites as Home Screen shortcuts</td></tr>
  <tr><td><code>favicon</code></td><td>Show website icons from Chrome's local favicon cache</td></tr>
  <tr><td><code>search</code></td><td>Search with your browser's default search engine</td></tr>
  <tr><td><code>alarms</code>, <code>notifications</code></td><td>Timers, Focus sessions and alarms that notify you even when no new tab is open</td></tr>
  <tr><td><code>offscreen</code></td><td>Keep your music, ambient sounds and timer chimes playing while you browse</td></tr>
  <tr><td><code>sidePanel</code></td><td>Show Notes, Reminders, Timer, Calculator and Music in Chrome's side panel</td></tr>
  <tr><td><code>tabGroups</code></td><td>Open a saved Workspace as a named tab group</td></tr>
  <tr><td><code>idle</code></td><td>Pause Screen Time and break reminders while you're away from the computer</td></tr>
  <tr><td><code>bookmarks</code>, <code>history</code> (optional)</td><td>Only requested if you turn on bookmark/history results in Search; searched locally</td></tr>
  <tr><td><code>tabs</code>, <code>sessions</code> (optional)</td><td>Only requested if you turn on open tabs in the App Switcher/Search, Recently Closed tabs, Focus site blocking, Screen Time or saving Workspaces. Used locally; never transmitted</td></tr>
  <tr><td><code>downloads</code>, <code>downloads.open</code> (optional)</td><td>Only requested if you turn on the Downloads stack in the Dock; lists and opens your downloads</td></tr>
  <tr><td><code>https://www.bing.com/*</code> (optional)</td><td>Only requested if you choose the Daily Photo wallpaper</td></tr>
  <tr><td>Access to a specific website (optional)</td><td>Only requested for a page you choose to watch or a calendar address you subscribe to — one site at a time</td></tr>
</table></div>

<h2>Your control</h2>
<ul>
  <li><strong>Export / Import</strong> your data in Settings → Privacy &amp; Data.</li>
  <li><strong>Reset All Settings</strong> erases everything the extension stored.</li>
  <li>Uninstalling the extension removes all of its data from your browser.</li>
</ul>

<h2>Contact</h2>
<p>Questions about this policy: <a href="mailto:aminking140@gmail.com">aminking140@gmail.com</a></p>

<footer>Liquid Tab is an independent project and is not affiliated with Apple Inc. iOS is a trademark of Apple Inc.</footer>
</div>
</main>
</body>
</html>
