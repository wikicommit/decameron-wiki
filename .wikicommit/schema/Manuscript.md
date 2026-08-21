---
wikicommit:
  base: https://schema.org/Manuscript
  provenance: generate-interactive
  granularity:
    - Create a new page for each individual codex or manuscript witness that has its own shelfmark, conventional name, or independent scholarly identity (e.g. an autograph codex, a named illuminated manuscript)
    - Do not create a page for the work the manuscript transmits — that belongs on a [[Book/slug]] or [[ShortStory/slug]] page. This page is about the physical/textual witness, not the work itself; record the work via the about property
    - about names the work the manuscript transmits; write it as a WikiLink when that work has (or should have) its own page, and as plain text otherwise
    - creator names the scribe or copyist; link each copyist who independently qualifies for their own [[Person/slug]] page with a WikiLink, and list others as plain text
    - locationCreated names where the manuscript was written; write it as a WikiLink to [[Place/slug]] when that place independently qualifies for its own page
    - Do not create a separate page for a modern printed critical edition of a work — note it in the body of the work's own page instead
    - Do not invent a shelfmark, a date, or a holding institution the source does not state; leave the property empty and say so in the body if the source is silent
title: ""
type: "schema:Manuscript"
lang: ""
sources: []
tags: []

properties:
  description: ""
  about: "[[Book/slug]]"
  creator: "[[Person/slug]]"
  dateCreated: ""
  locationCreated: "[[Place/slug]]"
---

(2-3 paragraph overview of the manuscript: what work it transmits, who copied it, and why it matters textually)

## Description and History
(shelfmark, holding institution, material and layout as stated by the source; how the manuscript was identified, attributed, or rediscovered)

## Textual Significance
(the manuscript's place in the tradition of the work: authority, relation to other witnesses, use in critical editions)
