# Research Paper - GamiFi project withdrawals

Public crypto research edition. The following material preserves historical analysis, source identifiers, transaction amounts and stated qualifications. Observations retain their original dates, principally 5-7 September 2026. Preparing this edition did not repeat the blockchain, corporate-registry or legal research.

Correction precedence: the 7 September 2026 ShibaFriend claims review reports repayment of the principal of all 23 non-dust funding addresses, with only 168 base units of dust unmatched. It also reports equal project matches for all 194 identified paid Mystery Box mints. Those later findings supersede earlier uncertainty about those specific questions. See Research_Paper_ShibaFriend_Claims_Review.pdf.

The PDF is authoritative for tables, figures and column alignment. The text below is a searchable extraction of the public edition, with source-page labels retained.

---

RESEARCH PAPER | GAMIFI PROJECT WITHDRAWALS

Contents and document control

                                                     | Consolidated review | 7 September 2026

This report integrates the complete FOMO refund match, GAMI allocations and backing, pooled-wallet history,
original project4 funding route and the distinct 2025 Polygon event. It separates token movement, customer
settlement and human authorization.


What the seven withdrawals represent                                                           3

Original FOMO: full principal refunds                                                             3

GAMI: buyer allocations and remaining backing verified                                              4

Time Raiders: BSC cash and Polygon tokens                                                       4

Pooled wallet 35b1: cash accounting and the August sweep                                           6

Project 4: funding circuit and receiver reassignment                                                 7

Control, attribution and remaining records                                                        7

Evidence coverage and detailed schedules                                                        8

Exact withdrawal ledger                                                                       8

 Full address register                                                                          9

Public sources and decisive transactions                                                         10

Additional primary identifiers for printed review                                                   12





Historical analysis | Source page 2 | Public crypto edition

---

RESEARCH PAPER | GAMIFI PROJECT WITHDRAWALS



Consolidated findings through 7 September 2026. Times are UTC; BSC means BNB Smart Chain, chain ID 56.
GAMI, GMI and Polygon XPND are distinct tokens and must not be combined.

What the seven withdrawals represent

The 63,001.817377359365034843 BUSD subtotal is not a proven theft or unpaid-loss figure.
Original FOMO principal was fully refunded; every original GAMI funding address has its exact
recorded token allocation, with remaining allocations fully backed. Other settlement and
custody questions remain specific and unresolved.

  Campaign / project               BUSD, rounded                  Established outcome


  Original FOMO /8                 3775.23                             Full principal returned to all 27 original funding
                                                                   addresses.


  GAMI /6                         28421.14                             All 127 original funding addresses match funded vesting
                                                                            allocations; 30 additional allocations need entitlement
                                                                        records. Cash entered pooled wallet 35b1.


  Time Raiders /7                  23722.72                  An exact matching BSC BUSD balance was located at
                                                                   the original recipient. Polygon token history is assessed
                                                                     separately below.


  Shibafriend /9                    4720.23                     Cash entered 35b1; participant elections and fulfilment
                                                              remain unresolved. Two SHF token versions now have
                                                                          further distribution leads.


  Unidentified /1,3,4                2362.50                      362.50 paid to owner/caller 8fea; project 4's 2000
                                                                         follows a documented operational funding circuit and
                                                                          recipient change.

  Total                               63001.82                     Seven campaign withdrawals, 10 March-22 June
                                                                       2022; separate from November's 44 million GMI
                                                                       removal.

Original FOMO: full principal refunds

The original delay notice promised refunds; its publication metadata is 23 May 2022 03:21:19.809 and its
Wayback capture 13:00:44. Official post 555 repeated the promise at 14:24:52. Actual transfers establish
fulfilment for this cohort. [P01-P02; E03]

  23 May 2022 UTC                  Movement                                  Exact BUSD


  11:50:16                          Project→56aa                          3775.228767123287671432


  11:56:31                          56aa→administrator 3e0f                 3775.228767123287671432


  15:23:53                         Batch contract pays 2 original funders      23


  15:37:05                    Same contract pays 25 original funders     3752.228767123287671432


 All 34 contributions from 27 addresses match the 27 payouts address by address and to the smallest token
unit. No contributor or amount is unmatched. The intermediary 4867 is a batch contract, not the final
beneficiary. The complete configured funding window was recovered; all 34 funding receipts and both payout
receipts were independently checked. Refunds finished 3 hours 46 minutes 49 seconds after withdrawal. The
 full comparison is in fomo_funding_payout_reconciliation.csv.

This resolves original contract project 8 principal. It does not resolve the later version 2 FOMO relaunch,
staking, NFT purchases or separate losses.





Historical analysis | Source page 3 | Public crypto edition

---

RESEARCH PAPER | GAMIFI PROJECT WITHDRAWALS

GAMI: buyer allocations and remaining backing verified

The complete funding census recovered 154 events from 127 addresses, totalling
28,421.141280969119319259 BUSD. Each event also records its token allocation: their sum is
284,211.41280969119319259 GAMI. Every address and aggregate allocation matches the March 28
vesting setup exactly. This uses actual event allocations rather than assuming that the advertised $0.10
price proves accepted legal terms. All 154 funding receipts passed independent BUSD-transfer checks. [E08;
P06-P07]

