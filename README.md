---
title: SQL Grundlagen
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


# 08 | Einfache SQL-Abfragen

In dieser Aufgabe sollen Sie einfache SQL-Abfragen stellen, um die gewünschten Daten aus der Ihnen zur Verfügung gestellten _MovieDatabase_ auszulesen. Verwenden Sie das in der Vorlesung besprochene Tool  [\textcolor{blue}{DB Browser für SQLite}](https://sqlitebrowser.org/), um die Datenbank zu importieren und ihre SQL-Abfragen zu formulieren. Schreiben Sie anschließend SQL-Queries, mit welchen Sie

- alle Filmtitel auflisten.

- alle Filmtitel und die dazugehörigen Erscheinungsjahre auflisten.
- alle amerikanischen Filme ausgeben.
- das Jahr herausfinden, in dem der Film Avatar erschienen ist.
- alle Filme, die länger als 150 Minuten dauern, auflisten.
- alle Filme, die im Jahr 2020 erschienen sind, ausgeben.
- alle Filme, die vor dem Jahr 2000 erschienen sind, auflisten.
- die Anzahl aller in der Datenbank gespeicherten Filmen ausgeben.
- die Anzahl aller in der Datenbank gespeicherten amerikanischen Filme ausgeben.
- alle Filme, die zwischen 160 und 180 Minuten dauern, auflisten.
- alle amerikanischen Filme, die länger als 110 Minuten und weniger als 160 Minuten dauern, ausgeben.

------

*Abgabekriterien:*

Laden Sie Ihre Antworten bis spätestens 06.07.2020 (23:59 Uhr) als zip-komprimierten Ordner auf GRIPS hoch. Benennen Sie die einzelnen Dateien pro Aufgabe sinnvoll und verwenden Sie geeignete Formate:

- Aufgabe: Eine SQL-Datei (.sql) mit allen Queries


Der Name der Datei ergibt sich aus dem Präfix „Übung_WT_SS20“, der Nr. des Übungsblattes, ihrem Vor- und Nachnamen jeweils getrennt durch _ .

 

Beispiel: **Übung_WT_SS20_8_Max_Mustermann.zip**

