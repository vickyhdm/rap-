---
title: "Codebuch Deutschrap"
author: "Luisa Funk"
date: "4 6 2021"
output: html_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

## CODEBUCH

Im Codebuch definieren Sie, wie und nach welchen Kriterien erfasst werden.									
Achtung: das Codebuch wird immer als eigene Datei in Github gesetzt. Beispiel siehe hier.									
								
edgelist:	Grundregel: Die Edgelist darf pro Spalte immer nur einen Wert enthalten. Bis auf die ID idealerweise numerisch codiert (als Zahl).								
from: definiert Sender in gerichteten Netzwerken, entspricht ID in der Nodelist. 								
to: definiert Empfänger in ungerichteten Netzwerken, entspricht ID in der Nodelist. 								

## Attribute:
relationship:	Art der Beziehung (1=neutral, 2=Freundschaft, 3=Feindschaft), fester Zeitpunkt Monat Juni 2021								
feature:	Song zusammen veröffentlicht (1=ein Feature, 2=zwei oder mehr, 3=Album zusammen, 4=Tour zusammen)								
musiclabel:	Zugehörigkeit zum gleichen Label (1=ja, 2=nein)								

nodelist:	Grundregel: die IDs der Nodelist müssen mit den IDs der Edgelist komplett übereinstimmen. Ausprägungen der Attribute in der Regel numerisch definieren							
##Attribute
id:	die ersten drei Buchstaben des Künstlernamens 								
stagename:	Künstlername, Pseudonym								
aka:	bürgerlicher Name								
home:	Wohnort bzw. Hauptsitz des Künstlers								
sex:	binäres System: male oder female. 1=male, 2=female.								
fans:	monatliche Hörer auf Spotify, Skala 1-5 (1=2-2,5 Mio, 2=2,5-3 Mio etc.)								
age:	Alter der Rapper, Skala 1-5 (1=20-24, 2=25-29, 3=30-34, 4=35-39, 5=40<)								
nationality:	Nationalität								
criminality:	Straftaten, Skala 1-5 (1=keine Auffälligkeiten, 2=Kontakt mit Polizei, 3=Verurteilung, 4=Strafe auf Bewährung, 5=Gefängnisstrafe)								
									
NA	definiert fehlende Werte, bei der Datenerhebung das Feld einfach leer lassen, R rechnet NAs (missing values) automatisch raus.								
									
Bearbeitungshinweise									
Achten Sie bitte auf die Kommentare in den Spalten. Diese erklären genauer, welche Daten erfasst werden. 									
Wer seine Daten nicht sauber erstellt muss diese nachbereinigen.									
Dokumentieren Sie jeden Schritt Ihrer Datenerfassung mit, um dies zu rekonstruieren.									
Nutzen Sie das Skript zur Datenbereinigung auf dem letzten Reiter!									
Beispiel für die Dokumentation von Codebuch, Edge- und Nodelist									
https://github.com/hdm-crpr/226305/tree/master/data/crpr2									
Vergeben Sie stets eindeutige Spaltenbeschriftungen. Am besten immer nur ein Begriff ohne Sonderzeichen etc.									