On 28 March at 10:07:05, 56aa sent 555,555 GAMI to 3e0f. At 11:38:29, 3e0f transferred all 555,555 into
published distribution endpoint 0xf1adf471918b65006bf5d8505f6df976d9873d8b, creating 157 allocations: 10%
 initial, zero cliff and 270-day linear vesting, maturing 23 December 2022. The second transaction is
4a8ebee7. Its historical implementation independently recompiles to the exact 4,895-byte deployed runtime.
[P13]

At block 120,402,387, 7 September 2026 00:57:54 UTC:

  Allocation group         Addresses            Allocated GAMI           Recorded claimed         Remaining GAMI
                                                           GAMI


  Original funders        127               284211.412809691193   173544.016373193397   110667.396436497796
                                       19259                 146791                045799


  Additional addresses    30                271343.587190308806   91221.9778048066579   180121.609385502148
                                       80741                 93183                 814227

The actual contract balance, 290,789.005821999944860026 GAMI, exactly covers both groups'
remaining amounts. All original allocation amounts remain unchanged, all schedules are mature and the
token is not paused. Among original funders, 53 have fully claimed, 62 partially claimed and 12 have no
recorded claim. An atomic snapshot was independently reproduced through another provider. These are
claim counters and funded allocations, not a complete individual-claim/onward-wallet census.

The 30 additional addresses are absent from the complete ID 6 funding census. Their near-equal allocations
consume the remainder of the 555,555-GAMI deposit without reducing the 127 funders' entitlements. All 30
have partially claimed. Their consideration, entitlement and purpose remain unidentified; reviewed
publications do not explain this specific allocation. This is a records question, not proof of theft. See the
157-row gami_buyer_delivery_reconciliation.csv.

Time Raiders: BSC cash and Polygon tokens

The 18 March 2022 withdrawal paid 23,722.715761539594859905 BUSD to d2b8, whose preceding BUSD
balance was zero. At BSC block 120,394,077, 6 September 2026 23:55:32, its balance equalled that payment
exactly; three providers agreed. Block hash:
0x779aaa476a63ca5f06ca65989f33617ab4851f24970f9114a9182c6cbba8b809. [E04]

 Its two ordinary signed transactions were a 286,013.071750000025796608-GMI transfer on 24 January 2022
and a 0.03854508-BNB transfer to f4f8 on 4 November. Neither transferred or approved BUSD. This
establishes a dated asset balance, not continuous non-movement, human ownership, key access or
commercial entitlement.

First-party records specify BSC funding and Polygon delivery, initially scheduled for 18 March 2022 12:30
with later claims. [P03-P05]

Time Raiders: delivered tokens and a separate 2025 withdrawal

The original BSC offering and the later Polygon event must be assessed separately. A complete six-query
funding census identifies 111 contributions from 80 addresses, totaling
23,722.715761539594859905 BUSD. Every address matches a Polygon allocation at the contract's 0.022
BUSD/XPND rate, with integer rounding applied to each contribution. All 80 received actual initial XPND
transfers on 18 March 2022.




Historical analysis | Source page 4 | Public crypto edition

---

RESEARCH PAPER | GAMIFI PROJECT WITHDRAWALS


The published Polygon vesting contract held 149 allocation records. Initial distributions plus 437
successful later claims match every address's historical claimed counter exactly; three other indexed
claim calls reverted. Immediately before the 2025 upgrade, 107 addresses still had tokens outstanding,
including 38 of the original 80 BSC funding addresses. The other 42 original funding addresses had
received their full allocations.

  Group                          Allocated XPND                 Actually delivered XPND         Outstanding before
                                                                                        upgrade


  Original 80 BSC funding       1,078,305.26188816340272   634,523.4156916794923346   443,781.8461964839103882
  addresses                 2904                     46                        58


  Other 69 allocation           2,330,785.73811183659727   1,261,989.920557900869328   1,068,795.817553935727948
  addresses                 7096                     958                       138


   All 149 records               3,409,091                  1,896,513.336249580361663   1,512,577.663750419638336
                                                    604                       396

These amounts were mature under the original contract's rules: the schedule ended 14 September 2022
at 12:37:03 UTC. At Polygon block 78,964,530, 13 November 2025 11:39:06 UTC, the total outstanding
amount exactly matched the contract's XPND balance. The original implementation was independently
recompiled to its complete 4,960-byte deployed runtime. The per-address ledgers and receipt
reconciliation are preserved in the timeraiders_delivery evidence folder.

On 13 November 2025, the following sequence removed and sold that entire
balance.

  UTC                            Action                                                Primary transaction


  11:37:26                  A transaction sent by 4d96 to 3e0f replaces 3e0f's      Delegation and ownership
                                    existing code delegation and transfers ProxyAdmin
                               ownership from 3e0f to 4d96.


  11:39:08                   4d96 uses its new upgrade authority to replace the     Implementation upgrade
                                  vesting implementation.

  11:40:16                   4d96 withdraws 1,512,577.663750419638336396         Token withdrawal
                          XPND to itself. Contract balance becomes zero.


  11:46:10                   4d96 sends the full amount through a 1inch swap     Swap and native payout
                            and receives 325.142524926446493136 native
                          POL gross.


