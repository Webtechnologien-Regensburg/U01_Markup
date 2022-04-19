---
title: Auszeichnungssprachen - Extensible Markup Language (XML)
author: Martin Kocur
documentclass: scrartcl
classoption:
  - a4paper
header-includes: |
    \usepackage{german} 
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


# 01 | Markup

Sie haben in der Vorlesung das Konzept von Auszeichnungssprachen kennengelernt und am Beispiel von XML erste Einblicke in die Arbeit mit solchen Sprachen erhalten. In diesem Übungsblatt sollen Sie die bisher erlernten Grundkenntnisse mit Hilfe eines Texteditors praktisch anwenden, um sich mit der Markupsprache XML vertraut zu machen. Laden Sie sich dafür den kostenfreien Texteditor [Visual Studio Code](https://code.visualstudio.com/) (https://code.visualstudio.com/) herunter, mit welchem wir in diesem Kurs arbeiten werden.

## Aufgabe 1: XML-Wohlgeformheit und Validität

a) Welche der einzelnen Tags sind nach den Regeln der Wohlgeformtheit von XML valide und welche nicht? Begründen Sie ihre Entscheidung.

&lt;Kurs&gt; &lt;dozEnt&gt; &lt;Student/&gt; &lt;name&gt; &lt;Student Semester=3 &gt;&lt;Dozent alter="30"&gt; &lt;XMLelement&gt; &lt;_tag&gt; &lt;&gt; &lt;1anderesTag&gt; &lt;WebTech machtSpaß&gt; &lt;digital.humanities/&gt;



b) Zeigen Sie anhand des unten stehenden XML-Dokuments, an welchen Stellen Wohlgeformtheit und Validität gegenüber der angegebenen DTD verletzt werden. Sie können die Zeilennummern verwenden, um die entsprechenden Stellen zu referenzieren.

DTD:

![](C:\Users\LocalAdmin\Documents\GitHub\WebtechÜbung\U01_Markup\DTD.PNG)

 XML:

![](C:\Users\LocalAdmin\Documents\GitHub\WebtechÜbung\U01_Markup\XML.PNG)

## Aufgabe 2: Erstellen einer XML-Datei

In dieser Aufgabe sollen Sie eine einfache XML-Datei erstellen, mit der Sie die Struktur der folgenden Bundesligatabelle im Frauenfußball darstellen.  

![Frauenfußball-Bundesligatabelle (Bild-Quelle: https://www.fussballdaten.de/)](TabelleBundesligaFrauen.png)

Betrachten Sie die Tabelle und versuchen Sie alle Bestandteile der Darstellung der einzelnen Mannschaften in Ihrer XML abzubilden, so dass man mit Hilfe Ihrer XML eine solche Tabelle in einer beliebigen Applikation integrieren könnte.
Überprüfen Sie Ihr XML-Dokument anschließend mit Hilfe eines Validators (https://www.truugo.com/xml_validator/) auf Wohlgeformtheit. Um das zu testen, müssen Sie lediglich den XML-Code ihres Dokuments in das dafür vorgesehene Feld einfügen.

------

*Abgabekriterien:*

Laden Sie Ihre Antworten bis spätestens 02.05.2022 (23:59 Uhr) als zip-komprimierten Ordner auf GRIPS hoch. Benennen Sie die einzelnen Dateien pro Aufgabe sinnvoll und geben Sie folgende Dateien ab:

- Aufgabe 1: Ein PDF-Dokument
- Aufgabe 2: Eine XML-Datei

Der Name des zip-Ordners ergibt sich aus dem Präfix „Übung_WT_SS22“, der Nr. des Übungsblattes, ihrem Vor- und Nachnamen jeweils getrennt durch _ .

 

Beispiel: **Übung_WT_SS22_1_Max_Mustermann.zip**

