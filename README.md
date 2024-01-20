# Addressing Changes in the EUR-Lex Case-Law Directory Classification Scheme

Scholars of the Court of Justice of the European Union (CJEU) are interested in the development of case-law over time. However, the CJEU implemented a fundamental change to the classification scheme in its directory of case-law after the Treaty of Lisbon, in effect since 2010 (1). This shift makes it challenging to compare the development of case-law across substantive areas over time. This may constrain machine learning models, which can be trained on data from the past few years rather than a more extended period of time.

Here I offer some Python code to create a mapping between the case-law directory classification schemes before and after Lisbon. The code takes the pre-Lisbon classification scheme (level 1 and 2) and assigns post-Lisbon categories, where applicable. Doing so, it bridges the break from changing classification scheme, allowing researchers to make full use of the entire history of case-law. 

The code can be plugged into your data project. 

(1) Link to source: https://eur-lex.europa.eu/browse/directories/new-case-law.html

