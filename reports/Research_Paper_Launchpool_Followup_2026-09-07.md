# Launchpool follow-up integrated into the master report

Research date: 7 September 2026 UTC

## 9. Claims, continuity and transition follow-up

Public-record and read-only blockchain checks | 7 September 2026 UTC

**The website problem is corroborated by DNS records. A separate Mintlayer final-claim system remains accessible and is fully backed for the published unclaimed allocations at the checked block.** The historical GamiFi deficit is a different contract and token. The follow-up also identifies publicly represented Launchpool operating leadership after the 2024 transition.

### 9.1 Website observations and their limits

| Observation | Evidence and meaning |
| --- | --- |
| Domain registration | CentralNic registry RDAP lists expiration on 18 September 2026, 23:59:59 UTC. The domain had not expired at the 7 September check. Registrar: GoDaddy. No registrant identity was disclosed. [F01] |
| Web-address resolution | Google DNS returned no A/AAAA address for the apex and NXDOMAIN for app/www. Cloudflare DNS independently agreed for apex A and app A. These establish resolver failures at the checked time. [F02] |
| Last recovered app capture | 28 January 2026, 01:29:04 UTC: substantive Launchpool HTML with navigation, sign-in fields and a Panama footer. Its content digest matches an April 2025 capture; it is a shell, not proof that login, balances or claims worked. [F03] |
| Other live surface | The separate Mintlayer final-claim page returned HTTP 200. Its application bundle and public allocation files were recovered. Official Launchpool notices identify this claim route. [F04-F05] |

RDAP and resolver nameserver lists differ; the observed SOA points to Netlify. This is a configuration-history lead. No account log establishes who changed the settings, when the web addresses disappeared, or why. Registry change fields and SOA serials are not treated as deletion dates. [F01-F02]

**Still open:** DNS/hosting change logs, the last verified functioning customer session, service/closure notices and affected-user access outcomes. A January archive response and September DNS failures do not establish continuous functionality or a precise shutdown interval.


---

## 9.2 Mintlayer: all published claims reconciled

Ethereum block **25,923,249** | 7 September 2026, **05:00:23 UTC**. Amounts are ML tokens, not dollars. Wallet counts do not identify distinct people. [F05-F07]

Final distributor: 0xcc32853fb709666332cde0fc47f3f74119b970c4
ERC-20 ML token: 0x059956483753947536204e89bfad909e1a434cc6

| Measure | Exact result |
| --- | --- |
| Published allocation ledger | 1,999 unique wallet/index records; indices 0-1998 |
| Total allocated ML | 1,294,650.3000849776853554 |
| Claimed records / ML | 119 / 178,609.45446753072393 |
| Unclaimed records / ML | 1,880 / 1,116,040.8456174469614254 |
| Distributor ML balance | 1,116,041.281767546177360307 |
| Balance above unclaimed ledger | 0.436150099215934907 ML |

**Finding:** this distributor has sufficient token backing for its entire published unclaimed ledger at the checked block. The 1.116 million unclaimed ML is not a missing-funds total. This does not establish that the ledger includes every historically entitled Raise 2 participant.

### Independent verification

Every readable allocation equals its raw integer amount at the token's verified 18 decimals. All 1,999 cryptographic allocation proofs validate; an independent tree reconstruction reproduces the published root, and the deployed root matches it. All eight claimed-bitmap storage words were checked, with no set bits outside the allocation range. [F05-F07]

All 119 successful claim inputs match the ledger and bitmap, and each matches an ML transfer to the specified beneficiary. The 123 ML transfer events in the retrieved history reconcile exactly to the pinned balance. One unrelated token event is excluded from ML accounting. The last successful claim in that history was 3 May 2026, 12:57:47 UTC. [F06-F07]

Merkle root:

0x031862a21347c8b43c3fd3e7d67615141f32476371b3a31e3447de2530d06aa7


---

## 9.3 Mintlayer: control and the corrected deadline

### The migration deadline is now 1 November 2026

The older Launchpool feed referred to January and then April 2026 ERC-20 support/migration dates. Mintlayer's current official ML page instead states that its migration tool remains open until **1 November 2026**, with requests processed every two weeks from 1 August to that date. The separate migration page also loads. This supersedes the April date for current reporting. [F04, F08]

Mintlayer says the tool will then close and unmigrated ERC-20 tokens will remain locked rather than burned. That is a published policy, not a demonstrated future contract event. No migration was submitted in this research, and no individual mainnet delivery was verified. Older generic 48-hour UI text should not override the newer dated processing schedule. [F08]

### Identified contract authority

At the pinned Ethereum block, owner() and the immutable treasury both identify:
0x6c2b3a90acb72ef896325e19af9098d157f929c4
The verified deployed source permits the owner to withdraw the token balance to that treasury and contains no calendar cutoff in claim(). This identifies contract powers, not the human signer or a company mandate. [F06]

| Dated event | Verified result |
| --- | --- |
| 25 August 2025 | Distributor deployed. Deployer: 0xb72fc236Ab043029776b9d25e99A5B6456A2e16D. [F06] |
| 30 September 2025 | Ownership transferred to the treasury address. [F06] |
| 10 October 2025 | A 1-ML deposit and successful 1-ML owner withdrawal preceded the bulk funding. Later deposits backed the allocation ledger. [F06-F07] |
| 25 March 2026 | A withdrawal call from a different address reverted; no ML withdrawal resulted. [F06-F07] |
| 3 May 2026 | A successful claim occurred after the older April deadline. Neither that date nor the current migration policy creates a calendar expiry inside this distributor. [F06-F08] |

**Remaining claims questions:** reconcile the 1,999-record final ledger to original Raise 2 purchases and earlier rounds; identify the treasury controller and mandate; determine whether notices reached the remaining holders; and verify mainnet receipt after any migration. The current token backing result closes a balance question, not these delivery and identity questions.


---

## 9.4 GamiFi remains a separate reconciliation

BNB Smart Chain | fresh state block **120,435,314**, **7 September 2026, 05:04:55 UTC**. [F09]

GMI token: 0x93d8d25e3c9a847a5da79f79ecac89461feca846
Launchpool vesting vault: 0xf50488dc8339fb7d1d5a8e8b401c4a5d71a090bb

| Evidence date / scope | Measured result |
| --- | --- |
| Fresh balance, 7 September | 207.412329404181026961 GMI; token decimals 18. |
| Fresh administrative owner | 0xf27f9a2eb9b2c70d32476cf9dc2d74ca4e61c27b; no deployed bytecode returned for that address at the checked block. |
| Prior audited schedule book | 39 funding transactions on 19 April 2022; 7,495 schedules for 7,490 distinct addresses; total 15,456,885.882908530406846 GMI. [F10] |
| Prior 6 September observation | Unpaid original schedules: 14,000,207.412329404181026961 GMI. Balance: 207.412329404181026961 GMI. Difference: 14,000,000 GMI. [F10] |

The new balance equals the earlier balance exactly. **The unpaid schedule book was not recalculated in this follow-up.** The historical 14-million-GMI finding retains its earlier observation date and supporting evidence. Equal endpoint balances do not establish no intervening activity; the fresh owner address does not identify the historical human signer. [F09-F10]

### What the 2024 status label says

Launchpool's 2024 project notice places GamiFi in the **Completed Vesting** category, while Mintlayer was still listed in vesting. The label does not explicitly say every beneficiary was paid. A schedule can finish maturing while claims remain unpaid. The relevant test is whether original obligations were delivered, refunded, migrated or discharged elsewhere. [F11]

### Lifetime history remains open

No requested GMI transfer-log interval completed successfully. Even 100-block queries returned provider limits; other sources were unavailable. These failed requests cannot support a zero-transfer conclusion. Complete transfers, refills, claims, control changes and any alternate settlement records are still required. Raw access results and the successful fresh-state reads are preserved separately. [F09]

The original study records Laura's GamiFi replacement announcement on 1 September 2022, before the November control changes and withdrawals. This pass supplies no new evidence attributing those actions to her. [S18; F10]


---

## 9.5 The 2024 operating transition is clearer

**Roxana Nasoi was publicly identified as Launchpool CEO by July 2024.** Launchpool's 26 July article identifies her in that role during its 19 July discussion; the Labs site also uses the title beside its 2024 XDC program. These are operating-role statements, not Carajo shareholder or director records. The same article calls Decentric a sister launchpad; no legal ownership chain follows from that phrase. [F12-F13]

| Migration evidence | What it adds |
| --- | --- |
| 28 April 2024: Gate notice | Supports a 1:1 token migration and identifies the new Arbitrum LPOOL contract. This is exchange-side corroboration, not identification of the corporate signatories. [F14] |
| July 2024 reopening | Official post 1606 gives missed-window users another opportunity: KYC and old-token burning by midnight Friday 26 July; claim instructions follow. Messages 1609/1610 announce final claims. The earlier cutoff was not the last opportunity announced. [F15] |
| Unizen partnership scope | The 3 May 2023 joint announcement identifies a strategic relationship. The later migration FAQ withholds guaranteed swaps for Unizen farming rewards. Contracts and any amendment/termination notice must distinguish partnership scope from reward authorization. [F16; S22-S23] |

Arbitrum LPOOL token: 0xf6dae0d2be4993b00a2673360820af6bafd53887 [F14]

### Records now targeted more precisely

| Record set | Question it resolves |
| --- | --- |
| Nasoi appointment and handover | Exact start date, employing entity, delegated signing powers and transfer from earlier management. |
| Migration eligibility and payouts | Legacy-chain burn logs, holder snapshot, KYC decisions, exceptions, new-token claim ledger and remaining reserve. |
| Exchange and KYC mandates | Which entity instructed Gate and held the Sumsub client relationship, administration and customer-data responsibilities. |
| Executed transfer documents | Assets/IP/customer contracts transferred to Carajo; consideration, liability assumptions and original issuer identity. |

Carajo's share register, February 2025 voting-owner records, SCR ownership, Linford restoration history and the named regulatory basis remain unresolved. The two Panama deeds remain obtained. No new signed transfer instrument or shareholder record was found; publicly identified operating management narrows only one part of the earlier gap.


---

## 9.6 Laura and the original Mintlayer offers

**The connection is historical platform involvement; no reviewed Mintlayer-specific approval, receipt or wallet-control record names Laura.** Nativz dates her Launchpool COO appointment to May 2021. An 8 October 2021 interview identifies her as COO and records her explanation of the Launchpool/Alphabit allocation model. [F17; S15]

| Dated evidence | What the record establishes |
| --- | --- |
| 22 November-1 December 2021 | First Mintlayer offer: 600,000 BUSD target on BSC; $0.0952 per token; 10% at token generation, then 6% monthly for 15 months. Archived opening and closing-day pages agree. [F18] |
| 16-23 March 2022 | Raise 2 preoffer page targets 350,000 BUSD at about $0.162. It summarizes 20 months, but the launch-week AMA specifies two tranches extending to 34 months. The preoffer page also prints the wrong year. [F19-F20] |
| 13 December 2022 | Mintlayer announces initial Ethereum ERC-20 distribution for 21 March 2023, followed by a future 1:1 distribution to Mojito wallets. Earlier app pages had advertised native Mintlayer delivery. [F18-F19; F25] |
| By 30 March 2023 | Archived Raise 2 page shows a 400,000 BUSD target, a 34-month vesting summary and Ethereum distribution. This dates the recovered page state, not the exact revision or investor agreement. [F19] |

Advertised targets and stake values are not payment receipts. Those app snapshots did not expose a collection wallet; section 9.11 now identifies the contract and pools through recovered public configuration. The early 20-month summary must be read alongside the 34-month launch-week AMA; the evidence does not establish a post-sale extension from 20 to 34 months. [F18-F20]

### Named contacts narrow the records search

The March 2022 AMA names Enrico Rubboli and Andreas Kohl as guests, with a Launchpool host using the name Spiderman. Kohl identifies himself and Sarita Yasmin for investor relations and describes his relationship with Richard and the Alphabit team. The reviewed text does not name Laura. These statements identify contacts, not treasury signers. [F20]

A 2 March 2023 Mintlayer partnership page names Roxana Nasoi as Launchpool Labs managing director. Laura's July 2022 Nativz profile describes separate accelerator-liaison work; her exact COO end date remains unverified. GamiFi's September 2022 CEO change does not establish departure from Launchpool. [F17; F26; S18]

**Personal attribution still requires:** the Mintlayer deal file, approval/signature records, allocation and payment instructions, management handover and communications showing Laura's own role. The search found no such personal bridge.


---

## 9.7 Withdrawal authority and the funding trail

**The distributor owner can already withdraw the entire ML balance to the fixed treasury. Missing 1 November is not a condition for that power.** At the pinned block in section 9.2, owner and treasury are the same address. No retrieved record identifies its human controller or the entity for which it acts. [F06; F21]

Treasury: 0x6c2b3a90acb72ef896325e19af9098d157f929c4
Deployer: 0xb72fc236ab043029776b9d25e99a5b6456a2e16d

