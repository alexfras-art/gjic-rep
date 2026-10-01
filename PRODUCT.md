# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Stack

static HTML/CSS/JS, single `index.html` with everything inlined (brief-pinned). No backend, framework, build step, form submission, analytics or integrations. Opened directly from disk, later hosted as a static page.

## Users

Individuals, families and small/medium businesses in Slovenia who already hold insurance policies (home, car, life, health, business) and suspect they are overpaying, under-covered, or will be alone when a claim happens. The scene (inferred from brief): a renewal notice or an unsatisfying claim experience prompts them to look for an advisor who is not an insurer's salesperson. They read in Slovenian, mostly on a phone, often in the evening.

## Product Purpose

GJIC (GJ Insurance Consulting) advises clients on insurance independently of any single insurer. It reviews what a client already has, compares offers across insurers, removes unnecessary cost, and stands by the client when a claim happens. The site exists so a prospective client understands the independent-advisor model, trusts the person behind it, and gets in touch. Success is a contact request (inferred: the brief names no other conversion).

## Positioning

Independence: GJIC works across 13 partner insurers (Slovenian and Austrian) and is paid to serve the client, not to sell one insurer's product. An insurer's own agent cannot truthfully copy "we compare everyone, including our competitors, and we stay on your side at claim time".

## Operating Context

The advisor's work products are real documents: the client's existing policies, a comparison of offers across insurers, a cost-reduction summary, and the claims file when something happens. Clients evaluate the service by whether the comparison is honest, the savings are concrete and the advisor shows up at the claim.

## Capabilities and Constraints

- Language: Slovenian (brief-pinned).
- Phone and desktop must both work (brief-pinned).
- Header: the logo scrolls away with the page; the navigation controls stay fixed (brief-pinned).
- No invented shield or protection-cliché iconography; the client's logo is the only shield on the page (brief-pinned).
- Avoid: small uppercase labels above headings, scattered tiny captions, rows of identical icon cards (brief-pinned).
- Contact form must look and behave correctly on the frontend only; no submission (brief-pinned).
- Undecided / unknown facts (use labelled demo placeholders, never present as real): figures, address, phone, email, years of experience, licence numbers, client names.

## Brand Commitments

- Name: GJIC, long form "GJ Insurance Consulting". Founder: Jaka Gerencer.
- Voice: trustworthy, calm, competent; a professional advisor, not a sales page (brief-pinned).
- Logo: monochrome "GJ" shield, `assets/brand/gj-logo.png` (512px, transparent, black/grey ink).
- Portrait: `assets/owner/jaka-gerencer.png` (1254px square; navy suit, white shirt, neutral office wall, plant). Shrink before inlining.
- Partner insurer logos (13, coloured, for light backgrounds): `assets/partners/*.png` — Allianz, ARAG, Avrio, Dr Best, Generali, GRAWE, Groupama, Merkur, Prva, Sava, Triglav, Vzajemna, Wiener Städtische.

## Evidence on Hand

- The 13 partner logos (real).
- The founder's portrait and the company logo (real).
- No testimonials, case studies, savings figures, client counts or press exist in the repo. Any such content on the page is demo material and must be marked as such in the handoff; commercial claims are not to be invented as fact.

## Product Principles

1. Independence is the product: every section should make the "we compare across insurers for you" mechanism concrete, not merely state it.
2. Show the work: the comparison, the review, the claim support are documents and processes; depict them rather than symbolising them.
3. One person carries the trust: Jaka Gerencer is the advisor the client will actually meet; the page should feel like meeting him.
4. Calm over persuasion pressure: no urgency devices, no hype numbers, no gamified proof.
5. Mobile first in practice: the whole argument must read on a phone in one evening sitting.

## Accessibility & Inclusion

Slovenian-language readers of all ages, including older policyholders: comfortable body size, high contrast, large touch targets, keyboard-operable navigation and form.
