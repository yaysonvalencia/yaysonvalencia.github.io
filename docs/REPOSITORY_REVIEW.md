# Repository review and positioning

Reviewed November 20, 2026. All five public repositories were inspected without modification. Repository inventories, READMEs, selected source files, live and synthetic exports, manifests, and both business-project PDF reports informed this version. This is an artifact review, not an independent audit of every underlying research source or a rerun of the original cloud environments.

| Repository | Portfolio role | Supported capability | Constraint |
|---|---|---|---|
| amazon-india-market-intelligence-agent | Lead case study | Decision framing, configured AI workflow, evidence assessment, executive synthesis | Udacity program project; no independent model, verified sales, causal findings, or measured implementation impact |
| novatech-revenue-intelligence-dashboard | Full case study | Cross-functional BI, metric definitions, source discipline, dashboard and Topic configuration | Course-provided data; many-to-many fan-out; public exports are not a live production deployment |
| market-research-analytics-pipeline | Full case study | Public API ingestion, quality checks, reproducible outputs, provenance | Synthetic default output differs from live example; no margins of error or investment scoring |
| python-web-scraping-and-data-analysis-portfolio | Supporting repository link | pandas cleaning, Selenium collection, exploratory analysis | UF coursework, synthetic book data, limited practice-site sample |
| yaysonvalencia | Preserve as profile repository | Existing professional introduction and project discovery | Separate from the new Pages repository |

## Evidence details

The market-intelligence PDF contains seven pages and five evaluated insights. External claims in that brief vary in source quality and age. The site describes the workflow and proposed decisions without asserting those claims as established current market facts.

The NovaTech report confirms 499 CRM records, 2,240 marketing records, 3,000 support records, and 63,420 joined rows. The site explains why joined row counts do not represent additional business activity and why source totals remain authoritative.

The pipeline root `run_manifest.json` is synthetic demo mode. `run_manifest (5).json` identifies live mode and records 18 OK statuses. `market_indicators (3).csv` contains the live example. `quality_report (4).csv` is the corresponding live quality artifact. The site links to those actual filenames rather than mixing demo and live values.

## Existing documentation issues

The pipeline README links to `examples/demo_output/`, `examples/live_output/`, `notebooks/market_research_pipeline.ipynb`, and `examples/config.example.json`; these directories do not exist in the inspected tree. The actual notebook and config are at the repository root, and outputs are also root-level files with duplicated upload suffixes. These links should be corrected in a separately authorized repository-maintenance change. The portfolio uses actual root-level evidence links and leaves the original files untouched.

## Positioning recommendation

Lead with enterprise operations and business decision-making. Present analytics and applied AI through decisions, controls, and inspectable work. Keep tools secondary to business questions. Retain program context rather than obscuring it. Avoid skill percentages, certificate walls, developer contribution widgets, client-logo strips, invented testimonials, and unsupported financial results.

Career descriptions and education reflect owner-provided background. No confidential carrier names, account economics, internal performance figures, or unannounced role changes are included.

## Architecture decision

A static multi-page site fits GitHub Pages and the initial editorial scope. It has no runtime dependencies and can be edited directly in GitHub. Three case-study URLs support deeper review and direct sharing. A content framework such as Astro becomes useful if the portfolio grows substantially; it adds unnecessary build and dependency maintenance at this size.

## Visual direction

Charcoal-green, warm white, restrained green accent; editorial serif headings with system sans body text; ample space; short decision-oriented sections; accessible contrast; clear evidence links; mobile stacking. The design uses a real dashboard export and explicit summaries of actual work rather than generic stock AI imagery.
