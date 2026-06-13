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

## FDE Content Architecture

The website must use a clear structure for forward deployment engineering
content:

- `/` is the personal homepage for `iRizwan`
- `/fde/` is the main hub page for forward deployment engineering
- `/fde/<child-topic>/` is a focused article on one keyword or concept
- `/fde/<child-topic>/<subtopic>/` is used only when a deeper layer is genuinely needed

The hub page must:

- define forward deployment engineering in plain English
- explain why the topic matters
- show the topic tree with links to the child pages
- give beginners a clear starting point
- include a short personal note connecting the topic to Rizwan and iRizwan

Child pages must:

- own one topic or keyword each
- avoid duplicating the hub page
- avoid combining too many unrelated concepts
- link back to the hub page and to sibling pages where useful

Do not create deeper child pages just to make the tree look larger. Add depth
only when the concept truly needs it and the page can stand on its own.

Preferred FDE child page themes include:

- what forward deployment engineering is
- business analysis in FDE
- data science in FDE
- software engineering in FDE
- cloud deployment in FDE
- beginner roadmap
- related comparisons only when they are actually written

## Article Richness

When writing FDE articles, the writing must be rich, specific, and technical.

Use:

- expert-level terminology where it is accurate and appropriate
- domain-specific language that a serious practitioner would use
- precise technical nouns instead of vague filler words
- concrete concepts, failure modes, tradeoffs, and implementation details

Avoid:

- generic motivational language
- vague filler that could fit any topic
- over-simplified wording when the subject calls for technical depth
- buzzword stuffing or inflated phrasing that is not technically grounded

The rule is not to sound flashy. The rule is to sound informed, exact, and
credible to someone who already understands the domain.
