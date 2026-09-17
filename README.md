# Investigative Research & Resource Toolkit By Azutech

 A practical collection of investigative resources, research tools, datasets, and methodologies for OSINT, digital forensics, intelligence research, and cross-domain investigations.

---

## Resource Areas

**Open-Source Intelligence (OSINT)** / **Digital Forensics** / **Geospatial Intelligence (GEOINT)** / **Geopolitical Intelligence** / **Cyber Threat Intelligence (CTI)** / **Social Media Intelligence (SOCMINT)** / **Human Intelligence (HUMINT)** / **Corporate & Business Intelligence** / **Financial Intelligence** / **Cryptocurrency Intelligence** / **Economic Intelligence** / **Public Records Intelligence** / **Document & Data Intelligence** / **News & Media Intelligence** / **Archival & Historical Intelligence** / **Satellite & Remote Sensing Intelligence** / **Transportation Intelligence** / **Aviation Intelligence** / **Maritime Intelligence** / **Vehicle Intelligence** / **Threat & Risk Intelligence** / **Malware & Vulnerability Intelligence** / **Dark Web & Leak Intelligence** / **Law Enforcement & Criminal Intelligence** / **Scientific & Academic Intelligence** / **Research Intelligence** / **Country & Regional Intelligence** / **Open Data & Datasets** / **Investigative Methodology** / **Research & Investigation Utilities**

---

## OSINT

OSINT investigations often begin with a small piece of information such as a username, full name, email address, phone number, domain, IP address, image, location, organization, or document.

The starting point helps determine the appropriate research path and resources to use.

## Phase 1: Username & Identity
Username and identity analysis is an investigation starting point for researching online identities, aliases, and usernames across publicly available sources.
A username can serve as an initial pivot for discovering potentially related profiles, accounts, websites, and other identifiers. Findings should be correlated with additional evidence before attributing multiple accounts to the same individual.

