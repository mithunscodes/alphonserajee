# alphonsemichael.in — Outstanding Items

Compiled from the full build conversation. Nothing here has been applied to the HTML yet unless noted.

## Photo
- [ ] Upload the real transparent cutout (must be `image.png`, PNG format — JPEG can't hold transparency) into the same folder as the HTML file
- [ ] Verify sizing/placement once the real transparent file is in — current CSS is tuned for it (280px column, native 413:531 aspect ratio, drop-shadow) but untested against the actual transparent version
- [ ] No AI-generated photo will be used — confirmed decision, real photo only

## Content Gaps (currently generic/placeholder but not visibly marked as such)
- [ ] **Engagement Model** (§09) — currently general copy reused from the "Prepared For" framing. Needs real input on how he actually wants to work with people (advisory retainer, board seat, project-based, etc.) if he wants it more specific
- [ ] **Credentials** (§10) — only ISO 9001 / FSSC 22000 Lead Auditor confirmed. Still need:
  - Formal education (degree, institution)
  - Any certifications beyond ISO/FSSC
  - Awards or recognitions, if any exist
  - He mentioned having physical certificates — scans/photos of these could be added as visual proof, matching the document aesthetic
- [ ] **Thought Leadership** (§06) — currently just one quote ("Mastering the details, ensure success."). More material (other real quotes, LinkedIn posts, actual opinions) could expand this later
- [ ] **Strategic Insights** (§07) — currently built entirely from existing career-record facts (CMU story, TCM/HDPE savings, regulatory scope). Real additional input could make this richer

## Publishing / Technical
- [ ] Register the domain: **alphonsemichael.in** (not yet confirmed purchased)
- [ ] Deploy `alphonse-rajee-michael.html` and `image.png` together — image reference is relative, both files must sit in the same folder on whatever host is used
- [ ] Point DNS at hosting once domain + host are set up
- [ ] Cross-browser check on the `zoom: 1.25` page-scale — well-supported in Chrome/Edge/Safari/current Firefox, but not a universal CSS standard; worth a quick check on an older browser if that matters for the audience
- [ ] Re-test mobile/responsive breakpoints — the `zoom` property changes the effective viewport CSS sees, so breakpoints (e.g. `max-width:820px` for the hero photo grid) may trigger at different real screen sizes than before

## SEO Follow-Through (outside the HTML file itself)
- [ ] Submit the URL in Google Search Console once live
- [ ] Add the site URL to his LinkedIn profile (`sameAs` in the file already points to LinkedIn — good to make it bidirectional)
- [ ] Get at least one or two real backlinks (e.g. a link from the Seeli Terra Taste site) — matters more than anything in the code for actually ranking #1 on his name
- [ ] Consider whether the plain-text `mailto:`/`tel:` contact info is worth obfuscating later — public plain-text email/phone will eventually attract spam scrapers; not urgent, just a known tradeoff of publishing contact info directly

## Standing Rules (already applied, listed here so they don't get lost in future edits)
- "Independent Director" — never printed on the site, literally or as a synonym; tone stays implied at that level throughout
- No fabricated stats, quotes, or achievements — every number/claim must trace back to something actually provided
- No self-congratulatory flourishes (certification stamps, "verified" labels on self-reported numbers, fake document-status claims) — already stripped once, watch for this creeping back in with future additions
- No looping/continuous animation (typing effects, shiny sweeps) — static or count-once only, per explicit decision
- Co-Founder (not Director of Operations) at Seeli Terra Taste
