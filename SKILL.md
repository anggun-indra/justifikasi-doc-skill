---
name: justifikasi-pengajuan-doc
description: Create, revise, and validate Indonesian administrative justification documents in Google Docs from requirements, supporting evidence, an existing template, and requested wording or visual references. Use when asked to prepare or update a justifikasi promosi, pengadaan barang dan jasa, permohonan mutasi karyawan, or another formal internal submission while preserving its Google Docs structure.
---

# Justifikasi Pengajuan Doc

Create a decision-ready internal justification while preserving the user's Google Docs structure and keeping personal and organizational data out of reusable skill files.

## Required Inputs

Collect only what is needed for the request:

- the working Google Doc, or a reusable template plus destination folder;
- the submission type, requester, exact purpose, and requested decision;
- authoritative supporting evidence and requirements;
- requested wording, section changes, and any visual reference image.

Use the applicable evidence:

- **Promotion:** candidate CV or work history, role requirement, and documented business need.
- **Procurement:** business need, scope/specification, required quantity or service, budget/timeline only when supplied, and applicable approval requirements.
- **Employee mutation:** current and proposed placement, documented business reason, role context, and applicable approval requirements.

Ask for a missing input only when it materially changes the document. Do not infer a vacancy, resignation, vendor, budget, date, approver, metric, job requirement, or employee detail without a user-provided source.

## Privacy Rules

- Treat names, employers, employee data, email addresses, CV contents, procurement details, document URLs, Drive IDs, folder IDs, screenshots, and approval details as task-local confidential data.
- Never place those values in this skill, bundled resources, example prompts, commit messages, or repository documentation.
- Use generic placeholders only when an example is necessary, such as `[requester]`, `[submission type]`, `[supporting evidence]`, or `[working document]`.
- Do not upload source CVs, screenshots, exports, vendor material, or generated PDFs to the skill repository unless the user explicitly asks.

## Native Google Docs Workflow

1. Use the connected Google Drive and Google Docs skills for live Drive/Docs work. Read their instructions before acting.
2. For a reusable template, create a native copy in the requested destination. For a user-designated working document, edit that document in place.
3. Before the first write to an existing document, run the Google Docs trusted read. Confirm document ID, title, tab ID, revision, protected controls, and the exact target table/cell.
4. Preserve native tabs, headers, footers, tables, lists, person chips, and approval blocks unless the user explicitly asks to change them.
5. Use `get_document_tables` for table edits. Resolve the target table, row, and column from current readback; use a revision guard; then re-read after every index-shifting write.
6. Make the smallest section-sized change. Do not rebuild the document or duplicate a section merely to change one row.

## Content Placement

- Keep the background focused on the documented business reason for the submission.
- Place promotion evidence under competency-and-role fit when that is the intended logic.
- Place procurement scope, operational need, and service/goods justification in the designated procurement sections; do not invent commercial facts.
- Place mutation rationale, current/proposed placement, readiness, and organizational considerations in the designated mutation sections; do not infer personal details.
- Update corrected roles, units, submission titles, or other identifiers consistently across the document only when the user requests a global correction.
- Ground claims in the supplied evidence and use cautious language when evidence supports readiness or need rather than proven outcomes.
- When a user supplies a visual reference for a decision row, reproduce only the requested wording, line breaks, and emphasis in the named current row. Retain the current row number and label unless the user explicitly asks to change them.
- Apply strikethrough, italics, bolding, and blank note space only to the requested ranges. Do not convert them into typed approximations of native controls.

## Validation and Handoff

1. Re-read the settled document and confirm the changed content is in the intended table cell and tab.
2. Verify that unrelated approval names, signatures, tables, and template structure remain unchanged.
3. For table-heavy or layout-sensitive changes, export to PDF, rasterize every page, and inspect for clipping, broken rows, unwanted page breaks, or formatting drift. State plainly if rendered verification is unavailable.
4. Return the working Google Docs link and a concise summary of the completed change. Do not repeat confidential source data in the handoff.
