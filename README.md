# Automated Technical SEO Audit & Reporting Pipeline 🚀

An end-to-end Technical SEO automation system built using **Python (Google Colab)**, **Google Sheets**, and **Looker Studio** to crawl websites, detect on-page/technical gaps, prioritize developer fixes, and visualize site health.

## 🔗 Live Project Proofs (Click to Explore)
* 📊 **Interactive Looker Studio Dashboard:** [View Live Dashboard](https://datastudio.google.com/reporting/fa676b41-cc92-46cc-994a-f379c57a085b)
* 📑 **Python-Generated SEO Audit Sheet:** [View Audit Data](https://docs.google.com/spreadsheets/d/1ruB2ZfMHqeyRHfg1BqxsV76F1emht__8MWE3u-f7_Ho/edit?usp=sharing)
* ⚙️ **Automated Formula & Logic Sheet:** [View Formula Automation](https://docs.google.com/spreadsheets/d/13AHcXV-XxQdal7ebclbGtUTHQlqWAdlR8qhS2CoBt9Q/edit?usp=sharing)
* 💻 **Google Colab Python Script:** [Open Colab Notebook](https://colab.research.google.com/drive/1FBJwTTGtjaoif2OcJk_DBsWyb1By54mN?usp=sharing)

---

## 🛠️ Architecture & Workflow
1. **Automated Crawling (Python + Google Colab):** Extracts URL-level metadata (`<title>`, meta descriptions), heading hierarchy (`H1`, `H2`, `H3`), and image `alt` attributes.
2. **Rule-Based Audit Logic (Google Sheets):** Uses dynamic formulas to flag missing tags, evaluate character lengths, assign priority (`High`, `Medium`, `Low`), and map business impact.
3. **Executive Visualization (Looker Studio):** Connects processed audit data into an interactive dashboard for instant stakeholder reporting.

## 🔍 Key Audit Checks Automated
* **Title & Meta Optimization:** Checks character limits (50–60 chars for Title, 120–160 chars for Meta) and brand consistency.
* **Heading Structure:** Flags missing `H1` tags and `H2/H3` structural gaps for better crawlability.
* **Image SEO & Accessibility:** Identifies images missing descriptive `alt` attributes.
* **Actionable Roadmap:** Automatically generates a step-by-step fix guide for every detected issue.
