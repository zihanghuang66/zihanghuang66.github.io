# Zihang Huang — personal website

Buildless HTML/CSS site for GitHub Pages. No package installation or build is required.

## Local preview

From this directory:

```bash
python3 -m http.server 8765 --bind 127.0.0.1
```

Open http://127.0.0.1:8765/. Stop with Ctrl-C.

## Editing

- `index.html`: profile, News & Milestones, publications, patents and collaboration/contact section.
- `assets/site.css`: desktop sidebar, top navigation, mobile layout and accessibility styles.
- `profile.jpg` and `assets/profile-5d1a64cf831a.jpg`: user-supplied IMG_2285.HEIC, converted to JPEG for browser compatibility; the circular upper-body framing is applied with CSS.
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

Input-pruning paper venue corrected to ITSC 2024, confirmed by the official conference program (https://its.papercept.net/conferences/scripts/abstract.pl?ConfID=87&Number=248). The title and IEEE link point to the owner-supplied publication page (https://ieeexplore.ieee.org/abstract/document/10920182/); arXiv and open PDF remain available.

The displayed portrait, favicon and social image use a content-hashed filename so browsers do not reuse a cached older `profile.jpg`. The original filename is retained for existing external links.

Patents section restored on request: eight publications from the supplied CV, with Google Patents links. All eight linked records list 黄梓航 among the inventors. Titles use the English wording in the CV. A-publication numbers and publication dates are shown, not claims that every application is granted. CN115774844B is separately linked as a grant publication dated 2026-02-17; no claim of current legal enforceability is made.

Additional application from the owner-provided CNIPA acceptance notice: 202611294661.9, filed and accepted 2026-08-25, applicant South China University of Technology; inventors 黄梓航, 陈俊龙, 张通. Original title: 一种数据真值全自动生成方法及相关设备. The displayed English title is a translation. Listed as application accepted, not granted; the notice supplies no publication number. The source PDF is not included in this website repository or preview archive. Total list: nine entries.

Patent formatting unified with publications: title, complete inventor line in source order, and identifiers/dates. The owner is bolded. Inventor order was checked against all eight Google Patents records and the 2026 acceptance notice. English names follow existing CV/paper spellings where available and standard transliteration otherwise; each name retains the Chinese source spelling in its HTML title attribute. News includes the August 2026 acceptance and February 2026 grant publication.

Paper News added on request: September 2024 groups QuadBEV and input pruning, verified against the official ITSC program (https://its.papercept.net/conferences/scripts/abstract.pl?ConfID=87&Number=249 and https://its.papercept.net/conferences/scripts/abstract.pl?ConfID=87&Number=248). September 2023 BEVENet and March 2018 EXGbuds dates/venues were checked against publisher-deposited Crossref metadata for 10.1109/ITSC57777.2023.10422223 and 10.1145/3173386.3177836. Dates refer to conference/publication milestones, not unverified acceptance dates; HRI is explicitly labeled Companion.

Desay management experience added to About Me from the owner-supplied CV_Huang_Zihang_EN_MGR_20260615.pdf: leadership of a 40+ engineer perception R&D organization across Singapore and China, perception system architecture and design, technical roadmaps, resource allocation, delivery planning, and KPI frameworks. Interviewing, mentoring, and architecture review wording was removed at the owner’s request. The organization size is not described as a count of direct reports.

WeRob 2017 paper added from the owner-supplied Google Scholar record (https://scholar.google.com/citations?view_op=view_citation&hl=en&user=dPbv6xsAAAAJ&citation_for_view=dPbv6xsAAAAJ:d1gkVwhDpl0C). Title, all five authors in order, November 2017 publication date, venue and pages 1–2 were cross-checked against publisher-deposited Crossref metadata for DOI 10.1109/WeRob.2017.8383845. The owner is the fourth author. Publication entry links to IEEE and DOI; News records the November 2017 publication milestone. No unverified PDF link or citation count is displayed.
