---
name: GJIC
description: "The advisor's office, taken literally: plaster-white ground, navy wool bands, aluminium hairlines, and the client's documents laid out as white sheets."
colors:
  ground: "#F3F1EC"
  sheet: "#FFFFFF"
  navy: "#15213A"
  navy-deep: "#0F182B"
  navy-line: "#2A3A5C"
  navy-text: "#B9C2D6"
  ink: "#121419"
  ink-2: "#4F545D"
  ink-3: "#62676F"
  rule: "#A9ADB3"
  rule-soft: "#D9D7D1"
  green: "#2F6B4A"
  green-soft: "#E3EEE6"
  error: "#A8392B"
typography:
  display:
    fontFamily: "Schibsted Grotesk, system-ui, -apple-system, Segoe UI, Roboto, sans-serif"
    fontSize: "clamp(2.5rem, 5.4vw, 4.25rem)"
    fontWeight: 700
    lineHeight: 1.02
    letterSpacing: "-0.03em"
  headline:
    fontFamily: "Schibsted Grotesk, system-ui, -apple-system, Segoe UI, Roboto, sans-serif"
    fontSize: "clamp(1.9rem, 3.2vw, 2.75rem)"
    fontWeight: 700
    lineHeight: 1.08
    letterSpacing: "-0.02em"
  title:
    fontFamily: "Schibsted Grotesk, system-ui, -apple-system, Segoe UI, Roboto, sans-serif"
    fontSize: "clamp(1.25rem, 1.6vw, 1.5rem)"
    fontWeight: 700
    lineHeight: 1.2
    letterSpacing: "-0.015em"
  lead:
    fontFamily: "Schibsted Grotesk, system-ui, -apple-system, Segoe UI, Roboto, sans-serif"
    fontSize: "1.25rem"
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: "normal"
  body:
    fontFamily: "Schibsted Grotesk, system-ui, -apple-system, Segoe UI, Roboto, sans-serif"
    fontSize: "1.125rem"
    fontWeight: 400
    lineHeight: 1.55
    letterSpacing: "normal"
  label:
    fontFamily: "Schibsted Grotesk, system-ui, -apple-system, Segoe UI, Roboto, sans-serif"
    fontSize: "1rem"
    fontWeight: 600
    lineHeight: 1.3
    letterSpacing: "normal"
  button:
    fontFamily: "Schibsted Grotesk, system-ui, -apple-system, Segoe UI, Roboto, sans-serif"
    fontSize: "1.0625rem"
    fontWeight: 600
    lineHeight: 1
    letterSpacing: "normal"
  caption:
    fontFamily: "Schibsted Grotesk, system-ui, -apple-system, Segoe UI, Roboto, sans-serif"
    fontSize: "0.9375rem"
    fontWeight: 400
    lineHeight: 1.35
    letterSpacing: "normal"
  figure:
    fontFamily: "Schibsted Grotesk, system-ui, -apple-system, Segoe UI, Roboto, sans-serif"
    fontFeature: "tnum, lnum"
rounded:
  sheet: "2px"
spacing:
  s-1: "4px"
  s-2: "8px"
  s-3: "12px"
  s-4: "16px"
  s-5: "24px"
  s-6: "32px"
  s-7: "48px"
  s-8: "64px"
  s-9: "96px"
  s-10: "128px"
