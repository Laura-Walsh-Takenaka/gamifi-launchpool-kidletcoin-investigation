# Research Paper — Evidence

This directory indexes 17,719 normalized public-source records supporting the research. Use the [CSV catalog](Research_Paper_Evidence_Catalog.csv) to filter by topic, record ID, source label or representation. The [JSON catalog](Research_Paper_Evidence_Catalog.json) contains the same index for programmatic use.

Use the [archive-location table](Research_Paper_Evidence_Locations.csv) to find the archive and member path for a record. Extract the eight evidence archives into one local `evidence-extracted/` directory; their shared `records/` folder will merge. Catalog `file` paths are relative to that `records/` folder. Keep the compressed archives intact when uploading the repository.

The collection contains 48 additional CSV copies of tabular records. Thirty-nine indexed items are source references only; the catalog marks them explicitly and their records explain the extraction limitation.

The evidence archives are independently extractable. Their files use the topic paths shown in the catalog. Each JSON record contains its source data or selected text, its representation type, direct provenance links when available, and other links found in the source. CSV copies accompany tabular records.

## Launchpool follow-up, 7 September 2026

The [Launchpool follow-up evidence archive](Research_Paper_Launchpool_Followup_2026-09-07.tar.xz) contains the recovered public-source bundle as a searchable report, preserved on-chain/RPC and explorer responses, claim data, source registers, peer checks and reproduction scripts. It is stored under `launchpool-followup/` when extracted. The path names and filenames preserve the original research collection structure so its reproduction commands and path references still resolve. The bundled README lists offline reproduction commands and identifies scripts that rewrite outputs; run those only in a working copy. Do not treat a successful reproduction of supplied data as independent source corroboration.

The original source bundle contained branded document identifiers; those labels and duplicate branded report PDFs were removed. A new public-edition SHA-256 list covers all 2,007 retained evidence files; that list is excluded from its own hash table. The searchable public report is in `reports/`. Source URLs, dates, transaction data and caveats remain. This archive does not contain every original deed, full third-party webpage, application body or private/customer record. It excludes scripts that only built or audited the branded PDF. Bundled scripts are inert until a contributor chooses to inspect or run them; the claim re-fetch option makes public network requests, and several reproduction scripts rewrite derived files. Review the code and run it only in a disposable working copy. No script was run to prepare this package.

## Reading the records

- `public_source_urls` lists direct provenance recorded with the source or an unambiguous match to its provenance metadata. An empty list means a reliable direct locator was not retained. It does not mean the record was independently verified.
- `referenced_public_urls` inside each record lists other links that appeared in its source, which may be citations or navigation links. These are not automatically primary sources. The catalog records their count.
- Structured chain data retains recorded request parameters, responses, transaction identifiers and integer or string amounts. Recheck the network, block, token decimals, success status and attribution before drawing conclusions.
- Web and PDF text are normalized derivatives. They do not preserve page layout, every image or executable content. Corporate excerpts are selected passages; inspect the linked original for context.
- `source-reference` identifies a document without reproducing its full contents. Its record states the extraction limitation.
- Smart-contract code is inert source text for comparison. No bundled collector or contract code was executed to produce findings for this edition.
- Historical ledger cells retain stored values and formula text; formulas were not recalculated during this conversion.

SHA-256 values in the catalog verify the delivered derivative bytes. They do not authenticate a publisher, prove a factual claim or establish control of a wallet. The historical sources were not all downloaded again or independently reverified for this edition.

Begin with the topical research papers for context and uncertainty. Use source records to reproduce calculations and challenge unsupported interpretations.

The evidence archives use `.tar.xz` compression. Open them with a compatible archive manager, or first create an `evidence-extracted` folder and extract from a terminal with `tar -xJf ARCHIVE.tar.xz -C evidence-extracted`. The outer repository download remains a standard ZIP.
