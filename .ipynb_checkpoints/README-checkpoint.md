# Portfolio: Data Analysis and Machine Learning Projects

Dieses Repository enthält eine Sammlung von Projekten im Bereich Datenanalyse und maschinelles Lernen, die verschiedene Ansätze und Technologien demonstrieren. 

## Projektübersicht

### Projekt 1: Datenintegration und Analyse von 7 Bezirksdaten Hamburg ("BesterBezirkHamburgs", Dezember 2022)

#### Einleitung
Dieses Projekt konzentriert sich auf die Integration und Analyse von Daten, um den besten Bezirk in Hamburg basierend auf mehreren Kriterien zu identifizieren. Mithilfe der "Multi-Criteria Decision Analysis (MCDA)" wurde eine fundierte Bewertung durchgeführt.

#### Beschreibung
- **Datenquellen**: Vier Datensätze, darunter allgemeine Bezirksfakten, Flächeninformationen, Nutzungszwecke der Siedlungsfläche und Händlerzahlen aus einer API.
- **Datenverarbeitung**: Import, Transformation und Bereinigung, einschließlich der Behandlung von Attributskorrelationen und Visualisierung in einem Dashboard.
- **Ergebnisse**: Der beste Bezirk wurde mithilfe von MCDA ermittelt, und die Ergebnisse sind in der Datei **BesterBezirkHamburgs** dokumentiert.

#### Technologien
- **Datenverarbeitung**: Python (pandas, numpy, requests)
- **Visualisierung**: Matplotlib, Seaborn, Dash

---

### Projekt 2: Vergleich von Self-Trained und Pre-Trained Modellen bei der Bildregression ("Pawpularity", März 2023)

#### Einleitung
In diesem Projekt wurden die Leistungen von Self-Trained und Pre-Trained Modellen bei einer Bildregressionsaufgabe verglichen. Ziel war es, den Pawpularity Score – eine Kennzahl für die Attraktivität von Fotos verlassener Haustiere – vorherzusagen, um deren Chancen auf eine Adoption zu erhöhen.

#### Beschreibung
- **Ansatz**:
  - Ein Self-Trained Modell basierend auf einem spezifischen CNN-Ansatz.
  - Pre-Trained Modelle mit ResNet-Architekturen (ResNet50, ResNet101, ResNet152).
- **Daten**:
  - 9.912 Haustierbilder mit Pawpularity Scores.
  - Einheitliche Datenvorbereitung, einschließlich Bildskalierung und Datenaugmentation.
- **Vergleich**:
  - Zwei Verlustfunktionen (MSE und MAE) getestet.
  - Bewertung anhand von RMSE, MAE und Trainingszeit.

#### Ergebnisse
- Das Self-Trained Modell war effizienter und lieferte ähnliche Ergebnisse wie ResNet50 und ResNet101.
- ResNet152 zeigte Überanpassung und schlechte Leistung.
- MSE war zuverlässiger als MAE.

#### Fazit
- Self-Trained Modelle sind bei spezifischen Aufgaben und begrenzten Ressourcen vorteilhaft.
- Pre-Trained Modelle eignen sich besser für generische Aufgaben mit ähnlichen Datensätzen.
- Ergebnisse sind in dem Paper **Pawpularity.pdf** dokumentiert.

#### Technologien
- **Modelltraining**: TensorFlow, Keras
- **Datenvorbereitung**: Python (pandas, sklearn), ImageDataGenerator
- **Frameworks**: ResNet-Architekturen (ResNet50, ResNet101, ResNet152)

---

## Kontakt
Für Fragen oder Feedback zu den Projekten können Sie mich gerne kontaktieren.