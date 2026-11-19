# Gieß den Kiez – Analyse des Gießverhaltens in Berlin

Dieses Repository dokumentiert die wöchentlichen Fortschritte meines Projekts im Kurs **Data Science** an der Berliner Hochschule für Technik (BHT).

## Worum geht's?

Das Projekt basiert auf [Gieß den Kiez](https://www.giessdenkiez.de/) vom CityLAB Berlin. Die Webanwendung dokumentiert seit 2020, welche Stadtbäume in Berlin von Bürger:innen gegossen werden. Die Gießdaten werden regelmäßig als Open Data auf GitHub veröffentlicht und enthalten unter anderem Baum-ID, Standort, Baumart, Pflanzjahr, Gießdatum und Wassermenge.

Die Analyse konzentriert sich auf den Bezirk **Charlottenburg-Wilmersdorf**. Leitfragen sind:

- Wie verändert sich die Beteiligung am Gießen im Laufe der Zeit?
- Welche Faktoren – Baumart, Alter, Jahreszeit, Wetter – beeinflussen das Gießverhalten?
- Lässt sich mit Machine Learning vorhersagen, welche Bäume unter bestimmten Bedingungen gegossen werden?

## Ordnerstruktur

```
├── datasource/   # Rohdaten mit Quellenangaben
├── w1/      # Notebook und Ergebnisse der jeweiligen Kurswoche
├── w2/
├── ...
└── README.md
```

- **Data Source/** enthält alle verwendeten Rohdaten. Die Quellen sind dort jeweils angegeben.
- Für jede Kurswoche wird ein neuer Ordner mit dem jeweiligen Arbeitsstand hinzugefügt.

## Datenquellen

- Gießdaten: [giessdenkiez-de-opendata](https://github.com/technologiestiftung/giessdenkiez-de-opendata) (Technologiestiftung Berlin / CityLAB Berlin)
- Baumbestand: Baumkataster Berlin (Straßen- und Anlagenbäume), Geoportal Berlin
- Wetterdaten: [Open-Meteo Historical Weather API](https://open-meteo.com/) (CC BY 4.0)

## Werkzeuge

Die Analyse erfolgt in **Jupyter Notebook** mit Python (pandas, matplotlib, seaborn).
