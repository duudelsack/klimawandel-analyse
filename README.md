# Klimawandel in Daten

Explorative Datenanalyse und Visualisierung zum Klimawandel: CO2-Emissionen, Temperatur, Meeresspiegel, Meereis, Naturkatastrophen und Gesundheit.

Gruppenprojekt im Kurs **Data Science 2** (2. Semester, Bachelor Künstliche Intelligenz, HAW Landshut, SoSe 2025).

## Inhalt

| Datei | Inhalt |
|---|---|
| `klimawandel_analyse.ipynb` | Hauptanalyse: CO2-Emissionen absolut, pro Kopf und logarithmisch, Temperatur, Meereis |
| `visualisierungen.ipynb` | Katastrophen, Krankheiten, Meeresspiegel und Emissionen nach Sektor |
| `engere_auswahl_visualisierung.ipynb` | Auswahl der Visualisierungen für die Präsentation |
| `co2_vergleich.ipynb` | Vergleich der Emissionen nach Sektor mit Daten von Climate TRACE |
| `data/` | die verwendeten Datensätze |

## Daten

| Datei | Quelle |
|---|---|
| `owid-co2-data.csv`, `co-emissions-by-sector.csv` | Our World in Data |
| `nasa_temperature.csv` | NASA GISS, globale Temperaturabweichung |
| `N_09_extent_v3.0.csv`, `S_09_extent_v3.0.csv` | NSIDC Sea Ice Index, Meereisausdehnung im September |
| `1900_2021_DISASTERS.xlsx - emdat data.csv` | EM-DAT, internationale Katastrophendatenbank |
| `sea_level_data.csv` | Meeresspiegel |
| `climate_disease_dataset.csv` | Klima und Krankheiten |

Die Rohdaten von Climate TRACE für `co2_vergleich.ipynb` sind über 20 GB groß und deshalb nicht im Repository. Sie stehen frei unter [climatetrace.org](https://climatetrace.org/data).

## Ausführen

```bash
pip install pandas numpy matplotlib seaborn plotly jupyter
jupyter notebook klimawandel_analyse.ipynb
```