| Tool | Starting Point | Purpose | What It Provides | URL |
|---|---|---|---|---|
| **WhatsMyName** | Username / Alias | Search a username across multiple public websites and social platforms. | Potential matching profiles and profile URLs across supported sources. | [WhatsMyName](https://whatsmyname.io/) |
| **Sherlock** | Username / Alias | Search for a username across social networks and other supported websites. | Potential matching accounts and profile URLs across supported sites. | [Sherlock](https://github.com/sherlock-project/sherlock) |
| **Maigret** | Username / Alias | Investigate a username across a large collection of websites and gather related account information. | Potential profiles, profile information, related identifiers, linked accounts, and investigation reports. | [Maigret](https://github.com/soxoj/maigret) |
| **Namechk** | Username / Alias | Check a username across social platforms and domain extensions. | Username registrations across supported social networks and domain availability results. | [Namechk](https://namechk.com/) |
| **Blackbird** | Username / Alias / Email | Search for accounts associated with a username or email across supported online services. | Potential accounts across social networks, streaming services, gaming platforms, stores, blogs, and other services. | [Blackbird](https://github.com/p1ngul1n0/blackbird) |
| Snoop | Username / Alias | Search for a username across a large collection of websites and online services. | Use a username as a pivot to discover possible accounts across multiple platforms and preserve findings for further correlation and verification. | [Snoop](https://github.com/snooppr/snoop?utm_source=chatgpt.com) |
| **User-Searcher** | Username / Alias | Search a username across a broad range of social networks, forums, communities, and other platforms. | Potential matching profiles, avatars, bios, linked websites, public activity, and exportable search results. | [User-Searcher](https://www.user-searcher.com/) |
| **Social Analyzer** | Username / Alias | Find and analyse profiles associated with a username across social platforms and websites. | Detected profiles, profile metadata, extracted patterns, screenshots, and confidence-based detection ratings. | [Social Analyzer](https://github.com/qeeqbox/social-analyzer) |
| **Tookie** | Username / Alias | Discover accounts associated with a username across supported websites and social platforms. | Potential matching profiles, account URLs, and site-specific username results. | [Tookie](https://github.com/Alfredredbird/alfred) |
| **IntelTechniques** | Username / Alias | Run a username across multiple search and account-discovery services from one interface. | Aggregated search results, profile links, and potential username reuse across supported services. | [IntelTechniques](https://inteltechniques.com/tools/Username) |
| **Marple** | Username / Alias | Find profiles and pages associated with a username through search engines. | Potential profile links and search-engine results containing the target username. | [Marple](https://github.com/soxoj/marple) |
| **IDCrawl** | Username / Alias | Search for usernames across social networks and people-search sources. | Potential matching profiles, usernames, social accounts, and related public information. | [IDCrawl](https://www.idcrawl.com/username-search) |
| **Lullar** | Username / Alias | Search a username across multiple social networks, communities, and online platforms. | Potential matching profiles, direct account links, and cross-platform username presence. | [Lullar](https://com.lullar.com/?utm_source=chatgpt.com) |
| **Instant Username Search** | Username / Alias | Check a username across multiple platforms to identify where the handle is already registered. | Platform-by-platform username availability and direct profile links for potential matches. | 🟡 Freemium [Instant Username Search](https://instantusername.com/?utm_source=chatgpt.com) |
| **NameMC** | Username / Alias | Investigate Minecraft usernames and gaming identities through player profiles and related account data. | Minecraft username availability, UUIDs, skins, servers, and available profile information. | [NameMC](https://namemc.com/) |
| **Enola** | Username / Alias | Search a username across supported social networks and online services using a fast Go-based CLI. | Potential matching profiles and account URLs across 400+ supported sites, with CSV/JSON export. | [Enola](https://github.com/theyahya/enola) |
| **Aliens Eye** | Username / Alias | Scan a username across social networks and web platforms to identify potential online identities. | Potential matching accounts, confidence-based results, and identity correlations across 800+ platforms. | [Aliens Eye](https://github.com/arxhr007/Aliens_eye) |
| **User Scanner** | Username / Alias / Email | Search usernames across multiple platforms and extract additional public profile information. | Potential accounts, extracted profile data, username results, and email-related intelligence across supported platforms. | [User Scanner](https://github.com/kaifcodec/user-scanner) |
| **WolverEye** | Username / Alias | Search a username across social, gaming, developer, forum, and other online platforms. | Potential profile URLs across 1,000+ platforms plus Google-dorking results for wider web mentions. | [WolverEye](https://wolverbot.online/?utm_source=chatgpt.com) |
| **Socialscan** | Username / Alias / Email | Check whether a username or email is registered on supported online services. | Registration-status results across supported platforms, including services such as Instagram, GitHub, GitLab, Reddit, Tumblr, and Twitter/X. | [Socialscan](https://github.com/iojw/socialscan) |
| **Aware Online** | Username / Alias | Search a username across supported online services to identify potential account reuse. | Potential matching profiles and account locations across supported platforms. | [Aware Online](https://www.aware-online.com/en/osint-tools/username-search-tool/) |
| **Social Searcher** | Username / Name | Search public social profiles, posts, and mentions using a name, username, or keyword. | Potential social profiles, public posts, mentions, images, and related account activity across supported sources. | [Social Searcher](https://www.social-searcher.com/) |
| **Intelligence X** | Username / Alias / Identity | Run username investigations through a multi-source lookup interface and pivot from discovered identifiers into broader Intelligence X searches. | Username results from supported third-party services, plus potential pivots to emails, domains, URLs, IPs, phone numbers, leaked/public data, and historical indexed records. | Free / Paid Features [Intelligence X](https://intelx.io/tools?tab=username) |
| **OSINT Name Checker** | Username / Alias | Check a username across multiple social, developer, gaming, and other platforms. | Profile-existence results across 50+ supported sites, with found/not-found/uncertain classifications and direct profile links. | [OSINT Name Checker](https://github.com/quelquun667/OSINT-Name-Checker?utm_source=chatgpt.com)  |
| **Nexfil** | Username / Alias | Search a username across a large collection of websites to identify potential online profiles. | Potential matching profiles and account URLs across supported social networks, forums, gaming sites, and other platforms. | [Nexfil](https://github.com/thewhiteh4t/nexfil) |
| **Keybase** | Username / Identity Proof | Investigate a username through cryptographic identity proofs and linked online identities. | Keybase profiles, verified links to services such as GitHub/Twitter, public keys, identity proofs, and historical username changes. | [Keybase](https://keybase.io/) |
| **OMAR-Thing** | TikTok Username / ID | Investigate a TikTok account from its username or permanent user ID. | Public profile details, user ID, region, language, account dates, follower/following counts, likes, videos, and other public profile data. | [OMAR-Thing](https://omar-thing.site/?utm_source=chatgpt.com) |

---

## Phase 2: People Search & Identity Analysis
People search and identity analysis focuses on finding, identifying, and correlating information about individuals using publicly available names, identifiers, profiles, records, and other online sources.

| Tool | Type | Purpose | What It Provides | URL / Access |
| ---- | ---- | ------- | ---------------- | ------------ |
| **X-Ray Contact** | Web-based Platform | Search and correlate public identity information from names, usernames, emails, phone numbers, and social profiles. | Potential names, contact details, social profiles, usernames, locations, and other identity-related information aggregated from public sources. | [X-Ray Contact](https://x-ray.contact/) Freemium |
| Spokeo | Web-based Platform | Search for people and correlate identity information from names, phone numbers, email addresses, and addresses. | Potential contact details, address history, social profiles, relatives, and other publicly sourced identity information. | [Spokeo](https://www.spokeo.com/) Freemium |