| Related deployment | Verified difference in authority |
| --- | --- |
| 24 July 2025 | 0xaf6a981053942dd8cb1ee99c37f99227ed7ca34b: claim/proof/bitmap functions; no owner, treasury or withdrawal function. [F22] |
| 25 August 2025 | 0xcc32853fb709666332cde0fc47f3f74119b970c4: same deployer, ML token and allocation root; adds ownership and withdrawal of the whole ML balance to immutable treasury. [F06; F22] |

The claim/proof logic is unchanged. Neither source includes a calendar expiry or automatic sweep. Initial history access failed; section 9.10 now records zero balance, zero claim bits and explicit empty transfer history. This remains an earlier related deployment, not a proved operational replacement or a second set of liabilities. The reason for the added authority remains undocumented. [F22-F23]

### Three incoming ML transfers funded the treasury

| UTC date / source | Exact ML received |
| --- | --- |
| 2-3 June 2025: unidentified account0x77bfe8d704b1948374bf8dab8328a810b2836e66 | 10 plus 1,246,628.736235076904436035 |
| 26 August 2025, 15:12:11: explorer label MEXC 160x9642b23ed1e01df1092b92641051881a322f5d4e | 48,011.999999999996854272 |
| Combined incoming ML | 1,294,650.736235076901290307 |

The combined inflows exactly equals the two bulk October transfers into the final distributor. The separate 1-ML deposit/return cancels. All seven ML events in the retrieved treasury history net to zero; this is event arithmetic, not a new pinned balance read. [F21]

MEXC-labeled withdrawal transaction:

0xb49e67fb0823b34d8e4864b0a4c442bb27be4959ee28f280e7a10da5e6a3bc8d

The label identifies an exchange hot wallet, not its customer. The transaction gives investigators an exact account/order-mapping target. Initial gas funding of 0.01 ETH came from 0x1aafe5974189e5a854e20617be8176578868da0f on 29 May 2025; shared funding alone does not identify common ownership. [F21]


---

## 9.8 What happens if a holder misses the deadline?

**No automatic payment to Laura or an identified organization is established.** Mintlayer's 1 November 2026 notice concerns access to its migration portal. The assets and contracts below have different custody rules. [F08; F21-F24]

| Asset or stage | Established custody / remaining question |
| --- | --- |
| Original purchase money | All six original Mintlayer withdrawals paid 903,794.346419582485370326 BUSD to 77bf on 3-4 November 2022. Sections 9.19-9.24 trace onward payments. Payment purposes, mandates and human control remain unresolved. These receipts are separate from ML distributor reserves. [F46-F52] |
| Unclaimed ML in the distributor | The current owner can invoke withdraw() and send all ML to the immutable treasury. Without a transaction, the calendar date itself does not move those tokens. Who controls the treasury, and under which mandate, remains unknown. [F06; F21-F23] |
| ML successfully submitted to the migration contract | The portal calls burnTokens(amount, mintlayerAddress). This transfers caller-approved ML into the separate TokenBurner contract and emits an event. Its verified source has no withdrawal or owner function. [F24] |
| Native Mintlayer delivery | An Ethereum submission/event is not proof of native-coin receipt. Individual mainnet payments and the final disposition of any unused native migration reserve remain unreconciled. [F24] |

Separate migration contract: 0xe03aed8dfa6200292a2585918f656e2345ea283f

### The word burned needs a technical distinction

Although the contract and event use burn terminology, the inspected function transfers ERC-20 tokens into the contract; it does not call a supply-reducing burn. Its source has no timestamp check and no native-chain payout logic. The portal application points to this exact contract and function. No wallet transaction was submitted in this research. [F23-F24]

Mintlayer's notice says unmigrated tokens will remain locked and the portal will close. That published wording does not, by itself, demonstrate a future global Ethereum-token freeze, automatic forfeiture, transfer to Laura, or legal extinction of investor claims. Successfully submitting tokens and receiving native ML remain separate events. [F08; F24]

### The records that would answer who benefits

Identify the distributor treasury signer and company mandate; obtain the specified MEXC withdrawal account mapping and upstream source records; reconcile original BUSD payments to signed purchase obligations; recover the authorization and notice for added withdrawal power; and match remaining holder entitlements to final native-chain payments or any alternative settlement.

The source comparison establishes a discretionary withdrawal power and the MEXC transfer establishes a funding route. Neither identifies Laura as beneficiary or proves that the unclaimed, fully backed allocation has been taken. [F21-F24]


---

## 9.9 Upstream ML and the treasury-owned Safe

**The June funding can now be reconciled one step further upstream.** The unidentified account 0x77bf...6e66 received ML from earlier contracts and other wallets before funding the current treasury. Its recovered 90 ML events total 31,915,885.437859292120865343 ML in and the same amount out. This includes repeated movement of tokens; it is not money raised or new investor allocations. [F27]

| Immediate funding calculation | Exact ML |
| --- | --- |
| Carried balance before 29 May 2025 | 675,375.086483023767618475 |
| 29 May: received from contract 0x4d7b...f0a9 | 571,273.64975205313681756 |
| 29 May: sent to a separate Safe address | -10 |
| 2-3 June: combined transfers to current treasury | 1,246,638.736235076904436035 |

At 11:10:47 UTC on 29 May, a call by 0x77bf...6e66 caused the 571,273.64975205313681756 ML transfer from 0x4d7b84910d042f5431b156397bff0db5ebb4f0a9. The explorer labels the method Transfer Remaining To Owner. The source remains unverified. Section 9.12 now verifies the selected owner/time checks in deployed bytecode and reconciles earlier holder payments; the explorer label alone was insufficient. [F27]

Withdrawal transaction:

0xf86225aedc2adce03c53e006d295c8241623154d664ecd92b45f1c3dec3e8769

### A second wallet under the current treasury owner

Safe: 0x03fafab75267cdf75c64a1c86188e612205b455e

| 29 May 2025 UTC | Observed sequence |
| --- | --- |
| 11:12:35 | 0x77bf...6e66 sends 10 ML to the future Safe address. |
| 12:11:23 | 0x1aafe...8da0f sends 0.01 ETH to treasury 0x6c2b...929c4. |
| 12:12:11 | Treasury creates the Safe with itself as sole owner and threshold 1. |

Official Safe creation data and independently decoded initialization bytes agree. At block 25,923,475, fresh RPC reads show the same sole owner, threshold 1, nonce 0 and **10 ML still held in the Safe**. This is separate from the fully backed final distributor. A threshold of one does not require a second owner's approval. Modules and guards were not audited. [F28]

The ML transfer precedes creation by 59 minutes 36 seconds. Prefunding a predicted address is plausible; an attempted historical code check was denied for lack of archive access. The sequence supports an operational link between the upstream wallet and treasury arrangement, but identifies no human controller or company mandate. [F27-F28]


---

## 9.10 Control evidence, exchange leads and refreshed state

### The upstream wallet exercised fundraising authority

On 2 July 2024, 0x77bf...6e66 successfully called claimFundRaising for pools 9 and 10 in verified contract 0x689cf22e945466340f2e0bfd80ac8ee398ab9ecf, receiving a combined **191,393.685754 USDC**. The function is restricted to the owner and pays owner(). This establishes wallet-level administrative control at those calls. Current poolInfo reads identify IAGON (IAG) as the reward token for both pools, matching IAGON's published token address. These are IAG-pool receipts, separate from the original Mintlayer BUSD receipts recovered in section 9.19. [F31]

### The distributor deployer has exchange-facing routes

| Observed route | Meaning and boundary |
| --- | --- |
| 5 June 2025: 90,843 TLOS sold; net 4,761.97158 USDC received by deployer | Exact USDC amount sent to 0xaa3f...b2d1 and then, four minutes later, to Etherscan-labeled Coinbase 10 (0xa9d1...3e43). Three successful transaction/receipt pairs verify the route. These are TLOS sale proceeds. [F29] |
| 2 October 2025: deployer sends 0.006568313627127521 ETH to 0xc989...26ed | That address later sends 0.006559021031199521 ETH to Coinbase 44 (0xb5d8...f511) on 22 August 2026. The long interval and incomplete intervening flows prevent a closed funds reconciliation. [F29] |

These are precise account-mapping leads, not evidence of the exchange customer's identity. Labels are Etherscan attributions, not customer records. No ML event appears in the retained 105-event deployer token history, and neither route establishes diversion of the final distributor balance or a transfer to Laura. [F29]

### Earlier contract gap closed; final allocation unchanged

At Ethereum block **25,923,475, 7 September 2026 05:45:47 UTC**, the July contract has zero ML and all eight claim bitmap words zero. Successful explorer history returns creation only and zero token transfers, with pagination complete. It appears unused in these records; this does not prove an operational replacement or add a second set of debts. [F30]

| Final distributor, refreshed state | Result |
| --- | --- |
| Claimed / unclaimed indices | 119 / 1,880 |
| Unclaimed ML entitlement | 1,116,040.8456174469614254 |
| ML held by distributor | 1,116,041.281767546177360307 |
| Balance above unclaimed amount | 0.436150099215934907 |

All eight bitmap words, owner, treasury, token, root and balance match the preceding snapshot. A fresh full final-contract transfer history was not fetched. The remaining gap is attribution and mandate: who controls 0x77bf...6e66 and 0x6c2b...929c4, who receives the exchange credits, and which signed investor obligations each arrangement serves. Nothing here establishes Laura as beneficiary or a deadline-triggered transfer. [F27-F31]


---

## 9.11 Original BSC fundraising pools identified

**The original Mintlayer fundraising contract is now identified, and its six pools record 903,794.346419582485370326 BUSD raised.** Recovered public application configuration maps Raise 1 to pools 19-21 and Raise 2 to pools 125-127. Pinned contract reads confirm the funding token and matching schedule blocks. [F32-F33]

BSC contract: 0xd975b13cdf91de3aa0e0e888fb827fec3650624a
State: block 120,444,465 | 7 September 2026, 06:13:37 UTC

| Raise / pool | Recorded BUSD raised | Funds claimed flag |
| --- | --- | --- |
| Raise 1 / 19 | 194,775.268548166718546 | True |
| Raise 1 / 20 | 195,415.21517867104204 | True |
| Raise 1 / 21 | 197,226.626562780028172 | True |
| Raise 1 subtotal | 587,417.110289617788758 | All three |
| Raise 2 / 125 | 101,799.763199702252300446 | True |
| Raise 2 / 126 | 103,426.318782728639320062 | True |
| Raise 2 / 127 | 111,151.154147533804991818 | True |
| Raise 2 subtotal | 316,377.236129964696612326 | All three |

The owner getter returns the same upstream ML wallet, 0x77bfe8d704b1948374bf8dab8328a810b2836e66. This establishes its current contract role. The counters are not an independent sum of every investor transfer, and a true claimed flag does not reveal a historical withdrawal recipient or date. Neither the total nor the flags establish missing or stolen funds. [F33]

### One original purchase independently confirmed

On 29 November 2021 at 19:02:49 UTC, a successful fundPledge(21) call transferred **59.820643332035352 BUSD** into this contract and emitted the matching purchase event. The same transaction returned LPOOL staking tokens; that was not a BUSD refund. This purchase belongs within the recorded total and must not be added again. [F34]

### The original withdrawal trail is now recovered

Sections 9.19-9.20 now recover all six original Mintlayer withdrawal receipts and their immediate BUSD outflows. Section 9.16 verifies D975 withdrawal mechanics. Its full source remains unverified; the different Ethereum contract is not used as proof of its authority. [F32-F33; F46-F47]

Provenance limits: archived 2021/2022 app code led to public project records read in 2026, last updated in August 2024 and February 2025. These are not unchanged 2021 snapshots. The reward-token field is a TBUSD test placeholder, not Ethereum ML; project attribution rests on the explicit mapping and corroborating schedule/purchase evidence. The 153-pool contract's aggregate BUSD balance is not a segregated Mintlayer reserve. [F32-F34]


---

## 9.12 Earlier ML payments and vesting origins

**The old contract's previously unexplained 135,122.08850450400117 ML difference is fully accounted for by 236 successful payments.** Public project configuration identifies 0x4d7b...f0a9 as Raise 2, tranche 13, dated 8 November 2024 and displayed as 8.4%. [F32; F35]

Earlier contract: 0x4d7b84910d042f5431b156397bff0db5ebb4f0a9

| Verified movement | Exact ML |
| --- | --- |
| 8 November 2024: funding from 0x77bf...6e66 | 706,395.73825655713798756 |
| 236 claims, 8 November 2024-6 February 2025 | -135,122.08850450400117 |
| 29 May 2025: return to 0x77bf...6e66 | -571,273.64975205313681756 |
| Reconciled remainder / pinned balance | 0 / 0 |

Two explorer histories agree on all 238 ML events. Every successful claim matches its proof, payment and claimed bit. One additional claim attempt failed out of gas, paid nothing, and was later retried successfully. All 236 recipients also appear in the final 1,999-record ledger: 49 have claimed there, while 187 retain combined final allocations of **143,732.0324654474325 ML** in the retained final-state census. Different tranches must not be counted as duplicate liabilities. [F35]

