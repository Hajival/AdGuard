# AdGuard-Home-Whitelist ✅

A strict curated whitelist for [AdGuard Home](https://adguard.com/en/adguard-home/overview.html) with a focus on enforcing privacy and security.

It also helps avoid ads, trackers and malware, and blocks tracking and telemetry whenever possible, by default.

__It's a great starting point for people who wish to run AdGuard Home in a strict whitelisting manner.__

ℹ Please learn [AdGuard Home's interface](https://github.com/AdguardTeam/AdGuardHome/wiki) before using this list.

_AdGuard-Home-Whitelist © 2021 - hl2guide_

## Aspects ⏺

### What's Whitelisted ✔

* 🏢 Microsoft products (Windows 10)
* 💻 Ubuntu (OS)
* 📔 Development languages (Python, C# etc)
* ✍ Programming Editors (Visual Studio Code and VSCodium)
* 🔑 Password Managers (LastPass and Bitwarden)
* 📓 Note Managers (Standard Notes and Evernote)
* 🎮 PC Game Launchers (Steam, Epic Games and EA Desktop)
* 🦠 Second-Opinion Malware Scanners (Malwarebytes, SuperAntispyware, ESET Online Scanner, HitManPro etc)
* 🏬 Australian specific stores (JB Hifi, OfficeWorks etc)
* 🏦 Australian government websites (election, tax office etc)
* and more.. [see whitelist as RAW](https://raw.githubusercontent.com/hl2guide/AdGuard-Home-Whitelist/main/whitelist.txt)

### What's __Not__ Whitelisted 🛑

* 🍏 Apple products or services
* 💭 Social media sites
* 🛒 Majority of online shopping sites

🖊 Take the above into account and that fact I live in Australia. The whitelist reflects those facts.

👀 Check the whitelist first to see if it suits your needs.

### Details

* __Expected AdGuard Home Average RAM Usage:__ around 16MB
* __Number of Rules:__ over 2400

See [USAGE.md](https://github.com/hl2guide/AdGuard-Home-Whitelist/blob/main/USAGE.md) for more information.

## Updates 👩‍💻

I will update this repo infrequently and sporadically.

## Usage 🗃

Within AdGuard Home:

1. Add one 🛑 [blocklist](https://raw.githubusercontent.com/hl2guide/AdGuard-Home-Whitelist/main/base.txt).
2. Add one ✅ [whitelist](https://raw.githubusercontent.com/hl2guide/AdGuard-Home-Whitelist/main/whitelist.txt).
3. Disable or remove all other lists you have added.

(Optional but recommended)

* copy and paste [disallowed domains](https://raw.githubusercontent.com/hl2guide/AdGuard-Home-Whitelist/main/dns_disallowed_domains.txt)
into AdGuard's "Disallowed domains" section at the bottom of "DNS settings"
* Click the "Save" button to keep a much clearer query log
