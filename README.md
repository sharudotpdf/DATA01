# DATA_MINING01
Prüfungsleistung Data Mining Data Science and Management

Dieses Repository enthält das Jupyter-Notebook `spotify_analyse.ipynb`.


## Kurzbeschreibung
Das Projekt beschäftigt sich mit der **Segmentierung von Spotify-Nutzer:innen** auf Basis des öffentlich verfügbaren *Spotify User Behavior Dataset* (Kaggle).  
Ziel ist es, mithilfe moderner **Data-Mining-Methoden** charakteristische Nutzergruppen (Personas) zu identifizieren und deren Merkmale sowie **Upgrade-Bereitschaft** zu Premium-Abos herauszuarbeiten.  
Die Analyse folgt dem **CRISP-DM-Prozessmodell** und umfasst:
- **Business Understanding**: Erkennen der geschäftlichen Relevanz von Free- vs. Premium-Nutzer:innen sowie Free-Nutzer:innen mit hoher Upgrade-Bereitschaft.  
- **Data Understanding & Preparation**: Bereinigung, Transformation und Feature Engineering der größtenteils kategorialen Variablen.  
- **Modeling**: Einsatz von **k-Modes-Clustering** (und ggf. k-Prototypes) zur Gruppierung der Nutzer:innen.  
- **Evaluation**: Bestimmung der optimalen Clusteranzahl (Elbow-Methode), Validierung über Silhouettenwerte und inhaltliche Interpretation.  
- **Deployment**: Ableitung von **Personas** als Grundlage für gezielte Marketing- und Produktstrategien.

Das Projekt zeigt, wie **fragebogenbasierte Daten** auch ohne direkte Verhaltenslogs wertvolle Einblicke in Nutzersegmente liefern können und welche Herausforderungen beim kategorialen Clustering auftreten.

## Voraussetzungen
- Python 3.9+ empfohlen
- Siehe `requirements.txt` für die Python-Abhängigkeiten.

## Installation
```bash
# (optional) neues virtuelles Environment
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate

# Abhängigkeiten installieren
pip install -U pip
pip install -r requirements.txt
```

## Nutzung
```bash
# Jupyter starten
jupyter notebook
# oder JupyterLab
# jupyter lab
```
Öffnen Sie anschließend `spotify_analyse.ipynb` im Browser.

## Struktur & Inhalte
- Business Understanding  
- Data Understanding  
- Data Preparation  
- Modeling (k-Modes)  
- Evaluation  
- Deployment / Personas  

## Reproduzierbarkeit
- Setzen Sie ggf. einen Seed in Zellen, die Zufallszahlen verwenden.
- Überprüfen Sie Pfade zu Datenquellen; passen Sie sie an Ihre Umgebung an.



## Fragen
Bei Fragen schreibe Sie eine Mail an sharujan.premkumar@dbuas.student.de
