---
title: CITES data analysis
publishDate: 2023-11-01 00:00:00
img: /assets/CITES-background-image.jpg
img_alt: Convention on International Trade in Endangered Species of Wild Fauna and Flora
description: |
  Using public data from Convention on International Trade in Endangered Species of Wild Fauna and Flora (CITES),
  this project analyses global wildlife trade data to identify trends, concentration patterns, and potential risks
  in endangered species trading.
tags:
  - Data Analysis
  - Data Visualisation
  - Hypothesis Analysis
---

#### Overview
- **Problem**: understand global wildlife trade patterns and identify unusual concentration or potential risk areas in endangered species trading  
- **Approach**: applied exploratory data analysis and hypothesis-driven investigation to examine trade data across multiple dimensions (species, geography, and product types)  
- **Tools**: SQL, Tableau, Excel  
- **Outcome**: uncovered key trends, highly concentrated trade patterns, and underlying drivers behind large trade volumes  

---

#### Definitions
Species protection levels:
- Appendix-I: the most endangered species, trades are exempted only for certain purposes (e.g. scientific research)
- Appendix-II: not necessarily now threatened with extinction but may become so unless trade is closely controlled
- Appendix-III: regulated for trading but still requires international cooperation to prevent unsustainable or illegal exploitation

Biological hierarchy: species → genus → family → order → class

---

#### Overall trend
Illustrating endangered species trade quantity, Figure 1 shows that trade volume is overwhelmingly dominated by Appendix-II species, while Appendix-I and Appendix-III trades remain negligible (only ~0.3% of total trade quantity across the years).

A key observation is the **high volatility in trade volume**, with more than 1,000M kg recorded in 2013, followed by a sharp drop to approximately 150M kg in 2014.

![ Endangered species trade quantities worldwide](/assets/CITES-endangered-species.png)
<center>Figure 1. Endangered species trade quantities worldwide</center>

This sharp decline and partial recovery in 2015 indicate that global wildlife trade is **not stable and may be influenced by external factors such as regulation, market demand, or reporting changes**.  
Overall, the data suggests a **potential downward trend**, which could indicate improved control measures, although further validation would be required.

---

#### Further data investigation
To better understand the dominance of Appendix-II species, further analysis was conducted to examine **trade concentration across species and countries**.

As shown in Figure 2, trade is **highly concentrated within a small number of genera**.  
The top two genera (Gonystylus and Euphorbia) account for about 80% of total trade volume.

At the country level, imports are also heavily concentrated:
- Switzerland accounts for over 85% of total imports  
- The Netherlands follows with ~5%  
- Other countries contribute only marginally  

![Appendix II Species imported and Countries importing worldwide](/assets/CITES-imported-species.png)
Figure 2. Appendix II Species imported and Countries importing worldwide.

This reveals a **significant concentration risk**, where global trade volume is dominated by specific species and a single importing country.

---

#### Hypothesis validation
Based on the above findings, a hypothesis was formed:

> Switzerland’s dominant trade volume is closely linked to specific genera and product types.

To validate this, a treemap analysis was performed to examine the relationship between **importing countries, species, and product forms (terms)**.

![Importing countries divided by Appendix II species and term distribution](/assets/CITES-imported-species-by-terms.png)
Figure 3. Importing countries divided by Appendix II species and term distribution

The results confirm a **strong correlation between Switzerland and the two dominant genera (Gonystylus and Euphorbia)**, primarily in the form of:
- timber  
- timber pieces  
- wax  

This suggests that the observed trade concentration is **driven more by industrial demand for specific plant-based products rather than broad biodiversity exploitation**.

---

#### Key insights
- Global wildlife trade is **highly concentrated**, both in terms of species and importing countries  
- A small number of genera contribute disproportionately to total trade volume (>80%)  
- Switzerland plays a **dominant role in global imports**, indicating potential dependency on specific supply chains  
- Trade patterns are strongly influenced by **product type and industry demand (e.g. timber-related products)**  
- Large fluctuations in trade volume suggest **external influences such as regulation or market conditions**

---

#### Impact & relevance
Although this is an academic project, the analysis demonstrates how data can support:

- **Policy and regulatory monitoring** by identifying unusual concentration or dependency in trade flows  
- **Risk identification**, where over-reliance on specific species or regions may indicate sustainability concerns  
- **Context-aware analysis**, showing that trade volume alone is insufficient without understanding product type and industry demand  

Overall, this project highlights the importance of **combining data analysis with domain context** to derive meaningful and actionable insights.