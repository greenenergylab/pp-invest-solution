# Fallstudie Energiemanagement – Musterlösung  
## Investitionsanalyse für Kraftwerkstechnologien

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/greenenergylab/pp-invest-solution/HEAD?urlpath=%2Fdoc%2Ftree%2FCaseStudy_PP_Profitability_Solution.ipynb)

**Hinweis:** Dieses Jupyter-Notebook stellt die Musterlösung zur Fallstudie _„Investitionsanalyse für Kraftwerke“_ bereit. Es kann direkt im Browser über Binder geöffnet und ausgeführt werden.

---

## Inhalt der Fallstudie

Analysiert werden Investitionsentscheidungen unter Unsicherheit für folgende Technologien:

- Windkraft (Onshore)  
- Biomassekraftwerk  
- Batteriespeicher

Ziel ist eine vergleichende Bewertung auf Basis ökonomischer Kennzahlen, Simulationen und Portfolioansätzen.

---

## Schwerpunkte der Analyse

- Berechnung des Net Present Value (NPV) unter Unsicherheit (Monte-Carlo-Simulation)  
- Sensitivitätsanalyse zentraler Einflussfaktoren  
- Risikoanalyse mit statistischen Kennzahlen (z. B. Value-at-Risk)  
- Portfolio-Optimierung zur Risikominimierung  
- Szenarioanalyse für verschiedene Marktentwicklungen

---

## Nutzungshinweise

### Variante 1 – Direkt im Browser (empfohlen)

1. Auf den Binder-Button oben klicken  
2. Nach kurzer Ladezeit die Datei `CaseStudy_PP_Profitability_Solution.ipynb` öffnen  
3. Zellen der Reihe nach ausführen (Shift + Enter)

### Variante 2 – Lokale Ausführung

```bash
git clone https://github.com/greenenergylab/pp-invest-solution.git
cd pp-invest-solution
pip install -r requirements.txt
jupyter notebook CaseStudy_PP_Profitability_Solution.ipynb
```

---

## Aufbau des Notebooks

1. **Einführung und Modellsetup**  
   Parameterdefinition, NPV-Berechnung pro Technologie

2. **Interaktive Analyse**  
   Parametervariation mit Widgets, Tornado-Diagramme, dynamische Visualisierungen

3. **Monte-Carlo-Simulation**  
   Modellierung von Unsicherheiten, Risikomaße

4. **Portfolio-Optimierung**  
   Risiko-Rendite-Auswertung, effiziente Portfoliozusammenstellungen

5. **Szenarioanalyse**  
   Bewertung unter vordefinierten Marktentwicklungen

---

## Verwendete Bibliotheken

- `numpy`, `pandas` – Datenverarbeitung  
- `plotly`, `matplotlib` – Visualisierung  
- `ipywidgets` – Interaktive Steuerung  
- `scipy` – Optimierung

---

## Fehlerbehebung

**Widgets funktionieren nicht:**  
→ Notebook vollständig durchlaufen oder Kernel neu starten.

**Binder lädt nicht:**  
→ Seite neu laden oder zu einem späteren Zeitpunkt erneut versuchen.

**Visualisierungen erscheinen nicht:**  
→ Sicherstellen, dass alle Bibliotheken korrekt geladen wurden.

---

## Lizenz

Dieses Notebook steht unter der [MIT-Lizenz](LICENSE). Es kann im Rahmen von Studium und Lehre frei verwendet werden.
