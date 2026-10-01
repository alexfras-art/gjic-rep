---
name: GJIC
description: "The advisor's office, taken literally: plaster-white ground, navy wool bands, aluminium hairlines, and the client's documents laid out as white sheets."
colors:
  ground: "#F3F1EC"
  sheet: "#FFFFFF"
  sheet-tint: "#F7F6F2"
  sheet-hover: "#E9ECF2"
  navy: "#15213A"
  navy-deep: "#0F182B"
  navy-line: "#2A3A5C"
  navy-text: "#B9C2D6"
  on-navy: "#FFFFFF"
  ink: "#121419"
  ink-2: "#4F545D"
  ink-3: "#62676F"
  rule: "#A9ADB3"
  rule-soft: "#D9D7D1"
  control: "#80858D"
  green: "#2F6B4A"
  green-soft: "#E3EEE6"
  green-mid: "#D6E6DB"
  error: "#A8392B"
  error-tint: "#FFFBFA"
typography:
  display:
    fontFamily: "Schibsted Grotesk, Schibsted Fallback, Arial, sans-serif"
    fontSize: "min(clamp(2.5rem, 5.4vw, 4.25rem), 11.5vw)"
    fontWeight: 700
    lineHeight: 1.02
    letterSpacing: "-0.03em"
  headline:
    fontFamily: "Schibsted Grotesk, Schibsted Fallback, Arial, sans-serif"
    fontSize: "clamp(1.9rem, 3.2vw, 2.75rem)"
    fontWeight: 700
    lineHeight: 1.08
    letterSpacing: "-0.02em"
  title:
    fontFamily: "Schibsted Grotesk, Schibsted Fallback, Arial, sans-serif"
    fontSize: "clamp(1.25rem, 1.6vw, 1.5rem)"
    fontWeight: 700
    lineHeight: 1.2
    letterSpacing: "-0.015em"
  promise:
    fontFamily: "Schibsted Grotesk, Schibsted Fallback, Arial, sans-serif"
    fontSize: "1.375rem"
    fontWeight: 600
    lineHeight: 1.3
    letterSpacing: "-0.01em"
  lead:
    fontFamily: "Schibsted Grotesk, Schibsted Fallback, Arial, sans-serif"
    fontSize: "1.25rem"
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: "normal"
  body:
    fontFamily: "Schibsted Grotesk, Schibsted Fallback, Arial, sans-serif"
    fontSize: "1.125rem"
    fontWeight: 400
    lineHeight: 1.55
    letterSpacing: "normal"
  label:
    fontFamily: "Schibsted Grotesk, Schibsted Fallback, Arial, sans-serif"
    fontSize: "1rem"
    fontWeight: 600
    lineHeight: 1.3
    letterSpacing: "normal"
  button:
    fontFamily: "Schibsted Grotesk, Schibsted Fallback, Arial, sans-serif"
    fontSize: "1.0625rem"
    fontWeight: 600
    lineHeight: 1.15
    letterSpacing: "normal"
  caption:
    fontFamily: "Schibsted Grotesk, Schibsted Fallback, Arial, sans-serif"
    fontSize: "0.9375rem"
    fontWeight: 400
    lineHeight: 1.35
    letterSpacing: "normal"
  figure:
    fontFamily: "Schibsted Grotesk, Schibsted Fallback, Arial, sans-serif"
    fontFeature: "tnum, lnum"
rounded:
  sheet: "2px"
spacing:
  s-0: "2px"
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
    textColor: "{colors.on-navy}"
    typography: "{typography.button}"
    rounded: "{rounded.sheet}"
    padding: "8px 24px"
    height: "52px"
  button-primary-hover:
    backgroundColor: "{colors.navy-deep}"
  button-primary-compact:
    backgroundColor: "{colors.navy}"
    textColor: "{colors.on-navy}"
    typography: "{typography.caption}"
    rounded: "{rounded.sheet}"
    padding: "4px 16px"
    height: "44px"
  button-light:
    backgroundColor: "{colors.sheet}"
    textColor: "{colors.navy}"
    typography: "{typography.button}"
    rounded: "{rounded.sheet}"
    padding: "8px 24px"
    height: "52px"
  button-light-hover:
    backgroundColor: "{colors.sheet-hover}"
  button-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    typography: "{typography.button}"
    rounded: "{rounded.sheet}"
    padding: "8px 24px"
    height: "52px"
  link-arrow:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    typography: "{typography.label}"
    padding: "19px 0 2px"
  nav:
    backgroundColor: "{colors.ground}"
    textColor: "{colors.ink}"
    height: "60px"
  nav-link:
    textColor: "{colors.ink}"
    height: "44px"
  nav-panel:
    backgroundColor: "{colors.ground}"
    textColor: "{colors.ink}"
    padding: "12px 24px 24px"
  nav-panel-link:
    textColor: "{colors.ink}"
    padding: "16px 0"
  nav-panel-tel:
    textColor: "{colors.navy}"
    padding: "16px 0"
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
    backgroundColor: "{colors.sheet-tint}"
    textColor: "{colors.ink}"
    padding: "24px 16px"
  sheet-total-recommended:
    backgroundColor: "{colors.green-mid}"
    textColor: "{colors.ink}"
    padding: "24px 16px"
  sample-tag:
    backgroundColor: "{colors.rule-soft}"
    textColor: "{colors.ink-2}"
    typography: "{typography.caption}"
    rounded: "{rounded.sheet}"
    padding: "4px 12px"
  sample-tag-on-navy:
    backgroundColor: "{colors.navy-line}"
    textColor: "{colors.navy-text}"
    typography: "{typography.caption}"
    rounded: "{rounded.sheet}"
    padding: "4px 12px"
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
  partner-note:
    backgroundColor: "{colors.ground}"
    textColor: "{colors.ink-2}"
    padding: "24px"
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
    padding: "12px 16px"
    height: "50px"
  input-invalid:
    backgroundColor: "{colors.error-tint}"
    textColor: "{colors.ink}"
  chip:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    rounded: "{rounded.sheet}"
    padding: "0 12px"
    height: "44px"
  chip-selected:
    backgroundColor: "{colors.navy}"
    textColor: "{colors.on-navy}"
  faq-row:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    padding: "16px 0"
  success-note:
    backgroundColor: "{colors.green-soft}"
    textColor: "{colors.ink}"
    rounded: "{rounded.sheet}"
    padding: "32px"
  success-tel:
    backgroundColor: "transparent"
    textColor: "{colors.navy}"
    typography: "{typography.title}"
    height: "44px"
  navy-band:
    backgroundColor: "{colors.navy}"
    textColor: "{colors.on-navy}"
    padding: "128px 0"