### Withdrawal authority existed without a 2026 wait

Selected deployed-bytecode analysis establishes an owner check and a withdrawal timestamp threshold. At block 25,923,590, the stored delay is zero and the threshold equals creation: 8 November 2024, 12:20:23 UTC. Read-only simulations agree with the owner restriction. The full source remains unverified; these are bounded runtime findings. The May return is established by its actual transfer, not by the simulation. [F35]

### The upstream ML now reaches the original vesting tree

| Direct vesting beneficiary | Total ML received from token contract |
| --- | --- |
| 0x3b883762...1610061 | 4,201,680.67226891 |
| 0x752d11a9...5b62562 | 5,252,100.84033613 |
| 0xdd923ff5...8bd3695 | 1,575,630.2521008 |
| Combined direct releases | 11,029,411.76470584 |

On 21 March 2023, releases to the first two beneficiaries flowed through 0xdd923...3695, which sent 683,000 ML to 0x77bf...6e66 that afternoon. Seven sampled schedules validate against the original or later whitelisted vesting roots. The complete relevant ML ledgers reconcile to pinned balances; inter-wallet turnover is not additional issuance or investor cash. A shared gas/ML counterparty is a lead, not a named controller. [F36]


---

## 9.13 Dated control handover and settlement wallets

**Launchpool's Ethereum fundraising contract changed owner on 11 February 2022 at 08:19:43 UTC.** The earlier owner 0xdb7d...fea6c transferred authority to 0x77bf...6e66. The call and ownership event agree, and the pinned current-owner read still returns 0x77bf...6e66. This is a wallet-control chronology, not a management appointment. [F37]

Ethereum contract: 0x689cf22e945466340f2e0bfd80ac8ee398ab9ecf
Earlier owner: 0xdb7d1459ddce7887266f25de31f090ff0eafea6c

| Observed control / receipts | Verified result |
| --- | --- |
| 17 May 2021, 10:43:53 UTC | Contract created by 0xdb7d...fea6c. |
| 15 fundraising withdrawals in 2021 | 2,520,862.549169 USDC paid to 0xdb7d...fea6c. |
| 11 February 2022, 08:19:43 UTC | Ownership transferred to 0x77bf...6e66. |
| 2 July 2024: IAG pools 9 and 10 | 191,393.685754 USDC paid to 0x77bf...6e66. |
| Complete 17-withdrawal total | 2,712,256.234923 USDC; all events match actual USDC transfers and pool bookkeeping. |

All 21 pools were created in May-July 2021 and use USDC; none specifies the exact ML reward token. These receipts are separate from the original Mintlayer BUSD raises. The deployed Ethereum runtime exactly matches the archived app artifact, corroborating platform attribution. This exact match does not extend to the different BSC D975 runtime. [F32; F37]

### A repeated settlement link predates Mintlayer

Four daily fundraising totals received by the earlier owner exactly match eight later transfers to 0xa594af6496a61423582b19319732e3c7dc072f9f, a wallet that later supplied ML to 0x77bf...6e66. Each pair was 10 USDC plus the remainder, sent after the corresponding fundraising withdrawals. [F36-F37]

| Date UTC | Matched daily USDC total |
| --- | --- |
| 23 June 2021 | 459,688.011230 |
| 5 August 2021 | 445,769.391270 |
| 14 September 2021 | 372,973.160577 |
| 1 October 2021 | 387,592.576407 |
| Combined eight onward transfers | 1,666,023.139484 |

The records support a repeated operational settlement relationship between the earlier fundraising owner and a later ML supplier. They do not provide the earlier owner's complete balance history, exclude commingling, identify the purchase mandate, or name Laura as either wallet's controller. This matched sum is part of existing USDC flows and must not be added as new fundraising. [F36-F37]


---

## 9.14 Exchange routes and remaining attribution

**A connected USDC branch now reaches a specifically labeled KuCoin deposit address.** After receiving 150,010 USDC from 0x77bf...6e66 on 2 July 2024, 0x1991...86d0 sent three payments to 0x4d0d...a7ee. Each amount then reached Etherscan-labeled KuCoin 20. [F38]

Sender: 0x1991e27e2908847c0274a662eb6675002e8386d0
KuCoin Deposit label: 0x4d0d32b42bb4d6a3e3ed503c5faaf49b6b64a7ee
KuCoin 20 label: 0x58edf78281334335effa23101bbe3371b6a36a51

| Date UTC | 1991 to deposit address | Deposit address to KuCoin 20 |
| --- | --- | --- |
| 3 July 2024 | 15,000 USDC | 15,000 USDC |
| 9 July 2024 | 50,250 USDC | 50,250 USDC |
| 14 July 2024 | 15,500 USDC | 15,500 USDC |
| Total | 80,750 USDC | 80,750 USDC |

All six explorer transaction records show successful matching inputs. Two onward sweeps were transferFrom calls by Etherscan-labeled KuCoin 22. The deposit label and sweeps supply a precise exchange-account mapping lead; customer identity remains unknown. Section 9.21 now reconstructs the sender's zero starting USDC event balance and narrows the earlier source-attribution gap, accounting separately for the 20-USDC outside contribution. [F38; F48; F50]

### A separate MEXC route and an exact cash reconciliation

On 2 July 2024, 0x77bf...6e66 sent **10,000 USDC** to 0x9118...05f9, which forwarded the same amount to Etherscan-labeled MEXC 1 about seven minutes later. Both successful transfer logs were independently checked through RPC. The intermediary's complete retained token history contains only these two USDC events. [F38]

The originating IAG fundraising receipt was 191,393.685754 USDC. Outflows totaled 191,413.685754 USDC: the extra 20 came from two distinct lookalike addresses sending 10 each. Their full addresses differ from the genuine recipient, so they are excluded from operator attribution. The remaining 31,403.685754 USDC passed through 0x3b4d...2eef to 0x78d7...5582. These are separate USDC flows, not original Mintlayer BUSD proceeds. [F38]

### What this changes for Laura and the deadline

The evidence now connects original BSC fundraising configuration, current administrative ownership, earlier ML payments, vesting origins and exchange-facing settlement routes. It still does not establish Laura's signing key, personal receipt, exchange account or authority over these funds. The examined evidence establishes no automatic 1 November 2026 payment to Laura. The final distributor remains fully backed at the retained 05:45:47 UTC snapshot; section 9.15 now records a later common-block refresh. [F30; F32-F38]

The D975 original withdrawal receipts and recipients are now recovered in sections 9.19-9.24. Remaining records include wallet signers and corporate mandates, exchange customer mappings, complete purchase-to-tranche reconciliation, and actual native Mintlayer delivery. Public roles and explorer labels do not identify a human key holder. [F46-F53]


---

## 9.15 A second ML reserve and its withdrawal authority

**An additional 2,418,075.7303282383408825 ML remains in an earlier Raise 1 claim contract.** A census of all 24 unique Ethereum tranche addresses in the recovered public configuration found this one nonzero balance; the other 23 hold zero ML. The publisher maps this contract to Raise 1, tranche 11, dated 16 July 2024 and displayed as 6%. [F39]

Raise 1 reserve: 0x9298136ec995aefb1e99fd4087080d3df328162f
Common state block: 25,923,764 | 7 September 2026, 06:43:59 UTC

| Complete token-flow reconciliation | Exact ML |
| --- | --- |
| 16 July 2024: one funding from 0x77bf...6e66 | 2,886,449.7276626812265525 |
| 1,000 outgoing payments to 1,000 recipients | -468,373.99733444288567 |
| Reconciled remaining balance / RPC balance | 2,418,075.7303282383408825 |
| Transfers from this contract to its owner | 0 |

All 1,001 ML events across eleven explorer pages reconcile exactly. The last payout was 16 January 2026. The explorer labels all outgoing payments Claim; 105 successful normal claim calls were separately matched. All 1,000 inputs and proofs were not audited. The verified reserve is a custody balance, not a proved remaining liability or loss total. [F39]

### The upstream owner can already withdraw this reserve

Owner is 0x77bf...6e66, claiming is unpaused, and withdrawal duration is zero. The runtime matches the reviewed 4d7b contract after changing only its two embedded Merkle roots. Owner and nonowner read-only simulations confirm the withdrawal restriction. The stored threshold is its July 2024 creation time; no November 2026 wait applies. No withdrawal was sent in this research. [F35; F39]

### The final Raise 2 reserve remains separately backed

| Final distributor at the same block | Result |
| --- | --- |
| ML held by 0xcc3285...970c4 | 1,116,041.281767546177360307 |
| Unclaimed ledger: 1,880 allocations | 1,116,040.8456174469614254 ML |
| Owner and immutable treasury | 0x6c2b...929c4; unchanged |

Its root and all eight claimed-bitmap words still match the 1,999-record ledger, with 119 claimed indices. The older Raise 1 reserve must not be added as a second copy of those obligations. Fourteen configured earlier addresses currently have no code; that does not establish their historical use or why code is absent. [F39]

**Delivery gap:** the listed Raise 1 proof directory, claims.launchpool.xyz/mintlayer1-11/, returned HTTP 502 in the prior check. The recovered app builds individual proof URLs from that directory plus a checksummed wallet address and .json. An exact archive-prefix query returned no captures; current tree listings of two published Launchpool Merkle repositories exposed no Mintlayer-named ledger. The full allocation ledger and reconciliation with earlier tranches remain unrecovered. Unpaused code and an unlocked app flag do not establish that holders can obtain their proofs. No human signer or automatic payment to Laura is identified. [F39; F45]


---

## 9.16 Actual BSC withdrawals and a ChangeNOW route

**D975's actual bytecode now establishes who can call its fundraising withdrawal and where it directs payment.** The caller must equal owner(); the selected pool's recorded raised amount is used in a token transfer call to the owner at execution time. Fresh simulations and an independent offline interpreter agree. This closes the selected mechanics gap without importing the different Ethereum contract's source. [F40]

At BSC block 120,448,587, 7 September 2026 06:44:32 UTC, owner remains 0x77bf...6e66. Historical owner reads for the original Mintlayer periods failed. Full source equivalence remains unverified, and claimed flags alone are not historical token-transfer receipts. [F40]

### Eighteen historical withdrawals independently verified

| Project / pools | UTC withdrawal date | BUSD received by 77bf |
| --- | --- | --- |
| Championfy / 68-70 | 11 January 2023 | 452,941.643436827790107713 |
| Spark World / 134-136 | 30 March 2023 | 80,117.358323940697139962 |
| Yesports / 80-82 | 13 April 2023 | 396,930.330400262063764776 |
| 5ire / 56-58 | 20 April 2023 | 454,964.151441835747044046 |
| Hinata / 39-41 | 25 April 2023 | 472,707.89103104557463491 |
| Circularr / 146-148 | 3 July 2024 | 60,526.6449367719358245 |
| Selected total: 18 calls |  | 1,918,188.019570683808515907 |

Each successful call, pool event and actual BUSD Transfer receipt agrees on the pool, amount and recipient. Public project records match both D975 and BSC. These are six other projects; section 9.19 separately recovers the original Mintlayer pools 19-21 and 125-127. Indexer rounding was replaced with exact RPC event integers. [F41; F46]

### Circularr receipts connect to the ML treasury gas funder

Two minutes 21 seconds after the last Circularr withdrawal on 3 July 2024, 77bf sent **60,000 BUSD** to 0x1aafe...8da0f, the address that later funded the ML treasury's gas. The next day, 1aafe split it into 100 and 59,900 BUSD. Two intermediaries forwarded those exact amounts to a common destination within 117 and 104 seconds respectively. All four onward transfers have matching successful RPC receipts. [F21; F41]

Destination: 0xa96be652a08d9905f15b7fbe2255708709becd09
BSC-specific OKLink label: ChangeNOW. Withdraw_1; Blockscan/Etherscan label: ChangeNOW: Hot Wallet 2. [F41]

The service-associated destination is established as an explorer attribution. The exchange order, customer, output asset and payout remain unknown. The source wallet can mix funds; the sequence does not identify an undocumented settlement purpose or Laura as beneficiary. A separate Hinata onward transfer of 472,707.8910310446569656 BUSD is verified in the evidence. [F41]


---

## 9.17 The shared wallet reaches Gate, MEXC and KuCoin

**The common gas/ML counterparty is now traced to concrete exchange routes.** Address 0x183600361dc42c6f022fd219c3a9dabbf08c9ce4 received ML from the earlier operational wallets and 525,000 ML in direct vesting releases. Its recovered exact-token histories contain 67 ML and 322 USDC events, with each event ledger netting to zero. These are historical flow totals, not investor liability calculations. [F42]

### ML forwarding is reconciled through an intermediary

Intermediary: 0x980bff583a8133600462bc034871dc548d6bfc84

| ML route | Exact ML |
| --- | --- |
| 183600 to 980b: 20 transfers | 1,234,268.124 |
| Original vesting beneficiary 3b883 to 980b | 21,890.76 |
| Combined incoming ML | 1,256,158.884 |
| 980b to explorer-labeled MEXC 1: 16 transfers | 1,069,905.362 |
| 980b to explorer-labeled MEXC 3: 4 transfers | 186,253.522 |

