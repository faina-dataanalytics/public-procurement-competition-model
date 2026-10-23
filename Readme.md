# AI‑Supported Public Procurement Analytics

Dieses Repository enthält den vollständigen Code, die Notebooks und die Dokumentation für ein datenwissenschaftliches Analyseprojekt im Bereich der öffentlichen Beschaffung in der Europäischen Union. Der Schwerpunkt liegt auf der Untersuchung von Wettbewerb, Effizienz und Digitalisierung sowie auf der Entwicklung KI‑gestützter Analyse‑ und Prognosemodelle. 



## Projektstruktur
Das Repository ist wie folgt aufgebaut:
- **projectmanagement** – ausführliche Projektbeschreibung  
- **data** – Hinweise zur Datenquelle, Data Dictionary  
- **notebooks** – explorative Analyse, Modellierung, NLP, Deep Dives  
- **my_scripts** – produktionsreifer Code (Preprocessing, Features, Modelle)  
- **models** – gespeicherte Modelle (optional)  
- **visuals** – Grafiken und Visualisierungen  
- **germany_deep_dive** – spezifische Analyse für Deutschland  
- **README.md** – kurze Übersicht über das Repository


### Inhalt des Repositories
- Datenvorbereitung und Feature‑Engineering  
- Explorative Datenanalyse (Wettbewerb, Effizienz, Digitalisierung)  
- Modellierung (Prognose der Wettbewerbsintensität, Klassifikation, NLP)  
- Analyse der digitalen Reife europäischer Vergabeverfahren  
- Vergleich EU vs. Deutschland  
- Visualisierungen und Auswertungsergebnisse  

### Technische Hinweise
- Python 3.x  
- pandas, NumPy, scikit‑learn, matplotlib, seaborn  
- optional: XGBoost, CatBoost, spaCy / scikit‑learn NLP  
- große CSV‑Dateien sollten per Chunk‑Loading geladen werden (`load_data.py`)

### Lizenzhinweis für Daten
Die Nutzung der TED‑Daten unterliegt den Bedingungen von *data.europa.eu*.  
Eine korrekte Quellenangabe ist erforderlich.
Die Originaldaten werden aufgrund ihrer Größe nicht im Repository gespeichert.
