# Codex Project Instructions

This repository is the iRizwan personal website. The public website content is
high-risk because it defines the user's professional positioning, search topic
authority, and public credibility.

## Website Page Approval Gate

For any task that changes public website content, navigation, metadata, SEO
positioning, generated root HTML, or anything that affects a rendered page,
Codex must not commit, push, open a pull request, merge, or publish until the
user has read, audited, and explicitly approved each changed page.

This approval must be page by page. A broad approval such as "looks good" or
"approve the site" is not enough unless the user clearly states that every
changed page is approved.

## Required Codex Workflow For Page Changes

1. Make the requested draft changes locally.
2. Build or render the site locally.
3. Identify every public page affected by the change.
4. Present the changed pages to the user one at a time.
5. For each page, provide the local URL, source file, and a concise summary of
   what changed.
6. Ask the user to read and audit that page.
7. Wait for explicit approval for that page before moving to the next page.
8. Do not commit, push, open a PR, merge, or publish until every affected page
   has explicit approval.

## Approval Wording

Acceptable approval wording:

- `Approved: I have read and audited this page for publication.`
- `Approved for this page.`
- `This page is approved.`

If the user gives feedback, make the requested edits, rebuild, and restart the
approval check for that page.

## Content Audit Standard

When asking for approval, Codex must remind the user to check:

- factual accuracy
- whether the wording reflects the user's real experience
- brand correctness: `iRizwan`
- unsupported claims
- placeholder links or placeholder contact details
- whether the page supports the intended search topic
- mobile and desktop readability when relevant

## Hard Stop Conditions

Codex must stop and request page approval if:

- a page has been newly created
- a page heading, definition, roadmap, article idea, or professional claim has
  changed
- metadata or navigation changed in a way that affects search appearance or
  site structure
- generated root files were rebuilt from changed source pages
- the user asks Codex to commit, push, or create a PR before changed pages have
  been approved

## Scope Exception

Purely technical changes that do not affect rendered page content, navigation,
metadata, or public messaging can be committed after normal verification.