The recipient held zero XPND before the withdrawal, the exact withdrawn amount before the swap, and zero
afterward. The final POL payout is established by native-system transfer logs and a balance reconciliation. Its
balance rose 325.048546292010275756 POL; adding the swap's 0.09397863443621738 POL gas fee
reproduces the gross payout exactly. Earlier transaction fees are separate. Intermediate USDC, WBTC and
wrapped POL are steps in that one route, not additional proceeds. The separate
3,781.44415937604909584 XPND split within the route has not been assigned a contractual purpose.
Neither the original offering price nor these intermediate amounts establish customer damages.

Control explains how this was possible. Ordinary vesting ownership changed from 3e0f to f27f on 29
September 2022, but the separate ProxyAdmin upgrade authority remained with 3e0f at that date and
immediately before the November 2025 change. Transferring ordinary ownership did not itself transfer
upgrade control. A post-upgrade owner() call reverting does not prove earlier allocation storage was erased.

The 2025 transaction contains an EIP-7702 authorization. Independent signature recovery by two
methods identifies 3e0f as its cryptographic authority. The signed tuple authorizes a chain, code target and
nonce; it does not itself sign a commercial mandate or the explicit ownership-transfer instruction. The outer
transaction sender was 4d96. The evidence proves address-level delegation, not who used the key, what
they understood, whether access was compromised, or whether the transaction had legitimate business
approval. It replaced an existing delegation rather than creating the address's first delegation.



Historical analysis | Source page 5 | Public crypto edition

---

RESEARCH PAPER | GAMIFI PROJECT WITHDRAWALS



  Polygon role                                                  Full address


 XPND token                                           0x03f61137bfb86be07394f0fd07a33984020f96d8


  Vesting proxy                                         0xcfb37488ee5ebbadf9b879c05d318beb7b85f6a5


  ProxyAdmin                                           0x7ece517ee810f95f540c0ebdbdb09c4ae3d64720


  Original deployment / upgrade authority                0x3e0f4c7bdbf9bcc4aa9f22b3d03048b3ef2d7199


  Ordinary vesting owner before upgrade                0xf27f9a2eb9b2c70d32476cf9dc2d74ca4e61c27b


 New implementation                                  0xd346309df75eb6832bdc90dd8ba3b8e0264c97e3


 New controller / withdrawal and sale recipient          0x4d96f2d2143dd74a96d015a70953a5686fa6ed55

Assessment: this is documented removal and sale of tokens that exactly backed mature, unclaimed
contract allocations. It is a specific adverse event with identifiable affected addresses. The record does not
yet establish the human responsible, informed authorization, later migration or compensation, or the final
economic loss. Explorer phishing labels are third-party annotations and are not the basis for that conclusion.
Laura is not identified as a signer or recipient; a November 2025 event cannot explain her September 2022
departure without separate connecting evidence.

The 23,722.715761539594859905 BUSD located at d2b8 on BSC is a different asset on a different
network. The Polygon finding does not establish that this BUSD was stolen or settled to a bank. Current zero
XPND backing is separately pinned at Polygon block 93,358,017, 7 September 2026 00:47:39 UTC;
continuous intervening balances were not fully queried.

Sources and reproducibility: timeraiders_delivery/SUMMARY.md,
original80_bsc_funder_delivery_ledger.csv, all149_buyer_delivery_ledger.csv,
claim_receipts_verified.json, authorization_recovery.json and timeraiders_review/REVIEW.md. Fresh
decisive-receipt checks used the same successful Polygon RPC provider; arithmetic and local signature
recovery were independently performed. The claim census is all 440 explorer-indexed ordinary claim calls
reconciled to all 149 records, not an unrestricted internal-call census. Primary technical sources: EIP-7702,
1inch deployment list, Polygon system contracts and Polygon native-transfer event schema. Issuer token
identification: Time Raiders XPND guide.

Pooled wallet 35b1: cash accounting and the August sweep

56aa forwarded 28,421.141280969119319259 BUSD for GAMI on 17 May and 4,720.231567727363184247
for Shibafriend on 22 June. Both entered 35b1, whose respective preceding balances were
183,169.280000000000000012 and 131,015.421280969119319271 BUSD. Project 4's 2000 had entered
against 283,305.280000000000000012 BUSD. 56aa had zero BUSD before each of its three campaign
receipts; all ten ordinary signed transactions were recovered. Matching the next outgoing amount from
pooled 35b1 cannot identify a particular campaign's fungible proceeds. [E03, E05, E09]

The repository MemberCard source names 35b1 as treasury, but that revision has not been matched to its
historical deployment. This source association does not identify a legal owner. [P09]

The expanded inventory covers all 184 successful signed transactions, nonces 0-183, from 29 November
2021-7 November 2022, and 301 independently receipt-verified token events for BUSD, USDC, GMI and two
SHF contracts. Its BUSD ledger matches eight historical balance checkpoints. External BUSD inflow/outflow
each total 634,245.652848696482503518; USDC inflow/outflow each total 1,360,439.274293674825498827.
A 2000-BUSD self-transfer is excluded from external totals. Both stablecoin ledgers close at zero, as does
native BNB at pinned block 120,402,767. These are pooled turnover figures, not new fundraising or losses.

On 3 August 2022, 35b1 sent administrator address 14cc 390.50307622 BNB at 15:50:04,
26,626.652848696482503518 BUSD at 15:53:16 and 2302 USDC at 15:53:34. The BUSD and USDC
payments exhausted their respective balances; native value plus gas reconciles the BNB balance. 14cc
supplied 3 BNB between those payments. On 4 August, 14cc supplied 200 BNB, 35b1 converted it to




