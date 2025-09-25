# Portfolio: Datenanalyse- und Machine-Learning-Projekte

Dieses Repository enthält eine Sammlung von Projekten im Bereich Datenanalyse und maschinelles Lernen, die verschiedene Ansätze und Technologien demonstrieren.

## Projektübersicht

### Projekt 1: Datenintegration und Analyse von 7 Bezirksdaten in Hamburg  
**Datei:** `1_BesterBezirkHamburgs.ipynb`  
**Datum:** Dezember 2022  

#### Einleitung
Dieses Projekt konzentriert sich auf die Integration und Analyse von Daten, um den besten Bezirk in Hamburg anhand mehrerer Kriterien zu identifizieren. Mithilfe der Methode „Multi-Criteria Decision Analysis (MCDA)“ wurde eine fundierte Bewertung durchgeführt.

#### Beschreibung
- **Datenquellen**:  
  - Allgemeine Bezirksfakten  
  - Flächeninformationen  
  - Nutzungszwecke der Siedlungsfläche  
  - Händlerzahlen aus einer API  
- **Datenverarbeitung**:  
  - Import, Transformation und Bereinigung der Daten  
  - Umgang mit Attributskorrelationen  
  - Visualisierung in einem Dashboard  
- **Ergebnisse**:  
  Der beste Bezirk wurde mithilfe der MCDA-Methode ermittelt. Die Ergebnisse sind in der Datei **BesterBezirkHamburgs** dokumentiert.

#### Technologien
- **Datenverarbeitung**: Python (pandas, numpy, requests)  
- **Visualisierung**: Matplotlib, Seaborn, Dash  

---

### Projekt 2: Vergleich von Self-Trained und Pre-Trained Modellen in der Bildregression  
**Datei:** `2_Pawpularity`  
**Datum:** März 2023  

#### Einleitung
In diesem Projekt wurden die Leistungen von Self-Trained und Pre-Trained Modellen bei einer Bildregressionsaufgabe verglichen. Ziel war es, den sogenannten Pawpularity-Score – eine Kennzahl für die Attraktivität von Fotos verlassener Haustiere – vorherzusagen, um deren Chancen auf eine Adoption zu erhöhen.

#### Beschreibung
- **Daten**:  
  - 9.912 Haustierbilder mit entsprechenden Pawpularity-Scores  
  - Einheitliche Datenvorbereitung, einschließlich Bildskalierung und Datenaugmentation  
- **Ansatz**:  
  - Ein Self-Trained Modell basierend auf einem spezifischen CNN-Ansatz  
  - Pre-Trained Modelle mit ResNet-Architekturen (ResNet50, ResNet101, ResNet152)  
  - Test von zwei Verlustfunktionen (MSE und MAE)  
  - Bewertung anhand von RMSE, MAE und Trainingszeit  

#### Ergebnisse
- Self-Trained Modelle eignen sich für spezifische Aufgaben und begrenzte Ressourcen.  
- Pre-Trained Modelle zeigen Vorteile bei generischen Aufgaben mit ähnlichen Datensätzen.  
- MSE erwies sich als zuverlässiger als MAE.  
- Die Ergebnisse sind im Paper **Pawpularity.pdf** dokumentiert.

#### Technologien
- **Modelltraining**: TensorFlow, Keras  
- **Datenvorbereitung**: Python (pandas, sklearn), ImageDataGenerator  
- **Frameworks**: ResNet-Architekturen (ResNet50, ResNet101, ResNet152)  

---

### Projekt 3: Erklärbare Künstliche Intelligenz (XAI) in der Wirtschaft  
**Datei:** `3_XAI.pdf`  
**Datum:** Juli 2023  

#### Einleitung
Dieses Projekt untersucht Methoden der erklärbaren künstlichen Intelligenz (XAI) zur Einkommensprognose anhand des Census-Datensatzes. Ziel war es, komplexe Modelle verständlicher und transparenter zu machen.

#### Beschreibung
- **Datensatz**: Census-Einkommensdatensatz  
- **Ansatz/Technologien**:  
  - **Facets Dive**: Visualisierung relevanter Merkmale und deren Muster  
  - **What-If Tools**: Analyse von Fairness und Optimierung durch Manipulation von Datenpunkten und Slicing  
  - **SHAP**: Intuitive Darstellung der Merkmalbedeutung und partiellen Abhängigkeiten  
  - **LIME**: Erklärung individueller Vorhersagen durch Ersatzmodelle  

---

### Projekt 4: Modell-Drift  
**Dateien:** `4_Drift`  
**Zeitraum:** März 2023 – Sep 2025  

#### Einleitung
Dieses umfassende Projekt behandelt das Thema „Modell-Drift“ und ist in vier Teile gegliedert, die über vier Semester hinweg bearbeitet wurden. Es bildet die Grundlage der aktuell geschriebenen Masterarbeit. Im Fokus steht die Python-Bibliothek „Evidently“, die in drei Hauptkomponenten unterteilt ist: Reports, Test Suites und Monitoring-Dashboard. Am Ende September 2025 wurden die vollständige Masterarbeit sowie die dazugehörigen Jupyter Notebooks hinzugefügt.

#### Beschreibung
- **Forschungswerkstatt 1: Evidently Reports (`4_1_Drift_Report.pdf`)**:  
  - Einführung in das Thema „Modell-Drift“  
  - Erste Experimente zu Datendrift in Klassifikations- und Regressionsaufgaben (z. B. Brustkrebs-, Housing-Daten)  
- **Grundprojekt: Evidently Monitoring-Dashboard (`4_2_Drift_Dashboard.pdf`)**:  
  - Experiment mit Evidently-Dashboards basierend auf dem Census-Datensatz  
- **Forschungswerkstatt 2: Messe-Präsentation (`4_3_Drift_Poster.pdf`)**:  
  - Präsentation der bisherigen Ergebnisse auf einer hochschulweiten Messe  
- **Hauptprojekt: Evidently-Integration in Architektur (`4_4_Drift_Architektur.pdf`)**:  
  - Implementierung einer ML-Monitoring-Architektur mit Prefect für Batch-Jobs, Evidently für Drift-Analysen und Grafana zur Visualisierung  
- **Masterarbeit (`4_5_Drift_Masterarbeit.pdf` + Jupyter Notebooks)**:
  - Untersuchung verschiedener Ansätze zur Modelldrift-Erkennung, darunter datenverteilungsbasierte, leistungsbasierte, mehrfachhypothesenbasierte und kontextbasierte Methoden
  - Theoretische Erläuterung der Algorithmen sowie experimenteller Vergleich hinsichtlich Genauigkeit und Effizienz

#### Technologien
- **Python**: pandas, sklearn, Evidently, scikit-multiflow
- **Workflow-Orchestrierung**: Prefect  
- **Visualisierung**: Grafana  

---

### Projekt 5: Happiness Dashboard (Tableau)
**Dateien:** https://public.tableau.com/app/profile/nhut.hoa.huynh/viz/NhutHoa_Huynh_Happyness_Ver2/Dashboard1
**Zeitraum:** Sep 2025  

#### Einleitung
Visualisierung und Analyse zu Faktoren, die sich auf das Wohlbefinden auswirken

## Kontakt
Für Fragen oder Feedback zu den Projekten können Sie mich gerne kontaktieren.  