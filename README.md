# Zihang Huang — personal website

Buildless HTML/CSS site for GitHub Pages. No package installation or build is required.

## Local preview

From this directory:

```bash
python3 -m http.server 8765 --bind 127.0.0.1
```

Open http://127.0.0.1:8765/. Stop with Ctrl-C.

## Editing

- `index.html`: profile, News & Milestones, publications and collaboration/contact section.
- `assets/site.css`: desktop sidebar, top navigation, mobile layout and accessibility styles.
- `profile.jpg`: user-supplied IMG_2285.HEIC, converted to JPEG for browser compatibility; the circular upper-body framing is applied with CSS.
- `CV_Huang_Zihang_EN_20260615.pdf`: supplied June 2026 CV, linked with its date.
- `HuangZihangCV_EN_20250625.pdf`: previous CV kept so existing incoming links continue to work.
- `assets/registration-comparison.png`: retained public-data demo asset; not currently displayed on the page.

Navigation and content work without JavaScript. There are no remote fonts, analytics, form submissions or framework dependencies.

## Content sources and update notes

Layout reference: https://ziyuguo99.github.io/ (visual reference only; its code, portrait and personal content were not copied).

Profile and employment details: user's supplied June 2026 CV. Website designation is PhD Candidate, per the owner’s 2026-10-14 correction (the supplied PDF is unchanged); Desay employment ends in October 2025; Anker employment is November 2025–February 2026. No current employer is assumed. The draft should be reviewed for any changes since that CV. Public page performance percentages were removed where evaluation context was unavailable. Team contributions remain identified as leadership or team work.

Publication titles and author order were cross-checked with arXiv 2410.06516, 2410.07268 and 2312.00633. Conference venues and EXGbuds bibliographic information follow the supplied CV. Patent identifiers are described as published applications, not granted patents. No Google Scholar profile or academic service was invented.

Point-cloud results use the existing experiment metrics (60→120, seed 7). The demo also discloses failures on 60→180. Data source: Sturm et al., TUM RGB-D Benchmark (https://cvg.cit.tum.de/data/datasets/rgbd-dataset), freiburg1_desk, CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). Figure adaptations include depth backprojection, subsampling, rigid registration, coloring and rendering.

## Publishing

The root `index.html` remains compatible with the repository's existing GitHub Pages setup. GitHub Pages publishes from the root of `main`; the owner approved this redesign for publication on 2026-10-14. Check the linked CV and all profile details before publishing; the CV includes the contact information and personal details provided by its owner.

Owner corrections on 2026-10-14: removed the October 2026 News item, replaced the profile photograph, used PhD Candidate throughout the webpage, and changed Anker product wording to robotic products / robotic product failure analysis.

News additions requested on 2026-10-14:

- M1 approval: November 2019 is the actual approval month, distinct from the January 2020 announcement. Source: Desay SV's Media OutReach release reproduced at https://vietnamnews.vn/media-outreach/571348/a-good-start-to-2020-desay-sv-singapore-received-the-vehicle-safety-assessment-milestone-1-approval-to-test-autonomous-vehicles-in-singapore.html . The approval belongs to Desay SV Singapore; the owner's contribution to perception development and validation follows his CV.
- WIDC: May 2021, Silver Award in the Intelligent Driving Extreme Challenge. Desay SV's official report, published June 16, states that the competition concluded May 23: https://www.desaysv.com/newsDetails/291.html . The team award is distinguished from the owner's engineering contribution. No individual medal or unverified overall ranking is claimed in News.

Latest owner edits: changed the introduction to “over eight years”; removed the Industry Experience, Education, Patents & Applications, Selected Project and Technical Skills sections and their navigation links; placed publication brackets inside each link and spacing only between links.

GitHub username and website repository renamed on 2026-10-14 to `zihanghuang66` and `zihanghuang66.github.io`. Target site: https://zihanghuang66.github.io/ . Profile and canonical links use the new address.
