# Research Paper — GamiFi public filings check — 6 September 2026

**Historical edition.** Findings and access descriptions are dated to the research date shown. This public edition is limited to crypto-related research. Later evidence supersedes some earlier gaps: the 7 September ShibaFriend claims review records repayment to all 23 non-dust original funding addresses, with 168 BUSD base units of unmatched dust; the later Mystery Box review records matching project contributions for all 194 paid mints. These narrow results do not settle every wider claim or identify a human wallet controller. Consult the repository README for the latest report precedence before quoting an earlier unresolved finding. Source URLs, transaction hashes and archive dates remain the research locators; historical local file locators below are not assertions that those working files are distributed unchanged.

Target: Gamifi Limited, British Virgin Islands entity 2082070; project domain gamifi.gg; GMI on BNB Smart Chain. This is an immediate public-record check following the consolidated master report.

## Result

No additional company filing, court judgment, insolvency notice or regulator notice was positively matched to this entity in the free sources searched. The check did not obtain a director, beneficial owner, registered agent or current official company status. The existing corporate number remains the useful record target.

## Corporate registry and Gazette

The free i-BVI entry still matches Gamifi Limited and number 2082070 and reports registration on 12.11.2021 (12 November 2021). This date is commercial-directory evidence; no official certificate was retrieved.

- https://i-bvi.com/company/gamifi-limited_978843

The BVI FSC's official search guidance, revised 1 September 2025, describes paid company-search reports containing status, registered agent, name history, registry transaction history and certificate history. The registry transaction history is a list of filed corporate actions, not a blockchain transaction list. Copies of listed filings may then be requested. The portal's public landing page was readable, but its linked entity-search and beneficial-ownership login endpoints returned retrieval errors in this check.

- https://www.bvifsc.vg/searches-bvi-registered-entities
- https://www.bvifsc.vg/public-search

Exact-name/number and liquidation, dissolution, strike-off, notice and filing searches did not locate a matching indexed BVI Gazette notice. The Gazette's own guidance says older liquidation and other notices require an electronic subscription; the recent-publications link also returned a retrieval error. This was not a complete native Gazette archive search.

- https://eservices.gov.vg/gazette/content/help-support
- https://eservices.gov.vg/gazette/content/about-official-gazette

## Eastern Caribbean Supreme Court: direct public search

The court's public judgments search was queried through the normal endpoint exposed by its official client. An independent repeat returned:

| Query | HTTP status | Reported hits |
|---|---:|---:|
| Gamifi | 200 | 0 |
| Exact phrase Gamifi Limited | 200 | 0 |
| 2082070 | 200 | 0 |
| company — functionality control only | 200 | 3,577 |

The control shows that the endpoint was returning searchable results. It does not establish complete coverage of filed proceedings. The separate public site search also returned empty results for Gamifi and 2082070. Unpublished, sealed and unindexed case files remain outside this check.

Official interface: https://www.eccourts.org/judgments

Endpoint: POST https://api.eccourts.org/judgments/search

Repeated query body, changing the query value for each row:

```json
{"query":"Gamifi","mustFilters":[],"yearFilters":[],"countryFilter":[],"queryType":"simple","pagination":{"perPage":1,"page":1}}
```

Each zero-result response reported hits.total 0 and pagination page 1, total 0, totalPages 0. The exact-phrase query value included quotation marks around Gamifi Limited. Public site search: https://api.eccourts.org/v1/search?s=Gamifi

Public client references: https://www.eccourts.org/js/app.c6aef834.js and https://www.eccourts.org/js/search.00504cf2.js

Additional indexed court checks covered ECSC, JCPC, Cayman judiciary, BAILII, CanLII, UK judiciary, US federal-court domains and freely indexed OffshoreAlert material using the company name, number and insolvency/judgment variants. No positively matched filing emerged. A South African Gamifi Industrial Properties (Pty) Ltd liquidation and the UK Gamifi Solutions Limited record were excluded as separate corporate identities.

## Regulatory coverage and namesake resolution

All four BVI FSC VASP directory pages were directly reviewed, containing 57 category entries. Gamifi was absent from the retrieved text of each. This is an observation about the public directory checked today, not a determination about past licensing or whether a particular registration duty applied.

Indexed SEC, FCA and Canadian regulator searches produced no matched GamiFi project filing. Native EDGAR and Canadian database searches were not completed. The detailed coverage and exact query log follow below.

The UK strike-off notice concerns GAMIFI SOLUTIONS LIMITED, company 07703903. Its official filing history records a 21 May 2024 notice and an 11 June 2024 suspension. No positive link to BVI 2082070 or gamifi.gg was identified; this notice is not attributed to the investigated BVI entity.

No payment, account creation, purchase, outbound record request or scheduled monitoring was performed. This check does not add a verified human wallet owner or bank account to the evidence.

## Detailed regulatory query log

### GamiFi regulatory and UK corporate filing check — 6 September 2026

#### Result

No filing, warning, enforcement notice, or regulator entry positively matched to the investigated GamiFi project was identified in this bounded free public-source check. Matching identifiers were Gamifi Limited (BVI entity 2082070), gamifi.gg, and BNB Smart Chain GMI contract 0x93d8d25e3c9a847a5da79f79ecac89461feca846. This records search coverage and results, not proof that no filing exists or that the company had no regulatory obligations.

#### Direct official-source checks

