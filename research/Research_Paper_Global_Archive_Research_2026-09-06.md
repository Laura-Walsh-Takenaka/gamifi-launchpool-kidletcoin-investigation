# Research Paper — global and archival evidence expansion

**Historical edition.** Findings and access descriptions are dated to the research date shown. This public edition is limited to crypto-related research. Later evidence supersedes some earlier gaps: the 7 September ShibaFriend claims review records repayment to all 23 non-dust original funding addresses, with 168 BUSD base units of unmatched dust; the later Mystery Box review records matching project contributions for all 194 paid mints. These narrow results do not settle every wider claim or identify a human wallet controller. Consult the repository README for the latest report precedence before quoting an earlier unresolved finding. Source URLs, transaction hashes and archive dates remain the research locators; historical local file locators below are not assertions that those working files are distributed unchanged.

**Report ID:** RESEARCH-GLOBAL-ARCHIVE-2026-0906  
**Date:** 6 September 2026 UTC  
**Scope:** A deeper second pass across 53 crypto-related evidence gaps, covering jurisdictions and archive services.

This pass recovered original historical documents and reconstructed additional transactions. It changes the earlier account in material ways: the staking pools received substantial later replenishments, an exact membership-control sequence is now dated, and public-source gaps in the MEXC interview and NEM reserve mapping have been closed at the document level. Human authorization, customer entitlement and final bank receipt remain separate questions.

## The findings that change the investigation

1. **46,020,000 GMI was replenished into the two staking pools on 15–17 May 2023.** Six consecutive transactions from `0x949040eedb2abecc0b9d2558a6d22d9724eaea88` sent 30,010,000 GMI to the 23m-November-source pool and 16,010,000 GMI to the 7m-source pool. The completed matching-inflow window is precisely bounded to 10–18 May; it is not a complete lifetime history. A 6m top-up restored the smaller pool's backing against recorded principal at its block. The larger remained short **15,531,357.317956608042669419 GMI** after its final listed top-up. Rewards remain unquantified.
2. **Two additional membership-control transfers are now exact.** On 28 April 2022, control moved from the original token-deployer address to `0x14cc…b412`; on 19 September 2022 at 09:51:41 UTC it moved onward to `0xf27…c27b`. Receipts, transfer inputs, events and adjacent states agree. The archived app additionally shows the account-wallet and participation record relationships its client was designed to use. Neither finding identifies a human signer.
3. **Historical offering records are now recoverable in full.** The original February 2022 MEXC publisher page and August staking announcement were obtained. Cross-venue Shibafriend notices preserve specific changes that can be compared with GamiFi's cancellation; they do not establish GamiFi refunds.
4. **The Cayman/overseas corporate trail has new identifiers and documents.** Alphabit's Cayman company **WC-319009** can be joined to its LEI/name history and historical fund-licence records. Portugal preserves October 2021 Launchpool terms. Seychelles records add Yield's company number, a strike-off event and a later court listing, without establishing a GamiFi customer account.
5. **NEM's missing reserve mapping is recovered.** The historical report maps three NIS sources into **125 Symbol addresses**. A July 2019 archive also attaches the historical label **Gemdealer** to the exact KID issuer. That is a pseudonym lead, not a civil identity or proof of uninterrupted custody. Government and university records add positive institutional-delivery evidence.
6. **A separate MegaFans sale now has reconciled payment-token outcomes.** Successful receipts establish **6,025 USDT deposited = 5,000 USDT refunded + 1,025 USDT withdrawn to the sale-owner wallet**. The proceeds withdrawal occurred on **1 July 2024**. This is the Launchblock venue, separate from Republic and from GamiFi; it does not identify the human owner or later spending. Historical tokenomics, policy-wrapper and staking documents were recovered.
7. **Kidlet's historical infrastructure is more concrete.** A January 2019 WARC response identifies a server IP, and an actual certificate valid during the contest names mail/webmail and hosting-control subdomains. These do not prove inbox use, entries, parental consent or prize payment.

## Geographic and archive coverage

| Region / archive | What actually produced evidence | Main limit |
|---|---|---|
| Portugal / Europe — Arquivo.pt | Earlier Launchpool terms; GamiFi team pages and app resources; Kaskade and NEM captures | Capture location does not establish company or customer residence. Redirect/error captures were not treated as substantive pages. |
| United States — Internet Archive, Common Crawl, IRS and RECAP | MEXC and project publications, historical infrastructure, NEM reserve report, an original tax filing and a court order | A filing or publisher statement is not proof of a specific GamiFi payment. Incomplete/truncated captures are identified. |
| Cayman, BVI, Gibraltar, UK and UAE | GLEIF/CIMA historical identity joins, UK incorporation, earlier published operator terms and regulator records | Executed agreements and shareholder/custody records remain missing. Unrelated historical proceedings are not evidence of GamiFi misconduct. |
| Seychelles / African legal archives | Yield gazettes, company/status history and an official court listing | Court scheduling is not a merits judgment or confirmation that a hearing occurred. |
| Malaysia, Philippines, Thailand, Japan, Hong Kong and Korea | Government/university statements, original regional interviews, issuer notices and a company-release translation | Syndication and citation chains are identified; repeated publicity is not repeated independent verification. |
| Public software, certificate and blockchain records | Exact contract state/receipts, archived client data models, CT certificates, source provenance and WARC headers | Technical roles do not identify humans; public code and certificates do not demonstrate actual use or retained private records. |

No search was represented as exhaustive of every country's records or every archive collection. Alternative indexes were used adaptively when ordinary search or replay failed. Successful records, bounded no-matches, redirects, rate limits and other errors are distinguished in the acquisition records.

## Evidence standard and corrections

- The later replenishments are included alongside the November withdrawals. A replenishment is not automatically a refund to an individual, and current backing cannot erase a historical shortfall.
- The two staking addresses are paired with the recovered advertised products by matching start, duration, rates, cap and cooldown. This is an explicitly labelled configuration inference; no recovered frontend object directly names those two addresses.
- The recovered NEM reserve table is a historical publisher dataset. Its arithmetic is reproduced separately from a fresh chain audit, which is still outstanding.
- Later US Symbol Syndicate finances are separate from the older Singapore Foundation. A historical account label, corporate-services biography or archive location does not establish beneficial ownership or personal receipt.
- No human GamiFi signing-key holder, private 120m beneficiary, credited MEXC customer, final FixedFloat payout, Cayman bank receipt or Laura personal receipt was newly identified. No message, purchase, registry application or private-account access was undertaken.

Verification reproduced selected staking replenishment states and arithmetic, the two membership-owner transitions and archived code extracts, the MegaFans payment reconciliation, the NEM table sums, and selected original PDF pages. All blockchain re-queries used the same public RPC provider, so these checks are not independent-provider corroboration.

## Detailed research chapters


---

## Human control: additional dated handovers and archived account architecture

Research date: 6 September 2026 UTC. This chapter extends EV-001–EV-007 and overlaps the paid-NFT and customer-record questions. The original signing-key, beneficiary, exchange-customer and bank-receipt gaps are retained. Two newly reconstructed ownership transactions and newly examined archived application code add concrete evidence; they do not identify a human signer.

### 1. Two additional membership-contract handovers are verified

The September 2022 archived application names membership NFT contract **`0x0be0e13c828b60b53d7577651cc54581855f7bad`**. A fresh historical call to the original project contract **`0x56c0cb2d047b69278f49b4759c1718436a546c7f`**, at the block of the 23 March 2022 project-ID-4 withdrawal, independently returns that same membership address from `memberCard()`. This connects the archived membership component to the actual original project contract at a material date. The earlier frontend used another member-card address; this finding does not collapse the two deployments. [HG01–HG02]

The membership proxy's `owner()` changes are supported by successful transaction receipts, standard ownership-transfer events, transaction input and adjacent-block state reads:

| UTC | Block | Previous owner and transaction sender | New owner | Transaction |
|---|---:|---|---|---|
| **28 April 2022, 10:46:31** | **17,337,174** | `0x0d2c8df71c846d0dbc9c8bc75ea39c45d5197dca` | `0x14ccacd699287c1b6ad07fd911394a05d802b412` | `0x91937205fa3f52aca3d6e7c7553570f34755149831a7da2b5a0d9f1ac4baa750` |
| **19 September 2022, 09:51:41** | **21,464,912** | `0x14ccacd699287c1b6ad07fd911394a05d802b412` | `0xf27f9a2eb9b2c70d32476cf9dc2d74ca4e61c27b` | `0x8f7d2470e42dba573f54f13754764a253b7e274d6bf040c8baba616afe60c6fb` |

The earlier sender is the original GMI token deployer already distinguished in the baseline from vesting/NFT deployer `0x3e0f…7199`. The intervening owner `0x14cc…b412` is an additional custody target. The September recipient is the already investigated `0xf27…c27b` owner. The September event precedes the separately established Safe-owner change at 14:24:11 that day by **4 hours 32 minutes 30 seconds**. Temporal proximity does not identify a common human or establish that the transactions shared an instruction. [HG03–HG04; prior authority schedule]

The two exact transitions are verified events. Binary searches located sampled state crossings; this is not a complete census excluding all other historical ownership changes or intermediate upgrades.

### 2. Membership state is now pinned at two dates

| Observation | 23 March 2022, 14:58:07 UTC | 6 September 2026, 15:10:14 UTC |
|---|---|---|
| Block | 16,311,927 | 120,324,101 |
| Block hash | `0xec2c6344451210a8e20c981c49c495cc8c4eac560e8936227affb21c3dd0e6df` | `0x35dd633867a0eaa3c1ece866725d8690093f039503ab98c06c0cb701f76b598d` |
| `totalSupply()` result | 100 | 100 |
| `owner()` result | `0x0d2c8df71c846d0dbc9c8bc75ea39c45d5197dca` | `0xf27f9a2eb9b2c70d32476cf9dc2d74ca4e61c27b` |
| EIP-1967 implementation slot | `0xf4c95885a11b4e3bd9dbc0ae5b179e3f22e0a369` | Same address |

The historical `name()` response decodes to **GamiFi RPG**. These are contract responses at specified blocks. Equal supply or implementation at two points does not demonstrate an unchanged intervening history, 100 paid purchases, 100 distinct customers, or completed membership benefits. [HG02, HG05]

The prior source-only `MemberCard.sol` treasury match to the ID-4 recipient remains qualified. Direct Sourcify lookups for this proxy and its implementation returned 404, and direct BscScan page retrieval returned 403. This pass has not verified a byte-for-byte match between the earlier repository treasury code and the historical implementation. It therefore does not upgrade that source-code treasury lead into a verified historical payee role.

### 3. The archived app shows how accounts, wallets and participation were linked

Newly examined modules in the previously preserved **21 September 2022** application bundle show these client operations: [HG01]

| Archived operation | Exact record structure visible in the code | Evidential use |
|---|---|---|
| Register an account | Firebase email/password account creation, followed by `updateUserMeta({walletaddress: …})` | Code was designed to associate a registered account with its submitted wallet address. |
| Save user metadata | `usermeta/{uid}`, adding `useruuid` to the metadata | Supplies the account-to-wallet record structure to reconcile against authenticated exports, if retained. |
| Retrieve project participation | `usermeta/{uid}/projectRecords`, filtering `funded == true` and `staked == true` | Identifies separate application participation indicators. These are not independently verified payments or blockchain receipts. |
| Track NFT information | `nftdata/{uid}`, with `uses`, `tokenIndex`, `series`, `uri`, `created` and `updated` fields | Supplies a specific off-chain NFT usage/index record to compare with token ownership, activation and benefits. |
| Check wallet registration | A configured cloud-function URL under project `gamifi-ffc78`, named `checkForWalletAddress` | Identifies a deployment namespace; no customer lookup was performed. |

The configured function URL contains `us-central1`. That identifies the regional endpoint named by the frontend, not the storage region of every database, a person's operating location or proof the service successfully ran on a particular day. Firebase/Google infrastructure does not establish Google as the controller of GamiFi's customer data.

The supplied archive was inspected as public client code. No database was queried, no login was attempted, and no private customer record or cloud-function response was accessed. The code shows designed record relationships, not that every user completed them or that the records still exist. In particular, it does not show that the private 120m-GMI beneficiary ever registered in this app.

### 4. What this changes in the original seven gaps

| Gap | New result | Remaining decisive evidence |
|---|---|---|
| EV-001 — custody and instructions | Two additional exact owner changes and an intermediate owner wallet; direct on-chain chronology improved. | Dated human assignments, authorizing instructions, delegation and handover acknowledgements. |
| EV-002 — 120m beneficiary | An archived general account-wallet data model is now documented; no beneficiary match obtained. | Identity, entitlement and agreement for the exact beneficiary. |
| EV-003 — MEXC customer credits/trades/withdrawals | No new customer ledger. The original MEXC AMA was recovered in the fundraising lane; it is a separate publication record. | Historical customer mapping and settlement for the four prior deposits. |
| EV-004 — FixedFloat historical payout | No new order match. | Historical custody confirmation and authenticated input/order/payout-or-refund mapping. |
| EV-005 — onward ownership and purpose | The blockchain chapter adds actual later inflows and subsequent onward-wallet activity. No human attribution. | Ownership, instructions and commercial purpose for each relevant wallet and transfer. |
| EV-006 — Cayman bank or personal receipt | No identified bank account or receipt. | An actual bank/off-ramp leg and matched account/settlement evidence. |
| EV-007 — project withdrawals | Membership component linked to the original project contract at the ID-4 withdrawal block. | Commercial identities for IDs 1/3/4 and actual entitlement/settlement for all seven withdrawals. |

### Sources and reproduction

- **HG01:** previously supplied archive capture, newly examined modules: https://web.archive.org/web/20220921100142id_/https://app.gamifi.gg/_nuxt/c2c9d04.js . SHA-256 `b5c7871c8d74618c740cfefeb3c261a563073c7cba8420b1a17fa73779750cd4`. Exact extracted contexts and character offsets: *Historical file: frontend_account_nft_extracts.json*. The archive URL and source hash identify the original selected bundle for reproducing the extraction.
- **HG02:** fresh RPC historical state at block 16,311,927 and the prior project-ID-4 transaction: https://bscscan.com/tx/0x33f6c2ae7893cf8763b5306d4220780592390cc22ab9399034f4b3ac6ee09683 . Transaction/receipt and request-response bytes are preserved.
- **HG03:** April ownership transaction: https://bscscan.com/tx/0x91937205fa3f52aca3d6e7c7553570f34755149831a7da2b5a0d9f1ac4baa750 . Receipt, transaction, event, adjacent states and header are preserved.
- **HG04:** September ownership transaction: https://bscscan.com/tx/0x8f7d2470e42dba573f54f13754764a253b7e274d6bf040c8baba616afe60c6fb . Same evidence types preserved.
- **HG05:** fresh pinned observation block 120,324,101, hash shown above; `eth_call`, `eth_getStorageAt` and `eth_getBlockByNumber` responses in `human_raw/`.

