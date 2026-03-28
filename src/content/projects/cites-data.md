---
title: CITES data analysis
publishDate: 2023-11-01 00:00:00
img: /assets/CITES-background-image.jpg
img_alt: Convention on International Trade in Endangered Species of Wild Fauna and Flora
description: |
  Using public data from Convention on International Trade in Endangered Species of Wild Fauna and Flora (CITES) in the period of 2013-2015, 
  this project aims to identify trading trends and abnormal trading patterns.
tags:
  - Data Analysis
  - Data Visualisation
  - Hypothesis Analysis
---

#### Overview
- **Problem**: analyse trading data to identify trends and patterns
- **Approach**: apply data analysis techniques to examine data in different angles and investigate findings
- **Tools**: SQL, Tableau, Excel
- **Outcome**: identified key trends, patterns, and the reasoning behind them

#### Definitions
Specicies protection levels:
- Appendix-I: the most endangered species, trades are exempted only for certain purposes (e.g. scientific research)
- Appendix-II: not necessarily now threatened with extinction but that may become so unless trade is closely controlled
- Appendix-III: regulated for trading but still needs international cooperation to prevent unsustainable or illegal exploitation

Biological hierarchy: species -> genus -> family -> order -> class


#### Overall trend
Illustrating endangered species trade quantity, Figure 1 highlights that trade quantity was predominated by Appendix-II species, whihle trades related to Appendix I and Appendix III are insignificant 
(contributing only 0.3% of total trade quantity throughout the years). 
Moreover, the trade quantities were highly flutuated over the years, with more than 1,000M kg in 2013, followed by only about 150M kg in 2014 in trade for Appendix-II species.

![ Endangered species trade quantities worldwide](/assets/CITES-endangered-species.png)
<center>Figure 1. Endangered species trade quantities worldwide</center>

By looking at the total trade quantities over time, it is evident that there was a huge drop in 2014 from the top value in 2013, then the quantity bounced back clearly in 2015 but still was just about half of the amount in 2013 (Figure 1). 
The trade movement reveals a potential downtrend even though it is not stable throughout the years. From a conservation perspective, this is a good sign that wild species are being traded less over time.

#### Further data investigation
Beyond the overall trend, another analysis was conducted to reveal deeper insights from the highly centralised trade distribution of Appendix II species.

As demonstrated in Figure 2, within Appendix II species, the trades were highly concentrated for certain endangered genera - the top two genera (Gonystylus and Euphorbia) contributed more than 80% of the trades. 
Additionally, regarding importer countries, a few countries account for most of the import - Switzerland stands for over 85% of trade, followed by Netherlands with 5.18%, while the rest have minor figures.

![Appendix II Species imported and Countries importing worldwide](/assets/CITES-imported-species.png)
Figure 2. Appendix II Species imported and Countries importing worldwide.

The investigation reveals that the trade domination of Appendix II species was imported by a particular country (Switzerland), likely for specific genera (Gonystylus and Euphorbia). It is interesting to further dive deeper into the data to explore whether there is any connection between Switzerland and the two genera.

![Importing countries divided by Appendix II species and term distribution](/assets/CITES-imported-species-by-terms.png)
Figure 3. Importing countries divided by Appendix II species and term distribution

Using another analysis approach, a treemap is used to examine the relation between importer countries and the imported species, plus the product form, or also known as term (Figure 3). From the graph, it can be observed that there is a strong correlation between the top one importer country (Switzerland) with the top two imported genera (Gonystylus, Euphorbia), accounting for most of the total international trades. This analysis confirms our hypothesis aforementioned that Switzerland was importing concentratedly specific genera. 

Furthermore, it is recognisable that “timber pieces”, “wax”, and “timber” are contributing to the top trades from Switzerland of the two identified genera (which are plants). 
This fact shows that the notable pattern in trade quantities could be just because of the nature of the product type, where there is high demand in certain industries, in a particular country. 
According to Schafer (2022), Swiss timber-frame construction is world-leading and growing, backed by research activity from Swiss federal institutions. 
These plant-based products might have huge markets which require a tremendous amount of quantities.

In general, the analysis identified the overall downtrend for international trades of endangered species and which products, countries were importing the most in 2013-2015 period. 
Especially, it is notable that a big portion of trades was focused on plant-based species, in the form of timber, wax, and wood. 
The findings recommend that trade analysis needs to be more specific on context rather than just focusing on the absolute number of trade quantities.