The complete 202-row token history contains 41 ML events. All incoming ML is accounted for by the two exchange-facing destinations. The evidence is the actual onward transfer record; 980b's separate initial-gas-funder label is not used to infer its operator. Representative successful RPC receipts corroborate both MEXC destinations. [F42]

A separate **118,172 ML** route passes from dd923 through 183600 to an explorer-labeled Gate deposit address, then to a Gate-labeled wallet. Deposit/account mapping remains an exchange-record question. The route does not establish an executed sale or its proceeds. [F42]

### Both connected wallets used the same KuCoin deposit

Between July 2022 and March 2023, 183600 sent **693,701.8471 USDC in ten payments** to 0x4d0d...a7ee, the same KuCoin-labeled deposit address that received 80,750 USDC from 1991 in July 2024. A representative 404,740.72 USDC payment has a successful raw RPC receipt. This establishes reuse of a precise exchange deposit destination across the two wallets; it does not identify the credited customer. [F38; F42]

KuCoin deposit: 0x4d0d32b42bb4d6a3e3ed503c5faaf49b6b64a7ee

### Interpretation and remaining records

These flows connect vesting beneficiaries, an administrative wallet and exchange-facing accounts. They do not show that the still-held Raise 1 or final Raise 2 reserves were withdrawn, or that every token came from a particular investor allocation. Account mandates, exchange customers and actual trade statements remain missing. The following page separately tracks the July 2024 USDC branch through Base. [F39; F42]


---

## 9.18 Base bridge, BAMBOO trades and returned funds

**The July trading route now includes both returns from Base and the later USDT payments.** Wallet 1991 sent 2,100 and 25,000 USDC to 183600, which bridged those amounts from Ethereum to itself on Base through Circle CCTP V1. All four reviewed bridge messages match the source events and destination inputs: outbound nonces 81239/81473 and return nonces 235711/240419. [F42-F44]

Wallet on both chains: 0x183600361dc42c6f022fd219c3a9dabbf08c9ce4
BAMBOO token on Base: 0x689644b86075ed61c647596862c7403e1c474dbf

| Verified July 2024 movement | Amount / result |
| --- | --- |
| 10-11 July: two bridge mints | 27,100 USDC received on Base |
| Eight BAMBOO purchases | 20,100 USDC spent; 3,911,181.851848323949800498 BAMBOO acquired |
| 14 July: first two BAMBOO sales | 2,000,000 BAMBOO sold for 14,116.998523 USDC |
| All fourteen sales, through 23 July | 73,854.395784 USDC received; +53,754.395784 USDC above purchase payments, before native gas |
| 18 July: first return via Ethereum to 1991 | 21,116.99 USDC |
| 23 July: second return to 183600 on Ethereum | 59,737.4 USDC |
| 23 July: Ethereum swap | 59,737.4 USDC exchanged for 59,724.105382 USDT |
| 23 July: two subsequent USDT payments | 1,000 USDT to f695...aae9; 58,724.105382 USDT to 1991 |

All 22 BAMBOO trades have successful Base receipts with 66 matched transfer logs. Five further successful receipts verify the second bridge burn/mint, Ethereum swap and two USDT payments. The 13.294618 difference between swap input and output compares quantities of two different tokens; it is not measured as a fee or fiat loss. [F43-F44]

The complete retrieved 699-row Ethereum USDT history through the return reconciles to zero before the swap and zero after both payments. Historical balanceOf requests failed; this is an event-ledger reconciliation. [F44]

Additional USDT recipient: 0xf695f1d1688698abc97b2e5937ba24934561aae9
No public explorer name tag was retrieved. The payment purpose and recipient's human controller remain unknown. [F44]

### Returns and remaining inventory

The first return left 0.008523 USDC and 1,911,181.851848323949800498 BAMBOO on Base. Later sales closed that inventory except one raw BAMBOO unit. The second bridge began 118 seconds after the final sale. All 34 July USDC events reconcile to **0.005784 USDC** after the second burn; historical reads at Base block 17,475,891 independently confirm that balance and the one-unit BAMBOO remainder. [F43-F44]

The complete indexed Base token history contains 505 rows. Before the first bridge mint, both token balances were zero. At the later 7 September snapshot, block 50,987,229 at 06:50:05 UTC, balances were 0.003937 USDC and one raw BAMBOO unit (0.000000000000000001 token). Later activity is separate from the July trading calculation. [F43-F44]

### Attribution and settlement records

Verified returns to 1991 are 21,116.99 USDC and 58,724.105382 USDT. Section 9.21 follows the returned funds and narrows the initial Base funding to a conditional 27,080-27,100 USDC IAG-pool origin interval. Section 9.22 follows the separate 1,000-USDT payment. Original Mintlayer BUSD and ML reserves remain separate. Native gas and fiat valuation are excluded; the human trader, authorization and allocation of returns remain unresolved. [F39; F44; F48-F50]


---

## 9.19 Original Mintlayer BUSD withdrawals recovered

**All six original Mintlayer fundraising withdrawals paid 903,794.346419582485370326 BUSD to 77bf on 3-4 November 2022.** Successful official BNB RPC receipts now establish actual payment, recipient and time. This closes the historical receipt gap behind the earlier raised-counter finding. It is the same amount, not additional fundraising or a loss estimate. [F33; F46]

BSC fundraising contract: 0xd975b13cdf91de3aa0e0e888fb827fec3650624a
Caller and actual recipient: 0x77bfe8d704b1948374bf8dab8328a810b2836e66

| Pool | UTC payment time | Exact BUSD transferred |
| --- | --- | --- |
| 19 | 3 Nov 2022 09:02:17 | 194,775.268548166718546 |
| 20 | 3 Nov 2022 09:02:44 | 195,415.21517867104204 |
| 21 | 3 Nov 2022 09:03:14 | 197,226.626562780028172 |
| Raise 1 total | Three calls in 57 seconds | 587,417.110289617788758 |
| 125 | 4 Nov 2022 13:59:08 | 101,799.763199702252300446 |
| 126 | 4 Nov 2022 13:59:35 | 103,426.318782728639320062 |
| 127 | 4 Nov 2022 14:00:02 | 111,151.154147533804991818 |
| Raise 2 total | Three calls in 54 seconds | 316,377.236129964696612326 |
| Combined |  | 903,794.346419582485370326 |

### Three matching records for every payment

Each transaction input selects the configured Mintlayer pool using claimFundRaising(uint256). D975 emits the matching FundRaisingClaimed pool/recipient/amount, and the exact BUSD contract emits the same transfer to 77bf. All receipts are successful. Pool mapping matches the public application's BSC deployment and network; similarly numbered pools elsewhere are excluded. [F32-F33; F46]

BUSD token: 0xe9e7cea3dedca5984780bafc599bd69add087d56
Transition blocks: 22,732,478 / 22,732,487 / 22,732,497 and 22,766,632 / 22,766,641 / 22,766,650.

### How the old access gap was resolved

A documented keyless archive endpoint returned historical claimed-state reads. A bounded binary search located adjacent false/true blocks for each pool; official BNB RPC then independently supplied the full block bodies and actual transaction receipts. An independent decoder checked all six payments and 151 preserved historical query points. Failed earlier searches remain preserved with their original limits. [F46]

### What is now established

77bf received original Mintlayer fundraising cash in November 2022 and later operated ML allocation contracts. The following section records the immediate BUSD outflows. Original purchase obligations, payment purposes, company mandates and human signing-key holders remain separate records questions. Laura's public role alone does not identify the person who called these six transactions. [F19; F39; F46-F47]


---

## 9.20 Original BUSD outflows connect to wallet 1991

**Eleven payments moved 896,370 BUSD from 77bf to six addresses within the two reviewed 24-hour windows.** The only positive BUSD inflows in those windows were the six original Mintlayer withdrawals. Historical opening/closing balance calls and official BNB receipts reconcile the flows exactly. One zero-value incoming row is retained but contributes no cash. [F47]

| Recipient from 77bf | Payments | Total BUSD |
| --- | --- | --- |
| 0x1991...386d0 | 4 on 3 November | 267,000 |
| 0xf98f...de420 | 3 across both dates | 424,990 |
| 0xbf7f...ce630 | 1 on 4 November | 150,000 |
| 0x14c8...a7b25 | 1 on 3 November | 29,370 |
| 0x8724...30757 | 1 on 4 November | 25,000 |
| 0x2108...dcc6c | 1 on 3 November | 10 |
| Total | 11 | 896,370 |

### The same address appears in the later cash/trading network

Recipient 0x1991e27e2908847c0274a662eb6675002e8386d0 received 10, 199,990, 25,000 and 42,000 BUSD on 3 November 2022. Its first payment arrived 2 minutes 15 seconds after the final Raise 1 withdrawal. This exact address later received 150,010 USDC from 77bf in July 2024 and participated in the Base trading/return routes. The link is a repeated address relationship across BSC and Ethereum, not an identified human. [F38; F44; F47-F48]

### 54,370 BUSD reaches Binance 51

14c840 received 29,370 BUSD directly from 77bf and 25,000 from 1991, then sent both amounts to Binance 51 at 09:38:08 and 10:00:27 UTC on 3 November. The exact endpoint is 0x8894e0a0c962cb723c1976a4421c95949be2d4e3. Both 1991 and 14c840 opened and closed the window at zero. Raw receipts and historical state calls verify these paths; the Binance customer remains unidentified. This 54,370 is part of the onward total, not additional proceeds. [F47]

### Historical custody balances

| 24-hour window | Opening BUSD | Incoming BUSD | Outgoing BUSD |
| --- | --- | --- | --- |
| Raise 1 | 0.332011149154053912 | 587,417.110289617788758 | 521,370 |
| Raise 2 | 66,047.442300766942811912 | 316,377.236129964696612326 | 375,000 |

Raise 1 closes at **66,047.442300766942811912 BUSD**; the next window opens at that same amount. Raise 2 closes at **7,424.678430731639424238 BUSD**. The original windows cover 3-4 and 4-5 November 2022. Section 9.24 now closes the intervening gap with complete zero-event BUSD queries and matching historical balances, allowing continuous owner reconciliation. These are historical balances, not September 2026 reserves. [F47; F52]

The opening 0.332011149154053912 BUSD predates the Mintlayer receipts and limits exclusive source allocation. Payment purposes, contractual settlement and human control remain unidentified. Full recipient addresses and hashes are in the evidence. [F47]


---

## 9.21 Returned funds and a second KuCoin deposit

**1991 deposited 105,907.029506 USDT through a second KuCoin-labeled deposit address on 24 July 2024.** The whole amount reached the KuCoin 18-labeled wallet nine minutes later. Both transfers have successful raw RPC receipts. This deposit combines the earlier trading return, an existing balance and new receipts. [F48]

| USDT event at 1991 | Change | Balance afterward |
| --- | --- | --- |
| Before 23 July return |  | 8,375.183313 |
| Return from 183600 | +58,724.105382 | 67,099.288695 |
| Payment to 188b | -21,882.27 | 45,217.018695 |
| Payment to 2c94 | -4,000 | 41,217.018695 |
| Receipt from MEXC 1 | +14,690.010811 | 55,907.029506 |
| Receipt from 33b2 | +50,000 | 105,907.029506 |
| Payment to KuCoin Deposit 327a | -105,907.029506 | 0 |

KuCoin Deposit: 0x327ae1e62fdea32763d6e5de1b08ebe84edff303
KuCoin 18: 0x83c41363cbee0081dab75cb841fa24f3db46627e
24 July: deposit 09:32:23 UTC; onward sweep 09:41:23. This deposit address differs from the earlier 4d0d USDC route. Labels identify services, not customers. [F48]

### The first USDC return also moved onward

Before the 21,116.99-USDC return on 18 July, 1991 held an event-derived 11,460 USDC. It then sent 32,500 USDC to 2c94, leaving 76.99; 2c94 forwarded 32,500 to unlabeled 47da one minute later. A separate 8,720.1948-USDT payment followed the same route. After additional July 24 funding, a 318,192.184647-USDC payment went through 0008; its later 318,192.18-USDC transfer to d541 involved other balances. Exact receipts and token separation are preserved. [F48]

### Initial Base funding is now bounded more tightly

The newly complete USDC history reaches zero at 1991 before its July 2 receipts; its only positive inflows before the first return are the 150,010 USDC from 77bf. Upstream, 77bf's event balance was zero before 191,393.685754 USDC of IAG-pool receipts, with only 20 USDC added by the two lookalike-address payments. 183600 also had an event-derived zero USDC balance before receiving and bridging 27,100 USDC. [F38; F48; F50]

**Conservation interval: 27,080-27,100 USDC of the Base funding came through the IAG-pool receipts, conditional on complete captured histories.** Even allocating all 20 USDC of outside funding to that branch leaves 27,080 from the pool receipts. This uses neither FIFO nor proportional allocation, and does not assign investor entitlements or trading profits. It narrows the earlier unbounded source gap. [F50]

