# Research Paper — GamiFi master investigation

**Historical edition.** Findings and access descriptions are dated to the research date shown. This public edition is limited to crypto-related research. Later evidence supersedes some earlier gaps: the 7 September ShibaFriend claims review records repayment to all 23 non-dust original funding addresses, with 168 BUSD base units of unmatched dust; the later Mystery Box review records matching project contributions for all 194 paid mints. These narrow results do not settle every wider claim or identify a human wallet controller. Consult the repository README for the latest report precedence before quoting an earlier unresolved finding. Source URLs, transaction hashes and archive dates remain the research locators; historical local file locators below are not assertions that those working files are distributed unchanged.

Consolidated research edition • 6 September 2026 • All times UTC

## Executive findings

Research date: **6 September 2026**. Network: **BNB Smart Chain, chain ID 56**. All times are UTC. This master consolidates the earlier project-history reviews and the latest completed on-chain investigation. Its current findings supersede earlier selected-only findings retained in the evidence. The accompanying ledger contains **262 transfer and fee records across 172 transactions**, plus all **7,495 original funded Launchpool schedules**. Raw receipts, historical contract calls, calculation code and independent accounting checks accompany it.

**Latest completed follow-up:** a supplied BVI registry screenshot now identifies Gamifi Limited as entity **2082070**, with a matching free directory entry; three administrative handovers are dated and receipt-verified; a later provider-attributed statement strengthens the FixedFloat address association; and a bounded onward-wallet review establishes direct BNB payments back to the private beneficiary and further address intersections. Company and customer records remain necessary to identify the relevant human custodians.

**Two numerical gaps are closed.** The previously untraced 107.87 million GMI consists of three additional private-vesting claims; all five claims sum to exactly 120 million GMI. Separately, Launchpool's original funded obligations were fully backed immediately before the 5 November 2022 withdrawal. That transaction removed exactly 14 million GMI without reducing any of the 7,495 obligations, creating a 14-million-GMI deficit. The same exact deficit is present at the pinned September 2026 observation.

**The human and banking links remain unproved.** We can identify signing keys, token recipients, swaps and exchange-wallet leads. No verified public evidence located here identifies the human owners of the critical wallets, a Cayman bank account, or a personal receipt by Laura. Public blockchain data cannot supply an exchange's private customer ledger.

| Finding | Established amount | Historical dollars / interpretation |
|---|---:|---|
| Complete private allocation paid out | 120,000,000 GMI in five claims | Claim-time marginal marks total US$22,859.76 / C$30,902.87; not cash proceeds |
| Private beneficiary's direct GMI sales | 42 sale outputs across four assets | Gross received-asset value US$10,226.39 / C$13,755.46; not profit or bank cash |
| Private route into MEXC-associated wallets | 18,000,000 GMI in four sweeps | Arrival-time marginal marks total US$2,153.25 / C$2,906.98; exchange sales unproved |
| Launchpool backing deficit created 5 Nov 2022 | 14,000,000 GMI | Withdrawal-time marginal mark US$2,675.88 / C$3,616.99; not a dollar-loss calculation |
| Combined sale of Launchpool's 14m and two other contracts' 30m | 5,174.293394005109506048 BUSD | Actual on-chain output; US$5,174.14 / C$6,993.89 |
| Seven earlier project-contract withdrawals | 63,001.817377359365034843 BUSD | US$63,019.16 / C$79,740.69; purpose and entitlement unresolved |

A market mark multiplies quantity by a historical marginal price. It does not establish investment, realizable liquidation value or cash received. Sale proceeds are actual received cryptoassets converted at their own transaction dates. Repeated hops, liquidity inputs, LP shares, redemptions and later conversions overlap. **Do not add these categories into a grand total or an alleged loss.** Transfer and swap values are gross of transaction gas costs. The new onward-wallet network fees are listed separately.

## Reading guide and evidence package

The main findings are followed by the exact record-location briefs, corporate-source details, the complete financial register and source links. Historical reports are retained as prior editions. Their superseded numbers and unresolved items are not the current conclusions.

| File or evidence group | What it contains |
|---|---|
| Research_Paper_GamiFi_Master_Investigation.pdf | Consolidated narrative, complete dated financial register and printed source identifiers |
| Research_Paper_GamiFi_Master_Investigation_2026-09-06.md | Editable master source |
| GAMIFI_ONCHAIN_LEDGER_2026-09-06.xlsx | Financial records, exact-text quantities, valuation sources, 7,495 vesting records and reconciliation checks |
| GAMIFI_COMPLETE_EVIDENCE_2026-09-06.zip | Current and historical source evidence, prior report editions, source code, raw responses and document manifests |
| EVIDENCE_INDEX_2026-09-06.md and SHA256SUMS.txt | Package navigation, coverage and file integrity checks |

The evidence package preserves the source distinctions: a successful archived page, a search-index recovery, a supplied screenshot and an unsuccessful request are different kinds of record. Failed captures do not prove that a page or event never existed. No paid registry report or private account records were obtained, and no record requests were sent. The earlier reports' dated legal analysis is retained in the evidence; it has not been updated for this consolidation.

This report concerns GamiFi and the documented relationships relevant to it. Historical publication dates, archive-capture dates, transaction dates and September 2026 observations are kept separate. Financial amounts in different categories overlap and must not be added into a single loss or personal-receipt figure.

## Project background and the published financing model

GamiFi presented itself as a launchpad for blockchain-game token offerings. GMI holdings, staking and qualifying NFTs were promoted as routes to allocation access; purchasers still had to pay for the partner tokens. A Golden Ticket was advertised at 100 BUSD for three IDOs or three months, whichever came first. The launchpad's usefulness therefore depended on a continuing offering pipeline. These were the advertised commercial terms, not proof of the amount any purchaser ultimately received. [B01, B02]

The complete February 2022 litepaper presents the following issuer financing schedule. It also describes a 5% fee on hosted IDO allocations. Issuer financing and platform fees are separate categories; the schedule is not a receipts ledger and cannot be added to the later traced token-sale proceeds. The 120-million-GMI vesting allocation in the current accounting has no verified human-readable category label and should not be assigned to a fundraising round merely by comparing quantities. [B01; current on-chain accounting]

| Published round | Tokens | Token price, US$ | Published raise, US$ |
|---|---:|---:|---:|
| Seed | 30,000,000 | 0.015 | 450,000 |
| Strategic | 35,000,000 | 0.015 | 525,000 |
| Private 1 | 50,000,000 | 0.017 | 850,000 |
| Private 2 | 60,000,000 | 0.018 | 1,080,000 |
| Public | 5,000,000 | 0.030 | 150,000 |
| **Published total** | **180,000,000** | Different prices | **3,055,000** |

The early delivery sequence is documented in project publications. On 31 January 2022, GamiFi disclosed doubled participation thresholds while retaining the same ticket counts. GAMI and Time Raiders were promoted in March. By 4 May the company acknowledged only two completed IDOs and extended Golden Ticket validity. On 23 May it postponed FOMO's token-generation event to Q3 and promised refunds. The 29 June ShibaFriend cancellation cited changes to tokenomics and insufficient time for contract and investor updates, offering a refund or alternative private allocation. A September FOMO schedule and subsequent distribution notice are company-reported delivery; those notices do not reconcile earlier refunds. [B03-B07; prior branded memorandum, pages 4 and 11]

## Laura's documented role and the business network

The historical GamiFi sources use the name **Laura Walsh**. The January team page identifies her as CEO. Nativz's 9 July 2022 account describes her Launchpool COO appointment in May 2021 and credits her with establishing GamiFi within Alphabit. A separate Techstars release states that Alphabit Digital Currency Fund started Launchpool in 2020. These records establish professional and organizational relationships. They do not identify shareholdings, signing-key custody or personal banking authority. [B08-B10]

The prior reviewed MEXC interview attributes to Laura promotion of GMI acquisition, staking-based allocations and an initial four-IDO plan, together with statements about fundraising, diligence and a PeckShield audit. It also carried an express qualification that market conditions could change launch dates. Its source status is limited: the prior review recovered indexed material, while a direct download timed out and a later check returned 404. A complete original MEXC HTML payload was not preserved. The audit claim therefore remains a specific verification lead; the later repository references to an audit do not identify PeckShield as the auditor. [B11; prior branded memorandum, page 10]

Two further records establish direct participation in promotion: GAMI's 28 February issuer release includes Laura's named endorsement of the first partner offering; episode 33 identifies Laura and Casey discussing the proposed burn initiative. The RSS dates publication to 1 July 2022 at 09:15:08 UTC. Publication is not the recording date, and the audio was not transcribed in the reviewed package. The description does not identify who approved the conflicting Mystery Box quantities published the following day. [B04, B12, B13]

GamiFi's 1 September 2022 succession announcement names Eleanor Rooney as CEO and describes her prior Alphabit/Launchpool analysis roles. The homepage still named Laura on 4 September and changed by 6 September. Eleanor's 3 October update announced the IDO pause. The September-November key-control changes and November transfers in the current report occur after the succession announcement. None of these titles identifies the relevant human key holders. [B14-B16]

The corporate-account lead is specific but conditional. Yield App's 11 March 2021 announcement offered Launchpool fundraising projects corporate treasury/custody accounts, 20,000 YLD tokens and advertised returns of up to 20% APY, with Alphabit described as the facilitator. This establishes an available service; GamiFi enrollment, deposits and a creditor claim have not been established. [B17]

The litepaper identifies Liam Robertson as an adviser and Alphabit Digital Currency Fund CEO. Ghaf Capital's own portfolio page also listed GamiFi in the prior indexed-source review. Neither record establishes an investment amount, ownership percentage or transaction instruction. [B01, B31]

The Cayman connection in the reviewed corporate record concerns **Alphabit Digital Currency Fund**: its SEC-hosted Form D, signed 1 February 2018, describes a Cayman Islands exempted company formed in 2017 and names Dalma Capital Management as investment manager. This is an organizational record, not a Cayman bank-account record for GamiFi or Laura. GamiFi's own identified corporate target is **Gamifi Limited, BVI 2082070**, as addressed in the current corporate findings. [B18]

The phrase about a managed fund in clause 7.1.3 of the terms is not independent evidence of a separate GamiFi investment fund. It matches language in earlier Launchpool and Yield terms after replacing provider names and normalizing typography; the prior review independently repeated that comparison. The Yield terms' named operators and digital-wallet custodian belong to Yield and must not be assigned to GamiFi. [B32-B34; GAMIFI_MISSING_LINKS section 3]

## Documented discrepancies and later public offers

The archive preserves several different kinds of discrepancy. They should be stated individually, with their original qualifications. Authorship, materiality, buyer reliance, actual purchase terms and any required state of mind remain separate questions.

| Record | Documented comparison | Evidence meaning |
|---|---|---|
| November litepaper valuation | The 15 November edition gives a $20m private-round valuation at $0.018 against a 1bn supply; the 18 November edition corrects it to $18m. | A corrected published arithmetic discrepancy. |
| TGE market capitalization | 18m circulating tokens × $0.03 = $540,000; four complete archived editions state $577,500. | A $37,500 arithmetic difference; not cash received. |
| GAMI offering | 28 February issuer release advertises a $100,000 target; 28 March app capture displays $50,000. | Different published targets; not verified conflicting balances. |
| Time Raiders price | 3 March capture states $0.22; corrected body states $0.022 for the same $150,000 target. Edit metadata says 5 March; first recovered corrected capture is 10 August. | Tenfold published unit-price correction; actual buyer execution price unresolved. |
| Mystery Box quantity | Twelve recovered captures from July 2022 to December 2023 contain both 1,000 and 500 boxes. | Persistent internal marketing conflict; current observed contract cap was 500. |
| Golden Ticket after pause | 4 October 2023 capture still advertises 100 BUSD and three-IDOs/three-months access after the October 2022 IDO pause. | A surviving public offer; no completed post-pause purchase was established. |

Sources: litepaper/version comparison [B01, B19]; GAMI [B04, B20]; Time Raiders [B21, B22]; Mystery Boxes [B13]; October offer [B02]. Additional preserved changes include a same-day staking disclosure addition, contradictory 60-/45-day pool wording, later increases in advertised May staking limits and two published FOMO schedules. The prior report records their exact archive observations and embedded edit metadata separately. [Prior branded memorandum, pages 6-7; source register pages 19-20]

The last recovered substantive project homepage was captured on 25 July 2024. The earliest recovered adult-portal version was 14 May 2025 at 11:42:26 UTC. This bounds an observed domain-content change; operator identity and cause remain unestablished. It is not evidence that Laura operated the later site. [B23; prior branded memorandum, page 11]

## Additional verified token, NFT and market mechanics

The initial creation transaction on 17 January 2022 at 23:09:27 UTC emitted the zero-address transfer for exactly one billion GMI. The matched token implementation reproduced 6,989 executable bytes, with compiler metadata excluded. Its initialized code has no public mint or burn function; a different repository file with unrestricted minting did not match the deployment and was excluded. The token is upgradeable, so present code is not an immutable guarantee of its complete history. Two successful 18 January upgrades, at 23:16:28 and 23:16:58 UTC, changed and restored token logic; neither receipt contained a mint/transfer event. This January token sequence is distinct from the November vesting-contract allowance mechanism. [B24-B27]

The September 5, 2026 NFT review fully matched the deployed Mystery Box and Duke implementation bytes, including metadata. At the sampled settings, a successful public Mystery purchase sends 25,000 GMI from the buyer and an equal prefunded contract contribution to the designated sink. Owner batch issuance sends only the prefunded contribution. Consequently, an NFT supply count is neither a paid-purchase count nor proof of a 50,000-GMI burn for every NFT. [B28, B29]

At block 120,183,085, Mystery supply was 200 and Duke supply was 193, each against a cap of 500. The Mystery contract held zero GMI; a read-only buy(1) simulation failed because the matching contribution could not be funded. That prerequisite occurred before buyer payment. At block 120,182,210 the designated sink held 9,850,042 GMI. These observations establish deployed mechanics and a failure at the sampled state. They do not establish a July 2022 reserve shortfall, the source of every sink transfer, or a wholly fictitious burn mechanism. [B28, B29; prior branded memorandum, page 13]

Mystery and Duke shared vesting/NFT owner f27 and ProxyAdmin 6ef at the sampled state, linking their control infrastructure to the contracts in the current trace. That linkage does not identify a human. The original GMI token deployer was 0x0d2c8df71c846d0dbc9c8bc75ea39c45d5197dca; the vesting/NFT deployer was 0x3e0f4c7bdbf9bcc4aa9f22b3d03048b3ef2d7199. They must not be collapsed into a single verified address. [Current contract trace; prior branded memorandum, pages 12-13]

The earlier market study verified three PancakeSwap pools and observed about 0.8442 WBNB, 0.00468 BUSD and 0.02076 USDT in quote reserves at separately identified September 5 blocks. It also recovered all 14,751 chain receipts for 24 consecutive blocks around the advertised 18 January 2022 14:30 UTC listing minute and found zero GMI/pool logs in that bounded interval. Those were all-chain receipts, not 14,751 GMI trades. Thin later liquidity and an empty one-minute trade sample establish neither a wash-trading scheme nor the destination of earlier removed assets. The later transaction-level accounting provides the documented sales and transfers in its own stated coverage. [B30; prior branded memorandum, page 14]

The earlier project-history reports also contain dated Canadian/BVI legal analysis. Those reports are preserved as prior evidence editions; their legal analysis was not revalidated or extended for this master consolidation.

## Launchpool: all original funded obligations reconciled

Thirty-nine funding transactions on 19 April 2022 created 7,495 schedules for 7,490 distinct addresses, totaling **15,456,885.882908530406846 GMI**. The opening 10 GMI created two 5-GMI records; the remaining records match the decoded bulk funding inputs. The sum of the deposits' individual historical marks is US$213,274.65 / C$269,237.92, not cash raised.

| Observation | Unpaid original schedules, GMI | Vault balance, GMI | Backing deficit, GMI |
|---|---:|---:|---:|
| Immediately before withdrawal, block 22,786,455 | 14,923,065.568267084392219941 | 14,923,065.568267084392219941 | 0 |
| Immediately after withdrawal, block 22,786,456 | 14,923,065.568267084392219941 | 923,065.568267084392219941 | 14,000,000 |
| 6 Sep 2026 04:08:52, block 120,235,949 | 14,000,207.412329404181026961 | 207.412329404181026961 | 14,000,000 |

Every complete vesting record is byte-identical immediately before and after the withdrawal. Before it, aggregate claimed counters were **533,820.314641446014626059 GMI**. At the current observation, aggregate claimed counters are **1,456,678.470579126225819039 GMI**. All original schedules had matured by 14 January 2023 at 17:29:53 UTC.

The current identity is exact in integer token units:

**15,456,885.882908530406846 funded − 1,456,678.470579126225819039 claimed − 14,000,000 removed = 207.412329404181026961 held.**

Independent decoding of all funding inputs and historical/current records found no amount, owner or nonce mismatch. Current non-claimed fields match their earlier values; claimed counters only increase. Of the 7,495 schedules, 684 show claims: 290 fully claimed, 394 partially claimed, and 6,811 never claimed.

This closes the **aggregate accounting of the original funded book**. It does not constitute a dated census of every intervening token movement, rule out offsetting intermediate refill/withdrawal cycles, or cover hypothetical records for wholly different unfunded addresses. Equal deficits at two observations do not prove the deficit was constant at every intervening block.