Historical analysis | Source page 6 | Public crypto edition

---

RESEARCH PAPER | GAMIFI PROJECT WITHDRAWALS



60,439.274293674825498827 USDC and returned that exact amount to 14cc. The return is not another
independent fundraising diversion. [N1-N6]

Earlier receipts include 650,000 USDC each from 87055 and ab2e in November 2021, 399,990 BUSD from
93cf in January 2022, and recurring payments to several counterparties. The largest repeated stablecoin
recipient, e602, received 246,171 BUSD and 185,750 USDC. Full addresses, test/main payment splits and
recurring schedules are in token_ledger_verified.json and repeated_counterparties.json; no investor,
employment or vendor identity is inferred.

35b1 also sent 20,000 BUSD to private-route onward wallet f4f8 on 30 May 2022, before that wallet's later
private-allocation proceeds. Its September/November BNB exchanges link f4f8 and April Launchpool funder
78d09. These establish operational connections, not common human ownership. [E09]

Shibafriend choices and two token versions

The 29 June cancellation notice offered private SHF allocation plus 1000 GMI or a refund; individual elections
are missing. The withdrawal preceded that notice by seven days. All 27 funding events from 26 addresses
reconcile to 4,720.231567727363184247 BUSD. Their comparison with 35b1's ten BUSD payments on 27
June, totalling 39,970, produced only two address overlaps and no exact amount matches: d2d6 contributed
100 base units and received 600 BUSD; e5d5 contributed 1243.781094527363184079 and received 4050.
This is not a verified refund schedule. Administrator 3e0f signed no ordinary outgoing transaction after the
22 June withdrawal block until 5 July; another payer, delegated transfer or later refund remains possible.
[P08; E03-E05]

New receipts trace distinct SHF versions: 0x96bad480691fee450598f3a6c144f09fa5df950d supplied
85,733.882037037 tokens through 35b1/3e0f in July, then to 74f7 on 25 August. Token
0x2d4df8a0e975e15ea443933affb27afe9395e2a8 supplied 9,259,259.2592 on 24 August; the next day
9,166,666.666608 went to 74f7 and 92,592.592592 to 3643, a 99%/1% split whose purpose is unassigned.
Neither destination is an original ID 9 funding address; an intermediary distribution remains possible.
Participant elections, token-version terms, onward deliveries and promised 1000-GMI payments remain
unresolved. [E09]

Project 4: funding circuit and receiver reassignment

Project 4's sole contributor 391a obtained 10,000 GMI and 1 BNB from 35b1 before its first signed transaction
on 11 March. The GMI had reached 35b1 from 3604, beneficiary of the 120 million GMI private vesting
allocation. At 10:52:07, 35b1 sent 2000 BUSD to 3604; at 10:54:34, 3604 sent 2000 to 391a; at 10:55:04,
391a contributed 2000 to project 4. Its claimBack(4) returned the 10,000 GMI stake at 11:55:43. That
function did not refund BUSD. [E10]

On 23 March, owner 3e0f changed project 4's receiver from its earlier configured 8fea destination to 35b1 at
14:56:37, then withdrew 2000 BUSD there at 14:58:07, using consecutive nonces 117-118. The
same-amount circuit is established at address level; it does not identify unique units after mixing, prove
testing, or establish that outside customer money was stolen. The purpose, authorization and contributor
relationship remain unknown. The 100-GMI onward payment on 29 March and 9,900-GMI return to 3604 on 6
December are individually preserved, not a complete intervening history.

Projects 1 and 3 paid 252.50 and 110 BUSD to owner/caller 8fea. Project 1 had six funding events from four
addresses; project 3's two funders are also in project 1, and all three small projects used 300-block funding
windows. Their names and commercial purposes remain unidentified. [E01-E02, E06]

Control, attribution and remaining records

The seven calls used the designed withdrawFunding function, paid the recorded funded total after the
configured end and changed the withdrawal flag. The March and May/June implementations independently
match all 14,983 and 15,877 runtime bytes. Historical owners were 8fea for projects 1/3 and 3e0f for 7/6/4;
May/June calls used enabled administrator 3e0f while 14cc was owner. Valid technical roles do not establish
human identity or commercial authority. [E02; P10-P11]





Historical analysis | Source page 7 | Public crypto edition

---

RESEARCH PAPER | GAMIFI PROJECT WITHDRAWALS



 All seven withdrawals preceded Eleanor Rooney's 1 September succession announcement. Laura's named
GAMI endorsement establishes promotion, not custody or instructions. No dated key assignment,
authenticated instruction or personally attributed receipt establishes her involvement in these payments.
[P06, P12]

The remaining records are: dated signing mandates; project 4's purpose and receiver-change instruction;
issuer settlement for GAMI/Time Raiders; entitlement of the 30 extra GAMI allocations; Shibafriend elections
and deliveries; and 35b1/14cc accounting for the August sweep and recurring recipients. Bank receipts
matter where fiat conversion or bank settlement is claimed. Crypto refunds, funded allocations and token
payments require their own evidence and must not be treated as absent merely because no bank receipt
exists.

