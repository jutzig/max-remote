---
layout: page
title: MAX! Remote
description: Anleitung
---


* TOC
{:toc}

# Anleitung für Einsteiger zur MAX! Remote-App

## Einleitung

Nachdem man mit der MAX!-Desktopsoftware alle Räume,
Wandthermostate und Heizkörper an einem Cube angemeldet und
konfiguriert hat, ermöglicht diese App die Bedienung und Steuerung
des Cube. Wenn die Desktopsoftware noch nicht vollständig beendet
wurde, dann lässt der Cube keinen Zugriff mit der App zu.

Die Wochenprogrammierung der Tagesverläufe für Zeit/Temperatur
lassen sich grafisch in der Desktopsoftware und/oder in Tabellenform
mit dieser App programmieren.

Der Cube selbst kann nur ein Profil speichern! Innerhalb der
Remote-App kann man viele Profile speichern und falls gewünscht
über die google-Synchronisation sichern oder austauschen.
Gespeicherte Profile aktiviert man aus der App heraus. Dadurch wird
dieses Profil zum Cube gesendet und dort abgelegt. Im Cube verbleibt
das Profil (ohne dort irgendwie erkennbar benannt zu sein) bis zum
nächsten Überschreiben.

## Erste Schritte

Links neben dem MAX! Remote-Icon lässt sich das App-*Menü* öffnen.
Auch das obere, schwarze Feld ist ein anklickbarer Menüpunk unter
dem man Cube Verbindungen verwalten kann.

Es können mehrere Cube Verbindungen angelegt werden (falls man mehrere Cubes besitzt) indem man
jeder Verbindung einen eigenen Namen vergibt.

Im *Übersichtsdisplay* hat man im obersten Feld die Möglichkeit, 'auf
einen Schlag' Einstellungen für alle Räume, Wandthermostate oder
Heizkörper an diesem ausgewählten Cube gleichzeitig vorzunehmen.
Im Übersichtsdisplay eröffnen sich beim Druck auf eine der
*Sollgradzahlen* fast die gleichen Möglichkeiten für den einzelnen
Raum.

Die Möglichkeiten beim Druck auf die Sollgradzahl sind: 

 * `Auto` - Die Temperatur wird entsprechend des aktuellen Wochenprogramms gestellt 
 * `Komfort` - Die Komforttemperatur des Raums (wird in der Desktop Anwendung konfiguriert) 
 * `Eco` - Die Ecotemperatur des Raums (wird in der Desktop Anwendung konfiguriert)
 * `Aus` - Die Temperatur wird auf 3,5 Grad gestellt

Die Schiebereinstellung "dauerhaft EIN/AUS" lässt die Werte manuell (bis
in alle Ewigkeit) oder bis zum nächsten Automatik-Zeitpunkt aus dem
Wochenprogramm wirken.
Bei der Bedienung aller Räume (Sie wissen bereits: im obersten Feld)
kommt noch unter `Erweitert` | `Alle Räume` -> `AUS` in der nachfolgenden Maske die Mehrfachauswahl einzelner Räume hinzu.

Ein Druck auf das Einstellzahnrad unterhalb der jeweiligen
Solltemperatur lässt Sie ein *Wochenprogramm* für den jeweiligen
Raum anlegen, ergänzen oder ändern.

## Zeitgesteuerten Ablauf programmieren (für Fortgeschrittene)

Eine Urlaubsprogrammierung ist innerhalb der MAX!-Remote-App
bis auf weiteres nicht möglich. Die aktuelle MAX!-Remote-App enthält
jetzt ein so genanntes plugin für die Apps Tasker und Llama. Das
ermöglicht - gesteuert durch den (gmail.com-)Terminkalender - auch
die Datum- und/oder zeitabhängige Party-/Urlaubssteuerung aus nah
und fern mit der MAX!-Remote-App. In Llama müsste man die
Bedingung `Kalendereintrag` `[nicht den ganzen Tag]` für eine
Terminnachricht nutzen. Viele Arten von Zeitsteuerungen für
Schichtdienste, Urlaub, Party usw. sind damit prinzipiell eröffnet.


## Contributors

 * Initiale Version: Klaus Richter (vielen Dank)
 * Ergänzungen gerne an jutzig.dev@gmail.com