---

# Design System: GJIC

## Overview

**Creative North Star: "The Advisor's Desk"**

The site is the advisor's office with the client's documents laid out on the desk. Every material on the page is one that is visible in the founder's portrait, taken literally: the plaster wall, lifted a few tones toward white, becomes the page ground, the navy wool of the suit becomes the two bands that hold the comparison sheet and the contact form, the anodised aluminium of the office furniture becomes every hairline rule, and the plant's green appears only where something is covered or better. Documents are drawn as documents: white sheets with 2px corners, 1px hairlines inside them, and one soft shadow that sets them on the desk.

Independence is demonstrated, not claimed. The central object is a real comparison sheet across insurers with tabular figures, and the rest of the page is arranged around it like paperwork: ruled definition rows for services, a numbered hairline column for the process, a grid of hairline cells for the thirteen partner logos, ruled rows for facts and questions. Density is calm and editorial: an 18px body at a 62ch measure, 96px between sections on desktop, headings that tighten as they grow. One typeface, Schibsted Grotesk, carries everything from the 68px headline to the 15px footer line.

The build refuses the category arrangement it replaces: no stock-family hero, no row of icon cards, no stat strip, no testimonial carousel, no gradients, no pills, no small uppercase labels above headings. The only icons are an authored 1.5px-stroke mark set (arrow, menu, close, plus, phone) used inside controls. The only shield on the page is the GJ logo itself. Wherever the page shows invented data (the sample sheet, the facts list, the office address) it says so with one filled sample tag, so the demonstration never passes for a record.

**Key Characteristics:**
- Plaster-white ground lightened from the warm wall tone beside the founder; navy wool owns whole regions, never tints.
- Documents as white sheets: 2px corners, 1px aluminium hairlines, one soft offset shadow.
- Aluminium hairlines rule every list; the strong rule opens and closes, the soft rule separates; controls are outlined in the darker Control Grey.
- Green appears only as the "covered / better" mark.
- One typeface at four weights; tight-tracked bold headings, normal-tracked body, tabular lining figures everywhere a number appears.
- 5/7 and 7/5 split grids that collapse to one column at 860px.
- Every control at least 44px tall; the 2px focus ring follows its surface (navy on plaster and white, white on navy).
- One filled sample tag marks every piece of invented data: the sheet badge, the facts list, the office block.

## Colors

The palette is the founder's room: wall, suit, furniture, ink, plant. Nothing is decorative; every colour is a material with a job.

### Primary
- **Navy Wool** (`navy`): the suit, taken as cloth that owns whole regions. It is the background of the desk band that holds the comparison sheet and of the closing contact band, the fill of the primary button and the selected choice chip, the colour of the focus outline, the text selection and the caret, the mobile panel's phone row and current link, the colour of the one emphasised link inside the about card and of the success card's phone link. It is never used as a tint, a wash or a hairline on the plaster ground.
- **Navy Wool, Pressed** (`navy-deep`): the primary button's hover fill. It exists for that state only.
- **Navy Seam** (`navy-line`): the hairline used on navy: the 1px top edge of the desk band and the rules between contact-side blocks; also the fill of the sample tag on navy. On navy, hairlines are navy, not aluminium.
- **Navy Chalk** (`navy-text`): secondary text on navy: section lead paragraphs inside the desk and contact bands, the two muted paragraphs under the comparison sheet, the contact-side body copy, and the text of the sample tag on navy, which sits on a Navy Seam fill so the tag reads as one tone on the wool. Headings, links and the promise sentence on navy are Document White, on Navy.

### Secondary
- **Plant Green** (`green`): the plant in the portrait, used only as the semantic "covered / better" mark. It colours the recommended column's header text, the "better" difference figures, the success heading of the sent form, the mobile "Priporočilo GJIC" cell label and the success card's border. It is never a button, a heading colour or decoration.
- **Plant Green, Washed** (`green-soft`): the fill of the recommended column in the comparison sheet and of the form's success card. It only ever sits behind the thing Plant Green marks.
- **Plant Green, Deeper Wash** (`green-mid`): the recommended total cell in the sheet's foot row, one step deeper than the column above it so the total reads as the sum.

### Tertiary
- **Red Pen** (`error`): the only colour not in the room. It appears exclusively on invalid form fields: the field border (kept even while the field is focused), the error message beneath it, the 2px ring around an unchecked consent box, and the outer band of the double halo that box shows when it is both invalid and focused.
- **Red Pen, Faint** (`error-tint`): the warm near-white fill of an invalid field, so the red border is read as a correction on the page rather than a filled box.

