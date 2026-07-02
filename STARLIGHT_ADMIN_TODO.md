# Star Light Cafe - Owner/Admin Action Items

Items below need confirmation or action from the owner (Rashidi) or JJ before going live.

## URGENT - Legal

- [ ] **Age requirement: 18 or 21?** Federal Tobacco 21 law (Dec 2019) sets minimum to 21 nationwide. Virginia follows federal law. The site currently says neutral wording pending confirmation. Toggle `AGE_GATE_EXPLICIT` to `true` in `site.config` once confirmed. Recommendation: set to 21 immediately.
- [ ] **Remove "Virginia state law requires 18+" language** - replaced with policy-neutral wording. Confirm the final age copy.

## Pricing - Needs Verification

- [ ] **Al Fakher for 2 = $27 and Starbuzz for 2 = $27** - Both brands show the same price for 2 people, but individual pricing is $10 vs $15. Is $27 correct for both, or should Starbuzz for 2 be higher (e.g. $30)?
- [ ] **Friday & Saturday Special** - The special banner has no actual offer text. What is the special? (e.g. "2-for-1 refills", "$5 off Starbuzz", etc.)
- [ ] **Non-smoking $5 charge** - Is this still current? Only on Fri/Sat?

## Content

- [ ] **Instagram handle** - Currently no Instagram link on the site. What is the handle? (e.g. @starlightcafe_va)
- [ ] **Watch party page** - World Cup schedule data is placeholder. Confirm which matches Star Light will host and any specials offered.
- [ ] **Group/event booking** - Confirm the form endpoint for group booking requests. Currently pointed at KG capture-lead.
- [ ] **Text/SMS signup** - Confirm if SMS marketing is desired. Requires TCPA-compliant opt-in. Currently added with consent checkbox.
- [ ] **Drink menu completeness** - Only 4 drinks listed (Mango juice, Strawberry smoothie, Mixed Berry smoothie, Moroccan Mint Tea). Are there more items?

## Technical

- [ ] **Domain**: starlight-cafe.com is connected. HTTPS certificate still provisioning on GitHub Pages. Once issued, enable "Enforce HTTPS" in repo Settings > Pages.
- [ ] **Google Business Profile**: Email verification submitted via info@starlight-cafe.com. Google processing (up to 5 days from June 29, 2026).
- [ ] **Google Maps Place ID**: Current Place ID returned "NOT_FOUND". May need to re-verify the listing or use updated coordinates.
- [ ] **Analytics**: Add Google Analytics / Tag Manager ID to the config once available.

## Completed

- [x] Hours updated to new schedule (Tue-Sat 5pm-1am, Sun-Mon 6pm-12am)
- [x] Logo added to age gate popup
- [x] Domain connected (starlight-cafe.com)
- [x] GBP description created
- [x] Images optimized to WebP (22MB+ savings)
- [x] OG image created from crowd/vibe photo
