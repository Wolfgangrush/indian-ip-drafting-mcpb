# Sample Cases — Reviewer Examples

Three anonymised fact patterns. All party names are placeholders.

## Example 1 — trademark-infringement-suit

> *"Use the connector to draft a trademark infringement suit (Trademark infringement suit under Sections 27, 29, 134 Trade Marks Act 1999). Use anonymised placeholders for party names and figures."*

Tool sequence: list_case_types → get_case_type_format("trademark-infringement-suit") → get_pleading_base → draft → save_draft_as_docx

## Example 2 — trademark-rectification-application

> *"Use the connector to draft a trademark rectification application (Rectification application before HC IP Division / Registrar of Trade Marks). Use anonymised placeholders for party names and figures."*

Tool sequence: list_case_types → get_case_type_format("trademark-rectification-application") → get_pleading_base → draft → save_draft_as_docx

## Example 3 — copyright-infringement-suit

> *"Use the connector to draft a copyright infringement suit (Copyright infringement suit under Section 55 Copyright Act 1957). Use anonymised placeholders for party names and figures."*

Tool sequence: list_case_types → get_case_type_format("copyright-infringement-suit") → get_pleading_base → draft → save_draft_as_docx

## Notes for the reviewer

- All examples use placeholders.
- No external API keys / accounts required.
- `save_draft_as_docx` requires `pandoc`.
- Three-layer privacy firewall applies throughout.
