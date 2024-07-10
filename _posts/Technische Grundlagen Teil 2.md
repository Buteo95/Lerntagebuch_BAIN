---
title: "Technische Grundlage Teil 1"
date: 15.02.2024
---

Nach dem Mittagessen ging es weiter, es folgt der zweite Teil der Einführung, dieses mal geht es mehr um technische Grundlagen als im ersten Teil.

Doch als erstes füllten wir eine Umfrage aus, Chur als Studierendenstadt. Ich fand es doch sehr ironisch das unsere Klasse dieses ausfüllte der Umfrage ausgewählt wurde. Infolge des extrem unregelmässigen Unterrichts vor Ort in Chur sind die allermeisten schon ausgezogen und leben nicht mehr in Chur. Als einer der letzten vor Ort habe ich meinen Senf dazu gegeben, aber viel Hoffnung auf verbesserung habe ich nicht. 

Als nächstes habe wir das Zeitlimit des Codespaces erhöt, damit dieser nicht gelöscht wird wenn wir Pause machen oder über den Mittag Unterricht haben.
Nachdem alle ihre Einstellungen angepasst hatten, ging es an die erste Übung. Uns wurde ein GitHub Repository zur Verfügung gestellt, sowie eine Aufgabensammlung (Library Carpentry: The Unix Shell: Navigating the filesystem), aus der wir die Kapitel 2 (Navigating the file system) und 3 (Working with files and directories) bearbeiten sollten. Wir hatten Unixbefehle schon in mehreren Modulen behandelt, aber ich bin immer um eine Auffrischung froh, da wir damit noch nie länger gearbeitet und deshalb auch nie richtig im Langzeitgedächtnis abgespeichert haben. Um eine schnell griffbereite Ressource bereit zu haben, stelle ich hier die wichtigsten Befehle noch einmal zusammen:

-pwd (print working directory) – zeigt den path des aktuell geöffneten Ordner an

-ls (list) – zeigt eine Auflistung aller Inhalte des aktuellen Ordners an

-ls -l – gibt die gleiche Liste mit zusätzlichen Informationen, wie die Dateigrösse, an

-ls -lh – gibt die Dateigrösse in nutzbarerer Form an

-cd «Name des Ordners» (change directory) – bewegt sich zum Angegebenen Ordner (Anführungszeichen sind nötig, um mehrere * durch Abstände getrennte worte zu einem Namen zusammenzufügen)

-cd – ohne Argumente bewegt sich zum Home Directory

-cd .. – bewegt sich einen Ordner «nach oben» in der Baumstruktur

-mkdir «Name des neuen Ordners» - erschafft einen Ordner an der aktuellen Stelle mit dem gewünschten Namen

-cat «Name eines Textdokuments» - druckt den gesamten Text eines Dokuments in die Konsole

-head «Name eines Textdokuments» - druckt die ersten zehn Zeilen eines Dokuments

-tail «Name eines Textdokuments» - druckt die letzten Zehn Zeilen

-less «Name eines Textdokuments» - zeigt das Dokument Seite für Seite an, Leertaste für nächste Seite, q um die Ansicht zu beenden

-Wildcards: ? steht für genau ein Zeichen, * steht für beliebig viele Zeichen Bsp: dokument?.txt = dokument1.txt, dokument2.txt *.txt =dokument1.txt, dokument2.txt, text.txt

-mv «alter Name» «neuer Name» (move) – umbenennen einer Datei oder eines Ordners

-mv «Datei» «Ordner» - bewegt die Datei in den angegebenen Ordner

-cp «Datei» «Kopie» - erstellt eine Kopie einer Datei mit dem angegebenen Namen

-rm (remove) – löscht Dateien

-rm -r – löscht Ordner mitsamt den Inhalten

!: Nützlicher Tipp: Nutze tab zur Autovervollständigung von Ordner- und Dateinamen

Als nächstes hat uns der Dozent noch git und GitHub näher erklärt. Git ist eine Software zur Versionskontrolle. GitHub ist eine Plattform, auf der Repositories angelegt werden können, so dass mehrere Entwickler an den gleichen Dateien arbeiten können. Dies erfolgt nicht wie bei bsp, Google Docs per live-Bearbeitung sondern über verschiedene Branches, die dann, nach etwaiger Kontrolle, einander überführt werden.

Zum Abschluss wurde uns noch einmal das Löschen von Codespaces gezeigt und ein Ort angelegt, wo wir die Links zu unseren Lerntagebüchern einfügen können.

Und damit war der erste Tag Pain ... ich meine BAIN vorbei. 
