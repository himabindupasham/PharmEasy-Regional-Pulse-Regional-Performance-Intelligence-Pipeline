# Pharma Sales Analytics Deliverables & Evaluation Package

## Executive Cover Note

### Headline Finding
Driven by rapid adoption in top-tier medical device and lab test lines, **Guntur sales surged by +122.19% from April to May 2026**, marking a major regional shift against a steady baseline of ₹3,265,191 in overall revenue and ₹492,279 in profit across 2,100 unique orders.

### The 4 Key Artifacts
1. **`app.py` (Streamlit Dashboard):** Interactive, multi-level analytics platform for live data exploration and granular visualization across regions and categories.
2. **CII Narrative (Embedded in `app.py`):** Top-level 3–5 sentence executive summary framing the key metrics, trends, breakdown, and operational call-to-action.
3. **`memo.md` (One-Page Decision Memo):** Strategic action plan detailing core findings, risk trade-offs, inventory reallocation options, and operational recommendations.
4. **`presentation_storyline.md` (Audience Reframing & Defense):** Dual-framed presentation structures (SCR for Executives and OCD for Regional Managers) with Q&A defense strategies for handling live pushback.

### Recommended Review Order
Reviewers are encouraged to consume the package in the following sequence:
1. **Read the Embedded Executive Summary / Narrative** (inside `app.py` or `memo.md`) for high-level context.
2. **Explore `app.py`** to interactively audit the data visualisations and Level 2/3 tables.
3. **Review `memo.md`** to evaluate the core strategic recommendations and risk trade-offs.
4. **Examine `presentation_storyline.md`** to inspect stakeholder reframing and pushback handling.

### Key Unverified Assumption
* **Unverified Assumption Flagged Upfront:** The current inventory allocation models assume that Guntur's +122.19% growth spike represents sustainable regional demand expansion rather than a temporary promotional surge or batch fulfillment anomaly.

---

### Running the Data Pipeline (Parts 1–3)

# Part 1: Dataset regeneration and data cleaning
generate_dataset.py,
clean_data.py

# Part 2: Build database and execute analytical queries
build_db.py,
queries.py,
metrics_engine.py

# Part 3: Automated reports and audit gate testing
draft_report.py,
review_gate.py

### Launching the Interactive Dashboard (Part 4)

Using share.streamlit.io ,login with gmail, create app ,select repository, 
Repository must contain app.py, requirements.txt, pharmeasy.db files.
Select main file path app.py then deploy.this will generate the dashboard.
Access the dashboard in your browser at https://jlfnw2qqon3idfrrdvp3k7.streamlit.app
