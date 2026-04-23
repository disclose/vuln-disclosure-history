---
title: "The disclose.io History Timeline"
date: 2026-04-23
source: "https://disclose.io/history/"
source_archive_ph: "https://archive.ph/newest/https://disclose.io/history/"
source_archive_org: "https://web.archive.org/web/2026/https://disclose.io/history/"
last_imported: 2026-04-23
tags: ["timeline", "coordinated-disclosure", "legal", "standards"]
---

## About this page

This is a fact-checked import of the timeline published at [disclose.io/history/](https://disclose.io/history/) ([archive.ph](https://archive.ph/newest/https://disclose.io/history/)), annotated in the spirit of this repo's [mission]({{< ref "/" >}}) — surfacing the **people**, not just the events, and beginning to trace the **drafting lineage** between them. Where a named individual's role in an event is well-documented in public record, they are attributed with a citation; where the drafting authors are known to exist but are not yet researched, the entry is flagged for enrichment rather than left blank.

Every source URL below is linked with an archive.ph permalink and, where a Wayback Machine snapshot exists, an archive.org link.

## Fact-check findings

> ⚠️ **Discrepancy — ISO standard number and date (Feb 2012 entry).**
>
> The disclose.io/history page labels the February 2012 entry as **"ISO 24197/30111"**. The linked ISO page (`iso.org/standard/45170.html`) is actually **ISO/IEC 29147** (Information technology — Security techniques — Vulnerability disclosure). **ISO/IEC 24197** is an unrelated standard on water-management accounting.
>
> Additionally, **ISO/IEC 29147** was first formally published in **February 2014**, not 2012; **ISO/IEC 30111** was first published in **2013**. The "Feb 2012" date on disclose.io may reference an earlier committee draft stage, but the publication year listed is inconsistent with the ISO catalogue.
>
> **Recommendation:** file a PR to [disclose.io-website](https://github.com/disclose/disclose.io-website) correcting the typo to "ISO 29147/30111" and updating the date to reflect the actual publication year (2013–2014).

---

## Timeline

### 1995-10-10 — Netscape launches the first "bugs bounty"

Netscape Communications Corporation announces the **Netscape Bugs Bounty** program, offering rewards to external researchers who report security flaws in Navigator 2.0 beta — the first corporate bug bounty in the modern software industry.

**Known contributors:** Jarrett Ridlinghafer (Netscape technical support engineer) is widely credited in public retellings with proposing the program. *Attribution to verify with primary sources.*

**Drafting lineage:** The starting point. Subsequent commercial bounty programs trace their conceptual ancestry here.

**Sources:**
- Primary: [Netscape press release (1995)](https://web.archive.org/web/19970501041756/http://www101.netscape.com/newsref/pr/newsrelease48.html) · [archive.ph](https://archive.ph/newest/https://web.archive.org/web/19970501041756/http://www101.netscape.com/newsref/pr/newsrelease48.html) · [archive.org](https://web.archive.org/web/19970501041756/http://www101.netscape.com/newsref/pr/newsrelease48.html)

**Fact-check:** Verified — Netscape press release is datelined "MOUNTAIN VIEW, Calif. (October 10, 1995)" and titled "Netscape Announces Netscape Bugs Bounty".

---

### 2001-09-28 — RFPolicy v1

Version 1 of the **Rain Forest Puppy disclosure policy** template is released — the first widely-adopted written framework for how a researcher and a vendor should behave during a disclosure.

**Known contributors:** Published under the handle **Rain Forest Puppy** (RFP), a pseudonymous researcher whose identity the community has long respected as private. The point of record is the handle, not the legal name.

**Drafting lineage:** Cited by nearly every subsequent disclosure policy template. RFPolicy's structural DNA (deadline, good-faith contact attempts, graduated escalation) shows up in OSVDF (2014), disclose.io core terms (2018), and most modern VDPs.

**Sources:**
- Secondary (contemporaneous coverage): [PCWorld, Sept 2001 (via Wayback)](https://web.archive.org/web/20010930194040/http://pcworld.com/news/article/0,aid,63944,00.asp) · [archive.ph](https://archive.ph/newest/https://web.archive.org/web/20010930194040/http://pcworld.com/news/article/0,aid,63944,00.asp) · [archive.org](https://web.archive.org/web/20010930194040/http://pcworld.com/news/article/0,aid,63944,00.asp)

**Fact-check:** Verified — archived PCWorld article references Rain Forest Puppy and the disclosure policy release dated September 28, 2001.

**To enrich:** Link to the original RFPolicy document text (multiple mirrors exist) and to RFP's own Wiretrip site where it was first posted.

---

### 2012–2014 — ISO/IEC 29147 and ISO/IEC 30111

> **This entry combines what disclose.io/history lists as "ISO 24197/30111 released for paying customers" (Feb 2012) and "Free ISO 24197" (Apr 2016). Per the fact-check above, the correct standard numbers are 29147 and 30111. Publication dates below use the ISO catalogue of record.**

- **ISO/IEC 30111:2013** — *Information technology — Security techniques — Vulnerability handling processes.* First published October 2013. (Updated 2019 edition below.)
- **ISO/IEC 29147:2014** — *Information technology — Security techniques — Vulnerability disclosure.* First published February 2014. (Independently verified against the ISO catalogue page: title is "ISO/IEC 29147:2014 - Information technology — Security techniques — Vulnerability disclosure". A second edition, **ISO/IEC 29147:2018**, has since superseded the 2014 version at [iso.org/standard/72311](https://www.iso.org/standard/72311.html).)
- **2016-04-18** — ISO/IEC 29147 made available as a free download (a rare move for ISO).

**Known contributors:** **Katie Moussouris** is widely documented as a principal drafter and evangelist of ISO/IEC 29147 during her time at Microsoft and afterwards. The standards were developed under **ISO/IEC JTC 1/SC 27 WG4**, whose working-group members are the behind-the-scenes drafters whose names are the kind of quiet-giant work this repo is built to surface.

**Drafting lineage:** 29147 codifies the RFPolicy-era norms of coordinated disclosure into an international standard. 30111 focuses on the vendor-side handling process. Both are cited by CISA BOD 20-01, NIST SP 800-216, and the EU NIS2 / CRA frameworks downstream.

**Sources:**
- ISO/IEC 29147 catalogue entry: [iso.org/standard/45170](https://www.iso.org/standard/45170.html) · [archive.ph](https://archive.ph/newest/https://www.iso.org/standard/45170.html) · [archive.org](https://web.archive.org/web/20260421011508/https://www.iso.org/standard/45170.html)
- Free-download news: [itnews.com.au — ISO vulnerability disclosure standard now free](https://www.itnews.com.au/news/iso-vulnerability-disclosure-standard-now-free-418253) · [archive.ph](https://archive.ph/newest/https://www.itnews.com.au/news/iso-vulnerability-disclosure-standard-now-free-418253)

**To enrich:** Identify the SC27/WG4 drafters of record for both standards. Capture the story of how 29147 got pushed to free availability in 2016.

---

### 2014-07-24 — OSVDF (Open Source Vulnerability Disclosure Framework)

**Bugcrowd** and **CipherLaw** collaborate to release the Open Source Vulnerability Disclosure Framework — reusable template text for organizations to publish a VDP without re-inventing legal language from scratch.

**Known contributors:**
- **Casey Ellis** (founder, Bugcrowd)
- **Jim Denaro** (CipherLaw)

**Drafting lineage:** OSVDF's terms trace back to RFPolicy (2001) for the researcher-vendor handshake and to ISO/IEC 29147 (2014) for structural norms. It later merges with #legalbugbounty to become the disclose.io Core Terms in 2018.

**Sources:**
- Repository: [github.com/bugcrowd/disclosure-policy](https://github.com/bugcrowd/disclosure-policy) · [archive.ph](https://archive.ph/newest/https://github.com/bugcrowd/disclosure-policy) · [archive.org](https://web.archive.org/web/20260222082216/https://github.com/bugcrowd/disclosure-policy)

---

### 2018 — #legalbugbounty

**Amit Elazari-Bar On** hits the cybersecurity talk circuit with the **#legalbugbounty** campaign — advocating for explicit legal "safe harbor" language in VDPs so researchers know they won't be sued or prosecuted for good-faith work. She maintains a running "Hall of Fame / Shame" grading public programs on their safe-harbor posture.

**Known contributors:**
- **Amit Elazari-Bar On** (then at UC Berkeley, later at Intel and Open Policy Group)

**Drafting lineage:** Directly addresses the legal gap that RFPolicy, OSVDF, and ISO/IEC 29147 didn't close — explicit anti-prosecution and anti-litigation language inside the VDP itself. Merges with OSVDF in August 2018 to form disclose.io.

**Sources:**
- #legalbugbounty HoF (original): [amitelazari.com/#legalbugbounty-hof](https://amitelazari.com/%23legalbugbounty-hof) · [archive.ph](https://archive.ph/newest/https://amitelazari.com/%23legalbugbounty-hof) · [archive.org (root)](https://web.archive.org/web/20260324071353/https://amitelazari.com/)

**Note:** The specific `#legalbugbounty-hof` anchor may no longer resolve on the live page; the archived root of amitelazari.com is included as a secondary anchor.

---

### 2018-08-03 — disclose.io launches

**#legalbugbounty** and **OSVDF** combine to create **The disclose.io Project** — a common open-source template that marries OSVDF's workflow terms with #legalbugbounty's safe-harbor language, intended as a drop-in VDP that any organization can adopt.

**Known contributors:**
- **Casey Ellis** (Bugcrowd)
- **Amit Elazari-Bar On**
- **Jim Denaro** (CipherLaw)

**Drafting lineage:** A direct merge — OSVDF (2014) + #legalbugbounty (2018) = disclose.io Core Terms (2018). Those terms are later cited or paralleled by DOJ's 2022 good-faith research policy, CISA BOD 20-01, and many corporate VDPs.

**Sources:**
- [Ars Technica launch coverage](https://arstechnica.com/information-technology/2018/08/new-open-source-effort-legal-code-to-make-reporting-security-bugs-safer) · [archive.ph](https://archive.ph/newest/https://arstechnica.com/information-technology/2018/08/new-open-source-effort-legal-code-to-make-reporting-security-bugs-safer)
- [Crunchbase — disclose-io](https://www.crunchbase.com/organization/disclose-io) · [archive.ph](https://archive.ph/newest/https://www.crunchbase.com/organization/disclose-io)
- [Wikitia — Disclose.io](https://wikitia.com/wiki/Disclose.io) · [archive.ph](https://archive.ph/newest/https://wikitia.com/wiki/Disclose.io) · [archive.org](https://web.archive.org/web/20231204101900/https://wikitia.com/wiki/Disclose.io)

---

### 2019-10 — ISO/IEC 30111:2019 (updated)

Updated edition of the vulnerability handling processes standard — reflects practitioner experience since the 2013 first edition.

**Known contributors:** ISO/IEC JTC 1/SC 27 WG4 — drafters of record to be identified.

**Sources:**
- [iso.org/standard/69725](https://www.iso.org/standard/69725.html) · [archive.ph](https://archive.ph/newest/https://www.iso.org/standard/69725.html)

---

### 2020-09-02 — CISA BOD 20-01

**CISA Binding Operational Directive 20-01** requires all U.S. federal civilian executive-branch agencies to publish a Vulnerability Disclosure Policy — the first time VDPs become mandatory across a government.

**Known contributors:**
- Signed by **Christopher Krebs** (then CISA Director).
- Drafted by CISA's **Vulnerability Management** team and policy staff — individual drafters to be identified.

**Drafting lineage:** The earlier 18F / GSA VDP (2016) and DoD VDP (2016) are the two operational precedents. ISO/IEC 29147 and the disclose.io terms provide the structural template. BOD 20-01 is the moment those templates become obligatory.

**Sources:**
- [cisa.gov/news-events/directives/bod-20-01](https://www.cisa.gov/news-events/directives/bod-20-01-develop-and-publish-vulnerability-disclosure-policy) · [archive.ph](https://archive.ph/newest/https://www.cisa.gov/news-events/directives/bod-20-01-develop-and-publish-vulnerability-disclosure-policy)

---

### 2020-09 — UK NCSC Vulnerability Disclosure Toolkit

The **UK National Cyber Security Centre** releases a comprehensive VDP guidance document and templates for UK organisations.

**Known contributors:** NCSC technical directorate — drafters of record to be identified.

**Sources:**
- [ncsc.gov.uk/information/vulnerability-disclosure-toolkit](https://www.ncsc.gov.uk/information/vulnerability-disclosure-toolkit) · [archive.ph](https://archive.ph/newest/https://www.ncsc.gov.uk/information/vulnerability-disclosure-toolkit)

---

### 2021-06-03 — *Van Buren v. United States*

U.S. Supreme Court narrows the CFAA's "exceeds authorized access" clause in a landmark 6–3 ruling — substantially limiting the statute's reach against good-faith security researchers.

**Known contributors:**
- **Justice Amy Coney Barrett** (majority opinion, public record).
- Amicus briefs from **EFF**, **researchers**, and industry groups — specific brief-drafters to be catalogued.

**Drafting lineage:** Decades of CFAA-overreach advocacy by the security research community, EFF, and academic scholars (including **Orin Kerr**, whose academic writing is cited). The ruling does not explicitly bless security research but sets the doctrinal foundation DOJ relies on for its 2022 policy below.

**Sources:**
- Opinion: [supremecourt.gov/opinions/20pdf/19-783_k53l.pdf](https://www.supremecourt.gov/opinions/20pdf/19-783_k53l.pdf) · [archive.ph](https://archive.ph/newest/https://www.supremecourt.gov/opinions/20pdf/19-783_k53l.pdf)
- EFF analysis: [eff.org/deeplinks/2021/06/supreme-court-substantially-limits-scope-controversial-hacking-law](https://www.eff.org/deeplinks/2021/06/supreme-court-substantially-limits-scope-controversial-hacking-law) · [archive.ph](https://archive.ph/newest/https://www.eff.org/deeplinks/2021/06/supreme-court-substantially-limits-scope-controversial-hacking-law)

---

### 2021-07-30 — CISA VDP Platform

CISA launches a centralized VDP platform for federal agencies, operationalizing BOD 20-01 by providing shared infrastructure rather than requiring each agency to build its own.

**Known contributors:** CISA Cybersecurity Division staff — drafters of record to be identified.

**Sources:**
- [cisa.gov/resources-tools/services/vulnerability-disclosure-policy-vdp-platform](https://www.cisa.gov/resources-tools/services/vulnerability-disclosure-policy-vdp-platform) · [archive.ph](https://archive.ph/newest/https://www.cisa.gov/resources-tools/services/vulnerability-disclosure-policy-vdp-platform) · [archive.org](https://web.archive.org/web/20250816125007/https://www.cisa.gov/resources-tools/services/vulnerability-disclosure-policy-vdp-platform)

---

### 2022-04 — RFC 9116 (security.txt)

IETF standardizes **security.txt**, a machine-readable file format at `/.well-known/security.txt` telling researchers how to report a vulnerability to the site owner.

**Known contributors (per the RFC itself):**
- **Edwin Foudil** (primary author)
- **Yakov Shafranovich**

**Drafting lineage:** Conceptual parallel to `robots.txt` and `humans.txt`. Years of Internet-Draft iteration preceded publication as RFC. Now a default element in mature VDP programs.

**Sources:**
- [rfc-editor.org/rfc/rfc9116](https://www.rfc-editor.org/rfc/rfc9116) · [archive.ph](https://archive.ph/newest/https://www.rfc-editor.org/rfc/rfc9116)

---

### 2022-05-19 — DOJ Good-Faith Security Research Policy

**U.S. Department of Justice** announces it **will not prosecute good-faith security research** under the CFAA — a policy statement following the doctrinal opening of *Van Buren*.

**Known contributors:**
- Announced under **Attorney General Merrick Garland** / **Deputy AG Lisa Monaco**.
- Career DOJ attorneys who drafted the policy — names to be identified.

**Drafting lineage:** Builds doctrinally on *Van Buren* (2021) and rhetorically on the decade of #legalbugbounty, EFF, and researcher-community advocacy.

**Sources:**
- [justice.gov press release](https://www.justice.gov/opa/pr/department-justice-announces-new-policy-charging-cases-under-computer-fraud-and-abuse-act) · [archive.ph](https://archive.ph/newest/https://www.justice.gov/opa/pr/department-justice-announces-new-policy-charging-cases-under-computer-fraud-and-abuse-act)

---

### 2022-12-14 — EU NIS2 Directive

The EU adopts the **NIS2 Directive**, which mandates coordinated vulnerability disclosure across Member States and directs ENISA to maintain a European Vulnerability Database.

**Known contributors:** European Commission DG CNECT drafters and rapporteurs — individuals to be identified.

**Drafting lineage:** Carries ISO/IEC 29147 norms into EU law and is the statutory basis for the ENISA European Vulnerability Database (2025).

**Sources:**
- Directive text: [eur-lex.europa.eu/eli/dir/2022/2555](https://eur-lex.europa.eu/eli/dir/2022/2555) · [archive.ph](https://archive.ph/newest/https://eur-lex.europa.eu/eli/dir/2022/2555) · [archive.org](https://web.archive.org/web/20260408195803/https://eur-lex.europa.eu/eli/dir/2022/2555)
- Vulnerability-disclosure article: [CELEX:32022L2555](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX%3A32022L2555#d1e2775-80-1) · [archive.ph](https://archive.ph/newest/https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX%3A32022L2555) · [archive.org](https://web.archive.org/web/20260401201951/https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX%3A32022L2555)

---

### 2023-05 — NIST SP 800-216

NIST publishes **SP 800-216**, *Recommendations for Federal Vulnerability Disclosure Guidelines* — the U.S. federal civilian reference for how an agency should run a VDP.

**Known contributors:** NIST Computer Security Resource Center staff — drafters listed on the document itself; to be transcribed into this entry.

**Sources:**
- [csrc.nist.gov/pubs/sp/800/216/final](https://csrc.nist.gov/pubs/sp/800/216/final) · [archive.ph](https://archive.ph/newest/https://csrc.nist.gov/pubs/sp/800/216/final) · [archive.org](https://web.archive.org/web/20251204151709/https://csrc.nist.gov/pubs/sp/800/216/final)

---

### 2024-04-29 — UK PSTI Act enforcement begins

The **UK Product Security and Telecommunications Infrastructure Act** takes effect — the first law anywhere requiring consumer IoT manufacturers to operate a vulnerability disclosure policy.

**Known contributors:** UK DCMS / DSIT policy staff — drafters to be identified.

**Drafting lineage:** Operationalizes years of IoT-security advocacy and the NCSC VDP toolkit (2020) into binding law on device makers.

**Sources:**
- [gov.uk PSTI product security regime](https://www.gov.uk/government/publications/the-uk-product-security-and-telecommunications-infrastructure-product-security-regime) · [archive.ph](https://archive.ph/newest/https://www.gov.uk/government/publications/the-uk-product-security-and-telecommunications-infrastructure-product-security-regime)

---

### 2024-12-10 — EU Cyber Resilience Act enters into force

The **EU Cyber Resilience Act** enters into force, mandating VDPs for all products with digital elements sold in the EU.

**Known contributors:** European Commission DG CNECT drafters and rapporteurs — individuals to be identified.

**Sources:**
- [digital-strategy.ec.europa.eu/en/policies/cyber-resilience-act](https://digital-strategy.ec.europa.eu/en/policies/cyber-resilience-act) · [archive.ph](https://archive.ph/newest/https://digital-strategy.ec.europa.eu/en/policies/cyber-resilience-act)

---

### 2025-05-13 — ENISA European Vulnerability Database launches

**ENISA** launches the **European Vulnerability Database** as mandated by the NIS2 Directive — the EU's centralized catalogue.

**Known contributors:** ENISA CVD team and vulnerability-management staff — individuals to be identified.

**Sources:**
- [enisa.europa.eu/topics/vulnerability-disclosure](https://www.enisa.europa.eu/topics/vulnerability-disclosure) · [archive.ph](https://archive.ph/newest/https://www.enisa.europa.eu/topics/vulnerability-disclosure)

---

## Provenance

- **Source page:** [disclose.io/history/](https://disclose.io/history/) · [archive.ph](https://archive.ph/newest/https://disclose.io/history/)
- **Imported:** 2026-04-23
- **Method:** page fetched via curl (HTTP 200, no redirects); entries parsed from Hugo timeline component; each source URL re-archived where an archive.org snapshot was absent.
- **Fact-check:** 3 spot-checks performed on entries 0, 1, 2. Findings: (0) ✅ verified, (1) ✅ verified, (2) ⚠️ ISO standard number typo + date mismatch — see top-of-page callout.

## Contributing

This is a first-pass import. Many entries are flagged **"drafters of record to be identified"** — that's the quiet work this repo exists to surface. If you drafted any of these documents, sat in the working-group rooms, or remember the people who did — [open an issue or PR](https://github.com/disclose/vuln-disclosure-history/issues).
