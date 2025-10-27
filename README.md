#  20th Century – Network Visualisations and Natural Language Processing with Python

This project explores key relationships between countries mentioned in 20th-century historical texts using **web scraping**, **Natural Language Processing (NLP)**, and **Network Analysis** techniques.

The analysis follows CareerFoundry’s Data Analytics program (Tasks 1.4 – 1.7), covering data extraction, cleaning, NLP feature generation, and interactive graph visualisation.

---

## Structure

| Folder | Description |
|:--|:--|
| `notebooks/` | Jupyter notebooks for each CareerFoundry task (1.4–1.7). |
| `data/` | Clean text and relationship CSVs used for NLP and network analysis. |
| `outputs/` | HTML network graphs and exported results. |
| `outputs/visualisations/` | PNG plots and visualisation outputs from analysis. |

---

## Tools and Libraries

**Python:**
- `pandas`, `nltk`, `spacy`, `networkx`, `cdlib`, `pyvis`, `matplotlib`, `seaborn`

**Visualisation:**
- `PyVis` (interactive HTML graphs)  
- `Seaborn` and `Matplotlib` for static plots  

**Community Detection:**
- `Leiden` algorithm via `cdlib` to identify clusters of countries

---

## Highlights

- Extracted named entities and country mentions from a 20th-century text corpus.
- Built a **network graph** showing relationships between countries.
- Detected **11 communities** using the Leiden algorithm.
- Calculated **degree**, **closeness**, and **betweenness** centralities to find influential countries:
  - **Germany** and **France** show the highest degree centrality.
  - **China** and **Japan** act as key bridges (high betweenness).
  - Nordic and Eastern European countries form distinct clusters.

---

## Outputs

| File | Description |
|:--|:--|
| `outputs/network_interactive.html` | Interactive country network graph (PyVis). |
| `outputs/network_leiden.html` | Network visualisation colored by Leiden communities. |
| `outputs/visualisations/` | Static PNG plots showing top countries, adjectives, and more. |

---

See the interactive graphs here:

- [Interactive network](outputs/network_interactive.html)
- [Leiden communities network](outputs/network_leiden.html)







