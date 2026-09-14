# MarktWissen Deutschland – Final Technical QA

## Purpose
Final pre-submission check for the German (`/de/`) site before affiliate/compliance review. This is an internal QA document, not legal or regulatory approval.

## Scope
- Germany only: `/de/`
- Austria remains separate and is not part of this QA change.
- No unapproved provider affiliate link is activated in the German area.

## Checks completed
- [x] German homepage has canonical URL and `index,follow`.
- [x] German sitemap contains the DE homepage and the main educational/comparison pages.
- [x] Public Affiliate-Transparenz page is present and linked from the homepage.
- [x] Methodik/Transparenz and Impressum/Datenschutz pages are part of the public trust layer.
- [x] Main commercial-intent pages explicitly state that concrete provider affiliate links are not active until required approvals/current provider information are available.
- [x] Comparison page avoids a blanket “best broker” ranking and uses consistent comparison criteria.
- [x] No invented provider loss percentage is published in the German area.
- [x] No bonus, discount, recruit-a-friend, easy-money or guaranteed-profit language is used in the German editorial positioning.
- [x] German pages use responsive CSS with mobile breakpoints at 900px and 650px; navigation becomes horizontally scrollable on small screens and content grids collapse to one column.
- [x] Legal pages contain operator/contact information and links to privacy/risk information.
- [x] Affiliate transparency explains that provider links/materials are only used after the required approval gate.

## Technical observations
- Internal navigation is relative and designed for the `/de/` directory, avoiding accidental Austria/DE mixing.
- `sitemap.xml` contains the German URLs and the public affiliate-transparency page.
- The German stylesheet includes responsive rules for navigation, cards, grids, CTA panels and article layout.
- The current German site intentionally has no active provider outbound affiliate URL. Therefore affiliate target/tracking validation is deferred until the official link is supplied by the affiliate program.

## Compliance-dependent items that must remain open
1. Approval of the exact German website/source by the affiliate program.
2. Approval/provision of the exact affiliate link and tracking target.
3. Approval of any provider-specific creatives or marketing materials.
4. Confirmation of the applicable German retail legal entity/product conditions.
5. Current provider-specific CFD risk warning and loss percentage.
6. Final review of warning prominence and placement on every provider-specific commercial communication.
7. Final traffic-source, brand-use, keyword and placement restrictions supplied by the affiliate program.

## Submission status
**Editorial/technical pre-submission: prepared.**

**Affiliate activation: intentionally not active.**

The site should be submitted for review without inventing or activating a provider link. After the affiliate program supplies the approved materials and current provider data, the commercial CTA can be implemented and checked as a separate release.

## External basis
BaFin states that CFD marketing to German retail clients requires a provider-specific risk warning and explicitly addresses affiliate/partner marketing. Google states that affiliate links should be qualified appropriately and that affiliate sites should provide meaningful original value rather than copied merchant content.
