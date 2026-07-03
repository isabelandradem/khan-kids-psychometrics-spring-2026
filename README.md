# Khan Academy Kids — Spring 2026 Psychometrics

An interactive report of the Spring 2026 psychometric analyses for the Khan
Academy Kids direct-assessment scales, covering four domains (English):

- **Mathematics** (MAT)
- **Literacy** (LIT)
- **Executive Function** (ATL)
- **Language** (LAN)

The site is a single, self-contained `index.html` — all data and charts are
embedded, so it needs no server or build step to view.

## Viewing

- **Live site:** enabled via GitHub Pages (see the repository's *Pages* settings
  for the URL).
- **Locally:** open `index.html` in any modern browser.

## What's inside

For each assessment scale:

- **Percent Correct** by intended difficulty tier, with a difficulty ladder
- **Performance Levels** (post-stop percent-correct vs. guessing)
- **Total Score Distribution**
- **Exit Rate** (item-attrition drop-off across items)
- **Inter-Item Correlations** heatmap and Cronbach's α
- **Concurrent Validity** against external criteria

Each domain also has an **All → Domain summary** view (one row per scale). Use
the collapsible sidebar and the search box to navigate.

## Notes

Figures are aggregate psychometric statistics (reliability, correlations, exit
rates, score distributions) — no individual student records are included.

The data-processing pipeline used to build this report (Python extractors and
the build guide) lives alongside the source data outside this repository.
