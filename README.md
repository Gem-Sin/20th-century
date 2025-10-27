# 20th Century – Text Mining and Network Analysis

This project explores key relationships between countries mentioned in 20th-century historical texts using web scraping, Natural Language Processing (NLP) and Network Analysis techniques.

## Structure

| Folder | Description |
|---------|--------------|
| notebooks/ | Jupyter notebooks for each CareerFoundry task (1.4–1.7) |
| data/ | Clean text and relationship CSVs used for NLP & network analysis |
| visuals/ | Plots, network visualisations, and HTML interactive graphs |

## Tools
- **Python libraries:** pandas, nltk, spacy, networkx, cdlib, pyvis, matplotlib, seaborn  
- **Visualisation:** PyVis (interactive HTML), Seaborn, Matplotlib

## Highlights
- Extracted named entities and country mentions from 20th-century texts.
- Built a network graph to show inter-country relationships.
- Detected 11 communities using the **Leiden algorithm**.
- Calculated **degree**, **closeness**, and **betweenness** centralities:
  - Germany and France showed the highest degree centrality.
  - China and Japan acted as key bridges (high betweenness).
  - Nordic and Eastern European clusters formed distinct communities.

## Outputs
See `visuals/network_interactive.html` for the interactive network graph.
