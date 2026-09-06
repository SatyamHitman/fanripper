# Fanripper — OnlyFans, Fansly, JustForFans & privacy.com.br Downloader (Chrome Extension)

> **Back up everything you've already paid for.** Fanripper is a browser extension for **Chrome, Brave and Edge** that saves photos, videos, DM media and **DRM-protected / encrypted** clips from the **OnlyFans**, **Fansly**, **JustForFans** and **privacy.com.br** creators you subscribe to — whole profiles, direct messages and the Vault — decrypted and processed **entirely on your own device**. No password, no media uploaded.

![Version](https://img.shields.io/badge/version-0.1.56-FF5A5F)
![Browsers](https://img.shields.io/badge/Chrome%20·%20Brave%20·%20Edge-supported-2b2b2b)
![Platforms](https://img.shields.io/badge/OnlyFans%20·%20Fansly%20·%20JustForFans%20·%20privacy.com.br-supported-2b2b2b)
![VirusTotal](https://img.shields.io/badge/VirusTotal-0%2F65-3fb950)
![License](https://img.shields.io/badge/license-proprietary-lightgrey)

🌐 **[fanripper.com](https://fanripper.com)** &nbsp;·&nbsp; ⬇️ **[Install](https://install.fanripper.com)** &nbsp;·&nbsp; 📊 **[Compare all four sites](https://fanripper.com/supported-sites)** &nbsp;·&nbsp; 💬 **[Telegram](https://t.me/fanripper)**

---

## Supported sites

Support depth genuinely differs per site. Here is the honest picture, with the gaps stated — the full side-by-side lives at **[fanripper.com/supported-sites](https://fanripper.com/supported-sites)**.

### [OnlyFans downloader](https://fanripper.com/onlyfans-downloader)
DRM-protected video at the manifest's **highest** rendition — no resolution cap, HEVC included, and **no file-size limit** (multi-gigabyte files that stall other tools finish here, because media is streamed to disk instead of held in memory). Photos, DM media, stories and highlights. Whole-profile backup across **10 surfaces** including paid/PPV, DMs and your own Vault, with date, media-type and paid-only filters.
*Limits:* on protected video you always get the top rendition — you cannot deliberately pick a smaller one. You cannot download PPV you have not bought, and you cannot crawl another creator's Vault.

### [Fansly downloader](https://fanripper.com/fansly-downloader)
**Downloads are free.** Photos, video and DM media save on any signed-in account with no plan at all. Real per-rung quality picker (1080p / 720p / 480p, whatever the manifest carries). Whole-timeline backup on Pro.
*Limits:* a rare Fansly video is published only as an HLS stream and is not supported yet. No stories, no crawl filters, and Fansly is the one site with no crawl resume.

### [JustForFans downloader](https://fanripper.com/justforfans-downloader)
Encrypted (cbcs / ClearKey) video **decrypted locally, with no 720p cap** — the ceiling most rival tools hit because they assume heavyweight DRM. Photos as originals, whole-profile crawl, and a **whole-library crawl covering every creator you have ever purchased from**. Works on every regional xvid CDN.
*Limits:* encrypted video sent in a DM cannot be saved yet (DM photos and unencrypted clips work). No stories. Requires Max or Lifetime.

### [privacy.com.br downloader](https://fanripper.com/privacy-downloader)
HLS-AES-128 encrypted video decrypted locally at **the post's top rendition — there is no cap on Fanripper's side**; 1080p is simply the highest rung the site currently serves. Photos, download chips on posts **and chat**, whole-profile crawl, and all five collections: My Purchases, Favorites, Chat Purchases, Hidden and Tips.
*Limits:* no chat bulk crawl, no stories, no Vault. Requires Max or Lifetime.

## Why Fanripper?

Most downloaders are either **free but basic** (no DRM, no bulk, often pulled from the store) or **paid but limited** (manual scrolling, stall on big files, capped resolution).

- ✅ **Protected and encrypted video is the point, not a gap.** The case "paste a link" tools choke on.
- ✅ **Any size.** Multi-gigabyte DRM files complete because the file streams to disk.
- ✅ **No quality ceiling.** JustForFans is *not* capped at 720p here; OnlyFans takes the top rung including HEVC.
- ✅ **Whole-profile auto-crawl.** One click; no scrolling to "load more".
- ✅ **See a PPV's real length before you buy** — never pay for a 10-second clip sold as an hour.
- ✅ **Metadata baked into every file** — creator, caption, price and post date, searchable for years.
- ✅ **100% on your device.** No password, no media on our servers.

## How we compare

| Feature | **Fanripper** | Other paid extensions | Free downloaders |
|---|:---:|:---:|:---:|
| DRM / encrypted video, any size | ✅ no size limit | ⚠️ stalls on large files | ❌ |
| Whole-profile auto-crawl | ✅ posts · PPV · Vault | ❌ manual scroll only | ❌ timeline only |
| Posts · DMs · Vault | ✅ | ⚠️ partial | ❌ feed only |
| Sites covered | ✅ **4** | ⚠️ usually 1 | ❌ 1 |
| JustForFans at full quality | ✅ no 720p cap | ❌ 720p or none | ❌ |
| privacy.com.br | ✅ | ❌ | ❌ |
| See a PPV's true length first | ✅ | ❌ | ❌ |
| Metadata baked into files | ✅ | ❌ | ❌ |
| Runs 100% on your device | ✅ always | ⚠️ often "cloud" | ✅ usually |
| Never asks your password | ✅ | ⚠️ varies | ⚠️ varies |

## Install (about 60 seconds)

1. Download the latest **`fanripper.zip`** from [**Releases**](../../releases) (or [install.fanripper.com](https://install.fanripper.com)).
2. Unzip it somewhere permanent.
3. Open `chrome://extensions` and turn on **Developer mode** (top-right).
4. Click **Load unpacked** and select the unzipped folder.
5. Open OnlyFans, Fansly, JustForFans or privacy.com.br — a **save** button appears on content you can already see.

Works on **Chrome, Brave and Edge**.

**Updating:** a load-unpacked install cannot update itself, so Fanripper **tells you** when a new version ships. Download the new zip, extract it over the same folder, and click **Reload** on `chrome://extensions` — about 15 seconds, and your settings and login are kept.

> **Why not the Chrome Web Store?** Stores remove extensions that interact with subscription-content platforms, so Fanripper ships as a signed build you load once in developer mode. Every release is scanned — the current build is flagged by **0 of 65** engines on VirusTotal.

## Plans

Free to install, and **free for everyday backups** — unlimited photos and standard video from posts and DMs on OnlyFans, and *everything* on Fansly. No account, no card.

| Plan | Price | Adds |
|---|---|---|
| Free | — | Photos + standard video (OnlyFans, Fansly) |
| Basic | $5/mo | DRM-protected OnlyFans video, OnlyFans DM media |
| Pro | $8/mo | Whole-profile bulk backup + crawl filters |
| Unlimited | $40/6mo | Pro, prepaid |
| **Max** | $15/mo | **JustForFans + privacy.com.br**, every new site we add · 2 devices |
| **Lifetime** | $99 once | Every Max feature, permanently · 1 device |

Cloud backup + Telegram delivery is a separate **$4/month add-on** that works on any plan, including Free. Paid plans are bought inside the extension and billed in crypto — no card, no KYC.

## FAQ

See [**docs/FAQ.md**](docs/FAQ.md) for the full list.

- **Is it safe?** It runs entirely in your browser, never asks for your password, and stores no media on a server. The build is VirusTotal-scanned at 0/65.
- **Will it get my account banned?** It saves posts and messages you are already viewing, paced like ordinary browsing, on your own device. No tool that talks to a site it does not control can promise you an outcome, so we won't — but human-paced requests are why it behaves like a normal session.
- **Does it handle big videos?** Yes — multi-gigabyte DRM video that stalls other tools completes here.
- **Which sites?** OnlyFans and Fansly on any plan; **JustForFans and privacy.com.br** on Max or Lifetime.
- **Does it unlock content I haven't paid for?** No. It only saves what your account can already open. No paywall is bypassed.
- **Where do downloads go?** Your normal Downloads folder, named by a template you control.

## Links

- 🌐 Website — https://fanripper.com
- 📊 Supported sites — https://fanripper.com/supported-sites
- ⬇️ Install — https://install.fanripper.com
- 💬 Telegram (help + updates) — https://t.me/fanripper

## License

Proprietary — **licensed, not sold.** See [LICENSE](LICENSE).

## Disclaimer

Fanripper is a personal backup utility for content you have **lawful, paid access to**. It is **not affiliated with, endorsed by, or connected to** OnlyFans, Fansly, JustForFans, privacy.com.br, or any content platform. No paywall is bypassed. You are responsible for complying with each platform's terms of service and your local law.
