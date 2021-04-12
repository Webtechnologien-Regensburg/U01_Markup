---
title: Auszeichnungssprachen - Extensible Markup Language (XML)
author: Jakob Fehle
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

## Aufgabe 1: XML-Wohlgeformheit 

Welche der einzelnen Tags sind nach den Regeln der Wohlgeformtheit von XML valide und welche nicht? Begründen Sie ihre Entscheidung.

&lt;Kurs&gt; &lt;dozEnt&gt; &lt;Student/&gt; &lt;name&gt; &lt;Student Semester=3 &gt;&lt;Dozent alter="30"&gt; &lt;XMLelement&gt; &lt;_tag&gt; &lt;&gt; &lt;1anderesTag&gt; &lt;WebTech machtSpaß&gt; &lt;digital.humanities/&gt; 

## Aufgabe 2: Erstellen einer XML-Datei

In dieser Aufgabe sollen Sie eine einfache XML-Datei erstellen, mit der Sie die Struktur der folgenden Bundesligatabelle im Frauenfußball darstellen. 

![Frauenfußball-Bundesligatabelle]("Tabelle Bundesliga Frauen .png"){#fig:Frauenfußball-Bundesligatabelle (Quelle: https://www.fussballdaten.de/)}

Betrachten Sie die Tabelle und versuchen Sie alle Bestandteile der Darstellung der einzelnen Mannschaften in Ihrer XML abzubilden, so dass man mit Hilfe Ihrer XML eine solche Tabelle in einer beliebigen Applikation integrieren könnte.
Überprüfen Sie Ihr XML-Dokument anschließend mit Hilfe eines Validators (https://www.xmlvalidation.com/) auf Wohlgeformtheit. Um das zu testen, müssen Sie lediglich den XML-Code ihres Dokuments in das dafür vorgesehene Feld einfügen.

## Aufgabe 3:  NetflixXML

Schreiben Sie ein kleines XML-Dokument, das die Onlinevideothek Netflix in stark vereinfachter Form darstellt. Fügen Sie dem XML-Dokument eine einfache DTD hinzu und überlegen Sie sich Regeln, die für NetflixXML gelten sollen. Sie können sich an folgender DTD orientieren (https://www.w3schools.com/xml/xml_dtd_intro.asp). Falls Sie kein/e Netflix Abonnent/in sind und somit die Struktur dieser Onlinevideothek nicht kennen, dann überlegen Sie sich, wie Sie selbst eine Onlinevideothek strukturell für den Nutzer aufbauen würden. Es ist völlig ausreichend, wenn Sie pro Kategorie ein Filmbeispiel angeben. Sie können Ihr XML-Dokument auf 40 Zeilen Code beschränken. Überprüfen Sie Ihr XML-Dokument anschließend mit Hilfe eines Validators (https://www.xmlvalidation.com/) auf Wohlgeformtheit und Validität. 

------

*Abgabekriterien:*

Laden Sie Ihre Antworten bis spätestens 22.04.2020 (23:59 Uhr) als zip-komprimierten Ordner auf GRIPS hoch.  Benennen Sie die einzelnen Dateien pro Aufgabe sinnvoll und geben Sie folgende Dateien ab:

- Aufgabe 1: Ein PDF-Dokument
- Aufgabe 2 und 3: Jeweils eine XML-Datei

Der Name des zip-Ordners ergibt sich aus dem Präfix „Übung_WT_SS21“, der Nr. des Übungsblattes, ihrem Vor- und Nachnamen jeweils getrennt durch _ .

 

Beispiel: **Übung_WT_SS21_1_Max_Mustermann.zip**

