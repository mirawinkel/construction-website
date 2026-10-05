---
id: TASK-1
title: Define site requirements and content
status: Done
assignee: []
created_date: '2026-10-04 22:07'
updated_date: '2026-10-05 00:10'
labels: []
dependencies: []
ordinal: 1000
---

## Description

<!-- SECTION:DESCRIPTION:BEGIN -->
Determine what the construction-business website actually needs before any visual design or implementation begins. Governing principle: less is more - this is a small public-facing informational/marketing website, not a web application. This task defines the work that will later discover those answers; it does NOT solve the requirements itself. Out of scope (do not address in this task): HTML/CSS/JavaScript implementation, visual design, framework selection, CMS selection, analytics, customer accounts or portals, backend systems, speculative features, and invented marketing claims or copy.
<!-- SECTION:DESCRIPTION:END -->

## Acceptance Criteria
<!-- AC:BEGIN -->
- [x] #1 The business name and basic business/brand information are identified and documented
- [x] #2 The services that genuinely need representation on the site are identified
- [x] #3 The visitor's primary goal(s) are documented
- [x] #4 The site's primary call to action (e.g., calling, emailing, or requesting an estimate) is documented
- [x] #5 Available assets are inventoried (logo, photographs, contact information, service descriptions, testimonials)
- [x] #6 Missing content/assets are identified and documented
- [x] #7 Required content/sections for the site are identified
- [x] #8 A single-page vs multi-page decision is made with a short rationale
- [x] #9 Necessary business/legal/footer information is identified
- [x] #10 No speculative functionality has been added to the requirements
<!-- AC:END -->

## Implementation Plan

<!-- SECTION:PLAN:BEGIN -->
TASK-1 is a requirements-definition task. No code or site files are changed by this task; all deliverables are recorded in this Backlog task.

Approach (human interview completed 2026-10-04):
1. Human interview covered identity, location, services, customers, contact/CTA, assets, and legal/footer info. No business information was invented; unknowns were explicitly marked.
2. Record in this task's implementation notes:
   - Content inventory (confirmed / exists-but-needs-supplying / needs-human-decision / not-required-for-initial-site)
   - Visitor and CTA definition (primary visitor, their goal, single primary CTA, secondary actions)
   - Site size decision (single-page vs multi-page) with rationale
   - Initial content structure (only sections justified by requirements)
   - Deferred non-required features (recorded only; no new Backlog tasks created)
3. Verify each of the 10 acceptance criteria against the recorded document and record per-AC results in notes.
4. Stop for human review: no commit, no push, do not start TASK-2.
<!-- SECTION:PLAN:END -->

## Implementation Notes

<!-- SECTION:NOTES:BEGIN -->
## TASK-1 Requirements Document (recorded 2026-10-04 from human interview; updated 2026-10-04 with human-supplied follow-up items)

### Business identity
- Name: Lavender Dreams Painting LLC
- Location / service area: Seattle / King County, WA
- Market: residential properties only (no commercial)
- Customers: homeowners, renters, landlords of residential properties

### Services to represent on the site (confirmed actually offered)
1. Exterior painting
2. Interior painting
3. Landscaping
4. Renovations
5. Home maintenance
Note: service copy must be short and factual; no unverified claims (years in business, project counts, guarantees, awards).

### Visitor and CTA definition
- Primary visitor: residential property stakeholders (homeowners/renters/landlords) in Seattle/King County looking for painting, landscaping, renovation, or home-maintenance help.
- What they are trying to learn: whether this business offers the service they need locally, and how to get a quote.
- Action after viewing: contact the business for an estimate.
- Primary CTA (single): "Request an Estimate" via email to lavenderdreamspainting@proton.me (email form / mailto).
- Secondary actions (non-competing): view services, check license info, view business hours.

### Contact information
- Preferred method: email (form or mailto) - lavenderdreamspainting@proton.me
- Phone (CONFIRMED 2026-10-04 follow-up): +1 (425) 675-6296 - to be displayed in the contact section and footer alongside the email. (Earlier open question "whether to include a phone number" is now DECIDED: yes.)
- Business hours: Monday-Friday 8:00 AM - 4:00 PM

### Legal / footer information
- WA L&I license number (CORRECTED 2026-10-04 follow-up): LAVENDP742O1 - the character after "742" is a capital letter O, NOT the digit zero. The earlier recorded value LAVENDP74021 was wrong and is superseded everywhere in this record.
- L&I license lookup URL (CONFIRMED 2026-10-04 follow-up; use exactly): https://secure.lni.wa.gov/verify/Detail.aspx?UBI=606188914&LIC=LAVENDP742O1&SAW=
  - The URL's LIC parameter is LAVENDP742O1 (capital O), matching the corrected license number.
- Insurance: referenced via the L&I WA website record; no separate insurance details needed on the site.
- Footer contents: business name, license number LAVENDP742O1 + L&I lookup link, business hours, contact email, phone +1 (425) 675-6296, "Residential only - Seattle and King County".

### Content inventory
Confirmed (documented above):
- Business name, location/service area, five services, customer types, primary CTA + email address, business hours, corrected license number LAVENDP742O1, L&I license lookup URL, phone number +1 (425) 675-6296, about-section requirement, footer legal info.

