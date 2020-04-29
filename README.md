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
    \rhead{Mobile Apps für Android}
    \lhead{Übungsaufgaben}
    \fancypagestyle{plain}{
      \fancyhf{}
      \rhead{Webtechnologien}
      \lhead{Übungsblatt 1}}
---


# 01 | Markup

Sie haben in der Vorlesung das Konzept von Auszeichnungssprachen kennengelernt und am Beispiel von XML erste Einblicke in die Arbeit mit Markupsprachen erhalten. In diesem Übungsblatt sollen sie die bisher erlernten Grundkenntnisse mit Hilfe eines Texteditors praktisch anwenden, um sich mit der Markupsprache XML vertraut zu machen. Laden Sie sich den Texteditor [Sublime Text](https://www.sublimetext.com/) (https://www.sublimetext.com/) herunter, mit welchem wir in diesem Kurs arbeiten werden.

## Aufgabe 1: XML-Wohlgeformheit 

Welcher der folgenden einzelnen Tags sind nach den Regeln der Wohlgeformtheit von XML valide und welche nicht? Begründen Sie ihre Entscheidung.

&lt;Kurs&gt; &lt;dozEnt&gt; &lt;Student/&gt; &lt;name&gt; &lt;Student Semester=3 &gt;&lt;Dozent alter="30"&gt; &lt;XMLelement&gt; &lt;_tag&gt; &lt;&gt; &lt;1anderesTag&gt; &lt;WebTech machtSpaß&gt; &lt;digital.humanities/&gt; 

## Aufgabe 2: Erstellen einer XML-Datei

In dieser Aufgabe sollen Sie eine einfache XML-Datei erstellen, mit Sie die ersten drei Platzierungen dieser Fußballtabelle darstellen. 

![Fußball-Bundesliga Tablle](TableSoccer.PNG)

Betrachten Sie die Tabelle und versuchen Sie alle Bestandteile der Darstellung der einzelnen Mannschaften in Ihrer XML abzubilden.
Überprüfen Sie ihr XML-Dokument anschließend mit Hilfe eines Validators (https://www.xmlvalidation.com/) auf Wohlgeformtheit. Fügen Sie dazu einfach den XML-Code ihres Dokuments in das dafür vorgesehene Feld ein.

## Aufgabe 3:  NetflixXML

Schreiben Sie ein kleines XML-Dokument, das die Onlinevideothek Netflix in stark vereinfachter Form darstellt. Fügen Sie dem XML-Dokument eine einfache DTD hinzu und überlegen Sie sich Regeln, die für NetflixXML gelten sollen. Falls Sie kein/e Netflix Abonnent/in sind, dann überlegen Sie sich, wie Sie selbst eine Onlinevideothek strukturell für den Nutzer aufbauen würden. Es ist völlig ausreichend, wenn Sie pro Kategorie ein Filmbeispiel angeben.



*Abgabekriterien:*

Laden Sie Ihre Antworten bis spätestens 11.5.2020 (23:59 Uhr) als zip-komprimierten Ordner auf GRIPS hoch.  Benennen Sie die einzelnen Dateien pro Aufgabe sinnvoll und verwenden Sie ein geeignetes Format.

Der Name der Datei ergibt sich aus dem Präfix „Übung_HCI_SS18“, der Nr. des Übungsblattes, ihrem Vor- und Nachnamen jeweils getrennt durch _ .

 

Beispiel: **Übung_HCI_SS20_1_Max_Mustermann.zip**

