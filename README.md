---
title: SQL Grundlagen 2
author: Martin Kocur
documentclass: scrartcl
classoption:
  - a4paper
header-includes: |
    \usepackage{german} 
	\usepackage{xcolor}
    \usepackage[a4paper,left=2.5cm, right=2.5cm,top=2.5cm, bottom=3cm]{geometry}
    \usepackage{fancyhdr}
    \pagestyle{fancy}
    \fancyhf{}
    \rhead{Webtechnologien}
    \lhead{Übungsblatt}
    \fancypagestyle{plain}{
      \fancyhf{}
      \rhead{Webtechnologien}
      \lhead{Übungsblatt}}





---


# 08 | Normalisierung

- Überführen Sie folgende Relation in 1NF

  |   Abteilung    | Abteilungsnummer | Abteilungsmanager-SSN | Abteilungsstandort          |
  | :------------: | :--------------: | --------------------- | --------------------------- |
  |   Forschung    |        5         | 12345678              | {München, Regensburg, Köln} |
  | Administration |        4         | 88776655              | Hamburg                     |
  | Hauptquartier  |        1         | 87654321              | Berlin                      |

- Überführen Sie folgende Relation in 2NF

  | Matrikelnummer |  Sportart  | Gebühr |
  | :------------: | :--------: | ------ |
  |    9988776     |  Fußball   | 50     |
  |    2233445     | Volleyball | 100    |
  |     998876     |    Golf    | 100    |
  |    2233445     |  Fußball   | 50     |
  |    1234567     |    Golf    | 100    |

- Überführen Sie folgende Relation in 3NF

  |  ID  | Vorname | Nachname | PLZ   | Stadt      |
  | :--: | :-----: | -------- | ----- | ---------- |
  |  1   | Franco  | Moretti  | 94305 | Stanford   |
  |  2   | Manuel  | Baumarkt | 93047 | Schwandorf |
  |  3   | Hartmut | Ilsemann | 30159 | Hannover   |

------

*Abgabekriterien:*

Laden Sie Ihre Antworten bis spätestens 13.07.2020 (23:59 Uhr) als zip-komprimierten Ordner auf GRIPS hoch. Benennen Sie die einzelnen Dateien pro Aufgabe sinnvoll und verwenden Sie geeignete Formate:

- Aufgabe: Ihre drei Datenbanken mit den Tabellen in der entsprechenden Normalform (.sqlite)


Der Name der Datei ergibt sich aus dem Präfix „Übung_WT_SS20“, der Nr. des Übungsblattes, ihrem Vor- und Nachnamen jeweils getrennt durch _ .

 

Beispiel: **Übung_WT_SS20_9_Max_Mustermann.zip**

