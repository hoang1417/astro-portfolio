---

title: CITES Data Analysis
publishDate: 2023-11-01 00:00:00
img: /assets/cites/data-analysis-for-wildlife-trade-data.png
img_alt: Convention on International Trade in Endangered Species of Wild Fauna and Flora
description: |
  In this personal data analysis project, I explored public CITES trade data using SQL and Tableau to uncover patterns, concentration risks, and underlying drivers in global endangered species trade.
tags:
- Data Analysis
- Data Visualisation
- Hypothesis Analysis

---

> This analysis reveals that global wildlife trade is highly concentrated, with over 80% of trade volume driven by just two plant genera and a single importing country.

#### Overview

* **Problem**: understand global wildlife trade patterns and detect concentration risks that may indicate sustainability or regulatory concerns
* **Approach**: applied exploratory data analysis and hypothesis-driven investigation, including aggregation, segmentation, and comparative analysis across time, species, and product categories
* **Tools**: SQL, Tableau, Excel
* **Outcome**: uncovered key trends, highly concentrated trade patterns, and underlying drivers behind large trade volumes

---

#### Definitions
CITES: Convention on International Trade in Endangered Species of Wild Fauna and Flora

Species protection levels:
* Appendix-I: the most endangered species, trades are exempted only for certain purposes (e.g. scientific research)
* Appendix-II: not necessarily now threatened with extinction but may become so unless trade is closely controlled
* Appendix-III: regulated for trading but still requires international cooperation to prevent unsustainable or illegal exploitation

Biological hierarchy: species → genus → family → order → class

---

#### Overall trend

Illustrating endangered species trade quantity, Figure 1 shows that trade volume is overwhelmingly dominated by Appendix-II species, while Appendix-I and Appendix-III trades remain negligible (only ~0.3% of total trade quantity across the years).

A key observation is the **high volatility in trade volume**, with more than 1,000M kg recorded in 2013, followed by a sharp drop to approximately 150M kg in 2014.

![Endangered species trade quantities worldwide](/assets/cites/CITES-endangered-species.png)
Figure 1. Endangered species trade quantities worldwide

This sharp decline and partial recovery in 2015 indicate that global wildlife trade is **not stable and may be influenced by external factors such as regulation, market demand, or reporting changes**.
Overall, the data suggests a **potential downward trend**, which could indicate improved control measures, although further validation would be required.

---

#### Further data investigation

To better understand the dominance of Appendix-II species, further analysis was conducted to examine **trade concentration across species and countries**.

As shown in Figure 2, trade is **highly concentrated within a small number of genera**.
The top two genera (Gonystylus and Euphorbia) account for more than 80% of total trade volume.

At the country level, imports are also heavily concentrated:

* Switzerland dominates global imports (>85%), indicating a highly centralised trade dependency
* The Netherlands follows with ~5%
* Other countries contribute only marginally

![Appendix II Species imported and Countries importing worldwide](/assets/cites/CITES-imported-species.png)
Figure 2. Appendix II Species imported and Countries importing worldwide.

This reveals a **significant concentration risk**, where global trade volume is dominated by specific species and a single importing country.

---

#### Hypothesis validation

Based on the above findings, a hypothesis was formed:

> Switzerland’s dominant trade volume is closely linked to specific genera and product types.

To validate this, a treemap analysis was performed to examine the relationship between **importing countries, species, and product forms (terms)**.

![Importing countries divided by Appendix II species and term distribution](/assets/cites/CITES-imported-species-by-terms.png)
Figure 3. Importing countries divided by Appendix II species and term distribution

The results confirm a **strong correlation between Switzerland and the two dominant genera (Gonystylus and Euphorbia)**, primarily in the form of:

* timber
* timber pieces
* wax

This suggests that the observed trade concentration is **driven more by industrial demand for specific plant-based products rather than broad biodiversity exploitation**.

This interpretation is consistent with external observations that timber-related industries in Switzerland are well-developed and growing (e.g. Schafer, 2022), which may contribute to higher demand for such materials.

---

#### Key insights

* Over 80% of trade volume is concentrated in just two genera, highlighting a significant concentration risk
* Switzerland dominates global imports (>85%), indicating a highly centralised trade dependency
* Trade patterns are strongly influenced by **product type and downstream industry demand (e.g. timber-related products)**
* Large fluctuations in trade volume suggest **external influences such as regulation, reporting practices, or market conditions**
* High-level trade volume alone can be misleading without understanding **context such as species type and product form**

---

#### Impact & relevance

Although this is an academic project, the analysis demonstrates how data can support:

* **Policy and regulatory monitoring** by identifying unusual concentration or dependency in trade flows
* **Risk identification**, where over-reliance on specific species or regions may indicate sustainability concerns
* **Context-aware decision-making**, showing that trade volume alone is insufficient without understanding product type and industry demand

Overall, this project highlights the importance of **combining data analysis with domain context** to derive meaningful and actionable insights.

---

#### Limitations

* Trade data may be influenced by reporting inconsistencies or regulatory changes
* Observed trends may not fully reflect illegal or unreported trade activities
