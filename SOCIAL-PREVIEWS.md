# 🔄 Social previews: refresh guide + share-image ledger

When a link to one of Psanctuary Church's GitHub Pages sites is pasted into a chat app, the app shows a
preview card (title, description and a share image) that it fetched **once** and then **cached**.
After a share image or title changes, old previews keep showing until each app is told to look again.
This file lists how to do that for each app, and which pages have their own tailored share image.

*Generated 2026-10-23 by the arrival kit's `social/social-previews.mjs` (canonical copy in
[my-template](https://github.com/drasticstatic/my-template/tree/main/changelog-template/arrival/social)).
Re-run it after deploys that add pages or change share images.*

## 🧰 How to refresh each app

| App | How to make it re-fetch | Notes |
|---|---|---|
| ✈️ **Telegram** | Message [@WebpageBot](https://t.me/WebpageBot) the link (you can send several links, one per line) | The bot replies with the fresh preview; new shares use it right away |
| 💼 **LinkedIn** | Paste the link into [Post Inspector](https://www.linkedin.com/post-inspector/) | Inspecting re-scrapes the page |
| 📘 **Facebook / Messenger** | Paste into the [Sharing Debugger](https://developers.facebook.com/tools/debug/) and press **Scrape Again** | Also accepts a batch of links |
| 💬 **Discord** | No refresh tool. Share the link with a harmless suffix such as `?v=2` | Discord caches per exact URL, so a new suffix gets a new preview |
| 🟪 **Slack** | No refresh tool. Use the `?v=2` suffix trick | Old messages keep their old unfurl |
| 🐦 **X (Twitter)** | No public validator any more. Use the `?v=2` suffix, or wait (cards refresh on their own, roughly a week) | |
| 🟢 **WhatsApp** | No refresh tool. Use the `?v=2` suffix | WhatsApp caches aggressively |
| 🦋 **Bluesky** / 🐘 **Mastodon** | Fetched when a post is written; nothing to clear | Each Mastodon server fetches its own copy |
| 💬 **iMessage** | Fetched on the sender's phone at send time | Nothing to clear |

**Rule of thumb:** after changing a share image, refresh Telegram (@WebpageBot), LinkedIn and
Facebook for the pages listed below. Use the `?v=2` suffix anywhere else.

## 🖼️ Share-image ledger

17 pages checked: **14 tailored**, 3 using the default card,
0 with no share image.

### ✨ Pages with their own tailored share image

| Page | Title | Share image |
|---|---|---|
| [psanctuarychurch.github.io/donate/](https://psanctuarychurch.github.io/donate/) | Donate — Psanctuary Church on GitHub | [image](https://psanctuarychurch.github.io/changelog-astro-public/og/page/donate.jpg) |
| [psanctuarychurch.github.io/pledge/](https://psanctuarychurch.github.io/pledge/) | A pledge of support — Psanctuary Church on GitHub | [image](https://psanctuarychurch.github.io/changelog-astro-public/og/page/pledge.jpg) |
| [psanctuarychurch.github.io/map/](https://psanctuarychurch.github.io/map/) | Map — Psanctuary Church on GitHub | [image](https://psanctuarychurch.github.io/changelog-astro-public/og/page/map.jpg) |
| [psanctuarychurch.github.io/changelog-astro-public/changelog](https://psanctuarychurch.github.io/changelog-astro-public/changelog) | Changelog — Psanctuary Church | [image](https://psanctuarychurch.github.io/changelog-astro-public/og/page/changelog.jpg) |
| [psanctuarychurch.github.io/changelog-astro-public/library](https://psanctuarychurch.github.io/changelog-astro-public/library) | Library — Psanctuary Church | [image](https://psanctuarychurch.github.io/changelog-astro-public/og/page/library.jpg) |
| [psanctuarychurch.github.io/changelog-astro-public/ledger](https://psanctuarychurch.github.io/changelog-astro-public/ledger) | Ledger — Psanctuary Church AstroLog | [image](https://psanctuarychurch.github.io/changelog-astro-public/og/ledger.jpg) |
| [psanctuarychurch.github.io/changelog-astro-public/changelog/github/2026-10-22-a-pledge-receipts-and-one-door](https://psanctuarychurch.github.io/changelog-astro-public/changelog/github/2026-10-22-a-pledge-receipts-and-one-door) | A pledge of support, receipts and taxes in the church's own words, and one door to the member network — Psanctuary Church Changelog | [image](https://psanctuarychurch.github.io/changelog-astro-public/og/changelog/github/2026-10-22-a-pledge-receipts-and-one-door.jpg) |
| [psanctuarychurch.github.io/changelog-astro-public/changelog/github/2026-10-13-a-navbar-a-map-and-one-window-for-every-way-in](https://psanctuarychurch.github.io/changelog-astro-public/changelog/github/2026-10-13-a-navbar-a-map-and-one-window-for-every-way-in) | A navbar on every page, a map with pictures, and one window for every way in — Psanctuary Church Changelog | [image](https://psanctuarychurch.github.io/changelog-astro-public/og/changelog/github/2026-10-13-a-navbar-a-map-and-one-window-for-every-way-in.jpg) |
| [psanctuarychurch.github.io/changelog-astro-public/changelog/github/2026-10-12-choose-how-you-arrive](https://psanctuarychurch.github.io/changelog-astro-public/changelog/github/2026-10-12-choose-how-you-arrive) | Choose how you arrive: a welcome, / to search, and faces on every change — Psanctuary Church Changelog | [image](https://psanctuarychurch.github.io/changelog-astro-public/og/changelog/github/2026-10-12-choose-how-you-arrive.jpg) |
| [psanctuarychurch.github.io/changelog-astro-public/changelog/github/2026-10-12-every-entry-shares-with-its-own-card](https://psanctuarychurch.github.io/changelog-astro-public/changelog/github/2026-10-12-every-entry-shares-with-its-own-card) | Share one entry, and it arrives with its own spore print — Psanctuary Church Changelog | [image](https://psanctuarychurch.github.io/changelog-astro-public/og/changelog/github/2026-10-12-every-entry-shares-with-its-own-card.jpg) |
| [psanctuarychurch.github.io/changelog-astro-public/changelog/github/2026-10-12-reading-mode-and-whats-new](https://psanctuarychurch.github.io/changelog-astro-public/changelog/github/2026-10-12-reading-mode-and-whats-new) | Reading mode, and what's new since your last visit — Psanctuary Church Changelog | [image](https://psanctuarychurch.github.io/changelog-astro-public/og/changelog/github/2026-10-12-reading-mode-and-whats-new.jpg) |
| [psanctuarychurch.github.io/changelog-astro-public/changelog/github/2026-10-12-the-ledger-every-public-change](https://psanctuarychurch.github.io/changelog-astro-public/changelog/github/2026-10-12-the-ledger-every-public-change) | The ledger: every public change, in plain words — Psanctuary Church Changelog | [image](https://psanctuarychurch.github.io/changelog-astro-public/og/changelog/github/2026-10-12-the-ledger-every-public-change.jpg) |
| [psanctuarychurch.github.io/changelog-astro-public/changelog/github/2026-10-11-the-foundation-is-laid](https://psanctuarychurch.github.io/changelog-astro-public/changelog/github/2026-10-11-the-foundation-is-laid) | The foundation is laid: Psanctuary Church gets a home on GitHub — Psanctuary Church Changelog | [image](https://psanctuarychurch.github.io/changelog-astro-public/og/changelog/github/2026-10-11-the-foundation-is-laid.jpg) |
| [psanctuarychurch.github.io/changelog-astro-public/library/how-this-changelog-stays-public-safe](https://psanctuarychurch.github.io/changelog-astro-public/library/how-this-changelog-stays-public-safe) | How this changelog stays public-safe — Psanctuary Church Library | [image](https://psanctuarychurch.github.io/changelog-astro-public/og/library/how-this-changelog-stays-public-safe.jpg) |

### 🪪 Pages using the default card

- [psanctuarychurch.github.io/](https://psanctuarychurch.github.io/)
- [psanctuarychurch.github.io/changelog-astro-public/](https://psanctuarychurch.github.io/changelog-astro-public/)
- [psanctuarychurch.github.io/changelog-astro-public/changelog/github](https://psanctuarychurch.github.io/changelog-astro-public/changelog/github)

## 📋 Copy-paste list for @WebpageBot

```
https://psanctuarychurch.github.io/
https://psanctuarychurch.github.io/donate/
https://psanctuarychurch.github.io/pledge/
https://psanctuarychurch.github.io/map/
https://psanctuarychurch.github.io/changelog-astro-public/
https://psanctuarychurch.github.io/changelog-astro-public/changelog
https://psanctuarychurch.github.io/changelog-astro-public/library
https://psanctuarychurch.github.io/changelog-astro-public/ledger
https://psanctuarychurch.github.io/changelog-astro-public/changelog/github
https://psanctuarychurch.github.io/changelog-astro-public/changelog/github/2026-10-22-a-pledge-receipts-and-one-door
https://psanctuarychurch.github.io/changelog-astro-public/changelog/github/2026-10-13-a-navbar-a-map-and-one-window-for-every-way-in
https://psanctuarychurch.github.io/changelog-astro-public/changelog/github/2026-10-12-choose-how-you-arrive
https://psanctuarychurch.github.io/changelog-astro-public/changelog/github/2026-10-12-every-entry-shares-with-its-own-card
https://psanctuarychurch.github.io/changelog-astro-public/changelog/github/2026-10-12-reading-mode-and-whats-new
https://psanctuarychurch.github.io/changelog-astro-public/changelog/github/2026-10-12-the-ledger-every-public-change
https://psanctuarychurch.github.io/changelog-astro-public/changelog/github/2026-10-11-the-foundation-is-laid
https://psanctuarychurch.github.io/changelog-astro-public/library/how-this-changelog-stays-public-safe
```