### Neutral
- **Plaster White** (`ground`): the page ground, the sticky nav and its mobile panel, and the partner grid's note cell. It is a lightened derivation of the warm wall tone beside the founder, not the wall as sampled: the plaster at the right of his head reads around #D8D4CD, and the ground lifts that tone toward white so the portrait's wall and the page read as the same plaster in different light. Warm and matte. Everything that is not a document or a navy band sits on plaster.
- **Document White** (`sheet`): the sheets. The comparison sheet, the form, the partner-grid cells, the about card, the inputs and the light button on navy are document white; it is also the inner band of the consent checkbox's error halo, separating the navy ring from the red.
- **Document White, on Navy** (`on-navy`): the same white as its own token for everything that sits directly on navy wool: headline, link and promise text in the desk and contact bands, the primary button's and the selected chip's text, text selection, the skip link, and the focus ring on navy surfaces. Keeping it separate lets the focus ring switch colour with the surface.
- **Document White, Toned** (`sheet-tint`): the warm off-white of the comparison sheet's total row, one tone off the sheet so the sum is a band and not a border.
- **Document White, Cool** (`sheet-hover`): the light button's hover fill on navy, a cool off-white that reads as pressed paper.
- **Near-Black Ink** (`ink`): headings, body text on plaster and on sheets, the ghost button's text and hover border, the nav's active underline, the hover border of chips.
- **Ink, Diluted** (`ink-2`): secondary text: lead paragraphs, service descriptions, FAQ answers, table headers, meta lines, the form's intro sentence, the hover border of inputs, the masthead's right column, the partner note, the sample tags on white and plaster, and the ghost button's border when it sits on the green success card.
- **Ink, Faint** (`ink-3`): tertiary text: step counters, placeholders, footnotes, the "same" difference figure, the legal line, the sheet's small notes.
- **Anodised Aluminium** (`rule`): the strong hairline. It opens and closes every ruled list, outlines the sheet's head and foot and the mobile panel's bottom edge, draws the nav's top edge, underlines the arrow link, and colours the scrollbar thumb.
- **Aluminium, Soft** (`rule-soft`): the soft hairline between rows: service rows, FAQ rows, fact rows, table rows, the mobile panel's rows, the partner grid's 1px gaps, the about card's border and the nav's resting bottom edge; also the fill of the sample tag on white and plaster, the one place it is a surface rather than a line.
- **Control Grey** (`control`): the edge of anything the reader can type into or press: text inputs and textareas, choice chips and the ghost button; also the 1px underline of plain links in prose. Darker than the list hairlines so a control's outline holds at least 3:1 against document white.

### Named Rules
**The Room Rule.** Every colour derives from a material visible in the founder's portrait: plaster (the wall tone, lightened), navy wool, aluminium, ink, plant. The one exception is Red Pen, and it appears only on an invalid field.

**The Whole-Region Rule.** Navy owns regions and controls: the desk band, the contact band, the primary button, the selected chip, the focus ring. It is never a tint, a wash, a card background or a hairline on the plaster ground.

**The Green Means Better Rule.** Plant Green marks the recommended, covered or confirmed state and nothing else. A screen with no recommendation has no green on it.

## Typography

**Display Font:** Schibsted Grotesk, self-hosted variable 400–900 (with Schibsted Fallback, Arial, sans-serif)
**Body Font:** Schibsted Grotesk (same family)
**Label/Mono Font:** none; figures use tabular lining numerals of the same family

**Character:** A single grotesk doing the whole job of an advisor's paperwork: bold and tightly tracked at display sizes so headlines read as statements, plain and generously leaded at body size so a policyholder can read the whole argument on a phone in one sitting. Weights in use are 400, 500, 600 and 700; nothing is set in uppercase.

**Loading:** Both inlined Schibsted Grotesk faces (400–900, normal) load with `font-display: block`. Behind them sit three Schibsted Fallback faces, one per weight band, each a metric-matched local face: 400–500 maps to the regular locals (`local("Arial")`, `local("Liberation Sans")`, `local("Helvetica Neue")`, `local("Helvetica")`) with `size-adjust: 104.2%`, `ascent-override: 93.7%` and `descent-override: 24.7%`; 600 maps to the bold locals (`local("Arial Bold")`, `local("Arial-BoldMT")`, `local("Liberation Sans Bold")`, `local("Helvetica Neue Bold")`, `local("Helvetica-Bold")`) with `size-adjust: 100.3%`, `ascent-override: 97.3%` and `descent-override: 25.7%`; 700–900 maps to the same bold locals with `size-adjust: 102.5%`, `ascent-override: 95.3%` and `descent-override: 25.2%`. All three set `line-gap-override: 0%`. Every weight the page uses (400, 500, 600, 700) is therefore covered by a face matched to it; the build measured the swap at a layout shift of 0.0001. The block period means no visible fallback flash; the overrides mean the fallback fills the same lines as the grotesk, so there is no layout shift when it arrives. The body stack is `"Schibsted Grotesk", "Schibsted Fallback", Arial, sans-serif`.

