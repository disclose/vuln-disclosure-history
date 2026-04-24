---
title: "The disclose.io History Timeline"
date: 2026-04-23
source: "https://disclose.io/history/"
source_archive_ph: "https://archive.ph/newest/https://disclose.io/history/"
source_archive_org: "https://web.archive.org/web/2026/https://disclose.io/history/"
last_imported: 2026-04-23
last_enriched: 2026-04-24
tags: ["timeline", "coordinated-disclosure", "legal", "standards"]
---

## About this page

This is a fact-checked import of the timeline published at [disclose.io/history/](https://disclose.io/history/) ([archive.ph](https://archive.ph/newest/https://disclose.io/history/)), annotated in the spirit of this repo's [mission]({{< ref "/" >}}) — surfacing the **people**, not just the events, and beginning to trace the **drafting lineage** between them. Every named contributor has a citation URL plus a quoted excerpt from that source substantiating the role. Where drafters are known to exist but are not surfaced in public record, the entry carries an explicit **quiet giants** note rather than a guess.

Confidence tags: **high** (primary-source citation), **medium** (secondary-source corroboration or inferred from institutional role), **unconfirmed** (community attribution without a primary source yet).

## Fact-check findings

> ⚠️ **Discrepancy 1 — ISO standard number and date (Feb 2012 entry).**
>
> The disclose.io/history page labels the February 2012 entry as **"ISO 24197/30111"**. The linked ISO page (`iso.org/standard/45170.html`) is actually **ISO/IEC 29147** (Information technology — Security techniques — Vulnerability disclosure). **ISO/IEC 24197** is an unrelated standard on water-management accounting. Independently verified against the live ISO catalogue page.
>
> Additionally, **ISO/IEC 29147** was first formally published in **February 2014**, not 2012; **ISO/IEC 30111** was first published in **2013**. The "Feb 2012" date on disclose.io may reference an earlier committee draft stage, but the publication year listed is inconsistent with the ISO catalogue.

> ⚠️ **Discrepancy 2 — RFPolicy v1 date.**
>
> The disclose.io/history page gives the RFPolicy v1 release as **September 28, 2001**. Wikipedia and community retellings place **v1 in 2000**, with 2001-09-28 corresponding to **v2**. Worth verifying against RFP's Wiretrip archive (multiple mirrors exist) before accepting 2001-09-28 as v1's date.

> ⚠️ **Discrepancy 3 — I Am The Cavalry origin year.**
>
> Although not currently listed on disclose.io/history/ specifically, community retellings often date I Am The Cavalry to **2014** (its DEF CON 22 automotive-industry open-letter moment). The organization's own [history page](https://iamthecavalry.org/about/history/) says it was "born" earlier: Josh Corman and Nick Percoco originated it through conversations at DEF CON 21 / BSides Las Vegas in **summer 2013**. 2014 was the public-policy debut, not the founding.

> ⚠️ **Attribution note 4 — disclose.io launch credits (2018).**
>
> Community discussion commonly credits **Casey Ellis + Amit Elazari + Jim Denaro** as co-founders of disclose.io in August 2018. The primary source — Bugcrowd's [launch press release](https://www.bugcrowd.com/press-release/bugcrowd-launches-disclose-io-open-source-vulnerability-disclosure-framework-to-provide-a-safe-harbor-for-white-hat-hackers/) — names **Ellis** (Bugcrowd) and **Elazari** (UC Berkeley / CLTC) as the launching co-founders, and cites CipherLaw's OSVDF (Denaro's prior work), #legalbugbounty, and Dropbox's VDP safe-harbor language as antecedent contributions. **Denaro's verifiable role is upstream — OSVDF 2014 — rather than direct disclose.io co-founding in 2018.** This distinction does not diminish the foundational role; it clarifies the public record.

> **Recommendations for follow-up PRs to [disclose.io-website](https://github.com/disclose/disclose.io-website):**
> 1. Correct the "ISO 24197" typo to "ISO 29147" and update the date to 2013–2014.
> 2. Verify the RFPolicy v1/v2 dates against RFP's own Wiretrip archive.

---

## Timeline

### 1995-10-10 — Netscape launches the first "bugs bounty"

Netscape Communications Corporation announces the **Netscape Bugs Bounty** program, offering rewards to external researchers who report security flaws in Navigator 2.0 beta — the first corporate bug bounty in the modern software industry.

**Known contributors:**
- **Jarrett Ridlinghafer** (Netscape technical support engineer, employee #113) — **high** confidence. Proposed the program and coined the phrase "bugs bounty." *[His own about.me bio](https://about.me/jnridlinghafer): "I created the first original 'Bugs Bounty' program and coined the phrase while at Netscape Communications Corp where I was employee #113 in 1995 - 1999."*
- **James Barksdale** (Netscape CEO) — **medium**. Attended the executive meeting that approved the proposal. *[Wikipedia mirror (IPFS)](https://ipfs.io/ipfs/QmXoypizjW3WknFiJnKLwHCnL72vedxjQkDDP1mXWo6uco/wiki/Bug_bounty_program.html): "the executive team meeting … attended by James Barksdale, Marc Andreessen and the VPs of every department".*
- **Marc Andreessen** (Netscape co-founder) — **medium**. Same executive meeting. *(same source)*

**Drafting lineage:** The starting point of the commercial bug bounty lineage. Subsequent programs (Mozilla, Google, Facebook, HackerOne/Bugcrowd platform era) trace their conceptual ancestry here.

**Quiet giants:** The Netscape VP of Engineering who initially opposed the proposal but was overruled, the legal counsel who blessed it, and the PR team who operationalized the October 10, 1995 announcement — all remain uncredited in public record. Ridlinghafer's own narrative necessarily centers his role.

**Sources:**
- Primary: [Netscape press release (1995)](https://web.archive.org/web/19970501041756/http://www101.netscape.com/newsref/pr/newsrelease48.html) · [archive.ph](https://archive.ph/newest/https://web.archive.org/web/19970501041756/http://www101.netscape.com/newsref/pr/newsrelease48.html) · [archive.org](https://web.archive.org/web/19970501041756/http://www101.netscape.com/newsref/pr/newsrelease48.html)

**Fact-check:** Verified — Netscape press release is datelined "MOUNTAIN VIEW, Calif. (October 10, 1995)".

---

### 2001-09-28 — RFPolicy v2 (see fact-check note above re: v1 date)

A widely-adopted written framework for how a researcher and a vendor should behave during a disclosure.

**Known contributors:**
- **"Rain Forest Puppy" (RFP)** — **high** confidence as handle attribution. Sole author. Pseudonymity respected in community practice; RFP has given interviews but continues to be identified by handle. *[Wikipedia](https://en.wikipedia.org/wiki/RFPolicy): "It was initially written in 2000 by hacker and security consultant Rain Forest Puppy."*

**Drafting lineage:** Cited by nearly every subsequent disclosure policy template. RFPolicy's structural DNA (deadline, good-faith contact attempts, graduated escalation) shows up in OSVDF (2014), disclose.io core terms (2018), and most modern VDPs.

**Quiet giants:** Early full-disclosure community discussants on Bugtraq and similar lists shaped the norms RFPolicy formalized, but only RFP's byline appears. Peer-review dynamics for v1/v2 are undocumented in public.

**Sources:**
- Secondary (contemporaneous coverage): [PCWorld, Sept 2001 (via Wayback)](https://web.archive.org/web/20010930194040/http://pcworld.com/news/article/0,aid,63944,00.asp) · [archive.ph](https://archive.ph/newest/https://web.archive.org/web/20010930194040/http://pcworld.com/news/article/0,aid,63944,00.asp)

**To enrich:** Link to the original RFPolicy document text (multiple mirrors exist) and to RFP's own Wiretrip site where it was first posted.

---

### 2012–2014 — ISO/IEC 29147 and ISO/IEC 30111

> **This entry combines what disclose.io/history lists as "ISO 24197/30111 released for paying customers" (Feb 2012) and "Free ISO 24197" (Apr 2016). Per the fact-check above, the correct standard numbers are 29147 and 30111. Publication dates below use the ISO catalogue of record.**

- **ISO/IEC 30111:2013** — *Information technology — Security techniques — Vulnerability handling processes.* First published October 2013. (Updated 2019 edition below.)
- **ISO/IEC 29147:2014** — *Information technology — Security techniques — Vulnerability disclosure.* First published February 2014. (Independently verified against the ISO catalogue page: title is "ISO/IEC 29147:2014 - Information technology — Security techniques — Vulnerability disclosure". A second edition, **ISO/IEC 29147:2018**, has since superseded the 2014 version at [iso.org/standard/72311](https://www.iso.org/standard/72311.html).)
- **2016-04-18** — ISO/IEC 29147 made available as a free download (a rare move for ISO).

**Known contributors:**
- **Katie Moussouris** — **high** confidence. Co-author and co-editor of ISO/IEC 29147 and ISO/IEC 30111; U.S. National Body subject-matter expert. During the core drafting years she was Senior Security Strategist Lead at Microsoft MSRC (Sept 2010 – May 2014); later at HackerOne and then founded Luta Security. *[Luta Security founder bio](https://www.lutasecurity.com/founder-ceo): "Katie is also the co-author and co-editor of ISO 29147 (vulnerability disclosure) and ISO 30111 (vulnerability handling processes)."*
- **Art Manion** — **high**. Co-editor; co-led the 2016 "make it free" advocacy with Moussouris while at CERT/CC. *[iTnews (April 2016)](https://www.itnews.com.au/news/iso-vulnerability-disclosure-standard-now-free-418253): "the global standards organisation approved a request from Luta Security researcher Kate Moussouris and Art Manion of the US CERT Coordination Centre (CERT/CC) to offer ISO/IEC 29147 at no cost. The two have worked as co-editors of the standard since after the free version was published, and have helped edit it since around 2008."*

**Drafting lineage:** 29147 codifies the RFPolicy-era norms of coordinated disclosure into an international standard; 30111 focuses on the vendor-side handling process. Both are cited downstream by CISA BOD 20-01, NIST SP 800-216, and the EU NIS2 / CRA frameworks.

**Quiet giants:** ISO/IEC JTC 1/SC 27 WG4's full roster of editors, rapporteurs, and national-body reviewers across years of meetings — dozens of experts — is effectively anonymous in public discourse. Moussouris's visibility is exceptional for an ISO editor. The US National Body delegation, UK, Japanese, and German experts who shaped 29147 remain unnamed in the public record. A further pass would extract editor lists from the published standard's Foreword and SC27 meeting minutes.

**Sources:**
- ISO/IEC 29147 catalogue entry: [iso.org/standard/45170](https://www.iso.org/standard/45170.html) · [archive.ph](https://archive.ph/newest/https://www.iso.org/standard/45170.html) · [archive.org (2026-04-21)](https://web.archive.org/web/20260421011508/https://www.iso.org/standard/45170.html)
- Free-download news: [itnews.com.au — ISO vulnerability disclosure standard now free](https://www.itnews.com.au/news/iso-vulnerability-disclosure-standard-now-free-418253) · [archive.ph](https://archive.ph/newest/https://www.itnews.com.au/news/iso-vulnerability-disclosure-standard-now-free-418253)

---

### 2014-07-24 — OSVDF (Open Source Vulnerability Disclosure Framework)

**Bugcrowd** and **CipherLaw** collaborate to release the Open Source Vulnerability Disclosure Framework — reusable template text for organizations to publish a VDP without re-inventing legal language from scratch.

**Known contributors:**
- **Casey Ellis** — **high**. CEO and co-founder of Bugcrowd; sponsor/co-author of the framework. *[PRNewswire launch release](https://www.prnewswire.com/news-releases/bugcrowd-releases-open-source-responsible-disclosure-framework-268435072.html): quoted as "Bugcrowd is all about connecting independent security researchers with companies big and small."*
- **Jim Denaro** — **high**. Founder of CipherLaw; legal collaborator and co-author. *[Same PRNewswire release](https://www.prnewswire.com/news-releases/bugcrowd-releases-open-source-responsible-disclosure-framework-268435072.html): quoted as "We need to ensure that independent researchers with the skills to find these vulnerabilities are not discouraged from reporting them because of the legal risks."* The GitHub README confirms "This Framework is maintained by Bugcrowd and CipherLaw."

**Drafting lineage:** OSVDF borrows structural norms from RFPolicy (2001) for the researcher-vendor handshake and from ISO/IEC 29147 (2014) for process structure. Later merges with Elazari's #legalbugbounty safe-harbor language to become the disclose.io Core Terms in 2018.

**Quiet giants:** The framework was released on GitHub under CC-BY — so subsequent community pull requests (findable in the repo's git log) are the best documented layer of contributors. Internal Bugcrowd policy/ops staff and any CipherLaw associate attorneys who drafted language are not named in launch materials; git commit history is the authoritative trail.

**Sources:**
- Repository: [github.com/bugcrowd/disclosure-policy](https://github.com/bugcrowd/disclosure-policy) · [archive.ph](https://archive.ph/newest/https://github.com/bugcrowd/disclosure-policy) · [archive.org](https://web.archive.org/web/20260222082216/https://github.com/bugcrowd/disclosure-policy)

---

### 2018 — #legalbugbounty

**Amit Elazari Bar-On** launches the **#legalbugbounty** campaign — advocating for explicit legal "safe harbor" language in VDPs so researchers know they won't be sued or prosecuted for good-faith work. She maintains a running "Hall of Fame / Shame" grading public programs on their safe-harbor posture.

**Known contributors:**
- **Amit Elazari Bar-On** — **high**. Author of the campaign. Affiliation at the time: UC Berkeley (doctoral candidate; Center for Long-Term Cybersecurity grantee). *[#legalbugbounty project repo description](https://github.com/EdOverflow/legal-bug-bounty): "creating safe harbors on bug bounty programs and vulnerability disclosure programs. Authored by Amit Elazari."* Her 2018 USENIX Enigma talk "Hacking the Law: Are Bug Bounties a True Safe Harbor?" is the canonical presentation.
- **EdOverflow** — **medium**. Hosts the project repo on GitHub; editorial/contribution scope unclear without commit-log review.

**Drafting lineage:** Directly addresses the legal gap that RFPolicy, OSVDF, and ISO/IEC 29147 didn't close — explicit anti-prosecution and anti-litigation language inside the VDP itself. Merges with OSVDF in August 2018 to form disclose.io.

**Quiet giants:** CLTC grant reviewers, Elazari's doctoral supervisor at UC Berkeley, and the researchers who provided bug-bounty terms-and-conditions samples used in her empirical analysis all remain uncredited in public campaign materials.

**Sources:**
- #legalbugbounty HoF (original): [amitelazari.com/#legalbugbounty-hof](https://amitelazari.com/%23legalbugbounty-hof) · [archive.ph](https://archive.ph/newest/https://amitelazari.com/%23legalbugbounty-hof) · [archive.org (root)](https://web.archive.org/web/20260324071353/https://amitelazari.com/)

---

### 2018-08-03 — disclose.io launches

**#legalbugbounty** and **OSVDF** combine to create **The disclose.io Project** — a common open-source template marrying OSVDF's workflow terms with #legalbugbounty's safe-harbor language, intended as a drop-in VDP that any organization can adopt.

**Known contributors (per the launch press release):**
- **Casey Ellis** — **high**. Bugcrowd founder/CTO at launch. *[Bugcrowd press release](https://www.bugcrowd.com/press-release/bugcrowd-launches-disclose-io-open-source-vulnerability-disclosure-framework-to-provide-a-safe-harbor-for-white-hat-hackers/): quoted as Bugcrowd founder/CTO.*
- **Amit Elazari Bar-On** — **high**. UC Berkeley doctoral candidate / CLTC Grantee. *[Same press release](https://www.bugcrowd.com/press-release/bugcrowd-launches-disclose-io-open-source-vulnerability-disclosure-framework-to-provide-a-safe-harbor-for-white-hat-hackers/): "More often than not, companies (usually unintentionally) omit legal safe-harbor language in their contracts."*

**Upstream contributors (acknowledged as antecedent work):**
- **Jim Denaro / CipherLaw** — via OSVDF (2014).
- **Dropbox** legal/security team — the Bugcrowd press release acknowledges Dropbox's VDP safe-harbor language as inspiration; individual Dropbox contributors are not named in the launch materials.

> **Note on attribution:** community retellings commonly list Denaro as a 2018 co-launcher alongside Ellis and Elazari. The primary source (the Bugcrowd 2018-08 press release) names only Ellis and Elazari, and cites CipherLaw/OSVDF and Dropbox as upstream contributors. Denaro's verifiable role is **upstream** (OSVDF 2014), not direct 2018 co-founding. Presented here as the public record shows; individual recollection from people present at the merger may fill in any gaps.

**Quiet giants:** The Dropbox attorneys who drafted the pioneering VDP safe-harbor language, and the engineers/legal counsel who shepherded OSVDF's community pull requests between 2014 and 2018, all made disclose.io possible without equal billing at the 2018 launch.

**Sources:**
- [Ars Technica launch coverage](https://arstechnica.com/information-technology/2018/08/new-open-source-effort-legal-code-to-make-reporting-security-bugs-safer) · [archive.ph](https://archive.ph/newest/https://arstechnica.com/information-technology/2018/08/new-open-source-effort-legal-code-to-make-reporting-security-bugs-safer)
- [Crunchbase — disclose-io](https://www.crunchbase.com/organization/disclose-io) · [archive.ph](https://archive.ph/newest/https://www.crunchbase.com/organization/disclose-io)
- [Wikitia — Disclose.io](https://wikitia.com/wiki/Disclose.io) · [archive.ph](https://archive.ph/newest/https://wikitia.com/wiki/Disclose.io) · [archive.org](https://web.archive.org/web/20231204101900/https://wikitia.com/wiki/Disclose.io)

---

### 2019-10 — ISO/IEC 30111:2019 (updated)

Updated edition of the vulnerability handling processes standard.

*Contributors as 2014 ISO entry (JTC 1/SC 27 WG4 — Moussouris, Manion, plus unidentified WG members).*

**Sources:**
- [iso.org/standard/69725](https://www.iso.org/standard/69725.html) · [archive.ph](https://archive.ph/newest/https://www.iso.org/standard/69725.html)

---

### 2020-09-02 — CISA BOD 20-01

**CISA Binding Operational Directive 20-01** requires all U.S. federal civilian executive-branch agencies to publish a Vulnerability Disclosure Policy — the first time VDPs become mandatory across a government.

**Known contributors:**
- **Christopher C. Krebs** — **high**. Signatory as CISA Director. *[Signed BOD 20-01 PDF](https://www.cisa.gov/sites/default/files/bod-20-01.pdf) FROM block: "Christopher C. Krebs, Director, Cybersecurity and Infrastructure Security Agency, Department of Homeland Security … SUBJECT: Develop and Publish a Vulnerability Disclosure Policy."*
- **Russell T. Vought** — **high**. OMB Director, CC'd on the directive via companion memorandum M-20-32. *(same PDF)*
- **Bryan Ware** — **high**. CISA Assistant Director for Cybersecurity; authored the companion blog summarizing the public-comment process. *[CISA blog "Improving Vulnerability Disclosure Together (Officially)"](https://www.cisa.gov/news-events/news/improving-vulnerability-disclosure-together-officially), September 2, 2020.*
- **Casey Ellis** (Bugcrowd) — **high**. Filed named public comment on draft BOD 20-01 that shaped the final directive. *[GitHub issue cisagov/cyber.dhs.gov#139](https://github.com/cisagov/cyber.dhs.gov/issues/139).* *(COI note: Ellis is the principal maintainer of this repo.)*

**Drafting lineage:** Operational precedents are the 18F/GSA VDP (2016) and DoD VDP (2016); structural template is ISO/IEC 29147 and the disclose.io Core Terms. BOD 20-01 is the moment those templates become obligatory for federal civilian agencies.

**Quiet giants:** BOD 20-01 went through an unusually open public-comment process on GitHub (cisagov/cyber.dhs.gov repo). External commenters are named in issue threads; the CISA staff inside Vulnerability Management who responded to comments and revised drafts are identified only by GitHub handles, not real names. A git-archaeology pass would surface the actual CISA drafting team.

**Sources:**
- [cisa.gov/news-events/directives/bod-20-01](https://www.cisa.gov/news-events/directives/bod-20-01-develop-and-publish-vulnerability-disclosure-policy) · [archive.ph](https://archive.ph/newest/https://www.cisa.gov/news-events/directives/bod-20-01-develop-and-publish-vulnerability-disclosure-policy)
- Signed PDF: [cisa.gov/sites/default/files/bod-20-01.pdf](https://www.cisa.gov/sites/default/files/bod-20-01.pdf)

---

### 2020-09 — UK NCSC Vulnerability Disclosure Toolkit

The **UK National Cyber Security Centre** releases a comprehensive VDP guidance document and templates.

**Known contributors:**
- **"Ollie N"** — **medium**. Head of Vulnerability Management at NCSC at the time; the named public face of the toolkit. NCSC publishes staff by first-name-plus-initial for security reasons, so the surname is not publicly disclosed. *[NCSC X/Twitter post](https://x.com/ncsc/status/1305556678658662400): "Ollie N explains the thinking behind the NCSC's new Vulnerability Disclosure Toolkit".*

> **Attribution note:** community chatter has at times suggested Ollie Whitehouse as the Toolkit's author. His own NCSC bio confirms he became NCSC CTO only in **late 2023** — three years after the Toolkit was published — so he cannot be the 2020 author. Similarly, Eleanor Fairford's NCSC portfolio is Incident Management, not Vulnerability Management; no primary source ties her to the Toolkit.

**Quiet giants:** NCSC's deliberate first-name-initial publishing convention makes authoritative attribution unusually hard. The drafters of record beyond "Ollie N" are effectively unknowable without NCSC choosing to disclose.

**Sources:**
- [ncsc.gov.uk/information/vulnerability-disclosure-toolkit](https://www.ncsc.gov.uk/information/vulnerability-disclosure-toolkit) · [archive.ph](https://archive.ph/newest/https://www.ncsc.gov.uk/information/vulnerability-disclosure-toolkit)

---

### 2021-06-03 — *Van Buren v. United States*

U.S. Supreme Court narrows the CFAA's "exceeds authorized access" clause in a landmark 6–3 ruling — substantially limiting the statute's reach against good-faith security researchers. The doctrinal foundation DOJ relies on for its 2022 good-faith research policy (below).

**Known contributors — the Court:**
- **Justice Amy Coney Barrett** — **high**. Majority author. *[Slip opinion, supremecourt.gov](https://www.supremecourt.gov/opinions/20pdf/19-783_k53l.pdf): "VAN BUREN v. UNITED STATES … No. 19–783. Argued November 30, 2020—Decided June 3, 2021".* (Barrett, J., delivered the opinion of the Court.)
- **Justice Clarence Thomas** — **high**. Dissent author (joined by Chief Justice Roberts and Justice Alito).

**Known contributors — petitioner's counsel (Stanford Supreme Court Litigation Clinic):**
- **Jeffrey L. Fisher** — **high**. Counsel of Record. *[Stanford Law publication](https://law.stanford.edu/publications/brief-for-petitioner-nathan-van-buren-petitioner-v-united-states-of-america-respondent/): "Jeffrey L. Fisher served as Counsel of Record for the petitioner Nathan Van Buren at the Stanford Law School Supreme Court Litigation Clinic … Jeffrey L. Fisher, along with Pamela S. Karlan and Brian H. Fletcher, authored the Brief for Petitioner."*
- **Pamela S. Karlan** — **high**. Co-author, petitioner's brief.
- **Brian H. Fletcher** — **high**. Co-author, petitioner's brief. (Fletcher later became Principal Deputy Solicitor General.)
- **Saraliene Smith Durrett** — **medium**. Co-counsel for petitioner. *(SCOTUS docket 19-783.)*
- **Rebecca Shepard** — **medium**. Federal Defender Program, Inc. (N.D. Ga.); the trial-level defender who **preserved the issue through the 11th Circuit** — without this, the case never reaches the Supreme Court.

**Known contributors — the government's brief (DOJ OSG):**
- **Jeffrey B. Wall** — **high**. Counsel of Record (Acting Solicitor General). *[DOJ OSG brief page](https://www.justice.gov/osg/brief/van-buren-v-united-states).*
- **Eric J. Feigin** — **medium**. Deputy Solicitor General.
- **Brian C. Rabbitt** — **medium**. Acting Assistant AG, Criminal Division.
- **Morgan L. Ratner** — **medium**. Assistant to the Solicitor General.
- **Jenny C. Ellickson** — **medium**. DOJ attorney on brief.

**Known contributors — amici curiae supporting petitioner:**
- **Prof. Orin S. Kerr** (then UC Berkeley Law; cross-listed GWU) — **high**. Filed a pro se amicus brief. *[UC Berkeley Law catalog record](https://lawcat.berkeley.edu/record/1174867): "Brief of Professor Orin S. Kerr as Amicus Curiae Supporting Petitioner".* Kerr's decades of academic writing on CFAA scope were cited across the filings.
- **Andrew Crocker** (EFF, Senior Staff Attorney) — **high**. Counsel of Record on EFF/CDT/OTI cert-stage amicus brief. *[EFF brief signature block](https://www.eff.org/files/2020/01/17/19-783_amicus_brief.pdf).*
- **Jamie Williams** (EFF, Staff Attorney) — **high**. Co-signer.
- **Camille Fischer** (EFF, Frank Stanton Legal Fellow) — **high**. Co-signer.
- **Sharon Bradford Franklin** (New America's Open Technology Institute, Director of Surveillance & Cybersecurity Policy) — **high**. OTI counsel on the EFF/CDT/OTI amicus.
- **Ross Schulman** (New America OTI, Senior Counsel) — **high**. OTI counsel on the same amicus.
- **Riana Pfefferkorn** (Stanford Center for Internet and Society, Associate Director of Surveillance & Cybersecurity) — **high**. Named amicus on a separate EFF-led brief. *[Stanford CIS publication](https://cyberlaw.stanford.edu/publications/amicus-brief-eff-and-riana-pfefferkorn).*

**Drafting lineage:** Decades of CFAA-overreach advocacy by the security research community, EFF, and academics (Orin Kerr's academic work runs through the majority opinion). The ruling does not explicitly bless security research but lays the doctrinal foundation for DOJ's 2022 good-faith research policy.

**Quiet giants:** The career DOJ attorneys on the government's brief (**Feigin, Ratner, Ellickson**) and the trial-level federal defenders (**Shepard, Durrett**) are the textbook quiet giants of this case — the constitutional question would never have reached the Supreme Court without them preserving the issue through the trial and appellate records. Fisher, Karlan, and Fletcher are famous; the record-preserving public defenders are not.

**Additional amici to catalog in a follow-up pass:** ACLU, Knight First Amendment Institute, Reporters Committee for Freedom of the Press, and many others filed briefs — each with its own named counsel. Full enumeration is retrievable from SCOTUS docket 19-783.

**Sources:**
- Opinion: [supremecourt.gov/opinions/20pdf/19-783_k53l.pdf](https://www.supremecourt.gov/opinions/20pdf/19-783_k53l.pdf) · [archive.ph](https://archive.ph/newest/https://www.supremecourt.gov/opinions/20pdf/19-783_k53l.pdf)
- EFF analysis: [eff.org — Supreme Court substantially limits scope of controversial hacking law](https://www.eff.org/deeplinks/2021/06/supreme-court-substantially-limits-scope-controversial-hacking-law) · [archive.ph](https://archive.ph/newest/https://www.eff.org/deeplinks/2021/06/supreme-court-substantially-limits-scope-controversial-hacking-law)
- EFF/CDT/OTI cert-stage amicus: [eff.org/files/2020/01/17/19-783_amicus_brief.pdf](https://www.eff.org/files/2020/01/17/19-783_amicus_brief.pdf)
- SCOTUS docket: [supremecourt.gov/docket/docketfiles/html/public/19-783.html](https://www.supremecourt.gov/docket/docketfiles/html/public/19-783.html)

---

### 2021-07-30 — CISA VDP Platform

CISA launches a centralized VDP platform for federal agencies, operationalizing BOD 20-01 with shared infrastructure.

**Known contributors:**
- **Eric Goldstein** — **high**. CISA Executive Assistant Director for Cybersecurity (succeeded Bryan Ware); announced and endorsed the platform. *[Executive Gov coverage](https://executivegov.com/2021/08/cisa-launches-new-online-vulnerability-disclosure-platform/): "CISA Executive Assistant Director for Cybersecurity Eric Goldstein wrote in a blog post".*
- **Bugcrowd** (vendor partner under prime contractor EnDyna) — **high**. *[Infosecurity Magazine](https://www.infosecurity-magazine.com/news/cisa-bugcrowd-federal-vdp-platform/): "CISA Partners with Bugcrowd to Launch First Federal Civilian Crowdsourced VDP Platform."*

**Quiet giants:** The CISA career civil servants who wrote the VDP Platform requirements, ran the procurement, and operate the platform day-to-day are not publicly identified in launch materials or in the VDP Platform Annual Reports. EnDyna's delivery manager and Bugcrowd's engineering lead are similarly unnamed in primary CISA sources.

**Sources:**
- [cisa.gov/resources-tools/services/vulnerability-disclosure-policy-vdp-platform](https://www.cisa.gov/resources-tools/services/vulnerability-disclosure-policy-vdp-platform) · [archive.ph](https://archive.ph/newest/https://www.cisa.gov/resources-tools/services/vulnerability-disclosure-policy-vdp-platform) · [archive.org (2025-08-16)](https://web.archive.org/web/20250816125007/https://www.cisa.gov/resources-tools/services/vulnerability-disclosure-policy-vdp-platform)

---

### 2022-04 — RFC 9116 (security.txt)

IETF standardizes **security.txt**, a machine-readable file format at `/.well-known/security.txt` telling researchers how to report a vulnerability to the site owner. This is one of the cleanest, most-cited primary sources in the whole timeline — the RFC itself names its contributors.

**Known contributors (authors):**
- **Edwin Foudil** — **high**. Listed on RFC 9116 first page. Independent; originated the security.txt concept (often under the handle @EdOverflow).
- **Yakov Shafranovich** — **high**. Listed on RFC 9116 first page. Affiliation given on the RFC as Nightwatch Cybersecurity.

**Known contributors (Acknowledgments section, verbatim from the RFC):**
> *"The authors would like to acknowledge the help provided during the development of this document by Tom Hudson, Jobert Abma, Gerben Janssen van Doorn, Austin Heap, Stephane Bortzmeyer, Max Smith, Eduardo Vela, and Krzysztof Kotowicz."*

- **Tom Hudson** — development contributor.
- **Jobert Abma** (HackerOne co-founder) — development contributor.
- **Gerben Janssen van Doorn** — development contributor.
- **Austin Heap** — development contributor.
- **Stephane Bortzmeyer** (AFNIC) — development contributor.
- **Max Smith** — development contributor.
- **Eduardo Vela** (Google) — development contributor.
- **Krzysztof Kotowicz** (Google) — development contributor.
- **IETF LAST CALL, SAAG, and SECDISPATCH list members** — collective feedback providers.

**Drafting lineage:** Conceptual parallel to `robots.txt` and `humans.txt`. Years of Internet-Draft iteration preceded publication. Now a default element in mature VDP programs.

**Quiet giants (named, unusually!):** The eight Acknowledgments contributors — particularly Kotowicz and Vela at Google, Abma at HackerOne — are the "quiet giants" of security.txt standardization, and the RFC explicitly preserves their names. This is the model other primary sources should aspire to.

**Sources:**
- [rfc-editor.org/rfc/rfc9116](https://www.rfc-editor.org/rfc/rfc9116) · [archive.ph](https://archive.ph/newest/https://www.rfc-editor.org/rfc/rfc9116)

---

### 2022-05-19 — DOJ Good-Faith Security Research Policy

**U.S. Department of Justice** announces it **will not prosecute good-faith security research** under the CFAA — revising Justice Manual §9-48.000.

**Known contributors:**
- **Merrick B. Garland** — **high**. Attorney General under whose authority the revised policy was issued. *[DOJ press-release PDF](https://www.justice.gov/opa/press-release/file/1507126/download).*
- **Lisa O. Monaco** — **high**. Deputy Attorney General publicly identified with the policy roll-out; DAG office is the escalation point of record in the policy itself. *(same PDF: "When an office has consulted with CCIPS and intends to charge a CFAA case in a manner contrary to a written recommendation … that office shall inform the Office of the Deputy Attorney General before charging.")*
- **Computer Crime and Intellectual Property Section (CCIPS)** — **high**. DOJ component that drafted and administers the consultation framework. *(same PDF: "All federal prosecutors who seek to charge cases under the CFAA are required to consult with DOJ's Computer Crime and Intellectual Property Section ('CCIPS') before bringing charges.")*

**Drafting lineage:** Builds doctrinally on *Van Buren* (2021) and rhetorically on the decade of #legalbugbounty, EFF, and researcher-community advocacy. The Justice Manual does not name individual drafters — typical for JM revisions.

**Quiet giants:** The career CCIPS attorneys who drafted the revision are institutionally anonymous. **Leonard Bailey** (Special Counsel for National Security at CCIPS and long-associated with CFAA policy) is a strong candidate but not confirmed as drafter in any primary source.

**Sources:**
- [justice.gov press release](https://www.justice.gov/opa/pr/department-justice-announces-new-policy-charging-cases-under-computer-fraud-and-abuse-act) · [archive.ph](https://archive.ph/newest/https://www.justice.gov/opa/pr/department-justice-announces-new-policy-charging-cases-under-computer-fraud-and-abuse-act)
- Policy PDF: [justice.gov/opa/press-release/file/1507126/download](https://www.justice.gov/opa/press-release/file/1507126/download)

---

### 2022-12-14 — EU NIS2 Directive

The EU adopts the **NIS2 Directive** (Directive (EU) 2022/2555), mandating coordinated vulnerability disclosure across Member States and directing ENISA to maintain a European Vulnerability Database.

**Known contributors:**
- **Bart Groothuis MEP** (Renew Europe; VVD, Netherlands) — **high**. European Parliament rapporteur in the Committee on Industry, Research and Energy (ITRE). *[ITRE committee report A9-0313/2021](https://www.europarl.europa.eu/doceo/document/A-9-2021-0313_EN.html): "Committee on Industry, Research and Energy. Rapporteur: Bart Groothuis".* Groothuis's prior role was cybersecurity expert at the Dutch Ministry of Defence.

**Drafting lineage:** Carries ISO/IEC 29147 norms into EU law and is the statutory basis for the ENISA European Vulnerability Database (2025).

**Quiet giants:** Shadow rapporteurs from each EP group (EPP, S&D, Greens, ID, ECR, Left) meaningfully shaped NIS2 text. Their names appear on the A9-0313/2021 opinions page but were not enumerated in this pass.

**Sources:**
- Directive text: [eur-lex.europa.eu/eli/dir/2022/2555](https://eur-lex.europa.eu/eli/dir/2022/2555) · [archive.ph](https://archive.ph/newest/https://eur-lex.europa.eu/eli/dir/2022/2555) · [archive.org (2026-04-08)](https://web.archive.org/web/20260408195803/https://eur-lex.europa.eu/eli/dir/2022/2555)
- Vulnerability-disclosure article: [CELEX:32022L2555](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX%3A32022L2555#d1e2775-80-1) · [archive.ph](https://archive.ph/newest/https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX%3A32022L2555) · [archive.org](https://web.archive.org/web/20260401201951/https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX%3A32022L2555)

---

### 2023-05 — NIST SP 800-216

NIST publishes **SP 800-216**, *Recommendations for Federal Vulnerability Disclosure Guidelines* — the U.S. federal civilian reference for how an agency should run a VDP. The cover page of the PDF names its authors explicitly.

**Known contributors (from the cover page):**
- **Kim Schaffer** — **high**. Named first author; NIST Computer Security Division, ITL (ORCID 0000-0003-3073-2395).
- **Peter Mell** — **high**. Named author; NIST CSD. Long-time NIST contributor also known for NVD scoring work. (ORCID 0000-0003-2938-897X.)
- **Hung Trinh** — **high**. Named author; NIST CSD. (ORCID 0000-0002-3323-0836.)
- **Isabel Van Wyk** — **high**. Named author; NIST CSD. (ORCID 0000-0001-8566-6829.)

**Known contributors (Acknowledgments section, verbatim):**
> *"The authors would like to thank Tanya Brewer for her advice and support."*

- **Tanya Brewer** — **high**. Sole named acknowledgee.

**Institutional signatories:**
- **Laurie E. Locascio** — NIST Director and Under Secretary of Commerce for Standards and Technology.
- **Gina M. Raimondo** — U.S. Secretary of Commerce.

**Drafting lineage:** Mandated by the IoT Cybersecurity Improvement Act of 2020 (P.L. 116-207). Structurally downstream of ISO/IEC 29147/30111 and BOD 20-01.

**Quiet giants:** SP 800-216 went through two public-comment drafts (2021, 2022). Comment-file authors are cataloged by NIST but the final publication does NOT name them in acknowledgments — an unusually thin treatment. Congressional staff who drafted the IoT Cybersecurity Improvement Act of 2020 are upstream quiet giants.

**Sources:**
- [csrc.nist.gov/pubs/sp/800/216/final](https://csrc.nist.gov/pubs/sp/800/216/final) · [archive.ph](https://archive.ph/newest/https://csrc.nist.gov/pubs/sp/800/216/final) · [archive.org](https://web.archive.org/web/20251204151709/https://csrc.nist.gov/pubs/sp/800/216/final)
- PDF: [nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-216.pdf](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-216.pdf)

---

### 2024-04-29 — UK PSTI Act enforcement begins

The **UK Product Security and Telecommunications Infrastructure Act** takes effect — the first law anywhere requiring consumer-IoT manufacturers to operate a vulnerability disclosure policy.

**Known contributors:**
- **Julia Lopez MP** — **high**. Minister for Media, Data and Digital Infrastructure (DCMS); bill lead in later stages. *[Parallel Parliament bill page](https://www.parallelparliament.co.uk/mp/julia-lopez/bill/2021-22/productsecurityandtelecommunicationsinfrastructure).*
- **Matt Warman MP** — **high**. Parliamentary Under-Secretary of State (DCMS); earlier PSTI policy driver. *[House of Commons research briefing](https://researchbriefings.files.parliament.uk/documents/CBP-9430/CBP-9430.pdf): "the then Secretary of State for Culture, Media and Sport, Matt Warman, said that the Government would introduce legislation to protect consumers from insecure products."*

**Drafting lineage:** Operationalizes years of IoT-security advocacy and the 2020 NCSC VDP Toolkit into binding law on device makers. Its policy antecedent is the **Code of Practice for Consumer IoT Security** (October 2018), jointly authored by DCMS and NCSC.

**Quiet giants:** UK civil-service bill drafters at DCMS (later DSIT) are not routinely named publicly. The 2018 Code of Practice drafters — the unacknowledged spine of PSTI — are similarly anonymous. FOI requests or DSIT organograms would be required for attribution.

**Sources:**
- [gov.uk PSTI product security regime](https://www.gov.uk/government/publications/the-uk-product-security-and-telecommunications-infrastructure-product-security-regime) · [archive.ph](https://archive.ph/newest/https://www.gov.uk/government/publications/the-uk-product-security-and-telecommunications-infrastructure-product-security-regime)

---

### 2024-12-10 — EU Cyber Resilience Act enters into force

The **EU Cyber Resilience Act** (Regulation (EU) 2024/2847) enters into force, mandating VDPs for all products with digital elements sold in the EU.

**Known contributors:**
- **Nicola Danti MEP** (Renew Europe; Italia Viva, Italy) — **high**. European Parliament rapporteur (ITRE). *[European Parliament Multimedia Centre](https://multimedia.europarl.europa.eu/en/video/eu-cyber-resilience-act-extracts-from-the-vote-and-statement-by-nicola-danti-renew-it-rapporteur_I244230): "EU Cyber Resilience Act: extracts from the vote and statement by Nicola DANTI (Renew, IT), Rapporteur".*
- **Thierry Breton** — **high**. European Commissioner for Internal Market (DG CNECT) — the proposing Commissioner.

**Quiet giants:** DG CNECT unit heads who drafted the CRA are not routinely named in Commission press materials. Shadow rapporteurs across EP groups and the Council Working Party on Horizontal Cyber Issues did enormous unseen work; their names sit in EP committee rolls and Council meeting documents rather than in press releases.

**Sources:**
- [digital-strategy.ec.europa.eu/en/policies/cyber-resilience-act](https://digital-strategy.ec.europa.eu/en/policies/cyber-resilience-act) · [archive.ph](https://archive.ph/newest/https://digital-strategy.ec.europa.eu/en/policies/cyber-resilience-act)
- EP press release: [europarl.europa.eu/news/20240308IPR18991](https://www.europarl.europa.eu/news/en/press-room/20240308IPR18991/cyber-resilience-act-meps-adopt-plans-to-boost-security-of-digital-products)

---

### 2025-05-13 — ENISA European Vulnerability Database launches

**ENISA** launches the **European Vulnerability Database** as mandated by the NIS2 Directive — the EU's centralized catalogue.

**Known contributors:**
- **Juhan Lepassaar** — **high**. Executive Director, ENISA; announcing authority. *[ENISA news item, May 13, 2025](https://www.enisa.europa.eu/news/consult-the-european-vulnerability-database-to-enhance-your-digital-security): "ENISA achieves a milestone with the implementation of the vulnerability database requirement from the NIS 2 Directive."*

**Quiet giants:** EUVD is an implementation of NIS2 Article 12 obligations — the operational engineers at ENISA who stood it up are not publicly named. This is arguably the single largest current attribution gap in recent EU vulnerability-policy history.

**Sources:**
- [enisa.europa.eu/topics/vulnerability-disclosure](https://www.enisa.europa.eu/topics/vulnerability-disclosure) · [archive.ph](https://archive.ph/newest/https://www.enisa.europa.eu/topics/vulnerability-disclosure)
- Launch news: [enisa.europa.eu/news/consult-the-european-vulnerability-database](https://www.enisa.europa.eu/news/consult-the-european-vulnerability-database-to-enhance-your-digital-security)

---

## Provenance

- **Source page:** [disclose.io/history/](https://disclose.io/history/) · [archive.ph](https://archive.ph/newest/https://disclose.io/history/)
- **Imported:** 2026-04-23
- **People-enriched:** 2026-04-24 (first pass, four parallel research batches with strict citation_url + citation_quote rules to prevent confident-sounding hallucination).
- **Method:** page fetched via curl (HTTP 200, no redirects); entries parsed from Hugo timeline component; each source URL re-archived where an archive.org snapshot was absent; people-enrichment via four parallel research batches against primary sources (signed PDFs, RFC text, SCOTUS slip opinions, EP committee reports, ISO catalogue, own bios, press releases).
- **Fact-check:** four discrepancies / attribution notes surfaced (see top of page).

## Contributing

Many entries still carry explicit **"quiet giants"** flags — career civil servants, committee staff, shadow rapporteurs, working-group rapporteurs, CCIPS attorneys, ENISA engineers, DC3 staff, NHTSA OVSR researchers — whose names are not in the public record we could access. That's the work this repo exists to surface.

If you drafted any of these documents, sat in the working-group rooms, or remember the people who did — [open an issue or PR](https://github.com/disclose/vuln-disclosure-history/issues). Primary sources (the person's own bio, a document byline, a press release quote) beat community retellings every time.