The selected 587,755.519557566-GMI allocation requires a separate timing distinction. Immediately after the November withdrawal, the vault could still cover that one allocation, although the full funded book was already short. On **24 January 2023 at 15:45:16**, a normal claim of **8,309.56763892731 GMI** lowered the vault from **591,902.853950097638463553** to **583,593.286311170328463553 GMI**, below the selected still-unclaimed allocation. The [receipt](https://bscscan.com/tx/0x7f556eb1d5da208355961506485c529d11ee850d5ebf136188a9a5e20dc202e5) and before/after balances verify this crossing. Its claim-time mark was about **US$0.75 / C$1.00**. It is a documented crossing, not a proven first-ever crossing.

## How the November tokens left the vesting contracts

The Launchpool vesting implementation active before the November changes had no ordinary owner-withdrawal function. The historical transaction shows a different mechanism: administrative control temporarily changed the implementation, granted a spending allowance, and restored the original implementation. A later transaction used that allowance to transfer tokens out. Restored code alone would not reveal the earlier permission grant.

| 5 Nov UTC | Verified action | Evidence |
|---|---|---|
| 06:14:38 | Three proxies temporarily upgraded to 0x1ee3…e6fb; each grants maximum GMI allowance to Safe 0x9362…25f3; original implementations restored. | [transaction](https://bscscan.com/tx/0x4af5d1dccd4008191749c6f193b552edd4e2d10d96028661eed4d508b8901a63) |
| 06:45:09 | 23m + 14m + 7m GMI transferred from three contracts into 0x35dc…5422 using transferFrom. | [transaction](https://bscscan.com/tx/0xce306e566653d227a138975f721436d91d457d81ebc32d9cd4386e2fb7455f48) |
| 06:45:39 | Withdrawal executor 0x343c…235e sends 0.019849782233850894 BNB to 0x35dc…5422 for subsequent activity. | [transaction](https://bscscan.com/tx/0xb954f172ba0faed75a15967fce0e72a52ee674fd585d9d1e5385199c72f82a17) |
| 06:51:21 | All 44m GMI sold through router 0x1111…097d; 5,174.293394005109506048 BUSD received by 0x35dc…5422. | [transaction](https://bscscan.com/tx/0x7096720b8dc95afac5ad1029a489ce8dd2b2dcb5ff78e960fcb5e10d03acd8aa) |
| 07:15:11 | 5,174 BUSD sent from 0x35dc…5422 to 0x96f0…aeb6. | [transaction](https://bscscan.com/tx/0x34bfa37b43fc0426e45ffcd3af9927be6495d4710f340f7f80e09d2fc41fe1b4) |
| 07:15:20 | 0x4727…7c95 funds 0x96f0…aeb6 with 0.00084 BNB. | [transaction](https://bscscan.com/tx/0xfce9f602e9b578c45f056eaa29343e0932d46f796d3fcb9a9b2dc326e1367a7a) |
| 07:15:32 | The same 5,174 BUSD moves from 0x96f0…aeb6 to 0x4727…7c95. | [transaction](https://bscscan.com/tx/0x7702b5e67906c5eb1dea5d1fdde0f7ade3e37cb5cd657944bd539ed460791e48) |
| 07:15:41 | Remaining 0.000502984 BNB swept from 0x96f0…aeb6 back to 0x4727…7c95. | [transaction](https://bscscan.com/tx/0xfc4c26165b9fad6ae7aa5c69b0763f4bed1af11f97ecebb9112793ca121303c4) |

The original receiving wallet retained 0.293394005109506048 BUSD and no GMI at the checked later state. The two intermediary wallets' subsequent top-level transactions were accounted for using their nonces and receipts. Swap-routing intermediate WBNB/BUSD legs are preserved in the evidence but excluded from ledger endpoint totals to avoid repeated counting.

The earlier [Ethereum explorer label](https://etherscan.io/address/0x4727250679294802377dd6ca6541b8e459077c95) is now supported by stronger, BSC-specific business provenance. A **10 May 2025** reply by the **Administrator FixedFloat** account on its [BestChange listing](https://www.bestchange.ru/fixedfloat-exchanger-79.html) names the exact BSC address **0x4727250679294802377dd6ca6541b8e459077c95** among the service's main outgoing addresses. FixedFloat's [own FAQ](https://ff.io/ru/faq) links that listing. This is a provider-attributed statement through an endorsed channel; it does not independently authenticate the human poster.

The statement postdates the November 2022 transfers. Historical custody, the intermediary's order assignment and any payout still require provider confirmation. The gas-funding and immediate-sweep sequence is consistent with service collection, an inference rather than an order match. Other customers' allegations on the review page are excluded. No specific customer or bank payment is established.

## Which keys authorized it

Historical Safe owner/threshold calls and cryptographic recovery of the transaction signatures agree:

| Role | Safe / administrator | Signing address | Required signatures |
|---|---|---|---|
| Permission grant | 0x6bf55810ab061a016a968016818a6e1246aa8b5a | 0x538a8b615e98e87d025c4336be44e4b8588277c7 | 1 of 1 |
| Three token withdrawals | 0x9362ced428b4179650252ad87731240b32ef25f3 | 0xafd9cfc21ee553ef9c0f3e5525b077b12d0dc3f9 | 1 of 1 |

The approval signer authorized two Safe calls; the withdrawal signer authorized three. Both Safes pointed to the Safe 1.3.0 L2 singleton whose runtime matched the official deployment artifact. These were single-owner smart accounts at the relevant blocks; the word “Safe” does not establish approval by several people. The transaction submitter paying gas was a separate address, not automatically the owner of the signing key.

Safe 0x9362…25f3 changed its sole owner from 0x7e01…7445 to 0xafd9…c3f9 on **19 September 2022**, transaction [0x958512…](https://bscscan.com/tx/0x958512439479d367fc0afd13e8928f810dfe40b4945b084bc51fffedc5b9627b). The approval Safe was created by its sole owner 0x538a…7c7 on **4 November 2022**, transaction [0x2ecfae…](https://bscscan.com/tx/0x2ecfaeb4b20fedb2a1d0fd838c01cc9e26e898c48284d74062898861eab1bda5). No verified public evidence identifies the humans controlling these keys.

GamiFi [announced Eleanor Rooney as CEO on 1 September 2022](https://gamifi-launchpad.medium.com/new-ceo-for-gamifi-451f0e5a2147), thanking Laura for her prior leadership. That announcement precedes the September owner change and November transactions. Neither Laura's earlier role nor Eleanor's later title identifies either person as a signer or establishes personal responsibility for these transfers.

GamiFi's [3 October 2022 update](https://gamifi-launchpad.medium.com/gamifi-update-f8d6326f1780), signed by Eleanor Rooney as CEO, announced a pause in IDOs and reduced activity focused on GMI performance. This is operating context, not transaction-specific authorization for the November withdrawals.

## Newly verified handovers: vesting control and upgrade control

Three previously undated transfers are now verified through successful receipts, direct `transferOwnership(address)` calldata, matching ownership events and six immediately adjacent historical owner checks:

| UTC | Contract / control change | Transaction |
|---|---|---|
| 2022-09-29 08:24:51 | Launchpool owner: 3e0f…7199 → f27f…c27b | [receipt](https://bscscan.com/tx/0xa8b12962f2cecd9136794c2bef6c462c4b88d85ce0f9ba98275f4b033eb8bf75) |
| 2022-11-04 04:29:30 | Shared ProxyAdmin owner: 3e0f…7199 → 538a…7c7 | [receipt](https://bscscan.com/tx/0xadbe145db91127aa89e416895092f4865b2c966ea5b3d2c39e359372b769bb66) |
| 2022-11-05 05:51:26 | Shared ProxyAdmin owner: 538a…7c7 → approval Safe6bf | [receipt](https://bscscan.com/tx/0xe1391addc79820a59676b049d2a4545719cbdc241b5d12164caab588beb5982a) |

Each was sent directly by the previous recorded owner. The original handover sender was **0x3e0f4c7bdbf9bcc4aa9f22b3d03048b3ef2d7199**, already linked to the project's deployments and Launchpool funding. The 29 September recipient was **0xf27f9a2eb9b2c70d32476cf9dc2d74ca4e61c27b**. The 4 November recipient was **0x538a8b615e98e87d025c4336be44e4b8588277c7**, which created the approval Safe later that morning.

The 5 November handover took place **23 minutes 12 seconds before** the established temporary-upgrade/allowance transaction. During that later transaction, the Safe passed ProxyAdmin ownership to orchestration contract **0x5e0cf46e675b985f992c5fafd15e56e8c9a94387**; the orchestrator completed the upgrade/allowance/restore sequence and returned ProxyAdmin ownership to **538a**. That within-transaction sequence was already established in the earlier Safe evidence.

This distinguishes ownership of the vesting implementation's functions from authority over replacement code. They moved on different dates. Moving the administrator into a Safe did not itself establish another human decision-maker: the later Safe signatures recover the same 538a key. The three newly located events and adjacent states are verified; this is not a census of every lifetime ownership transition.

The events provide precise targets for dated custody, handover, mandate and authorization records. They identify technical control, not the humans holding the keys or the commercial entitlement to assets. All three occur after GamiFi's 1 September CEO announcement; chronology alone assigns neither Laura nor Eleanor responsibility.

## Private vesting: all 120 million GMI and the beneficiary's token balance

On **18 January 2022 at 15:56:50**, the original GMI deployer funded 120,000,000 GMI for beneficiary **0x36048413c4edf0cf3e633aab317fcd9824dfb4d4** in private vesting contract **0x74e0ddf89807107378beb02e6bc504243e0cdf6c**. The [funding transaction](https://bscscan.com/tx/0xac39350f0f652c95dfb73e0cd8f2028a2c8aa34a51d081374a6c850647625787) sets zero initial release, zero cliff and 360-day linear vesting. Category 5 has no human-readable definition in the verified implementation; it cannot identify the allocation as a particular person's, team's or investor's property.

At funding, multiplying the marginal token quote gives **US$5,769,088.34 / C$7,228,090.79**. The pool held only about **3.983m GMI and 413.8 WBNB**. This highly theoretical mark is not evidence of a multi-million-dollar payment or realizable sale.

All five successful payout receipts are now reconstructed:

| UTC | GMI | Historical US$ mark | Historical C$ mark | Receipt |
|---|---:|---:|---:|---|
| 2022-11-04 14:25:40 | 96,645,563.271604938271604938 | 21,061.17 | 28,468.38 | [transaction](https://bscscan.com/tx/0x6f2c3e43f94de965feaf666ad8a35a6951c72a9367360d9dc138d236902e787f) |
| 2022-12-06 10:46:01 | 10,615,821.759259259259259259 | 756.09 | 1,031.99 | [transaction](https://bscscan.com/tx/0xf692b324a95a159bd4c5142cd7eed711211ac0b4e85912fa336cfde0ca961453) |
| 2022-12-08 06:32:39 | 608,016.975308641975308642 | 59.66 | 81.03 | [transaction](https://bscscan.com/tx/0x325e3df49c8f81d74d5343bff786dd8d08f4996d798cefff4a31dcbf8e4b1078) |
| 2022-12-14 16:01:19 | 2,131,635.802469135802469136 | 171.20 | 232.17 | [transaction](https://bscscan.com/tx/0x03aa7debf2d0fe654828d9b560902166f050f499d1be2cd20dadcf69c22e8639) |
| 2023-01-20 05:38:45 | 9,998,962.191358024691358025 | 811.64 | 1,089.31 | [transaction](https://bscscan.com/tx/0x8657b3b3182771a12734fa434536f6f2a667246a2f94998546da301f7e464f3d) |

The first three rows are the previously unresolved **107,869,402.006172839506172839 GMI**. Their individual claim-time marks sum to **US$21,876.92 / C$29,581.40**. Including the two previously studied payouts gives exactly **120 million GMI**, with claim-time marks totaling **US$22,859.76 / C$30,902.87**. Claims and later sales are different events and must not be summed.

The beneficiary's reconstructed GMI balance also closes exactly from immediately before the first November claim through its last February 2023 disposal:

| GMI entering beneficiary | Exact GMI | GMI leaving beneficiary | Exact GMI |
|---|---:|---|---:|
| Five vesting claims | 120,000,000 | Direct GMI sale inputs | 103,642,447.956409389183293472 |
| Tokens returned from liquidity positions | 29,574,727.895903672410206412 | Tokens contributed to liquidity | 27,942,179.939494283226912940 |
| Separate incoming transfer | 9,900 | Forwarded to exchange intermediary | 18,000,000 |
| **Total in** | **149,584,627.895903672410206412** | **Total out** | **149,584,627.895903672410206412** |

Opening and ending GMI balances are both zero. The separate 9,900-GMI receipt is [transaction 0x782a…de7ae](https://bscscan.com/tx/0x782a3cb1e15038899222d883a233bcf031c20236ba0b8a3f8584052d799de7ae), from 0x391a51d884b240908a88e1e757ec42189d294423. Liquidity tokens were mixed with the vested allocation; individual fungible units cannot be labeled as uniquely belonging to one source after mixing.

The 42 direct GMI sale outputs are:

| Asset actually received | Exact quantity | Historical US$ | Historical C$ |
|---|---:|---:|---:|
| BNB | 12.733084792018608967 | 3,993.65 | 5,359.27 |
| WBNB | 2.296091425541797281 | 820.80 | 1,109.48 |
| BUSD | 5,361.649777056501864007 | 5,362.44 | 7,219.59 |
| CAKE | 13.065639141470576526 | 49.50 | 67.13 |
| **Gross output value** | Different assets; no unit total | **10,226.39** | **13,755.46** |

This total includes the earlier five selected sales worth US$756.14 / C$1,021.91; those five are not additional proceeds. It measures cryptoassets received, not profit, a bank withdrawal or Laura's income.

Three liquidity additions also supplied **11.779827980541797281 BNB gross**; trace-verified refunds totaled **0.000000000000000003 BNB**, giving **11.779827980541797278 BNB net supplied**. Two redemptions returned **11.149287235974376070 BNB** alongside the GMI shown above. Received and redeemed LP shares total **9,177.891351247917090180 LP**. These position movements are separate from the 42 direct-sale receipts and cannot be added as additional sale profit.

**Correction to the earlier selected report:** the later CAKE transaction was related to the GMI route. A GMI sale received **13.065639141470576526 CAKE**, then [transaction 0x30c5…aca71](https://bscscan.com/tx/0x30c5e3af5fa69cf54e59ec46a3cf3c74ffea59cd3e795cf6aa8923b6482aca71) converted that CAKE into **49.354088681602483584 BUSD**. The CAKE receipt is already included in the direct-sale total. Its later BUSD conversion is shown separately, not counted again as new GMI-sale proceeds. A failed GMI swap remains excluded from financial transfer totals.

All **100 normal transactions sent by the beneficiary**, nonces 0–99, were recovered and receipt-checked. They span 1 February 2022 through 4 April 2023; the nonce remained 100 at sampled block 120,238,607. Nine failed transactions contribute no completed asset flows. This completes the normal sender inventory through that observation; it does not establish a complete census of third-party incoming transfers or internal native funding.

The **5,361.649777056501864007 BUSD** received in GMI swaps plus the later **49.354088681602483584 BUSD** from the CAKE conversion total **5,411.003865738104347591 BUSD**. That equals exactly the ten BUSD transfers to **0xf4f86e37815217ed73ae817a4e5164d56315b1d7**. Their individual forwarding-date marks total **US$5,411.28 / C$7,278.79**. This is an aggregate flow reconciliation, not additional income or identification of the recipient's human owner.

An earlier separate 2,000-BUSD transfer on 11 March 2022 went to 0x391a51d884b240908a88e1e757ec42189d294423. Seven normal native transfers also sent **27.336801380291603498 BNB** to 0xf4f8…b1d7. Those native balances were commingled with liquidity returns and external funding; the full BNB forwarding amount cannot be assigned to GMI sale income. The **2.296091425541797281 WBNB** sale output was later unwrapped into the same quantity of BNB, an overlapping conversion preserved separately in the ledger.

## Onward wallet: payments back to the beneficiary and further address intersections

The selected recipient **0xf4f86e37815217ed73ae817a4e5164d56315b1d7** now has a receipt-verified inventory of **24 normal outgoing transactions**, nonces 50–73, from **7 October 2022 through 16 May 2023**. There are 23 successful transactions and one failed swap, represented only by its actual network fee. All 54 transfer and fee records carry exact base units, transaction identifiers and separate historical USD/CAD marks. This is a bounded sender inventory; inbound activity, third-party allowance transfers, earlier transactions and transactions after nonce 73 are not comprehensively inventoried.

The clearest new link is a **1 BNB** payment from this wallet back to private beneficiary **3604…b4d4** on **4 November 2022 at 14:25:04 UTC**, worth approximately **US$356.08 / C$481.31** at the historical mark. Its [successful transaction](https://bscscan.com/tx/0x1d511630993eefca8a67f6a63e189a6e25054f340e0d8867a00c6b5fb67cfbf3) preceded the beneficiary's **96,645,563.271604938271604938 GMI claim by 36 seconds**. Three further payments—3 BNB and 5 BNB on 6 November, then 3 BNB on 7 November—bring the selected reverse-direction total to **12 BNB**. This directly establishes a funding and counterparty relationship; purpose, business authority and human control remain unproved.

| New observed movement | Exact asset amount | Historical US$ mark | Historical C$ mark |
|---|---:|---:|---:|
| Back to the private beneficiary, four transfers, 4–7 Nov 2022 | 12 BNB | 4,173.22 | 5,638.53 |
| To earlier Launchpool token source 78d0…14c3, 7 Nov 2022 | 0.5 BNB | 166.41 | 224.54 |
| To earlier project-contract recipient 35b1…b5f3, 7 Nov 2022 | 0.5 BNB | 164.35 | 221.75 |
| To unassigned recipient ba4d…bf53, 7 Dec 2022 | 6,590 BUSD | 6,589.99 | 8,988.75 |
| To the same unassigned recipient, three transfers, 21 Oct–7 Dec 2022 | 25,906.285983337104699148 USDT | 25,906.29 | 35,478.50 |
| 11 BNB conversion: output returned to the sending wallet, 16 May 2023 | 3,398.645844082231 USDT | 3,399.33 | 4,574.14 |

The two 0.5 BNB payments intersect with earlier established transactions: **0x78d09e1435e1906878621bcb0aaa9d47561214c3** supplied 15,456,876 GMI to the original deployer on 19 April 2022; **0x35b119730f79881dac623dc51c831c6a04cab5f3** received project-contract withdrawal ID 4's 2,000 BUSD on 23 March 2022. The corresponding new transaction hashes and individual marks are in the ledger and record-request briefs. The intersections establish address relationships, not a shared human owner.

The other direct recipient is **0xba4d665059c97d6baa42e097707a504aecafbf53**. No reliable public business/service assignment was established for it in the searches performed. Its subsequent history is an open public-chain lead; this pass does not trace it onward. The May conversion returned USDT to the sending wallet and supplies no bank-payment evidence. Its swap contract remains unattributed in this report because a primary BSC deployment attribution was not established.

These values must **not be added to the earlier GMI-sale proceeds**. The onward wallet had commingled activity. It sold **4,816,523.694499999999787008 GMI** across three earlier swaps, including an October sale equal in quantity to a selected September receipt of 161,278.104499999999787008 GMI. It also made stablecoin/BNB conversions and a 0.02 BTCB conversion, and transferred a larger existing USDT balance. These events precede or overlap the selected private-claim period and are not all attributable to its 120m allocation.

Likewise, the earlier **27.336801380291603498 BNB** sent from the private beneficiary to this wallet remains a **gross directional total**. The newly documented 12 BNB sent back makes it unsuitable as a net-receipt or personal-income figure. Neither matching selected amounts nor close timing removes commingling. The address prefix “f4f” is simply an address abbreviation and does not establish FixedFloat control.

USD amounts use the prior completed block's supported oracle/reference mark, with observation ages preserved. USDT is valued using its historical USDT/USD feed, rather than assumed to equal exactly US$1. BTCB's separate ledger mark is explicitly a BTC-underlying reference valuation, not a verified BTCB market execution. CAD uses Bank of Canada's daily rate for the date or the preceding available business day. Values are estimates of cryptoasset amounts, not proof of fiat receipts.


## Expanded exchange route: 18 million GMI

Four token transfers from the beneficiary passed through **0x9564f530d9f270a48c510a92c97b59248cefd464** and then arrived at two exchange-associated wallets:

| UTC | GMI | Historical US$ mark | Historical C$ mark | Receipt |
|---|---:|---:|---:|---|
| 2022-11-04 15:00:29 | 5,000,000.000000000000000000 | 877.32 | 1,185.87 | [transaction](https://bscscan.com/tx/0x7f8323049c6585d0dee94b8ba6b7dcb96d9bd0f2ac11617a00ca2299cb7ae3a8) |
| 2022-11-08 17:48:21 | 5,000,000.000000000000000000 | 576.08 | 774.31 | [transaction](https://bscscan.com/tx/0xb0b3bf6768b4cb92820c90c4aca9a2103e3b49c753b31bf6258916b3dab5855c) |
| 2022-12-08 02:27:14 | 5,000,000.000000000000000000 | 467.87 | 635.46 | [transaction](https://bscscan.com/tx/0xff3ac1adab98247b4a1c468612618e00f322c6a7ab66b3b9825150a7f7aa4d8f) |
| 2023-01-21 02:34:05 | 3,000,000.000000000000000000 | 231.98 | 311.33 | [transaction](https://bscscan.com/tx/0x2e371d5d37cc3deaef36f8c4798f0a18256257304d8eb4db697e6b4414cec02e) |

The first three transfers total **15 million GMI** into **0x2e8f79ad740de90dc5f5a9f0d8d9661a60725e64**. Current [MEXC proof-of-reserves disclosures](https://www.mexc.com/nb-NO/proof-of-reserve?page=34), successfully retrieved through search indexing, list that exact address; explorers also label it MEXC 5. Direct page opens did not return the same address data. This establishes a current public association; historical custody and customer credit on the 2022 dates still require confirmation.

The January **3 million GMI** arrived at **0x4982085c9e2f89f2ecb8131eca71afad896e89cb**, which MEXC identified as its BSC wallet in its [own July 2021 disclosure](https://mexcglobal.medium.com/recent-rumors-against-mexc-global-clarified-7205e6828907). The four arrivals' marginal marks total **US$2,153.25 / C$2,906.98**. No exchange sale at those prices, credited customer or fiat withdrawal is established. Sharing an intermediary does not prove all four deposits belonged to the same exchange account.

## Project-contract stablecoin withdrawals and shared operational links

The archived official application identifies project contract 0x56c0…46c7f. Seven successful receipts show withdrawals totaling **63,001.817377359365034843 BUSD**, historically marked at **US$63,019.16 / C$79,740.69**. Their sum reconciles to the nine current project records' funded-total counters. That is not a lifetime audit of investor deposits or company revenue.

| Project ID | UTC | BUSD | US$ mark | C$ mark | Recipient | Receipt |
|---|---|---|---|---|---|---|
| 1 | 2022-03-10 15:25:05 | 252.5 | 252.51 | 322.61 | 0x8fea0bb760218398d32d4a9ef18553c403e3c2a0 | [receipt](https://bscscan.com/tx/0x4b0b66e2f020479b6381a1b31be240bfb86347cf1813ddb520c094576e6158df) |
| 3 | 2022-03-11 09:35:55 | 110 | 109.99 | 139.91 | 0x8fea0bb760218398d32d4a9ef18553c403e3c2a0 | [receipt](https://bscscan.com/tx/0x4389510604c93f928c4e1a2f6fda07979d792228de1b6bb66a8242a7a7ee05b5) |
| 7 | 2022-03-18 06:58:39 | 23722.715761539594859905 | 23,730.18 | 29,940.37 | 0xd2b806f9c0352a267ce7ccf33e74d68c070d6171 | [receipt](https://bscscan.com/tx/0xa68d28501388dd1939659be1a24f6fbed8c0c22d6df5bbe43196ff408b3ffba4) |
| 6 | 2022-03-18 12:23:52 | 28421.141280969119319259 | 28,430.09 | 35,870.24 | 0x56aa83035aea8bfeb9e395a51607cc4621649aa2 | [receipt](https://bscscan.com/tx/0x4e2b2cebb9895bb8ed1ffa817e730273d9271e97e559a2fdd7ba2d4e86fd5299) |
| 4 | 2022-03-23 14:58:07 | 2000 | 2,000.00 | 2,514.20 | 0x35b119730f79881dac623dc51c831c6a04cab5f3 | [receipt](https://bscscan.com/tx/0x33f6c2ae7893cf8763b5306d4220780592390cc22ab9399034f4b3ac6ee09683) |
| 8 | 2022-05-23 11:50:16 | 3775.228767123287671432 | 3,775.69 | 4,843.83 | 0x56aa83035aea8bfeb9e395a51607cc4621649aa2 | [receipt](https://bscscan.com/tx/0xfb51cbbf265af6b604ba3499d1608f36ab04a57eb3a71a4d5cbe3c6fe807d780) |
| 9 | 2022-06-22 08:29:58 | 4720.231567727363184247 | 4,720.69 | 6,109.52 | 0x56aa83035aea8bfeb9e395a51607cc4621649aa2 | [receipt](https://bscscan.com/tx/0x757fe0ce1d898fff34b0d4c4f58f2fc7610d3821eacc51c43d7e7e6ac0edcf63) |

IDs 6–9 account for 60,639.317377359365034843 BUSD. The earlier IDs 1, 3 and 4 account for 2,362.5 BUSD and should stay separate until their purposes are documented. Project names, commercial purpose, contractual entitlement and recipient ownership have not been independently established.

The same address **0x3e0f4c7bdbf9bcc4aa9f22b3d03048b3ef2d7199** initiated withdrawals for IDs 4, 6, 7, 8 and 9 and funded the Launchpool vesting contract. It received **15,456,876 GMI** from **0x78d09e1435e1906878621bcb0aaa9d47561214c3** at 13:32:12 on 19 April, [receipt](https://bscscan.com/tx/0x00f1ad6f5d7560d5325d08d0afcf253a99b46d588a6509abb37349bacdea965f). Later that day, 39 deposits moved 15,456,885.882908530406846 GMI into Launchpool, including an initial 10 GMI transfer. The bounded upstream history also contains a 5 GMI transfer; these are not a full funding-wallet balance reconciliation.

Recipient **0x56aa…9aa2** received 36,916.601615819770174938 BUSD across IDs 6, 8 and 9. This repeated recipient and **0xd2b8…6171**, which received project 7's 23,722.715761539594859905 BUSD, are concrete accounting leads. No personal or corporate key ownership has been proved for them.

At the sampled current September 2026 blocks, the project contract owner and the private vesting owner/proxy administrator equal **0xf27f9a2eb9b2c70d32476cf9dc2d74ca4e61c27b**, also seen in prior GMI/NFT/Launchpool control checks. Current common control does not prove control by that address throughout 2022–23, and it does not identify a human.

## Contract and address directory

| Role | Full BSC address |
|---|---|
| Canonical GMI token | [0x93d8d25e3c9a847a5da79f79ecac89461feca846](https://bscscan.com/address/0x93d8d25e3c9a847a5da79f79ecac89461feca846) |
| Launchpool vesting proxy | [0xf50488dc8339fb7d1d5a8e8b401c4a5d71a090bb](https://bscscan.com/address/0xf50488dc8339fb7d1d5a8e8b401c4a5d71a090bb) |
| Other November source: 23m | [0xee57b1241f243a1a794f60ffa643d202188d31d9](https://bscscan.com/address/0xee57b1241f243a1a794f60ffa643d202188d31d9) |
| Other November source: 7m | [0xba306306b117a25145d58c67a03deb7f22ee2a3a](https://bscscan.com/address/0xba306306b117a25145d58c67a03deb7f22ee2a3a) |
| ProxyAdmin used in November | [0x6ef316a4e3d378e5b75599daeca94c86d5ce4475](https://bscscan.com/address/0x6ef316a4e3d378e5b75599daeca94c86d5ce4475) |
| Temporary implementation / withdrawal helper | [0x1ee38d535d541c55c9dae27b12edf090c608e6fb](https://bscscan.com/address/0x1ee38d535d541c55c9dae27b12edf090c608e6fb) |
| Combined 44m recipient | [0x35dc4a16db1e30036fee83e733ee065ad8535422](https://bscscan.com/address/0x35dc4a16db1e30036fee83e733ee065ad8535422) |
| November stablecoin intermediary | [0x96f0ae9dc91983d87379cf7bbe2cebc69123aeb6](https://bscscan.com/address/0x96f0ae9dc91983d87379cf7bbe2cebc69123aeb6) |
| Address supported by later FixedFloat statement | [0x4727250679294802377dd6ca6541b8e459077c95](https://bscscan.com/address/0x4727250679294802377dd6ca6541b8e459077c95) |
| Private vesting proxy | [0x74e0ddf89807107378beb02e6bc504243e0cdf6c](https://bscscan.com/address/0x74e0ddf89807107378beb02e6bc504243e0cdf6c) |
| Selected private beneficiary | [0x36048413c4edf0cf3e633aab317fcd9824dfb4d4](https://bscscan.com/address/0x36048413c4edf0cf3e633aab317fcd9824dfb4d4) |
| Private token intermediary | [0x9564f530d9f270a48c510a92c97b59248cefd464](https://bscscan.com/address/0x9564f530d9f270a48c510a92c97b59248cefd464) |
| MEXC-disclosed wallet | [0x4982085c9e2f89f2ecb8131eca71afad896e89cb](https://bscscan.com/address/0x4982085c9e2f89f2ecb8131eca71afad896e89cb) |
| Additional currently disclosed MEXC wallet | [0x2e8f79ad740de90dc5f5a9f0d8d9661a60725e64](https://bscscan.com/address/0x2e8f79ad740de90dc5f5a9f0d8d9661a60725e64) |
| Private route onward wallet | [0xf4f86e37815217ed73ae817a4e5164d56315b1d7](https://bscscan.com/address/0xf4f86e37815217ed73ae817a4e5164d56315b1d7) |
| Project contract | [0x56c0cb2d047b69278f49b4759c1718436a546c7f](https://bscscan.com/address/0x56c0cb2d047b69278f49b4759c1718436a546c7f) |

## Public business records and the remaining document trail

The expanded review of the corroborated GamiFi repository covered **143 reachable commits, 384 unique file blobs and all 34 public pull-request heads**. Five public Launchpool repository histories were also checked for the five critical signing/admin addresses. No match identified a key custodian or mandate. The latest fetched GamiFi commit is dated **24 August 2022**, limiting what this source can say about September and November custody changes.

Two public development records provide additional audit-document targets: [PR13, fix audit report](https://github.com/sheandev/gamifiContracts/pull/13), opened 4 January 2022 and closed unmerged on 23 February; and [PR25, Update code for audit](https://github.com/sheandev/gamifiContracts/pull/25), merged 28 March 2022. The saved primary GitHub API records preserve exact dates and commits. Neither record names an auditor, attaches a verified audit report, or identifies a wallet custodian. No GamiFi-named report was located in PeckShield's complete current public publication tree; that does not rule out a private engagement and does not attribute these PRs to PeckShield.

GamiFi's archived terms, captured on 7 October 2022 and displaying a 25 January revision date, identify **GamiFi Limited** as a BVI company and anticipate account identity-verification records. They supply no company number or specific-wallet identity. The original successful capture remains preserved; a fresh web open in this follow-up failed.

A supplied [official BVI public-search](https://www.bvifsc.vg/public-search) screenshot showing **Gamifi Limited, entity number 2082070**. A free [i-BVI directory entry](https://i-bvi.com/company/gamifi-limited_978843) separately matches that name and number and lists **12 November 2021** as its registration date. The date remains secondary-source evidence; an official certificate was not obtained. The screenshot supplies no status, registered agent or officers. This supersedes the earlier statement that no matching registry number had been obtained.

Section 2 of the preserved GamiFi terms also attributes creation and release of GMI to **GamiFi Limited**. Its matching name and BVI jurisdiction, alongside the number-bearing registry screenshot, support a specific corporate record target. The terms themselves do not supply number 2082070 or a wallet-to-human mapping. [Avark's first-party case study](https://avark.agency/case-studies/gamifi) documents work on GamiFi's branding, website and launchpad application. Engagement, invoice and handover records could help identify the contracting entity and authorized contacts; no such private records or key assignment were obtained. Appendix B records the source distinctions and free-search limits.

Appendix A contains unsent, transaction-specific briefs for corporate/key custodians, FixedFloat, MEXC and audit/deployment record holders. They request custody evidence, account/order mappings and business authority records; they do not request private keys or passwords. No messages, requests or paid searches were submitted.

## Remaining ownership and record links: exact targets

Exact-address public searches and the expanded public repository review did not identify the humans controlling the November signers, the former Safe owner, the transaction executor, the common current contract owner, or the private beneficiary. This is a bounded negative finding, not proof that no identifying record exists. A signature proves use of a key, not a legal name or the signer's commercial authority.

| Record holder / lead | Concrete identifiers | Record needed to resolve the gap |
|---|---|---|
| GamiFi and relevant key custodians | Permission signer 0x538a8b615e98e87d025c4336be44e4b8588277c7; withdrawal signer 0xafd9cfc21ee553ef9c0f3e5525b077b12d0dc3f9; former owner 0x7e0135da76bb6cdb35ac5f1342808925e3ef7445; executor 0x343cebd1e7d1a6838cd8b82f6238b29ad78e235e | Key assignments and handover records; mandates; instructions and approval records for the 19 September owner change and 5 November permission/withdrawal transactions |
| Private-allocation record holder | 120m funding receipt and beneficiary 0x3604…b4d4; current common owner 0xf27f9a2eb9b2c70d32476cf9dc2d74ca4e61c27b; onward recipient 0xf4f86e37815217ed73ae817a4e5164d56315b1d7 | Allocation agreement, beneficial ownership and custody records; recipient identification, business purpose and settlement records |
| MEXC | All four dated arrival hashes above, chain ID 56, exact GMI contract, amounts, intermediary and two destination addresses | Historical custody; assigned deposit address and credited account; account authority/identity information actually held; associated orders, fills and withdrawals; record-retention status |
| FixedFloat, supported by later provider-attributed address statement; historical confirmation required | 5,174 BUSD deposit/sweep on 5 Nov 2022 at 07:15:11/07:15:32; hashes 0x34bfa…fe1b4 and 0x7702…91e48 in the November table; intermediary 0x96f0…aeb6; destination 0x4727…7c95 | First confirm historical service custody/operator; then any order mapping, payout asset/network/amount/address/transaction, refunds and customer or verification information actually retained |
| Project withdrawal recipients / accounting record holders | Seven project IDs and receipts above, particularly repeated recipient 0x56aa…9aa2 and recipient 0xd2b8…6171 | Project identities, funding agreements, invoices, entitlement, settlement and any onward accounting records |

The evidence archive contains a full record-location schedule with complete hashes and addresses. No requests were sent. MEXC's [current law-enforcement guidance](https://www.mexc.com/support/article/law-enforcement-guidelines-4403594593434) restricts its LEORS process to eligible agency/judicial officials and describes formal disclosure and preservation requirements. This is not a public account-lookup tool or a guarantee that historical records remain.

FixedFloat's [guide](https://ff.io/en/blog/guides/how-to-exchange) describes exchanges without registration, so the crucial missing item may be an **order and payout mapping**, rather than a named exchange account. Its [support page](https://ff.io/support) publishes the published organizational contact for law enforcement and the published organizational contact for victims. Any approach must first confirm the address's historical relationship to the service. Amount/timing similarities among pooled-wallet outputs do not prove a particular customer's payout.

No bank document, wire reference, named bank beneficiary or verified Laura-owned receiving wallet was located. Cayman incorporation of an associated entity, if established separately, is not evidence of a Cayman bank account. The September CEO succession neither identifies the November key holders nor, by itself, proves or disproves any former or current executive's involvement.

## Valuation method and reproducibility

For a transaction in block N, GMI marks use the GMI/WBNB pool reserves at block N−1 multiplied by the Chainlink BNB/USD answer available at that same historical block. This is the previous completed block, not necessarily the state immediately before a transaction within block N. Each row preserves its block, exact token quantity, price and source age. BUSD and BNB proceeds use their own historical USD oracle answers. BUSD is not silently treated as exactly one US dollar.

The main pool is 0x58d4b61983ca0afe6e352e90719f403e24e016f4; BNB/USD feed is 0x0567f2323251f0aab15c8dfb1967e4e8a7d42aee; BUSD/USD feed is 0xcbb98864ef56e9042e7d2efef76141f15731b82f. The [Chainlink API documentation](https://docs.chain.link/data-feeds/api-reference) defines the decimals and historical observation timestamps used. Successful feed-identity responses and compact official-document excerpts are retained.

Canadian-dollar equivalents use [Bank of Canada daily USD/CAD averages](https://www.bankofcanada.ca/rates/exchange/daily-exchange-rates/), taking the previous available business-day observation on weekends and holidays. These are dated daily averages, not transaction-time FX quotes. For example, April 19 uses 1.2624 CAD/USD; November 5 uses November 4's 1.3517; December 14 uses 1.3561. The workbook shows the FX observation date separately.

Price-age limitations matter. The November withdrawal's GMI pool ratio was 15,764 seconds old; the January 20 private claim's ratio was 17,222 seconds old. One June 22 BUSD oracle answer was 79,865 seconds old. They are explicitly identified as then-available marks, not exact contemporaneous exchange fills. A large position can move a shallow pool substantially, explaining why multiplying a marginal quote can exceed actual sale proceeds. The 44m sale's actual BUSD output is therefore the relevant realized on-chain amount.

The workbook preserves exact decimal quantities in text and uses formulas for dollar columns. Spreadsheet numeric precision is limited; JSON/raw integer evidence remains authoritative for exact token units. No total adds across overlapping transfer categories. Each transaction links to its explorer page, while primary RPC receipts and historical calls are preserved in the evidence archive. Some exploratory downloads failed; error responses are not proof of missing transactions.

CAKE outputs use historical Chainlink CAKE/USD feed **0xb6064ed41d4f67e353768aa239ca86f4f73665a1**, with identity and decimals checked. WBNB uses its redeemable BNB underlying mark while remaining labeled WBNB. LP marks use the previous block's reserves and LP supply to value the underlying position; they are theoretical position values, not additional proceeds. The first November private claim used a pool ratio 8,135 seconds old; the January coverage-crossing mark used a ratio 13,519 seconds old. Observation ages are retained in each ledger row.

The follow-up supplies 54 separately valued transfer and fee records from the bounded onward-wallet inventory. These entries track commingled-wallet activity and are not added to the earlier GMI-sale proceeds.

## Coverage, validation and limits

- Full private-allocation payout accounting: five successful receipts, exactly 120 million GMI; no reliance on the current claimed counter alone.
- Beneficiary GMI balance accounting: exact zero residual over the reconstructed disposal period, including the separate 9,900-token inflow and liquidity returns.
- Original Launchpool funded book: all 7,495 records checked against decoded funding inputs and archived pre/post/current state. Independent recomputation confirms zero pre-withdrawal deficit and exactly 14 million GMI afterward and at observation.
- A complete dated lifetime Launchpool transfer census remains outside coverage. Current state and bounded historical observations cannot rule out offsetting intervening movements.
- Human ownership, customer credit, off-chain trades, business entitlement, bank records and intent are not established by these numerical reconciliations.

The workbook's exact-text quantities and the raw integer JSON remain authoritative where spreadsheet floating-point precision rounds low-order digits. Reconciliation formulas use visible source balances and link to all original funded schedules. There is no across-category money total. A separate analyst independently decoded the funding and payout evidence and found no material arithmetic errors.

The evidence archive retains the earlier raw record set for provenance and adds this completed investigation, ledger inputs, calculation scripts, historical RPC responses, record-location schedule and SHA-256 manifest. Earlier selected-only findings within the retained evidence are historical snapshots and are superseded by this report. These findings establish token movement, contract mechanics and measured obligations; they do not establish theft, laundering, fraud or a final human beneficiary.

## Appendix A — Exact record-location and request briefs

Prepared 6 September 2026. **Unsent working briefs for an investigator or properly authorized representative.** No provider, company, individual or regulator has been contacted. No private account or order record has been accessed. These briefs identify evidence to request; they do not certify that it exists, remains retained, or can be disclosed to the requester.

All transaction times are UTC. Blockchain: BNB Smart Chain, chain ID 56. GMI contract: `0x93d8d25e3c9a847a5da79f79ecac89461feca846`. BUSD contract: `0xe9e7cea3dedca5984780bafc599bd69add087d56`.

### 1. Corporate identity and key-custody records

**Corporate record target:** **Gamifi Limited — BVI entity number 2082070**, matching the legal name and jurisdiction in GamiFi's archived terms. The number comes from the supplied official-search screenshot and is corroborated by a free i-BVI directory entry. That directory reports registration on **12 November 2021**; the date awaits official confirmation. The responsible record holder, registered agent, officers and any development/key-custody contractor remain to be identified. A corporate record target does not identify a wallet's human custodian.

**Purpose:** establish who held and exercised each key for the particular actions below, in what capacity, and under what business instructions. A blockchain key and a CEO title are not substitutes for these records.

| UTC | Action | Full transaction |
|---|---|---|
| 2022-09-19 14:24:11 | Withdrawal Safe owner change: 7e01 → afd9 | `0x958512439479d367fc0afd13e8928f810dfe40b4945b084bc51fffedc5b9627b` |
| 2022-09-29T08:24:51+00:00 | Launchpool owner: original deployer → f27 | `0xa8b12962f2cecd9136794c2bef6c462c4b88d85ce0f9ba98275f4b033eb8bf75` |
| 2022-11-04T04:29:30+00:00 | ProxyAdmin owner: original deployer → 538a | `0xadbe145db91127aa89e416895092f4865b2c966ea5b3d2c39e359372b769bb66` |
| 2022-11-05T05:51:26+00:00 | ProxyAdmin owner: 538a → approval Safe6bf | `0xe1391addc79820a59676b049d2a4545719cbdc241b5d12164caab588beb5982a` |
| 2022-11-05 06:14:38 | Temporary implementations, GMI spending allowances, original implementations restored | `0x4af5d1dccd4008191749c6f193b552edd4e2d10d96028661eed4d508b8901a63` |
| 2022-11-05 06:45:09 | 44m GMI transfer, including 14m from Launchpool | `0xce306e566653d227a138975f721436d91d457d81ebc32d9cd4386e2fb7455f48` |

Relevant addresses:

- Original deployer / handover sender: `0x3e0f4c7bdbf9bcc4aa9f22b3d03048b3ef2d7199`.
- Launchpool owner after 29 September: `0xf27f9a2eb9b2c70d32476cf9dc2d74ca4e61c27b`.
- Upgrade-control signer: `0x538a8b615e98e87d025c4336be44e4b8588277c7`.
- Upgrade ProxyAdmin: `0x6ef316a4e3d378e5b75599daeca94c86d5ce4475`.
- Approval Safe: `0x6bf55810ab061a016a968016818a6e1246aa8b5a`.
- Withdrawal Safe: `0x9362ced428b4179650252ad87731240b32ef25f3`.
- Withdrawal signer: `0xafd9cfc21ee553ef9c0f3e5525b077b12d0dc3f9`.
- Former withdrawal-Safe owner: `0x7e0135da76bb6cdb35ac5f1342808925e3ef7445`.
- Transaction executor: `0x343cebd1e7d1a6838cd8b82f6238b29ad78e235e`.

**Requested records:** the key-assignment/custody register and dated handover acknowledgments for these addresses; the relevant corporate or operational mandates; records showing authorized signatories and approvers on the transaction dates; instructions for the temporary upgrade, spending allowance, withdrawals and sale; and any corresponding settlement, refund or liability-adjustment records. Request attestations or custody documentation, **not private keys, seed phrases or passwords**.

For the separate 120m allocation, request the allocation agreement and any platform-account/wallet mapping for beneficiary `0x36048413c4edf0cf3e633aab317fcd9824dfb4d4`, linked to funding transaction `0xac39350f0f652c95dfb73e0cd8f2028a2c8aa34a51d081374a6c850647625787` (18 January 2022). The archived terms anticipate identity-verification records, but do not establish that this particular wallet used the account/KYC process.

Also request any settlement or recipient-assignment record for onward wallet `0xf4f86e37815217ed73ae817a4e5164d56315b1d7`. Its public human/business ownership remains unproved; the address prefix does not identify FixedFloat. The bounded follow-up establishes four BNB payments back to the private beneficiary totaling 12 BNB. One sent 1 BNB at 14:25:04 UTC on 4 November 2022, transaction `0x1d511630993eefca8a67f6a63e189a6e25054f340e0d8867a00c6b5fb67cfbf3`, 36 seconds before the large private claim. Request the instructions, business purpose and counterparties recorded for these transfers.

The same onward wallet paid 0.5 BNB to each of two addresses already present in the project trace: `0x78d09e1435e1906878621bcb0aaa9d47561214c3` at 13:07:05 UTC on 7 November 2022, transaction `0xdcd15c3761db237bf135a6733531ccbf8293f7c96197ea782c1cecb3d1822f72`, and `0x35b119730f79881dac623dc51c831c6a04cab5f3` at 14:00:56 UTC that day, transaction `0x2640f592d8b45f512e121a014b7de6b7293aaf8b06785bd388e66d9c13195520`. These are specific counterparties for accounting-record questions; no common human ownership is inferred.

Another unassigned recipient, `0xba4d665059c97d6baa42e097707a504aecafbf53`, received 6,590 BUSD and 25,906.285983337104699148 USDT in four payments. The ledger and *Historical file: counterparty_totals.json* preserve every transaction identifier. No business/service assignment was verified for this recipient. The sending wallet had commingled assets; those amounts cannot all be designated GamiFi proceeds.

### 2. FixedFloat — historical custody and order/payout mapping

**Attribution basis:** a provider-attributed administrator reply dated 10 May 2025 on FixedFloat's own FAQ-linked BestChange listing identifies `0x4727250679294802377dd6ca6541b8e459077c95` as a main BSC outgoing address. The reply is later than the transactions and is hosted on a third-party listing. Historical custody in November 2022 remains a question for the service.

**Identifier bundle:**

| UTC | Amount | From | To | Transaction |
|---|---:|---|---|---|
| 2022-11-05 07:15:11 | 5,174 BUSD | `0x35dc4a16db1e30036fee83e733ee065ad8535422` | `0x96f0ae9dc91983d87379cf7bbe2cebc69123aeb6` | `0x34bfa37b43fc0426e45ffcd3af9927be6495d4710f340f7f80e09d2fc41fe1b4` |
| 2022-11-05 07:15:32 | 5,174 BUSD | `0x96f0ae9dc91983d87379cf7bbe2cebc69123aeb6` | `0x4727250679294802377dd6ca6541b8e459077c95` | `0x7702b5e67906c5eb1dea5d1fdde0f7ade3e37cb5cd657944bd539ed460791e48` |

**Questions to resolve:**

1. Did the service control the destination on 5 November 2022, and was the intermediary one of its deposit/order addresses? Which operator holds the historical records?
2. Was the first transaction accepted as an order payment, credited another way, refunded, or unrecognized? Supply any associated order identifier and bookkeeping.
3. For a matched order, identify its output asset, network, amount, payout address and transaction hash, and any refund or cancellation.
4. Identify any account or verification information actually retained and the available preservation process. The service supports no-registration exchanges, so a conventional named account cannot be presumed.

A pooled-wallet outgoing payment must be matched through the service's records, not inferred from a similar amount or nearby time.

The official support page currently publishes the published organizational contact for law enforcement and the published organizational contact for victims. Those labels do not establish the requester qualifies for either route. No request has been sent.

### 3. MEXC — four deposits and the credited account(s)

**Purpose:** confirm historical receiving-wallet custody, deposit-address assignment, whether each transfer was credited, and any linked trade or withdrawal. Do not assume that the common intermediary means a common customer account.

All four transfers below came through intermediary `0x9564f530d9f270a48c510a92c97b59248cefd464`:

| UTC | GMI | Destination | Transaction |
|---|---:|---|---|
| 2022-11-04T15:00:29+00:00 | 5000000 | `0x2e8f79ad740de90dc5f5a9f0d8d9661a60725e64` | `0x7f8323049c6585d0dee94b8ba6b7dcb96d9bd0f2ac11617a00ca2299cb7ae3a8` |
| 2022-11-08T17:48:21+00:00 | 5000000 | `0x2e8f79ad740de90dc5f5a9f0d8d9661a60725e64` | `0xb0b3bf6768b4cb92820c90c4aca9a2103e3b49c753b31bf6258916b3dab5855c` |
| 2022-12-08T02:27:14+00:00 | 5000000 | `0x2e8f79ad740de90dc5f5a9f0d8d9661a60725e64` | `0xff3ac1adab98247b4a1c468612618e00f322c6a7ab66b3b9825150a7f7aa4d8f` |
| 2023-01-21T02:34:05+00:00 | 3000000 | `0x4982085c9e2f89f2ecb8131eca71afad896e89cb` | `0x2e371d5d37cc3deaef36f8c4798f0a18256257304d8eb4db697e6b4414cec02e` |

The `4982…89cb` wallet was disclosed by MEXC in July 2021. The `2e8f…5e64` wallet appears in MEXC's current proof-of-reserves disclosures and current explorer labels; its 2022 custody still needs confirmation.

**Requested records:** the historically assigned deposit account(s), any credits/reversals, associated GMI order and execution records, related withdrawals linked by the exchange's own ledger, and identity/authority records actually held for those accounts. Request retention/preservation confirmation. Public delivery to a hot wallet alone proves neither credit nor sale.

MEXC's current official LEORS workflow is restricted to eligible agency/judicial officials. An authorized requester should supply their genuine capacity, case reference and legally appropriate process. No account access, request, preservation submission or identity claim has been made here.

### 4. Audit and deployment acceptance records

The corroborated GamiFi development repository contains public pull request #13, **fix audit report**, and #25, **Update code for audit**. They provide specific document-discovery targets. Neither title identifies an auditor, verifies a delivered report, or proves coverage of the deployed contracts or later administrative actions.

**Requested records:** any audit engagement letter, auditor identity, delivered report and version, audited source commit, contract-address scope, remediation correspondence, sign-off or deployment acceptance, and any later review of the upgrade/allowance mechanism. Relevant public links:

- https://github.com/sheandev/gamifiContracts/pull/13
- https://github.com/sheandev/gamifiContracts/pull/25
- https://github.com/sheandev/gamifiContracts/blob/main/.openzeppelin/unknown-56.json

The review of PeckShield's current public report catalog did not locate a GamiFi report. That is not proof that no private audit or engagement occurred and is not proof that the repository's audit references concern PeckShield.

### 5. BVI entity verification — free lookup completed

A supplied screenshot shows the official public-search result: **Gamifi Limited, BVI entity 2082070**. A free matching entry at https://i-bvi.com/company/gamifi-limited_978843 adds a displayed registration date of **12.11.2021** (12 November 2021). The date is a commercial-directory report, not an official certificate. Neither free source discloses the registered agent, current status or directors. Use **Gamifi Limited / BVI 2082070** in subsequent authorized corporate-record inquiries. Request dated official company records and the relevant 2022 authority/custody records. Present-day officers and registered agent, if later found, would not alone establish who held a wallet key in 2022.

### 6. Development/agency contracting and handover records

**Prospective record holder:** Avark, the agency whose own GamiFi case study describes branding, website and launchpad application development. Its legal contracting entity has not been established here. The case study does not identify BVI number 2082070, a payer or the investigated signing keys.

**Records to locate:** the engagement agreement and contracting-party identity; invoices and any available payment references; authorized project contacts; and deployment, access and handover documentation relevant to the GamiFi work. Ask whether the contracting client was Gamifi Limited, BVI 2082070, or another identified entity. These are records-location questions; the public agency relationship alone does not assign control or responsibility for the November transactions. No contact has been made.

### Primary and attributed source links

- GamiFi archived terms, prior successful capture: https://web.archive.org/web/20221007163947id_/https://app.gamifi.gg/terms-and-conditions/
- Matching free company entry: https://i-bvi.com/company/gamifi-limited_978843
- Avark GamiFi case study: https://avark.agency/case-studies/gamifi
- BVI registry search information: https://www.bvifsc.vg/searches-bvi-registered-entities
- FixedFloat FAQ endorsing the listing: https://ff.io/ru/faq
- Provider-attributed exact-address reply: https://www.bestchange.ru/fixedfloat-exchanger-79.html (10 May 2025; review-page pagination may change)
- FixedFloat support: https://ff.io/support
- MEXC 2021 wallet disclosure: https://mexcglobal.medium.com/recent-rumors-against-mexc-global-clarified-7205e6828907
- MEXC current wallet disclosure: https://www.mexc.com/nb-NO/proof-of-reserve?page=34
- MEXC current record-access guidance: https://www.mexc.com/support/article/law-enforcement-guidelines-4403594593434

No Cayman bank account, Laura-owned receiving wallet or personal bank receipt has been established. The briefs are evidence-location tools; they do not assign wrongdoing or substitute a company title for a verified signing-key identity.

## Appendix B — BVI entity 2082070: free-source findings

Research date: 6 September 2026. This follow-up uses the supplied registry screenshot and free public sources. The quoted currency was not supplied.

**A free directory entry matches the official-search screenshot by both company name and number, and adds a reported registration date of 12 November 2021.** The date is secondary-source evidence, pending an official company record.

| Field | Finding | Evidence and confidence |
|---|---|---|
| Legal name | Gamifi Limited | Supplied screenshot of BVI public-search result; also matched by i-BVI |
| BVI entity number | 2082070 | Screenshot wraps the number as 20820 / 70; i-BVI separately displays the full number |
| Registration date | 12 November 2021 | i-BVI displays 12.11.2021; directory date format checked against an unambiguous day/month example; not an official certificate |
| Registered agent / status | Not obtained | Neither the supplied screenshot nor free directory entry discloses these fields |
| Directors / shareholders / beneficial owners | Not obtained | No verified free disclosure located in this pass |

Free exact entry: [Gamifi Limited, i-BVI](https://i-bvi.com/company/gamifi-limited_978843). The commercial directory sells reports, but the name, number and displayed date were readable without ordering. Its rotating recommendations are navigation suggestions, not evidence of common ownership or business relationships.

**Connection with the GamiFi project**

The preserved first-party [GamiFi terms](https://web.archive.org/web/20221007163947id_/https://app.gamifi.gg/terms-and-conditions/) identify GamiFi Limited as the BVI contracting company in section 1. Section 2 also attributes creation and release of the GMI token to GamiFi Limited. The capture is dated 7 October 2022 and displays a revision date of 25 January 2022. These are distinct dates; the displayed revision is not itself an archival capture from January.

The terms provide no company number. The registry screenshot therefore supplies a concrete company identifier for the matching legal name and jurisdiction. The directory's reported November 2021 registration date is chronologically compatible with the January 2022 terms. This combination supports the company match; it is not a signed agreement identifying every project wallet or key custodian.

**A commercial document trail outside the paid registry**

[Avark's own GamiFi case study](https://avark.agency/case-studies/gamifi) describes branding, website and launchpad application work, including NFT and staking features. This supplies a documented agency relationship. Its engagement agreement, invoices and deployment handover records are potential sources for the contracting entity and authorized project contacts. That is a records-location inference, not a claim those documents were obtained or that Avark controlled the investigated keys. The public case study does not identify entity 2082070, a payer or the November transaction instructions. Its current page wording does not establish that the relationship remained active on the research date.

**Free-search coverage and remaining gaps**

Two search engines were used for the exact company number/name and combinations with BVI, incorporation and registered-agent terms. Indexed official BVI/FSC/Gazette and Eastern Caribbean court searches did not locate a matching notice. This is a bounded negative search, not proof no notice exists. The [official Gazette help](https://eservices.gov.vg/gazette/content/help-support) explains that native searching requires login and older liquidation/other notices need paid access, so this pass is not a complete historical Gazette search.

Searches also returned different companies and unrelated uses of the same digits in other identifier systems. These were excluded. No date was inferred from neighboring company numbers. The complete first-party litepaper captured on 21 February 2022 has a November 2021 cover date. Its extracted text supplies no entity number or registered agent. That cover date describes the document, not an incorporation certificate; the later May capture was incomplete and supplies no additional conclusion.

The useful corporate record target is now **Gamifi Limited — BVI 2082070**. Official confirmation of its date, registered agent, status and officers remains outstanding. No Cayman bank account, Laura-owned receiving wallet or personal bank receipt has been established. No paid search or outbound request was submitted.

The updated master report and record-request briefs incorporate this company identifier. The on-chain amounts and historical dollar calculations are unaffected by the new corporate reference.

### Supplied registry evidence

Historical screenshot description: Supplied BVI public-search screenshot. The result displays Gamifi Limited and entity number 2082070, wrapped as 20820 and 70. The image supplies no officers, registered agent, status or registration date.

## Appendix C — Complete dated financial register

The following 262 transfer and fee records reproduce the validated ledger across 172 transactions. Record IDs match the workbook. Each linked record points to its full transaction hash in the printed source register. A transaction may produce several rows; different rows are not necessarily separate payments or income. The recorded movement label distinguishes funding, claims, swaps, liquidity, forwarding, conversions and fees. Exact quantities are preserved as text. Dollar marks are rounded to cents only for presentation; small nonzero amounts may display 0.00.

The estimates use each row’s preserved historical price and CAD conversion rate. CAD is C$ and USD is US$. Rows describing actual swap output still show a cryptoasset receipt, not bank cash or profit. Funding and claim marks are marginal values, not proof of money invested. The full workbook and raw JSON retain counterparties, blocks, valuation methods and source-age details. No grand total is calculated.

### 2022-01

| Record | UTC | Recorded movement | Exact quantity | US$ | C$ |
|---|---|---|---:|---:|---:|
| [T001](https://bscscan.com/tx/0xac39350f0f652c95dfb73e0cd8f2028a2c8aa34a51d081374a6c850647625787) | 2022-01-18 15:56:50 | Private funding | 120000000 GMI | 5,769,088.34 | 7,228,090.79 |



### 2022-02

| Record | UTC | Recorded movement | Exact quantity | US$ | C$ |
|---|---|---|---:|---:|---:|
| [T002](https://bscscan.com/tx/0xdb0e3d669432d65c6b3d8870ffcae8be05339c8895b69cb3ab5cbf8fab9495f5) | 2022-02-01 11:27:09 | Private other forwarding GMI | 10000 GMI | 508.75 | 645.81 |



### 2022-03

| Record | UTC | Recorded movement | Exact quantity | US$ | C$ |
|---|---|---|---:|---:|---:|
| [T003](https://bscscan.com/tx/0xac69cf1d77454ccaa2b5e3331d317d89d7a89891da4865203d5551af6f6cbf38) | 2022-03-10 13:15:25 | Private other forwarding GMI | 10000 GMI | 236.82 | 302.56 |
| [T004](https://bscscan.com/tx/0x4a04b6856eae8a2ace67eed1d3fdaa5d14d934dc420cdf2c4eed8658696dac89) | 2022-03-10 13:16:43 | Private other forwarding GMI | 10000 GMI | 236.68 | 302.38 |
| [T005](https://bscscan.com/tx/0x76153356f5ce09e4e6913a335f84444ed3b9d380151ebbdd7214990e14d0df93) | 2022-03-10 13:31:47 | Private other forwarding GMI | 10000 GMI | 235.73 | 301.17 |
| [T006](https://bscscan.com/tx/0xe7858302265b4e9d6ad3b4e1545e35452c0725b5960bfed3ed79cdad48393f94) | 2022-03-10 13:33:32 | Private other forwarding GMI | 10000 GMI | 236.74 | 302.46 |
| [T007](https://bscscan.com/tx/0x4b0b66e2f020479b6381a1b31be240bfb86347cf1813ddb520c094576e6158df) | 2022-03-10 15:25:05 | Project IDs 1, 3, 4 withdrawals | 252.5 BUSD | 252.51 | 322.61 |
| [T008](https://bscscan.com/tx/0x4389510604c93f928c4e1a2f6fda07979d792228de1b6bb66a8242a7a7ee05b5) | 2022-03-11 09:35:55 | Project IDs 1, 3, 4 withdrawals | 110 BUSD | 109.99 | 139.91 |
| [T009](https://bscscan.com/tx/0x2bb55dffcc3ae56b0b81a68b277d2318e27438e3bacbe79cb12d94f0162228bb) | 2022-03-11 10:10:10 | Private earlier other incoming GMI | 10000 GMI | 168.35 | 214.15 |
| [T010](https://bscscan.com/tx/0x43060bbf502f7ae2d1c1db8cbf4e5bcdaef9c1d16356855c26f9c48aaaa0deb3) | 2022-03-11 10:21:43 | Private other forwarding GMI | 10000 GMI | 237.93 | 302.64 |
| [T011](https://bscscan.com/tx/0xbe801f3b0e1fffdc58e884ad6359bf07ee93a0db6d5cc2c7a98a5d782fe2d39b) | 2022-03-11 10:22:10 | Private other forwarding GMI | 10000 GMI | 236.23 | 300.48 |
| [T012](https://bscscan.com/tx/0x9397957fd74ccd8680e56b5c8734c1917efec4c57611bf4a59fa8705b5ce6a62) | 2022-03-11 10:54:34 | Private other forwarding BUSD | 2000 BUSD | 1,999.85 | 2,543.81 |
| [T013](https://bscscan.com/tx/0xa68d28501388dd1939659be1a24f6fbed8c0c22d6df5bbe43196ff408b3ffba4) | 2022-03-18 06:58:39 | Project IDs 6–9 withdrawals | 23722.715761539594859905 BUSD | 23,730.18 | 29,940.37 |
| [T014](https://bscscan.com/tx/0x4e2b2cebb9895bb8ed1ffa817e730273d9271e97e559a2fdd7ba2d4e86fd5299) | 2022-03-18 12:23:52 | Project IDs 6–9 withdrawals | 28421.141280969119319259 BUSD | 28,430.09 | 35,870.24 |
| [T015](https://bscscan.com/tx/0x33f6c2ae7893cf8763b5306d4220780592390cc22ab9399034f4b3ac6ee09683) | 2022-03-23 14:58:07 | Project IDs 1, 3, 4 withdrawals | 2000 BUSD | 2,000.00 | 2,514.20 |



### 2022-04

| Record | UTC | Recorded movement | Exact quantity | US$ | C$ |
|---|---|---|---:|---:|---:|
| [T016](https://bscscan.com/tx/0x00f1ad6f5d7560d5325d08d0afcf253a99b46d588a6509abb37349bacdea965f) | 2022-04-19 13:32:12 | Launchpool upstream funding | 15456876 GMI | 216,583.61 | 273,415.15 |
| [T017](https://bscscan.com/tx/0x020b2a285f0c7f1bc3560d814e2d6a13358d35ee2a96b8b70e36ce2f0b840ccc) | 2022-04-19 15:22:53 | Launchpool opening deposits | 10 GMI | 0.14 | 0.18 |
| [T018](https://bscscan.com/tx/0x19d1cd7e49be9a4226dec5323cc5bc8c36a6e465dceec4fb70fa3f598b019bfd) | 2022-04-19 16:19:46 | Launchpool upstream funding | 5 GMI | 0.07 | 0.09 |
| [T019](https://bscscan.com/tx/0x8a5f1c2ac6bd2a1f8ff17d16c55a64ac384401a27c15a1c1899c6c10d8e237bd) | 2022-04-19 16:30:49 | Launchpool opening deposits | 458882.5934562736916 GMI | 6,361.87 | 8,031.22 |
| [T020](https://bscscan.com/tx/0xec5e3fa4180a89f6732e45f9be8b32dca79a4216d2fae9930bf364f294e2bd1b) | 2022-04-19 16:33:22 | Launchpool opening deposits | 366206.751525064626544 GMI | 5,075.13 | 6,406.84 |
| [T021](https://bscscan.com/tx/0x562dd1aec6bf5e91ff8fe33a907ddb4b2241aa672ee78cc75c46703f0a65fa1b) | 2022-04-19 16:34:43 | Launchpool opening deposits | 399040.53056674101 GMI | 5,529.22 | 6,980.08 |
| [T022](https://bscscan.com/tx/0xe958fb6a25e98a3807872140d8b086a3dbc1585c4fb3944c6f7a32b223cfa6ac) | 2022-04-19 16:36:22 | Launchpool opening deposits | 431061.7431797660877 GMI | 5,966.81 | 7,532.50 |
| [T023](https://bscscan.com/tx/0x5deafdf0447762c763f4ccf7f2ef72fff0eae8324c4af63e383581ce9cca40b4) | 2022-04-19 16:37:49 | Launchpool opening deposits | 337679.1659489148667 GMI | 4,674.67 | 5,901.30 |
| [T024](https://bscscan.com/tx/0x0597d21f73149ed14eaeec5422d3d5c8cda0a4ff71a292d33b79d0fd22a63d6f) | 2022-04-19 16:45:43 | Launchpool opening deposits | 331852.47089813748657 GMI | 4,555.10 | 5,750.36 |
| [T025](https://bscscan.com/tx/0xbf5e4cd1e23a6bef69ab109a42db1c20fd691d2b9a10b994133eb917b655b815) | 2022-04-19 16:47:58 | Launchpool opening deposits | 422884.66330513148782 GMI | 5,800.52 | 7,322.57 |
| [T026](https://bscscan.com/tx/0x5003a6a10ff422d40fa8ebbc1da4e8cc04951ec4b4ab6fe8b848f13efd414153) | 2022-04-19 16:49:04 | Launchpool opening deposits | 440485.85623327138017 GMI | 6,032.35 | 7,615.24 |
| [T027](https://bscscan.com/tx/0x50096f1e9322f81becdefcabd01fb4aefe14828adea24a45479677b1f853c788) | 2022-04-19 16:50:01 | Launchpool opening deposits | 288370.530186758633149 GMI | 3,957.06 | 4,995.40 |
| [T028](https://bscscan.com/tx/0xc730eafea349c136d8481096b4b8dbcd8b941321d946902f539badce1e3bd6d3) | 2022-04-19 16:51:10 | Launchpool opening deposits | 366971.6169596438259 GMI | 5,040.94 | 6,363.68 |
| [T029](https://bscscan.com/tx/0xf75ad88be4981de907e21b4b8b581c33d5a901a2a6a677b6b90c9d83aa83b228) | 2022-04-19 16:52:19 | Launchpool opening deposits | 359343.3683790981212 GMI | 4,951.17 | 6,250.36 |
| [T030](https://bscscan.com/tx/0xbd4fb2f379c2df3eee2c3658a8524df022ad5aadc16beeb93c018ae5676e5392) | 2022-04-19 16:53:37 | Launchpool opening deposits | 467106.443623012504 GMI | 6,433.14 | 8,121.20 |
| [T031](https://bscscan.com/tx/0xbd73d66bb89f452a8a3c1d6140c94dc57ec7017567498075c3530027d4fa9f38) | 2022-04-19 16:54:46 | Launchpool opening deposits | 488810.7314096476405 GMI | 6,741.79 | 8,510.83 |
| [T032](https://bscscan.com/tx/0x1887a310642ec35743719a96f2445eb546ffd401bd4e9e7565c4af8b502a5270) | 2022-04-19 16:55:49 | Launchpool opening deposits | 351362.3394890581639 GMI | 4,847.16 | 6,119.05 |
| [T033](https://bscscan.com/tx/0xa201472810893101c69f1b7ade2481f45e44813a42bfbe7faa2590f1c086b220) | 2022-04-19 16:56:52 | Launchpool opening deposits | 475436.8914711969995 GMI | 6,561.03 | 8,282.64 |
| [T034](https://bscscan.com/tx/0x8e9aa15452d47cbc6ed13157576862a7b74764fdd62e83a91ecfb97b510de9ea) | 2022-04-19 16:58:07 | Launchpool opening deposits | 328253.0673729666334 GMI | 4,532.01 | 5,721.21 |
| [T035](https://bscscan.com/tx/0x726ced6b9b1ea1d8e428ec398939170227b1e541b61e96ab73c1a19bc2363918) | 2022-04-19 16:59:01 | Launchpool opening deposits | 462044.7790815043877 GMI | 6,379.06 | 8,052.93 |
| [T036](https://bscscan.com/tx/0xa2f21fbeb96907cf74bccb95b2bc1ab8afe61d092399fe639295c3493ed0ae1a) | 2022-04-19 17:01:03 | Launchpool opening deposits | 380556.4634824556 GMI | 5,251.12 | 6,629.01 |
| [T037](https://bscscan.com/tx/0xe2240aefad7458e88c5e9b7bee673a2d63f7da6357abd132c8b46c23b6051bf4) | 2022-04-19 17:02:13 | Launchpool opening deposits | 354062.4986037318471 GMI | 4,880.78 | 6,161.49 |
| [T038](https://bscscan.com/tx/0x562536343c53d937828952778e59a84c1c94aa5af64e4d835cc0166833b0fff7) | 2022-04-19 17:03:19 | Launchpool opening deposits | 313382.0204564856549 GMI | 4,320.30 | 5,453.95 |
| [T039](https://bscscan.com/tx/0x5d7b2b12b68c299e0bfeebe67c4f914c38012cbf05e1aed7eeb6fd80482a529a) | 2022-04-19 17:04:28 | Launchpool opening deposits | 423206.14632237570352 GMI | 5,834.89 | 7,365.96 |
| [T040](https://bscscan.com/tx/0xff8ecb91421dafc810f693e04a84070c647e24bc2de708e10a59ec70a252f0e9) | 2022-04-19 17:05:34 | Launchpool opening deposits | 600036.3532744481064 GMI | 8,285.31 | 10,459.37 |
| [T041](https://bscscan.com/tx/0xaa80839f43b1e2c86097a92d54ebb471bf8b21fdf784a727784fd44d9d2ad066) | 2022-04-19 17:06:40 | Launchpool opening deposits | 376066.6970278263361 GMI | 5,202.09 | 6,567.12 |
| [T042](https://bscscan.com/tx/0x860dfc74cfb742e1b566830957ac8a39fd2f37b9a1573471aace3e4e414923dd) | 2022-04-19 17:07:43 | Launchpool opening deposits | 384448.6221635328328 GMI | 5,310.32 | 6,703.74 |
| [T043](https://bscscan.com/tx/0xbe98c1a56f9871f7ae97661c0eeff12d77abbd081c3ab423a6f48c12ee4cdb27) | 2022-04-19 17:08:52 | Launchpool opening deposits | 334065.716964341933 GMI | 4,606.78 | 5,815.60 |
| [T044](https://bscscan.com/tx/0x2312dc5173bf5bc8f152429d4641e542f091e80f1176606d5f4e7940a43171be) | 2022-04-19 17:09:55 | Launchpool opening deposits | 456941.0960645956783 GMI | 6,305.92 | 7,960.60 |
| [T045](https://bscscan.com/tx/0x0c7feeabec050bd7535cc141521781dce9dab619884076353ebb014a67f52e03) | 2022-04-19 17:10:58 | Launchpool opening deposits | 344753.2558957723187 GMI | 4,758.40 | 6,007.00 |
| [T046](https://bscscan.com/tx/0xefa983fcfceee834a72f7a7d715ba2b4d6517e9ec868bf6bb44352366ea9ecda) | 2022-04-19 17:12:34 | Launchpool opening deposits | 366612.8574825958087 GMI | 5,066.94 | 6,396.51 |
| [T047](https://bscscan.com/tx/0xe107685528296c810cd89f7cacf1c334eec0492189a7fc06f55e4c11aa7b9a51) | 2022-04-19 17:13:26 | Launchpool opening deposits | 576981.3866025976568 GMI | 7,974.74 | 10,067.31 |
| [T048](https://bscscan.com/tx/0x854f39b52c34c65f6e2229ade8b2d6d26226fd20323d30703241de9b4c82dd38) | 2022-04-19 17:14:29 | Launchpool opening deposits | 887877.3822482400862 GMI | 12,255.13 | 15,470.87 |
| [T049](https://bscscan.com/tx/0x946453c1f648db21aba304fe83607cd69dd00b22bff1e7bad184412d648dc6c6) | 2022-04-19 17:15:29 | Launchpool opening deposits | 427533.4783261787806 GMI | 5,901.64 | 7,450.22 |
| [T050](https://bscscan.com/tx/0x9821a0b12221f6b1be9f613866defc03a06e69c066ffbeb73ed694633f25e470) | 2022-04-19 17:16:20 | Launchpool opening deposits | 338506.3138068201254 GMI | 4,676.59 | 5,903.73 |
| [T051](https://bscscan.com/tx/0x40d015a2111036e56a123c75f3c1f3c9bb6505198523ccda63e019a3094c9919) | 2022-04-19 17:17:05 | Launchpool opening deposits | 343255.5148194810067 GMI | 4,739.25 | 5,982.82 |
| [T052](https://bscscan.com/tx/0x73c9d8ee6420ca6829a47558aac11498609ff48ae3786cd4dc8c9b975956edf9) | 2022-04-19 17:17:56 | Launchpool opening deposits | 385926.1212208234816 GMI | 5,325.35 | 6,722.73 |
| [T053](https://bscscan.com/tx/0x57b63c0580e9790f77eb641af77311a0e97ef7c3c595bec5838c4336ebbd3681) | 2022-04-19 17:18:41 | Launchpool opening deposits | 313371.426638854702168 GMI | 4,320.77 | 5,454.54 |
| [T054](https://bscscan.com/tx/0x10d7d069e1bc086aecf1433a214b5e70cd1a5b00b7a18dd29b679bc8f54dbbce) | 2022-04-19 17:19:26 | Launchpool opening deposits | 251644.68620389297602 GMI | 3,472.83 | 4,384.10 |
| [T055](https://bscscan.com/tx/0xd2a860e052d77f847e7517eb640815e59ed6d47dc3aba84e431998d6ba2c2969) | 2022-04-19 17:20:11 | Launchpool opening deposits | 622655.997352392143475 GMI | 8,598.14 | 10,854.29 |
| [T056](https://bscscan.com/tx/0x0b44c3c63f6f4ce4ff369632449fd50a7e58162bc7f102dc8a3ed37703138618) | 2022-04-19 17:29:53 | Launchpool opening deposits | 199198.30486490008201 GMI | 2,748.21 | 3,469.35 |



### 2022-05

| Record | UTC | Recorded movement | Exact quantity | US$ | C$ |
|---|---|---|---:|---:|---:|
| [T057](https://bscscan.com/tx/0xfb51cbbf265af6b604ba3499d1608f36ab04a57eb3a71a4d5cbe3c6fe807d780) | 2022-05-23 11:50:16 | Project IDs 6–9 withdrawals | 3775.228767123287671432 BUSD | 3,775.69 | 4,843.83 |



### 2022-06

| Record | UTC | Recorded movement | Exact quantity | US$ | C$ |
|---|---|---|---:|---:|---:|
| [T058](https://bscscan.com/tx/0x757fe0ce1d898fff34b0d4c4f58f2fc7610d3821eacc51c43d7e7e6ac0edcf63) | 2022-06-22 08:29:58 | Project IDs 6–9 withdrawals | 4720.231567727363184247 BUSD | 4,720.69 | 6,109.52 |



### 2022-07

| Record | UTC | Recorded movement | Exact quantity | US$ | C$ |
|---|---|---|---:|---:|---:|
| [T059](https://bscscan.com/tx/0x162b4219c7ae0867465cfd21a13244f888672d19f9296e9c8bdfbf4d3baeacfe) | 2022-07-12 16:05:10 | Private other forwarding GMI | 13150 GMI | 11.56 | 15.05 |



### 2022-09

| Record | UTC | Recorded movement | Exact quantity | US$ | C$ |
|---|---|---|---:|---:|---:|
| [T060](https://bscscan.com/tx/0x684835fae6b574a45be696151087cf039b173ca68c73cea92368401c49208dbf) | 2022-09-23 05:00:12 | Private other forwarding GMI | 161278.104499999999787008 GMI | 65.65 | 89.08 |
| [T061](https://bscscan.com/tx/0xb72e828b1c3fb94394837de4d71b685dfe57e00fbb0f320f24c68f0b95993659) | 2022-09-23 05:01:18 | Private onward transfers BNB | 0.99657042 BNB | 275.83 | 374.29 |



### 2022-10

| Record | UTC | Recorded movement | Exact quantity | US$ | C$ |
|---|---|---|---:|---:|---:|
| [T209](https://bscscan.com/tx/0xc48640d0a9169672220d5ead2b7bd1f8e538b0f079e55720fb55424790572bce) | 2022-10-07 16:24:19 | Onward swap inputs GMI | 161278.104499999999787008 GMI | 51.26 | 70.28 |
| [T210](https://bscscan.com/tx/0xc48640d0a9169672220d5ead2b7bd1f8e538b0f079e55720fb55424790572bce) | 2022-10-07 16:24:19 | Onward swap outputs BNB | 0.180520799210431341 BNB | 50.96 | 69.88 |
| [T211](https://bscscan.com/tx/0xc48640d0a9169672220d5ead2b7bd1f8e538b0f079e55720fb55424790572bce) | 2022-10-07 16:24:19 | Onward network fees BNB | 0.000779105 BNB | 0.22 | 0.30 |
| [T212](https://bscscan.com/tx/0x75cce83e042249dafb69f42a7f4aeeea96ace1773c073e7b5ba31b268606f2ff) | 2022-10-21 09:34:22 | Onward swap inputs GMI | 3749332.57 GMI | 709.19 | 972.51 |
| [T213](https://bscscan.com/tx/0x75cce83e042249dafb69f42a7f4aeeea96ace1773c073e7b5ba31b268606f2ff) | 2022-10-21 09:34:22 | Onward swap outputs BNB | 2.49884041770721016 BNB | 667.22 | 914.95 |
| [T214](https://bscscan.com/tx/0x75cce83e042249dafb69f42a7f4aeeea96ace1773c073e7b5ba31b268606f2ff) | 2022-10-21 09:34:22 | Onward network fees BNB | 0.000779165 BNB | 0.21 | 0.29 |
| [T215](https://bscscan.com/tx/0xc0ad1912342b01317d0a964a4abe670d5c371a160dc9d18d14d264de8d8bf51e) | 2022-10-21 10:45:19 | Onward network fees BNB | 0.00019509 BNB | 0.05 | 0.07 |
| [T216](https://bscscan.com/tx/0xd87f246c4060bc8afa087f398774c9cefc8a0a8d74b8b9aa175b005fe3cad84e) | 2022-10-21 10:45:55 | Onward swap inputs GMI | 905913.02 GMI | 155.00 | 212.56 |
| [T217](https://bscscan.com/tx/0xd87f246c4060bc8afa087f398774c9cefc8a0a8d74b8b9aa175b005fe3cad84e) | 2022-10-21 10:45:55 | Onward swap outputs USDT | 152.258665477104699148 USDT | 152.26 | 208.79 |
| [T218](https://bscscan.com/tx/0xd87f246c4060bc8afa087f398774c9cefc8a0a8d74b8b9aa175b005fe3cad84e) | 2022-10-21 10:45:55 | Onward network fees BNB | 0.000986045 BNB | 0.26 | 0.36 |
| [T219](https://bscscan.com/tx/0xc5a6fd46be61e3fb2805daf822ebd9fa8e3669517ec44f1f000beef817acf0cd) | 2022-10-21 10:56:43 | Onward wallet transfers USDT | 19436.285983337104699148 USDT | 19,436.29 | 26,652.98 |
| [T220](https://bscscan.com/tx/0xc5a6fd46be61e3fb2805daf822ebd9fa8e3669517ec44f1f000beef817acf0cd) | 2022-10-21 10:56:43 | Onward network fees BNB | 0.000180755 BNB | 0.05 | 0.07 |
| [T221](https://bscscan.com/tx/0x925415a01c808aef0c868b7cc91155caae6fd48a6b9b5a88585b07f569b5e707) | 2022-10-21 10:59:31 | Onward swap outputs USDT | 264.6190099022113 USDT | 264.62 | 362.87 |
| [T222](https://bscscan.com/tx/0x925415a01c808aef0c868b7cc91155caae6fd48a6b9b5a88585b07f569b5e707) | 2022-10-21 10:59:31 | Onward swap inputs BNB | 1 BNB | 266.90 | 366.00 |
| [T223](https://bscscan.com/tx/0x925415a01c808aef0c868b7cc91155caae6fd48a6b9b5a88585b07f569b5e707) | 2022-10-21 10:59:31 | Onward network fees BNB | 0.00104583 BNB | 0.28 | 0.38 |
| [T224](https://bscscan.com/tx/0xc0049ad7c17a1de264056335791f2f6527256e2ecd4c2cca594d4bed475f8ade) | 2022-10-21 11:00:21 | Onward wallet transfers USDT | 60 USDT | 60.00 | 82.28 |
| [T225](https://bscscan.com/tx/0xc0049ad7c17a1de264056335791f2f6527256e2ecd4c2cca594d4bed475f8ade) | 2022-10-21 11:00:21 | Onward network fees BNB | 0.000255575 BNB | 0.07 | 0.09 |



### 2022-11

| Record | UTC | Recorded movement | Exact quantity | US$ | C$ |
|---|---|---|---:|---:|---:|
| [T226](https://bscscan.com/tx/0x1d511630993eefca8a67f6a63e189a6e25054f340e0d8867a00c6b5fb67cfbf3) | 2022-11-04 14:25:04 | Onward returns to private wallet BNB | 1 BNB | 356.08 | 481.31 |
| [T227](https://bscscan.com/tx/0x1d511630993eefca8a67f6a63e189a6e25054f340e0d8867a00c6b5fb67cfbf3) | 2022-11-04 14:25:04 | Onward network fees BNB | 0.000105 BNB | 0.04 | 0.05 |
| [T062](https://bscscan.com/tx/0x6f2c3e43f94de965feaf666ad8a35a6951c72a9367360d9dc138d236902e787f) | 2022-11-04 14:25:40 | Private vesting claims | 96645563.271604938271604938 GMI | 21,061.17 | 28,468.38 |
| [T063](https://bscscan.com/tx/0x77aa71b436f968ef2c7845806036702b6b72947c57134bac12155b7adab445c0) | 2022-11-04 14:36:59 | Private sale inputs | 4000000 GMI | 872.69 | 1,179.62 |
| [T064](https://bscscan.com/tx/0x77aa71b436f968ef2c7845806036702b6b72947c57134bac12155b7adab445c0) | 2022-11-04 14:36:59 | Private sale proceeds WBNB | 2.296091425541797281 WBNB | 820.80 | 1,109.48 |
| [T065](https://bscscan.com/tx/0x203abb1c9c7dae34461bf67e753898d0671bbf25e13d80051745dd19344a32a5) | 2022-11-04 14:49:05 | Private sale inputs | 5000000 GMI | 994.83 | 1,344.72 |
| [T066](https://bscscan.com/tx/0x203abb1c9c7dae34461bf67e753898d0671bbf25e13d80051745dd19344a32a5) | 2022-11-04 14:49:05 | Private sale proceeds BUSD | 922.244231334011558017 BUSD | 922.24 | 1,246.60 |
| [T067](https://bscscan.com/tx/0xb92ef6cc144fc776ecc32cce28108f8903be0b1c17c669a788697a89f0e77d38) | 2022-11-04 14:50:32 | Private unwrap input WBNB | 2.296091425541797281 WBNB | 819.88 | 1,108.23 |
| [T068](https://bscscan.com/tx/0xb92ef6cc144fc776ecc32cce28108f8903be0b1c17c669a788697a89f0e77d38) | 2022-11-04 14:50:32 | Private unwrap output BNB | 2.296091425541797281 BNB | 819.88 | 1,108.23 |
| [T069](https://bscscan.com/tx/0x8a23f55933f775a0d1636fa9c8a791048fafc78838d8e708749938dea98b50f6) | 2022-11-04 14:52:40 | Private sale inputs | 2500000 GMI | 456.62 | 617.22 |
| [T070](https://bscscan.com/tx/0x8a23f55933f775a0d1636fa9c8a791048fafc78838d8e708749938dea98b50f6) | 2022-11-04 14:52:40 | Private sale proceeds BUSD | 437.046205300729306686 BUSD | 437.05 | 590.76 |
| [T071](https://bscscan.com/tx/0x0758105d02766f3730218abbc695e7eb890cd128b3798cf795c49a1069be0e0b) | 2022-11-04 14:54:38 | Private sale inputs | 2000000 GMI | 356.03 | 481.25 |
| [T072](https://bscscan.com/tx/0x0758105d02766f3730218abbc695e7eb890cd128b3798cf795c49a1069be0e0b) | 2022-11-04 14:54:38 | Private sale proceeds BUSD | 344.591362752858876366 BUSD | 344.59 | 465.78 |
| [T073](https://bscscan.com/tx/0x39ec8dffbd77f61914a2d5b30810ba69805d7fc9aec2af7fa64e1083e43fbe5c) | 2022-11-04 14:59:14 | Private exchange intermediary | 5000000 GMI | 877.18 | 1,185.68 |
| [T074](https://bscscan.com/tx/0x7f8323049c6585d0dee94b8ba6b7dcb96d9bd0f2ac11617a00ca2299cb7ae3a8) | 2022-11-04 15:00:29 | Private MEXC 2e8 receipt | 5000000 GMI | 877.32 | 1,185.87 |
| [T075](https://bscscan.com/tx/0xce306e566653d227a138975f721436d91d457d81ebc32d9cd4386e2fb7455f48) | 2022-11-05 06:45:09 | Launchpool November outflow | 14000000 GMI | 2,675.88 | 3,616.99 |
| [T076](https://bscscan.com/tx/0xce306e566653d227a138975f721436d91d457d81ebc32d9cd4386e2fb7455f48) | 2022-11-05 06:45:09 | Other November outflows | 23000000 GMI | 4,396.09 | 5,942.19 |
| [T077](https://bscscan.com/tx/0xce306e566653d227a138975f721436d91d457d81ebc32d9cd4386e2fb7455f48) | 2022-11-05 06:45:09 | Other November outflows | 7000000 GMI | 1,337.94 | 1,808.49 |
| [T078](https://bscscan.com/tx/0xb954f172ba0faed75a15967fce0e72a52ee674fd585d9d1e5385199c72f82a17) | 2022-11-05 06:45:39 | November gas links | 0.019849782233850894 BNB | 7.14 | 9.65 |
| [T079](https://bscscan.com/tx/0x7096720b8dc95afac5ad1029a489ce8dd2b2dcb5ff78e960fcb5e10d03acd8aa) | 2022-11-05 06:51:21 | November sale input | 44000000 GMI | 8,410.14 | 11,367.99 |
| [T080](https://bscscan.com/tx/0x7096720b8dc95afac5ad1029a489ce8dd2b2dcb5ff78e960fcb5e10d03acd8aa) | 2022-11-05 06:51:21 | November sale proceeds | 5174.293394005109506048 BUSD | 5,174.14 | 6,993.89 |
| [T081](https://bscscan.com/tx/0x34bfa37b43fc0426e45ffcd3af9927be6495d4710f340f7f80e09d2fc41fe1b4) | 2022-11-05 07:15:11 | November stablecoin forward | 5174 BUSD | 5,173.90 | 6,993.56 |
| [T082](https://bscscan.com/tx/0xfce9f602e9b578c45f056eaa29343e0932d46f796d3fcb9a9b2dc326e1367a7a) | 2022-11-05 07:15:20 | November gas links | 0.00084 BNB | 0.30 | 0.41 |
| [T083](https://bscscan.com/tx/0x7702b5e67906c5eb1dea5d1fdde0f7ade3e37cb5cd657944bd539ed460791e48) | 2022-11-05 07:15:32 | November service sweep | 5174 BUSD | 5,173.90 | 6,993.56 |
| [T084](https://bscscan.com/tx/0xfc4c26165b9fad6ae7aa5c69b0763f4bed1af11f97ecebb9112793ca121303c4) | 2022-11-05 07:15:41 | November gas links | 0.000502984 BNB | 0.18 | 0.24 |
| [T085](https://bscscan.com/tx/0x28335e5207a836dd8525191ff58c0b72331cff4d7e86f74c10eafd51dd4abc53) | 2022-11-06 12:45:06 | Private onward transfers BNB | 2 BNB | 702.72 | 949.87 |
| [T086](https://bscscan.com/tx/0x39658c447c0db971adf6459ea117ee8f656a3896d6a05de599b7bc8f0836de2a) | 2022-11-06 12:46:39 | Private BUSD forwarded to F4F | 1703.881799387599741069 BUSD | 1,704.14 | 2,303.48 |
| [T228](https://bscscan.com/tx/0x863e6939cdd3ba2bea57965a24a8a378960c4234406aa1dc63f1e1a3a5b896eb) | 2022-11-06 13:03:57 | Onward network fees BNB | 0.00022203 BNB | 0.08 | 0.11 |
| [T229](https://bscscan.com/tx/0x2330c9eb0faac11ab9e7fae7d82ec57606bfc71235c92f3d8c6d83e2c278d4bb) | 2022-11-06 13:03:57 | Onward swap inputs USDT | 204.6190099022113 USDT | 204.62 | 276.58 |
| [T230](https://bscscan.com/tx/0x2330c9eb0faac11ab9e7fae7d82ec57606bfc71235c92f3d8c6d83e2c278d4bb) | 2022-11-06 13:03:57 | Onward swap outputs BUSD | 203.007300309815295969 BUSD | 203.01 | 274.40 |
| [T231](https://bscscan.com/tx/0x2330c9eb0faac11ab9e7fae7d82ec57606bfc71235c92f3d8c6d83e2c278d4bb) | 2022-11-06 13:03:57 | Onward network fees BNB | 0.000976515 BNB | 0.34 | 0.46 |
| [T232](https://bscscan.com/tx/0x7c279e673b98372f0f6678500f17906b90d70cb7499b7822faba127eae7955df) | 2022-11-06 13:24:00 | Onward returns to private wallet BNB | 3 BNB | 1,056.33 | 1,427.84 |
| [T233](https://bscscan.com/tx/0x7c279e673b98372f0f6678500f17906b90d70cb7499b7822faba127eae7955df) | 2022-11-06 13:24:00 | Onward network fees BNB | 0.000105 BNB | 0.04 | 0.05 |
| [T087](https://bscscan.com/tx/0x1b6fb13de5737263b76277e7a24d22fd0b9a50fac9fc6931adb1c788ff1ffff9) | 2022-11-06 13:25:15 | Private liquidity add refund BNB | 1E-18 BNB | 0.00 | 0.00 |
| [T088](https://bscscan.com/tx/0x1b6fb13de5737263b76277e7a24d22fd0b9a50fac9fc6931adb1c788ff1ffff9) | 2022-11-06 13:25:15 | Private liquidity deposits BNB | 4.279827980541797281 BNB | 1,506.01 | 2,035.67 |
| [T089](https://bscscan.com/tx/0x1b6fb13de5737263b76277e7a24d22fd0b9a50fac9fc6931adb1c788ff1ffff9) | 2022-11-06 13:25:15 | Private liquidity deposits GMI | 10139294.126745140146790894 GMI | 1,506.01 | 2,035.67 |
| [T090](https://bscscan.com/tx/0x1b6fb13de5737263b76277e7a24d22fd0b9a50fac9fc6931adb1c788ff1ffff9) | 2022-11-06 13:25:15 | Private LP token receipts | 3332.459542883160311442 GMI-WBNB LP | 3,012.02 | 4,071.35 |
| [T234](https://bscscan.com/tx/0x2545cd928d92ca3a529f60d5e49479df9cc513ddce418aa39a9a0f81c0577c32) | 2022-11-06 13:29:30 | Onward returns to private wallet BNB | 5 BNB | 1,758.92 | 2,377.54 |
| [T235](https://bscscan.com/tx/0x2545cd928d92ca3a529f60d5e49479df9cc513ddce418aa39a9a0f81c0577c32) | 2022-11-06 13:29:30 | Onward network fees BNB | 0.000105 BNB | 0.04 | 0.05 |
| [T091](https://bscscan.com/tx/0x1448d738413857636ad78ff20f2eaa56c16fbf4800365b8e41f66e3bbe645a12) | 2022-11-06 13:30:48 | Private liquidity add refund BNB | 1E-18 BNB | 0.00 | 0.00 |
| [T092](https://bscscan.com/tx/0x1448d738413857636ad78ff20f2eaa56c16fbf4800365b8e41f66e3bbe645a12) | 2022-11-06 13:30:48 | Private liquidity deposits BNB | 4.5 BNB | 1,582.99 | 2,139.72 |
| [T093](https://bscscan.com/tx/0x1448d738413857636ad78ff20f2eaa56c16fbf4800365b8e41f66e3bbe645a12) | 2022-11-06 13:30:48 | Private liquidity deposits GMI | 10660901.274022018833217282 GMI | 1,582.99 | 2,139.72 |
| [T094](https://bscscan.com/tx/0x1448d738413857636ad78ff20f2eaa56c16fbf4800365b8e41f66e3bbe645a12) | 2022-11-06 13:30:48 | Private LP token receipts | 3503.895018947892528962 GMI-WBNB LP | 3,165.97 | 4,279.44 |
| [T236](https://bscscan.com/tx/0x1cf09021110c397c5262eb25a56c5d4a5478d738d3300038608dcb07adaa4f36) | 2022-11-07 07:41:45 | Onward returns to private wallet BNB | 3 BNB | 1,001.89 | 1,351.85 |
| [T237](https://bscscan.com/tx/0x1cf09021110c397c5262eb25a56c5d4a5478d738d3300038608dcb07adaa4f36) | 2022-11-07 07:41:45 | Onward network fees BNB | 0.000105 BNB | 0.04 | 0.05 |
| [T095](https://bscscan.com/tx/0x7c7a2fe044b574e5f8fd8e4eb585eeb094aa04ae2956d766c1463a2972962c93) | 2022-11-07 07:43:21 | Private liquidity add refund BNB | 1E-18 BNB | 0.00 | 0.00 |
| [T096](https://bscscan.com/tx/0x7c7a2fe044b574e5f8fd8e4eb585eeb094aa04ae2956d766c1463a2972962c93) | 2022-11-07 07:43:21 | Private liquidity deposits BNB | 3 BNB | 998.49 | 1,347.26 |
| [T097](https://bscscan.com/tx/0x7c7a2fe044b574e5f8fd8e4eb585eeb094aa04ae2956d766c1463a2972962c93) | 2022-11-07 07:43:21 | Private liquidity deposits GMI | 7141984.538727124246904764 GMI | 998.49 | 1,347.26 |
| [T098](https://bscscan.com/tx/0x7c7a2fe044b574e5f8fd8e4eb585eeb094aa04ae2956d766c1463a2972962c93) | 2022-11-07 07:43:21 | Private LP token receipts | 2341.536789416864249776 GMI-WBNB LP | 1,997.02 | 2,694.57 |
| [T238](https://bscscan.com/tx/0xdcd15c3761db237bf135a6733531ccbf8293f7c96197ea782c1cecb3d1822f72) | 2022-11-07 13:07:05 | Onward wallet transfers BNB | 0.5 BNB | 166.41 | 224.54 |
| [T239](https://bscscan.com/tx/0xdcd15c3761db237bf135a6733531ccbf8293f7c96197ea782c1cecb3d1822f72) | 2022-11-07 13:07:05 | Onward network fees BNB | 0.000105 BNB | 0.03 | 0.05 |
| [T240](https://bscscan.com/tx/0x2640f592d8b45f512e121a014b7de6b7293aaf8b06785bd388e66d9c13195520) | 2022-11-07 14:00:56 | Onward wallet transfers BNB | 0.5 BNB | 164.35 | 221.75 |
| [T241](https://bscscan.com/tx/0x2640f592d8b45f512e121a014b7de6b7293aaf8b06785bd388e66d9c13195520) | 2022-11-07 14:00:56 | Onward network fees BNB | 0.000105 BNB | 0.03 | 0.05 |
| [T099](https://bscscan.com/tx/0x90914bb510876debff2d9828706728765298905864d4450899c2372070283e89) | 2022-11-08 16:39:58 | Private liquidity returns BNB | 8.541343261253548134 BNB | 3,297.90 | 4,432.70 |
| [T100](https://bscscan.com/tx/0x90914bb510876debff2d9828706728765298905864d4450899c2372070283e89) | 2022-11-08 16:39:58 | Private LP tokens redeemed | 6883.418513435937817635 GMI-WBNB LP | 6,595.86 | 8,865.50 |
| [T101](https://bscscan.com/tx/0x90914bb510876debff2d9828706728765298905864d4450899c2372070283e89) | 2022-11-08 16:39:58 | Private liquidity returns GMI | 21680338.642683044091222143 GMI | 3,297.90 | 4,432.70 |
| [T102](https://bscscan.com/tx/0x88f61323abec9c4f7826fd90dad8d689f9461453c9906b0505923fcccd9affab) | 2022-11-08 16:40:47 | Private onward transfers BNB | 8 BNB | 3,088.88 | 4,151.76 |
| [T103](https://bscscan.com/tx/0xbb5706368c31e17c4fc0ec8b2faa93d57b707f6409c8ff217745856cc12a0f15) | 2022-11-08 16:42:56 | Private sale proceeds BNB | 0.387178971398081498 BNB | 150.47 | 202.25 |
| [T104](https://bscscan.com/tx/0xbb5706368c31e17c4fc0ec8b2faa93d57b707f6409c8ff217745856cc12a0f15) | 2022-11-08 16:42:56 | Private sale inputs | 1000000 GMI | 153.11 | 205.80 |
| [T105](https://bscscan.com/tx/0x4209ed260e5cb23946f75508fd2268bae46592f6224be8a310e44a4f58332fff) | 2022-11-08 16:44:00 | Private sale proceeds BNB | 0.378741246023242597 BNB | 147.88 | 198.76 |
| [T106](https://bscscan.com/tx/0x4209ed260e5cb23946f75508fd2268bae46592f6224be8a310e44a4f58332fff) | 2022-11-08 16:44:00 | Private sale inputs | 1000000 GMI | 149.88 | 201.45 |
| [T107](https://bscscan.com/tx/0x0220a34ba2222424e1a629ad6d9556f49de785400cace7942d4e35f7035f896a) | 2022-11-08 16:44:39 | Private sale proceeds BNB | 0.370576480579112181 BNB | 144.69 | 194.48 |
| [T108](https://bscscan.com/tx/0x0220a34ba2222424e1a629ad6d9556f49de785400cace7942d4e35f7035f896a) | 2022-11-08 16:44:39 | Private sale inputs | 1000000 GMI | 146.63 | 197.09 |
| [T109](https://bscscan.com/tx/0x3621e3c7b22846d2aea07991b80dcf5319160c46fb956c7cbbee56ec397b606f) | 2022-11-08 16:45:24 | Private sale proceeds BNB | 0.36267302469444156 BNB | 141.60 | 190.33 |
| [T110](https://bscscan.com/tx/0x3621e3c7b22846d2aea07991b80dcf5319160c46fb956c7cbbee56ec397b606f) | 2022-11-08 16:45:24 | Private sale inputs | 1000000 GMI | 143.49 | 192.86 |
| [T111](https://bscscan.com/tx/0x1f53047d22a56829dd1dd1f28ece71a5b7cae2c51492638e717eb7e2bfafd2c8) | 2022-11-08 16:46:18 | Private sale proceeds BNB | 0.355019843079312016 BNB | 137.66 | 185.04 |
| [T112](https://bscscan.com/tx/0x1f53047d22a56829dd1dd1f28ece71a5b7cae2c51492638e717eb7e2bfafd2c8) | 2022-11-08 16:46:18 | Private sale inputs | 1000000 GMI | 139.48 | 187.47 |
| [T113](https://bscscan.com/tx/0xdf15793fb1dfa7b3fce6ea540247630b85a3cadc5b24b420fdd94fc1c8b6a503) | 2022-11-08 16:47:04 | Private sale proceeds BNB | 0.174714172829105952 BNB | 67.64 | 90.91 |
| [T114](https://bscscan.com/tx/0xdf15793fb1dfa7b3fce6ea540247630b85a3cadc5b24b420fdd94fc1c8b6a503) | 2022-11-08 16:47:04 | Private sale inputs | 500000 GMI | 68.17 | 91.62 |
| [T115](https://bscscan.com/tx/0x614a22269124783eccee13db957b20c3f73312d8e4f22f73219c8f4595f17152) | 2022-11-08 16:47:46 | Private sale proceeds BNB | 0.234148918907064907 BNB | 90.65 | 121.84 |
| [T116](https://bscscan.com/tx/0x614a22269124783eccee13db957b20c3f73312d8e4f22f73219c8f4595f17152) | 2022-11-08 16:47:46 | Private sale inputs | 700000 GMI | 91.53 | 123.03 |
| [T117](https://bscscan.com/tx/0x586d19812d910a6a820c55aed37068ea4d1242eaf92ad6a30a5126ef92e4347b) | 2022-11-08 16:48:34 | Private sale proceeds BNB | 2.455484842171770585 BNB | 945.00 | 1,270.18 |
| [T118](https://bscscan.com/tx/0x586d19812d910a6a820c55aed37068ea4d1242eaf92ad6a30a5126ef92e4347b) | 2022-11-08 16:48:34 | Private sale inputs | 8000000 GMI | 1,025.02 | 1,377.73 |
| [T119](https://bscscan.com/tx/0x1d5dcc48c015a4a9c1cfffdd19f562c28b13d2ea862964db98bf9329223b6e2a) | 2022-11-08 16:49:34 | Private onward transfers BNB | 5 BNB | 1,924.27 | 2,586.41 |
| [T242](https://bscscan.com/tx/0x02fdf877c4901524ace8f5967a5422058d6b00d7fa6d56435de8ffbd5f6cdd1e) | 2022-11-08 17:18:38 | Onward swap outputs USDT | 4832.548709830717364662 USDT | 4,832.89 | 6,495.89 |
| [T243](https://bscscan.com/tx/0x02fdf877c4901524ace8f5967a5422058d6b00d7fa6d56435de8ffbd5f6cdd1e) | 2022-11-08 17:18:38 | Onward swap inputs BNB | 13 BNB | 4,884.04 | 6,564.64 |
| [T244](https://bscscan.com/tx/0x02fdf877c4901524ace8f5967a5422058d6b00d7fa6d56435de8ffbd5f6cdd1e) | 2022-11-08 17:18:38 | Onward network fees BNB | 0.002130935 BNB | 0.80 | 1.08 |
| [T120](https://bscscan.com/tx/0x17b757eede0f625d11d0306746682a4a32a1eaa00e1de64e8250c08b7e07f8f2) | 2022-11-08 17:45:18 | Private exchange intermediary | 5000000 GMI | 577.15 | 775.75 |
| [T121](https://bscscan.com/tx/0xb0b3bf6768b4cb92820c90c4aca9a2103e3b49c753b31bf6258916b3dab5855c) | 2022-11-08 17:48:21 | Private MEXC 2e8 receipt | 5000000 GMI | 576.08 | 774.31 |
| [T122](https://bscscan.com/tx/0xf12713c4fc0ab16c4ebeb52a5b195f62ba828ed1f484c1c2dc4b610192fdb5d3) | 2022-11-11 05:09:12 | Private sale inputs | 500000 GMI | 49.38 | 66.06 |
| [T123](https://bscscan.com/tx/0xf12713c4fc0ab16c4ebeb52a5b195f62ba828ed1f484c1c2dc4b610192fdb5d3) | 2022-11-11 05:09:12 | Private sale proceeds BUSD | 48.735073973554895612 BUSD | 48.79 | 65.28 |
| [T124](https://bscscan.com/tx/0x8787922cbe10a5e97d96e00db948bc4d98990fc90e4d15f7ba942fbd42b376b6) | 2022-11-11 05:09:39 | Private sale inputs | 550000 GMI | 53.72 | 71.87 |
| [T125](https://bscscan.com/tx/0x8787922cbe10a5e97d96e00db948bc4d98990fc90e4d15f7ba942fbd42b376b6) | 2022-11-11 05:09:39 | Private sale proceeds BUSD | 53.033274887508283565 BUSD | 53.10 | 71.03 |
| [T126](https://bscscan.com/tx/0x4c628980278e22d7747cbf7a573ae0bded7a90afc8f9594aab800c3babfd37a5) | 2022-11-11 05:31:52 | Private liquidity returns BNB | 2.607943974720827936 BNB | 768.37 | 1,027.93 |
| [T127](https://bscscan.com/tx/0x4c628980278e22d7747cbf7a573ae0bded7a90afc8f9594aab800c3babfd37a5) | 2022-11-11 05:31:52 | Private LP tokens redeemed | 2294.472837811979272545 GMI-WBNB LP | 1,536.81 | 2,055.94 |
| [T128](https://bscscan.com/tx/0x4c628980278e22d7747cbf7a573ae0bded7a90afc8f9594aab800c3babfd37a5) | 2022-11-11 05:31:52 | Private liquidity returns GMI | 7894389.253220628318984269 GMI | 768.37 | 1,027.93 |
| [T129](https://bscscan.com/tx/0x9f459055deac9f568871f6cd92077f03673958ab46184ef4dd8bacf911b92164) | 2022-11-11 05:33:28 | Private sale inputs | 1400000 GMI | 136.46 | 182.55 |
| [T130](https://bscscan.com/tx/0x9f459055deac9f568871f6cd92077f03673958ab46184ef4dd8bacf911b92164) | 2022-11-11 05:33:28 | Private sale proceeds BUSD | 133.365544435419768283 BUSD | 133.57 | 178.69 |
| [T131](https://bscscan.com/tx/0x0361272c59d8be9106aa8b64385d5366cd8579da22d3764281c01ed214e3b6f5) | 2022-11-11 05:37:47 | Private sale inputs | 100000 GMI | 9.47 | 12.67 |
| [T132](https://bscscan.com/tx/0x0361272c59d8be9106aa8b64385d5366cd8579da22d3764281c01ed214e3b6f5) | 2022-11-11 05:37:47 | Private sale proceeds BUSD | 9.38247695344865642 BUSD | 9.40 | 12.57 |
| [T133](https://bscscan.com/tx/0x3eb4a557e3cc88acc7e64dd9f66a4df9a383c106f999f5dbe19975432bcf8494) | 2022-11-19 09:48:03 | Private BUSD forwarded to F4F | 244.51637024993160388 BUSD | 244.53 | 327.31 |
| [T134](https://bscscan.com/tx/0x40871b477df601e7681470deaca31d58be0a4e2b1656f9f385c2268555074d9f) | 2022-11-19 09:51:51 | Private sale proceeds BNB | 4.285289686843634647 BNB | 1,159.42 | 1,551.88 |
| [T135](https://bscscan.com/tx/0x40871b477df601e7681470deaca31d58be0a4e2b1656f9f385c2268555074d9f) | 2022-11-19 09:51:51 | Private sale inputs | 14507027.807003581863724602 GMI | 1,354.37 | 1,812.83 |
| [T136](https://bscscan.com/tx/0xf9982e1d1a5043c22b7fbc3e7c0c005f40f18aa382c4004a21c0f35e3598af46) | 2022-11-19 09:53:15 | Private sale proceeds BNB | 0.390147523191066866 BNB | 105.54 | 141.27 |
| [T137](https://bscscan.com/tx/0xf9982e1d1a5043c22b7fbc3e7c0c005f40f18aa382c4004a21c0f35e3598af46) | 2022-11-19 09:53:15 | Private sale inputs | 1400000 GMI | 107.34 | 143.67 |
| [T138](https://bscscan.com/tx/0x5c12f503cfa66df55253faafb3d0c81972ca744ecfac296103b857a1607c256b) | 2022-11-19 09:54:06 | Private sale proceeds BNB | 0.691741985944504144 BNB | 187.07 | 250.40 |
| [T139](https://bscscan.com/tx/0x5c12f503cfa66df55253faafb3d0c81972ca744ecfac296103b857a1607c256b) | 2022-11-19 09:54:06 | Private sale inputs | 2500000 GMI | 192.39 | 257.51 |
| [T140](https://bscscan.com/tx/0x617019de109e31af87c9b84bf0f6c922693eee86f7db2598e252f49dd4cd8270) | 2022-11-19 09:58:45 | Private sale proceeds BNB | 0.388267052123310526 BNB | 105.03 | 140.58 |
| [T141](https://bscscan.com/tx/0x617019de109e31af87c9b84bf0f6c922693eee86f7db2598e252f49dd4cd8270) | 2022-11-19 09:58:45 | Private sale inputs | 1400000 GMI | 106.81 | 142.97 |
| [T142](https://bscscan.com/tx/0xf3fd8ec2971cfb10f8ddd36e5a1129d8a3770dfdcbf77efeeab9cf9ac7974b6b) | 2022-11-21 07:44:29 | Private sale proceeds BNB | 0.582129543392115814 BNB | 150.45 | 202.39 |
| [T143](https://bscscan.com/tx/0xf3fd8ec2971cfb10f8ddd36e5a1129d8a3770dfdcbf77efeeab9cf9ac7974b6b) | 2022-11-21 07:44:29 | Private sale inputs | 2000000 GMI | 154.02 | 207.19 |
| [T144](https://bscscan.com/tx/0xd26e3e5d5e5e3c8375e72b16196857d66e9b84c74bb5ebfeeca7ea3356926d7b) | 2022-11-21 07:44:59 | Private sale proceeds BNB | 1.094736394511955932 BNB | 282.93 | 380.60 |
| [T145](https://bscscan.com/tx/0xd26e3e5d5e5e3c8375e72b16196857d66e9b84c74bb5ebfeeca7ea3356926d7b) | 2022-11-21 07:44:59 | Private sale inputs | 4000000 GMI | 295.39 | 397.36 |
| [T146](https://bscscan.com/tx/0xc21c3c3ee62057ebe5f0bebbac78f48d7c16d24c81620f1461525c2005f95a19) | 2022-11-21 07:48:41 | Private sale inputs | 4000000 GMI | 275.63 | 370.78 |
| [T147](https://bscscan.com/tx/0xc21c3c3ee62057ebe5f0bebbac78f48d7c16d24c81620f1461525c2005f95a19) | 2022-11-21 07:48:41 | Private sale proceeds BUSD | 263.867721787667042029 BUSD | 263.99 | 355.12 |
| [T148](https://bscscan.com/tx/0xbb03bd0e65bb67fead14f138687283a1c167133570962c92f9614b0eef21df9b) | 2022-11-24 00:36:33 | Private BUSD forwarded to F4F | 263.867721787667042029 BUSD | 263.89 | 351.98 |
| [T149](https://bscscan.com/tx/0x5859779a769835115a1a080ad0c95721a81bcbc42365c98f584a57422caca8c1) | 2022-11-24 00:38:21 | Private sale inputs | 4000000 GMI | 336.87 | 449.32 |
| [T150](https://bscscan.com/tx/0x5859779a769835115a1a080ad0c95721a81bcbc42365c98f584a57422caca8c1) | 2022-11-24 00:38:21 | Private sale proceeds BUSD | 320.59479636055620389 BUSD | 320.63 | 427.65 |
| [T151](https://bscscan.com/tx/0x2c0841746c441de727842824780b6e09247f6fd6b49945cbe6a4e134615c5664) | 2022-11-24 00:39:00 | Private sale inputs | 950000 GMI | 73.37 | 97.86 |
| [T152](https://bscscan.com/tx/0x2c0841746c441de727842824780b6e09247f6fd6b49945cbe6a4e134615c5664) | 2022-11-24 00:39:00 | Private sale proceeds BUSD | 72.433061733286341383 BUSD | 72.44 | 96.62 |
| [T153](https://bscscan.com/tx/0x81a87dc87a1b3d6fc76b6c21d3b7290b0daa0a15a714015401631bee2ee8fbe4) | 2022-11-24 00:40:24 | Private sale inputs | 800000 GMI | 60.58 | 80.80 |
| [T154](https://bscscan.com/tx/0x81a87dc87a1b3d6fc76b6c21d3b7290b0daa0a15a714015401631bee2ee8fbe4) | 2022-11-24 00:40:24 | Private sale proceeds BUSD | 59.925453072850792848 BUSD | 59.93 | 79.94 |
| [T155](https://bscscan.com/tx/0x677dc2036fbb3fc31181eaefd5a9329e7dee8af63cc26ba341f03316b99a60e2) | 2022-11-24 00:41:06 | Private sale inputs | 650000 GMI | 48.46 | 64.64 |
| [T156](https://bscscan.com/tx/0x677dc2036fbb3fc31181eaefd5a9329e7dee8af63cc26ba341f03316b99a60e2) | 2022-11-24 00:41:06 | Private sale proceeds BUSD | 48.006999573725546959 BUSD | 48.01 | 64.04 |
| [T157](https://bscscan.com/tx/0x48f746263d74036dc34eba31e3bb83c45a64b4793fabe1e0188977b79c674074) | 2022-11-24 00:45:06 | Private BUSD forwarded to F4F | 500.96031074041888508 BUSD | 501.01 | 668.25 |
| [T158](https://bscscan.com/tx/0x7d8d9e6e8a7d9111c2f6bab0463afca7297e04aedc80a9f7ce31a2eef2d18cf7) | 2022-11-24 12:29:54 | Private sale inputs | 5000000 GMI | 397.98 | 530.83 |
| [T159](https://bscscan.com/tx/0x7d8d9e6e8a7d9111c2f6bab0463afca7297e04aedc80a9f7ce31a2eef2d18cf7) | 2022-11-24 12:29:54 | Private sale proceeds BUSD | 376.431633899894859871 BUSD | 376.48 | 502.15 |
| [T160](https://bscscan.com/tx/0x19b579dfe3278ba3ae20519200db7d1d910aa34191796ca59bc8c3cd07205066) | 2022-11-24 12:30:30 | Private BUSD forwarded to F4F | 376.431633899894859871 BUSD | 376.48 | 502.15 |
| [T161](https://bscscan.com/tx/0xb735822a5692dbbc3b9384993ba43cecd70ccc0e41b4755115ab12cfd0c35c61) | 2022-11-24 13:37:22 | Private sale inputs | 4205270.855252686397793452 GMI | 303.67 | 405.04 |
| [T162](https://bscscan.com/tx/0xb735822a5692dbbc3b9384993ba43cecd70ccc0e41b4755115ab12cfd0c35c61) | 2022-11-24 13:37:22 | Private sale proceeds BUSD | 290.463375480966450319 BUSD | 290.52 | 387.50 |
| [T163](https://bscscan.com/tx/0xc92cbef1aec7fd7153f85438f9f9b83b474b595abd51ab17a5bcef76aa2ee9ac) | 2022-11-24 13:38:28 | Private BUSD forwarded to F4F | 290.463375480966450319 BUSD | 290.52 | 387.50 |
| [T164](https://bscscan.com/tx/0xe3760121eaf73afc1d7762708678d9c723c321c4619cb1ff9a234a592b34ae0e) | 2022-11-24 13:40:16 | Private onward transfers BNB | 10 BNB | 2,980.40 | 3,975.26 |
| [T165](https://bscscan.com/tx/0x74c85c4ac133a120803d33610e6b74919252d5cbb5bd2d5e3ebdd80f68e85c6d) | 2022-11-24 23:07:41 | Private sale inputs | 3000000 GMI | 256.04 | 341.51 |
| [T166](https://bscscan.com/tx/0x74c85c4ac133a120803d33610e6b74919252d5cbb5bd2d5e3ebdd80f68e85c6d) | 2022-11-24 23:07:41 | Private sale proceeds BUSD | 247.652902915704154859 BUSD | 247.70 | 330.38 |
| [T167](https://bscscan.com/tx/0x2e34e8eaeca76264c88b3b8308157dfb94fc502a9ad13e76f94056a1bb909464) | 2022-11-24 23:08:08 | Private sale inputs | 2403953.141439514798345089 GMI | 193.02 | 257.45 |
| [T168](https://bscscan.com/tx/0x2e34e8eaeca76264c88b3b8308157dfb94fc502a9ad13e76f94056a1bb909464) | 2022-11-24 23:08:08 | Private sale proceeds BUSD | 187.949896569802101382 BUSD | 187.99 | 250.74 |



### 2022-12

| Record | UTC | Recorded movement | Exact quantity | US$ | C$ |
|---|---|---|---:|---:|---:|
| [T169](https://bscscan.com/tx/0xe25596e34da89e1849546c452b5cb0be0bb6311e70a0a3b1f4e88779bbba936d) | 2022-12-01 07:39:37 | Private sale inputs | 1802964.856079636098758816 GMI | 155.66 | 209.09 |
| [T170](https://bscscan.com/tx/0xe25596e34da89e1849546c452b5cb0be0bb6311e70a0a3b1f4e88779bbba936d) | 2022-12-01 07:39:37 | Private sale proceeds BUSD | 152.291393923795278613 BUSD | 152.34 | 204.64 |
| [T171](https://bscscan.com/tx/0x0a1ece8d035e4618ea259b496a47504479800c3a4d5de45b3104551d2fb03df2) | 2022-12-01 07:40:16 | Private sale inputs | 2704447.284119454148138225 GMI | 225.00 | 302.24 |
| [T172](https://bscscan.com/tx/0x0a1ece8d035e4618ea259b496a47504479800c3a4d5de45b3104551d2fb03df2) | 2022-12-01 07:40:16 | Private sale proceeds BUSD | 218.180807448917693151 BUSD | 218.25 | 293.18 |
| [T173](https://bscscan.com/tx/0x4ba5c45e430bd415b2ea6b65ea28dc49019ea17ebf730c01d5ae2a0e1f9960aa) | 2022-12-01 08:32:39 | Private BUSD forwarded to F4F | 806.075000858219228005 BUSD | 806.08 | 1,082.80 |
| [T174](https://bscscan.com/tx/0x6c9b3728929c1cf686050facd603529eb903aa7117ea2d263df1a50b0e9fe960) | 2022-12-06 10:10:03 | Private sale inputs | 2704447.284119454148138226 GMI | 209.31 | 285.69 |
| [T175](https://bscscan.com/tx/0x6c9b3728929c1cf686050facd603529eb903aa7117ea2d263df1a50b0e9fe960) | 2022-12-06 10:10:03 | Private sale proceeds BUSD | 194.26331405038374757 BUSD | 194.24 | 265.12 |
| [T176](https://bscscan.com/tx/0x3fc4164a2c9e64085fcd617ef88e3d1d53f0b0bde6ad643ee162ccddfe48724f) | 2022-12-06 10:12:33 | Private BUSD forwarded to F4F | 194.26331405038374757 BUSD | 194.24 | 265.12 |
| [T177](https://bscscan.com/tx/0x8abf1eed9f657fc0dcffe1d0fad5f2ba8bd0dccbfcf669c85d9c5447e935271a) | 2022-12-06 10:13:03 | Private onward transfers BNB | 0.5 BNB | 144.18 | 196.79 |
| [T245](https://bscscan.com/tx/0xdbf3b266bfb488139b1a152794957a3c40f627bed7a643215179f696d7179728) | 2022-12-06 10:36:05 | Onward wallet transfers BNB | 0.017368951262722757 BNB | 5.00 | 6.82 |
| [T246](https://bscscan.com/tx/0xdbf3b266bfb488139b1a152794957a3c40f627bed7a643215179f696d7179728) | 2022-12-06 10:36:05 | Onward network fees BNB | 0.000105 BNB | 0.03 | 0.04 |
| [T178](https://bscscan.com/tx/0xf692b324a95a159bd4c5142cd7eed711211ac0b4e85912fa336cfde0ca961453) | 2022-12-06 10:46:01 | Private vesting claims | 10615821.759259259259259259 GMI | 756.09 | 1,031.99 |
| [T247](https://bscscan.com/tx/0xab06d2d16c2eafb08460e7f85fa8e845f817c67d333f926cbc9294b15f362ec4) | 2022-12-06 11:03:10 | Onward swap outputs BUSD | 1428.0263153399440365 BUSD | 1,427.89 | 1,948.92 |
| [T248](https://bscscan.com/tx/0xab06d2d16c2eafb08460e7f85fa8e845f817c67d333f926cbc9294b15f362ec4) | 2022-12-06 11:03:10 | Onward swap inputs BNB | 5 BNB | 1,440.25 | 1,965.80 |
| [T249](https://bscscan.com/tx/0xab06d2d16c2eafb08460e7f85fa8e845f817c67d333f926cbc9294b15f362ec4) | 2022-12-06 11:03:10 | Onward network fees BNB | 0.001056155 BNB | 0.30 | 0.42 |
| [T250](https://bscscan.com/tx/0x779bee4133176e6e6fed539e18560ace9650eab571189fa7bb2c2b2797709ea4) | 2022-12-06 11:30:05 | Onward wallet transfers BNB | 0.006936496375680644 BNB | 2.00 | 2.73 |
| [T251](https://bscscan.com/tx/0x779bee4133176e6e6fed539e18560ace9650eab571189fa7bb2c2b2797709ea4) | 2022-12-06 11:30:05 | Onward network fees BNB | 0.000105 BNB | 0.03 | 0.04 |
| [T179](https://bscscan.com/tx/0x782a3cb1e15038899222d883a233bcf031c20236ba0b8a3f8584052d799de7ae) | 2022-12-06 11:32:09 | Private other incoming GMI | 9900 GMI | 0.73 | 0.99 |
| [T252](https://bscscan.com/tx/0xdc043f84a9e460faaef01d94eafe7d9ceafa4f18d3d5184f3c455d83c9096c4b) | 2022-12-07 01:05:12 | Onward network fees BNB | 0.00022203 BNB | 0.06 | 0.09 |
| [T253](https://bscscan.com/tx/0x2fec8bc59c14e1fc77f5e16d00f3ecb10682e918f1ca8870e18676a5446d6931) | 2022-12-07 01:05:12 | Onward swap inputs BTCB | 0.02 BTCB | 341.12 | 465.29 |
| [T254](https://bscscan.com/tx/0x2fec8bc59c14e1fc77f5e16d00f3ecb10682e918f1ca8870e18676a5446d6931) | 2022-12-07 01:05:12 | Onward swap outputs BUSD | 337.75700890945698599 BUSD | 337.76 | 460.70 |
| [T255](https://bscscan.com/tx/0x2fec8bc59c14e1fc77f5e16d00f3ecb10682e918f1ca8870e18676a5446d6931) | 2022-12-07 01:05:12 | Onward network fees BNB | 0.000930075 BNB | 0.27 | 0.37 |
| [T180](https://bscscan.com/tx/0x3d8cf351398adcaf852da8181972129eae09e720015748b5a77ed011d2481035) | 2022-12-07 01:07:54 | Private sale inputs | 4000000 GMI | 265.75 | 362.49 |
| [T181](https://bscscan.com/tx/0x3d8cf351398adcaf852da8181972129eae09e720015748b5a77ed011d2481035) | 2022-12-07 01:07:54 | Private sale proceeds BUSD | 240.722539323977159667 BUSD | 240.72 | 328.35 |
| [T182](https://bscscan.com/tx/0xd46a5bc6611b3a72085c6f73a02eb33f23080c99b973633d84e1d16baf8ad2bd) | 2022-12-07 01:08:30 | Private BUSD forwarded to F4F | 240.722539323977159667 BUSD | 240.72 | 328.35 |
| [T256](https://bscscan.com/tx/0xe404938b865ac88a13af6129c79a0d5e034c4bf279f3102241d6bda76672196d) | 2022-12-07 02:32:02 | Onward wallet transfers BUSD | 6590 BUSD | 6,589.99 | 8,988.75 |
| [T257](https://bscscan.com/tx/0xe404938b865ac88a13af6129c79a0d5e034c4bf279f3102241d6bda76672196d) | 2022-12-07 02:32:02 | Onward network fees BNB | 0.000255575 BNB | 0.07 | 0.10 |
| [T258](https://bscscan.com/tx/0x68b04457378b7185c1a584699ef89eae0145337b78e7aad06e666d7c7e0c3369) | 2022-12-07 02:32:55 | Onward wallet transfers USDT | 6410 USDT | 6,410.00 | 8,743.24 |
| [T259](https://bscscan.com/tx/0x68b04457378b7185c1a584699ef89eae0145337b78e7aad06e666d7c7e0c3369) | 2022-12-07 02:32:55 | Onward network fees BNB | 0.000255635 BNB | 0.07 | 0.10 |
| [T183](https://bscscan.com/tx/0xbf14d9959df516b8d028ac4e89084ce160b47375f52dc92ad1a4b6a232fdb0e5) | 2022-12-08 02:24:42 | Private exchange intermediary | 5000000 GMI | 467.39 | 634.81 |
| [T184](https://bscscan.com/tx/0xff3ac1adab98247b4a1c468612618e00f322c6a7ab66b3b9825150a7f7aa4d8f) | 2022-12-08 02:27:14 | Private MEXC 2e8 receipt | 5000000 GMI | 467.87 | 635.46 |
| [T185](https://bscscan.com/tx/0x61380c2e3f616522cc8e9dbd0ace06a26738d159f74593153dab4eb810d9e7bb) | 2022-12-08 06:27:46 | Private sale inputs | 1625721.759259259259259259 GMI | 171.34 | 232.71 |
| [T186](https://bscscan.com/tx/0x61380c2e3f616522cc8e9dbd0ace06a26738d159f74593153dab4eb810d9e7bb) | 2022-12-08 06:27:46 | Private sale proceeds BUSD | 161.912373055634703665 BUSD | 161.91 | 219.91 |
| [T187](https://bscscan.com/tx/0x325e3df49c8f81d74d5343bff786dd8d08f4996d798cefff4a31dcbf8e4b1078) | 2022-12-08 06:32:39 | Private vesting claims | 608016.975308641975308642 GMI | 59.66 | 81.03 |
| [T188](https://bscscan.com/tx/0x227aa6faa58237f47a7dc3ccf0e6c0265d1cb8245acc35aacfdccbee6f3d95c8) | 2022-12-14 16:00:38 | Private sale inputs | 608016.975308641975308642 GMI | 50.51 | 68.49 |
| [T189](https://bscscan.com/tx/0x227aa6faa58237f47a7dc3ccf0e6c0265d1cb8245acc35aacfdccbee6f3d95c8) | 2022-12-14 16:00:38 | Private sale proceeds CAKE | 13.065639141470576526 CAKE | 49.50 | 67.13 |
| [T190](https://bscscan.com/tx/0x03aa7debf2d0fe654828d9b560902166f050f499d1be2cd20dadcf69c22e8639) | 2022-12-14 16:01:19 | Private vesting claims | 2131635.802469135802469136 GMI | 171.20 | 232.17 |
| [T191](https://bscscan.com/tx/0x30c5e3af5fa69cf54e59ec46a3cf3c74ffea59cd3e795cf6aa8923b6482aca71) | 2022-12-14 16:02:19 | Private asset conversion input CAKE | 13.065639141470576526 CAKE | 49.56 | 67.21 |
| [T192](https://bscscan.com/tx/0x30c5e3af5fa69cf54e59ec46a3cf3c74ffea59cd3e795cf6aa8923b6482aca71) | 2022-12-14 16:02:19 | Private asset conversion output BUSD | 49.354088681602483584 BUSD | 49.35 | 66.92 |



### 2023-01

| Record | UTC | Recorded movement | Exact quantity | US$ | C$ |
|---|---|---|---:|---:|---:|
| [T193](https://bscscan.com/tx/0x8657b3b3182771a12734fa434536f6f2a667246a2f94998546da301f7e464f3d) | 2023-01-20 05:38:45 | Private vesting claims | 9998962.191358024691358025 GMI | 811.64 | 1,089.31 |
| [T194](https://bscscan.com/tx/0x411c9e992b80d6bb8a0f88127c51f9428c5f78950f5eb527ca99e2521e618dd8) | 2023-01-20 05:40:30 | Private sale inputs | 3032649.49845679012345679 GMI | 245.81 | 329.90 |
| [T195](https://bscscan.com/tx/0x411c9e992b80d6bb8a0f88127c51f9428c5f78950f5eb527ca99e2521e618dd8) | 2023-01-20 05:40:30 | Private sale proceeds BUSD | 225.410169579752827331 BUSD | 225.41 | 302.52 |
| [T196](https://bscscan.com/tx/0xa599f04b0cc1343b3c1048b5d4275ba1bdd587a960f37b95368bc8b04463b095) | 2023-01-21 02:29:17 | Private sale proceeds BNB | 0.582235106329889742 BNB | 177.60 | 238.35 |
| [T197](https://bscscan.com/tx/0xa599f04b0cc1343b3c1048b5d4275ba1bdd587a960f37b95368bc8b04463b095) | 2023-01-21 02:29:17 | Private sale inputs | 2274487.123842592592592592 GMI | 189.64 | 254.51 |
| [T198](https://bscscan.com/tx/0x331197c814cfecdbb91b25a81097b2b1280e65842abeffaa997c2f34bee5b77a) | 2023-01-21 02:31:35 | Private exchange intermediary | 3000000 GMI | 232.05 | 311.43 |
| [T199](https://bscscan.com/tx/0x2e371d5d37cc3deaef36f8c4798f0a18256257304d8eb4db697e6b4414cec02e) | 2023-01-21 02:34:05 | Private MEXC 4982 receipt | 3000000 GMI | 231.98 | 311.33 |
| [T200](https://bscscan.com/tx/0x7f556eb1d5da208355961506485c529d11ee850d5ebf136188a9a5e20dc202e5) | 2023-01-24 15:45:16 | Launchpool January coverage crossing | 8309.56763892731 GMI | 0.75 | 1.00 |



### 2023-02

| Record | UTC | Recorded movement | Exact quantity | US$ | C$ |
|---|---|---|---:|---:|---:|
| [T201](https://bscscan.com/tx/0x56da94a4b0cf7b380063929853763a2fa81aaf548b9e9a2e3f4d477688a7e0a5) | 2023-02-25 12:49:01 | Private sale inputs | 955865.342881944444444444 GMI | 92.33 | 125.78 |
| [T202](https://bscscan.com/tx/0x56da94a4b0cf7b380063929853763a2fa81aaf548b9e9a2e3f4d477688a7e0a5) | 2023-02-25 12:49:01 | Private sale proceeds BUSD | 89.301011917324055514 BUSD | 89.30 | 121.65 |
| [T203](https://bscscan.com/tx/0x776d2561d6329ba685647cc04cc2b4d42465c597be0cd1ae3a196c4df2d13d96) | 2023-02-25 12:49:28 | Private sale inputs | 1433798.014322916666666667 GMI | 130.53 | 177.81 |
| [T204](https://bscscan.com/tx/0x776d2561d6329ba685647cc04cc2b4d42465c597be0cd1ae3a196c4df2d13d96) | 2023-02-25 12:49:28 | Private sale proceeds BUSD | 124.564682082873742182 BUSD | 124.56 | 169.68 |
| [T205](https://bscscan.com/tx/0xd505ac7b81c6f1f2724eed8faafee4650ab6e70168f6d5ad2225e982dce560ff) | 2023-02-26 06:07:24 | Private sale inputs | 1433798.014322916666666668 GMI | 146.33 | 199.33 |
| [T206](https://bscscan.com/tx/0xd505ac7b81c6f1f2724eed8faafee4650ab6e70168f6d5ad2225e982dce560ff) | 2023-02-26 06:07:24 | Private sale proceeds BUSD | 139.279474641857817825 BUSD | 139.27 | 189.71 |



### 2023-04

| Record | UTC | Recorded movement | Exact quantity | US$ | C$ |
|---|---|---|---:|---:|---:|
| [T207](https://bscscan.com/tx/0xab1707a54f5d665be52be7c7f6e1a40f85575e835c884c92a69381dc6f730334) | 2023-04-04 10:56:48 | Private BUSD forwarded to F4F | 789.821799959045630101 BUSD | 789.67 | 1,061.87 |
| [T208](https://bscscan.com/tx/0xd9e76558654e142eb8355e18842c16e4985a0be2f03dd0e4b4e596bf713e9d58) | 2023-04-04 10:57:48 | Private onward transfers BNB | 0.840230960291603498 BNB | 260.48 | 350.27 |



### 2023-05

| Record | UTC | Recorded movement | Exact quantity | US$ | C$ |
|---|---|---|---:|---:|---:|
| [T260](https://bscscan.com/tx/0xcad217ad6766e48d3ada3297272b3b1f441067ffde02334468447fde0b1b3e60) | 2023-05-16 09:55:56 | Onward swap outputs USDT | 3398.645844082231 USDT | 3,399.33 | 4,574.14 |
| [T261](https://bscscan.com/tx/0xcad217ad6766e48d3ada3297272b3b1f441067ffde02334468447fde0b1b3e60) | 2023-05-16 09:55:56 | Onward swap inputs BNB | 11 BNB | 3,429.53 | 4,614.78 |
| [T262](https://bscscan.com/tx/0xcad217ad6766e48d3ada3297272b3b1f441067ffde02334468447fde0b1b3e60) | 2023-05-16 09:55:56 | Onward network fees BNB | 0.000582534 BNB | 0.18 | 0.24 |



## Appendix D — Background source register

Original public source links below are retained from the historical review. This consolidation did not perform a fresh live-web investigation. Source page locators refer to Research_Paper_GamiFi_Master_Investigation.pdf unless specified otherwise.

- **B01:** Complete February litepaper, tokenomics page 8 and allocations pages 14-15: https://web.archive.org/web/20220221193850/https://gamifi.gg/gamifi-litepaper-1.1.pdf — prior memorandum pages 4-6; GAMIFI_MISSING_LINKS section 5. Complete local PDF and extracted text preserved.
- **B02:** Golden Ticket offer, capture 4 October 2023: https://web.archive.org/web/20231004122812/https://app.gamifi.gg/buy-nft/ — pages 5 and 11.
- **B03:** Participation thresholds announcement: https://web.archive.org/web/20220131102740/https://gamifi-launchpad.medium.com/updated-tiers-information-99fd49d0d554 — page 4.
- **B04:** GAMI issuer release: https://via.tt.se/pressmeddelande/3317115/play-to-earn-company-gami-lists-gamifis-first-launchpad-ido?publisherId=259167 — pages 4, 8-9.
- **B05:** May 4 validity extension: https://web.archive.org/web/20220504011833/https://gamifi-launchpad.medium.com/new-staking-pools-launch-290e4bcc4c79 — pages 4 and 9.
- **B06:** June 29 cancellation: https://web.archive.org/web/20220629111324/https://gamifi-launchpad.medium.com/shibafriend-ido-announcement-e57f229783f7 — pages 9 and 11.
- **B07:** FOMO September schedule: https://gamifi-launchpad.medium.com/fomo-lab-ido-update-7733bd7d5693 ; distribution report https://t.me/GamiFiAnnouncements/813 — page 11.
- **B08:** Archived January team page: https://web.archive.org/web/20220127060611/https://gamifi.gg/ — page 8.
- **B09:** Nativz, 9 July 2022: https://www.nativzgaming.com/p/newsletter-09-07-22 — page 8; GAMIFI_MISSING_LINKS section 2.
- **B10:** Techstars partnership release: https://www.businesswire.com/news/home/20210630005204/en/Techstars-partners-with-Alphabit-Fund-and-Launchpool-to-bring-blockchain-focused-accelerator-to-London — GAMIFI_MISSING_LINKS section 2.
- **B11:** MEXC interview, indexed-source limitation applies: https://blog.mexc.com/mexc-ama-gamefi-session-with-laura-and-casey/ — pages 8-10.
- **B12:** Episode 33: https://pod.co/gamifi-everything-beyond-the-metaverse/33-a-conversation-with-gamifis-laura-walsh-and-casey-mcquillan ; RSS https://feeds.captivate.fm/gamifi/ — pages 9-10.
- **B13:** Mystery Box article: https://web.archive.org/web/20220703083857/https://gamifi-launchpad.medium.com/gamifi-mystery-box-nfts-2840e0eb885e — pages 5-6, 9-10.
- **B14:** CEO succession: https://web.archive.org/web/20220901114231/https://gamifi-launchpad.medium.com/new-ceo-for-gamifi-451f0e5a2147 — page 9.
- **B15:** Homepage captures: https://web.archive.org/web/20220904205757/https://gamifi.gg/ ; https://web.archive.org/web/20220906231901/https://gamifi.gg/ — page 8.
- **B16:** October pause: https://web.archive.org/web/20221004040428/https://gamifi-launchpad.medium.com/gamifi-update-f8d6326f1780 — pages 9 and 11.
- **B17:** Yield/Launchpool corporate accounts: https://yieldapp.medium.com/yield-app-partners-with-launchpool-provides-corporate-accounts-for-defi-projects-b70a68293245 — GAMIFI_MISSING_LINKS section 1.
- **B18:** Alphabit Form D: https://www.sec.gov/Archives/edgar/data/1729768/000094562118000060/xslFormDX01/primary_doc.xml — GAMIFI_MISSING_LINKS section 4.
- **B19:** November 15 litepaper: https://web.archive.org/web/20211115123436/https://gamifi.gg/gamifi-litepaper-1.0.pdf — page 6; archived version comparisons in evidence.
- **B20:** GAMI project page: https://web.archive.org/web/20220328170117/https://app.gamifi.gg/projects/gami/ — page 4.
- **B21:** Time Raiders original: https://web.archive.org/web/20220303150653/https://gamifi-launchpad.medium.com/ido-announcement-time-raiders-9e36dc1cd3ca — page 7.
- **B22:** First recovered corrected Time Raiders body: https://web.archive.org/web/20220810192341/https://gamifi-launchpad.medium.com/ido-announcement-time-raiders-9e36dc1cd3ca?source=read_next_recirc---------3---------------------8f489997_d0ee_4352_b7d4_fc093530a589------- — page 7.
- **B23:** Last recovered project homepage: https://web.archive.org/web/20240725004059/https://gamifi.gg/ — page 11. Adult-portal boundary is an archive observation, not a new operator attribution.
- **B24:** Initial GMI creation: https://bscscan.com/tx/0x9fe6991e983acb627cfaeb307bcb3a0d26bedfc1ad9a7de296722c9b82b4ff08 — page 12; raw RPC evidence controls.
- **B25:** First January upgrade: https://bscscan.com/tx/0x0ed5defdf69f72c0477452d8fbcc4d5a95e47f561ee82adcceaa5989fa84610f — page 12.
- **B26:** January return upgrade: https://bscscan.com/tx/0xec9679ec01f500b5be1684b6e6612fc75f1a9a7b7c52a47c9e25a9481f0e08f3 — page 12.
- **B27:** Matched token source: https://github.com/sheandev/gamifiContracts/blob/main/contracts/Token.sol — page 12.
- **B28:** Mystery implementation source record: https://sourcify.dev/server/v2/contract/56/0xced850373d573b58d2494c41f04d1fe34b965dfe?fields=all — page 13; legal_chain_followup/nft_burn_lane.
- **B29:** Duke implementation source record: https://sourcify.dev/server/v2/contract/56/0x1979dac9cff265bd446d08b5a162c05e417196e2?fields=all — page 13; legal_chain_followup/nft_burn_lane.
- **B30:** Dated launch announcement: https://web.archive.org/web/20220117125329/https://gamifi-launchpad.medium.com/fair-launch-notice-a842e1bf320c — page 14; historical blocks and receipts in legal_chain_followup/trading_lane.

- **B31:** Ghaf Capital portfolio, prior indexed-source limitation applies: https://ghafcapital.ae/investments.html — GAMIFI_MISSING_LINKS section 2.
- **B32:** Earlier Launchpool terms: https://web.archive.org/web/20210519003035/https://launchpool.xyz/terms-conditions/ ; https://web.archive.org/web/20220128063358/https://launchpool.xyz/terms-conditions/ — GAMIFI_MISSING_LINKS section 3.
- **B33:** Yield February terms: https://uploads-ssl.webflow.com/5f3b1e7e87a54051ee78b018/6023cb387c3551136db68ec2_YIELD%20-%20T%26C%20-%20FEB%2010.pdf — GAMIFI_MISSING_LINKS section 3.
- **B34:** GamiFi terms: https://web.archive.org/web/20221007163947/https://app.gamifi.gg/terms-and-conditions/ — GAMIFI_MISSING_LINKS section 3 and current BVI findings.

The PDF also prints the full targets of the report’s source hyperlinks. The separate FULL_HYPERLINK_TARGET_REGISTER_2026-09-06.md preserves that register in editable form. Archived URLs identify particular capture dates; current availability may differ.