Still outstanding / pending (placeholders approved in the meantime):
- About-section final wording - DEFERRED to a later subtask (recorded here only; no new Backlog task created; no about copy written now). The About section remains in the site IA with placeholder/pending wording.
- Logo file (use a placeholder until supplied)
- Real project/work photographs (use clearly labeled placeholder images until supplied)

Decisions still requiring human input:
- (none remaining - all previously open items resolved 2026-10-04: L&I lookup URL confirmed, phone number decision = include it, about-section wording deferred to a later subtask by explicit human instruction)

Not required for the initial site:
- Testimonials (none confirmed available)
- Detailed project history / case studies (placeholder photos only)
- Social media links, analytics, blog, commercial services, backend/form systems beyond a simple mailto-based estimate request

### Site size decision
Single page. Rationale: five short service descriptions plus one CTA, about, and contact fit comfortably on one page; there is no deep content or distinct search intent that would justify multiple pages. Single page minimizes scope per the less-is-more principle. Multi-page is not justified at this time.

### Initial content structure (single page, top to bottom)
1. Header/nav - business name + anchor links (Services, About, Contact)
2. Hero/intro - name, one-line description (residential painting and home services in Seattle/King County), primary CTA "Request an Estimate"
3. Services - five service blocks with short factual descriptions
4. About - section present; final wording DEFERRED to a later subtask (placeholder text in the meantime)
5. Our Work - placeholder photo slots clearly marked as placeholders, to be replaced with real photos later
6. Contact - estimate request via email form/mailto, email address, phone +1 (425) 675-6296, business hours, license number LAVENDP742O1 + L&I lookup link
7. Footer - name, license LAVENDP742O1 (linked to the L&I lookup URL above), business hours, email, phone, service area

### Deferred / later-to-do (recorded only; no new Backlog tasks created)
- About-section final wording (deferred to a later subtask per human instruction 2026-10-04)
- Social links, testimonials section, detailed project case studies, blog/content marketing, analytics

### Acceptance criteria verification (re-verified 2026-10-04 against the updated document)
- AC1 Business name + brand info: PASS - name/location/market documented; brand assets not yet available (tracked as needs-supplying; visual direction is TASK-2 scope).
- AC2 Services to represent: PASS - five confirmed services documented.
- AC3 Visitor primary goal(s): PASS - documented above.
- AC4 Primary CTA: PASS - single primary CTA (email estimate request) documented.
- AC5 Available assets inventoried: PASS - inventory documented; confirmed items now include corrected license LAVENDP742O1, L&I lookup URL, and phone number; logo/photos/about wording tracked as pending with placeholders approved.
- AC6 Missing content/assets identified: PASS - outstanding list updated to about-section final wording (deferred), logo file, real project/work photographs.
- AC7 Required sections identified: PASS - seven-section single-page structure documented, now including the phone number in contact and footer.
- AC8 Single vs multi-page + rationale: PASS - single page with rationale.
- AC9 Business/legal/footer info: PASS - corrected license LAVENDP742O1 with confirmed L&I lookup URL (LIC param matches), insurance reference, hours, email, phone documented.
- AC10 No speculative functionality: PASS - deferred items recorded only; no new tasks created; no invented claims or copy.

Gate state (updated 2026-10-04): all 10 ACs re-verified as met by the updated document above. Checkboxes intentionally left unchecked pending human review/finalization. Not committed. Not pushed. Stopping for human review. TASK-2 not started.

Gate state (FINALIZE 2026-10-05): Human approved commit + push for the TASK-1 definition checkpoint. All 10 ACs checked in Backlog and verified against the recorded requirements document. Final summary recorded. Marking Done. Only the TASK-1 Backlog file is expected to change; no production code, no site files, TASK-2 not started.
<!-- SECTION:NOTES:END -->

## Comments

<!-- COMMENTS:BEGIN -->
created: 2026-10-04 23:51
---
Human follow-up supplied 2026-10-04 (supersedes earlier open items):
1. License correction: correct WA L&I license number is LAVENDP742O1 (capital O after "742", not digit zero). All prior occurrences of LAVENDP74021 in this record replaced.
2. L&I lookup URL confirmed: https://secure.lni.wa.gov/verify/Detail.aspx?UBI=606188914&LIC=LAVENDP742O1&SAW= (LIC param matches corrected number).
3. Phone number decision resolved: include +1 (425) 675-6296 in contact section and footer; removed from open-decisions list.
4. About-section final wording deferred to a later subtask (recorded as deferred/later-to-do only; no new Backlog task created; no about copy written).
Requirements document (implementation notes) fully updated; all 10 ACs re-verified PASS. Stopping for human review; no commit/push; TASK-2 not started.
---
<!-- COMMENTS:END -->

## Final Summary

<!-- SECTION:FINAL_SUMMARY:BEGIN -->
TASK-1 definition checkpoint complete. All 10 acceptance criteria verified as met against the recorded requirements document: business identity (Lavender Dreams Painting LLC, Seattle/King County, residential-only), five confirmed services, visitor goal, single primary CTA (Request an Estimate via email lavenderdreamspainting@proton.me), contact info (email + phone +1 (425) 675-6296 + hours Mon-Fri 8:00-4:00), corrected WA L&I license LAVENDP742O1 with confirmed L&I lookup URL, seven-section single-page structure with rationale, and no speculative functionality. Deferred items tracked for later subtasks (recorded only, no new tasks created): about-section final wording, logo file, real project/work photographs. No production code written; no site files changed.
<!-- SECTION:FINAL_SUMMARY:END -->