components:
  button-primary:
    backgroundColor: "{colors.navy}"
    textColor: "{colors.sheet}"
    typography: "{typography.button}"
    rounded: "{rounded.sheet}"
    padding: "0 24px"
    height: "52px"
  button-primary-hover:
    backgroundColor: "{colors.navy-deep}"
  button-primary-compact:
    backgroundColor: "{colors.navy}"
    textColor: "{colors.sheet}"
    typography: "{typography.caption}"
    rounded: "{rounded.sheet}"
    padding: "0 16px"
    height: "40px"
  button-light:
    backgroundColor: "{colors.sheet}"
    textColor: "{colors.navy}"
    typography: "{typography.button}"
    rounded: "{rounded.sheet}"
    padding: "0 24px"
    height: "52px"
  button-light-hover:
    backgroundColor: "#E9ECF2"
  button-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    typography: "{typography.button}"
    rounded: "{rounded.sheet}"
    padding: "0 24px"
    height: "52px"
  link-arrow:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    typography: "{typography.label}"
    padding: "0 0 2px"
  nav:
    backgroundColor: "{colors.ground}"
    textColor: "{colors.ink}"
    height: "60px"
  nav-link:
    textColor: "{colors.ink}"
    padding: "8px 0"
  sheet:
    backgroundColor: "{colors.sheet}"
    textColor: "{colors.ink}"
    rounded: "{rounded.sheet}"
    padding: "24px 32px"
  sheet-cell:
    backgroundColor: "{colors.sheet}"
    textColor: "{colors.ink}"
    padding: "16px"
  sheet-cell-recommended:
    backgroundColor: "{colors.green-soft}"
    textColor: "{colors.ink}"
    padding: "16px"
  sheet-total:
    backgroundColor: "#F7F6F2"
    textColor: "{colors.ink}"
    padding: "24px 16px"
  sheet-total-recommended:
    backgroundColor: "#D6E6DB"
    textColor: "{colors.ink}"
    padding: "24px 16px"
  service-row:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    padding: "32px 0"
  step:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    padding: "16px 0 0"
  partner-cell:
    backgroundColor: "{colors.sheet}"
    padding: "24px"
    height: "112px"
  card:
    backgroundColor: "{colors.sheet}"
    textColor: "{colors.ink}"
    rounded: "{rounded.sheet}"
    padding: "24px"
  form-sheet:
    backgroundColor: "{colors.sheet}"
    textColor: "{colors.ink}"
    rounded: "{rounded.sheet}"
    padding: "32px"
  input:
    backgroundColor: "{colors.sheet}"
    textColor: "{colors.ink}"
    rounded: "{rounded.sheet}"
    padding: "12px 14px"
    height: "50px"
  input-invalid:
    backgroundColor: "#FFFBFA"
    textColor: "{colors.ink}"
  chip:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    rounded: "{rounded.sheet}"
    padding: "0 16px"
    height: "40px"
  chip-selected:
    backgroundColor: "{colors.navy}"
    textColor: "{colors.sheet}"
  faq-row:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    padding: "16px 0"
  success-note:
    backgroundColor: "{colors.green-soft}"
    textColor: "{colors.ink}"
    rounded: "{rounded.sheet}"
    padding: "32px"
  navy-band:
    backgroundColor: "{colors.navy}"
    textColor: "{colors.sheet}"
    padding: "128px 0"
---

# Design System: GJIC

## Overview

**Creative North Star: "The Advisor's Desk"**

The site is the advisor's office with the client's documents laid out on the desk. Every material on the page is one that is visible in the founder's portrait, taken literally: the plaster-white wall becomes the page ground, the navy wool of the suit becomes the two bands that hold the comparison sheet and the contact form, the anodised aluminium of the office furniture becomes every hairline rule, and the plant's green appears only where something is covered or better. Documents are drawn as documents: white sheets with 2px corners, 1px hairlines inside them, and one soft shadow that sets them on the desk.

Independence is demonstrated, not claimed. The central object is a real comparison sheet across insurers with tabular figures, and the rest of the page is arranged around it like paperwork: ruled definition rows for services, a numbered hairline column for the process, a grid of hairline cells for the thirteen partner logos, ruled rows for facts and questions. Density is calm and editorial: an 18px body at a 62ch measure, 128px between sections on desktop, headings that tighten as they grow. One typeface, Schibsted Grotesk, carries everything from the 68px headline to the 15px footer line.

The build refuses the category arrangement it replaces: no stock-family hero, no row of icon cards, no stat strip, no testimonial carousel, no gradients, no pills, no small uppercase labels above headings. The only icons are an authored 1.5px-stroke mark set (arrow, menu, close, plus) used inside controls. The only shield on the page is the GJ logo itself.