All new chain reads used the public endpoint `https://docs-demo.bsc.quiknode.pro/`. They are not independent-provider corroboration. The script records full JSON-RPC requests, responses and retrieval timestamps. Exact-address searches supplied no authenticated human attribution for the newly observed owner; the replenisher's rich-list appearance was treated only as a secondary locator and checked against chain state in the blockchain lane. Repository and explorer retrieval failures were not treated as absence of records.


---

## Corporate trail: deeper international and archive research

Research date: 6 September 2026 UTC. This pass extends *Historical file: corporate.md*, the prior Launchpool ownership memorandum and the GamiFi master. It searched European archives, Cayman identity datasets, Dubai regulatory records, Seychelles gazettes and court records, Panama Spanish-language indexes, BVI notices and US court archives. Findings below are new documents or independent captures; existing facts are expressly marked as corroboration.

### 1. Cayman: an exact Alphabit company identifier and a dated name-history record

The native GLEIF response identifies **Alphabit Fund I**, **LEI 213800NZCHTWXWVPWO96**, with Cayman General Registry identifier **WC-319009**. It explicitly records **Alphabit Digital Currency Fund** as its previous legal name. This is substantially more precise than linking similarly named funds or relying on the 2018 Form D alone. [CG01]

The full GLEIF field-change response contains **76 entries**. A **25 September 2019** entry changes the recorded legal name from ALPHABIT DIGITAL CURRENCY FUND to Alphabit Fund I. This dates the database update; the legal effective date of the name change still requires the registry certificate. Its parent-reporting exception is **NON_CONSOLIDATING**, which supplies no beneficial-owner identity. The entity field remains ACTIVE, while its LEI is LAPSED, with its latest record update in March 2022. A current golden-copy date does not convert those stale fields into a current certificate of good standing. [CG01]

**Effect on EV-014:** the historic Form D issuer now has a much stronger company-identity bridge and exact Cayman record target. Executed management agreements, investor subscriptions, GamiFi allocations and settlement remain unlocated. The identity bridge supplies neither a Cayman bank account nor a receipt by Laura.

CIMA's actual **31 December 2017** fund list, page 8, records **Alphabit Digital Currency Fund**, licence **1449685**, as a Master Fund with licence date **22 November 2017**; **Alphabit Digital Currency Fund II**, licence **1450105**, is Registered with licence date **6 December 2017**. Its **30 June 2021** list, page 10, retains these numbers and dates under **Alphabit Fund I** and **Alphabit Fund II**. The 2021 list was already cited in the prior memorandum; the newly recovered 2017 list supplies the historical name-to-number join. Both pages were visually checked. These are fund-licence identifiers, distinct from the company number and LEI. [CG26–CG27]

### 2. Portugal: independent Launchpool terms preserved before the previously emphasized January 2022 capture

Arquivo.pt returned seven capture records for the Launchpool terms URL. Two have recorded HTTP 200 status and their original-file replay bodies were retrieved:

| Portuguese archive capture | Page's printed revision date | Recorded contracting name |
|---|---|---|
| **19 October 2021, 07:59:25 UTC** | **13 January 2021** | Launch Pool Limited; described as registered under Virgin Islands law |
| **1 February 2022, 20:10:17 UTC** | **10 November 2021** | Same contracting description |

The October capture is an earlier independent historical document. Both pages identify that entity as the token issuer. They contain a Virgin Islands arbitration seat and a UK governing-law reference. Neither displays a company number. [CG02–CG03]

The **13 January 2021 printed revision date precedes the candidate BVI Launchpool Ltd incorporation date of 12 February 2021** supplied by the commercial directory in the prior report. This is a specific identity/dating ambiguity: a template date, another contracting entity, or an inaccurate date remain possible. The archive establishes what the page displayed by October; it does not establish publication on 13 January or prove that BVI 2054898 was the contracting company. [CG02; prior C5]

**Effect on EV-009 and EV-015:** stronger contemporaneous published-operator evidence, but still no UK/offshore shareholding agreement, BVI certificate linking the website issuer, or transfer/novation to Carajo. Capture metadata retains WARC filenames, offsets, digests and HTTP status, so these pages can be independently located outside the Internet Archive. The five other capture records include redirects or HTTP 403/503 responses and were not counted as substantive terms.

### 3. Portugal: the official homepage independently corroborates the CEO transition

Retrieved GamiFi homepage captures identify Laura Walsh as CEO on **26 January, 1 February and 3 May 2022**. Captures on **7 September 2022** and **23 January 2024** identify **Eleanor Rooney** as CEO in the team section. This corroborates the already-preserved 1 September 2022 succession announcement through another archival institution. [CG04]

The September and January pages retain older podcast text calling Laura CEO while the actual team panel names Eleanor. A text search that finds Laura's old title in those pages would therefore be an unreliable way to date her current office. None of these public biographies provides a bank mandate, token entitlement, signing-key custody record or handover acknowledgement. **EV-016 remains open.**

### 4. Seychelles and African legal archives: Yield's exact entity, creditor process and a newly located strike-off notice

The new gazette documents identify **Yield App Limited, Seychelles company 229095**:

| Instrument | Documentary finding | What it does not supply |
|---|---|---|
| Gazette No. 42, **5 August 2024**, notice **806/2024** | Notice dated 25 July identifies Cork/Chilton and commencement of insolvent winding-up effective **1 July 2024**. [CG05] | A GamiFi or Launchpool account mapping. |
| Gazette No. 44, **19 August 2024**, notice **864/2024**, printed p584 | Creditor meeting scheduled **29 August 2024, 11:00 UK time** to receive a liquidator report, ratify appointments and establish a creditors' committee. [CG06] | Attendance, voting outcomes or the resulting committee membership. |
| Gazette No. 71, **16 December 2024**, notice **1305/2024**, printed p816 | Intended first interim distribution; proof-of-debt bar date **20 December 2024**; notice says known creditors had received claim-access instructions on 29 October. [CG07] | Actual distribution receipts, claimant names or the company's customer ledger. |
| Gazette No. 7, **3 February 2026**, printed **p123 / PDF p38** | **229095 — Yield App Limited — struck-off date 21 December 2025.** The notice begins on printed p119 under **s272(4)** and is labelled **No. 120 of 2025** in the original, despite appearing in a 2026 Gazette. [CG08] | A conclusion that liquidation or creditor claims ended. |

The last row is a **new status-history document**, visually verified against the page image. The source's notice-number anomaly is preserved rather than silently corrected. The later official court list for **9 March 2026** still lists **Stephen Cork and Hadley Chilton as Yield's joint liquidators**, in **SPC-00-CV-MA-0247-2025**, arising from **SPC-00-CV-CC-0071-2025**, against Jason Corbett, Justin Wright, Tim Frost, James Sutherland, Lucas Kiely and Unifi Group Ltd. It lists Bernard Georges for the liquidators and a submissions hearing before Judge N. Burian. [CG09]

The gazette and court chronology should be retained together. Strike-off is a recorded event; the March listing is evidence of a scheduled proceeding, not a merits decision or proof the scheduled hearing occurred. A restoration instrument or later status certificate was not located.

**Effect on EV-017:** there are now actual published legal-process documents, a precise Seychelles entity number, a dated creditor-record trail and an exact court-file identifier. An actual GamiFi/Launchpool customer engagement still has not been established.

#### The failed judgment link was investigated further

The old SeyLII AKN address for **Cork & Anor v Corbett & Ors [2025] SCSC 126** returned 404 locally. The current SeyLII homepage states that it is transitioning platforms and auditing its collection. Its newly discovered native search was therefore used rather than stopping at the broken link. A search for the exact phrase Yield App returned **four gazettes**, including the previously unlocated February 2026 strike-off record. A separate Corbett search returned five other documents but not the sought judgment. [CG10]

A third-party automated summary describes the July 2025 matter as permission to serve an alleged wrongful/fraudulent-trading petition abroad. The original judgment was not obtained; that summary is retained only as a retrieval lead, **not adopted as a verified merits finding**. Likewise, the liquidators' December 2025 account of the separate commingled-assets ruling is a first-party summary, not a substitute for the full judgment. [CG11–CG12]

### 5. Jersey, Scotland, UAE and UK: a personnel bridge for the Cavenwell enquiry

NetZero Capital's own biography identifies **Neil Rankin** as a partner, former Alphabit operations participant and founder of Cavenwell Limited. This is a new first-party personnel link; it is not an employment contract or an identification of GamiFi's corporate-services provider. [CG13]

A newly retrieved UK incorporation document identifies **CAVENWELL (UK) LIMITED, 17062233**, incorporated **2 March 2026**. Its initial share schedule gives **Andrew Horbury 100 ordinary £1 shares**, with £0 paid and £1 unpaid per share. It records Horbury as the initial PSC with at least 75% of shares/votes. The current officer list includes Horbury, Christopher Mayfield, Neil Rankin and Chris Usher, all appointed on incorporation. [CG14–CG16]

This identifies a further current legal entity omitted from the earlier provider's group-entity list, and a professional contact whose published history crosses Alphabit and Cavenwell. The UK entity's **2026 incorporation cannot identify the legal provider for 2021–2022 work**. No engagement letter, registered-agent appointment, invoice, client instruction or payment tying Cavenwell to GamiFi was found.

### 6. Dubai: the manager has a precise regulatory identity and an actual tribunal record

DFSA's register identifies **Dalma Capital Management Limited, F002345**, licensed **20 March 2014**. This is the exact name shown as Alphabit's investment manager in the prior 2018 SEC filing. It gives a separate regulator-held record trail for checking historical authorized activities and individuals. [CG17; prior C12]

The regulator publishes a **31 January 2023 Financial Markets Tribunal decision, FMT 21019 / FMT 21020**, and a 7 February release. The majority upheld findings that Dalma and Zachary Cefaratti misled the regulator about trading during April–June **2016**; each fine was reduced to **US$162,500**. The tribunal rejected the allegation that the trader's lack of qualifications/experience had been proved. **This concerned the Dalma Unified Return Fund, not GamiFi, Launchpool or an identified Alphabit investment.** It cannot establish misconduct by Laura or conduct in the 2022 GMI transfers. The original regulator decision notice was locally recovered; the final tribunal PDF was readable through web retrieval but local download was forbidden. [CG18–CG20]

### 7. United States: identified sworn-document targets, with the actual dismissal preserved

The **SDNY Barron / Helbiz / micromobility.com case, 1:20-cv-04703**, contains two docketed declarations by **Liam Robertson** for Alphabit: **document 191, 27 July 2022**, and **document 222, 14 October 2022**. These are promising corporate-identity/authority sources because they are dated declarations by an Alphabit principal. Their full text was not freely recovered in this pass. [CG21]

The Internet Archive's RECAP collection supplied the actual **document 244** order. It grants Alphabit's dismissal motion in full; the court found that the plaintiffs had not shown personal jurisdiction over Alphabit. This adverse disposition is material and must accompany any reference to the lawsuit. It supplies **no finding of wrongdoing by Alphabit in GamiFi**. The collection's JSON docket was last modified in **2020** and omits the two 2022 declarations, despite the collection containing later PDFs; it must not be described as a complete current docket. [CG22–CG23]

### 8. A recovered September 2017 information memorandum, with a provenance limit

A 49-page Alphabit-branded **Information Memorandum**, dated **September 2017** and numbered **EFTA00797613–EFTA00797661**, was recovered from two public mirrors with identical SHA-256 hashes. Its structure and directory pages identify **Dalma Capital Management Limited** as investment manager, **Alphabit Ltd** as investment adviser, **Apex Fund Services (Dubai) Ltd** as administrator, **Grant Thornton Cayman Islands** as auditor, and **Walkers (Dubai) LLP** as legal adviser limited to Cayman law. The adviser is listed at a Cayman corporate-services address. The document describes an open-ended fund with a $100,000 minimum initial subscription. These pages were visually checked. [CG25]

The mirror's stated DOJ original redirected to age verification; the original PDF was **not** obtained there, so government-copy provenance remains unconfirmed. The recovered document is a historical representation of roles, **not an executed management, administration or GamiFi investment agreement**, an audit opinion, or proof of actual performance. Its September date and CIMA-registration language should be reconciled with the official master-fund licence date in November; a dated cover alone does not establish when the version was finalized or circulated. Only this bounded corporate summary and acquisition metadata are packaged. [CG25–CG27]

### Bounded searches that produced no new matching record

Exact-name/number and variant searches were made for Gamifi 2082070, candidate Launchpool 2054898, Linford 1943018 / 1943021, SCR Advisors / SCR Advisers in Gibraltar, and Asociados Carajo 155733022. Spanish queries included Panama's official Gazette and judiciary domains. No newly retrieved agent/owner record, share register, restoration instrument or authorization for Carajo's 2025 changes resulted. A commercial Carajo profile corroborates the supplied folio and officer names and adds RUC **155733022-2-2023**, but it is not an official tax certificate or shareholder disclosure. [CG24]

No-match web searches are bounded index results, not searches of every country's complete registry. UK, BVI, Cayman, Panama, Gibraltar and Seychelles corporate/legal identities remain separate. No paid report, creditor login, registry application, message or legal request was submitted.

### Preservation and source register

`corporate_sources.json` contains URLs, publication/capture dates, new-versus-prior descriptions, limits and raw acquisition status. *Historical file: acquisition_*.json* records successful downloads and failures with hashes. *Historical file: PACKAGE_SELECTION.json* identifies a safe, focused subset for the consolidated package.

Selected evidence includes GLEIF raw records and their full field history; Portuguese capture metadata and concise derived findings; the rendered Seychelles strike-off page and its notice header; and a derived Cavenwell incorporation/PSC extract. Full publisher webpages and unrelated personal details from registry/gazette pages are not needed in the deliverable. Exact original source hashes remain in the acquisition register. A saved full document does not mean its contents were exhaustively reviewed.

