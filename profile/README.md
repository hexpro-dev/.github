<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/hexpro-dev/.github/main/profile/assets/banner-dark.png">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/hexpro-dev/.github/main/profile/assets/banner-light.png">
  <img alt="Hex Pro: Software for People" src="https://raw.githubusercontent.com/hexpro-dev/.github/main/profile/assets/banner-light.png" width="100%">
</picture>

<p align="center">
  <a href="https://hex.pro"><img alt="hex.pro" src="https://img.shields.io/badge/hex.pro-the%20company-0B76D9?style=flat-square&labelColor=1b2530"></a>
  <a href="https://apps.hex.pro"><img alt="apps.hex.pro" src="https://img.shields.io/badge/apps.hex.pro-apps%20%26%20tools-0B76D9?style=flat-square&labelColor=1b2530"></a>
  <a href="https://citadel.hex.pro"><img alt="citadel.hex.pro" src="https://img.shields.io/badge/citadel.hex.pro-file%20sync-0B76D9?style=flat-square&labelColor=1b2530"></a>
  <a href="https://games.hex.pro"><img alt="Hex Games" src="https://img.shields.io/badge/Hex%20Games-the%20game%20studio-9F9F9F?style=flat-square&logo=github&logoColor=white&labelColor=1b2530"></a>
  <img alt="Australian owned and operated" src="https://img.shields.io/badge/Australian-owned%20%26%20operated-9F9F9F?style=flat-square&labelColor=1b2530">
</p>

---