**Key Characteristics:**
- Plaster-white ground sampled from the portrait wall; navy wool owns whole regions, never tints.
- Documents as white sheets: 2px corners, 1px aluminium hairlines, one soft offset shadow.
- Aluminium hairlines rule every list; the strong rule opens and closes, the soft rule separates.
- Green appears only as the "covered / better" mark.
- One typeface at four weights; tight-tracked bold headings, normal-tracked body, tabular lining figures everywhere a number appears.
- 5/7 and 7/5 split grids that collapse to one column at 860px.

## Colors

The palette is the founder's room: wall, suit, furniture, ink, plant. Nothing is decorative; every colour is a material with a job.

### Primary
- **Navy Wool** (`navy`): the suit, taken as cloth that owns whole regions. It is the background of the desk band that holds the comparison sheet and of the closing contact band, the fill of the primary button and the selected choice chip, the colour of the focus outline, the text selection and the caret, and the colour of the one emphasised link inside the about card. It is never used as a tint, a wash or a hairline on the plaster ground.
- **Navy Wool, Pressed** (`navy-deep`): the primary button's hover fill. It exists for that state only.
- **Navy Seam** (`navy-line`): the hairline used on navy: the 1px top edge of the desk band and the rules between contact-side blocks. On navy, hairlines are navy, not aluminium.
- **Navy Chalk** (`navy-text`): secondary text on navy: section lead paragraphs inside the desk and contact bands, the contact-side body copy. Headings and links on navy are pure document white.

### Secondary
- **Plant Green** (`green`): the plant in the portrait, used only as the semantic "covered / better" mark. It colours the recommended column's header text, the "better" difference figures, the success heading of the sent form, the mobile "Priporočilo GJIC" cell label and the success box's border. It is never a button, a heading colour or decoration.
- **Plant Green, Washed** (`green-soft`): the fill of the recommended column in the comparison sheet and of the form's success box. It only ever sits behind the thing Plant Green marks.

### Tertiary
- **Red Pen** (`error`): the only colour not in the room. It appears exclusively on invalid form fields: the field border and the error message beneath it.

### Neutral
- **Plaster White** (`ground`): the page ground and the sticky nav, sampled from the wall behind the founder. Warm and matte. Everything that is not a document or a navy band sits on plaster.
- **Document White** (`sheet`): the sheets. The comparison sheet, the form, the partner-grid cells, the about card, the inputs and the light button on navy are document white; so is all headline and link text on navy.
- **Near-Black Ink** (`ink`): headings, body text on plaster and on sheets, the ghost button's text and hover border, the nav's active underline.
- **Ink, Diluted** (`ink-2`): secondary text: lead paragraphs, service descriptions, FAQ answers, table headers, meta lines, the hover border of inputs, the masthead's right column.
- **Ink, Faint** (`ink-3`): tertiary text: step counters, placeholders, footnotes, the "same" difference figure, the legal line, the sheet's small notes.
- **Anodised Aluminium** (`rule`): the strong hairline. It opens and closes every ruled list, outlines inputs, ghost buttons, the sample tag and the sheet's head and foot, draws the nav's top edge, underlines plain links and colours the scrollbar thumb.
- **Aluminium, Soft** (`rule-soft`): the soft hairline between rows: service rows, FAQ rows, fact rows, table rows, the partner grid's 1px gaps, the about card's border and the nav's resting bottom edge.

### Named Rules
**The Room Rule.** Every colour is a material visible in the founder's portrait: plaster, navy wool, aluminium, ink, plant. The one exception is Red Pen, and it appears only on an invalid field.

**The Whole-Region Rule.** Navy owns regions and controls: the desk band, the contact band, the primary button, the selected chip, the focus ring. It is never a tint, a wash, a card background or a hairline on the plaster ground.

**The Green Means Better Rule.** Plant Green marks the recommended, covered or confirmed state and nothing else. A screen with no recommendation has no green on it.