| Code | Source / exact locator |
|---|---|
| CG01 | https://api.gleif.org/api/v1/lei-records/213800NZCHTWXWVPWO96 ; `/field-modifications?page%5Bsize%5D=100` ; `/direct-parent-reporting-exception` |
| CG02 | https://arquivo.pt/noFrame/replay/20211019075925id_/https://launchpool.xyz/terms-conditions/ |
| CG03 | https://arquivo.pt/noFrame/replay/20220201201017id_/https://launchpool.xyz/terms-conditions/ |
| CG04 | https://arquivo.pt/textsearch?versionHistory=gamifi.gg&maxItems=50 ; replay timestamps 20220126074129, 20220201190558, 20220503173716, 20220907174004, 20240123205624 |
| CG05 | https://archive.gazettes.africa/archive/sc/2024/sc-government-gazette-dated-2024-08-05-no-42.pdf ; original: https://www.gazette.sc/sites/default/files/2024-08/Gazette%20No%2042%20-%205th%20August%202024_0.pdf |
| CG06 | https://www.seylii.org/seylii/gz/en/601/1/document.do ; Gazette 44, 19 August 2024, p584 |
| CG07 | https://www.gazette.sc/sites/default/files/2024-12/Gazette%20No%2071%20-16th%20December%202024_0.pdf ; p816 |
| CG08 | https://www.seylii.org/seylii/gz/en/2993/1/document.do ; Gazette 7, 3 February 2026, pp119/123 |
| CG09 | https://www.judiciary.sc/wp-content/uploads/2026/03/supreme-court-civil-9-13-march.pdf ; p1 |
| CG10 | https://www.seylii.org/seylii/en/nav.do?iframe=true ; https://www.seylii.org/seylii/en/a/s/index.do?cont=%22Yield+App%22&iframe=true |
| CG11 | https://www.jibudocs.com/public/summaries/e4172205-1bdc-8e5a-ff07-fc6d97fd276d ; automated-summary lead only |
| CG12 | https://corkgully.com/yield-app-liquidation-commingled-cryptoassets/ ; 9 December 2025 first-party summary |
| CG13 | https://netzero.capital/neilrankin |
| CG14 | https://find-and-update.company-information.service.gov.uk/company/17062233/filing-history/MzUwNzUxMDgwNWFkaXF6a2N4/document?download=1&format=pdf |
| CG15 | https://find-and-update.company-information.service.gov.uk/company/17062233/persons-with-significant-control |
| CG16 | https://find-and-update.company-information.service.gov.uk/company/17062233/officers |
| CG17 | https://www.dfsa.ae/public-register/firms/dalma-capital-management-limited |
| CG18 | https://www.dfsa.ae/download_file/3344/0 ; FMT 21019 / 21020, 31 January 2023 |
| CG19 | https://www.dfsa.ae/news/financial-markets-tribunal-upheld-dfsa-decision-dalma-capital-management-limited-and-zachary-cefaratti-misled-dfsa |
| CG20 | https://365343652932-web-server-storage.s3.eu-west-2.amazonaws.com/files/4616/7576/2121/Decision_Notice_Dalma_080322_Redacted_2.pdf ; original 19 October 2021 decision notice, later varied |
| CG21 | https://dockets.justia.com/docket/new-york/nysdce/1%3A2020cv04703/538913 ; entries 191 and 222 |
| CG22 | https://archive.org/download/gov.uscourts.nysd.538913/gov.uscourts.nysd.538913.244.0.pdf |
| CG23 | https://archive.org/metadata/gov.uscourts.nysd.538913 ; https://archive.org/download/gov.uscourts.nysd.538913/gov.uscourts.nysd.538913.docket.json |
| CG24 | https://persono.io/apps/profiles/892bdf35e500ae7597c4eb418de6a1ff ; commercial corroboration only |

The main unresolved ownership and human-control questions remain unresolved. This pass adds a Cayman entity/name history, an earlier independent operator archive, dated CEO-page corroboration, a Seychelles company/status/court chronology, a new corporate-services personnel bridge and precise sworn-document targets.

| CG25 | Mirror PDF: https://assets.getkino.com/documents/EFTA00797613.pdf ; identical mirror: https://bitcoinprotocol.org/epstein-bitcoin-emails/files/EFTA00797613.pdf ; stated original (PDF not obtained): https://www.justice.gov/epstein/files/DataSet%209/EFTA00797613.pdf ; internal pages 3–4 / PDF pages 4–5 / Bates EFTA00797616–17 |
| CG26 | https://www.cima.ky/upimages/commonfiles/QuarterlyListofallMutualFundsregisteredandlicensedwiththeCaymanIslandsMonetaryAuthority_1516037823.pdf ; updated 31 December 2017, p8 |
| CG27 | https://www.cima.ky/upimages/commonfiles/QuarterlyListofallMutualFundsregisteredandlicensedwiththeCaymanIslandsMonetaryAuthority-30June2021_1625765870.pdf ; updated 30 June 2021, p10 ; already cited in prior memorandum |


---

## GamiFi — international archives, sales representations and hosted-project outcomes

Research cut-off: 6 September 2026, UTC. This is a second research pass after the initial 53-item report. It covers EV-018–EV-028. It uses newly retrieved archive payloads and additional publisher/launchpad records, not just new search routes or prospective record requests.

**Three substantive advances:** the original MEXC interview has now been recovered from a capture made minutes after publication; a contemporaneous August 2022 announcement gives the terms of the two later staking pools; and other launchpads preserve specific Shibafriend vesting and exchange-lock changes around GamiFi's cancellation. Portugal's Arquivo.pt supplies an independent archive route for dated GamiFi pages. These findings establish published statements and chronology. They do not supply private receipts or prove refund completion.

### 1. Previously missing MEXC original recovered

**The indexed-only access limitation is resolved.** The earliest located Wayback capture is **23 February 2022, 10:25:42 UTC**, 8 minutes 58 seconds after the HTML's reported publication time. An October 1 capture was also retrieved. These are publisher records, not a new transcription of the AMA. [F01–F02]

MEXC attributes to Laura: legal documents must be signed/submitted before the first-project announcement; NFT access still involves first-come purchasing; private, Launchpool strategic and January public raises occurred; PeckShield audited the token. It attributes to Casey that the team retained final decisions. Both captures preserve those material passages; differences found are editorial. Capture hashes, byte counts and publication/modification metadata are in the source register.

**EV-024 moves from open to narrowed.** The diligence-to-announcement sequence is now testable against subsequent announcements and actual executed documents. The archive does not supply private publication approval, signed agreements, receipts or the audit report.

### 2. The August staking offer is now recovered

GamiFi's **23 August 2022** article announced two pools opening on **24 August at approximately 12:00 GMT**. The Wayback capture is **23 August 2022, 11:15:56 UTC**, predating the scheduled launch. Its embedded publication timestamp is **2022-08-23T02:17:47.377Z**. [F03]

| Published product term | Nine-month pool | Twelve-month pool |
|---|---:|---:|
| Advertised APY | 75% | 100% |
| Maximum individual stake | 2,500,000 GMI | 2,500,000 GMI |
| Rewards access | Withdrawable at any time, subject to a 24-hour cooldown | Same |

The announcement gives **no contract addresses**. It therefore supplies a contemporaneous offer to compare with deployments, without by itself proving which address implemented which product. The two examined depletion sources are `0xee57b1241f243a1a794f60ffa643d202188d31d9` and `0xba306306b117a25145d58c67a03deb7f22ee2a3a`; the blockchain chapter must supply the independent configuration match. In particular, an advertised APY is not automatically an accurate description of the contract's simple reward formula or its funded reserves.

This is distinct from the earlier Mystery Box NFT pools, whose announcement describes NFT-dependent access and individual nine-month lock periods. Applying the Mystery Box terms to the ordinary two-pool announcement would combine separate products. [F03–F04]

I also pursued a direct frontend address-to-product bridge. Neither address appears in the prior app capture set or the twelve additional January 2024 application JavaScript resources retrieved from Arquivo.pt. The earlier staking page references lazy-loaded assets including `2984e41.js`, `4249918.js`, `63ad768.js` and `08b1c6e.js`. Selected absent chunks returned no Wayback index entries or replay 404s. This is a bounded retrieval limitation, not a claim that the website never displayed the addresses.

### 3. Shibafriend's changing release terms have independent platform records

GamiFi's 29 June cancellation notice was already in the investigation. It said changes to tokenomics and release timing prevented timely individual contact and contract revision, and offered private-allocation tokens plus 1,000 GMI or a refund. This pass found specific contemporaneous changes published by **other offering venues**, with exact post identifiers. They strengthen the factual context for that notice, while remaining separate from GamiFi customer settlement. [F05–F08]

| Source / date represented | Published terms or change | Evidential boundary |
|---|---|---|
| Gagarin Launchpad, 7 June 2022 | SHF public price $0.0054; 18% at TGE; remainder released in equal portions at the second and third months; text gives 10bn supply. | An external venue's published offer, not proof of GamiFi's accepted buyer terms. |
| KingdomStarter, post **1386**, listing-day notice referring to 30 June | 30% TGE, then 35% twice; launchpad Coinstore deposits locked seven days, then half released, unrestricted by 14 July. First Coinstore IEO round: 100% TGE. | Different cohorts had different stated restrictions. Post is marked edited; a complete edit history was not recovered. |
| KingdomStarter, post **1389**, forwarding a notice attributed to **Norman T** | No Coinstore lock; 1bn supply; $0.0054 price; claims 30 June 09:00 UTC, one hour after listing. | Displayed forwarded attribution, not civil identity or verified exchange unlocks. |
| KingdomStarter, post **1393**, July claiming schedule | Lists a 35% SHF tranche for **30 July 2022, 09:00 UTC**. | Scheduled claim, not verified payout; reconcile its month terminology. |

The tenfold difference in published supply and the 18%-to-30% TGE change are now specific discrepancies to reconcile. They are not an amount of money lost. Post 1389's lock reversal must be kept alongside the earlier lock notice; citing only the more restrictive version would misrepresent the recovered sequence.

GamiFi's own June 9 offering details are also accessible: whitelist blocks **18,535,600–18,650,800**; funding blocks **18,684,400–18,766,000**; June 30 listing target. The notice linked users to app accounts and mentioned RPG NFT access. Those block numbers identify the published funding window for comparison with project ID 9's actual `Funding` and withdrawal records. This research did not newly enumerate those customer transactions. [F09]

**Positive counterparty evidence:** HYPE Sports Innovation's own **1 June 2022** article names and links ShibaFriend among startups addressing sports-brand audience challenges. This independently supports a public association with HYPE. It does not verify the broader claims of signed agreements with every football federation, sports organizer or broadcaster, nor the completion of their pilots. The Gagarin and exchange texts largely repeat project promotional descriptions and must not be counted as independent confirmation of each commercial engagement. [F10]

### 4. Korean publication and named publication contact

A **2 March 2022** Korean Newswire release explicitly identifies **GamiFi as the news provider** and links to Business Wire release **20220228005415**. It repeats the GAMI first-IDO proposal: $100,000 / 1m tokens at $0.10, March 11–14, and access for Golden Ticket holders. It names **Chris Smith** as the release contact. This recovers an additional international publication location and a specific publication trail for EV-024/EV-028. It does not establish a Korean purchaser, a Korean operating office, or Chris's approval of every GamiFi statement. [F11]

The page explicitly labels itself a translation and directs readers to the original for authoritative wording. It is **one syndicated company announcement**, not another independently verified raise. Its $100,000 proposal is already part of the earlier report's $150,000/$100,000/$50,000 display history; finding a Korean copy does not make a new amount disappear.

### 5. Independent European archive captures and limits

Portugal's **Arquivo.pt** supplied 14 indexed homepage records, including redirects, spanning January 2022–October 2025. Three 200-status original homepage payloads were newly retrieved: [F12–F14]

- **1 February 2022, 19:05:58 UTC:** Laura Walsh displayed as CEO; Casey as PM. Footer displays PeckShield audit branding.
- **3 May 2022, 17:37:16 UTC:** Laura still displayed as CEO; Casey as VP Operations. Footer still links the audit branding to PeckShield's general homepage.
- **7 September 2022, 17:40:04 UTC:** Eleanor Rooney displayed as CEO. An older episode-33 teaser still names Laura as CEO, illustrating why a retained older article teaser cannot override the then-current team section.

These independently preserved pages reinforce the already-known replacement chronology. They provide no signing mandate or wallet handover. The footer hyperlink is to the auditor's homepage, **not a downloadable audit report**.

Arquivo.pt also yielded **38 indexed app resources** in January 2024 and twelve JavaScript payloads. Common Crawl indexes **CC-MAIN-2022-40** and **CC-MAIN-2023-14** returned app HTML records. The sampled **2022-49** and **2023-06** indexes returned 503 errors; they were not treated as empty. A targeted MEXC lookup in **2022-21** returned no capture. An Arquivo MEXC exact-URL lookup returned no results, while its broad full-text query timed out. Actual successful retrievals and failures are separated in the manifests.

A further litepaper index comparison recovered only the already-known November 2021/January 2022 `/gamifi-litepaper.pdf` payloads and the October 2022 `/litepaper.pdf` payload. The latter was already documented as truncated at 1,048,576 bytes against a declared 1,992,736-byte file. No newly complete version or changed financing schedule was obtained. The targeted Arquivo PDF wildcard lookup returned zero results; this does not establish archive-wide absence.

The PeckShield public-reports repository tree was newly pinned at **37558e095a7c82c9f4f8db4a84af313ed5eba67c**, 498 entries, `truncated:false`. A filename/path search found no GamiFi report; the ShibaNova report is unrelated. A missing filename in this one public repository cannot disprove a private engagement. [F15]

### 6. Effect on the eleven original evidence gaps

| Gap | Result of this deeper pass |
|---|---|
| EV-018 — fundraising receipts/use of proceeds | Still open. The newly recovered MEXC full text reports types of raises, not their actual receipts or expenses. |
| EV-019 — accepted buyer prices/terms | Further narrowed by the staking announcement and external SHF offer versions; individual acceptance remains unproved. |
| EV-020 — Shibafriend/FOMO outcomes | Further narrowed for SHF changes and scheduled releases. No GamiFi refund completion recovered. FOMO's original sale, relaunch and legacy migration remain separate cohorts. |
| EV-021 — paid NFT access versus delivered benefits | Full MEXC record now preserves the first-come purchase qualification. Payment/activation/use reconciliation remains necessary. |
| EV-022 — mint/burn/reserves | No new complete reserve/mint ledger in this lane. The earlier code accounting findings remain controlling. |
| EV-023 — staking deposits/rewards | New contemporaneous 75%/100% offers, maximum stake and 24-hour reward cooldown; use alongside the blockchain chapter's configuration and liability evidence. |
| EV-024 — statements/approval/knowledge | **Open → narrowed.** Original MEXC publisher record recovered and compared with later capture. Private approvals and signed documents remain missing. |
| EV-025 — buyer reliance/unrecovered exposure | Still open. External public announcements do not establish an individual purchaser's reliance or net loss. |
| EV-026 — game/integration delivery | HYPE independently confirms a public ShibaFriend association; the individual branded-pilot completions remain unverified. |
| EV-027 — audit/deployment sign-off | Audit representation is now stronger as a dated statement; report and audited deployment scope remain unverified. |
| EV-028 — material-date locations | Korean publication reach and dated European archive captures recovered. Reader location is not buyer residence or operating jurisdiction. |

### Primary sources and archive references