**Hex Pro** is the software side of Ars Vitae Pty Ltd, an Australian company. We build small, sharp software for iPhone and desktop, browser tools that never send your files anywhere, and an open-source file sync platform. Games come from our sister studio, [Hex Games](https://games.hex.pro).

People over profits, applied to what we charge and to what we collect. In practice: no advertising networks, no analytics SDKs inside the apps, and a one-time purchase where there are no servers to pay for.

> [!NOTE]
> Most repositories in this organisation are private while the products they belong to are still being built, and nothing has shipped to a store yet. The tables below say exactly what state each thing is in. A status that quietly overstates itself is the same problem as a claim that does.

<br>

## What we are building

Five apps, two browser tools and one platform. The status column uses the same wording as [apps.hex.pro](https://apps.hex.pro), which is the page that has to stay honest.

### Apps

<table>
<tr><th width="52"></th><th align="left">Product</th><th align="left">What it does</th><th>Platform</th><th>Status</th></tr>
<tr>
  <td width="52" align="center"><img src="https://raw.githubusercontent.com/hexpro-dev/.github/main/profile/assets/icons/sol.png" width="36" alt=""></td>
  <td><b><a href="https://apps.hex.pro/sol">Sol</a></b></td>
  <td>The alarm clock you can't cheat. Six challenges, three layers of enforcement, and alarms owned by iOS itself through AlarmKit, so they survive Silent mode, Focus and a force-quit.</td>
  <td>iPhone<br>iPad</td>
  <td><code>Coming&nbsp;soon</code></td>
</tr>
<tr>
  <td width="52" align="center"><img src="https://raw.githubusercontent.com/hexpro-dev/.github/main/profile/assets/icons/hex-nfc.png" width="36" alt=""></td>
  <td><b><a href="https://apps.hex.pro/hex-nfc">Hex NFC</a></b></td>
  <td>A complete NFC reader, writer and tag editor. Eighteen record types, per-family tag protection, passport and transit reading, and a raw command console.</td>
  <td>iPhone</td>
  <td><code>Coming&nbsp;soon</code></td>
</tr>
<tr>
  <td width="52" align="center"><img src="https://raw.githubusercontent.com/hexpro-dev/.github/main/profile/assets/icons/kcalc-ai.png" width="36" alt=""></td>
  <td><b><a href="https://apps.hex.pro/kcalc.ai">kcalc.ai</a></b></td>
  <td>AI calorie tracking with LiDAR portion scanning, so the hard part (how much is actually on the plate) stops being a guess.</td>
  <td>iPhone</td>
  <td><code>Coming&nbsp;soon</code></td>
</tr>
<tr>
  <td width="52" align="center"><img src="https://raw.githubusercontent.com/hexpro-dev/.github/main/profile/assets/icons/infinilang.png" width="36" alt=""></td>
  <td><b><a href="https://apps.hex.pro/infinilang">Infinilang</a></b></td>
  <td>Japanese reading material generated from exactly the kanji you already know, plus a speaking partner that grades every word you say. Reading is the mature half; speaking is a working preview.</td>
  <td>macOS<br>Windows<br>Linux</td>
  <td><code>In&nbsp;development</code></td>
</tr>
<tr>
  <td width="52" align="center"><img src="https://raw.githubusercontent.com/hexpro-dev/.github/main/profile/assets/icons/nepali-companion.png" width="36" alt=""></td>
  <td><b><a href="https://apps.hex.pro/nepali-companion">Nepali Companion</a></b></td>
  <td>A chapter book you play through, from not recognising a single letter of Devanagari to reading real Nepali.</td>
  <td>iPhone</td>
  <td><code>In&nbsp;development</code></td>
</tr>
</table>

### Browser tools

Both run entirely in the page. Nothing is uploaded, and the source is public so that claim can be checked rather than trusted.

| Tool | What it does | Source |
|:--|:--|:--|
| **[Private Image Converter](https://apps.hex.pro/tools/private-image-converter)** | Twenty-six image formats go in and twenty come out, all of it inside the tab. | [private-image-converter](https://github.com/hexpro-dev/private-image-converter) |
| **[Authenticator Secret Extractor](https://apps.hex.pro/tools/google-authenticator-secret-extractor)** | Reads the secret keys out of a Google Authenticator export. Also published to npm. | [google-auth-secret-retriever](https://github.com/hexpro-dev/google-auth-secret-retriever) |

### Platform

**[Hex Citadel](https://citadel.hex.pro)** is an open-source, self-hostable cloud file storage platform, and the largest thing we are building. Files are encrypted before they leave your device, so the server holds ciphertext and nothing that can read it. Run it on hardware you own and pay nothing, or let us run it for you.

Server and client are MIT licensed. Citadel is a prototype in active development, and its repositories open as they reach a state worth reading.

<br>

## How we build

<table>
<tr>
<td width="50%" valign="top">

**No third-party advertising**

There is no ad network in any of our apps and no plan to add one. The only thing any of them will ever promote is another Hex Pro app.

</td>
<td width="50%" valign="top">

**No analytics inside the apps**

No analytics SDK, no crash reporting, no tracking identifiers. Whatever an app does send is listed in its privacy policy. Hex NFC documents every request it makes by file and line, and there are three.

</td>
</tr>
<tr>
<td valign="top">

**Pay once where paying once makes sense**

A subscription is honest when there are servers to run. An alarm clock has none, so Sol is free to use and its full version is a single payment, with a monthly option for anyone who would rather not pay up front. kcalc.ai runs its AI on servers, so it is a subscription, and its own paywall tells you it costs less bought from our site than through the App Store. Hex NFC is free.

</td>
<td valign="top">

**Accessibility isn't a settings screen**

Reduce Motion is honoured throughout. Colour-blind-safe palettes, dyslexia-friendly type, and no meaning ever carried by hue alone.

</td>
</tr>
<tr>
<td valign="top">

**Costs published in the open**

Hex NFC lists what it cost to build, itemised down to the postage on a bag of test tags, and how much of that has come back. The [figures are live](https://apps.hex.pro/hex-nfc/costs), so they are not copied here where they could quietly go stale.

</td>
<td valign="top">

**Tested against real hardware**

Plenty of NFC support is written from a datasheet and never touched to a tag. A chip counts as supported once it has been read, written, protected and unlocked against a physical tag on physical hardware. Until then it is listed as untested.

</td>
</tr>
</table>

Seven languages, not five plus machine translation. The four websites are there today and so is Hex NFC; the other apps reach it before they ship. Arabic reads right to left, and that was built in rather than bolted on.

<p align="center">
  <code>English</code>&nbsp; <code>中文</code>&nbsp; <code>العربية</code>&nbsp; <code>Español</code>&nbsp; <code>日本語</code>&nbsp; <code>Français</code>&nbsp; <code>Português&nbsp;(BR)</code>
</p>

<br>

## The stack

<p align="center">
  <img alt="Swift" src="https://img.shields.io/badge/Swift-F05138?style=for-the-badge&logo=swift&logoColor=white">
  <img alt="SwiftUI" src="https://img.shields.io/badge/SwiftUI-0071E3?style=for-the-badge&logo=apple&logoColor=white">
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white">
  <img alt="React" src="https://img.shields.io/badge/React-087EA4?style=for-the-badge&logo=react&logoColor=white">
</p>
<p align="center">
  <img alt="Rust" src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white">
  <img alt="Node.js" src="https://img.shields.io/badge/Node.js-5FA04E?style=for-the-badge&logo=nodedotjs&logoColor=white">
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white">
  <img alt="Tailwind CSS" src="https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white">
</p>

Apps are Swift and SwiftUI, written against current iOS rather than the oldest version we could support. Sol is built on AlarmKit so that the operating system owns the alarm rather than the app, which is why it asks for iOS 26.1. That is a real cost, and it buys the one thing an alarm clock has to get right.

The websites are TypeScript end to end and rendered on the server, because a page that loads fast on a bad connection is worth more than one that is clever. Where a site handles anything about you, its own privacy policy sets out what is kept and for how long.

<br>

## Reading the source

The two browser tools are public today. Each one is the source behind a privacy claim made on the website, which is the entire reason for publishing it.

| Repository | What it is |
|:--|:--|
| [**private-image-converter**](https://github.com/hexpro-dev/private-image-converter) | Image format conversion that runs entirely in the browser. |
| [**google-auth-secret-retriever**](https://github.com/hexpro-dev/google-auth-secret-retriever) | Reads secret keys from a Google Authenticator export. Published to npm. |

Hex Citadel's server and client cores are MIT licensed. Hex NFC is source-available under the Business Source License 1.1, converting to Apache 2.0 in 2030, so that every privacy claim it makes can be read rather than believed. Those repositories are private while what is in them is still changing.

<br>

## Elsewhere

| Where | What is there |
|:--|:--|
| [**hex.pro**](https://hex.pro) | The company: mission, blog, contact. |
| [**apps.hex.pro**](https://apps.hex.pro) | Every app and tool, with the specifics. |
| [**citadel.hex.pro**](https://citadel.hex.pro) | Hex Citadel. |
| [**games.hex.pro**](https://games.hex.pro) | Hex Games, and its dev blog. |
| [**github.com/hexpro-games**](https://github.com/hexpro-games) | The games organisation. |

<br>

---

<p align="center">
  <img src="https://raw.githubusercontent.com/hexpro-dev/.github/main/profile/assets/mark.png" width="38" alt="">
</p>

<p align="center">
  <b>Ars Vitae Pty Ltd</b>, trading as Hex Pro<br>
  ABN 44 687 418 220 &nbsp;·&nbsp; Australian owned and operated
</p>

<p align="center">
  General enquiries through the <a href="https://hex.pro/contact">contact form</a>.<br>
  Privacy questions to privacy@hex.pro.
</p>