## Typography

**Display Font:** Schibsted Grotesk, self-hosted variable 400–900 (with system-ui, -apple-system, Segoe UI, Roboto, sans-serif)
**Body Font:** Schibsted Grotesk (same family)
**Label/Mono Font:** none; figures use tabular lining numerals of the same family

**Character:** A single grotesk doing the whole job of an advisor's paperwork: bold and tightly tracked at display sizes so headlines read as statements, plain and generously leaded at body size so a policyholder can read the whole argument on a phone in one sitting. Weights in use are 400, 500, 600 and 700; nothing is set in uppercase.

### Hierarchy
- **Display** (700, `clamp(2.5rem, 5.4vw, 4.25rem)`, 1.02, -0.03em): the hero headline only; four lines at desktop, balanced wrapping.
- **Headline** (700, `clamp(1.9rem, 3.2vw, 2.75rem)`, 1.08, -0.02em): section headings. On navy they are document white.
- **Title** (700, `clamp(1.25rem, 1.6vw, 1.5rem)`, 1.2, -0.015em): service names, step titles, contact-side headings, the success heading. Step titles and FAQ questions sit at the fixed 1.25rem end of this range; FAQ questions and the about-card name use 600/700 at 1.25rem with -0.01em.
- **Lead** (400, 1.25rem, 1.5, Ink Diluted): the hero paragraph, section-head paragraphs, the about lead (in Near-Black Ink), the FAQ lead. Max width 34em in the hero.
- **Body** (400, 1.125rem, 1.55): the default. Paragraphs are capped at 62ch; FAQ answers at 60ch. Table figures sit at 1.0625rem.
- **Label** (600, 1rem, 1.3): field labels and legends, chip text (400), nav links (500), the sheet's policy names, fact values, the sheet's signature line.
- **Button** (600, 1.0625rem, 1): all buttons; the compact nav button drops to 0.9375rem.
- **Caption** (400, 0.9375rem, 1.35): brand subline, masthead contact, table headers (600), insurer and note lines in the sheet, step timing, error messages, the footer.
- **Figure** (tabular lining numerals): every premium, difference, total, phone number, year and step counter.

### Named Rules
**The One Family Rule.** Schibsted Grotesk is the only typeface. There is no second face for display, no monospace for figures and no system face anywhere; a number that must align uses `font-variant-numeric: tabular-nums lining-nums`.

**The Tightening Rule.** Tracking tightens as size grows: -0.015em at title, -0.02em at headline, -0.03em at display. Body and labels stay at normal tracking, and nothing is set in letter-spaced uppercase.

**The Tabular Figure Rule.** Any number a reader might compare (premiums, differences, totals, years, phone numbers, step counters) is set in tabular lining figures, with a narrow no-break space as the thousands separator (`1 180 €`).

## Layout

The page is a single column of sections on a 1200px container with a 24px gutter on both sides. Inside a section, content is a two-column split on desktop: a 5/7 grid for section heads (heading left, lead right), service rows, the about section and the FAQ; a 7/5 grid for the hero (copy left, portrait right), the desk's closing paragraph and the contact band (form left, details right). Every split collapses to one column at 860px, which is the system's one structural breakpoint.

Vertical rhythm comes from the 4px-based scale (`s-1` 4px to `s-10` 128px). Sections are padded 128px top and bottom on desktop and 96px below 860px; section heads sit 64px above their content (48px on mobile); ruled rows are padded 32px (services) or 16px (FAQ, facts, table cells) vertically. The desk band pads 48px above the sheet and 128px below so the comparison sheet sits high on the navy.

