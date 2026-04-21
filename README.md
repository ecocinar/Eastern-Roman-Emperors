# Eastern-Roman-Emperors
An interactive data visualization project exploring the reigns of every Eastern Roman (Byzantine) Emperor from Constantine I (306 AD) to Constantine XI (1453 AD).

## Overview

This project combines historical research, data analysis, and interactive visualization to profile 90 Eastern Roman Emperors across multiple dimensions — including reign difficulty, effectiveness, dynasty, and length of rule.

The centerpiece is an interactive scatter chart where each emperor is represented by their portrait, sized by reign length and colored by dynasty, plotted against two custom rating axes.

## The Chart

The scatter chart plots each emperor on two axes:

**Difficulty of Reign (1–20):** Defined by how challenging was the state of the empire at the time of the emperor's ascension to the throne. A score of 1 means they inherited a stable, well-resourced empire with no major threats. A score of 20 means they inherited a near-impossible situation — existential military threats, civil war, financial collapse, or some combination of all three.

**Effectiveness (1–20):** How well the emperor handled their situation relative to what was achievable. This is deliberately judged against circumstances — an emperor who defended Constantinople heroically against impossible odds scores higher than one who squandered a stable inheritance. Loss of territory is not penalized if the emperor otherwise succeeded given their constraints.

A composite score (0–100) is calculated as:
```
Composite = (Effectiveness × 0.6 + Difficulty × 0.4) × 5
```
Effectiveness is weighted more heavily than difficulty since what an emperor achieved matters more than what they were handed.

## Dataset

The core dataset (`ERE_List_20260226.csv`) contains the following fields for each emperor:

- List number, simple name, name with epithets, full Latin/Greek name
- Broad dynasty and family name
- Reign start, end, and length in years
- Summary of reign
- Difficulty and Effectiveness scores (1–20)
- Composite score
- Co-emperor notes
- Usurper flag
- Wikipedia image URL and local image path
- Wikipedia page length and page views (used to identify most notable emperors)

## Naming Convention

Emperor names follow the framework of Anthony Kaldellis — Greek forms are used where appropriate for the middle and late Byzantine period (e.g. Herakleios, Nikephoros, Alexios), while deeply embedded Latin forms are retained where they are universally recognized (e.g. Justinian, Constantine). Epithets are rendered in English where vivid and descriptive (Bulgar-Slayer, the Drunkard), and in Greek where they carry specific Byzantine resonance (Porphyrogennetos, Kopronymos, Mourtzouphlos).

## Tools Used

- **Python** — data processing and HTML generation
- **Pandas** — data manipulation and analysis
- **Jupyter Notebook** — development environment
- **Wikipedia API** — image retrieval and notability metrics
- **HTML / JavaScript / Canvas** — interactive visualization
- **Wikimedia Commons** — emperor portrait images

## Running the Project

1. Clone the repository
2. Open `Untitled.ipynb` in Jupyter Notebook
3. Run the scatter chart cell to regenerate `byzantine_scatter_v3.html`
4. Open `byzantine_scatter_v3.html` in your browser

All emperor images are embedded directly in the HTML file as base64, so no internet connection is required to view the chart.

## Notes and Limitations

- Scores are subjective and reflect one researcher's interpretation of the historical record. They are intended as a starting point for discussion, not definitive rankings.
- Reign dates for the early period (4th–6th century) are sometimes contested among historians and should be treated as approximate.
- Co-emperors who never ruled alone (e.g. Michael IX Palaiologos) are included but are harder to score fairly.
- The Nikaia period (1204–1261) is treated as the legitimate continuation of the Eastern Roman Empire, following mainstream scholarly consensus.
- Trebizond is excluded.

## Contributing

This is a personal project but ideas, corrections, and suggestions are welcome. If you have thoughts on the scoring methodology, naming conventions, or historical accuracy, feel free to open an issue.

## Created By

Eric Cook — 2026

## License

MIT License