1. **BVI FSC VASP directory:** all four public pages were opened, covering the displayed 57 category entries (some firms appear more than once for different categories). `Gamifi` was absent from each page's retrieved text. This is a current public-list observation; it does not determine historical licensing, whether a filing obligation applied, or private filings.

   - https://www.bvifsc.vg/regulated-entities-vasp.
   - https://www.bvifsc.vg/regulated-entities-vasp?page=1.
   - https://www.bvifsc.vg/regulated-entities-vasp?page=2.
   - https://www.bvifsc.vg/regulated-entities-vasp?page=3.

2. **BVI FSC alerts:** current alerts landing page opened. No GamiFi-specific result surfaced in separate indexed name/domain searches. Older alert archive pages were not exhaustively traversed.

   - https://www.bvifsc.vg/library/alerts.

3. **UK Companies House namesake:** official overview and filing history identify **GAMIFI SOLUTIONS LIMITED, company 07703903**, incorporated 13 July 2011, previous name PHENIX DIGITAL LIMITED until 10 May 2023, advertising-agency SIC 73110. The filing history records a first compulsory strike-off Gazette notice 21 May 2024, followed by suspension 11 June 2024. These are records for a separate UK incorporation, not evidence of a strike-off or other filing by BVI Gamifi Limited 2082070. No positive connection to gamifi.gg/GMI/BVI 2082070 was identified.

   - https://find-and-update.company-information.service.gov.uk/company/07703903.
   - https://find-and-update.company-information.service.gov.uk/company/07703903/filing-history. Retrieved via click after initial direct opens failed.

4. **SEC EDGAR:** the public full-text-search interface opened, but the retrieved page did not expose query-specific results. Therefore, no completed native EDGAR full-text database search is claimed. Indexed SEC searches did not identify a project match.

   - https://www.sec.gov/edgar/search/.

#### Web-index query coverage

Search engine 2 initial discovery:

- `site.sec.gov ("GamiFi" OR "gamifi.gg" OR "2082070")`
- `site.bvifsc.vg "Gamifi"`
- `site.fca.org.uk "Gamifi"`
- `site.find-and-update.company-information.service.gov.uk "GAMIFI"`

Search engine 1 verification and expansion:

- `"Gamifi" site:sec.gov`
- `"Gamifi" site:bvifsc.vg`
- `"Gamifi" site:fca.org.uk`
- `"Gamifi Limited" "filing"`
- `"Gamifi" site:find-and-update.company-information.service.gov.uk`
- `"Gamifi" site:osc.ca`
- `"gamifi.gg" site:sec.gov`
- `"Gamifi" site:lautorite.qc.ca`
- `"Gamifi" site:securities-administrators.ca`
- `"GamiFi" (filing OR regulator OR enforcement OR registration)` with 365-day recency filter; returned generic gamification false positives, not a verified recent project filing.
- `"gamifi.gg" (site:bvifsc.vg OR site:fca.org.uk OR site:osc.ca OR site:lautorite.qc.ca)`
- `"Gamifi" (site:sedarplus.ca OR site:sedar.com OR site:bcsc.bc.ca OR site:asc.ca)`
- `site:sec.gov "GamiFi Limited"`
- `site:bvifsc.vg "Gamifi" -gamification`
- `site:fca.org.uk "Gamifi" -gamification`
- `GamiFi` with separate domain filters for www.sec.gov, www.bvifsc.vg, www.fca.org.uk.
- `"Gamifi"` with combined domain filters osc.ca, lautorite.qc.ca, securities-administrators.ca, sedarplus.ca, bcsc.bc.ca, asc.ca.
- `"2082070" ("Gamifi" OR "Limited") (regulator OR sec OR fca OR filings)`
- `"2082070"` with combined domain filters sec.gov, bvifsc.vg, fca.org.uk, osc.ca, lautorite.qc.ca.
- `"93d8d25e3c9a847a5da79f79ecac89461feca846" (filing OR regulator OR enforcement OR registration)`
- `"GAMIFI SOLUTIONS LIMITED" "filing history" "Companies House"`
- `"07703903" "11 Jun 2024"` with Companies House domain filter.

Several searches returned broad fallback results or broken-word matches such as `gamifi-cation`. Such results were excluded. Name/domain queries did not produce a matched filing or alert on SEC, FCA, Ontario OSC, Quebec AMF, CSA, SEDAR/SEDAR+, BCSC, or Alberta ASC websites. Native Canadian registry/database searches were not completed; these were bounded web-index searches.

#### Other false positives excluded

- SEC search surfaced **Gamify, Inc.** Form C-AR 2019, a differently named US issuer. It is not a verified GamiFi project match: https://www.sec.gov/Archives/edgar/data/1730217/000173021719000001/Gamify_FormC-AR.pdf.
- Number-only 2082070 returned **Novae Syndicates Limited** on FCA register and share-count quantities in SEC documents. No relationship to Gamifi Limited was identified; raw-number coincidence is insufficient. FCA source: https://register.fca.org.uk/s/firm?id=001b000000MfJRPAA3 (direct retrieval exposed only a dynamic interface).
- Canadian Gamifi Inc. at gamifi.com, Indian GAMIFI Consulting Services, and Gamifi LLC app-development results were not treated as the BVI GMI issuer.

No payments, account creation, outgoing requests, subscriptions, or monitoring were performed.