The hero is a 7/5 split aligned to the bottom: the portrait is a full-height photograph (`clamp(440px, 60vh, 600px)`, object-position 50% 20%) that bleeds to the right viewport edge at 1248px and wider and is pulled down by 96px (`s-9`) so its bottom edge rests on the navy desk band that begins the comparison section. Below 860px the portrait becomes a full-bleed 5:6 image pulled down by 64px, and the desk band pads 112px at the top to make room. The masthead (56px logo, brand name and subline, founder name and phone on the right) scrolls away; the nav is sticky at 60px with a strong hairline above and a soft one below, gaining a soft shadow and a strong bottom hairline once stuck.

Dense grids step down by count: steps 5 → 3 → 1 at 1040px and 860px; partner cells 5 → 3 → 2 at 1040px and 560px; the form's two columns become one at 560px; the contact split collapses at 960px; the comparison table turns into stacked two-column cards per policy at 700px, with the column headers hidden and re-rendered as small in-cell labels. The masthead drops the founder name at 640px and its right column entirely at 400px. The page shifts `scroll-padding-top` by the nav height plus 16px so anchor jumps land below the sticky nav.

## Elevation & Depth

Depth is material, not atmospheric. The plaster ground and the navy bands are flat planes; on the plaster, every container is flat and hairlined (the about card, the partner cells, the service and FAQ rows, inputs, ghost buttons). Documents gain depth only when they lie on navy: the comparison sheet, the contact form and the hero portrait carry the one sheet shadow, a soft, negative-spread drop that reads as paper resting on a desk. The sticky nav takes a similar soft shadow only in its stuck state, as a response to scrolling, and the mobile nav panel takes one because it floats over content. Focus is a 2px navy outline offset 3px (white on navy); inputs add a faint navy halo on focus.

### Shadow Vocabulary
- **Sheet** (`box-shadow: 0 18px 40px -18px rgba(15,24,43,.55), 0 2px 6px -2px rgba(15,24,43,.25)`): documents resting on navy: the comparison sheet, the contact form, the hero portrait.
- **Nav, stuck** (`box-shadow: 0 10px 24px -18px rgba(15,24,43,.45)`): the sticky nav once it has left its resting position.
- **Nav panel** (`box-shadow: 0 20px 30px -20px rgba(15,24,43,.5)`): the open mobile menu panel floating over the page.
- **Input focus halo** (`box-shadow: 0 0 0 3px rgba(21,33,58,.18)`): text inputs and textareas on focus, with the border turning navy.

### Named Rules
**The Paper-On-Desk Rule.** Only a document lying on navy casts a shadow. Containers on the plaster ground are flat and drawn with hairlines; the shadow is always soft, navy-tinted and negatively spread, never a hard offset.

**The Hairline Depth Rule.** Hierarchy on a flat plane is drawn with two hairlines: Anodised Aluminium opens and closes a list, Aluminium Soft separates its rows. On navy, the same job is done by Navy Seam.

## Shapes

Everything is rectangular with barely-softened corners: one radius of 2px (`sheet`) on sheets, cards, buttons, inputs, chips, the sample tag, the partner grid, the focus outline and the hero portrait's top-left corner. There are no pills, no circles and no gradients. Borders are 1px hairlines; the nav's active link is a 2px bottom border in ink. The hero portrait is a rectangle that bleeds off the right edge (radius only on the exposed top-left corner, none at all on mobile). The partner grid is a single hairlined rectangle whose cells are separated by 1px gaps of Aluminium Soft showing through, not by individual card borders. Icons are an authored mark set drawn on a 24-unit grid at 1.5px stroke with round caps and joins: a right arrow (buttons and the text link), two-bar menu, close cross and plus (FAQ, rotating 45° to a cross when open). They appear only inside controls, at 16px to 22px.

## Components

Controls feel like the stationery of a careful office: rectangular, hairlined, plainly labelled, with a single soft motion (`cubic-bezier(.16,1,.3,1)`, 200–300ms) on colour and border changes. Reduced motion removes the sheet reveal and the smooth scroll.

