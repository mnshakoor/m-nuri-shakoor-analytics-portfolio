# M. Nuri Shakoor Analytics Portfolio

**Quanta Analytica™ | MNS Consulting | ARAC International Inc | Lladner Business Solutions LLC, Global Development and Risk Management Division | IOSI Global**

Public portfolio of analytic data products, intelligence reporting, visualizations, and applied analytic tools produced under the Quanta Analytica Process™ (QAP™).

**Live site:** [portfolio.mnshakoor.com](https://portfolio.mnshakoor.com) (GitHub Pages)
**Primary site:** [mnshakoor.com](https://mnshakoor.com)

---

## 1. Purpose

This repository is the publication layer for finished analytic work. It holds three classes of product:

1. **Data product sets.** Coordinated outputs built from a single dataset under the `qap-data-viz-set` workflow: data stories, geospatial atlases, documented AI-assisted investigations with audit trails, and situational briefs.
2. **Intelligence reports.** QAP Web Report v2.0 assessments and situational intelligence briefs, published as self-contained HTML.
3. **Applied tools.** Links to production analytic applications and to interactive dashboards hosted on Tableau Public.

Each product is self-contained. Anything published here is intended to be readable without access to internal working files.

---

## 2. Repository structure

```
m-nuri-shakoor-analytics-portfolio/
├── index.html                  Portfolio landing page (GitHub Pages entry point)
├── CNAME                       Custom domain record: portfolio.mnshakoor.com
├── README.md
├── assets/                     Shared CSS, JS, fonts, logos used across products
│   ├── qap-viz.css
│   ├── viz-core.js
│   └── img/
├── reports/                    Published QAP assessments and situational briefs
├── data-viz/                   qap-data-viz-set product folders
│   └── <product-slug>/
│       ├── index.html
│       ├── data/               Source extracts and cleaned tables
│       ├── figures/            Static exports (PNG, SVG)
│       └── README.md           Product-level scope, sources, and method note
├── tableau/                    Landing pages wrapping Tableau Public embeds
└── apps/                       Landing pages and links for applied analytic tools
```

### Folder conventions

- One product, one folder. Folder names are lowercase, hyphenated, and stable once published, because published URLs depend on them.
- Every product folder carries its own `README.md` stating scope, data sources, collection window, method, and known limitations.
- Every product folder entry point is `index.html`, so the product resolves at a clean directory URL.
- Raw or licensed source data that cannot be redistributed is excluded. The product README records the source and access path instead.

---

## 3. Product index

### Reports

| Product | Type | Status |
| --- | --- | --- |
| _To be populated as reports are added._ | | |

### Data visualization sets

| Product | Dataset | Product types | Status |
| --- | --- | --- | --- |
| _To be populated._ | | | |

### Tableau Public dashboards

Interactive dashboards are authored on Tableau Public and surfaced here through QAP-branded wrapper pages that supply analytic framing, source declarations, and interpretation guidance around the embed.

| Dashboard | Wrapper page | Tableau Public |
| --- | --- | --- |
| _To be populated._ | | |

Profile: [Tableau Public — mnshakoor](https://public.tableau.com/app/profile/mnshakoor)

### Applied analytic tools

Applications are developed and deployed separately. This repository hosts their portfolio entries and links.

| Application | Description | Link |
| --- | --- | --- |
| QAP Intelligence Workbench | React application with structured analytic sections, Scenario Tool, RAPITIS Source Scorer, I&W Tracker, and Export Engine | _link_ |
| QA CARVER Assessment Tool | CARVER criticality and vulnerability assessment implementing SMI/Bencie methodology with DBT integration | _link_ |
| QA Risk Register App | Risk register with scoring, treatment tracking, and export | _link_ |
| GDELT Signal Console | OSINT working console over GDELT DOC 2.0 extracts with burst detection, source concentration, framing divergence, and entity networks | _link_ |
| QAP Framework Map | Interactive pan, zoom, and search map of the QAP™ analytic framework | _link_ |

---

## 4. Methodological standards

All products in this repository are produced under the Quanta Analytica Process™ (QAP™), a proprietary workflow that applies peer reviewed methods. Related proprietary workflows include QA-CSRF™ and IGRIS™.

Standards applied to every published product:

- **Source discipline.** Web sourced information is handled under the WSI Policy and scored using the RAPITIS rubric. Source cards state reliability and credibility ratings.
- **Evidence traceability.** Substantive claims are traceable to cited evidence, to explicitly labeled structured inference, or to stated assumptions.
- **Calibrated confidence.** Confidence language is proportionate to evidentiary strength and is stated, not implied.
- **Structured analytic techniques.** Analysis applies formal SATs where the question warrants them, and names the technique used.
- **Reproducibility.** Data preparation steps are documented at the product level so that figures can be regenerated from the stated source.

---

## 5. Design system

Products use the Quanta Analytica obsidian and gold design system.

- Core palette: obsidian `#0a0c10`, gold `#c8a96e`
- Typography: IBM Plex Sans, IBM Plex Mono, Libre Baskerville
- Standard components: hero and metrics strip, key finding box, panel cards with accent bars, source cards, status grids, scroll progress bar, and reveal on scroll behavior
- Shared styles live in `assets/`. Product pages import from there rather than redefining the system locally.

---

## 6. Publishing workflow

Files are added through the GitHub web interface or GitHub Desktop.

**Adding a product through the browser**

1. Open the repository and navigate into the target parent folder, for example `data-viz`.
2. Select **Add file**, then **Upload files**.
3. Drag the complete product folder into the upload area. GitHub preserves the folder structure.
4. Enter a commit message describing the product added, then select **Commit changes**.

**Enabling the site**

1. Open **Settings**, then **Pages** in the left sidebar.
2. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
3. Set the branch to `main` and the folder to `/ (root)`, then select **Save**.
4. Under **Custom domain**, enter `portfolio.mnshakoor.com` and select **Save**. GitHub writes the `CNAME` file automatically.
5. At the DNS host for `mnshakoor.com`, create a CNAME record for `portfolio` pointing to `mnshakoor.github.io`.
6. Return to **Settings**, then **Pages**, and select **Enforce HTTPS** once the certificate is issued.

DNS propagation and certificate issuance can take up to twenty four hours. The site remains reachable at the default `github.io` address during that period.

---

## 7. Citation

Products may be cited as:

> Shakoor, M. Nuri. *[Product Title]*. Quanta Analytica™ / MNS Consulting, [Year]. https://portfolio.mnshakoor.com/[path]

---

## 8. Rights and disclaimer

Analytic content, design system, and framework materials are © M. Nuri Shakoor / MNS Consulting. QAP™, QA-CSRF™, and IGRIS™ are proprietary workflows. Third party data retains the license terms of its originating source, recorded in each product README.

Products published here are independent analytic work. They do not represent the official position of any partner or client organization. Assessments are analytic judgments under uncertainty and are not operational, legal, or investment advice.

---

## 9. Contact

**M. Nuri Shakoor**
Global Security Analyst and Geopolitical Risk Intelligence Consultant
[mnshakoor.com](https://mnshakoor.com) | [linktr.ee/mnshakoor](https://linktr.ee/mnshakoor)