370 USDC and 1,577 USDT events each reconcile through the bounded 24 July endpoint. These historical balances are event reconstructions; state calls failed. All 15 selected onward transfers have successful raw receipts, with 14 token-call inputs decoded. Eight misleading other-token/zero rows were excluded. [F48]


---

## 9.22 The 1,000-USDT branch reaches Revolut

**The separate 1,000-USDT payment reached an Etherscan-labeled Revolut hot wallet on 23 July 2024.** 183600 paid f695 at 14:30:23 UTC; f695 forwarded the full amount at 15:57:47, **87 minutes 24 seconds later**. Both legs have successful raw RPC receipts. The reconstructed USDT cycle is zero before receipt and after the sweep, with no intervening USDT events. [F44; F49]

Intermediary: 0xf695f1d1688698abc97b2e5937ba24934561aae9
Revolut: Hot Wallet: 0xf7c8da79da4cb294c4f55dfebb1b404e3e38d921

| 183600 payment date | USDT received | Later sweep to Revolut | Other cycle inputs |
| --- | --- | --- | --- |
| 23 Jul 2024 | 1,000 | 1,000 | 0 |
| 4 Feb 2025 | 252.3037 | 745.8037 | 493.5 |
| 30 Jun 2025 | 305 | 789.581448 | 484.581448 |
| 22 Jul 2025 | 965 | 965 | 0 |
| 4 Aug 2025 | 283.514525 | 513.514525 | 230 |
| 19 Jan 2026 | 170 | 170 | 0 |
| Source total | 2,975.818225 |  |  |

All six source payments fall within balance cycles ending at the same Revolut-labeled endpoint. Three cycles include other inputs, so the larger sweep amounts cannot be assigned entirely to 183600. The five later payments establish repeated use; their upstream funding was outside this bounded inquiry. [F49]

### A service-associated pattern, with customers still unidentified

The complete retrieved USDT history has 65 events: 38 incoming and 27 outgoing, totaling 23,722.265580 USDT each way. Twenty-five payments sent 23,378.068982 USDT to Revolut; two separate September 2024 payments sent 344.196598 USDT to KuCoin Deposit 8e211. These whole-address totals include unrelated funds. [F49]

Etherscan-labeled Revolut 1, 0xb23360ccdd9ed1b15d45e5d3824bb409c8d7c460, provided initial and repeated gas funding: 34 ETH payments totaling 0.02092218 ETH. Together with the repeated sweeps, this is consistent with a service deposit/sweep address. That is a behavioral inference; f695 itself has no retrieved public name tag. [F49]

At Ethereum block 25,925,814, 7 September 2026 13:36:35 UTC, f695 holds zero USDT and 0.034566131300512124 ETH, with empty runtime and nonce 30. All 33 selected USDT edges were checked: 27 successful RPC receipts and six indexed successful-transaction/raw-log confirmations. The latter are not represented as RPC receipts. [F49]

Ancillary indexed activity includes 6.320509399529568055 ETH and 850.921922 USDC sent to the Revolut endpoint; those were not part of the 33-edge USDT receipt audit or assigned to the July trade. The exact incoming and sweep hashes supply account-credit records leads. Explorer labels are not direct confirmation by Revolut, and no customer, human signer, payment purpose or personal receipt by Laura is identified. [F49]


---

## 9.23 Three more BUSD routes converge at Binance

**Three additional branches sent 222,090.52 BUSD to Binance 51 on 3 November 2022.** Of that amount, 222,000 arrived through the already traced owner-payment chain; 90.52 was an intermediary's prior balance. Together with the earlier two transfers, the endpoint received **276,460.52 BUSD in five payments**, including 276,370 from the traced chain. These are further hops of previously counted funds. [F47; F51]

Binance 51 endpoint: 0x8894e0a0c962cb723c1976a4421c95949be2d4e3
Token: canonical BSC BUSD, 0xe9e7cea3dedca5984780bafc599bd69add087d56

| Path before Binance | Endpoint BUSD | UTC on 3 November | Delay after receipt |
| --- | --- | --- | --- |
| 1991 > 0d434 | 200,000 | 11:00:28 | 19m 44s |
| 1991 > ab3c | 2,090.52 | 12:00:37 | 29m 24s |
| f98 > 57e898 | 20,000 | 13:00:41 | 18m 52s |
| New three transfers | 222,090.52 |  |  |
| Earlier two via 14c840 | 54,370 | 09:38:08 / 10:00:27 | See section 9.20 |
| Five-transfer total | 276,460.52 |  |  |

### Each intermediary has a reconciled historical balance

0d434 and 57e898 opened at zero, received 200,000 and 20,000 respectively, sent the full amounts to Binance, and closed at zero. ab3c opened with 90.52, received 2,000 from 1991, then sent 2,090.52 and closed at zero. Complete first-window logs, successful official BNB receipts, matching token calldata and archive balance calls agree. [F51]

### Original-raise source amount

After excluding ab3c's 90.52 and allowing for 77bf's pre-existing 0.332011149154053912 BUSD, the original Mintlayer Raise 1 contribution to these five endpoint payments is bounded at **276,369.667988850845946088-276,370 BUSD**. Independent chronological allocations make both endpoints feasible. This is a conservation bound using captured histories and historical states; it assigns neither investor entitlements nor payment purposes. [F47; F51]

### A second use of the same intermediary

The later continuation finds cedfa sending another 225,000 BUSD to 57e898. The following section records its onward disposition and keeps this later interval separate from the five first-day payments above. [F51-F52]

The exact public explorer label identifies Binance 51. The route does not establish which customer received credit, what happened inside the exchange, or who controlled the sending wallets. Full addresses, transaction hashes and timestamps are in the evidence. No human identity is assigned to an unlabeled intermediary based on its transfer pattern. [F51]


---

## 9.24 Owner continuity and later BUSD custody

**Another 225,000 BUSD reached Binance 51 on 7-8 November 2022.** Cedfa received the second 200,000-BUSD payment from f98, then sent 10, 124,990 and 100,000 to 57e898. That intermediary forwarded 125,000 and 100,000 to Binance, with a complete zero-opening/zero-closing BUSD ledger for the reviewed week. All six route events have successful raw receipts. [F51-F52]

| Binance transfer from 57e898 | UTC | Delay after final input |
| --- | --- | --- |
| 125,000 BUSD | 7 Nov 2022 20:30:06 | 21m 25s |
| 100,000 BUSD | 8 Nov 2022 10:30:06 | 27m 06s |
| Combined later endpoint amount | 225,000 BUSD |  |

### Seven endpoint payments, with prior funds separated

The seven unique Binance receipts across 3, 7 and 8 November total **501,460.52 BUSD**. The original Mintlayer contribution is bounded at **501,153.870312770845946088-501,370 BUSD**. The interval excludes ab3c's 90.52 and allows for cedfa's prior 215.79767608 and the owner's prior 0.332011149154053912 BUSD. The small owner balance is counted once across the joint route. Both chronological extremes are feasible. [F47; F51-F52]

### The owner-window gap is now closed

Both-direction BUSD queries over blocks 22,760,779-22,766,631 returned zero events, and historical balances at both boundaries equal 66,047.442300766942811912 BUSD. Combined with the original windows and the extension, the owner now has a continuous captured BUSD history from the first withdrawal through 12 November 2022. Its accounting remains: opening 0.332011149154053912 + six receipts of 903,794.346419582485370326 - eleven payments of 896,370 = 7,424.678430731639424238 BUSD. [F46-F47; F52]

### What remained at the historical cutoffs

| Wallet | BUSD balance | Cutoff UTC in November 2022 |
| --- | --- | --- |
| 77bf | 7,424.678430731639424238 | 12 Nov / 13:59:08 |
| bf7f | 150,000 | 12 Nov / 13:59:08 |
| 8724 | 25,197.437915171993026378 | 12 Nov / 13:59:08 |
| f98 / 57e898 | 0 / 0 | 12 Nov / 13:59:08 |
| cedfa | 180,205.79767608 | 10 Nov / 09:02:17 |
| dc127 | 40,663 | 10 Nov / 09:02:17 |

The 8724 and dc127 balances include 197.437915171993026378 and 663 BUSD already held before the traced payments. Cedfa also had the prior funds identified above. These are dated custody balances, not amounts confirmed to remain today or a loss estimate. Address windows and overlapping first-day captures are kept distinct. [F51-F52]

No later period beyond the stated cutoffs was scanned in this pass. Successful smaller, slower log batches resolved the preserved rate limits. Exchange customer identity, payment mandate and human signing-key custody remain unresolved. [F51-F52]


---

## 9.25 A returned-funds recipient connects to Kraken

**Wallet 47da later sent 75,000 USDC and 300,000 USDT through dcea into Kraken-labeled collection wallets.** The exact sweeps are verified, including successful receipts and transferFrom calls made by the labeled receiving wallets. These service routes extend the address trail, but the sender's prior balances prevent assigning them specifically to the earlier trading returns. [F48; F53]

Intermediary: 0xdcea03a2a2b8647ae787c4c518dbea1c54ac86d2
Kraken 10: 0xae2d4617c862309a3d75a0ffb358c7a5009c673f
Kraken 7: 0x89e51fa8ca5d66cd220baed62ed01e8951aa7c40

| Asset | 47da > dcea | dcea > Kraken | Collection delay |
| --- | --- | --- | --- |
| 75,000 USDC | 18 Jul 2024 19:00:11 | Kraken 10 / 19:09:47 | 9m 36s |
| 300,000 USDT | 18 Jul 2024 18:59:47 | Kraken 7 / 19:09:47 | 10m |

All times are UTC. dcea's captured USDC and USDT cycles each begin at zero and end at zero, with one receipt and one exact sweep. The named Kraken wallet called the token contract to collect each amount from dcea. This supports exchange collection mechanics; it does not label dcea's customer or identify a human controller. [F53]

### Why the trading return cannot be assigned to these sweeps

Before receiving the selected 32,500-USDC payment from 2c94, 47da already held **136,210.313376 USDC**. Before the separate 8,720.1948-USDT receipt, it held **875,068.711065 USDT**. The 8,720.1948-USDT receipt predates the 23 July trading return. These are successful historical-state reads. The prior funds are sufficient to fund the later Kraken paths, so no positive amount from the selected incoming payments is mathematically forced into either sweep. [F48; F53]

47da's full captured window reconciles 15 USDC events and 69 USDT events against independently queried opening and closing states. Other inflows and outflows remain in the ledger. The 75,000 and 300,000 are separate token amounts and are not added to fundraising proceeds, missing funds or trading profits. [F53]

### The separate d541 branch waited more than five days

Before its 318,192.18-USDC receipt on 24 July, d541 held 228,092.803239 USDC. No outgoing USDC transfer occurred during the next 24 hours. The bounded extension finds one later payment: **21,664 USDC** to 0585 on 30 July at 06:47:35 UTC. Its existing funds exceed that payment, so the source is not unique. The extension follows outgoing USDC only through 31 July 17:23:35 UTC; it is not a complete week-long incoming ledger. [F53]

The endpoint addresses supply specific service-record leads. No exchange customer, fiat withdrawal, corporate mandate or Laura's personal receipt has been identified. Later histories beyond these explicit windows remain outside this pass. [F53]


---

## 9.26 IAG USDC: the complete initial disposition

**The 191,393.685754-USDC IAG pool receipts now reconcile through the initial distribution, with a shared 20-USDC outside contribution.** That contribution is additionally verified by two successful raw dRPC receipts from the canonical USDC contract. Its lookalike senders remain unattributed. The earlier source histories still supply the zero starting event balances. [F38; F48; F50; F54]

| Initial destination or retained balance | USDC |
| --- | --- |
| KuCoin deposit 4d0d via 1991 | 80,750 |
| Base funding via 1991 > 183600 | 27,100 |
| Payments from 1991 to 2c94 | 19,200 |
| Payment from 1991 to 0008 | 11,500 |
| Still at 1991 before 18 July return | 11,460 |
| MEXC route via 9118 | 10,000 |
| Separate route via 3b4d | 31,403.685754 |
| Total disposition / retained balance | 191,413.685754 |
| Less outside receipts | 20 |
| IAG pool contribution | 191,393.685754 |

The first five rows sum to the 150,010 USDC received by 1991. It paid 138,550 before the first trading return, leaving 11,460. The separate 10,000 and 31,403.685754 branches originate directly from 77bf. This partition excludes the later returned funds and avoids counting transfers between these wallets twice. [F54]

### The exchange-source interval is now explicit

The previously verified KuCoin and MEXC routes total **90,750 USDC**. Conditional on complete captured histories, **90,730-90,750 USDC** of that combined amount came through the IAG pool receipts. Including the separately verified 27,100-USDC Base funding gives a combined source interval of **117,830-117,850 USDC**. Independent chronological allocations verify both extremes. [F38; F50; F54]

