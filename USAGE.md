# Notes 📒

The below information relates to what I personally use and recommend people consider using.

Please assess what is best for you.

# Usage for AdGuard Home 🛡

Check that you are using __AdGuard Home v0.106.3__ or later
(vital functionality was hot-fixed).

## DNS Settings within AdGuard 🥅

I personally use and recommend people consider using Quad9 (https://www.quad9.net/) as their DNS.

Quad9 tops the speed and reliability tests for my location; they offer Malware Blocking, support DNS-over-TLS and also DNSSEC.

They are also now "incorporated in Switzerland to guarantee privacy for global DNS users" (quad9).

* _(optional)_ To test it at your location run the tool: [GRC Domain Name Speed Benchmark for Windows/Linux](https://www.grc.com/dns/benchmark.htm)

### Upstream DNS servers 🔼

tls://dns.quad9.net

### Bootstrap DNS servers 🥾

9.9.9.9

### DNS server configuration ⚙

Check/tick the "Enable DNSSEC" checkbox and click the green __Save__ button.

## Lists 📓

Once you have __AdGuard Home__ ready and are logged in, use its main menu to add
one __blocklists__ and one __allowlist__ (below).

Type | Link (URL)
--------- | -----
📗 Allowlist | [blocklist](https://raw.githubusercontent.com/hl2guide/AdGuard-Home-Whitelist/main/base.txt)
🛑 Blocklist | [whitelist](https://raw.githubusercontent.com/hl2guide/AdGuard-Home-Whitelist/main/whitelist.txt)

## Filters Update Interval ⏱

You can modify how often filter lists are updated within AdGuard Home in the
__Settings__ > __General Settings__ page.

Set "Filters update interval" to 12 hours _(recommended)_ and click the green "Save" button.

## Blocked Services 🚨

It's useful to set blocked services within AdGuard Home.

1. Go to "filters" then "blocked services"
2. Click the "Block all" button and then toggle on the services you actually use or will use
3. Click the green "Save" button at the bottom of the page

# Browsers 🌏

A mix of Internet Browser Addons/Extensions can improve your security and privacy further.

These are best security and privacy focused internet browser extensions/addons in my opinion.

## Mozilla Firefox Users 🦊

Install using this [collection](https://addons.mozilla.org/en-US/firefox/collections/3899969/BestSecurityPrivacy/?page=1&collection_sort=name).

## Microsoft Edge, Brave, Vivaldi and Google Chrome Users 🌐

Visit the official [Google Chrome Webstore](https://chrome.google.com/webstore/category/extensions):

_Manually add:_

- [AdGuard AdBlocker](https://chrome.google.com/webstore/detail/adguard-adblocker/bgnkhhnnamicmpeenaelnjfhikgbkllg)
- [ClearURLs](https://chrome.google.com/webstore/detail/clearurls/lckanjgmijmafbedllaakclkaicjfmnk)
- [Decentraleyes](https://chrome.google.com/webstore/detail/decentraleyes/ldpochfccmkkmhdbclfhpagapcfdljkj)
- [DuckDuckGo Privacy Essentials](https://chrome.google.com/webstore/detail/duckduckgo-privacy-essent/bkdgflcldnnnapblkhphbgpggdiikppg)
- [Emsisoft Browser Security](https://chrome.google.com/webstore/detail/emsisoft-browser-security/jfofijpkapingknllefalncmbiienkab)
- [HTTPS Everywhere](https://chrome.google.com/webstore/detail/https-everywhere/gcbommkclmclpchllfjekcdonpmejbdp)
- [I don't care about cookies](https://chrome.google.com/webstore/detail/i-dont-care-about-cookies/fihnjjcciajhdojfnbdddfaoknhalnja)
- [Malwarebytes Browser Guard](https://chrome.google.com/webstore/detail/malwarebytes-browser-guar/ihcjicgdanjaechkgeegckofjjedodee)
- [Never-Consent](https://chrome.google.com/webstore/detail/never-consent/pgahndjfiejekcbidhejmpplgdhejdpb)
- [Privacy Badger](https://chrome.google.com/webstore/detail/privacy-badger/pkehgijcmpdhfbdbbnkijodmdjhbjlgp)
- [Privacy Pass](https://chrome.google.com/webstore/detail/privacy-pass/ajhmfdgkijocedmfjonnpjfojldioehi)
- [SponsorBlock - Skip Sponsorships on YouTube](https://chrome.google.com/webstore/detail/sponsorblock-for-youtube/mnjggcdmjocbbbhaepdhchncahnbgone)

# Software-Level Firewall 🔥

I personally also use [SimpleWall](https://www.henrypp.org/product/simplewall) to have a baseline protection on an application level.

# Windows 10 Antispy Tool 🕵️‍♀️

If you use Windows 10, please use [O&O ShutUp10](https://www.oo-software.com/en/shutup10) to disable spying features initially and then after each major update.
