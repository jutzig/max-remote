---
layout: page
title: MAX! Remote FAQ
description: Häufig gestellte Fragen
---

* TOC
{:toc}

## Kann ich MAX! Remote auch unterwegs nutzen?

Ja, können Sie. Allerdings wird eine direkte Netzwerkverbindung zum Cube benötigt. Um das von unterwegs zu ermöglichen benötigen Sie eine VPN Verbindung die Sie zunächst in Ihrem Router und Handy einrichten müssen.
Auch Port Forwarding ist möglich, allerdings muss davon dringend abgeraten werden, da es fremden Personen vollen Zugriff auf Ihre Heizung ermöglicht.

Wie VPN eingerichtet werden muss hängt von Ihrem Router Modell ab. Hier finden Sie ein Beispiel für [Fritz!Box]("https://avm.de/service/vpn/tipps-tricks/vpn-verbindung-zur-fritzbox-unter-android-einrichten/")

## Warum wird die Raumtemperatur nicht angezeigt?

Das Heizungsthermostat sendet die Temperatur nur wenn sich die Ventilstellung oder der Modus des Raums (z.B. AUTO, MANUAL,...) ändert.
Falls sich beispielsweise die Ventilsteuerung des Thermostats über längere Zeit nicht verändert hat kennt der Cube die Temperatur nicht und die App kann den Wert nicht anzeigen.

## Ich bekomme eine Fehler wenn ich versuche die Temperatur eines Raumes zu verändern. Was ist das Problem?

Leider hat der Cube ein Stabilitätsproblem. Falls Sie jedesmal wenn Sie die Temperatur ändern möchten die Meldung `Der MAX! Cube hat die neuen Einstellungen nicht rechtzeitig bestätigt` sehen,
denn steckt Ihr Cube vermutlich fest. Die einfachste Möglichkeit das Problem zu beheben, besteht darin den Cube über die App neu zu starten, oder - falls das nicht funktioniert -
den Cube kurz vom Strom zu trennen, wieder zu starten und ein paar Minuten zu warten.
Sobald der Cube wieder initialisiert ist, sollten Sie die Temperatur wieder mit der App ändern können.

Sollten Sie häufig von dem Problem betroffen sein ist es empfehlenswert den Cube regelmäßig vom Strom zu trennen. Eine einfache Lösung dafür ist z.B. eine Steckdose mit Zeitschaltuhr.

## Wird Alexa unterstützt?

Alexa läuft serverseitig, daher lässt sich direkte Alexa Unterstützung nicht umsetzen, da der Server nicht mit Ihrem Cube kommunizieren kann.
Sie können Ihren Cube allerdings über einen Umweg dennoch mit Alexa verwenden. MAX! Remote hat Tasker Unterstützung. Wenn Sie Tasker mit AutoVoice kombinieren, können Sie
Ihre eigenen Sprachkommandos definieren die dann über Tasker ausgeführt werden.

## Wie funktionieren Heizprofile?

Heizprofile sind eine Möglichkeit um schnell zwischen verschiedenen Wochenprogrammen zu wechseln.
Das ist beispielsweise nützlich, wenn Sie in wechselnden Schichten arbeiten, oder ein anderes Wochenprogramm verwenden wollen wenn Sie Urlaub haben.

Um ein Heizprofil zu erstellen sollten Sie zunächst das Wochenprogramm nach Ihren Wünschen einstellen. Sobald Sie zufrieden sind, aktualisieren Sie die App und wählen `Heizprofile`.
Jetzt können Sie das aktuelle Programm unter einem Namen Ihrer wahl abspeichern. Der gleiche Bildschirm wird verwendet um bestehende Heizprofile zu löschen oder zu aktivieren.

_Tipp_: das derzeit aktive Heizprofil wird in Blau dargestellt

## Ich habe ein Heizprofil aktiviert aber die Räume zeigen die falsche Zieltemperatur, was kann ich tun?

Das MAX! System setzt nicht immer die richtie Zieltemperatur nachdem Sie das Wochenprogramm geändert haben. Die einfachste Lösung besteht darin in der App auf <code>Auto</code> zu drücken.
Die App setzt dann die korrekte Zieltemperatur aus dem Wochenprogramm für alle Räume.

## MAX! Remote kann die Rauminformationen nicht laden, was kann ich tun?

Zunächst sollten Sie prüfen ob die richtige IP Adresse eingestellt ist. Sie können zurück zu den Verbindungseinstellungen in dem Sie oben Links im Menü auf Ihre Cube Verbindung tippen und
ansschließend `Cubes verwalten...` auswählen.
Zusätzlich sollten Sie prüfen ob sie WLAN aktiviert haben und ob der Cube korrekt mit dem Netzwerk verbunden ist.
Falls alles korrekt ist, stellen Sie sicher, dass alle anderen Anwendung die sich mit dem Cube verbinden geschlossen sind, da der Cube immer nur eine Verbindung gleichzeitig erlaubt.

## Wird es eine Version für Windows oder IOS geben?

Leider nein

## Wofür steht der Duty Cycle?

Per gesetzlicher Richtlinien darf der Cube nur eine Minute pro Stunde funken.
Der Duty Cycle gibt an, wieviel dieser Sendeleistung verbraucht ist. Steigt der Duty Cycle auf 100% muss der Cube eine Stunde warten
bis neue Befehle gesendet werden können. 