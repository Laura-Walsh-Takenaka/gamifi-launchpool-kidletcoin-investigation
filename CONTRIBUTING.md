# Contributing to Research Paper — Public Crypto Research

Contributions should make a specific part of the record easier to verify. New evidence, reproduced calculations, narrower interpretations, corrections and rebuttals are all useful.

## Choose the right contribution

| Route | Use it for |
| --- | --- |
| **Verification task** issue | Define a bounded question and a reproducible method before doing the work. |
| **Evidence submission** issue | Add a public record or a reproducible observation, with its source and limits. |
| **Correction or rebuttal** issue | Challenge an existing statement, calculation, attribution or omission. |
| **Pull request** | Propose a precise change to reports, notes, tables, indexes or reproduction material. |

One claim or closely related set of claims per contribution is easier to review. Read the latest topic-specific correction before relying on an older report.

## The minimum evidence packet

Provide the following in the issue or pull request:

1. **Target:** repository file and page, section, table row or claim being addressed.
2. **Question:** what you tested, without assuming the answer.
3. **Source:** public URL, issuing organization or publisher, exact transaction/document identifier and relevant source date.
4. **Retrieval:** access date in UTC, archive capture timestamp where applicable, and checksum for any included file.
5. **Method:** query range, software/version and reproducible commands or calculations where relevant.
6. **Result:** what the record actually shows. Quote only what is needed and keep attribution clear.
7. **Limits:** missing records, incomplete ranges, failed requests, alternate explanations and contradictory evidence.
8. **Proposed change:** the wording, table correction or next step you recommend.

Indicate whether the contribution is an **observation**, a **publisher's statement**, an **inference**, a **hypothesis** or an **unresolved question**. A source's own claim should not become an independently verified fact simply because the repository repeats it.

## Blockchain checks

- Specify network and chain ID, contract/token address, decimals, block number and preferably block hash, transaction hash and successful receipt.
- Distinguish transaction input, emitted events, state reads, traces, explorer labels and human-identity evidence.
- Use integer base units or exact decimal arithmetic. State rounding and valuation dates. Do not silently assume a stablecoin traded exactly at its peg.
- State whether the query covers all relevant activity or a bounded sample. For completeness claims, explain the interval, pagination, nonce checks and gaps.
- Separate ordinary transactions from internal calls, token events, failed calls and approvals.
- Check bridge completion through protocol identifiers and matching fields where possible; a source-side request alone is not a completed destination transfer.
- Distinguish a first-party exchange disclosure from an explorer label. Preserve the disclosure date. Neither alone proves an earlier deposit was credited to a particular customer.
- For privacy pools, timing, denomination and shared relayers do not establish a deposit-to-withdrawal match. Never publish private keys, seed phrases or spendable notes.
- Avoid counting the same funds at successive hops. Record refunds, claims, replenishments, commingled funds and fees as separate accounting components.

Where practical, reproduce material observations using an independent provider. Repeating the same provider's answer is a useful consistency check, not independent-provider corroboration.

## Statements, companies and historical records

Keep event date, publication date, capture date and retrieval date separate. Archive metadata is not necessarily the date the underlying statement first appeared.

Match companies by identifiers and jurisdiction, not just similar names. A current director, a nominal officer, a shareholder, an adviser, a contract owner address and a historical signing-key custodian are different roles. Explain the evidence for each connection.

For audio/video, provide the source and timestamp. Automatic captions are review aids; verify disputed quotations and speaker attribution against the recording. Preserve relevant context and corrections.

For source code, pin the commit and distinguish reviewed code from the deployed implementation or released application. A source defect does not establish production exposure without a reliable deployment match.

Search no-matches and unavailable records should describe the search scope and access result. They must not become assertions that no such record exists.

## Corrections and contrary evidence

Identify the old wording and propose replacement wording with supporting evidence. Check which other files repeat the same claim. Explain whether your contribution supersedes an earlier finding or applies to a different date, token, contract, cohort or network.

Preserve evidence supporting refunds, delivery or other explanations. Do not turn every transfer into a loss or every professional connection into shared responsibility. An unresolved question should stay unresolved until the required evidence is obtained.

## Public research boundaries

Keep contributions relevant to public crypto-project conduct and records. Do not upload private contact details, personal addresses, identity documents, account credentials, information identifying children or unnecessary personal data. A public blockchain address may be relevant evidence, but identifying its human owner requires a reliable, relevant source.

Use public records and authorized access. Do not attempt to enter accounts, query private customer databases, impersonate officials or obtain confidential records through deception. If non-public material would answer a question, describe the missing record without posting it in an issue.

Do not organize targeted contact, pressure campaigns or personal attacks. Discuss the evidence and proposed corrections. A subject's response receives the same source and verification standards as any other submission.

## File and source handling

- Use neutral descriptive filenames, for example `research-paper-gamifi-offering-terms-2022.md`.
- Preserve source title, public URL, date and publisher attribution in the source register.
- Include only material you are entitled to contribute. Prefer a source link and necessary excerpt when full-document redistribution is unclear.
- Identify edits, annotations and redactions. Do not present an edited exhibit as untouched original evidence.
- Do not overwrite an existing artifact silently; explain substantive changes in the pull request.
- Keep secrets, personal workstation paths, authentication material and unrelated account metadata out of files and commits.

Review [RIGHTS_AND_SOURCES.md](RIGHTS_AND_SOURCES.md). No blanket license over third-party source material is created by submitting or merging a contribution.
