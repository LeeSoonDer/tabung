# Tabung

A monthly budget for one salary at a time. Built for iPhone, works offline, and keeps every number on the phone.

**Open:** https://leesoonder.github.io/tabung/

## Install on iPhone
1. Open the link above in Safari.
2. Tap Share, then **Add to Home Screen**.
3. Always open Tabung from the Home Screen icon. Safari and the Home Screen app keep separate data.

## Your data
- Everything is stored on your phone only. This repository holds the app code, never your entries.
- Deleting the Home Screen icon deletes the data. Use **Settings → Export backup** after each month close and keep the file in Files or iCloud Drive.
- Moving to a new phone: export on the old one, then **Import backup** on the new one.

## How a month works
A month runs from one salary to the next and is named after the month it pays for. Salary on 21 Oct starts "November", planned to the day before your latest payday (24 Nov). Tap **Salary in** when it arrives: the old month closes, you split what is left between investing and savings, and the new one starts from that day.

## Files
`index.html` picks the language, `en.html` and `zh.html` are the app (same data), `sw.js` keeps it working offline and offers updates, `manifest.webmanifest` and `icons/` make it a Home Screen app.