- **F01:** https://web.archive.org/web/20220223102542id_/https://blog.mexc.com/mexc-ama-gamefi-session-with-laura-and-casey/
- **F02:** https://web.archive.org/web/20221001232638id_/https://blog.mexc.com/mexc-ama-gamefi-session-with-laura-and-casey/
- **F03:** https://web.archive.org/web/20220823111556id_/https://gamifi-launchpad.medium.com/new-staking-pools-a931ff7dfd6a
- **F04:** https://gamifi-launchpad.medium.com/gamifi-mystery-box-nfts-2840e0eb885e — separate Mystery Box product.
- **F05:** https://gamifi-launchpad.medium.com/shibafriend-ido-announcement-e57f229783f7 — prior cancellation baseline, rechecked.
- **F06:** https://medium.com/@GAGARIN.World/shibafriend-nft-sport-a-groundbreaking-sports-metaverse-b4bb12192cc4
- **F07:** https://t.me/kdg_ann/1386 and readable context https://t.me/s/kdg_ann/1391
- **F08:** https://t.me/kdg_ann/1389 and https://t.me/kdg_ann/1393 — both readable in the same context page. Linked original group-post ID: https://t.me/Shibafriend_official/217128 . Its original body was not independently recovered.
- **F09:** https://gamifi-launchpad.medium.com/shibafriend-ido-details-e0e165279b8e
- **F10:** https://www.hypesportsinnovation.com/sports-brands-we-feel-you-pain-points/
- **F11:** https://www.newswire.co.kr/newsRead.php?no=940310 ; linked original https://www.businesswire.com/news/home/20220228005415/en/
- **F12:** https://arquivo.pt/noFrame/replay/20220201190558id_/https://gamifi.gg/
- **F13:** https://arquivo.pt/noFrame/replay/20220503173716id_/https://gamifi.gg/
- **F14:** https://arquivo.pt/noFrame/replay/20220907174004id_/https://gamifi.gg/
- **F15:** https://api.github.com/repos/peckshield/publications/git/trees/37558e095a7c82c9f4f8db4a84af313ed5eba67c?recursive=1

The source manifest records archive indexes, response status, original/replay URLs and capture hashes. Full newly downloaded copyrighted publication bodies are research working copies, not included as republished articles in the deliverable. The deliverable uses summaries, exact identifiers and retrieval receipts. No publisher, project, purchaser, exchange or auditor was contacted, and no paid lookup was used.


---

## Blockchain reconstruction — deeper historical follow-up

Research date: 6 September 2026. BNB Smart Chain, chain ID 56. This chapter adds fresh historical RPC evidence to EV-029–EV-032. Every amount below is a token quantity, not a dollar-loss estimate. Full contract addresses and exact base units are retained in the accompanying JSON records.

### New finding: a previously unmapped large holder replenished both staking pools

Wallet **`0x949040eedb2abecc0b9d2558a6d22d9724eaea88`** sent **46,020,000 GMI** into the two staking pools on **15 and 17 May 2023**. These are six successful, direct calls to the GMI token’s `transfer(address,uint256)` function, occupying the sender’s consecutive transaction nonces **19–24**. Transaction inputs, GMI Transfer logs and successful receipts agree on every amount and destination.

This is actual token replenishment. The sampled large top-ups increased pool balances without increasing recorded staking principal; they were not new customer stakes. The wallet’s human owners, key custodians, legal entitlement and payment instructions remain unidentified.

| Pool | Contract | GMI received in the completed window |
|---|---|---:|
| 23m November source | `0xee57b1241f243a1a794f60ffa643d202188d31d9` | 30,010,000 |
| 7m November source | `0xba306306b117a25145d58c67a03deb7f22ee2a3a` | 16,010,000 |

