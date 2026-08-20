# Insurance-Dashboard-Excel
Key Findings

Revenue Performance

Renewal significantly outperforms target (150% achievement), while New business lags badly (only 17% placed, 4% invoiced).
Cross Sell sits mid-pack (59% placed) but invoice conversion is weak (15%), showing a gap between "won" and "billed."
Across all categories, invoiced amounts trail achieved revenue — pointing to a collections/billing delay, not just a sales gap.

Pipeline

44 of 49 opportunities (90%) are still open, with a steep funnel drop-off: 42 deals at Qualify → 5 at Negotiate → 2 at Propose Solution.
Fire, Employee Benefits (EL-Group Mediclaim), and Property (DB-Mega Policy) drive the bulk of top-line opportunity value.

Team Performance

Gilbert leads invoice volume (61) but is almost entirely Renewal-driven, with minimal New business.
Ketan Jain and Juli show the most balanced mix across Cross Sell, New, and Renewal.
Meeting activity is concentrated in 2020 (31 of 34 meetings), suggesting either business ramp-up or a limited 2019 data window.
Workflow
Data Collection – Pulled raw opportunity, invoice, and meeting data from source exports (Opportunity, Invoice, Meeting sheets).
Data Cleaning (Power Query) – Standardized column names, fixed date formats, removed duplicates/blank rows, and merged Account Executive IDs with names across tables.
Data Modeling (Power Pivot) – Built relationships between Opportunity, Invoice, Meeting, and Account Executive tables using a star-schema style model to avoid repeated VLOOKUPs.
DAX Measures – Created calculated measures for Achieved Revenue, Achievement %, Placed vs Invoice comparisons, and stage-wise funnel counts.
PivotTables/PivotCharts – Summarized cleaned, modeled data into pivot tables feeding each dashboard visual.
Dashboard Design – Assembled KPI cards, bar/funnel charts, and a donut chart into a single-page Excel dashboard for at-a-glance reporting.
