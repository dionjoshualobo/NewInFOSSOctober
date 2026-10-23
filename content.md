### 1. IndiaFOSS 2026 held in Bengaluru; Mohit P. Tahiliani elected to FOSS United’s Governing Board

IndiaFOSS 2026 took place on 26–27 September at NIMHANS Convention Centre, Bengaluru, bringing together India's FOSS and digital commons communities. Dr. Mohit P. Tahiliani, Associate Professor at NITK Surathkal and an active contributor to the ns-3 community, was elected to the 2026 FOSS United Governing Board. The election drew 1,131 participants, including 985 votes cast and approximately 146 abstentions.

![](https://www.google.com/s2/favicons?domain=https://fossunited.org&sz=32)

FOSS United

+1

Why it matters: FOSS United is not just running meetups; it is developing governance, funding and community infrastructure for open-source work in India. Having an experienced educator and open-source contributor on its Governing Board is relevant to student contributor pathways and community sustainability.

### 2. postmarketOS renamed to Nura

On 27 September, the mobile Linux operating system formerly known as postmarketOS announced that it would henceforth be called Nura. The new name comes from Nuraghe, ancient stone structures in Sardinia, and reflects the project's long-term ambition of keeping devices useful for as long as possible. The rebrand followed roughly a year and a half of name selection.

![](https://www.google.com/s2/favicons?domain=https://nura.eco&sz=32)

Nura

Why it matters: The project continues to focus on Linux beyond conventional desktops and servers. Extending the life of phones and other devices has implications for electronic waste, user control, device ownership and the right to repair.

### 3. IFPI wants yt-dlp included in the EU's piracy watch list

The International Federation of the Phonographic Industry (IFPI) asked the European Commission to include yt-dlp, the popular open-source media-downloading tool, in its 2027 Counterfeit and Piracy Watch List. The music industry's submission argues that the tool facilitates unauthorised downloading and places it in the stream-ripping category.

![](https://www.google.com/s2/favicons?domain=https://torrentfreak.com&sz=32)

TorrentFreak

+1

Important distinction: This is a request for inclusion, not a ban. The EU's consultation says the next watch list is expected in the second quarter of 2027 and does not itself establish legal violations.

![](https://www.google.com/s2/favicons?domain=https://policy.trade.ec.europa.eu&sz=32)

Trade and Economic Security

Why it matters: It raises a major question for open-source maintainers: when software can be used for both legitimate and infringing purposes, should responsibility rest with the developer, the user, the platform or the service provider?

### 4. Microsoft WSL Containers reaches general availability

On 29 September, Microsoft announced general availability of WSL Containers. Developers can use the `wslc` CLI, also available through the `container` alias, to build, run and deploy Linux containers on Windows. The release includes container networking, file-copying, lifecycle management, event streaming and health checks.

![](https://www.google.com/s2/favicons?domain=https://blogs.windows.com&sz=32)

Windows Developer Blog

Why it matters: Windows developers get another way to work with Linux container environments without relying on the traditional Docker Desktop workflow. It is an interesting case of a proprietary operating system investing more deeply in Linux-based development tooling. Compose support was still on Microsoft's roadmap in the announcement.

### 5. Linux kernel 7.3 released

The mainline Linux kernel 7.3 was released on 18 October 2026, according to the official kernel archive.

![](https://www.google.com/s2/favicons?domain=https://kernel.org&sz=32)

Kernel.org

There's an additional timing detail worth mentioning: Ubuntu 26.10 had already been released on 15 October using a Linux 7.3 release-candidate kernel. The final kernel version arrived three days later.

![](https://www.google.com/s2/favicons?domain=https://documentation.ubuntu.com&sz=32)

Ubuntu release notes

+1

Why it matters: Each kernel release can bring support for newer processors and devices, improvements to filesystems, networking and graphics, and security fixes. For people running Linux on newer laptops, ARM systems or RISC-V hardware, upstream kernel development directly affects what works.

### 6. DankMaterialShell becomes Dux Shell

On 20 October, DankMaterialShell (DMS) announced version 2.0 and its rebrand to Dux Shell. Its wider ecosystem is also being renamed: Dank Linux becomes Dux Labs, with related projects renamed to match. The release brings a standalone Dux Files file manager, a customizable lock screen, new plugins and expanded compositor support, including Hyprland, MangoWC and Aqueous.

![](https://www.google.com/s2/favicons?domain=https://duxlabs.dev&sz=32)

Dux

Why it matters: This is more than a cosmetic name change. A project that began as a desktop shell has grown into a larger desktop ecosystem, and the new branding reflects that expansion.

Google open-sources Mantis, an AI framework for finding and fixing software vulnerabilities — 2 September

Google released Mantis as an open-source framework that uses AI agents to discover, reproduce, triage and help patch bugs. Its approach combines agent review with sandboxed reproduction, aiming to reduce false positives from AI-generated vulnerability reports.

![](https://www.google.com/s2/favicons?domain=https://cloud.google.com&sz=32)

Google Cloud Blog

The UN launches the System Data Commons — 17 September

The United Nations launched a public platform intended to make data from across the UN system easier to discover and access. Twenty-six UN entities had committed to sharing data, with 17 connected at the time of UNESCO's October announcement. It is a significant development for data interoperability and the reuse of public-interest information.

![](https://www.google.com/s2/favicons?domain=https://www.unesco.org&sz=32)

UNESCO

Ubuntu 26.10 brings RISC-V desktop images and local speech-to-text — 15 October

The release adds desktop image support for platforms including SpacemiT K3 and QEMU, alongside broader RISC-V support. It also introduces Myna, an opt-in speech-to-text feature processed locally. This connects open computing hardware, Linux support and on-device AI in one release.

Linux Foundation launches OpenGrid for electricity-grid planning — 7 October

OpenGrid is an open-source initiative intended to provide shared data, tools, APIs and interoperability standards for electricity-grid planning. The goal is to make grid planning more accessible and accelerate energy infrastructure deployment—a reminder that open-source infrastructure can matter far beyond computing.

## PHP2Shell: two critical, unauthenticated remote-code-execution vulnerabilities in PHP — 21 October

Critical

CVSS 9.2 each

PHP released fixes for CVE-2026-109618 and CVE-2026-109619. The bugs involve memory corruption during out-of-memory handling and stale global state. An attacker can potentially execute code on an exposed server without authentication, even before application-level code runs. The PHP team identifies Apache `mod_php` deployments as particularly concerning.

![](https://www.google.com/s2/favicons?domain=https://www.cert.europa.eu&sz=32)

Critical Vulnerabilities in PHP

+1

The story got worse on 23 October: a third issue, CVE-2026-115560, was reported. It requires an unusual combination of PHP session-serialization configuration and application behaviour. As of 24 October, a fix was not yet available; the PHP team recommended disabling `session.upload_progress.enabled` to mitigate this attack path. Authorities had also reported widespread exploitation attempts targeting the first two vulnerabilities.

![](https://www.google.com/s2/favicons?domain=https://www.cyber.gc.ca&sz=32)

Canadian Centre for Cyber Security

+1

Why it matters: This is a highly relevant incident for anyone running websites, PHP-based content-management systems, control panels or hosting infrastructure. The initial fixes are available in PHP 8.5.12, 8.4.27, 8.3.36 and 8.2.35. Older, unsupported versions require particular care.

## Node.js releases a major security update covering DNS, TLS, Brotli and cryptography — 21 October

High-severity issues

The Node.js project published security updates across its 22.x, 24.x and 26.x release lines. One of the most serious fixes, CVE-2026-111497, addresses an out-of-bounds write in the bundled Brotli decoder that could potentially lead to remote code execution when an application decompresses malicious input.

![](https://www.google.com/s2/favicons?domain=https://nodejs.org&sz=32)

Wednesday, October 21, 2026 Security Releases

Other bugs included DNS resolution silently truncating hostnames containing NUL bytes, TLS certificate hostname-verification bypasses involving unusual IP-address representations, and cryptographic random-number caches being reused across application snapshots. The last issue could cause generated UUIDs or random integers to repeat between processes.

![](https://www.google.com/s2/favicons?domain=https://nodejs.org&sz=32)

Wednesday, October 21, 2026 Security Releases

+1

Why it matters: These are not merely application-framework bugs. They affect Node's built-in security-sensitive APIs and bundled dependencies, so developers should check the actual Node version used in production.

Fixed releases: Node.js 22.23.4, 24.22.1 and 26.12.1. The risk from each issue depends on how an application uses the affected functionality.


## Zephyr gets stronger semiconductor backing from Texas Instruments and Infineon — 1 October

Texas Instruments and Infineon upgraded their membership in the Zephyr Project to Platinum, increasing their commitment to the open-source real-time operating system and its ecosystem.

![](https://www.google.com/s2/favicons?domain=https://www.linuxfoundation.org&sz=32)

Linux Foundation

Why it's exciting: Zephyr is designed for embedded devices with limited memory and compute resources. Stronger chip-vendor participation helps support the board integrations, drivers and tooling needed for real-world embedded development.

This is an excellent story for people interested in microcontrollers, IoT, firmware and open hardware.

## Google Data Commons launches an SDMX 3.0 API — 23 September

Google Data Commons introduced an API for discovering and retrieving statistical observations through SDMX (Statistical Data and Metadata eXchange), a widely used standard for exchanging statistical data and metadata. The API supports availability queries and retrieval of observations in SDMX formats.

![](https://www.google.com/s2/favicons?domain=https://blog.datacommons.org&sz=32)

Data Commons • Blog

Why it's exciting: Instead of writing a custom parser for every national statistics agency or dataset, developers can use standardised interfaces and data structures. It is a concrete example of open standards making public data more reusable.


## IETF advances post-quantum cryptography work for TLS 1.3 — September

The Internet Engineering Steering Group approved documents covering the use of ML-DSA digital signatures and ML-KEM key establishment with TLS 1.3. The September IETF activity report also records eight published RFCs for the month.

![](https://www.google.com/s2/favicons?domain=https://datatracker.ietf.org&sz=32)

IETF Datatracker

+1

Why it's exciting: Post-quantum cryptography is about preparing internet security for adversaries with future quantum-computing capabilities. Protocol work is needed before these algorithms can be adopted consistently across browsers, servers, libraries and infrastructure.

The approved documents were listed as informational, so this should be presented as progress in protocol development, not as the completion of a new universal TLS standard.

**HTTP Officially Gets a New Method: IETF Publishes RFC 10008 for `QUERY` (Sept 10)** For the first time in years, HTTP has a brand-new standard verb: `QUERY`. It solves a decades-old web engineering headache by creating a **safe, idempotent, cacheable** request method that _explicitly allows a request body_—meaning complex search queries and GraphQL-style payloads can finally stop pretending to be `POST` requests or stuffing massive JSON strings into `GET` URLs.

**OpenStreetMap Crosses 115 Million Mapped Names & Holds 20th AGM (Sept – Oct 17)** OpenStreetMap celebrated passing 115 million named local features under the open ODbL license while previewing its new localized **Vector Tile layer** on `openstreetmap.org`, right before the OSM Foundation held its landmark 20th Annual General Meeting and board election on October 17.

**DeepSeek Open-Sources "DeepInfer" Under Apache 2.0 (Oct 20)** In a rare move where a frontier AI lab gave away its production serving sauce, DeepSeek open-sourced **DeepInfer** (alongside `deepseek-recipe`), the internal inference engine built on vLLM that powers its V4.1-Flash models across both Nvidia and non-CUDA Huawei Ascend chips—racking up 8,000+ GitHub stars in a single afternoon.