Evidence coverage and detailed schedules

  Evidence                           Packaged records


  E01                                   chain/seven_withdrawals_verified.json and chain/root_raw/: exact original receipts,
                                             logs, calldata and timestamps.


  E02                                   chain/contract_review/: historical roles/recipient state, both exact code matches,
                                           project 4 and small-project records.


  E03                                   chain/recipient56aa/: ten signed transactions, FOMO funding/refund CSV and
                                     independent checks, SHF census/comparison.


  E04                                   chain/recipientd2b8/: pinned BSC balance, ordinary signed history and bounded
                                         administrator checks.


  E05                                   chain/35b_historical_balances.json, chain/35b_shf_window_verified.json and raw
                                          records: pooled balances and selected payments.


  E06                                   chain/id1_funding_logs.json: full project 1 funding window.


  E07                                   analysis/status_corrections.json, analysis/source_register.json,
                                         analysis/prior_project_mapping.json: historical classifications, locators and
                                       version-checked names; this report supersedes outdated outcome classifications.


  E08                                   onchain/gami_delivery/: exact 157-row allocation CSV, funding receipts, source match
                                  and atomic balance/claim snapshot.


  E09                                   onchain/pooled35b/: full signed inventory, selected token ledger, receipt checks,
                                          recurring counterparties and balances.


  E10                                   onchain/project4_control/: funding circuit, decoded actions and independent checks.


For BSC, public historical state used QuickNode and independent receipts/state used Binance and Defibit.
Polygon provider limits are described in its separate section above. The expanded 35b1 token index was
independently matched to receipts and balance checkpoints, not represented as an every-block census of
internal/allowance activity. GAMI claim counters are distinct from individual Claim receipts. No transactions
were broadcast and no third party was contacted. Full donor/allocation tables remain in the referenced CSVs.

Exact withdrawal ledger

Project 1 - Unidentified
UTC 2022-03-10 15:25:05; block 15,940,532; exact amount 252.5 BUSD. Caller 0x8fea; recipient 0x8fea.

0x4b0b66e2f020479b6381a1b31be240bfb86347cf1813ddb520c094576e6158df





Historical analysis | Source page 8 | Public crypto edition

---

RESEARCH PAPER | GAMIFI PROJECT WITHDRAWALS


Project 3 - Unidentified
UTC 2022-03-11 09:35:55; block 15,962,172; exact amount 110 BUSD. Caller 0x8fea; recipient 0x8fea.

0x4389510604c93f928c4e1a2f6fda07979d792228de1b6bb66a8242a7a7ee05b5

Project 7 - Time Raiders
UTC 2022-03-18 06:58:39; block 16,160,046; exact amount 23722.715761539594859905 BUSD. Caller
0x3e0f; recipient 0xd2b8.

0xa68d28501388dd1939659be1a24f6fbed8c0c22d6df5bbe43196ff408b3ffba4

Project 6 - GAMI
UTC 2022-03-18 12:23:52; block 16,166,501; exact amount 28421.141280969119319259 BUSD. Caller
0x3e0f; recipient 0x56aa.

0x4e2b2cebb9895bb8ed1ffa817e730273d9271e97e559a2fdd7ba2d4e86fd5299

Project 4 - Unidentified
UTC 2022-03-23 14:58:07; block 16,311,927; exact amount 2000 BUSD. Caller 0x3e0f; recipient 0x35b1.

0x33f6c2ae7893cf8763b5306d4220780592390cc22ab9399034f4b3ac6ee09683

Project 8 - Original FOMO
UTC 2022-05-23 11:50:16; block 18,051,156; exact amount 3775.228767123287671432 BUSD. Caller
0x3e0f; recipient 0x56aa.

0xfb51cbbf265af6b604ba3499d1608f36ab04a57eb3a71a4d5cbe3c6fe807d780

Project 9 - Shibafriend
UTC 2022-06-22 08:29:58; block 18,905,894; exact amount 4720.231567727363184247 BUSD. Caller
0x3e0f; recipient 0x56aa.

0x757fe0ce1d898fff34b0d4c4f58f2fc7610d3821eacc51c43d7e7e6ac0edcf63

Exact sum: 63001.817377359365034843 BUSD. All seven receipts have successful status and the
observed BUSD Transfer amount/recipient agrees with historical project state.

Full address register

  Role in this report                                                   Full BSC address


  Project proxy                                              0x56c0cb2d047b69278f49b4759c1718436a546c7f


 BUSD token on BSC                                        0xe9e7cea3dedca5984780bafc599bd69add087d56


  8fea: early owner / project 1 and 3 recipient                 0x8fea0bb760218398d32d4a9ef18553c403e3c2a0


  3e0f: March owner; May/June enabled administrator          0x3e0f4c7bdbf9bcc4aa9f22b3d03048b3ef2d7199


  14cc: owner at May/June withdrawal blocks                  0x14ccacd699287c1b6ad07fd911394a05d802b412


  56aa: GAMI / original FOMO / Shibafriend recipient           0x56aa83035aea8bfeb9e395a51607cc4621649aa2


  d2b8: Time Raiders recipient                               0xd2b806f9c0352a267ce7ccf33e74d68c070d6171


  35b1: pooled BUSD recipient                               0x35b119730f79881dac623dc51c831c6a04cab5f3




Historical analysis | Source page 9 | Public crypto edition

---