### Buttons
- **Shape:** rectangle with 2px corners, 1px border in the fill colour, 52px minimum height, 24px horizontal padding, 12px gap to an 18px arrow icon when one is present.
- **Primary:** Navy Wool fill, document-white text, 600 at 1.0625rem. Used for the two conversion actions (hero, form submit) and the compact nav button (40px high, 16px padding, 0.9375rem).
- **Hover / Focus:** fill and border darken to Navy Wool Pressed; active presses down 1px; focus-visible is the global 2px navy outline offset 3px. Disabled drops to 55% opacity.
- **Light (on navy):** document-white fill, Navy Wool text; hover fill and border shift to a cool off-white (#E9ECF2). Used for the desk band's secondary call to action.
- **Ghost:** transparent fill, Near-Black Ink text, Anodised Aluminium border; hover border turns ink. Reserved for tertiary actions.
- **Text link with arrow:** 600 label, no underline, a 1px Anodised Aluminium bottom border 2px below the text that turns ink on hover while the 16px arrow slides 3px right. Used for the hero's quiet "how it works" link. Plain inline links underline with a 1px aluminium decoration that turns to the text colour on hover.

### Chips
- **Style:** rectangular choice chip, 40px high, 16px horizontal padding, 1px Anodised Aluminium border, 2px corners, 1rem text in ink on transparent; the native checkbox is visually hidden and the chip is its label.
- **State:** hover border turns ink; checked fills Navy Wool with white text and a navy border; focus-visible draws the 2px navy outline on the chip. Multi-select ("Kaj naj pregledam?"), laid out in a wrapping row with 8px gaps.
- **Sample tag:** the sheet's "Vzorčni prikaz" marker is the same vocabulary at rest: aluminium hairline, 2px corners, 4px 10px padding, 600 at 0.9375rem in Ink Diluted.

### Cards / Containers
- **Corner Style:** 2px.
- **Background:** document white on plaster (about card, partner cells, form success box) or on navy (comparison sheet, form).
- **Shadow Strategy:** the sheet shadow only when the container lies on navy; flat on plaster (see Elevation & Depth).
- **Border:** 1px Aluminium Soft on plaster containers; the partner grid is one hairlined rectangle with 1px Aluminium Soft gaps; the success box borders in Plant Green.
- **Internal Padding:** 24px (about card, partner cells, sheet head and foot vertical), 32px (form, sheet head and foot horizontal, success box); 16px on sheet cells.

### Inputs / Fields
- **Style:** 1px Anodised Aluminium border, document-white fill, 2px corners, 12px 14px padding, 50px minimum height, 1.0625rem text in ink, placeholders in Ink Faint. Labels sit above at 600/1rem with an optional 400 hint in Ink Faint; textareas start at 132px and resize vertically. The consent checkbox is native at 20px with navy accent colour.
- **Focus:** border turns Navy Wool with a 3px navy halo at 18% and no outline; hover border turns Ink Diluted.
- **Error / Disabled:** invalid fields take a Red Pen border on a faint warm white (#FFFBFA) and reveal a 0.9375rem Red Pen message below; the form validates on submit and re-validates invalid fields as they change. Success replaces the form body with a Plant Green-bordered, green-washed box carrying a green title.

### Navigation
- **Masthead:** scrolls away. 56px logo, 700/1.25rem brand name with a 0.9375rem subline in Ink Diluted, founder name and phone right-aligned; the logo shrinks to 44px below 640px.
- **Sticky nav:** 60px, Plaster White, strong hairline top, soft hairline bottom; six 500/1rem links with 32px gaps and a transparent 2px bottom border that turns ink on hover and for the current section (set by an intersection observer); a compact primary button at the right. Once stuck it takes the nav shadow and a strong bottom hairline.
- **Mobile (≤860px):** links hide behind a "Meni" toggle with the 22px menu/close marks; the panel drops below the nav on Plaster White with a strong bottom hairline and the panel shadow, listing 600/1.25rem links separated by soft hairlines. Escape and link clicks close it.
- **Footer:** 40px logo, brand lines, a wrapping link list and a soft-hairlined legal line at 0.9375rem in Ink Faint.

### Comparison Sheet
The signature component: one household's policies on a white document resting on the navy desk. Head (24px 32px, strong hairline below) with a 700 title, a meta line and the sample tag; a borderless table at 1.0625rem with 600 table headers in Ink Diluted on a strong hairline, 16px cells separated by soft hairlines, first and last cells padded to 32px. The recommended column is washed Plant Green with a green header and 700 amounts; the difference column is right-aligned 600 and coloured green for better, Ink Faint 500 for unchanged, Ink Diluted 500 for added cover. The total row is 700 on a warm off-white (#F7F6F2) with a deeper green wash (#D6E6DB) under the recommended total. A foot (24px 32px, strong hairline above) carries the one-line conclusion and a 600 signature. On entering the viewport, rows settle in from 8px below at 110ms intervals while recommended amounts count from the current premium to the recommended one over 900ms with a cubic ease-out; reduced motion shows the final state. Below 700px each row becomes a two-column card (policy, then current beside recommended, then the difference) with the headers re-rendered as 0.8125rem in-cell labels.

### Ruled Rows
Services are a definition list: a strong hairline above the list, each row a 5/7 grid (title left, description right) padded 32px vertically and separated by soft hairlines, the last row closed by a strong hairline. The about facts and FAQ use the same grammar at 12px and 16px padding. The FAQ row is a native details element: a 600/1.25rem summary with the 20px plus mark at the right in Ink Diluted, rotating 45° when open, and a 60ch answer in Ink Diluted padded 24px below.

### Step List
Five numbered columns, each opened by a strong hairline, a 700/1rem tabular counter in Ink Faint, 32px of air, a 1.25rem title, a 1.0625rem description and a 0.9375rem timing line in Ink Faint. Below 860px the columns stack into 40px-counter rows separated by soft hairlines and closed by a strong one.

### Partner Grid
Thirteen logos in document-white cells of 112px minimum height (96px on small phones), logos capped at 36px tall and 150px wide, the whole grid one 2px-cornered rectangle with 1px Aluminium Soft gaps; the final cell is a plaster-coloured note spanning two columns.

## Do's and Don'ts

### Do:
- **Do** set body text at 18px/1.55 in Near-Black Ink with a 62ch measure, and lead paragraphs at 20px/1.5 in Ink Diluted.
- **Do** draw every list with hairlines: Anodised Aluminium opens and closes it, Aluminium Soft separates rows (Navy Seam on navy).
- **Do** draw documents as white sheets with 2px corners, 1px hairlines inside, and the sheet shadow only when they lie on navy.
- **Do** give navy whole regions and controls: bands, primary buttons, selected chips, the focus ring.
- **Do** set every comparable number in tabular lining figures with a narrow no-break space before the euro sign.
- **Do** keep controls tall: 52px primary buttons, 50px inputs, 40px chips and compact buttons, 2px navy focus outline offset 3px (white on navy).
- **Do** use the authored 1.5px-stroke mark set (arrow, menu, close, plus) as inline SVG inside controls only, at 16px to 22px.
- **Do** collapse every 5/7 and 7/5 split to one column at 860px and honour `prefers-reduced-motion` by showing final states.

### Don't:
- **Don't** add a second typeface, a monospace face or a system face; Schibsted Grotesk at 400–700 is the whole system.
- **Don't** set small uppercase, letter-spaced labels above headings; section heads are a headline beside a lead paragraph.
- **Don't** use pills, circles or any radius other than 2px; don't use gradients anywhere.
- **Don't** use green for buttons, headings or decoration; it marks the recommended or covered state only.
- **Don't** tint the plaster ground with navy or put a navy hairline on it; navy hairlines belong on navy.
- **Don't** cast shadows from containers on the plaster ground, and don't use hard offset shadows; the only shadow is the soft sheet shadow on navy.
- **Don't** lay out services, benefits or steps as rows of identical icon cards; use ruled rows or hairline-opened numbered columns.
- **Don't** add shield or protection imagery; the GJ logo is the only shield on the page.