| UTC | Recipient | Sender nonce | GMI | Transaction |
|---|---|---:|---:|---|
| 2023-05-15 11:25:43 | 7m source | 19 | 10,000 | [0x6e0db2525a74e2ba12ea62314bcad717efc45431ee7765fde8cffcfa9aa3c02b](https://bscscan.com/tx/0x6e0db2525a74e2ba12ea62314bcad717efc45431ee7765fde8cffcfa9aa3c02b) |
| 2023-05-15 11:27:22 | 7m source | 20 | 10,000,000 | [0xab96d82c3b50d3baa63a047b3e32b3a59e3bd970d8ef4a8bfa708d97d15f58e1](https://bscscan.com/tx/0xab96d82c3b50d3baa63a047b3e32b3a59e3bd970d8ef4a8bfa708d97d15f58e1) |
| 2023-05-15 11:28:40 | 23m source | 21 | 10,000 | [0x818c2d86968e175c6b34d4a880a99817a120454c15b8eae077f476e4f5219d81](https://bscscan.com/tx/0x818c2d86968e175c6b34d4a880a99817a120454c15b8eae077f476e4f5219d81) |
| 2023-05-15 11:29:52 | 23m source | 22 | 20,000,000 | [0xf655c6539b2402a64d74d10926f5dcc12bce358df3e27487c9bcab4f16204609](https://bscscan.com/tx/0xf655c6539b2402a64d74d10926f5dcc12bce358df3e27487c9bcab4f16204609) |
| 2023-05-17 12:56:39 | 7m source | 23 | 6,000,000 | [0x8cfcb8af2c5d104f1448071c5ecdc157d178cf1a2b055883358263ce9192edba](https://bscscan.com/tx/0x8cfcb8af2c5d104f1448071c5ecdc157d178cf1a2b055883358263ce9192edba) |
| 2023-05-17 13:01:23 | 23m source | 24 | 10,000,000 | [0x7bd805885cff3dadd62c190a919f7349bbb5821e1e3d0d927ad1e47e1d6726f5](https://bscscan.com/tx/0x7bd805885cff3dadd62c190a919f7349bbb5821e1e3d0d927ad1e47e1d6726f5) |

**Completed scope:** 23 consecutive successful `eth_getLogs` queries, each covering 10,000 blocks, exhaust the requested GMI Transfer-to filter from **block 28,090,000 (2023-05-10T14:03:00+00:00) through block 28,319,999 (2023-05-18T14:02:32+00:00)**, inclusive. The three destination filters were the two pools and Launchpool vesting proxy `0xf50488dc8339fb7d1d5a8e8b401c4a5d71a090bb`. The six listed transfers are all returned matching inflows in that window. Launchpool had **zero matching incoming GMI Transfer events in this window**.

The sender’s nonce sequence additionally establishes an uninterrupted six-transaction normal-outgoing segment for that address, from its first listed 10,000-GMI payment to its final listed 10m-GMI payment. It does not cover earlier or later transactions, incoming activity, third-party allowance-driven movements, or any other token. Calling the small initial payments “tests” would describe a plausible purpose rather than an established instruction, so the table records their amounts without assigning that purpose.

### How the replenishments changed backing

The verified StakingV3 implementation records outstanding principal through `_stakedAmount`. The accounting test used here is **actual GMI balance minus recorded principal**. New stakes increase both sides; a direct top-up increases the balance while leaving principal unchanged. Pending rewards are outside this principal-only comparison.

| Observation | Recorded principal, GMI | Actual balance, GMI | Principal shortfall, GMI |
|---|---:|---:|---:|
| 7m source 15 May 10m top-up, before, block 28,230,642 | 12896605.839068300731575844 | 189228.582279753411083506 | 12707377.256788547320492338 |
| 7m source 15 May 10m top-up, after, block 28,230,643 | 12896605.839068300731575844 | 10189228.582279753411083506 | 2707377.256788547320492338 |
| 7m source 17 May 6m top-up, before, block 28,289,920 | 5266931.543878876011679844 | 1668788.099285494103872403 | 3598143.444593381907807441 |
| 7m source 17 May 6m top-up, after, block 28,289,921 | 5266931.543878876011679844 | 7668788.099285494103872403 | 0 |
| 23m source 17 May 10m top-up, before, block 28,290,014 | 26044430.6709624340201061 | 513073.353005825977436681 | 25531357.317956608042669419 |
| 23m source 17 May 10m top-up, after, block 28,290,015 | 26044430.6709624340201061 | 10513073.353005825977436681 | 15531357.317956608042669419 |

On **17 May 2023 at 12:56:39 UTC**, the 6m-GMI payment changed the 7m-source pool from a **3,598,143.444593381907807441-GMI principal shortfall** to a **2,401,856.555406618092192559-GMI balance surplus over principal**. This identifies a particular replenishment that restored backing of the recorded principal counter at that block. It does not establish payment to every user or settlement of all rewards.

The other pool remained short by **15,531,357.317956608042669419 GMI** after its 17 May 10m top-up. The previous pass’s pinned September 2026 principal shortfall, **13,857,766.118460738573556824 GMI**, remains the sampled later state. The 30.01m received during this May window therefore cannot be described as full settlement of that pool’s recorded obligations.

### The pools grew substantially after the November withdrawals

Fresh historical calls show that the single previously identified post-withdrawal stake was part of a much larger change in recorded principal. These are selected dated snapshots, not a maximum-balance claim or a complete per-user ledger.

| UTC / block | Pool | Recorded principal, GMI | Balance, GMI | Principal shortfall, GMI |
|---|---|---:|---:|---:|
| 2022-11-05 06:45:09 / 22,786,456 | 23m source | 24044801.4386227977295061 | 291908.907982630011309744 | 23752892.530640167718196356 |
| 2022-11-05 06:45:09 / 22,786,456 | 7m source | 6789496.100023061372341 | 74012.180365341193990997 | 6715483.919657720178350003 |
| 2023-04-15 02:54:54 / 27,358,066 | 23m source | 91452676.5554947088098761 | 57749690.183363900575130927 | 33702986.372130808234745173 |
| 2023-04-15 02:54:54 / 27,358,066 | 7m source | 38255327.845678916229575844 | 28882580.066690851182531561 | 9372747.778988065047044283 |
| 2023-05-11 15:05:20 / 28,120,001 | 23m source | 48960057.9134003359586061 | 6161082.005004557264358969 | 42798975.908395778694247131 |
| 2023-05-11 15:05:20 / 28,120,001 | 7m source | 17260437.018456090231575844 | 5187695.461377318496472962 | 12072741.557078771735102882 |

At the two later historical snapshots in this table, fresh EIP-1967 implementation-slot reads identify the same verified **StakingV3** implementation, `0x4e9fcbbbca286a5be04bdfc9a7f7babb43253e55`. The source records a successful stake by increasing principal and a successful unstake by decreasing it. The additional observations therefore establish much larger recorded principal exposure after November, but this pass has not independently enumerated the contributing users, all deposits, all reward claims or every temporary implementation change.

At **15 April 2023 02:54:54 UTC**, principal was **91,452,676.5554947088098761 GMI** in the 23m-source pool and **38,255,327.845678916229575844 GMI** in the 7m-source pool. At **11 May 2023 15:05:20 UTC**, their principal shortfalls were **42,798,975.908395778694247131 GMI** and **12,072,741.557078771735102882 GMI**. These May observations follow the already-recorded 9 May owner transactions that shortened both pools and removed the subsequent-request delay.

The observations do not prove the exact causes of every intervening worsening or improvement. In particular, token rewards paid from the same asset can reduce backing without reducing principal, and full claim receipts are still needed to reconcile that effect.

### The replenisher was a substantial holder before November

Fresh historical and pinned balance calls for `0x949040eedb2abecc0b9d2558a6d22d9724eaea88` give:

| Block / observation | GMI balance |
|---|---:|
| 22,786,455, completed block immediately before the November withdrawal | 295,429,687.025769235288817275 |
| 28,090,000, 10 May 2023 14:03:00 UTC | 295,429,687.025769235288817275 |
| 120,314,156, 6 September 2026 13:55:39 UTC | 232,134,226.025769235288817275 |

This connects a large pre-existing GMI holder to the subsequent replenishment transactions. The identical two historical endpoint balances do not prove inactivity between them. The current nonce is **44** at the pinned block, while the six listed replenishments occupy nonces 19–24. Earlier funding, other spending and human/entity ownership remain new concrete tracing targets. A balance is not evidence that the holder owed it to particular customers.

### Historical settings match the newly recovered public pool announcement

The fundraising lane recovered an issuer announcement dated 23 August 2022 describing 75%/nine-month and 100%/twelve-month pools, a 2.5m-GMI per-wallet limit, and a 24-hour rewards claim cooldown. The following historical contract settings independently support that pairing. This is an **inference from matching configuration**, not a recovered frontend object explicitly naming each address.

| Historical setting, block 22,786,455 | 23m-source pool ee57…31d9 | 7m-source pool ba30…2a3a |
|---|---:|---:|
| Start UTC | 24 August 2022 12:00:00 | 24 August 2022 12:00:00 |
| Duration seconds | 31,104,000 | 23,328,000 |
| Duration days | 360 | 270 |
| Rate stored | 31,709,791,984 | 23,782,343,987 |
| Calculated simple annual rate, 365-day year | 100.0000000007424% | 74.9999999974032% |
| Maximum principal per wallet, GMI | 2,500,000 | 2,500,000 |
| Pending claim/unstake request delay, seconds | 86,400 | 86,400 |

The source formula is `principal × elapsed seconds × rate ÷ 10^18`, capped at the configured end time. `claim()` transfers rewards to the claimant and does not automatically add them to principal. The contract therefore implements simple elapsed-time reward accrual. The announcement’s APY terminology and the implementation’s lack of automatic compounding should be kept distinct when reproducing the terms buyers saw. The configured 360/270-day terms also should not be silently replaced by calendar-year/month arithmetic. The fresh maximum-principal calls use selector `0x86f95007`, independently derived by `web3_sha3` and matching the Sourcify signature record. The earlier historical rate/start/duration/delay responses are carried forward as clearly marked reference records.

### Three more outgoing transactions from the prior onward wallet

Wallet `0xf4f86e37815217ed73ae817a4e5164d56315b1d7` previously had a bounded receipt inventory ending at nonce 73. New nonce-crossing locators, complete block responses and receipts establish:

| UTC | Nonce | Verified action | Transaction |
|---|---:|---|---|
| 16 May 2023 09:56:44 | 74 | Successful unlimited BUSD approval to router `0x1a1ec25dc08e98e5e93f1104b5e5cdd298707d31` | [0xa21fc15ded26cb6733c3a1bf87f2672004c2014c071c2ffdc2e2f1f28a9cfbd5](https://bscscan.com/tx/0xa21fc15ded26cb6733c3a1bf87f2672004c2014c071c2ffdc2e2f1f28a9cfbd5) |
| 16 May 2023 09:56:44 | 75 | Successful swap: 789 BUSD left this wallet; 782.5799104396268 USDT returned to it | [0xda4db44df3a0c3594726fbcb884e1c07285c0ecea8836d481fabaa5a4de2ab57](https://bscscan.com/tx/0xda4db44df3a0c3594726fbcb884e1c07285c0ecea8836d481fabaa5a4de2ab57) |
| 4 August 2025 15:10:30 | 213 | Successful transaction to the same router, with 80.613025103197438517 USDT leaving this wallet through a swap route | [0xd02df3dfdf4c471e0a3ad35ee6dd8326545cff5b293dbd703efa64e2b50be5b2](https://bscscan.com/tx/0xd02df3dfdf4c471e0a3ad35ee6dd8326545cff5b293dbd703efa64e2b50be5b2) |

The first two transactions share block **28,257,569** and raise the sender’s nonce count from 74 to 76. The final selected transaction is in block **56,429,586**, raising it from 213 to 214. The pinned September 2026 nonce remains 214. This extends confirmed outgoing activity to August 2025 and adds the next contiguous two transactions after the old boundary. The middle nonces 76–212 and earlier activity remain outside this receipt inventory. Incoming transfers and allowance-driven transfers can occur without increasing this wallet’s outgoing nonce.

The 2023 receipt also identifies the intermediate router executor `0xc590175e458b83680867afd273527ff58f74c02b`, trading counterparty `0x2008b6c3d07b061a84f790c035c2f6dc11a0be70`, and 5.86227 BUSD sent to `0xb28da7bc87a9dd1e60849aa7fcb5da24ea913c42`. Those are contract/transaction counterparties; none is being identified here as a human final beneficiary. The 2025 transaction includes a WBNB conversion route, but this pass does not report an exact final native-BNB receipt without an internal-call trace. The amounts are commingled wallet activity and cannot all be assigned to GamiFi proceeds.

### What this resolves and what remains

| Gap | New evidence | Remaining boundary |
|---|---|---|
| EV-029, complete Launchpool intervening movements and control | A complete 230,000-block GMI-inflow segment finds no Launchpool receipts while identifying the two staking pools’ replenishment sequence | Full lifetime Launchpool in/out inventory, claims, control changes and offsetting movements remain open |
| EV-030, broader wallet histories | New replenisher with six consecutive verified outgoing transactions and three balance observations; three added onward-wallet transactions, including August 2025 activity | Replenisher upstream funding and remaining transactions; other onward nonces, allowance transfers, native internal transfers and human ownership remain open |
| EV-031, source-contract obligations and controls | Larger dated principal exposure, exact 46.02m-GMI replenishment sequence, one specific restoration of principal backing, and historical pool-terms comparison | Per-user principal and reward reconciliation, all top-ups outside the completed window, all upgrades/settings and contractual entitlement remain open |
| EV-032, trading/liquidity before manipulation assessment | Two new selected swap receipts from an onward wallet | Complete relevant GMI market/liquidity histories and centralized order records remain open; these swaps do not establish manipulation |

### Reproduction, provenance and limitations

New raw records are under `blockchain_raw/`. Every successful RPC record contains the endpoint, request parameters, retrieval timestamp and full response. The principal acquisition endpoint is `https://docs-demo.bsc.quiknode.pro/`; all queried blocks are explicit. Source code and older parameter calls reused from the preceding investigation are prefixed `prior_reference_` and listed in `reused_source_provenance.json`. They are not described as freshly acquired here.

The completed inflow window is independently checked by `build_results.py`: 23 contiguous ranges, no missing result arrays, six unique logs, six successful matching receipts, matching transfer calldata, consecutive sender nonces, and exact integer sums. Its `decoded_*.json` outputs retain the arithmetic. Adjacent-state top-up checks compare both balance and principal. New implementation-slot responses connect the April/May observations to the previously verified StakingV3 source.

The initial replenishment locator used binary subdivision of balance-minus-principal and then verified the located adjacent-block event. Because that quantity can rise and fall, the locator does not prove a first-ever replenishment. The later full May-window scan is what establishes complete matching inflows within the stated interval. The nonce locators use the account nonce and verify actual sender transactions in the crossing blocks, rather than calling every nonce increment a token payment.

Some requests received HTTP 429 and were subsequently retried with reduced concurrency. All 23 ranges used in the completed window ultimately returned successful result lists. A retained response may also contain a preceding retry error; the successful response is the basis for inclusion. No missing or failed request is being treated as an empty result. No transaction was signed or submitted, and no private customer or bank record was acquired.

Primary source navigation:

- Verified StakingV3 source and deployment metadata: https://sourcify.dev/server/v2/contract/56/0x4e9fcbbbca286a5be04bdfc9a7f7babb43253e55?fields=all
- Public StakingV3 source: https://github.com/sheandev/gamifiContracts/blob/main/contracts/StakingV3.sol
- GMI token: https://bscscan.com/token/0x93d8d25e3c9a847a5da79f79ecac89461feca846
- Newly traced replenisher: https://bscscan.com/address/0x949040eedb2abecc0b9d2558a6d22d9724eaea88
- Chain RPC documentation: https://docs.bnbchain.org/bnb-smart-chain/developers/json_rpc/json-rpc-endpoint/

Explorer links provide navigation. The fresh transaction findings rely on retained RPC inputs, logs and receipts, not on successful explorer-page retrieval.


---

## KidletCoin: deeper regional and archive research

Research date: 6 September 2026 UTC. Scope: EV-033–EV-037. This pass extends the earlier KidletCoin report through certificate-transparency records, Common Crawl WARC data, Wayback, Arquivo.pt, public source-code indexes, and Thai, Japanese, Chinese and international institutional publications. The substantial new result is historical web and mail-related infrastructure evidence. No contest submissions, private child data, inboxes or live administrative interfaces were accessed.

### New historical infrastructure records

#### 1. An original 2019 Common Crawl record identifies the website's server IP

A recovered WARC response records `https://kidlet.io/` at **2019-01-23 00:42:41 UTC**, with **`WARC-IP-Address: 162.241.252.29`**. The server answered as Apache with HTTP 406 and a Mod_Security rejection. This is direct historical infrastructure evidence, even though the crawler did not receive the homepage. It is **not a recovered privacy notice or successful website session**. The WARC payload digest was independently recomputed and matches its stored SHA-1. [KD01–KD02]

Exact acquisition identifiers:

| Field | Value |
|---|---|
| Common Crawl index | `CC-MAIN-2019-04` |
| Capture timestamp | `20190123004241` |
| WARC record ID | `e42a7083-9b44-4870-871b-ce51492b74cc` |
| WARC object | `crawl-data/CC-MAIN-2019-04/segments/1547583879117.74/crawldiagnostics/CC-MAIN-20190123003356-20190123025356-00192.warc.gz` |
| Compressed byte range | `16556837–16557481`, 645 bytes |
| Compressed record SHA-256 | `108389334fe907fd7caaab8e9b7780d4dfec6f6fd2b2ae04ac0cf5ce3414332f` |
| Payload SHA-1, base32 | `DXI2LRHAQOJGQSZF3D3M7V6WOC25TW4Z` |

Fresh primary ARIN data maps that IP into `UNIFIEDLAYER-NETWORK-16`, allocation `NET-162-240-0-0-1`, with registrant handle `BLUEH-2`, Unified Layer. Current reverse DNS returns **`box5680.bluehost.com`**. These are present-day records: the IP allocation was last changed in July 2026 and the registrant object in July 2025. Combining them with the original 2019 WARC produces a concrete **Bluehost/Unified Layer historical hosting-account lead**. It does not by itself identify the 2019 contracting company, physical server location, account holder or mail provider. [KD03–KD04]

The useful record target is now specific: the account serving `kidlet.io` on `162.241.252.29` at the pinned 2019 timestamp, together with its domain aliases, customer/billing record, historical DNS/MX configuration, site backups and cPanel/mail provisioning logs. Provider records would need to establish whether the website and the project's published submission mailbox used the same service. A web-server IP is not an MX record.

#### 2. A certificate spans the June 2019 contest and names historical mail services

The certificate-transparency query returned **345 observations**, representing **196 distinct issuer/serial pairs** after deduplication. Of those, **28 pairs** contain the recurring mail/cPanel hostname set. The earliest begins on **15 October 2018**; the latest begins on **21 April 2023**. These are bounded observations from this response, not a claim to every certificate ever issued. [KD05]

The actual certificate bytes for the interval covering the advertised June 2019 contest were retrieved and independently parsed with OpenSSL:

| Field | Certificate covering the contest period |
|---|---|
| crt.sh record | `1394242687` |
| Subject | `CN=kidlet.io` |
| Issuer | Let's Encrypt Authority X3 |
| Not before | **17 April 2019, 15:11:11 UTC** |
| Not after | **16 July 2019, 15:11:11 UTC** |
| Serial | `03808A09E1FB9CE098C0A87730CBA713C87F` |
| DER certificate SHA-256 fingerprint | `C64D61F37E8C63086B2ADE36A03AE64D797EEC6D292BB51B945EA209B91F0930` |
| Retrieved file SHA-256 | `1a8944601be32ff9aadcfa71b305a461ddcaaae46e1d61ccb6996857b2f77777` |

Its Subject Alternative Names include `kidlet.io`, `www.kidlet.io`, **`mail.kidlet.io`**, **`webmail.kidlet.io`**, **`autodiscover.kidlet.io`**, `cpanel.kidlet.io` and `webdisk.kidlet.io`. The October 2018 certificate was also downloaded and parsed; it names the same seven hosts. [KD06–KD07]

This moves the record beyond a generic submission email: mail-related and hosting-control names were included in a domain certificate valid during the contest's advertised period. A certificate can include automatically provisioned or unused hostnames. It does not prove that the project's published submission mailbox existed, received entries, supported a particular protocol, used that certificate, or had any particular access or retention settings. The certificate issuer is not identified as the mailbox provider. The checks parsed the certificates and matched their dates/names; they did not independently validate their signature chains.

#### 3. The certificate record adds a 2023 technical transition

The last observed certificate with the legacy mail/cPanel hostname set starts **21 April 2023** and expires **20 July 2023**. The first observed wildcard certificates for `*.kidlet.io` start **10 October 2023**, using Sectigo and Google Trust Services issuers. This is an additional dated change in the certificate footprint, preceding the previously recovered December 2023 unrelated subdomain content. [KD05]

It is not a proved ownership transfer, handover date or end of continuous service. A single operator can change hosting and certificates, and this certificate index may have gaps. It narrows the technical records needed to reconstruct the 2023 transition; it does not attribute the later content or access to any former project participant.

### Regional publications: what survives, and where the claims came from

These additional publications were inspected to look for named merchants, delivered products, adult operating roles and underlying records. They extend the publication history but do not supply entry registers, payouts, authenticated releases or merchant settlement.

| Region / record | Newly checked content and evidentiary use |
|---|---|
| Thailand: Beartai's original 4 July 2019 interview article | Describes future online-store partners and identifies the mother's NEM Country Head role. This supplies a further contemporaneous account of planned redemption. It does not name a completed merchant integration. [KD08] |
| Japan: BITTIMES item dated 2 December 2018 in the retrieved page | Explicitly derives the project account from NEM's official blog and treats the online store and additional educational-game rewards as future work. Its page also carries a 2025 update marker; that marker must not be used as a new project event. [KD09] |
| Hong Kong / traditional Chinese: Fortune Insight, 3 July 2019 | Describes an online shop to be established. This is regional reporting of the proposed product, without independently documented customer redemptions. [KD10] |
| UN institutional publication: *Youth Entrepreneurs Engaging in the Digital Economy* | The 2020 report mentions KidletCoin at printed pages 10 and 31. Footnote 14 links to Chris Skinner's July 2019 article, which credits e27. The recovered citation chain therefore leads back to the already known interview, not a UN product test. The Australian Government/Citi funding acknowledgement concerns the report; it is not a KidletCoin grant. [KD11–KD12] |
| International Baccalaureate, annual review for 2019/20 | A recovered **18 May 2021 Wayback capture** repeats the mother-assisted launch and online-spending claim, and links directly to the already known September 2019 IB feature. The English review calls the rewards bitcoins; that label conflicts with the known KID/NEM identity and cannot establish BTC payment. This is an independently dated publication capture, not independent verification of delivery. [KD13] |

The Beartai, Japanese and Chinese interpretations are working translations. No interview-video images or private entrants' media were collected. Other discovered reprints from Singapore, Europe and Brazil were treated as discovery leads; repeating the same promotional account across countries does not multiply the number of independent operating records.

### Archive and source-code searches performed

| Search surface | Outcome of this pass |
|---|---|
| Common Crawl, nineteen selected crawl indexes spanning 2018–2022 | One index returned the two January 2019 rejection records for homepage and robots.txt. The homepage WARC was recovered and verified. Other initial responses were eight no-capture responses and ten service errors; two of those errors became no-capture responses on a differently encoded retry. No archived policy or app binary was recovered. This was not a scan of every Common Crawl collection. |
| Wayback domain/subdomain CDX | Returned historical website resources and later subdomains. The 2021 and 2022 homepages reproduce the known project description; these are baseline rechecks, not newly discovered delivery evidence. A requested 2018 homepage redirected to the 2021 capture, and was not dated as 2018. |
| Wayback exact privacy path, educational-resources availability and historical Google Play package | No returned matching capture. This is an archive-query result, not proof that the pages or app never existed. |
| Wayback APKPure package path and mobile Twitter variant | Empty returned indexes. The mobile result replaces the prior timeout with an actual bounded response, but adds no contest result. |
| Arquivo.pt full text | Exact project-name search returns the previously known three records. Full-name search adds regional pages linking or referring to publicity, with no new operational record. Exact domain phrase and version-history requests return no matches. |
| Archive.org item metadata; Archive.today/indexed variants | No matching item metadata recovered. Direct Archive.is retrieval timed out; indexed searches supplied no usable snapshot. These are different search surfaces from Wayback and were not described as exhaustive. |
| GitHub and GitLab public project discovery | GitHub returned 29 `kidlet` name matches, including the known NEM wallet; GitLab returned 13 matches dominated by KDE KIdleTime and later unrelated shops. No additional project was authenticated as the historical quiz. Descriptions and names were screened; unrelated codebases were not comprehensively audited. |

### Effect on the five unresolved evidence items

| Gap | What this deeper pass adds | What remains unproved |
|---|---|---|
| **EV-033** — entries, selection and payment | Broader regional and archive search; no new award ledger. | Whether entries arrived, how selections were made, and which payments were prizes. |
| **EV-034** — consent, publication, mailbox access and retention | **Narrowed by new original infrastructure records:** the contest-period mail-host certificate plus a dated website IP and provider lead. | Inbox creation/use, parents' consent, publication authority, users/delegates/forwarders, historical MX, retention/deletion and actual records held. |
| **EV-035** — production binaries matched to reviewed source | Public repository discovery and exact archived package searches expanded. | Original signed APK/AAB/IPA, publisher, release record, matching commit, signing/build custody. |
| **EV-036** — quiz backend and merchant redemption | Additional regional statements and traced institutional citation chains. | Production backend, actual reward-event data, accepted merchant contracts, completed purchases and settlement. |
| **EV-037** — curriculum and channel/domain control | **Further narrowed:** dated certificates through 2023, October 2023 certificate-footprint change, and the 2019 IP record. | Commissioning, acceptance/payment, dated human account control and domain/mail/site handover. |

The exact infrastructure records are new. Previously established participant statements, wallet code defects, transaction totals and curriculum GitLab provenance are not relabelled as discoveries from this pass. The five compound gaps remain unresolved.

### Source register

- **KD01:** [Common Crawl January 2019 index](https://index.commoncrawl.org/CC-MAIN-2019-04-index?url=kidlet.io&matchType=domain&output=json). The `status` field is 406.
- **KD02:** [Original WARC object](https://data.commoncrawl.org/crawl-data/CC-MAIN-2019-04/segments/1547583879117.74/crawldiagnostics/CC-MAIN-20190123003356-20190123025356-00192.warc.gz), byte range specified above. Saved compressed/uncompressed record and digest verification are included.
- **KD03:** [ARIN IP record](https://rdap.arin.net/registry/ip/162.241.252.29), retrieved 6 September 2026. Current routing/registration context only.
- **KD04:** [Current reverse-DNS response](https://dns.google/resolve?name=29.252.241.162.in-addr.arpa&type=PTR).
- **KD05:** [Certificate-transparency query](https://crt.sh/?q=kidlet.io&output=json), saved with deduplicated certificate history.
- **KD06:** [Actual April 2019 certificate](https://crt.sh/?d=1394242687). Another observation, 1396411665, returned HTTP 502 for certificate download; the successful observation above was used.
- **KD07:** [Actual October 2018 certificate](https://crt.sh/?d=864035842).
- **KD08:** [Beartai original interview article](https://www.beartai.com/tech/336826), current redirect retained in retrieval context. 
- **KD09:** [BITTIMES article](https://bittimes.net/news/39389.html). 
- **KD10:** [Fortune Insight article](https://fortuneinsight.com/web/318355/). 
- **KD11:** [UNDP/UNCDF report on the UN APCICT host](https://www.unapcict.org/sites/default/files/2021-03/UNDP-RBAP-Youth-Entrepreneurs-Engaging-in-Digital-Economy-2020.pdf). ; relevant pages were extracted locally and footnote 14 read. Full PDF hash retained in provenance; full publication is not repackaged.
- **KD12:** [Skinner's attributed discussion](https://thefinanser.com/2019/07/the-10-year-old-who-runs-a-blockchain-company/), linking/crediting the known e27 interview. 
- **KD13:** [18 May 2021 archived IB annual review](https://web.archive.org/web/20210518085247id_/https://ibo.org/about-the-ib/facts-and-figures/ib-annual-review/year-in-review-2019-2020/impact/); [current primary page](https://www.ibo.org/about-the-ib/facts-and-figures/ib-annual-review/year-in-review-2019-2020/impact/),  Historical HTML hash and the original article target are retained in provenance; the full article is not repackaged.

`kidlet_sources.json` enumerates the permitted package files. Original certificate bytes, WARC data, public registry/index responses, derived facts and integrity checks are included. Full fresh publisher articles, unrelated search-result content and children’s photographs are excluded from the evidence selection.


---

## NEM: deeper international and archive research

Research date: 6 September 2026. Scope: EV-038–EV-045. This is an additional pass beyond *Historical file: nem.md*, using English, Malay, Thai, Japanese and German discovery queries; primary forum records; the Internet Archive; Portugal's Arquivo.pt; Common Crawl; Malaysian government and Philippine university publications; and an original US IRS filing. It does not reclassify the 21 previously indexed payments as newly reconstructed transactions.

### The new material

The most useful additions are **a historical pseudonym attached to the exact KID issuer, recovery of the lost Trust reserve mapping into 125 Symbol addresses, and original government/counterparty evidence of an earlier Malaysian deployment**. An IRS filing supplies a separate, later US organization record, with an explicit boundary against assuming it received the old Foundation's money.

#### 1. Exact issuer: a July 2019 archive supplies a historical pseudonym

The Internet Archive capture `20190721125710` of `https://nemnodes.org/topblocks/` contains this complete row:

| Field | Archived value |
|---|---|
| Address | `NC7HKOMA4N4ZCYJ7PXJPUGGQLSBLQL6S6LEFQHNZ` |
| Historical label | `Gemdealer - 1.0 - User Stake` |
| Row / harvested-block count | 188 / 2,128 |
| Displayed vested balance | 4,593,841.05 XEM |
| Table's stated last update | 19 July 2019, 01:57:56 UTC |
| Page's displayed time / block height | 21 July 2019, 12:57:09 UTC / 2,249,102 |

This is the same mixed-use issuer in the prior KID reconstruction. The present operator table retains the label, but its balance table is itself marked last updated January 2025; it must not be used as a live balance. The 2019 copy advances the lead beyond a label first observed in 2026. [ND-01]

The original NEM Bitcointalk subscription thread also contains January 27, 2014 posts by **Gemdealer**, including the stated Bitcoin payment hash `0f82e6ab178bf6ffa32e6cba30e590c685cda195da133f1563e2f46a20e55eba`. A follow-up says an additional amount was sent after another participant pointed out the subscription price increase. The forum page supports the account's historical subscription statement; this pass did not independently verify that Bitcoin transaction or obtain the original stake-redemption mapping. [ND-02]

**What changed:** there is now a specific historical handle and stake-origin record to test. **What remains:** no civil identity, 2018–2019 signing mandate, uninterrupted custody, or purchase/transfer of the original stake is established. Do not assign the handle to Laura, a developer, a family member or a gemstone business by inference. Other participants' quoted comments on the same Bitcointalk page are not Gemdealer's statements.

The archive download stopped at exactly **1,048,576 bytes** and lacks the document ending. The relevant row is complete and far before the cutoff. The package retains the extracted row, acquisition facts and hash of the partial source, not a claim that all 15,887 listed accounts were acquired.

#### 2. Europe: the lost reserve allocation report is recovered

The August 18, 2021 trustee statement identifies the **NEM Group Trust in Gibraltar**, lists five trustees, and directs readers to row 1 of a now-unavailable reserve report. It announces a proposed approximately 1.2 billion XEM / 770 million XYM award for a Swiss foundation. Crucially, the same thread contains Gimre's immediate disagreement and an August 20 statement that negotiations continued. The award must therefore remain a proposal, not an executed settlement. [ND-03]

The linked report was recovered at:

`https://web.archive.org/web/20210616173157id_/http://report.experimental.symboldev.network/`

The report says **generated March 30, 2021, 07:32:39 UTC**. Row 1 maps three NIS source accounts into **125 Symbol addresses**. All 125 address/amount pairs are transcribed in `archived_reserve_mapping_row1.json`. [ND-04]

| NIS source in archived row 1 | Displayed XEM |
|---|---:|
| `NATRUSTUAB5LAWDSOWDUPQUFYRTGZTJZDGML2JKP` | 1,424,848,818.491020 |
| `NANODESTSN7GU76QPLGMJ7BCGCAA2PHVBZZUUI62` | 18,983,656.691000 |
| `NBKXLNQ2GKTLQBTXNFOHULNJDA7T2Q57CZGQ2TFP` | 234,150,985.700000 |
| **Sum of displayed source figures** | **1,677,983,460.882020** |

The 125 displayed target allocations sum to **1,677,983,460.920000 XYM**. This arithmetic reproduces the archived table; it is not a fresh node audit or a statement of current reserves. The 0.037980 difference between displayed totals is left as a table-level reconciliation item. Decimal commas were converted to decimal points without changing digits.

**Important identity distinction:** the trustee announcement separately lists `NBLOCKYZLCBVO2XF2DB3D74AE2RC5WSHX5JEZOID` as the Symbol-block-rewards NIS account. That is **not** the third source displayed in the recovered March report. The two dated account lists must not be silently substituted for one another.

This closes the narrow task of recovering that particular missing public mapping table. It does **not** close EV-044: downstream spending, subsequent custody changes, Foundation-to-NGL legal transfers, and the actual Singapore liquidation beneficiary still require reconciliation.

A second European archive was tested successfully: **Arquivo.pt** preserved NEM's official about page on `20190413132709` and its blog index on `20200314202011`. These supply historical navigation/publication context. The exact foundation-page version-history query returned eight captures, all redirects, rather than a recovered signed constitution. **Common Crawl** returned 27 records for the report host in `CC-MAIN-2021-43`, 26 status-304 revisits and one status-404 record; they were not treated as independent content copies. [ND-05]

#### 3. A distinct US record is now in hand: Symbol Syndicate's Form 990

Following the later protocol reorganization led to an **IRS-hosted original 28-page Form 990 for The Symbol Syndicate**, EIN **88-0622815**, tax year 2022. The return identifies a Delaware corporation formed in 2022 and lists Kristy-Leigh A Minehan as President & CEO; its signature block is dated **November 17, 2025**. [ND-06]

| Filed figure, 2022 | USD |
|---|---:|
| Contributions and grants | 1,996,243 |
| Total revenue | 1,996,291 |
| Total expenses | 986,825 |
| Total year-end assets | 1,009,540 |
| Year-end liabilities | 74 |

Page 12 answers **No** to independent financial-statement compilation/review and to an independent audit. This is a filed tax return, not a signed audit of NEM.io Foundation. Pages 1, 7 and 12 were visually checked after rendering; OCR is an aid only and contains occasional digit errors elsewhere.

**Separation is mandatory:** the return does not identify the 12 SEA payments, nine issuer payments, their customers, or the Singapore liquidation beneficiary. It is not proof that the announced Swiss award was paid to this US organization. It is retained as an additional, distinct institutional record for the later reserve-governance branch. The older Singapore Foundation and later US organization are not treated as one entity.

A Japanese-language archived community account of the reorganization also points to proposed US, Bermuda and Swiss entities and changed multisignature custody. Because it is a translation and not the executed mandates or transaction receipts, it remains a discovery pointer. The report does not upgrade those planned custody arrangements into confirmed asset transfers. [ND-07]

#### 4. Malaysia: the government record advances and corrects the deployment chronology

The Malaysian ministry's **Malay-language release dated November 9, 2018** states that the e-Scroll system had launched and that IIUM's graduating PhD students would receive coded credentials at the November 10 convocation. It specifically identifies **NEM**, project lead **Prof Dato Dr Norbik Bashah Idris**, and the initial six-university consortium. This is direct government evidence predating the September 2019 date in the later IIUM Holdings newsletter used in the previous pass. The two dates should be recorded as different published milestones; the later retrospective date must not erase the earlier launch record. [ND-08]

LuxTag's **November 10, 2018** completion announcement says approximately **200 degrees** were issued at that day's IIUM ceremony. It describes a **consortium Catapult NEM blockchain**, names **Bekkai Amine Fatah** as development lead and **Elmi Haryadi** as project manager, and says the implementation took under three weeks. This is the implementer's completion claim, corroborated as to the rollout event and NEM technology by the ministry. It does not establish 200 independently inspected on-chain credentials, the contract price, Foundation invoices, or use of the public NIS1 chain. [ND-09]

The ministry's current copy notes an update on March 18, 2024, while its statement remains dated November 9, 2018. Thus it is a government-hosted historical statement read today, not yet an independently recovered unchanged November 2018 capture. Local direct downloads of the ministry and LPU pages returned 403; source reading succeeded through web retrieval, and no original-byte capture is claimed for those pages.

#### 5. Philippines: an institution confirms an actual course offering

LPU Manila's own 2023 account of its new agreement with The BLOKC states that its College of Technology offered a blockchain elective in **2018**, in partnership with **NEM Philippines, Inc.** It identifies the later BLOKC leadership as coming from that organization. This narrows the delivery question from an MOU alone to a university's retrospective statement of an offered course. [ND-10]

The statement does not establish specific enrollment/completion counts, payments, accreditation of the curriculum, or legal succession to the Singapore Foundation. In particular, it does not classify the selected SEA receipts as course funding.

#### 6. Governance: contemporary recognition of the Kidlet overlap, not a recovered approval

In the **November 20, 2018** Foundation election discussion, the participant `n3lz0n` explicitly mentions Laura's candidacy and her daughter's Kidlet project while discussing parallel business roles among Foundation candidates. This supplies a dated contemporaneous record that the overlap was being discussed publicly. It is **not** a signed conflict declaration or an independent approval for use of NEM money, staff or communications. The participant's separate USD 2,000 salary statement concerns himself; it must not be attributed to Laura or used to explain her selected wallet transfers. [ND-11]

A June 2019 response from `Inside_NEM` says proof of a roughly USD 20,000 initial customer payment, bank statements and partnership documents had been sent to the Core Team during a Q1 review, and says over 70 worldwide MOUs/contracts had been compiled and legally reviewed. These remain management statements about specific underlying records. They do not authenticate the missing documents or reconcile the 21 target payments. [ND-12]

The 2019 NEM Ventures governance publication links three distinct legal documents: NEM Holdings articles, NEM Community Trust deeds, and a declaration of trust. All three direct public downloads returned 404. The source publication remains the locator for the three linked documents. The first exact-URL Wayback check returned no snapshot. This negative result is bounded and is not proof that the documents cannot be recovered elsewhere. **NEM Community Trust and NEM Group Trust are kept distinct.** [ND-13]

### Effect on the eight missing items

| Evidence gap | Additional result from this pass | Still needed |
|---|---|---|
| **EV-038** — 12 SEA payments / nine issuer transfers | Contemporary governance and counterparty material supplies context; the exact payments remain unclassified. | Original contracts, invoice and approval matching each of the 21 hashes/references. |
| **EV-039** — signing mandates | Historical issuer label `Gemdealer` recovered from July 2019, with a 2014 subscription statement to test. | Human identity, original stake-redemption mapping, custody transfers and dated signing mandates. |
| **EV-040** — exchange mappings | No new customer ledger obtained. | Deposit-memo-to-customer match, legal entity, trades, withdrawals and settlements. |
| **EV-041** — conflicts/resource approvals | November 2018 public discussion explicitly recognizes the Kidlet overlap. | Signed interests, recusal/approval records and allocation of staff, money and channels. |
| **EV-042** — elections/appointments | Additional archive paths tested; no signed minutes or constitution recovered. | Notices, membership/quorum, governing versions and signed appointment records. |
| **EV-043** — signed audit / expense reconciliation | Separate US Form 990 recovered; it is not the missing Singapore audit. | Foundation audited statements and the 27.3%/43% allocation bridge. |
| **EV-044** — reserve spending / institutional transfers / winding up | Missing March 2021 reserve report recovered: three sources and 125 Symbol destinations. Trustee proposal/dispute preserved. | Fresh chain reconciliation, executed settlement schedules, later mandates and actual Singapore surplus recipient. |
| **EV-045** — institutional delivery | Malaysian government rollout statement and implementer completion report; Philippine university's course-offering account. | Production/acceptance/payment records and independently verified usage for each claimed institution. |

No private record request, communication, purchase or account impersonation occurred. These additions deepen the public evidence; they do not supply the remaining exchange customer ledgers, bank receipts, or human key-custody records.

### Source register

- **ND-01:** NEMNodes archived table, July 2019: https://web.archive.org/web/20190721125710id_/https://nemnodes.org/topblocks/ ; current operator page https://nemnodes.org/topblocks/ . Relevant complete row retained from a partial archive response.
- **ND-02:** Gemdealer's original NEM subscription discussion, January 27, 2014: https://bitcointalk.org/index.php?topic=422129.1160 . Search retrieval supplied the relevant posts; local direct request returned 403.
- **ND-03:** Trustee statement and contemporaneous Gimre responses, August 18–20, 2021: https://forum.nem.io/t/nem-trust-update/30744 . Native JSON acquired from https://forum.nem.io/t/30744.json .
- **ND-04:** Recovered report: https://web.archive.org/web/20210616173157id_/http://report.experimental.symboldev.network/ . Generated March 30, 2021; captured June 16, 2021.
- **ND-05:** Portuguese archive copies: https://arquivo.pt/noFrame/replay/20190413132709id_/https://nem.io/about/ ; https://arquivo.pt/noFrame/replay/20200314202011id_/https://blog.nem.io/page/2/ . Common Crawl index: https://index.commoncrawl.org/CC-MAIN-2021-43-index?url=report.experimental.symboldev.network%2F*&output=json .
- **ND-06:** Original IRS filing: https://apps.irs.gov/pub/epostcard/cor/880622815_202212_990_2026030223955904.pdf . Discovery index: https://projects.propublica.org/nonprofits/api/v2/organizations/880622815.json . The PDF was downloaded directly from IRS and is retained.
- **ND-07:** Japanese reorganization translation, discovery only: https://hackmd.io/@xymbassador/rJoa_afwK . Not an executed asset-management agreement.
- **ND-08:** Malaysian ministry statement: https://www.mohe.gov.my/en/broadcast/media-statements/kpm-lancar-sistem-e-scroll-menggunakan-teknologi-blockchain-atasi-masalah-ijazah-palsu .
- **ND-09:** Implementer's completion statement: https://www.luxtag.io/blog/luxtag-develops-e-scroll-system-to-fight-counterfeit-of-diplomas-using-catapult-nem-blockchain/ .
- **ND-10:** LPU institutional account: https://manila.lpu.edu.ph/technology/cot-news-and-events/lpu-college-of-technology-and-the-blokc-moa-signing-collaboration/ .
- **ND-11:** Contemporary conflicts discussion: https://forum.nem.io/t/transparency-with-proximax-candidates/20658 ; JSON https://forum.nem.io/t/20658.json .
- **ND-12:** Management statement on contract review and customer-payment evidence: https://forum.nem.io/t/foundation-update-questions/22994/2 ; JSON https://forum.nem.io/t/22994.json .
- **ND-13:** NEM Ventures legal-document publication: https://forum.nem.io/t/nem-ventures-governance-and-group-structure-a-deep-dive/24065 . The linked documents are the articles, Community Trust deed and declaration of trust; document-hosted identifiers are omitted in this edition.

The raw/derived evidence manifest records exact paths and SHA-256 values. Package inclusion is selective: the public financial filing, the original reserve-table header and row 1 as a bounded HTML extract, its complete 125-address JSON transcription, retrieval metadata and derived records. The full archived report remains a working copy; its SHA-256 and byte count are recorded, but its unrelated rows are excluded from the package. Full fresh articles, unrelated account lists, and OCR intermediates are also excluded.


---

## Secondary projects: global and archive expansion — 6 September 2026

Scope: EV-046–EV-053. These projects remain separate from the main Cayman/GamiFi money trail. This pass materially extends the earlier report through Portugal's Arquivo.pt, the Internet Archive, historical issuer PDFs and software, Asian/European app-store records, and direct BNB Smart Chain reads. Wallets below are addresses, not identified people. No messages, purchases, private-account entry or transactions were made.

### Material new results

1. **MegaFans Launchblock sale now has actual contract accounting.** The formerly only sale-linked address is a verified `Sale` contract using MBUCKS. Public state records **6,025 USDT deposited**, **5,000 USDT refunded**, and **561.112862335267803167 USDT-equivalent claimed**. The last number is the contract's currency-denominated entitlement counter, **not MBUCKS units or a cash payout**. Five deposit events sum to the deposit counter. A successful **1,025-USDT** proceeds withdrawal on **1 July 2024** completes the payment-token reconciliation: **6,025 = 5,000 + 1,025**. The refund and all five deposits are now cross-checked against successful payment-token Transfer receipts.
2. **Two 2022 MegaFans tokenomics versions were recovered.** Their public-round price changes from **$0.15 to $0.20**. Both print a **7,750,000** initial token total despite **8,500,000** in the listed TGE components: a **750,000-token reconciliation gap**. This is an archived publication discrepancy; no executed purchase or actual vesting obligation follows from it alone.
3. **Historical MegaFans privacy pages identify a specific hosted-policy document.** The 2021 and May 2022 wrappers embed Termly document `6187b4c9-0481-4366-bd7c-a8a9ab284a67`; the September 2022 wrapper uses that same ID in an iframe. The archived wrapper is not the policy body. This now makes the missing historical policy a precise provider-held version target.
4. **Kaskade's archived frontend identifies the public leaderboard's source.** Its May/July 2024 application references the exact campaign, epoch, claims and participation resources, replacing a generic request for scoring data with a reproducible source map. The public campaign endpoint currently failed with HTTP 502; the targeted Wayback backend query had no rows.

### EV-049 / EV-050 — MegaFans sale: source, state and actual events

The [Launchblock MegaFans page](https://launchblock.com/project/megafans) links BSC address `0x8d43Bdd99DB5a36ccb64f868f80Aa51B53FbcF4C`. Sourcify identifies this as an exact creation/runtime match for `contracts/Sale.sol:Sale`, Solidity 0.8.20, with no proxy. Deployment was transaction `0x03293a1077dc6bdc31cf1506c97f7f3ea72c0de714fb625235b9585ef19f2a25`, block **39,806,346**, 21 June 2024 12:52:14 UTC. The sale source labels its licence `None` and credits Liteflow.com; its locator/hash and bounded functional analysis are preserved. OpenZeppelin imports have separate licences.

Observation block **120,324,137**, **6 September 2026 15:10:31 UTC**, is pinned in `sale_observation_header.json`. RPC request and response files preserve the exact state read.

| Field | Observed value |
|---|---|
| Sale token | MBUCKS `0x3638fea0c645b1aa79db706fab6e8a761385c390` |
| Payment token | BSC USDT `0x55d398326f99059ff775485246999027b3197955` |
| Token decimals / payment decimals | 18 / 18 |
| Token price | 0.14 USDT per MBUCKS |
| Deposit period | 21 June 2024 13:00–26 June 2024 20:00 UTC |
| Refund period | 27 June 2024 09:00–28 June 2024 09:00 UTC |
| Claim period | 27 June 2024 08:00–27 December 2024 12:00 UTC |
| Vesting | 15% initial unlock; remainder through 27 November 2024 12:00 UTC |
| Hard cap / configured winning amount | 50,000 USDT / 50,000 USDT |
| Deposits / fees | 6,025 USDT / 0 USDT |
| Refunded winning / losing amounts | 5,000 USDT / 0 USDT |
| Claimed amount counter | 561.112862335267803167 USDT-equivalent |
| Sale-proceeds withdrawal flag | true |
| Current USDT / MBUCKS contract balances | 0 / 0 |
| Owner | `0x462a647318d8dc1f0b5217b14cdcc90957305a1d` |
| Allocation-signing authorizer | `0x5482d260df17a64c563b6b65f35748d4e2a0df00` |

The source's `deposit` counts payment principal separately from fees. `claim` tracks currency-denominated vested entitlement before converting it to the number of sale tokens transferred. Consequently, comparing `totalClaimedAmount` directly to a MBUCKS balance would mix units. Owner and authorizer are distinct technical roles; their human controllers are not identified.

The five recovered deposits:

| UTC | Wallet | USDT | Transaction |
|---|---|---:|---|
| 22 June 2024 12:54:14 | `0x3ce3a276e0d5475f5e1b4c8ff087843803c134bb` | 500 | `0xaffef60411879d50ccdd2e5d9f42d093bac1a302bb39eedfab077bc126c097b5` |
| 22 June 2024 19:22:01 | `0xa47a1d4515212504ce236dcee128da8f6f88264a` | 50 | `0xa4aecac858a2d737bc048deeafeff633b30c6a8990b90045bad9f89d7276a55a` |
| 24 June 2024 05:38:07 | `0x67eeae0a8946f5456002a7ea1a2d0547975336d8` | 5,000 | `0xcb51e6c012b5ea202ccef55b464c85bdc03ad89d36af03298f168963b1c5215f` |
| 25 June 2024 17:46:57 | `0x487363c0cf0528c1dad0ed13fcc0674b989cf47f` | 350 | `0xdd70e0af594e668d2df9a5f4cc04e6f4a7264503c4d8c57bbbc8912cfeee468f` |
| 26 June 2024 13:13:34 | `0x5a168ccbc4754fbaf66a2f1d5d3e28acf45a542b` | 125 | `0x479e78755c3b5b0aad85e2ac76112e8f152b9d2b297e326b5e245c8a7a4952fe` |

The 5,000-USDT refund is confirmed by both the sale event and the successful USDT Transfer receipt, dated **28 June 2024 05:26:10 UTC**, transaction `0xa03846182a4924cf6031972d080bf6ad0a09f84248da48d9464f7aa3fd7f8813`, for the same `0x67ee…36d8` depositing wallet. This is a concrete customer-wallet outcome in this venue. All Sale-emitted logs in blocks 39,806,346–40,056,346 were retrieved in bounded ranges; this includes the entire immutable deposit/refund periods. Republic's separate withdrawn offering must not be conflated with it.

Three early successful claim receipts additionally confirm transfers of **389.510620692782009428**, **144.830656974886436257** and **586.557728595609444357 MBUCKS** to their respective depositing wallets on 28–29 June 2024; complete hashes are in `sale_verified_early_events.json`.

**Proceeds recipient verified.** At **1 July 2024 11:21:38 UTC**, block **40,091,197**, transaction `0xa11da8f23720ac0b3113047633bc4c540783d4bed41d012ef5c5387674244de0`, owner wallet `0x462a647318d8dc1f0b5217b14cdcc90957305a1d` called `withdrawWinningAmountWithFees(address)` with its own address as recipient. The successful receipt transfers **1,025 USDT** from Sale to that wallet. Historical reads pin the withdrawal flag changing from false at block 40,091,196 to true at 40,091,197. For this sale, **6,025 deposited = 5,000 refunded + 1,025 proceeds withdrawn**. This does not identify a human owner or the later use of proceeds.

The difference between deposits less refunds and the claim counter is **463.887137664732196833 USDT-equivalent**. This is a contract-accounting remainder at the observation block. The claim window ended in December 2024. Its legal treatment, signed allocation details, notices, any other settlement, and what happened to unclaimed tokens require further records. A zero contract balance does not by itself make that amount a proven customer loss. Full lifetime claim history, all onward spending, staking liabilities and profit-funded buybacks remain outside the completed reconstruction.

### EV-049 — 2022 accepted-terms and model history

Recovered publisher files, with actual replay timestamps and SHA-256 hashes, are recorded in the source manifest:

- Q1 tokenomics: capture **1 February 2022 03:12:54 UTC**, original *Historical file: MEGAFANS-TOKENOMICS-Q1-2022.pdf*.
- Q2 tokenomics: capture **24 September 2022 23:13:56 UTC**, original *Historical file: MEGAFANS-TOKENOMICS-Q2-2022.pdf*.

Both allocate 100m tokens. Public allocation is 1m, with 500,000 at initial release. Q1 prices that sale at $0.15 and projects $150,000; Q2 changes it to $0.20 and $200,000. Seed/strategic/private prices stay $0.04/$0.06/$0.08. Both list initial components of 1.5m, 0.5m, 1m, 0.5m, 1m, 1.5m and 2.5m, summing to **8.5m**. Both print **7.75m** instead. Listed public-price circulation values, $1,162,500 and $1,550,000, follow the smaller printed total. Using the listed components yields $1,275,000 and $1,700,000 respectively. This reconciliation question now predates the separately reviewed 2024 offering displays; it does not identify the author or prove a buyer accepted any version.

The May 2022 whitepaper, retrieved at its September 2022 archive capture, describes a $3m seed effort plus $2m public-token/NFT effort, total $5m, for 2022. It claims 500,000 installs, 50,000 monthly play-to-earn entries and $0.55 average revenue per user. It separately describes player-contact and behavioural-segmentation data as having commercial value. These are dated company claims to reconcile with receipts, cohort definitions, consent versions and accepted agreements. They are not audited results or proof of data sold. The historical claims must not be substituted for the later Republic campaign's metrics.

### EV-050 — historically anchored staking promise

The archived staking page from **28 June 2024 18:28:54 UTC** supplies material-date evidence for the up-to-150%-APY and guaranteed time-based-return representations. It links three Ferrum-hosted pools:

- `0xdd1595de28b28d64b40803c9713f1ab33f47b173`
- `0xbf7e1ab7ea1f919dcce748e7d187f5d3d052abce`
- `0x2de19777f66f508173b392ed982b3d485f04ae38`

This is stronger dating than the prior current-page observation. It does not establish deposited totals, rewards paid or reserve sufficiency. Source code and accounts for these pools remain separate from the Launchblock sale and the 2023 NFT audit.

### EV-051 — policy version and regional app evidence

The 2021/2022 MegaFans privacy wrappers embed a Termly-hosted document rather than storing the policy text inline. All three retrieved wrappers identify `6187b4c9-0481-4366-bd7c-a8a9ab284a67`; September's source uses `https://app.termly.io/embed/terms-of-use/6187b4c9-0481-4366-bd7c-a8a9ab284a67`. A route containing `terms-of-use` does not itself establish the returned document's type. The current Termly viewer loaded, but both its public policy-metadata and content endpoints returned HTTP 404. The provider's dated body/version and rendered historical app link are the decisive targets. Empty text extraction from a wrapper must not be described as a missing privacy policy.

Thailand's Apple listing for Crash n Win and the UK's listing for Tunnel Tournament still link Appic Studio's policy. They identify Megafans, Inc. and developer-declared tracking identifiers and advertising-related device/usage data; Apple expressly marks these declarations as unverified. The two listings show 2023 last releases. Their local-currency in-app offerings are **MegaFans in-app tokens**, not authenticated MBUCKS on-chain purchases. Current regional listing availability is not proof of historical user residence, downloads or transactions.

Appic's linked policy describes ad/game SDKs, mailing lists, screen names, social/game identifiers, and country-dependent processing. It names Apple, Chartboost, Facebook, Google and Unity services. Its text does not identify which SDKs are in each MegaFans build. Matching production binaries and backend/processor records remains necessary.

### EV-046 / EV-047 / EV-048 — Kaskade archive reconstruction

**Independent European archive:** Arquivo.pt preserves `https://www.kaskade.finance/` at **16 March 2024 23:11:32 UTC**, collection FAWP56, WARC `WEB-20240316231129293-p97.arquivo.pt.warc.gz`, offset **10,349,521**. It renders a Join Us call to action. Wayback's **18 March 2024 17:41:47 UTC** capture instead has Launch App and a different Next.js build ID. This corroborates an entry-point change around campaign launch, not a contractual acceptance or ownership change.

**Application record:** May and July 2024 bundles identify public backend project `ghqbblfbbuhxhkwxpklf.supabase.co`. The public leaderboard calls `get_participation_for_all_epochs`, which maps campaign ID, epoch, wallet ID, total points, transaction counts, share of points and trading volume. Other referenced public functions include campaign totals, volume over campaign/days, claimed/unclaimed token totals and latest claims; the application also refers to `weekly_epochs` for Merkle-root retrieval. The exact archived bundles and hashes are in the manifest. The source map gives a precise custodian export target. It does not supply the missing rows or establish who could edit them.

A read of the same public campaign-list resource used by the frontend failed with HTTP 502. No private table was queried and no data was changed. A targeted Wayback CDX query for that backend returned an empty result. This does not prove the underlying records no longer exist. The initial and retrospective campaign rules remain distinct; no new human wallet controller or full scoring threshold table was recovered.

The issuer's **13 March 2024 gas-rebate announcement** adds a direct primary source for the rebate promise. It describes activity-dependent chances while also saying active participants benefit; it does not disclose a determinate rebate formula or settlement list. These missing rebates belong in any complete net campaign-return calculation.

### EV-052 — Ireland: organizer rules and outcome evidence

The organizer's current results archive names winners and runners-up for the May pilot and some September pilot titles, providing positive, bounded evidence of event activity. It is not the 2026 Alumni Summer Showdown payment ledger. Its CS2 and LoL rules now identify **Nemesis** as the tiebreaker system, while LoL rules still describe Challengermode-generated match codes and screenshot submissions for manually created lobbies. This identifies additional platform records and admin evidence that may explain altered brackets or accepted formats.

Current Nativz terms are dated **27 July 2025** and explicitly reserve separate transaction terms for paid products/services. Therefore, those generic website terms cannot close the alumni accepted-prize gap. They contain parental-permission provisions; performance of those safeguards still needs the actual registration/school records. The exact 2026 event IDs from the prior report remain the appropriate payout targets. A targeted Wayback query for the company-series domain returned no rows; a broader Nativz wildcard query failed with HTTP 503. These bounded archive results are not evidence of concealment.

### EV-053 — Techstars / Cardano

The official Catalyst milestone pages remain locatable, but milestone 6 retrieval failed in this pass. Search also surfaced a distinct 2026 expansion proposal and commentary that criticizes missing outcome attribution. Those third-party assessments were not adopted as evidence against the completed 2025 grant. The prior accepted delivery records remain the baseline. No underlying completed-meeting export, survey denominator or consented later revenue/funding dataset was recovered. This remains an outcome-evaluation gap rather than evidence of diverted funds.

### Research boundaries and preservation

Whole-item status remains narrowed or open across EV-046–EV-053. The new work closes particular public-source subquestions: the Launchblock address's contract identity and recorded sale outcomes, dating of the 2022 tokenomics/staking publications, a historical hosted-policy identifier. It does not close human custody, buyer-specific legal entitlement, all trading/staking accounting, actual app data flows or investigator-only evidence.

Raw blockchain requests/responses, archive-index metadata, source-code locators/hashes and derived facts are preserved. Full newly retrieved copyrighted publications and complete frontend bundles remain acquisition working files; the deliverable uses bounded summaries and hashes, not unlicensed republication. The source JSON explicitly selects package files.


#### Primary source locators

Full acquisition timestamps, URLs, result/error codes and hashes are in `secondary_sources.json`. Key reproductions:

- [Launchblock sale display](https://launchblock.com/project/megafans) and [verified contract metadata](https://sourcify.dev/server/v2/contract/56/0x8d43Bdd99DB5a36ccb64f868f80Aa51B53FbcF4C?fields=all).
- [MegaFans Q1 2022 tokenomics archive](https://web.archive.org/web/20220201031254id_/https://megafans.io/wp-content/uploads/2022/01/MEGAFANS-TOKENOMICS-Q1-2022.pdf) and [Q2 2022 archive](https://web.archive.org/web/20220924231356id_/https://megafans.io/wp-content/uploads/2022/06/MEGAFANS-TOKENOMICS-Q2-2022.pdf).
- [May 2022 whitepaper, captured September 2022](https://web.archive.org/web/20220924232837id_/https://megafans.io/wp-content/uploads/2022/06/MS-MegaFans-White-Paper-May-24-2022.pdf).
- [Historical staking page](https://web.archive.org/web/20240628182854id_/https://www.megafans.io/staking/index.html).
- [2021 privacy wrapper](https://web.archive.org/web/20210121053240id_/https://www.megafans.com/privacy-policy/) and [September 2022 wrapper](https://web.archive.org/web/20220926222442id_/https://www.megafans.com/privacy-policy).
- [Portugal Kaskade capture](https://arquivo.pt/noFrame/replay/20240316231132id_/https://www.kaskade.finance/) and [May 2024 application bundle](https://web.archive.org/web/20240522184330id_/https://app.kaskade.finance/_next/static/chunks/pages/_app-9052e43fbbdc9132.js).
- [Kaskade gas-rebate announcement](https://medium.com/@KaskadeFinance/gas-fee-rebates-187061a6ed57).
- [Thailand Crash n Win listing](https://apps.apple.com/th/app/crash-n-win/id1503172280), [UK Tunnel Tournament listing](https://apps.apple.com/gb/app/tunnel-tournament/id1503582224), and [linked Appic policy](https://appicstudio.com/privacy-policy.html).
- [Organizer results archive](https://company.irelandesportsleagues.com/results-archive), [CS2 rules](https://company.irelandesportsleagues.com/help-centre/cs2-match-rules), [LoL rules](https://company.irelandesportsleagues.com/help-centre/lol-match-rules), and [Nativz general terms](https://www.nativzgaming.com/terms-of-use).


---

## 53 crypto-related evidence items: deeper-pass register

The register retains the original IDs and titles. “Narrowed” means that a component is resolved or materially advanced; it is not closure of the full compound request. All remaining-evidence and custodian fields from the previous register are retained in the companion JSON.

| ID | Evidence item | Deeper-pass result |
|---|---|---|
| EV-001 | Identify the people behind the GamiFi control keys | Two additional membership-contract ownership transfers verified, 28 April and 19 September 2022; human assignments and instructions remain missing. |
| EV-002 | Identify the 120m private beneficiary and its entitlement | Archived client code associates registered users and wallet addresses; no record links the private beneficiary to a registered user or establishes entitlement. |
| EV-003 | Obtain MEXC deposit, customer and execution records | No new exchange customer ledger. The recovered MEXC interview is a publication record, not a deposit-credit record. |
| EV-004 | Obtain FixedFloat’s historical order and payout mapping | No new historical order or payout mapping recovered. |
| EV-005 | Identify onward-wallet owners and the purpose of returning funds | New replenisher identified on-chain; six consecutive outgoing transactions and additional onward-wallet activity through August 2025 verified. Human ownership/purpose remain missing. |
| EV-006 | Establish any actual Cayman bank or personal receipt | No bank account, bank settlement or personal receipt identified. |
| EV-007 | Identify the recipients and entitlement for seven project withdrawals | The original project contract returns the archived membership address at the ID-4 withdrawal block. Commercial attribution and final settlement remain unresolved. |
| EV-008 | Verify the exact GamiFi legal entity | No new official incorporation certificate, registered agent or ownership record for GamiFi; prior BVI 2082070 identification retained. |
| EV-009 | Verify offshore Launchpool and its relationship to the UK company | Independent October 2021 / February 2022 terms recovered in Portugal; an earlier printed revision creates a specific dating ambiguity against the candidate BVI incorporation. |
| EV-010 | Establish Asociados Carajo’s issued and beneficial ownership | No issued-share or beneficial-owner register obtained; supplied Panama documents remain controlling. |
| EV-011 | Identify who voted for the February 2025 Panama changes | No new proxies, voting-rights schedule or instructions for the 2025 Panama changes. |
| EV-012 | Resolve Linford’s 2018–2023 legal status | No new Linford restoration or material-date status instrument. |
| EV-013 | Trace SCR Advisors and the relevant dated ownership chains | No new SCR Advisors shareholder chain. |
| EV-014 | Document the actual Alphabit/Cayman investment and management relationships | Cayman company WC-319009, LEI/name history and historical CIMA licence identity joined; a historical information memorandum recovered with provenance limits. Executed GamiFi agreements remain missing. |
| EV-015 | Recover transfers between the old and new operating entities | Earlier operator terms recovered, but no executed Panama asset transfer, novation or liability assumption. |
| EV-016 | Establish Laura’s actual authority and economic interests by date | Independent Portuguese team-page captures corroborate CEO succession; old podcast text persists separately. No private authority/equity/handover records. |
| EV-017 | Determine whether GamiFi actually used Yield or a specific corporate adviser | Actual Yield gazettes, strike-off entry and later court listing recovered; Cavenwell incorporation/personnel evidence added. No actual GamiFi engagement. |
| EV-018 | Reconcile actual fundraising and use of proceeds | Full MEXC interview reiterates fundraising categories; actual proceeds and spending remain unreconciled. |
| EV-019 | Determine the terms and prices actual IDO buyers accepted | Contemporaneous staking terms and external Shibafriend offer changes recovered; individual buyer acceptance remains unproved. |
| EV-020 | Reconcile ShibaFriend and FOMO refunds and later distributions | Specific Shibafriend supply, release and exchange-lock changes recovered from other offering venues; no completed GamiFi refund ledger. |
| EV-021 | Reconcile paid NFT access with benefits actually available | Membership contract states/handovers and archived account/NFT usage structure recovered; MEXC original preserves first-come purchase qualification. Full payment/activation/benefit accounting remains missing. |
| EV-022 | Reconcile every Mystery/Duke mint and matching burn historically | No complete new Mystery/Duke lifetime mint/burn/reserve ledger. |
| EV-023 | Verify staking deposits, restrictions and rewards | Two-pool public offer recovered and matched by historical configuration; fresh principal snapshots and 46.02m-GMI replenishment accounting added. |
| EV-024 | Authenticate Laura’s statements and identify authors, approvers and knowledge | Original MEXC publisher interview recovered from February 2022 and compared with October capture; private publication approvals and signed diligence documents remain missing. |
| EV-025 | Obtain actual buyer accounts of reliance and economic exposure | No authenticated individual reliance or net-exposure packet obtained. |
| EV-026 | Verify advertised game, NFT-series and integration delivery | HYPE first-party Shibafriend association found; full integrations, user availability and acceptance records remain missing. |
| EV-027 | Obtain the claimed audit and deployment sign-off | Audit representation preserved in original dated interview; public publication tree checked; actual audit/report-to-deployment sign-off remains missing. |
| EV-028 | Establish material-date jurisdiction and offering classification | Korean company-release publication trail recovered; publication reach does not establish operating or buyer residence. |
| EV-029 | Complete the intervening Launchpool history and affected-user outcomes | Complete matching incoming-GMI window from 10–18 May 2023 found no Launchpool receipts; lifetime vesting history remains incomplete. |
| EV-030 | Extend bounded onward-wallet and funding inventories | Six replenisher transactions and three additional onward-wallet receipts verified; upstream funding and intervening nonces remain open. |
| EV-031 | Reconstruct remaining vesting obligations and historical token controls | 46,020,000 GMI replenishment sequence and exact restoration of smaller-pool principal backing verified; larger-pool shortage and reward/user reconciliation remain. |
| EV-032 | Test liquidity and manipulation allegations against complete relevant trading | Selected swap receipts extended; complete GMI trading/liquidity and centralized order history remain missing. |
| EV-033 | Establish whether contest entries were actually received and awarded | No contest entry, adjudication or prize-payment ledger recovered. |
| EV-034 | Recover consent, access, retention and post-project custody records | Original contest-period certificate and historical WARC IP record recovered; consent, mailbox use/access and retention remain unproved. |
| EV-035 | Match the reviewed wallet source to the released application | Broader source/package archive searches found no authenticated production APK/AAB/IPA matched to the reviewed source. |
| EV-036 | Recover quiz backend and rewards-economy delivery evidence | Regional publication and citation lineage checked; no production quiz backend or merchant settlement records. |
| EV-037 | Identify curriculum commissioning and later channel/domain control | Historical mail/cPanel certificate footprint and October 2023 wildcard change identified; commissioning and human handover remain missing. |
| EV-038 | Explain the twelve SEA payments and nine onward issuer transfers | The 21 previously indexed NEM payments remain unclassified by original invoice/contract purpose. |
| EV-039 | Establish NEM key custody and authorization by date | July 2019 archive labels the exact issuer Gemdealer, with a 2014 subscription statement to test; no civil identity or continuous custody established. |
| EV-040 | Obtain historical XEM exchange customer and settlement mappings | No new exchange customer mapping or settlement ledger. |
| EV-041 | Recover formal conflict and resource-allocation approvals | Contemporary November 2018 discussion recognizes Kidlet overlap; signed conflicts, recusals and resource approvals remain missing. |
| EV-042 | Verify election adjudication and later appointment authority | No newly recovered signed election or appointment records. |
| EV-043 | Reconcile the 2019 expense report to signed accounts and authorizations | Separate US Symbol Syndicate return recovered; it is not the Singapore Foundation audit or expense-allocation reconciliation. |
| EV-044 | Follow reserve spending, institutional asset transfers and wind-down custody | Missing reserve table recovered: three NIS sources and 125 Symbol destinations. Proposed award and dispute kept separate from actual settlement. |
| EV-045 | Verify claimed institutional delivery beyond announcements | Malaysian government 2018 rollout record and Philippine university 2018 course-offering account recovered; payment/use reconciliation remains. |
| EV-046 | Kaskade: settle campaign rules, scoring and payment completeness | Archived Kaskade leaderboard data model and gas-rebate representation recovered; final scoring rows and full settlement remain missing. |
| EV-047 | Kaskade: identify wallet controllers, mandates and Laura’s exact role dates | No authenticated Kaskade human wallet controllers or mandates. |
| EV-048 | Kaskade: extend the public history and verify later operations | Earlier Portuguese prelaunch capture and later application backend provenance added; full campaign and later operating history remain incomplete. |
| EV-049 | MegaFans: reconcile models, offering scope and actual buyer outcomes | Archived 2022 tokenomics versions and primary 2024 venue contract accounting recovered; accepted offering versions and company-wide outcomes remain incomplete. |
| EV-050 | MBUCKS: verify sale settlement, staking and buyback execution | Launchblock payment receipts reconcile 6,025 USDT deposited = 5,000 USDT refunded + 1,025 USDT withdrawn to the sale-owner wallet on 1 July 2024; complete staking/buyback accounting remains open. |
| EV-051 | MBUCKS: assess trading and application policy fit on actual evidence | Historical Termly document UUID and regional app declarations recovered; actual production data flows remain unverified. |
| EV-052 | Nativz: reconcile accepted competition terms, prizes and safeguards | Organizer pilot results and rules/platform evidence added; target alumni accepted terms, payments and safeguards remain unresolved. |
| EV-053 | Techstars/Cardano: validate remaining outcome metrics proportionately | No new underlying completed-outcome dataset; prior accepted grant deliverables retained. |

## Source retention and package contents

The historical research was based on this report, its status register, source registers, public records, technical metadata, transaction records, extracts and reproduction scripts. Consult the repository manifest for the exact files in this edition. Full fresh copyrighted publications and unrelated personal details are not republished. Their source URLs, capture timestamps and acquisition hashes are retained. The complete IRS filing is an official public record; the Seychelles and CIMA excerpts preserve the relevant original pages.

Some acquisition manifests refer to working copies intentionally omitted from the package. The root SHA256SUMS.txt is the definitive list of included bytes. A listed URL, hash or error response is not a claim that an original document was successfully acquired. Historical working archives are not a statement of this edition’s file inventory.

Integrity hashes establish byte identity; they do not certify a publisher's claims or replace legal and accounting records.