### Hierarchy
- **Display** (700, `min(clamp(2.5rem, 5.4vw, 4.25rem), 11.5vw)`, 1.02, -0.03em): the hero headline only; four lines at desktop, balanced wrapping. The outer `min()` keeps the headline under the viewport on narrow phones, and `hyphens: auto` with `overflow-wrap: anywhere` are the last resorts so a long Slovene word never pushes past the edge; every heading from h1 to h4 carries the same two last resorts.
- **Headline** (700, `clamp(1.9rem, 3.2vw, 2.75rem)`, 1.08, -0.02em): section headings. On navy they are Document White, on Navy.
- **Title** (700, `clamp(1.25rem, 1.6vw, 1.5rem)`, 1.2, -0.015em): service names, step titles, contact-side headings, the success heading. Step titles and FAQ questions sit at the fixed 1.25rem end of this range; FAQ questions, the about-card name, the mobile panel's links and the success card's navy phone link use 600/700 at 1.25rem with -0.01em. The contact aside's phone link is 700 at `min(1.5rem, 8vw)` with -0.01em so it never overflows a narrow phone.
- **Promise** (600, 1.375rem, 1.3, -0.01em, Document White, on Navy): the one white sentence under the comparison sheet, capped at 26em, that precedes two Navy Chalk paragraphs and the light button. It is the only text between lead and headline size, and it exists for that single sentence.
- **Lead** (400, 1.25rem, 1.5, Ink Diluted): the hero paragraph, section-head paragraphs, the about lead (in Near-Black Ink), the FAQ lead. Max width 34em in the hero.
- **Body** (400, 1.125rem, 1.55): the default. Paragraphs are capped at 62ch; FAQ answers at 60ch. Table figures sit at 1.0625rem (1rem under 860px). Paragraphs, list items, definitions, addresses, FAQ summaries, the about card's mail link, the consent text and the contact-side links carry `overflow-wrap: anywhere` as a last resort.
- **Label** (600, 1rem, 1.3): field labels and legends, chip text (500), nav links (500), the form's intro sentence (400, Ink Diluted), the steps' timing lines (400, Ink Faint), the sheet's policy names, fact values, the sheet's signature line.
- **Button** (600, 1.0625rem, 1.15): all buttons; the compact nav button drops to 0.9375rem, and below 560px every button drops to 1rem. The 1.15 line-height is what lets a label that wraps under enlarged text keep its box.
- **Caption** (400, 0.9375rem, 1.35): brand subline, masthead contact, table headers (600), insurer and note lines in the sheet, the mobile sheet's generated column labels (600), error messages, the sample tags (500), the footer. It is the smallest size on the page.
- **Figure** (tabular lining numerals): every premium, difference, total, phone number, year and step counter.

### Named Rules
**The One Family Rule.** Schibsted Grotesk is the only typeface the reader sees. There is no second face for display, no monospace for figures and no system face in the design; the metric-matched Schibsted Fallback exists only to hold the lines while the grotesk loads. A number that must align uses `font-variant-numeric: tabular-nums lining-nums`.

**The Tightening Rule.** Tracking tightens as size grows: -0.015em at title, -0.02em at headline, -0.03em at display. Body and labels stay at normal tracking, and nothing is set in letter-spaced uppercase.

**The Tabular Figure Rule.** Any number a reader might compare (premiums, differences, totals, years, phone numbers, step counters) is set in tabular lining figures, with a narrow no-break space as the thousands separator (`1 180 €`).

## Layout

The page is a single column of sections on a 1200px container with a 24px gutter on both sides. Inside a section, content is a two-column split on desktop: a 5/7 grid for section heads (heading left, lead right), service rows, the about section and the FAQ; a 7/5 grid for the hero (copy left, portrait right), the desk's closing paragraphs and the contact band (form left, details right). Every split collapses to one column at 860px, which is the system's one structural breakpoint.

Vertical rhythm comes from the 4px-based scale (`s-1` 4px to `s-10` 128px, with `s-0` 2px as the optical step between a line and its subline). Sections are padded 96px top and bottom on desktop and 64px below 860px; section heads sit 64px above their content (48px on mobile); ruled rows are padded 32px (services; 24px on mobile), 16px (FAQ, table cells) or 12px (facts) vertically. The two navy bands keep the larger rhythm: the desk band pads 48px above the sheet and 128px below so the comparison sheet sits high on the navy, and the contact band pads 128px top and bottom.

The hero is a 7/5 split aligned to the bottom: the portrait is a full-height photograph (`clamp(440px, 60vh, 600px)`, object-position 50% 20%) that bleeds to the right viewport edge at 1248px and wider and is pulled down by 96px (`s-9`) so its bottom edge rests on the navy desk band that begins the comparison section. The hero clips horizontally (`overflow-x: clip`) so the bleed ends at the viewport edge and never widens the page. The actions row reserves 52px (`min-height`) so the headline does not jump when the button renders; below 1100px the hero grid gap tightens to 32px and the actions stack as a column (button first, then the text link) aligned to the start with a 16px gap. Below 860px the portrait becomes a full-bleed 5:6 image capped at 58vh, pulled down by 64px (`s-8`), and the desk band pads 112px at the top to make room. Below 560px every button drops to 1rem with 16px side padding; the stacked hero actions stretch to the full width with a 24px gap, the hero and desk buttons fill it (the hero button at 56px tall) with the arrow pushed to the far end while the text link keeps its own width; below 360px the hero and submit buttons drop their arrows and the about card wraps, its 88px portrait above the name. The masthead (56px logo beside the brand name and subline stacked as blocks, founder name and phone on the right, the row wrapping so the phone never collides with the brand) scrolls away; the nav is sticky at a 60px minimum with a strong hairline above and a soft one below, gaining a soft shadow and a strong bottom hairline once stuck. Its row wraps under enlarged text rather than overflowing, and the compact button keeps the right edge (`margin-left: auto`); under 480px the bar never wraps: the toggle keeps its content width and the compact button yields, shrinking, wrapping its label and breaking a word if it must.

