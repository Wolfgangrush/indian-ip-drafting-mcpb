# Case Facts Background — Trade Mark Infringement Suit (Sections 27, 29, 134 TM Act 1999)

All party names, mark names, registration numbers, addresses, monetary figures, social-media handles, and ancillary dates are fictional placeholders.

## Parties

- **Plaintiff:** M/s [Plaintiff-Company-Placeholder] Private Limited, CIN [Plaintiff-CIN-Placeholder], registered office at [Plaintiff-Registered-Office-Placeholder]. Registered proprietor of the mark "[Plaintiff-Mark-Placeholder]".
- **Defendant:** M/s [Defendant-Company-Placeholder], having registered office at [Defendant-Registered-Office-Placeholder]. The party using the deceptively similar mark "[Defendant-Mark-Placeholder]".

## Plaintiff's intellectual property

- **Registered trade mark:** "[Plaintiff-Mark-Placeholder]" — Reg. No. [TM-Reg-No-Placeholder], Class [Nice-Class-Placeholder] (see `01-trademark-registration-certificate.docx`).
- **Date of registration:** [TM-Reg-Date-Placeholder].
- **First use claimed:** [First-Use-Date-Placeholder]. Continuous and extensive use since then; pan-India.
- **Reputation:** acquired secondary meaning and well-known status in [Geographic-Reputation-Placeholder]; annual revenue Rs. [Plaintiff-Revenue-Placeholder]/-.
- **Renewal:** valid up to [Renewal-Valid-To-Placeholder]; in good standing.

## Acts of infringement

(Investigation report — `02-defendants-infringing-use-investigation-report.docx`)

- Defendant uses "[Defendant-Mark-Placeholder]" on (a) website, (b) physical store signage, (c) product packaging, (d) trade catalogue, (e) social-media handles.
- The mark differs in only [Visual-Diff-Placeholder] characters; typeface, colour palette, stylistic flourishes substantially identical.
- Goods / services: identical class — same channel of trade — same target consumer.
- Market confusion documented: (i) three customer mis-identifications during site visit, (ii) [Customer-Complaints-Placeholder] complaints to Plaintiff's customer service in [Complaint-Period-Placeholder], (iii) two trade-publication mis-attributions.

## Cease-and-desist + non-compliance

- Notice issued: 22 April 2026 (see `03-cease-and-desist-notice-2026-04-22.docx`).
- 14-day compliance window: expired 06 May 2026.
- Defendant's response: NIL. Defendant continues to use the infringing mark.

## Forum and case type

- **Forum:** Bombay High Court (IP Division) under Section 134 of the Trade Marks Act, 1999 — Plaintiff's principal place of business is within the territorial jurisdiction. (Alternative under Section 134(2) — place where the Plaintiff carries on business.)
- **Case type:** `trademark-infringement-suit`.
- **Statutory anchors:** Sections 27, 28, 29, 134, 135 of the Trade Marks Act, 1999. Plus Order XXXIX Rules 1 and 2 CPC for interim injunction.

## Reliefs sought

1. **Permanent injunction** restraining the Defendant and all those acting through, by, under, or in concert with the Defendant from using the mark "[Defendant-Mark-Placeholder]" or any other mark deceptively similar to "[Plaintiff-Mark-Placeholder]" in respect of goods / services in Class [Nice-Class-Placeholder] or any other class.
2. **Interim and ad interim injunction** under Order XXXIX Rules 1 and 2 CPC pending hearing and final disposal of the suit.
3. **Mandatory injunction** directing the Defendant to (a) withdraw all infringing material from public-facing channels, (b) destroy all packaging / signage / catalogue / advertising material, (c) take down all online assets, (d) transfer / take down social-media handles using the infringing mark.
4. **Account of profits / damages** in the alternative — quantification to be determined on discovery, with a minimum prayer of Rs. [Damages-Sought-Placeholder]/-.
5. **Anton Piller, John Doe, and Mareva orders** as appropriate to preserve evidence and assets.
6. **Delivery up** of all infringing materials in the Defendant's possession.
7. **Costs** of the suit.

## Ingredient check (Verifier-stage)

- ✅ Registered mark proven — certificate at `01-trademark-registration-certificate.docx`.
- ✅ Deceptive similarity proven — investigation report at `02-defendants-infringing-use-investigation-report.docx`.
- ✅ Identical class and goods / services proven — Nice Class [Nice-Class-Placeholder] same for both.
- ✅ Likelihood of confusion proven — documented mis-identification incidents.
- ✅ Use in the course of trade — investigation evidence.
- ✅ Cease-and-desist served + ignored — `03-cease-and-desist-notice-2026-04-22.docx` + 14-day non-compliance.
- ✅ Limitation — within 3 years from cause of action under Article 113 Limitation Act 1963 (continuing infringement — fresh cause arises each day).
- ✅ Section 134(2) jurisdictional facts pleadable.

## How to use this fixture

1. Point `read_case_folder(path)` at this directory.
2. Reader extracts facts from the 3 `.docx` files plus this `case-facts-background.md`.
3. Call `get_case_type_format("trademark-infringement-suit")`.
4. The remaining 5 agents (Format → Drafter → Verifier → Refiner → Overseer) run end-to-end to produce `final-draft.docx` containing the suit (Cause Title, Parties, Statement of Facts, Cause of Action, Reliefs, Order XXXIX Rules 1/2 application, Verification, List of Documents, Affidavit).