Only one 20-USDC outside budget exists across the entire distribution. Individual branch minimums cannot be added as though each branch contained another 20 outside USDC. The calculation uses neither FIFO nor proportional allocation. It measures source constraints; it does not determine authorized use, investor entitlement or ownership of trading returns. [F54]

### What the new checks did and did not resolve

The two outside-input receipts are now raw-RPC verified. Publicnode returned null before dRPC succeeded; both outcomes are preserved. A new historical balance request for the original source wallets returned HTTP 403 and supplies no state evidence, so the source intervals retain their event-history completeness condition. Successful state reads for the separate Kraken-route wallets do not replace this missing source-wallet check. [F53-F54]

Bounded exact-address public searches found no reliable corporate declaration or human signing-key attribution for the selected original BUSD recipients. Generic analytics pages, NFT ownership records and API-documentation examples were not treated as proof of company ownership or Laura's control. [F54]


---

## 9.27 BUSD tail checks and exact flow accounting

**No BUSD leaves any of the six remaining wallets within the newly completed windows.** Both-direction canonical logs extend the owner, bf7f and 8724 through 19 November 2022; cedfa and dc127 through 17 November; and the small 2108 branch from 5 through 19 November. One later swap into BUSD is retained explicitly; all other queried BUSD activity is absent. Historical states agree with the complete logs. [F55]

The six wallets also have direct balance reads at one common historical block: **23,129,158, 17 November 2022 at 09:02:15 UTC**. This resolves the previously mixed-date comparison for these retained balances. [F55]

| Wallet | BUSD at the common block |
| --- | --- |
| 77bf owner | 7,424.678430731639424238 |
| bf7f | 150,000 |
| 8724 | 25,197.437915171993026378 |
| cedfa | 180,205.79767608 |
| dc127 | 40,663 |
| 2108 | 10 |
| Six-wallet total | 403,500.914021983632450616 |

These balances include previously held funds. In particular, 8724 began with 197.437915171993026378 and dc127 with 663 BUSD. Cedfa's prior 215.79767608 may have entered earlier payments or remained. The owner's original prior 0.332011149154053912 is a shared source budget. The total is historical token custody, not a current reserve or liability figure. [F47; F51-F52; F55]

### The captured original flow graph reconciles exactly

The earlier 34 unique positive graph events reconcile in base units:
**903,794.346419582485370326** original withdrawals
+ **1,167.08760240114708029** prior funds at participating wallets
= **501,460.52** gross Binance receipts
+ **403,500.914021983632450616** at the six retained leaves. [F57]

The zero-event continuations through 17 November and common-block states substantiate that retained total. The Binance figure is cumulative historical receipt throughput; it is not Binance's balance at that block. Intermediate hops are counted once. There is no arithmetic residual in this captured graph, while purchaser entitlements, settlement purpose and authority remain unreconciled. [F55; F57]

### Where this public trail stops

On 18 November at 17:38:52 UTC, 8724 swapped ULX through PancakeSwap v2 and received 3,457.600228610921015515 BUSD from pair 65f2. Its later BUSD balance is 28,655.038143782914041893. The ULX acquisition source is untraced; these swap proceeds are not counted again in the original-raise total. The owner/bf7f/8724/2108 endpoint is block 23,191,705 at 19 November 2022 13:59:08 UTC. Cedfa/dc127 stop at the common 17 November block. No later history is claimed here. The first seven Binance payments and their original-source interval remain unchanged; the BUSD extension adds no centralized-exchange receipt. [F51-F52; F55; F58]


---

## 9.28 The USDT return reaches Kraken and KuCoin

**The previously unresolved 21,882.27-USDT branch reaches Kraken 7.** On 23 July 2024, 1991 paid 188b; 188b passed the same amount to 0d56; Kraken 7 then called transferFrom to collect the full amount. Both intermediaries opened and closed the reviewed USDT windows at zero. Canonical logs, successful raw receipts, calldata and historical balances agree. [F48; F56]

| Step on 23 July 2024 | USDT | UTC / elapsed |
| --- | --- | --- |
| 1991 > 188b | 21,882.27 | 14:42:35 |
| 188b > 0d56 | 21,882.27 | 14:49:47 / 7m 12s |
| 0d56 > Kraken 7 | 21,882.27 | 14:51:59 / 2m 12s |

Kraken 7: 0x89e51fa8ca5d66cd220baed62ed01e8951aa7c40
Intermediary: 0x0d560ac1b578ee5ac815a0e096cac37cb4c0eb5e
Collection: 0x2d7f8d2319465342ca9766215c00fbded8896cdabe7a1e620cd261009650e987

### The selected return now has a stronger source bound

Immediately before receiving **58,724.105382 USDT** from 183600 on 23 July, 1991 held 8,375.183313 USDT. It paid 21,882.27 to this Kraken branch and 4,000 to 2c94, then received 14,690.010811 and 50,000 from other sources. Its final 105,907.029506-USDT payment went through the already verified KuCoin deposit route and left zero. [F48; F56-F57]

| Exchange route | Gross USDT | Selected-return contribution |
| --- | --- | --- |
| New Kraken branch | 21,882.27 | 13,507.086687-21,882.27 |
| Prior KuCoin branch | 105,907.029506 | 32,841.835382-41,217.018695 |
| Combined routes | 127,789.299506 | 54,724.105382-58,724.105382 |

The combined interval follows because 1991 ends at zero and only 4,000 USDT leaves by the third branch. Independent chronological allocations attain both bounds. Individual minimums cannot be added: they share the same prior funds and return. The gross 127,789.299506 includes substantial other money; it is not all trading return. [F57]

### A former evidence condition is closed for this window

New successful historical calls confirm 1991's opening 8,375.183313 and closing zero. Complete incoming and outgoing canonical-USDT raw queries cover blocks 20,369,851-20,375,526 and match all six positive indexed events. Smaller contiguous outgoing queries replaced a preserved range-limit failure. The narrow return-window bound no longer relies solely on an indexed starting balance. This does not upgrade the separate initial IAG-USDC source histories. [F56-F57]

The selected source is the USDT payment returned by 183600. Its division between invested principal, trading gains and other funding is a separate question. This new route is also separate from the mixed 300,000-USDT Kraken sweep on 18 July in section 9.25. No customer identity, payment mandate or Laura's personal receipt follows. [F53; F56-F57]


---

## 9.29 The 21,664-USDC tail reaches a Binance deposit

**A further branch reaches an address labeled Binance Deposit.** After d541 paid 21,664 USDC to 0585 on 30 July 2024, a matching 21,664-USDC transfer went to 22c84, which sent a net 21,664 to 2fb794. Later that day, 2fb794 sent 66,600 USDC to the deposit address below. Historical prior funds and remaining balances define how much of the selected payment must be included. [F53; F56]

Binance deposit: 0x67124cb10bd4cd6de2946caa1a905c61f05c838e
This Ethereum USDC branch is separate from the November 2022 BSC BUSD routes.

| 30 July 2024 movement | USDC / UTC |
| --- | --- |
| d541 > 0585 | 21,664 / 06:47:35 |
| 0585 > 22c84 | 21,664 / 08:52:59 |
| 22c84 > 2fb794; return to 22c84 | 100 sent; 60 returned |
| 22c84 > 2fb794 again | 21,624 |
| 2fb794 > Binance deposit | 66,600 / 13:50:59 |

### A positive downstream bound, with a firm upstream limit

0585 began with **452.461220 USDC**. 22c84 began and ended at zero. 2fb794 began with **31,008.122752 USDC**, also received 14,897.345416 from another source, and ended with **969.468168 USDC**. The 60-USDC reverse transfer is included; amounts passed repeatedly between the same wallets are not counted as new funds. [F56]

The 66,600-USDC deposit includes between **20,242.070612 and 21,664 USDC** from d541's selected 30 July payment. The minimum allows all 452.461220 of 0585's prior funds into the route and all 969.468168 remaining at 2fb794 to be selected-source funds. Chronological feasible allocations, complete bounded token logs and historical states substantiate the interval. [F56]

**This does not force any of the earlier 24 July receipt at d541 into Binance.** d541 held 228,092.803239 USDC before that earlier 318,192.18-USDC receipt; its prior funds exceed the later 21,664 payment. The newly forced source is the 30 July payment at a downstream point, not uniquely IAG proceeds or the earlier trading-return branch. [F53; F56]

### What the service endpoint resolves

The label and successful transfer supply a specific deposit-account record lead. The receiving account, credit, purpose, later trade or withdrawal and human controller remain unidentified. The captured route ends at this deposit; an internal Binance credit or fiat cashout is not inferred. [F56]

Full addresses, exact hashes, block ranges, UTC timestamps, rejected zero/lookalike rows and preserved retrieval failures are in onchain_pass8/eth_tail/. The report uses historical cutoffs, not present balances. [F56]


---

## 9.30 Inspector handoff: findings and remaining records

**The public evidence is ready to support focused records work.** The original withdrawals, repeated wallet relationships and selected exchange routes have exact identifiers. Public activity still does not identify the human signer, beneficial customer or contractual authority. Further tracing can extend dated balances, but those separate questions require matching records. [F55-F58]

| Question | Evidence to start from | Record that would resolve it |
| --- | --- | --- |
| Who controlled the wallets? | 77bf original withdrawals; 6c2 treasury authority; 1991 repeated payments | Dated custody/delegation logs, payment instructions, approvals and control handovers. Link to each transaction time. |
| Which account received credit? | Binance, Kraken, KuCoin, MEXC and Revolut routes; exact chain/token/hash/time in evidence | Deposit or sweep mapping to account/subaccount, ledger credits, account mandates, trades and later withdrawals. |
| Were obligations settled? | 903,794.346419582485370326 original BUSD; separate IAG-USDC and ML ledgers | Purchase and project-settlement agreements, purchaser register, invoices, allocations, refunds and alternate settlements. |
| Did holders receive native ML? | Claim proofs, migration-contract mechanics, reserve snapshots | Complete Raise 1 allocation dataset, Raise 2 version mapping and Ethereum-event-to-native-payout reconciliation. |
| Which entity assumed the business? | Existing corporate map and two obtained Panama deeds | Share/beneficial-owner records, voting/proxy instruments and executed asset, customer-contract and liability-transfer agreements. |

### The November deadline remains a migration policy

Mintlayer's official page still sets **1 November 2026** as migration-tool closure, with requests processed every two weeks in the current period. The public form is retrievable; this alone proves no successful submission or mainnet payout. The separate distributor has no calendar-triggered transfer to Laura or an identified company. Its existing withdrawal authority and fixed treasury remain the relevant custody facts. [F06; F21-F24; F58]

### Corrections and external evidence dependencies

Obsolete withdrawal-gap wording on pages 16, 18 and 19 and four source notes is corrected. The recovered transactions remain the controlling evidence. The historical GamiFi deficit on page 12 references a separate study: if inspectors rely on that finding, its existing master and underlying evidence are companion materials. This bundle contains the dated extract and disclosed refresh, not that full earlier schedule audit. [F10; F58]

No sum across BUSD, USDC, USDT and ML is presented as a loss total. Exchange labels identify service leads; they do not establish misconduct, investor entitlement or personal receipt. Laura's published roles remain contextual evidence, not proof that she held these keys or received these funds. [F55-F58]

## Follow-up source register F01-F08

All live observations below were collected on 7 September 2026. Original S/D references remain on the preceding source pages. Source files and exact requests are indexed in the evidence bundle. Links identify records for review; they are not instructions to connect a wallet.

**F01 | Registry record**

