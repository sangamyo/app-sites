# app-sites

Static home, privacy policy, terms of use and data/account deletion pages for several small Android apps,
served by GitHub Pages at **https://sangamyo.github.io/app-sites/**. Plain HTML and one stylesheet per app.
No build step, no external scripts, fonts or trackers.

Questions or requests about any of the apps: [open an issue](https://github.com/sangamyo/app-sites/issues)
and say which app it is about. Issues are public, so please do not post personal details (email
addresses, phone numbers, your records).

## Apps

| App | Folder | Home | Privacy policy | Deletion page | Google Play |
|---|---|---|---|---|---|
| Duo Budget | `duo-budget/` | [home](https://sangamyo.github.io/app-sites/duo-budget/) | [privacy](https://sangamyo.github.io/app-sites/duo-budget/privacy.html) | [delete account](https://sangamyo.github.io/app-sites/duo-budget/delete-account.html) | [com.hariomkasaundhan.duobudget](https://play.google.com/store/apps/details?id=com.hariomkasaundhan.duobudget) |
| Veilwise | `veilwise/` | [home](https://sangamyo.github.io/app-sites/veilwise/) | [privacy](https://sangamyo.github.io/app-sites/veilwise/privacy.html) | [delete account](https://sangamyo.github.io/app-sites/veilwise/delete-account.html) | [com.hariomkasaundhan.vowbudget](https://play.google.com/store/apps/details?id=com.hariomkasaundhan.vowbudget) |
| Swaddle Sync | `swaddle-sync/` | [home](https://sangamyo.github.io/app-sites/swaddle-sync/) | [privacy](https://sangamyo.github.io/app-sites/swaddle-sync/privacy.html) | [delete account](https://sangamyo.github.io/app-sites/swaddle-sync/delete-account.html) | [com.hariomkasaundhan.tandembaby](https://play.google.com/store/apps/details?id=com.hariomkasaundhan.tandembaby) |
| Hearthpool | `hearthpool/` | [home](https://sangamyo.github.io/app-sites/hearthpool/) | [privacy](https://sangamyo.github.io/app-sites/hearthpool/privacy.html) | [delete account](https://sangamyo.github.io/app-sites/hearthpool/delete-account.html) | [com.hariomkasaundhan.kinledger](https://play.google.com/store/apps/details?id=com.hariomkasaundhan.kinledger) |
| RentSlip | `rentslip/` | [home](https://sangamyo.github.io/app-sites/rentslip/) | [privacy](https://sangamyo.github.io/app-sites/rentslip/privacy.html) | [delete data](https://sangamyo.github.io/app-sites/rentslip/delete-data.html) | [com.hariomkasaundhan.rentslip](https://play.google.com/store/apps/details?id=com.hariomkasaundhan.rentslip) |
| Pennyquill | `pennyquill/` | [home](https://sangamyo.github.io/app-sites/pennyquill/) | [privacy](https://sangamyo.github.io/app-sites/pennyquill/privacy.html) | [delete data](https://sangamyo.github.io/app-sites/pennyquill/delete-data.html) | [com.hariomkasaundhan.paidup](https://play.google.com/store/apps/details?id=com.hariomkasaundhan.paidup) |
| Keepr | `keepr/` | [home](https://sangamyo.github.io/app-sites/keepr/) | [privacy](https://sangamyo.github.io/app-sites/keepr/privacy.html) | [delete data](https://sangamyo.github.io/app-sites/keepr/delete-data.html) | [com.hariomkasaundhan.keepr](https://play.google.com/store/apps/details?id=com.hariomkasaundhan.keepr) |
| FeeDesk | `feedesk/` | [home](https://sangamyo.github.io/app-sites/feedesk/) | [privacy](https://sangamyo.github.io/app-sites/feedesk/privacy.html) | [delete data](https://sangamyo.github.io/app-sites/feedesk/delete-data.html) | [com.hariomkasaundhan.feedesk](https://play.google.com/store/apps/details?id=com.hariomkasaundhan.feedesk) |
| CareNotes | `carenotes/` | [home](https://sangamyo.github.io/app-sites/carenotes/) | [privacy](https://sangamyo.github.io/app-sites/carenotes/privacy.html) | [delete account](https://sangamyo.github.io/app-sites/carenotes/delete-account.html) | [com.hariomkasaundhan.carenotes](https://play.google.com/store/apps/details?id=com.hariomkasaundhan.carenotes) |

Each folder also has `terms.html` (terms of use). Google Play links work once each app is live.

Pailbook (daily milk record and milk bill) has its own site: https://sangamyo.github.io/pailbook-site/

## Publishing

1. Push this folder's contents (the files, not the folder) to the root of the public repo `sangamyo/app-sites`.
2. Repo → **Settings → Pages** → Source: *Deploy from a branch* → branch `main`, folder `/ (root)` → Save.
3. After a minute the site is live at https://sangamyo.github.io/app-sites/.

The account-deletion pages of Duo Budget, Veilwise, Swaddle Sync, Hearthpool and CareNotes send a request
from the browser to that app's API, so each API's `CORS_ORIGINS` setting must include
`https://sangamyo.github.io` (origin only, no path).

## Source

These pages are copies. The source of each app's pages lives in that app's `site/` folder in the apps'
project; edit them there and copy them here again.