RESEARCH PAPER | GAMIFI PROJECT WITHDRAWALS



  Role in this report                                                   Full BSC address


  4867: FOMO batch intermediary                            0x4867171d50f734c34b020c45df23133cab5793a6


  f4f8: BNB recipient linked to 56aa and d2b8                 0xf4f86e37815217ed73ae817a4e5164d56315b1d7


  Gami Studio GAMI token                                    0xf0dcf7ac48f8c745f2920d03dff83f879b80d438


  GamiFi GMI token                                          0x93d8d25e3c9a847a5da79f79ecac89461feca846


  391a: sole project 4 contributor                             0x391a51d884b240908a88e1e757ec42189d294423


  3604: private-allocation beneficiary / project 4               0x36048413c4edf0cf3e633aab317fcd9824dfb4d4
  intermediary


  GAMI distribution endpoint                                  0xf1adf471918b65006bf5d8505f6df976d9873d8b


  74f7: SHF-token onward recipient                           0x74f7a03ee449bbe36f2c8201348962657cf96ddc


  3643: second-version SHF-token recipient                   0x3643c5c1ac8a7ecf0011e174ec8f94c451f833c3

Public sources and decisive transactions

P01 - GamiFi original FOMO delay/refund notice.

https://web.archive.org/web/20220523130044id_/https://gamifi-launchpad.medium.com/important-update-o
n-the-fomo-tge-a791fa00ca53

P02 - GamiFi official refund post 555.

https://t.me/GamiFiAnnouncements/555

P03 - Time Raiders participation announcement.

https://medium.com/timeraiders/how-to-participate-in-the-time-raiders-ido-43df9ca44e0f

P04 - GamiFi official Time Raiders distribution post 381.

https://t.me/GamiFiAnnouncements/381

P05 - GamiFi official Time Raiders timing post 386.

https://t.me/GamiFiAnnouncements/386

P06 - Issuer-distributed GAMI offering release.

https://kommunikasjon.ntb.no/pressemelding/17927527/play-to-earn-company-gami-lists-gamifis-first-launch
pad-ido?publisherId=90063

P07 - BitMart official Gami Studio token information.

https://bitmart.zendesk.com/hc/en-us/articles/4818549316891-Gami-Studio-GAMI

P08 - GamiFi Shibafriend cancellation notice.

https://web.archive.org/web/20220629111324id_/https://gamifi-launchpad.medium.com/shibafriend-ido-ann
ouncement-e57f229783f7





Historical analysis | Source page 10 | Public crypto edition

---

RESEARCH PAPER | GAMIFI PROJECT WITHDRAWALS


P09 - GamiFi repository MemberCard source.

https://raw.githubusercontent.com/sheandev/gamifiContracts/main/contracts/MemberCard.sol

P10 - Sourcify exact March implementation.

https://sourcify.dev/server/v2/contract/56/0xfa83e6a35d98e5243cd3e5740b6f52daa316c075?fields=all

P11 - Sourcify exact May/June implementation.

https://sourcify.dev/server/v2/contract/56/0xed2f3357813fb4796ce5da11ea8054ae0f2d22c8?fields=all

P12 - GamiFi CEO succession announcement.

https://gamifi-launchpad.medium.com/new-ceo-for-gamifi-451f0e5a2147

Decisive onward and control transactions

The transaction hashes are independently anchored in the packaged RPC receipts. Explorer URLs are
convenient locators; explorer page access was unavailable during this pass. All are BSC chain 56.

GAMI: 56aa to 35b1

0x9339942839aa8aa7e023b41b91c536b466f34fc32ced0ac9810ca21ba70eef04

FOMO: 56aa to administrator

0xa287c4c322a3db7f108b312a35845c3b6cbf910a0326c50b1b5690c0d6eb7144

FOMO refund batch A

0x41beaff61e66c1f292a53d0aaf60214b757c1130804535dd3f79e4c8c07e9f09

FOMO refund batch B

0xe49f8251937633b2e184fc4c4219c89cdbc110446cb822caab013e30be2b3837

Shibafriend: 56aa to 35b1

0x439605f89ef1315c95e5c8d61e4d6fd9c29a2a5d1cf304c6cb0a9dc5646b0dad

Project 4 recipient change

0x39f7777f43b5155f7238fa822d796206ddcd74e0b27481c78f33b7debf00f8cc

GAMI token transfer to administrator

0x2b21af95699be3decd17d62c3c1d8da96a4d21b7f848d6d58ffd47769716c766

Time Raiders recipient BNB to f4f8

0x5bdddcaebe994fbfd4809f99f2e04c7cd7621b4f5e124e39aa5f59de8f8b2af0

56aa BNB to f4f8

0xf60c791262ad96e8c1e51d766d7817f6b0d1f51293185b4b7973212cb4cb8f3e

P13 - GAMI vesting implementation and historical code match. Sourcify source.

P14 - Public 35b1 index and independent records. BSCTrace; NodeReal account endpoint. Index labels
are not human attribution.



Historical analysis | Source page 11 | Public crypto edition

---

RESEARCH PAPER | GAMIFI PROJECT WITHDRAWALS


 • N1, August 3 BNB sweep: receipt.
 • N2, August 3 BUSD sweep: receipt.
 • N3, August 3 USDC sweep: receipt.
 • N4, August 4 incoming 200 BNB: receipt.
 • N5, August 4 conversion: receipt.
 • N6, resulting USDC return: receipt.
 • N7, project 4 funding circuit: 35b1→3604, 3604→391a, 391a→project.