[https://rdap.centralnic.com/xyz/domain/launchpool.xyz](https://rdap.centralnic.com/xyz/domain/launchpool.xyz)

CentralNic RDAP; 04:58:45 UTC. website_sources/rdap.txt and network_receipts.json.

**F02 | Two public DNS resolvers**

[https://dns.google/resolve?name=launchpool.xyz&type=A](https://dns.google/resolve?name=launchpool.xyz&type=A)

Google DNS and https://cloudflare-dns.com/dns-query; exact A/AAAA/app/www/NS/SOA requests and responses in website_sources/. Cloudflare checks at 05:00:55 UTC.

**F03 | Archived application shell**

[https://web.archive.org/web/20260128012904/https://app.launchpool.xyz/](https://web.archive.org/web/20260128012904/https://app.launchpool.xyz/)

Capture 28 January 2026, 01:29:04 UTC. app_cdx_recent.txt and archived_app_source_record.json; original body hash retained. Static shell only; backend not tested.

**F04 | Launchpool claim notices**

[https://t.me/s/launchpoolannouncements](https://t.me/s/launchpoolannouncements)

Official channel linked from t.me/launchpoolxyz. Posts 1691-1694; complete post datetimes not exposed. Earlier deadlines superseded by F08.

**F05 | Published final-claim files**

[https://mintlayerclaim.netlify.app/](https://mintlayerclaim.netlify.app/)

claims.json and mintlayer_final_distro_readable.json recovered from the live UI. 1,999 records; hashes and exact CSVs in claims/.

**F06 | Deployed distributor and on-chain state**

[https://etherscan.io/address/0xcc32853fb709666332cde0fc47f3f74119b970c4](https://etherscan.io/address/0xcc32853fb709666332cde0fc47f3f74119b970c4)

Verified source via eth.blockscout.com; raw Ethereum RPC reads at block 25,923,249, transaction history and token events in claims/. Block hash 0xcbe553133f79829c8da8a4519d3944aa36c482c42cecc74a1986c05b5a22f912.

**F07 | Independent claim reconciliation**

claims_peer/verify_claims.py; independent_validation.json and independent_reconciliation.json. Every allocation proof, bitmap flag, successful input and ML payment was checked against the preserved files. This is independent analysis of the same evidence, not an independent historical witness.

**F08 | Current ML migration policy**

[https://www.mintlayer.org/ml-coin](https://www.mintlayer.org/ml-coin)

Current policy states 1 November 2026 closure and processing every two weeks from 1 August. Separate UI: https://token.mintlayer.org/migration. No submission or mainnet delivery test. migration_support_sources/ preserves policy excerpts and retrieval metadata.


---

## Follow-up source register F09-F16

**F09 | Fresh GMI state and failed history queries**

[https://bsc-dataseed.bnbchain.org](https://bsc-dataseed.bnbchain.org)

gmi_sources/state_snapshot_batch.json; block 120,435,314 at 05:04:55 UTC; hash 0xf802d033535ff7f508288fc1546fa3d4e9045029967eef52c9c88860dee2605b. Exact selectors, responses and access limits preserved.

**F10 | Prior GamiFi original-book study**

Research_Paper_GamiFi_Master_Investigation_2026-09-06.md, section 7, version 3; its 6 September 04:08:52 UTC observation at block 120,235,949 is carried forward. A dated extract and metadata are in prior_gmi_basis.json. Earlier research is not new corroboration.

**F11 | 2024 project status categories**

[https://t.me/s/launchpoolannouncements/1500](https://t.me/s/launchpoolannouncements/1500)

Post 1506 in this context; linked X status 1762833659093041216. GamiFi labeled Completed Vesting. Labels are distinguished from proof of delivery.

**F12 | Launchpool public CEO representation**

[https://launchpool.medium.com/launchpool-spaces-recap-decentric-2b5923c3367b](https://launchpool.medium.com/launchpool-spaces-recap-decentric-2b5923c3367b)

Publisher date 26 July 2024; discussion date 19 July. Identifies Roxana Nasoi as CEO and Decentric as sister launchpad. No shareholder inference.

**F13 | Labs public program and leadership**

[https://launchpoollabs.xyz/](https://launchpoollabs.xyz/)

Displayed 2024 program identifies Roxana Nasoi as CEO. Counterparty program corroboration: https://xdc.org/articles/xdc-weekly-jul-7 (15 July 2024). Exact date of any later staff-field change unknown.

**F14 | Gate migration announcement**

[https://www.gate.com/announcements/article/36255/gate.io-supports-launchpool-lpool-token-migration](https://www.gate.com/announcements/article/36255/gate.io-supports-launchpool-lpool-token-migration)

28 April 2024; ratio 1:1; service pause from 29 April 06:00 UTC; new Arbitrum address. Original Launchpool X references retained on source page.

**F15 | July migration reopening**

[https://t.me/s/launchpoolannouncements/1606](https://t.me/s/launchpoolannouncements/1606)

Official context includes messages 1606, 1609 and 1610. Text specifies the 26 July 2024 burn/KYC deadline. Full primary message posting dates were not independently recovered.

**F16 | Unizen issuer partnership announcement**

[https://www.globenewswire.com/news-release/2023/05/03/2660427/0/en/launchpool-and-unizen-announce-a-strategic-partnership.html](https://www.globenewswire.com/news-release/2023/05/03/2660427/0/en/launchpool-and-unizen-announce-a-strategic-partnership.html)

3 May 2023, issuer-supplied statement. Compare with preserved migration FAQ S22-S23; different partnership/reward scope may explain the later exclusion.


---

## Follow-up source register F17-F26

**F17 | Laura role records**

[https://www.nativzgaming.com/p/newsletter-09-07-22](https://www.nativzgaming.com/p/newsletter-09-07-22)

9 July 2022 profile dates COO appointment to May 2021; October 2021 interview at S15. laura_thread/laura_sources/ preserves source records and 28-query search scope; COO end remains unresolved.

**F18 | Original Mintlayer Raise 1 offer**

[https://web.archive.org/web/20211122150545/https://app.launchpool.xyz/projects/mintlayer/](https://web.archive.org/web/20211122150545/https://app.launchpool.xyz/projects/mintlayer/)

Opening and 1 December 2021 captures recovered. Funding/price/vesting fields and hashes: laura_thread/raise_chronology/. Targets are not payment receipts.

**F19 | Original Mintlayer Raise 2 snapshots**

[https://web.archive.org/web/20220316182610/https://app.launchpool.xyz/projects/mintlayer-raise-2/](https://web.archive.org/web/20220316182610/https://app.launchpool.xyz/projects/mintlayer-raise-2/)

Compare capture 20230330212228 of the same URL. Bounded fields preserve target, delivery-network and preliminary-summary changes; no payment recipient identified by these snapshots; F46 later supplies all six actual withdrawals.

**F20 | Named contacts and launch-week terms**

[https://launchpool.medium.com/launchpool-ama-recap-mintlayer-7dbef79f623d](https://launchpool.medium.com/launchpool-ama-recap-mintlayer-7dbef79f623d)

Published 23 March 2022; event 21 March. Detailed short/long tranches extend to 34 months. Named contacts are not wallet signers.

**F21 | Treasury and upstream transfers**

[https://etherscan.io/address/0x6c2b3a90acb72ef896325e19af9098d157f929c4](https://etherscan.io/address/0x6c2b3a90acb72ef896325e19af9098d157f929c4)

laura_thread/treasury/: exact event CSV, source histories and request receipts. MEXC 16 label preserved as a short source record; account customer remains unidentified.

**F22 | Earlier related distributor**

[https://etherscan.io/address/0xaf6a981053942dd8cb1ee99c37f99227ed7ca34b](https://etherscan.io/address/0xaf6a981053942dd8cb1ee99c37f99227ed7ca34b)

Verified source and constructor inputs compared with F06. Same deployer/token/root; later adds withdrawal power. Initial history gap is updated by F30: zero balance/claim bits and explicit empty transfer history.

**F23 | Independent control comparison**

laura_thread/control_peer_checks.json and control_peer_review.md. Source and constructor comparisons; no independent compiler rebuild. A later earlier-contract balance/bitmap census appears at F30.

**F24 | Separate migration mechanism**

[https://token.mintlayer.org/migration](https://token.mintlayer.org/migration)

Portal application identifies TokenBurner at 0xe03aed8dfa6200292a2585918f656e2345ea283f. Verified source, application hash/metadata and interpretation: laura_thread/migration_mechanics/.

**F25 | Initial Ethereum delivery announcement**

[https://medium.com/@mintlayer/mintlayer-token-launch-announcement-c5bdf062873c](https://medium.com/@mintlayer/mintlayer-token-launch-announcement-c5bdf062873c)

13 December 2022 original; prospective 21 March 2023 TGE. Later website copy has an inconsistent publication date; original Medium date used.

**F26 | Mintlayer and Launchpool Labs**

[https://www.mintlayer.com/blog/launchpool-partnership-1a7d0/](https://www.mintlayer.com/blog/launchpool-partnership-1a7d0/)

Displayed 2 March 2023; Roxana Nasoi identified as Labs managing director. Public role and partnership statement, not a corporate ownership or treasury record.


---

## Follow-up source register F27-F31

**F27 | Upstream ML event reconstruction**

[https://etherscan.io/address/0x77bfe8d704b1948374bf8dab8328a810b2836e66](https://etherscan.io/address/0x77bfe8d704b1948374bf8dab8328a810b2836e66)

onchain_pass2/ml_origin/: 131 token rows recovered, 90 ML events, exact running ledger and independent parser/arithmetic check. May 29 caller/transfer and source-verification limits preserved; F35 adds selected runtime and earlier-payment checks. Gross turnover is not money raised.

**F28 | Treasury-owned Safe and pinned state**

[https://safe-transaction-mainnet.safe.global/api/v1/safes/0x03FAFab75267CdF75c64a1c86188E612205B455E/creation/](https://safe-transaction-mainnet.safe.global/api/v1/safes/0x03FAFab75267CdF75c64a1c86188E612205B455E/creation/)

onchain_pass2/gas_control/: official creation/history records, initializer decoding and root RPC requests/results. Current sole owner, threshold 1, nonce 0 and 10 ML at block 25,923,475. Archive-code query denied; no bypass.

**F29 | Deployer routes and exchange labels**

[https://etherscan.io/tx/0x9f2022618d5326b97338f704ebf394485a48f083ff92942fe7c55951bffb4420](https://etherscan.io/tx/0x9f2022618d5326b97338f704ebf394485a48f083ff92942fe7c55951bffb4420)

onchain_pass2/deployer/: four transaction/receipt pairs, exact CSV and independent review. Etherscan address labels identify Coinbase 10/44, not customers; Coinbase 10 pairing also in docs.etherscan.io/api-reference/endpoint/getaddresstag.

**F30 | Earlier/final distributor state refresh**

[https://eth.blockscout.com/api/v2/addresses/0xaf6a981053942dd8cb1ee99c37f99227ed7ca34b/token-transfers](https://eth.blockscout.com/api/v2/addresses/0xaf6a981053942dd8cb1ee99c37f99227ed7ca34b/token-transfers)

onchain_pass2/distributors/: successful pinned PublicNode reads, explicit empty old transfer history and creation-only normal history. Block hash 0x649e3846d637a57dfa2efdc0ab4173b42c3d339b017aab2ab979361ef60c5622. Optional dRPC state crosscheck failed HTTP 500.

**F31 | Fundraising-owner USDC receipts**

[https://etherscan.io/address/0x689cf22e945466340f2e0bfd80ac8ee398ab9ecf#code](https://etherscan.io/address/0x689cf22e945466340f2e0bfd80ac8ee398ab9ecf#code)

onchain_pass2/cash_custody/: two 2 July 2024 successful claims, verified source and exact received USDC. Current poolInfo reward-token fields identify IAG, corroborated by blog.iagon.com/iagon-smart-contract-audited-by-gordian-agency/. Source has no reward-token setter; these are not Mintlayer BUSD receipts.


---

## Follow-up source register F32-F38

**F32 | Recovered public project configuration**

[https://web.archive.org/web/20211122145742id_/https://app.launchpool.xyz/_nuxt/41d2656.js](https://web.archive.org/web/20211122145742id_/https://app.launchpool.xyz/_nuxt/41d2656.js)

onchain_pass3/archived_bsc_contracts/: archived app metadata, public project records read 7 September 2026, exact contract/pool and tranche mappings. Records last updated in 2024/2025; stale Raise 2 pricing excluded. Runtime comparison confirms Ethereum artifact match and BSC mismatch.

**F33 | Original BSC pool state**

[https://bsc-dataseed.bnbchain.org](https://bsc-dataseed.bnbchain.org)

onchain_pass3/bsc_cash/ and bsc_validation/: exact pinned requests/responses, six amounts/flags, owner and token metadata; independent ABI/arithmetic checks. Block 120,444,465 at 06:13:37 UTC. Initial historical-withdrawal retrieval failed; F46 later recovered all six receipts. Full-source acquisition remains unresolved; failures retained.

**F34 | Original BUSD purchase receipt**

[https://bscscan.com/tx/0x56ba03b73564c3c110319c4c056230441b58c89a8cdaff071cfe71afc3912da9](https://bscscan.com/tx/0x56ba03b73564c3c110319c4c056230441b58c89a8cdaff071cfe71afc3912da9)

onchain_pass3/bsc_validation/: successful raw receipt at block 13,056,994, 29 November 2021; decoded fundPledge(21), BUSD transfer and PledgeFunded event. Exact contribution 59.820643332035352 BUSD.

**F35 | Old ML claims and selected runtime checks**

[https://etherscan.io/address/0x4d7b84910d042f5431b156397bff0db5ebb4f0a9](https://etherscan.io/address/0x4d7b84910d042f5431b156397bff0db5ebb4f0a9)

onchain_pass3/old_ml_contract/: two complete explorer histories, 237 valid proofs, 236 payments/bitmap matches, recipient overlap, owner/time checks and independent review. Runtime/state pin 25,923,590 at 06:09:11 UTC. Full source remains unverified.

**F36 | ML vesting origin and wallet crosslinks**

[https://etherscan.io/tx/0x06293db7ae63be6e47d9159c875d0ba0bd7a4b0c978f4770277c12699b0eb22e](https://etherscan.io/tx/0x06293db7ae63be6e47d9159c875d0ba0bd7a4b0c978f4770277c12699b0eb22e)

onchain_pass3/ml_upstream/: four ML ledgers, original/later roots and seven verified proof samples, pinned balances, exact 2021 USDC crosslinks. reproduce_verified.py runs offline without full webpage bodies. Full later tree and root registrar remain unrecovered.

**F37 | Dated ownership and complete fundraising census**

[https://etherscan.io/tx/0x520df656ffe5c57278aafd86977b8fb7e43c58d638c3f2f5dfc756cc77114ecf](https://etherscan.io/tx/0x520df656ffe5c57278aafd86977b8fb7e43c58d638c3f2f5dfc756cc77114ecf)

onchain_pass3/fundraising_control/: deployment/handover, 21 pools, 17 matched owner receipts and eight later settlement transfers. State pin 25,923,587 at 06:08:35 UTC. All pools use USDC; these are not the Mintlayer BUSD raises.

**F38 | USDC onward routes and exchange-label records**

[https://etherscan.io/address/0x4d0d32b42bb4d6a3e3ed503c5faaf49b6b64a7ee](https://etherscan.io/address/0x4d0d32b42bb4d6a3e3ed503c5faaf49b6b64a7ee)

onchain_pass3/usdc_onward/: exact event/calldata records, success checks, MEXC RPC receipts, KuCoin Deposit/20/22 labels and independent review. KuCoin route uses explorer transaction evidence; its raw RPC receipts were unavailable. Initial archive state was unavailable; F48/F50/F54 supply event-derived opening balances and conditional source bounds. Customer identity is not established.


---

## Follow-up source register F39-F45

**F39 | 24-tranche census and the additional Raise 1 reserve**

[https://etherscan.io/address/0x9298136ec995aefb1e99fd4087080d3df328162f](https://etherscan.io/address/0x9298136ec995aefb1e99fd4087080d3df328162f)

onchain_pass4/tranche_census/ and peer_review/: common block 25,923,764 at 06:43:59 UTC; complete 1,001-event token ledger, partial normal-call census, exact runtime comparison and owner simulations. Final Raise 2 root/bitmap/backing rechecked at the same block. Full Raise 1 liability/proof file unrecovered.

**F40 | D975 selected withdrawal path**

[https://bsc-dataseed.bnbchain.org](https://bsc-dataseed.bnbchain.org)

onchain_pass4/bsc_runtime/ and peer_review/: actual bytecode, slot mapping, live read-only simulations and independent offline interpreter. Current owner receives intended transfer; historical owner queries failed. Returned ERC-20 bool is discarded; this is not evidence of an actual false-return BUSD transfer.

**F41 | Actual BSC settlements and ChangeNOW-associated destination**

[https://www.oklink.com/zh-hans/bsc/address/0xa96be652a08d9905f15b7fbe2255708709becd09](https://www.oklink.com/zh-hans/bsc/address/0xa96be652a08d9905f15b7fbe2255708709becd09)

onchain_pass4/bsc_settlements/ and bsc_project_mapping/: 18 exact withdrawal receipts, Circularr split/convergence and separate Hinata onward transfer. D975/BSC project mappings verified. OKLink supplies a BSC-specific ChangeNOW label; Blockscan and Etherscan corroborate service attribution. Customer/order/output unknown.

**F42 | Shared counterparty ML and USDC exchange routes**

[https://etherscan.io/address/0x183600361dc42c6f022fd219c3a9dabbf08c9ce4](https://etherscan.io/address/0x183600361dc42c6f022fd219c3a9dabbf08c9ce4)

onchain_pass4/shared_counterparty/: exact-token histories, complete 980b intermediary ledger, Gate/MEXC/KuCoin label records and representative raw RPC receipts. Token custody, historical flow arithmetic and service labels are distinguished from customer identity, investor allocation and executed trade evidence.

**F43 | Circle messages, Base receipts and BAMBOO inventory**

[https://developers.circle.com/cctp/v1/evm-smart-contracts](https://developers.circle.com/cctp/v1/evm-smart-contracts)

onchain_pass4/shared_counterparty/base_continuation/: official Circle message/attestation records, matching mint/burn inputs, 22 successful swap receipts with 66 matched transfer logs, complete 505-row token census and historical inventory reads. BAMBOO identified by its exact contract and token getters. Trading cash difference excludes native gas and does not identify a human or investor entitlement.

**F44 | Second Base return, Ethereum swap and exact USDT payments**

[https://etherscan.io/tx/0x7ae7223ebfbeb9c0a06f34342c1e15f1a068c7feae454548d170d2f8ac16fd43](https://etherscan.io/tx/0x7ae7223ebfbeb9c0a06f34342c1e15f1a068c7feae454548d170d2f8ac16fd43)

onchain_pass5/base_final_returns/, root_reconciliation/ and peer_review/: five new successful RPC receipts, Circle nonce 240419, 34-event July USDC reconciliation, post-burn Base state and 699-event Ethereum USDT ledger. Historical USDT state calls failed; event balances are distinguished. Exact swap and payment amounts are verified; payment purpose and human ownership remain unknown.

**F45 | Raise 1 wallet-specific proof files and bounded retrieval gap**

[https://claims.launchpool.xyz/mintlayer1-11/](https://claims.launchpool.xyz/mintlayer1-11/)

onchain_pass5/raise1_entitlements/: recovered app URL construction, exact archive-prefix result and two current public Merkle repository tree listings. No full Mintlayer allocation ledger recovered. Empty archive results are limited to that query; failed requests and an input error are disclosed separately.


---

## Follow-up source register F46-F50

**F46 | All six original Mintlayer BUSD withdrawal receipts**

[https://bscscan.com/tx/0x3d0006d4dc6efd3afa6e0ef00c6fc922e923c9554948b3603cdb68b67693e530](https://bscscan.com/tx/0x3d0006d4dc6efd3afa6e0ef00c6fc922e923c9554948b3603cdb68b67693e530)

onchain_pass6/original_busd/ and peer_review/: six official BNB receipts/block bodies, exact input/event/Transfer agreement and all counter matches. Archive-state discovery and its bounded incomplete SQD alternative are preserved; independent original-receipt review passed 935 checks.

**F47 | Original BUSD: immediate outflows and historical balances**

[https://bscscan.com/address/0x77bfe8d704b1948374bf8dab8328a810b2836e66](https://bscscan.com/address/0x77bfe8d704b1948374bf8dab8328a810b2836e66)

onchain_pass6/original_busd_onward/: exact 24-hour windows, both-direction logs, official BNB receipts and historical opening/closing state. Eleven owner payments total 896,370 BUSD; 267,000 BUSD reaches the same 1991 address seen in later Ethereum flows. A 54,370-BUSD branch reaches Binance 51 via 14c840. All 14 historical balance equations reconcile; independent onward review passed 1,002 checks. Service label: https://blockscan.com/Address/0x8894e0a0c962cb723c1976a4421c95949be2d4e3 . The original window gap is closed by F52. Prior-fund and human-attribution limits remain explicit.

**F48 | Returned funds and the second KuCoin deposit route**

[https://etherscan.io/address/0x327ae1e62fdea32763d6e5de1b08ebe84edff303](https://etherscan.io/address/0x327ae1e62fdea32763d6e5de1b08ebe84edff303)

onchain_pass6/returned_funds/ and peer_review/: 370 USDC and 1,577 USDT events; 15 selected successful RPC receipts; second KuCoin deposit/sweep and other bounded onward routes. Historical state calls failed; event balances, mixed funding and rejected lookalikes are explicitly documented.

**F49 | Revolut endpoint and recurring f695 payments**

[https://etherscan.io/address/0xf7c8da79da4cb294c4f55dfebb1b404e3e38d921](https://etherscan.io/address/0xf7c8da79da4cb294c4f55dfebb1b404e3e38d921)

onchain_pass6/f695_recipient/ and peer_review/: 65 USDT events, six recurring source cycles, direct Ethereum explorer labels and current state. 33 selected edges use 27 RPC receipts plus six indexed status/raw-log confirmations. Ancillary ETH/USDC activity has separate evidence scope; customer identity remains unknown.

**F50 | Conditional conservation bound for the Base funding**

[https://eth.blockscout.com/address/0x1991e27e2908847c0274a662eb6675002e8386d0](https://eth.blockscout.com/address/0x1991e27e2908847c0274a662eb6675002e8386d0)

onchain_pass6/source_bounds/ and peer_review/: exact-token histories, zero starting event balances, 20-USDC outside input and 27,080-27,100 source interval. Independent review proves both endpoints feasible. Event-history completeness is a stated condition; no legal tracing rule, investor entitlement or human identity is inferred.


---

## Follow-up source register F51-F54

**F51 | Original BUSD: three more Binance routes and later convergence**

[https://blockscan.com/Address/0x8894e0a0c962cb723c1976a4421c95949be2d4e3](https://blockscan.com/Address/0x8894e0a0c962cb723c1976a4421c95949be2d4e3)

onchain_pass7/busd_branches/ and peer_review/: canonical logs, official BNB receipts/calldata, historical balances, exact delays and source bounds. Three new sweeps add 222,090.52 BUSD gross, including 90.52 previously held. Later cedfa/57e898 convergence is separately reconciled; no customer identity inferred.

**F52 | Owner gap closure and bounded retained-funds continuation**

[https://bscscan.com/address/0x77bfe8d704b1948374bf8dab8328a810b2836e66](https://bscscan.com/address/0x77bfe8d704b1948374bf8dab8328a810b2836e66)

onchain_pass7/owner_and_retained/ and peer_review/: exact zero-event gap, state-backed continuous original withdrawal accounting, first-day checks and bounded later custody/outflow records. Seven Binance payments total 501,460.52 BUSD; the joint original-source interval accounts for all prior balances. Retrieval limits and historical cutoffs are preserved; later transfers are not new fundraising.

**F53 | Kraken collection mechanics and mixed-funds limits**

[https://etherscan.io/address/0xae2d4617c862309a3d75a0ffb358c7a5009c673f](https://etherscan.io/address/0xae2d4617c862309a3d75a0ffb358c7a5009c673f)

onchain_pass7/returned_branches/ and peer_review/: successful raw receipts and transferFrom calldata, exact USDC/USDT cycles, primary explorer labels, independent historical balances and bounded d541 outgoing continuation. Prior funds prevent exclusive allocation of the selected returns to Kraken.

**F54 | Initial IAG disposition and shared-source bounds**

[https://etherscan.io/tx/0xdb32b44e9cb8048521ee3d350c5fdcc3175db307bf8779887f9fa0a0b6c9ecc4](https://etherscan.io/tx/0xdb32b44e9cb8048521ee3d350c5fdcc3175db307bf8779887f9fa0a0b6c9ecc4)

onchain_pass7/iag_allocation/, historical_state/, entity_checks/ and peer_review/: seven-part exact USDC partition; two newly successful outside-input receipts; shared 20-USDC budget and feasible joint intervals. Failed source-wallet state probe preserved. Public searches did not supply a human/controller attribution.


---

## Follow-up source register F55-F58

**F55 | BUSD tail closure and a common historical balance cut**

[https://bscscan.com/address/0x77bfe8d704b1948374bf8dab8328a810b2836e66](https://bscscan.com/address/0x77bfe8d704b1948374bf8dab8328a810b2836e66)

onchain_pass8/busd_tail/: complete bounded canonical logs for six wallets, pinned boundary headers and historical balances. Common-block custody is separately distinguished from each longer/shorter scan cutoff. No outgoing transfer is found; one later ULX-to-BUSD swap by 8724 is separately verified. Empty windows use actual successful responses; prior funds remain explicit.

**F56 | Kraken USDT collection and a separate Binance USDC deposit**

[https://etherscan.io/address/0x89e51fa8ca5d66cd220baed62ed01e8951aa7c40](https://etherscan.io/address/0x89e51fa8ca5d66cd220baed62ed01e8951aa7c40)

onchain_pass8/eth_tail/: thirteen successful selected receipt/input pairs, twelve historical balance calls, complete both-direction token windows and preserved limits. Kraken collects 21,882.27 USDT from 0d56. Separate Binance deposit 67124 receives 66,600 USDC with bounded source contribution from the selected 30 July payment; no forced attribution to the earlier d541 receipt. Direct primary explorer labels and exact identifiers retained.

**F57 | Joint return-source bounds and exact original BUSD flow accounting**

onchain_pass8/source_accounting/ and peer_review/: independently feasible chronological bounds for the selected USDT return, new raw/state corroboration for its source window, deduplicated original BUSD conservation and a focused nine-event service-record index. No token totals are combined, individual minima are not added and arithmetic conservation is not proof of authorized settlement or human ownership.

**F58 | Inspector readiness audit and current migration-policy recheck**

[https://www.mintlayer.org/ml-coin](https://www.mintlayer.org/ml-coin)

onchain_pass8/handoff_audit/ and public_recheck/: source-grounded content audit, corrected obsolete gaps, current official November 1, 2026 policy and concrete unresolved records. Prior GamiFi schedule study is an external evidence dependency. Public portal access is not native delivery. No outside records request or communication was made.

Preservation: factual records, exact ledgers, verification code, source metadata and SHA-256 hashes are bundled. Full third-party webpages/application bundles are represented by metadata or bounded extracts. Wallet control is not a personal identity.
