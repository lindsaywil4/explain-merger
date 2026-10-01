# UP-NS Merger Explainer (Houston)

A static, multi-page explainer on the proposed Union Pacific / Norfolk Southern merger (STB Docket FD 36873) and its Houston impacts. Plain HTML and CSS. No build step, no dependencies beyond Google Fonts.

## Pages

- `index.html` - Overview and site guide
- `timeline.html` - Full merger timeline, July 2025 to present
- `letters.html` - Pre-filing support letters vs. Houston officials' requests
- `opposition.html` - GOP delegates, state AGs, senators, cities, rival railroads
- `antitrust.html` - The market concentration argument
- `houston-data.html` - Blocked crossings, idling trains, train length (FRA data)
- `impacts.html` - Transportation, cancer clusters, truck traffic, Settegast expansion
- `discrepancies.html` - Where UP's public claims and filings diverge
- `action.html` - Sign the resident statement (lindsaywil4.github.io/stb-statement), file a comment, attend the hearing

## Deploy to GitHub Pages

1. Create a new repository (public).
2. Upload all files in this folder to the repository root.
3. In the repo: Settings > Pages > Source: "Deploy from a branch" > Branch: `main`, folder `/ (root)` > Save.
4. Your site publishes at `https://<username>.github.io/<repo-name>/` within a few minutes.

To use a custom domain, add it under Settings > Pages and create a CNAME record with your DNS provider.

## Updating

Each fact carries a `SOURCE` line naming the STB filing number, FRA dataset, letter, or news report it came from. When the docket moves (new filings, hearing dates, deadlines), update:

- The "UPDATED" date in each page header
- `timeline.html` (add entries)
- `action.html` (deadlines and hearing info)

## Notes

- Verify filing citations against the STB filing search (Docket FD 36873) before publishing updates.
- FRA blocked-crossing figures come from the public portal data (fra.dot.gov/blockedcrossings), 2021 through mid-2026 extracts.

## Change log

- **Oct 1, 2026.** Timeline through Sept 30 and the schedule to final decision; corrected review thresholds (50% tonnage, OEA +4.00/+4.26 trains/day); fifth vintage of Houston numbers and the Settegast contradiction (EI-34309); withdrawn, disavowed, and affiliated support letters; Texas AG, BNSF Gulf Coast condition, RPA, NLC; Take Action now leads with the resident statement page and the Nov 18, 2026 deadline; deadline strip added to every page.
