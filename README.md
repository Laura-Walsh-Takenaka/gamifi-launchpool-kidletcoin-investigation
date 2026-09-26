**GamiFi / Launchpool: suspected investor fraud, contract manipulation and 44 million GMI removed**

**Contract code was temporarily changed. Maximum spending permissions were granted. The original code was restored—but the permissions remained. Those permissions were then used to remove 44 million GMI from contracts that still recorded investor obligations.**

That is the central finding we are opening to independent scrutiny.

This repository investigates **suspected investor fraud involving smart-contract manipulation**, alongside research into GamiFi/GMI, Launchpool, Laura Takenaka/Walsh’s documented project roles, KidletCoin, NEM and separately identified related projects.

The allegation deserves examination at the code and transaction level: **were these mechanisms used deliberately to defraud investors, who authorized their use, and who ultimately benefited?**

**Start with the November 2022 transactions.**

The research reconstructs this sequence on **5 November 2022**:

1. **Temporary contract upgrades granted maximum GMI spending allowances**, followed by restoration of the original implementations.
2. **44 million GMI were removed:** 14 million from Launchpool vesting and 30 million from two staking contracts.
3. **The tokens were sold for approximately 5,174.29 BUSD**, while recorded investor obligations remained.
4. **The withdrawal route bypassed the staking code’s ordinary principal-protection calculation.** Restoring the original code did not revoke the spending permissions.

This gives independent reviewers something specific to test: **the upgrade transactions, temporary implementation, surviving allowances, token withdrawals and resulting backing shortfalls.** Looking only at the restored contract code would miss the earlier permission change.

Start with the GamiFi master investigation’s **“November control and removal mechanism”** section and the companion transfer review. Check the preserved receipts, code comparisons and accounting against the primary records.

**Help establish responsibility.**

The transaction sequence establishes a technical mechanism and its accounting consequences. Identifying the people behind the keys—and establishing their authority, knowledge and intent—requires further evidence.

Laura’s public statements and documented roles are examined separately. Her replacement as CEO was announced on **1 September 2022**, before the November withdrawals. A public title alone does not identify a transaction signer or establish personal receipt.

We welcome developers, blockchain investigators, journalists and affected participants who can:

- Reproduce or challenge the contract analysis.
- Trace the withdrawals and subsequent proceeds.
- Supply dated custody, handover, authorization or settlement records.
- Compare investor promises with the contracts’ actual behaviour.

The repository also retains findings that corrected earlier suspicions: matched original FOMO refunds, reconciled original GAMI allocations and backing, and later ShibaFriend repayment findings. The approximately **63,002 BUSD** project-withdrawal subtotal is **not an established theft or loss figure**.

Read `RESEARCH_QUESTIONS.md` and `CONTRIBUTING.md`, then open a verification task, evidence submission or correction. Include exact sources, dates and reproducible steps. Keep private identifying information and children’s information out of submissions.

The main research snapshot is **5–7 September 2026**; this repository edition was prepared on **20 September 2026**.

**Inspect the code. Reproduce the transactions. Help establish who controlled the mechanism—and why it was used.**

# Research Paper — Public Crypto Research

**Laura Takenaka / Walsh · GamiFi · Launchpool · KidletCoin · NEM**

An open research collection for examining public crypto-project statements, corporate records, token mechanics, customer outcomes and blockchain transactions. The purpose is to make the material easier to inspect, reproduce, correct and extend.

**Fork it. Check the sources. Reproduce the calculations. Submit corrections and contrary evidence.** A useful contribution can confirm a finding, narrow it, disprove it or explain an unresolved record.

Research observations are principally dated **5–7 September 2026**; individual records retain their own collection dates. This repository edition was prepared on **25 September 2026**. That packaging date does not mean every source, balance, company status or conclusion was checked again.

## Start here

| Material | What to use it for |
| --- | --- |
| [Reports](reports/) | Read the consolidated research papers, attribution assessment, transaction studies and later corrections. |
| [Research notes](research/) | Follow the detailed reasoning, source registers, archival work and unresolved questions. |
| [Evidence](evidence/) | Obtain the supporting records and technical material. Evidence archives are download containers; extract them locally to inspect their files. |
| [Network viewer](network/) | Explore the documented relationships and embedded source records in the offline viewer. |
| [Data](data/) | Inspect the delivered tables, indexes and machine-readable records. |
| [Research questions](RESEARCH_QUESTIONS.md) | Choose a bounded question and see what would move it forward. |
| [Contribution guide](CONTRIBUTING.md) | Submit a reproducible finding, correction or rebuttal. |
| [Rights and sources](RIGHTS_AND_SOURCES.md) | Understand source attribution and reuse boundaries. |

For Launchpool, read the ownership and deeds report alongside the new 7 September claims, continuity and transition follow-up. The follow-up includes a public evidence bundle with pinned on-chain responses, derived ledgers and reproduction scripts. For GamiFi, read the consolidated report alongside the attribution follow-up, seven-withdrawal study, ShibaFriend claims review and exchange-links report. Later topic-specific corrections qualify earlier text even where reports share the same date.