Additional primary identifiers for printed review

These identifiers reproduce the targets of the cited links above; they add no separate evidentiary claim.

 • receipt: 0x202357295230d75ff4683405feb2fde8ab8ce9de177275d61bafe9c050b2d16a

 • receipt: 0x3f5359c3f405974a4b9e91705ecae180221c6c984bfeac800b1cde2f83f4f423

 • receipt: 0x4a0f5d61337a404788cab8d53d6e4702a2ee62cbc41142a1347965399e01f701

 • 35b1→3604: 0x4a298bd4a19e7993c92d2e54651f55145330c93e8f9a2b61592b6f7a65ec7ccd

 • 4a8ebee7: 0x4a8ebee724b6bc76a07ce56c239f2f16b3f03361f558fe959dc86f55c96ffe5b

 • Delegation and ownership:
   0x4e8f533f07d6294332437777661389d9fb6668c768bc49c645c5c868af3b2d84

 • 391a→project: 0x553cf2385ef6d40f35e589accd89be0129ee78ff4e1ce3edae423700ce27a288

 • Implementation upgrade: 0x70b2ca519be59b73947714d7c9fcc7dcfe0b8aa4e3a2f59ad5f97044f494755a

 • receipt: 0x7d9b1d573aef0370c63c764df2c3325428238b6b0a53108957fb58cdebed167d

 • 3604→391a: 0x9397957fd74ccd8680e56b5c8734c1917efec4c57611bf4a59fa8705b5ce6a62

 • Sourcify source: 0x957e15b2fa377bfe35e6134411c65bd36dab9522

 • Swap and native payout: 0x97b91a02cd4efa3668fccfe2962e40fb7f398c3587b3a4613ff8bbbd65aeff64

 • Token withdrawal: 0xbd929f950089a74c90bff99743514421126bf31a9abd4c943fefb6cee317b38a

 • receipt: 0xc64dbd4a8322d5b5a4877095f1adb3e050a2ae3f7ba6cd68e141b2253ec817a1

 • receipt: 0xe3195050fc274cc6e176a82997f668fd796932c693297039e6fe1d36210b979e





Historical analysis | Source page 12 | Public crypto edition

## Public source link targets

These retain the external targets of citation links and transaction-receipt cells in the PDF.

