# Wolfgang Rush — Indian IP Drafting

**MCPB Desktop Extension** for Indian advocates using Claude Desktop App. Local-execution. Zero data collection.

> *Also available as a Claude Code Plugin:* *[github.com/Wolfgangrush/indian-ip-drafting](https://github.com/Wolfgangrush/indian-ip-drafting)*

## What this connector does

Trademark, copyright, patent, design + IP-defence drafting for HC IP Divisions post-IPAB-abolition. John Doe / Anton Piller orders, interim injunctions. Six-agent local pipeline. Zero data leaves the user's machine.

## Case types

- `trademark-infringement-suit` — Trademark infringement suit under Sections 27, 29, 134 Trade Marks Act 1999
- `trademark-rectification-application` — Rectification application before HC IP Division / Registrar of Trade Marks
- `copyright-infringement-suit` — Copyright infringement suit under Section 55 Copyright Act 1957
- `copyright-fair-dealing-defence` — Fair-dealing defence framework under Section 52 Copyright Act
- `patent-infringement-suit` — Patent infringement suit under Sections 104, 108 Patents Act 1970
- `patent-revocation-application` — Patent revocation application under Section 64 Patents Act
- `design-piracy-suit` — Design piracy suit under Section 22 Designs Act 2000
- `passing-off-suit` — Passing-off action (common-law tort)
- `john-doe-anton-piller-order-application` — John Doe / Anton Piller order application
- `interim-injunction-application-ip` — Interim injunction application in IP suits

## Install

1. Claude Desktop App → **Settings → Extensions → Install Extension**
2. Select `wolfgang-indian-ip-drafting.mcpb`
3. Enable

## System requirements

Claude Desktop App ≥ 0.10.0 · Python ≥ 3.10 · `pandoc` for .docx · `pdftotext` for PDF case-files (optional)

## Privacy

Zero data collection. Three-layer privacy firewall. Canonical policy: **<https://wolfgangrush.github.io/privacy/>**


## ⚠️ AI verification disclaimer · 🔒 Pseudonymisation procedure

> **⚠️ AI can make mistakes — please verify the information before filing.**
> Every draft produced by this connector is a STARTING POINT. The Verifier
> agent runs an anti-hallucination firewall and the Overseer agent runs an
> opposing-counsel review, but neither replaces an advocate's independent
> verification of statutory references, citation accuracy, factual fidelity,
> and Registry-formatting compliance with the user's High Court / forum.
> The advocate filing the pleading remains responsible for the contents.
>
> **🔒 Protected by pseudonymisation procedure.** The Reader agent applies a
> domain-specific privacy firewall as the first step of the pipeline — party
> names, addresses, identifying numbers (FIR / CR / Crime / Suit / Diary /
> SLP / lower-court case numbers), PAN / Aadhaar references, financial
> figures, witness names, and statutory-notice references are substituted
> with structural placeholders BEFORE any downstream agent sees the facts.
> The Drafter, Verifier, Refiner, and Overseer agents process placeholders
> only. Real values are re-substituted at the final docx render step on the
> user's local machine. No real identifying data leaves the case folder.

## License

MIT.

## Publisher

**Rushikesh R. Mahajan**, Advocate, Bombay HC Nagpur, publishing as **Wolfgang Rush**. advrushikeshravindramahajan@gmail.com

## Source

<https://github.com/Wolfgangrush/indian-ip-drafting-mcpb>

## Sample cases

See `SAMPLE-CASES/`.