## What the collection covers

| Research area | Questions examined |
| --- | --- |
| **Public roles and statements** | Laura Takenaka / Walsh's dated public-facing involvement, promotional statements, project representations, leadership succession and the evidence needed to attribute a particular decision. |
| **GamiFi / GMI** | Published fundraising plans; offering versions; project withdrawals; FOMO, GAMI, Time Raiders and ShibaFriend outcomes; staking and vesting; membership NFTs; Mystery Box promises; administrative permissions; liquidity and trading. |
| **Exchange and cross-chain routes** | Transaction paths involving MEXC, FixedFloat, Bitkub and other exchange-associated infrastructure; privacy-pool limits; bridge matching; mixed funds; the distinction between a wallet label and a customer identity. |
| **Launchpool and corporate history** | Dated operator terms; BVI, UK, Panama and Cayman records; Asociados Carajo, Linford, SCR Advisors and Alphabit; unresolved ownership, authority and transfer-of-obligation questions. |
| **KidletCoin / NEM** | Adult project involvement; public contest and consent notices; wallet-source versus released-app evidence; token utility; curriculum and delivery; shared signing authority; regional payments; governance, reserve mapping and institutional outcomes. |
| **Related project records** | Separately identified Kaskade, MegaFans / MBUCKS, Nativz and Cardano-program material where relevant to the documented project connections. Shared personnel do not establish common custody or responsibility. |

Laura is named because the research examines her documented public-facing project roles and statements. A public title, an association or an address-level link does not by itself establish that she instructed a transaction, controlled its keys, knew of a defect or received funds personally.

## Corrections are part of the research

The collection contains findings that materially qualify earlier questions. Preserve them when quoting or extending the work.

| Topic | Latest assessment preserved in the collection |
| --- | --- |
| **Original FOMO campaign** | All 27 original funding addresses were matched to full principal repayments. This finding is specific to that campaign. |
| **GAMI allocations** | All 127 original funding addresses matched their recorded vesting allocations; the remaining recorded allocation balance was fully backed at the stated block. GAMI and GMI are different tokens. |
| **ShibaFriend principal** | The later claims review located repayments for all 23 non-dust funding addresses. Three dust contributions totaling 168 base units remained unmatched; this is not a material unpaid-loss finding. |
| **Mystery Boxes** | All 194 identified paid mints in the later review had matching buyer and project transfers to the designated burn address. A publication discrepancy about box quantities remained. |
| **Staking pools** | The reports include later replenishments as well as withdrawals. Funding restoration, rewards and individual customer settlement are separate questions. |
| **Time Raiders** | Initial token deliveries and later claims are documented; the separately dated Polygon control/withdrawal event requires its own assessment. A located BUSD balance does not by itself prove current access or final settlement. |

These are reported results from the preserved research, not a claim that this repository release independently replayed every query.

## How to read a finding

Separate **observed records**, **publisher statements**, **analysis** and **unresolved questions**. Check the date, network, exact asset, contract version and completeness of the queried interval.

- A transfer proves an address-level event when its successful receipt and relevant event are established; it does not identify the human custodian, commercial authority or final economic beneficiary.
- The approximately **63,002 BUSD** figure is a subtotal of seven project withdrawals. It is not automatically a loss, profit, personal receipt or illicit-proceeds figure. Refunds and delivered allocations must remain in the accounting.
- Successive transfer hops, replenishments and reused trading capital must not be added together as if they were separate losses.
- An exchange-associated endpoint does not establish the credited customer or what happened inside the exchange. A mixer withdrawal is not linked to a particular deposit merely by timing, amount or shared infrastructure.
- A missing record, failed download, search no-match or incomplete archive does not prove that an agreement, payment, safeguard or approval never existed.

Public URLs, dated captures, transaction hashes and source identifiers allow independent checks. A file checksum establishes byte identity, not the truth of its contents. Some linked or indexed records may require a new public retrieval; use the delivered inventory to determine which bytes are included.

## Contribute

1. Choose one question from [the research questions](RESEARCH_QUESTIONS.md).
2. Check the latest relevant report and its underlying record.
3. Record the exact source, date, method and result, including evidence that contradicts your initial interpretation.
4. Open an issue using **Verification task**, **Evidence submission** or **Correction or rebuttal**. Use a pull request for a proposed file change.

Keep contributions focused on records and reproducible reasoning. Do not publish credentials, private identifying data or information identifying children. Disagreement and supported rebuttals are welcome. Coordinated contact, pressure campaigns and personal attacks are outside the project's research purpose.

See [CONTRIBUTING.md](CONTRIBUTING.md) before submitting material. The invitation to fork and verify is subject to the [rights notice](RIGHTS_AND_SOURCES.md); it does not grant blanket rights over third-party publications.