| Historical source page | Public URL |
| --- | --- |
| 4 | <https://bscscan.com/tx/0x4a8ebee724b6bc76a07ce56c239f2f16b3f03361f558fe959dc86f55c96ffe5b> |
| 5 | <https://polygonscan.com/tx/0x4e8f533f07d6294332437777661389d9fb6668c768bc49c645c5c868af3b2d84> |
| 5 | <https://polygonscan.com/tx/0x70b2ca519be59b73947714d7c9fcc7dcfe0b8aa4e3a2f59ad5f97044f494755a> |
| 5 | <https://polygonscan.com/tx/0xbd929f950089a74c90bff99743514421126bf31a9abd4c943fefb6cee317b38a> |
| 5 | <https://polygonscan.com/tx/0x97b91a02cd4efa3668fccfe2962e40fb7f398c3587b3a4613ff8bbbd65aeff64> |
| 6 | <https://eips.ethereum.org/EIPS/eip-7702> |
| 6 | <https://github.com/1inch/limit-order-protocol> |
| 6 | <https://docs.polygon.technology/pos/reference/contracts/genesis-contracts> |
| 6 | <https://medium.com/the-polygon-blog/finer-details-of-matics-plasma-implementation-jaynti-kanani-d333550fa71d> |
| 6 | <https://medium.com/timeraiders/how-to-buy-xpnd-on-quickswap-the-ultimate-guide-d3b81a3e7a9b> |
| 8 | <https://bscscan.com/tx/0x4b0b66e2f020479b6381a1b31be240bfb86347cf1813ddb520c094576e6158df> |
| 9 | <https://bscscan.com/tx/0x4389510604c93f928c4e1a2f6fda07979d792228de1b6bb66a8242a7a7ee05b5> |
| 9 | <https://bscscan.com/tx/0xa68d28501388dd1939659be1a24f6fbed8c0c22d6df5bbe43196ff408b3ffba4> |
| 9 | <https://bscscan.com/tx/0x4e2b2cebb9895bb8ed1ffa817e730273d9271e97e559a2fdd7ba2d4e86fd5299> |
| 9 | <https://bscscan.com/tx/0x33f6c2ae7893cf8763b5306d4220780592390cc22ab9399034f4b3ac6ee09683> |
| 9 | <https://bscscan.com/tx/0xfb51cbbf265af6b604ba3499d1608f36ab04a57eb3a71a4d5cbe3c6fe807d780> |
| 9 | <https://bscscan.com/tx/0x757fe0ce1d898fff34b0d4c4f58f2fc7610d3821eacc51c43d7e7e6ac0edcf63> |
| 10 | <https://web.archive.org/web/20220523130044id_/https://gamifi-launchpad.medium.com/important-update-on-the-fomo-tge-a791fa00ca53> |
| 10 | <https://t.me/GamiFiAnnouncements/555> |
| 10 | <https://medium.com/timeraiders/how-to-participate-in-the-time-raiders-ido-43df9ca44e0f> |
| 10 | <https://t.me/GamiFiAnnouncements/381> |
| 10 | <https://t.me/GamiFiAnnouncements/386> |
| 10 | <https://kommunikasjon.ntb.no/pressemelding/17927527/play-to-earn-company-gami-lists-gamifis-first-launchpad-ido?publisherId=90063> |
| 10 | <https://bitmart.zendesk.com/hc/en-us/articles/4818549316891-Gami-Studio-GAMI> |
| 10 | <https://web.archive.org/web/20220629111324id_/https://gamifi-launchpad.medium.com/shibafriend-ido-announcement-e57f229783f7> |
| 11 | <https://raw.githubusercontent.com/sheandev/gamifiContracts/main/contracts/MemberCard.sol> |
| 11 | <https://sourcify.dev/server/v2/contract/56/0xfa83e6a35d98e5243cd3e5740b6f52daa316c075?fields=all> |
| 11 | <https://sourcify.dev/server/v2/contract/56/0xed2f3357813fb4796ce5da11ea8054ae0f2d22c8?fields=all> |
| 11 | <https://gamifi-launchpad.medium.com/new-ceo-for-gamifi-451f0e5a2147> |
| 11 | <https://bscscan.com/tx/0x9339942839aa8aa7e023b41b91c536b466f34fc32ced0ac9810ca21ba70eef04> |
| 11 | <https://bscscan.com/tx/0xa287c4c322a3db7f108b312a35845c3b6cbf910a0326c50b1b5690c0d6eb7144> |
| 11 | <https://bscscan.com/tx/0x41beaff61e66c1f292a53d0aaf60214b757c1130804535dd3f79e4c8c07e9f09> |
| 11 | <https://bscscan.com/tx/0xe49f8251937633b2e184fc4c4219c89cdbc110446cb822caab013e30be2b3837> |
| 11 | <https://bscscan.com/tx/0x439605f89ef1315c95e5c8d61e4d6fd9c29a2a5d1cf304c6cb0a9dc5646b0dad> |
| 11 | <https://bscscan.com/tx/0x39f7777f43b5155f7238fa822d796206ddcd74e0b27481c78f33b7debf00f8cc> |
| 11 | <https://bscscan.com/tx/0x2b21af95699be3decd17d62c3c1d8da96a4d21b7f848d6d58ffd47769716c766> |
| 11 | <https://bscscan.com/tx/0x5bdddcaebe994fbfd4809f99f2e04c7cd7621b4f5e124e39aa5f59de8f8b2af0> |
| 11 | <https://bscscan.com/tx/0xf60c791262ad96e8c1e51d766d7817f6b0d1f51293185b4b7973212cb4cb8f3e> |
| 11 | <https://sourcify.dev/server/v2/contract/56/0x957e15b2fa377bfe35e6134411c65bd36dab9522?fields=all> |
| 11 | <https://bsctrace.com/address/0x35b119730f79881dac623dc51c831c6a04cab5f3> |
| 11 | <https://bsc-explorer-api.nodereal.io/api/tx/getAssetTransferByAddress> |
| 12 | <https://bscscan.com/tx/0x7d9b1d573aef0370c63c764df2c3325428238b6b0a53108957fb58cdebed167d> |
| 12 | <https://bscscan.com/tx/0x4a0f5d61337a404788cab8d53d6e4702a2ee62cbc41142a1347965399e01f701> |
| 12 | <https://bscscan.com/tx/0x202357295230d75ff4683405feb2fde8ab8ce9de177275d61bafe9c050b2d16a> |
| 12 | <https://bscscan.com/tx/0xe3195050fc274cc6e176a82997f668fd796932c693297039e6fe1d36210b979e> |
| 12 | <https://bscscan.com/tx/0xc64dbd4a8322d5b5a4877095f1adb3e050a2ae3f7ba6cd68e141b2253ec817a1> |
| 12 | <https://bscscan.com/tx/0x3f5359c3f405974a4b9e91705ecae180221c6c984bfeac800b1cde2f83f4f423> |
| 12 | <https://bscscan.com/tx/0x4a298bd4a19e7993c92d2e54651f55145330c93e8f9a2b61592b6f7a65ec7ccd> |
| 12 | <https://bscscan.com/tx/0x9397957fd74ccd8680e56b5c8734c1917efec4c57611bf4a59fa8705b5ce6a62> |
| 12 | <https://bscscan.com/tx/0x553cf2385ef6d40f35e589accd89be0129ee78ff4e1ce3edae423700ce27a288> |
| 12 | <https://bscscan.com/tx/0x4a8ebee724b6bc76a07ce56c239f2f16b3f03361f558fe959dc86f55c96ffe5b> |
| 12 | <https://polygonscan.com/tx/0x4e8f533f07d6294332437777661389d9fb6668c768bc49c645c5c868af3b2d84> |
| 12 | <https://polygonscan.com/tx/0x70b2ca519be59b73947714d7c9fcc7dcfe0b8aa4e3a2f59ad5f97044f494755a> |
| 12 | <https://sourcify.dev/server/v2/contract/56/0x957e15b2fa377bfe35e6134411c65bd36dab9522?fields=all> |
| 12 | <https://polygonscan.com/tx/0x97b91a02cd4efa3668fccfe2962e40fb7f398c3587b3a4613ff8bbbd65aeff64> |
| 12 | <https://polygonscan.com/tx/0xbd929f950089a74c90bff99743514421126bf31a9abd4c943fefb6cee317b38a> |