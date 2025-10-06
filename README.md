# 🌍 CO₂ Emissions Analysis (1900–2025)

This repository contains a complete data analysis project focused on the evolution of global CO₂ emissions over more than a century. The goal is to explore emission trends, analyze key drivers, and communicate insights through clear visualizations.

---

## 📚 Table of Contents

- [English Version](#english-version)
  - [Project Overview](#project-overview)
  - [Objectives](#objectives)
  - [Tech Stack](#tech-stack)
  - [Data](#data)
  - [Key Results](#key-results)
  - [Visualizations](#visualizations)
  - [Learnings](#learnings)
  - [Future Work](#future-work)
  - [Project Structure](#project-structure)
- [Deutsche Version](#deutsche-version)

---

## 🇬🇧 English Version

### Project Overview

This project explores global CO₂ emissions data from 1900 to 2025 using Python. The aim is to understand long-term emission trends, analyze differences between energy sources, and highlight the contribution of the largest emitting countries. The focus is on data cleaning, transformation, visualization, and deriving insights that support environmental decision-making.

### Objectives

- Analyze historical global CO₂ emissions over time  
- Break down emissions by source (coal, oil, gas)  
- Identify the top 10 emitting countries and how their contributions evolved  
- Create clear and meaningful visualizations of key trends  
- Derive insights that can inform climate strategies and sustainability policies  

### Tech Stack

- **Languages & Libraries:** Python (Pandas, NumPy, Matplotlib, Seaborn, Plotly)  
- **Tools:** Jupyter Notebook  

### Data

The datasets include annual CO₂ emissions by country and by source. They are based on publicly available historical data (e.g. *Our World in Data*).

- `co2_total.csv` – total annual CO₂ emissions  
- `co2_coal.csv` – emissions from coal  
- `co2_oil.csv` – emissions from oil  
- `co2_gas.csv` – emissions from gas  

### Key Results

- Global CO₂ emissions have increased more than twentyfold since 1900.  
- Fossil fuels remain the dominant sources, though their relative shares have shifted.  
- The ten largest emitters account for more than 70% of global emissions.  
- Emerging economies have become significant contributors in the last three decades.  

### Visualizations

The analysis includes several visual components, such as:

- Total global CO₂ emissions over time  
- Comparison of emissions by energy source  
- Share of global emissions by the top 10 countries  
- Evolution of emissions for key individual countries  

### Learnings

This project improved my skills in data cleaning, exploratory data analysis, and visualization. It also taught me how to turn raw datasets into meaningful insights and communicate them through data storytelling.

### Future Work

- Extend the analysis with per-capita and sector-level emissions  
- Explore correlations with GDP and population data  
- Build an interactive dashboard using Streamlit or Power BI  

### Project Structure

```
├── data/                         # CSV datasets  
├── notebooks/                    # Jupyter Notebooks  
│   └── Daten_analyse_Co2_Emissonen.ipynb  
├── figures/                      # Generated visualizations  
├── scripts/                      # Data processing scripts  
└── README.md                     # Project documentation  
```

---

## 🇩🇪 Deutsche Version

### Projektübersicht

In diesem Projekt werden weltweite CO₂-Emissionsdaten von 1900 bis 2025 mit Python analysiert und visualisiert. Ziel war es, langfristige Emissionstrends besser zu verstehen, Unterschiede zwischen Energiequellen herauszuarbeiten und die Beiträge der größten Emittenten im Zeitverlauf zu untersuchen. Der Schwerpunkt liegt auf Datenaufbereitung, Transformation, Visualisierung und der Ableitung von Erkenntnissen, die für nachhaltige Entscheidungen relevant sind.

### Ziele

- Analyse der globalen CO₂-Emissionen im historischen Verlauf  
- Aufschlüsselung der Emissionen nach Energiequellen (Kohle, Öl, Gas)  
- Identifizierung der zehn größten Emittenten und Analyse ihrer Entwicklung  
- Erstellung verständlicher und aussagekräftiger Visualisierungen zentraler Trends  
- Ableitung von Erkenntnissen für Klimastrategien und Nachhaltigkeitsmaßnahmen  

### Technologien

- **Programmiersprache & Bibliotheken:** Python (Pandas, NumPy, Matplotlib, Seaborn, Plotly)  
- **Arbeitsumgebung:** Jupyter Notebook  

### Datengrundlage

Die Analyse basiert auf öffentlich verfügbaren Datensätzen (z. B. *Our World in Data*), die jährliche CO₂-Emissionen pro Land und Energiequelle enthalten.

- `co2_total.csv` – Gesamte jährliche CO₂-Emissionen  
- `co2_coal.csv` – Emissionen aus Kohle  
- `co2_oil.csv` – Emissionen aus Öl  
- `co2_gas.csv` – Emissionen aus Gas  

### Zentrale Ergebnisse

- Die globalen CO₂-Emissionen haben sich seit 1900 mehr als verzwanzigfacht.  
- Fossile Brennstoffe bleiben die Hauptquelle, ihre Anteile haben sich jedoch verändert.  
- Die zehn größten Emittenten verursachen gemeinsam über 70 % der weltweiten Emissionen.  
- Schwellenländer spielen in den letzten Jahrzehnten eine zunehmend bedeutende Rolle.  

### Visualisierungen

Die Analyse umfasst verschiedene Visualisierungen, darunter:

- Entwicklung der weltweiten CO₂-Emissionen über die Zeit  
- Vergleich der Emissionen nach Energiequelle  
- Anteil der globalen Emissionen durch die zehn größten Länder  
- Emissionsverlauf einzelner wichtiger Länder  

### Erkenntnisse

Im Rahmen des Projekts konnte ich meine Fähigkeiten in der Datenaufbereitung, explorativen Datenanalyse und Visualisierung vertiefen. Außerdem habe ich gelernt, umfangreiche Datensätze in aussagekräftige Erkenntnisse zu überführen und diese verständlich zu kommunizieren.

### Ausblick

- Erweiterung der Analyse um Pro-Kopf-Emissionen und sektorale Betrachtungen  
- Untersuchung von Zusammenhängen zwischen Emissionen, BIP und Bevölkerungsentwicklung  
- Entwicklung eines interaktiven Dashboards mit Streamlit oder Power BI  
