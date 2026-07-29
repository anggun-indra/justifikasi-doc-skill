---
name: justifikasi-promosi-doc
description: Create, revise, and validate Indonesian promotion-justification documents in Google Docs from a candidate CV, role requirements, an existing template, and requested wording or visual references. Use when asked to prepare a justifikasi promosi, revise its rationale or decision section, update the target role throughout a promotion document, or preserve a Google Docs template while adapting its content.
---

# Justifikasi Promosi Doc

Create a decision-ready promotion justification while preserving the user's Google Docs structure and keeping personal data out of reusable skill files.

## Required Inputs

Collect only what is needed for the request:

- the candidate evidence (for example, CV, work history, or portfolio);
- the authoritative role requirement and exact target job title;
- the working Google Doc, or a reusable template plus destination folder;
- requested wording, section changes, and any visual reference image.

Ask for a missing input only when it materially changes the document. Do not infer a vacancy, resignation, date, approver, metric, or job requirement without a user-provided source.

## Privacy Rules

- Treat candidate names, employers, email addresses, CV contents, document URLs, Drive IDs, folder IDs, screenshots, and approval details as task-local confidential data.
- Never place those values in this skill, bundled resources, example prompts, commit messages, or repository documentation.
- Use generic placeholders only when an example is necessary, such as `[candidate]`, `[target role]`, or `[working document]`.
- Do not upload source CVs, screenshots, copied document exports, or generated PDFs to the skill repository unless the user explicitly asks.

## Native Google Docs Workflow

1. Use the connected Google Drive and Google Docs skills for live Drive/Docs work. Read their instructions before acting.
2. For a reusable template, create a native copy in the requested destination. For a user-designated working document, edit that document in place.
3. Before the first write to an existing document, run the Google Docs trusted read. Confirm document ID, title, tab ID, revision, protected controls, and the exact target table/cell.
4. Preserve native tabs, headers, footers, tables, lists, person chips, and approval blocks unless the user explicitly asks to change them.
5. Use `get_document_tables` for table edits. Resolve the target table, row, and column from current readback; use a revision guard; then re-read after every index-shifting write.
6. Make the smallest section-sized change. Do not rebuild the document or duplicate a section merely to change one row.

## Content Placement

- Keep the background focused on the documented business reason for the promotion or vacancy.
- Put candidate experience, technical skills, education, and demonstrated work under the competency-and-role-fit section when that is the intended logic.
- Update a corrected target role consistently in the document title, headers, footers, metadata, and body only when the user requests a global correction.
- Ground claims in the candidate evidence and stated requirements. Use cautious language when evidence supports readiness rather than proven outcomes.
- When a user supplies a visual reference for a decision row, reproduce only the requested wording, line breaks, and emphasis in the named current row. Retain the current row number and label unless the user explicitly asks to change them.
- Apply strikethrough, italics, bolding, and blank note space only to the requested ranges. Do not convert them into typed approximations of native controls.

## Validation and Handoff

1. Re-read the settled document and confirm the changed content is in the intended table cell and tab.
2. Verify that unrelated approval names, signatures, tables, and template structure remain unchanged.
3. For table-heavy or layout-sensitive changes, export to PDF, rasterize every page, and inspect for clipping, broken rows, unwanted page breaks, or formatting drift. State plainly if rendered verification is unavailable.
4. Return the working Google Docs link and a concise summary of the completed change. Do not repeat confidential source data in the handoff.
