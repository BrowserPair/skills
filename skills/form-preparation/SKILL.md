---
name: form-preparation
description: Prepare a browser form using user-provided information, validate the visible draft and hand it back for review without assuming submission authority.
---

# Form preparation

## Inputs and applicability

Use when the user asks to prepare or fill a form. Obtain the approved website, purpose and supplied field values. Ask for missing required facts rather than inventing identity, eligibility, consent or financial information.

Required task capabilities: read, navigate and fill. Click or select needs independent task authority when controls require it. Uploads, authentication, payments, publication and submission effects are outside this Skill's default preparation scope.

## Workflow

1. Confirm the current form's origin and purpose from the visible page.
2. Read required fields, constraints and any visible save/autosave behavior before entering information.
3. Match user-provided values to field labels. If a value is sensitive, ensure its entry is authorized for this destination; typing can itself transmit data.
4. Enter a small group of fields and inspect validation feedback.
5. Never select a consent, declaration or legal acceptance on the user's behalf without the required authority.
6. Review the resulting draft, unresolved fields and validation messages.
7. Leave the page ready for review. Summarize the draft without repeating unnecessary sensitive values.

## Verification

Check each required field against its intended meaning, including country, currency, date format and optional checkboxes. State whether the page is a local draft, an autosaved draft or already submitted. Do not infer submission merely from filled fields or a clicked button.

## Recovery and boundaries

If the site autosaves, treat entry as a possible external write and stay within the user's request. Stop if a change is outside preparation scope. After interruption, inspect which values persisted before re-entering them. If a submission outcome is uncertain, check for a confirmation or existing record before any retry.