Dense grids step down by count: the five process columns become one ruled list at 1040px; partner cells 5 → 3 → 2 at 1040px and 560px; the form's two columns become one at 560px; the contact split (whose children have `min-width: 0`, so the form and the aside can shrink below their content) collapses at 960px; the comparison table turns into stacked two-column cards per policy at 700px, with the column headers hidden and re-rendered as small in-cell labels. At 640px the masthead compacts: the logo shrinks to 44px, the brand name to 1.0625rem, and the founder name hides; under 480px the long name and subline give way to the short "GJIC" mark (700, 1.125rem), which is hidden at every wider width, and the founder name returns at 1rem. The phone number stays at every width. The page shifts `scroll-padding-top` by the nav's measured height plus 16px (a ResizeObserver writes the bar's height to `--nav-measured`; the 60px `--nav-h` is the fallback) so anchor jumps land below the sticky nav whatever height it takes. The scrollbar keeps the OS default width and is only coloured (`scrollbar-color`: Anodised Aluminium thumb on the plaster track), so older readers keep the grab area they know.

## Elevation & Depth

Depth is material, not atmospheric. The plaster ground and the navy bands are flat planes; on the plaster, every container is flat and hairlined (the about card, the partner cells, the service and FAQ rows, inputs, ghost buttons). Documents gain depth only when they lie on navy: the comparison sheet, the contact form and the hero portrait carry the one sheet shadow, a soft, negative-spread drop that reads as paper resting on a desk. The sticky nav takes a similar soft shadow only in its stuck state, as a response to scrolling, and the mobile nav panel takes one because it floats over content. Focus is a 2px outline with 2px corners (the one radius token): navy on plaster and on white, white on navy surfaces, and navy again inside a white sheet or form that lies on navy. The offset is 3px on buttons, links, chips and summaries, 2px on text inputs, the textarea and the consent checkbox, where the ring hugs the control's own border while that border turns navy, and 3px inside the comparison sheet's table region, which draws its ring inward because the sheet clips its contents; an invalid text input keeps its Red Pen border under the navy ring. There is no halo, with one exception: the consent checkbox, whose native box has no border to turn red, carries its invalid state while focused as a double band outside the navy ring (`box-shadow: 0 0 0 5px` Document White, `0 0 0 7px` Red Pen), so the error and the focus are both visible at once. Under forced colours, checked chips take the system Highlight fill and border with a 3px Highlight outline, the nav's transparent underline disappears except on the current link, the mobile panel's current link keeps its mark as a 3px Highlight left border, and every button gains a ButtonText border; the forced-colours block closes the stylesheet so it wins the cascade.

### Shadow Vocabulary
- **Sheet** (`--shadow-sheet`, `box-shadow: 0 18px 40px -18px rgba(15,24,43,.55), 0 2px 6px -2px rgba(15,24,43,.25)`): documents resting on navy: the comparison sheet, the contact form, the hero portrait.
- **Nav, stuck** (`--shadow-nav`, `box-shadow: 0 10px 24px -18px rgba(15,24,43,.45)`): the sticky nav once it has left its resting position.
- **Nav panel** (`--shadow-panel`, `box-shadow: 0 20px 30px -20px rgba(15,24,43,.5)`): the open mobile menu panel floating over the page.

### Named Rules
**The Paper-On-Desk Rule.** Only a document lying on navy casts a shadow. Containers on the plaster ground are flat and drawn with hairlines; the shadow is always soft, navy-tinted and negatively spread, never a hard offset.

**The Hairline Depth Rule.** Hierarchy on a flat plane is drawn with two hairlines: Anodised Aluminium opens and closes a list, Aluminium Soft separates its rows. A control's edge (input, chip, ghost button) is the darker Control Grey so it holds 3:1 on white. On navy, list hairlines are Navy Seam. The sample tag is the one label that is filled rather than outlined: Aluminium Soft on white and plaster, Navy Seam on navy, with no border on either.

**The Ring Follows the Surface Rule.** The focus ring is always a 2px outline with 2px corners, offset 3px on buttons, links, chips and summaries, 2px on text inputs, the textarea and the consent checkbox, and 3px inward on the sheet's table region, which clips; its colour is the ink of its surface: navy on plaster and on white sheets, white directly on navy, and navy again inside a white sheet that lies on navy. There is no halo, except the white-then-red double band that keeps an invalid consent checkbox's error visible while it is focused.

## Shapes

Everything is rectangular with barely-softened corners: one radius of 2px (`sheet`) on sheets, cards, buttons, inputs, chips, the sample tag, the partner grid, the focus outline, the mobile sheet's recommended cell and the hero portrait's top-left corner. There are no pills, no circles and no gradients. Borders are 1px hairlines; the nav's active link is a 2px bottom border in ink, and the mobile panel's current link a 3px navy bar inset at its left edge. The hero portrait is a rectangle that bleeds off the right edge (radius only on the exposed top-left corner, none at all on mobile), and the hero clips it at the viewport. The comparison sheet clips its own contents (`overflow: clip`) so its rounded edge holds; inside it, the table region is the one place on the page that may scroll horizontally, and the open mobile panel the one place that scrolls vertically on its own. The partner grid is a single hairlined rectangle whose cells are separated by 1px gaps of Aluminium Soft showing through, not by individual card borders. Icons are an authored mark set drawn on a 24-unit grid at 1.5px stroke with round caps and joins: a right arrow (buttons and the text link), two-bar menu, close cross, plus (FAQ, rotating 45° to a cross when open) and a phone handset (the mobile panel's call row). They appear only inside controls, at 16px to 22px.

## Components

Controls feel like the stationery of a careful office: rectangular, outlined in Control Grey, plainly labelled, with a single soft motion (`cubic-bezier(.16,1,.3,1)`, 200–300ms) on colour and border changes. Every control is at least 44px tall: 52px buttons, 50px inputs, 44px chips, the 44px nav links, nav toggle and compact nav button, and a 44px minimum height on every link that acts as a control (the masthead, contact and success-card phone numbers, the about card's e-mail, the footer links). Buttons pad 8px vertically with a 1.15 line-height, so a label that wraps under enlarged text keeps its box instead of overflowing it. Reduced motion removes the sheet reveal and the smooth scroll, the button press, the arrow link's slide and the transition on the FAQ mark's rotation, leaving buttons their colour transitions only; forced colours keep every state legible with system Highlight and ButtonText.

### Buttons
- **Shape:** rectangle with 2px corners, 1px border in the fill colour, 52px minimum height, 8px vertical and 24px horizontal padding, 1.15 line-height, `overflow-wrap: anywhere` as a last resort for a long label, 12px gap to an 18px arrow icon when one is present. Below 560px every button drops to 1rem with 16px side padding; the hero and desk buttons stretch to the full width with the arrow at the far end (the hero button at 56px tall), and below 360px the hero and submit buttons hide their arrows.
- **Primary:** Navy Wool fill, Document White, on Navy text, 600 at 1.0625rem. Used for the two conversion actions (the hero's "Naročite pregled polic", the form submit "Pošljite povpraševanje") and the compact nav button "Naročite pregled" (44px high, 4px 16px padding, 0.9375rem, held at the right of the nav row with `margin-left: auto`; under 480px it yields to the toggle: it may shrink, wrap its label at a 1.1 line-height, break a word if it must and pad 12px at the sides so the bar never wraps).
- **Hover / Focus:** fill and border darken to Navy Wool Pressed; active presses down 1px (not under reduced motion); focus-visible is the 2px outline offset 3px in the surface's ring colour. Disabled drops to 55% opacity.
- **Light (on navy):** document-white fill, Navy Wool text; hover fill and border shift to Document White, Cool. Used for the desk band's secondary call to action, "Želim takšen pregled".
- **Ghost:** transparent fill, Near-Black Ink text, Control Grey border; hover border turns ink. Used for the success card's "Popravite podatke" action that reopens the form, where its border steps up to Ink Diluted so it holds on the green wash; reserved for tertiary actions elsewhere.
- **Text link with arrow:** 600 label, no underline, a 1px Anodised Aluminium bottom border 2px below the text with 19px of padding above so the link meets the 44px target; the border turns ink on hover while the 16px arrow slides 3px right (the slide is dropped under reduced motion). Used for the hero's quiet "how it works" link. Plain inline links underline with a 1px Control Grey decoration offset 0.18em that turns to the text colour on hover.

### Chips
- **Style:** rectangular choice chip, 44px high, 12px horizontal padding, 1px Control Grey border, 2px corners, 500/1rem text in ink on transparent; the native checkbox or radio is visually hidden and the chip is its label, which carries no bottom margin of its own.
- **State:** hover border turns ink; checked fills Navy Wool with Document White, on Navy text and a navy border; focus-visible draws the 2px navy outline on the chip; under forced colours a checked chip takes the Highlight fill and border with a 3px Highlight outline so the state survives without colour. One appearance serves both the multi-select "Kaj naj pregledam?" (five checkboxes: Dom, Vozila, Življenje in nezgoda, Zdravje, Imam odprto škodo) and the single-select "Za koga?" (three radios: Zase, Za družino, Za podjetje); each group is a fieldset that spans the full width of the form grid, its chips laid out in a wrapping row with 8px gaps under a 600/1rem legend.

### Sample Tag
The one device the page uses to mark invented data, so a demonstration is never mistaken for a record. It is a filled label, not an outlined chip, so it reads as a stamp on the paper rather than a control: an inline-flex box with 2px corners, 4px 12px padding and no border, at 500/0.9375rem, and it always reads "Vzorčni podatki", in sentence case, wherever it appears. On white and plaster it is an Aluminium Soft fill with Ink Diluted text: the sheet head's badge and the first row of the about facts list, where "Letnici v tem seznamu" is answered by the tag before the years and counts. On navy it is recoloured for its surface, a Navy Seam fill with Navy Chalk text, and sits inside the contact aside's "Pisarna" heading (a wrapping flex row with a 12px gap) above the sample address. It never appears on real data and never carries an icon; the page's handoff comment names the tag and its three locations.

### Cards / Containers
- **Corner Style:** 2px.
- **Background:** document white on plaster (about card, partner cells, form success card) or on navy (comparison sheet, form).
- **Shadow Strategy:** the sheet shadow only when the container lies on navy; flat on plaster (see Elevation & Depth).
- **Border:** 1px Aluminium Soft on plaster containers; the partner grid is one hairlined rectangle with 1px Aluminium Soft gaps; the success card borders in Plant Green.
- **Internal Padding:** 24px (about card, partner cells, sheet head and foot vertical), 32px (form, sheet head and foot horizontal, success card); 16px on sheet cells.

### Inputs / Fields
- **Style:** 1px Control Grey border, document-white fill, 2px corners, 12px 16px padding, 50px minimum height, 1.0625rem text in ink, placeholders in Ink Faint. Labels and legends sit above at 600/1rem with an 8px gap; the rule reaches only the field's direct children, so the consent label stays a 400 flex row and each chip label is 500, neither with a bottom margin. One intro sentence at 1rem in Ink Diluted above the field grid names the two required fields and the consent at the end ("Obvezna sta samo ime in e-poštni naslov ter strinjanje na koncu. Vse drugo lahko pustite prazno."); there are no per-field "(neobvezno)" hints. Textareas start at 132px and resize vertically. The consent checkbox is native at 22px with navy accent colour, marked `required` and `aria-required`. The form is answered in the page (`method="get"`, validated and swapped to its success state by script; nothing is posted).
- **Focus:** the system 2px navy ring at a 2px offset with the border turning navy and no halo; hover border turns Ink Diluted. The consent checkbox takes the same 2px ring at 2px offset.
- **Error / Disabled:** invalid fields take a Red Pen border on Red Pen, Faint and reveal a 0.9375rem Red Pen message below; the red border stays while the field is focused, under the navy ring. An unchecked consent box takes a 2px Red Pen ring at 2px offset; when it is focused the ring returns to navy and the error moves outside it as a white (5px) then red (7px) double band. The form validates on submit and re-validates invalid fields as they change. Success replaces the form body with a Plant Green-bordered, green-washed card (a polite `role="status"` live region) that reads "Hvala, povpraševanje je oddano.", then "<first name>, oglasim se v enem delovnem dnevu…", written one frame after the card is shown so the live region announces it, after which the card takes focus; a line asking the reader to have their policies ready, the phone number as a 44px-tall navy tabular link (700, 1.25rem, `flex` at `max-content` width, underlined on hover), and a ghost "Popravite podatke" button (Ink Diluted border) that reopens the form with focus on the name field.

### Navigation
- **Masthead:** scrolls away. 56px logo beside the brand name (700/1.25rem) and subline (0.9375rem, Ink Diluted) stacked as blocks, the whole brand a content-width link (`flex: 0 1 auto`, `margin-right: auto`) so its focus ring hugs the logo and name; founder name and phone right-aligned with a 44px tap height on the phone; the row wraps rather than colliding. At 640px the logo shrinks to 44px, the name to 1.0625rem and the founder name hides; under 480px the long name and subline give way to the short "GJIC" mark (700/1.125rem), which is `display: none` at every wider width so it never shows beneath the long name, and the founder name returns at 1rem. The phone stays at every width.
- **Sticky nav:** 60px minimum, Plaster White, strong hairline top, soft hairline bottom; five 500/1rem links in page order (Primerjava, Storitve, Postopek, Partnerji, O meni), each an inline-flex 44px-tall target, with 32px gaps and a transparent 2px bottom border that turns ink on hover and for the current section (set by an intersection observer); a 44px compact primary button "Naročite pregled" that keeps the right edge (`margin-left: auto`). The row wraps under enlarged text rather than overflowing; under 480px it stops wrapping (`flex-wrap: nowrap`, 8px gap): the toggle keeps its content width (`flex: none`) and the compact button yields, shrinking, wrapping its label and breaking a word if it must (`overflow-wrap: anywhere`). The bar's measured height is written to `--nav-measured` for the page's scroll padding. Once stuck it takes the nav shadow and a strong bottom hairline. Vprašanja and Kontakt are reached from the panel and the footer, not the bar.
- **Mobile (≤860px):** links hide behind a 44px "Meni" toggle with the 22px menu/close marks (the mark, and under 480px the toggle itself, are `flex: none`, so neither is squeezed); the panel is fixed from the bar's bottom edge (the script writes it to `--panel-top` on open and resize, one layout read per frame) to the bottom of the viewport, on Plaster White with a strong bottom hairline and the panel shadow, scrolling on its own (`overflow-y: auto`, `overscroll-behavior: contain`) while the page beneath is locked (`html.menu-open { overflow: hidden }`), so a long list never scrolls it. Its first row is a navy call link with the 22px handset mark and the tabular phone number; the seven section links follow at 600/1.25rem, separated by soft hairlines, and the current section's link turns navy with a 3px navy bar inset at its left (a 3px Highlight left border under forced colours). Escape, a click outside the nav, a click on any link in the bar or panel (the compact button included) and tabbing out of the nav all close it; a close that takes focus with it returns focus to the toggle.
- **Footer:** 40px logo (the masthead's source reused), the "GJIC" name and its subline (both stay visible under 480px, where the masthead alone swaps to its short mark and hides its subline), the brand a content-width link like the masthead's, a wrapping list of all seven links at 44px tap height, and a soft-hairlined legal line at 0.9375rem in Ink Faint.

### Comparison Sheet
The signature component: one household's policies on a white document resting on the navy desk. The sheet clips its contents (`overflow: clip`). Head (24px 32px, strong hairline below) with a 700 title, a meta line and the sample tag. The table sits in a named, focusable scroll region (`role="region"` labelled by the sheet title, `tabindex="0"`) that scrolls horizontally if it must and clips vertically, its focus ring drawn 3px inside its edge because the sheet clips, so a reader who enlarges text gets a scrollable, announced table the keyboard can reach rather than a broken sheet. It is a borderless table at 1.0625rem with a visually hidden caption and explicit table roles, laid out `table-layout: fixed` with the policy column at 44% and the difference column at 14% so the count-up never resizes a column; 600 table headers in Ink Diluted on a strong hairline, 16px cells separated by soft hairlines, first and last cells padded to 32px. Figures stay on one line only in the table layout above 700px; on phones every cell wraps, insurer names carry soft hyphens (`Zavaro&shy;valnica`) so they break at a syllable first, and insurer lines may break anywhere (`overflow-wrap: anywhere`) as the last resort, so a long insurer name never widens the sheet. The recommended column is washed Plant Green with a green header and 700 amounts; the difference column is right-aligned 600 and coloured green for better, Ink Faint 500 for unchanged, Ink Diluted 500 for added cover. The total row is 700 on Document White, Toned with Plant Green, Deeper Wash under the recommended total. A foot (24px 32px, strong hairline above) carries the conclusion ("Boljše kritje za vso družino, nižja skupna premija. Odločitev ostane vaša. Zavarovalnice so v vzorcu zakrite."), which no longer calls the data invented because the head's tag already does, and a 600 signature. On entering the viewport (observer at threshold 0 with a -35% bottom root margin, so the sheet reveals once its top edge has risen into the upper 65% of the viewport and the reader is near it, and a 6-second fallback that reveals the sheet regardless), rows settle in from 8px below at 110ms intervals while recommended amounts count from the current premium to the recommended one over 650ms after a 200ms pause with a cubic ease-out, every difference and the total derived from the counted values on each frame; reduced motion shows the final state. Below 700px each row becomes an equal two-column card (`1fr 1fr`: policy across both columns, then current beside recommended, then the difference across both), its cells padded 12px, with the headers re-rendered as 0.9375rem in-cell labels generated with the `content: "…" / ""` alternative-text syntax so assistive technology does not hear them twice, every cell free to wrap (`min-width: 0`, `overflow-wrap: anywhere`), and the roles keep it a table. Under the sheet, the Promise sentence in Document White, on Navy precedes two Navy Chalk paragraphs and the light button.

### Ruled Rows
Services are a definition list: a strong hairline above the list, each row a 5/7 grid (title left, description right) padded 32px vertically and separated by soft hairlines, the last row closed by a strong hairline. The about facts and FAQ use the same grammar at 12px and 16px padding. The facts list opens with the sample-tag row ("Letnici v tem seznamu" against the "Vzorčni podatki" tag) before the years and counts, so the invented figures are labelled before they are read. The FAQ row is a native details element: a 600/1.25rem summary with the 20px plus mark at the right in Ink Diluted, rotating 45° when open (without transition under reduced motion), and a 60ch answer in Ink Diluted padded 24px below.

### Step List
Five numbered columns, each opened by a strong hairline, a 700/1rem tabular counter in Ink Faint, 32px of air, a 1.25rem title, a 1.0625rem description and a 1rem timing line in Ink Faint (the first step's reads "30 minut, brez obveznosti"). Below 1040px the columns stack into a single ruled list of 40px-counter rows padded 24px, separated by soft hairlines and closed by a strong one.

### Partner Grid
Thirteen logos in document-white cells of 112px minimum height (96px on small phones), logos capped at 36px tall and 150px wide (48px for the three square marks; 32px tall and the full cell width under 560px), the whole grid one 2px-cornered rectangle with 1px Aluminium Soft gaps. The grid closes with a plaster-coloured note cell in Ink Diluted spanning two columns; below 560px the thirteenth logo also spans both columns so the two-column grid closes square.

### Imagery and Rasters
Every raster is inlined in the page. Twelve of the thirteen partner logos, the masthead logo and the favicon are lossless WebP; the Generali mark, whose fine gradient would bloat a lossless encode, is lossy WebP (q88) with a lossless alpha plane at 11.9 KB. All thirteen partner logos decode asynchronously (`decoding="async"`), so the grid never holds up the first paint. The hero portrait is a WebP photograph. The about card's 88px portrait and the footer's 40px logo do not embed a second copy: they ship as a 1px GIF placeholder marked `data-portrait` or `data-logo`, take the hero and masthead sources from the DOM after load, and a `noscript` rule hides them so no empty placeholder shows without scripting.

## Do's and Don'ts

### Do:
- **Do** set body text at 18px/1.55 in Near-Black Ink with a 62ch measure, and lead paragraphs at 20px/1.5 in Ink Diluted.
- **Do** load Schibsted Grotesk with `font-display: block` over the three metric-matched Schibsted Fallback faces (400–500, 600, 700–900), so there is no fallback flash and no layout shift at any weight the page uses.
- **Do** draw every list with hairlines: Anodised Aluminium opens and closes it, Aluminium Soft separates rows (Navy Seam on navy); outline controls in Control Grey.
- **Do** draw documents as white sheets with 2px corners, 1px hairlines inside, and the sheet shadow only when they lie on navy.
- **Do** give navy whole regions and controls: bands, primary buttons, selected chips, the focus ring.
- **Do** set every comparable number in tabular lining figures with a narrow no-break space before the euro sign.
- **Do** keep every control at least 44px tall: 52px primary buttons, 50px inputs, 44px chips, nav links and compact nav button, 44px minimum on links that act as controls.
- **Do** draw focus as a 2px outline, offset 3px (2px on text inputs, the textarea and the consent checkbox; 3px inward on the sheet's clipped table region), navy on plaster and white, white on navy, navy again inside a white sheet on navy; keep an invalid field's red border under the ring.
- **Do** honour forced colours: Highlight fill, border and a 3px Highlight outline on checked chips, a ButtonText border on buttons, the nav underline only on the current link, and a 3px Highlight left border on the panel's current link.
- **Do** use the authored 1.5px-stroke mark set (arrow, menu, close, plus, phone) as inline SVG inside controls only, at 16px to 22px.
- **Do** mark every piece of invented data with the one filled "Vzorčni podatki" tag (500, no border; Aluminium Soft fill with Ink Diluted text on white and plaster, Navy Seam fill with Navy Chalk text on navy); it is the only device and the only wording for it.
- **Do** ship rasters as WebP, lossless for logos (lossy with a lossless alpha plane only where a gradient makes lossless heavy), and reuse an inlined source rather than embedding it twice.
- **Do** collapse every 5/7 and 7/5 split to one column at 860px and honour `prefers-reduced-motion` by showing final states: no sheet reveal, smooth scroll, button press, arrow slide or FAQ-mark rotation transition; buttons keep colour transitions only.
- **Do** give headings `hyphens: auto` and `overflow-wrap: anywhere`, and prose, list items, addresses, summaries, the consent text and the contact and mail links `overflow-wrap: anywhere`, as last resorts against a long Slovene word; soft-hyphenate a long proper name (`Zavaro&shy;valnica`) where it must wrap in a narrow cell.

### Don't:
- **Don't** add a second typeface, a monospace face or a system face to the design; Schibsted Grotesk at 400–700 is the whole system, and Schibsted Fallback exists only to hold the lines while it loads.
- **Don't** set small uppercase, letter-spaced labels above headings; section heads are a headline beside a lead paragraph.
- **Don't** use pills, circles or any radius other than 2px; don't use gradients anywhere.
- **Don't** use green for buttons, headings or decoration; it marks the recommended or covered state only.
- **Don't** tint the plaster ground with navy or put a navy hairline on it; navy hairlines belong on navy.
- **Don't** cast shadows from containers on the plaster ground, and don't use hard offset shadows; the only shadow is the soft sheet shadow on navy.
- **Don't** add a halo to a focused text input; the ring is always the 2px outline. The one halo on the page is the invalid consent checkbox's white-then-red band, which exists only because a native checkbox has no border to turn red.
- **Don't** thin or restyle the scrollbar's width; it keeps the OS default and is only coloured.
- **Don't** lay out services, benefits or steps as rows of identical icon cards; use ruled rows or hairline-opened numbered columns.
- **Don't** add shield or protection imagery; the GJ logo is the only shield on the page.
- **Don't** set any text below 0.9375rem; the mobile sheet's in-cell labels and the footer are the floor.
- **Don't** promise anything free or leave a fee unstated; the fee model is only ever "agreed in writing in advance", and the first step is "30 minut, brez obveznosti".
