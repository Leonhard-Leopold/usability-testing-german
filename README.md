# Usability Testing - Browser-Erweiterung
Eine Browser-Erweiterung, die das Erstellung und das Durchführung von Usability-Tests sowie die Visualisierung der Testergebnisse ermöglicht.

## Einen Test erstellen
Mit dieser Browser-Erweiterung können Sie einen Remote-Usability-Test durchführen, um jede Webanwendung zu verbessern. Der Benutzer hat die Möglichkeit, einen neuen Test zu erstellen, der mehrere Aufgaben enthält, bei denen entweder eine bestimmte URL erreicht oder ein Element angeklickt werden muss, um sie zu erledigen. Zusätzlich kann, falls gewünscht, jeder Aufgabe ein Zeitlimit hinzugefügt werden. Bei der Auswahl des gewünschten Ziels hat der Ersteller eines Tests die Möglichkeit, auf das gewünschte Ziel direkt auf der Webseite zu klicken.

## Einen Test durchführen
Nachdem ein Test erstellt wurde, kann er heruntergeladen und an beliebig viele Tester versendet werden. Jeder Tester kann nun die Testdatei hochladen, um den Usability-Test automatisch zu starten. Es wird kein Moderator benötigt, da das Plugin ein Overlay anzeigt, das den Teilnehmer alleine durch den Test führt. Wenn alle Aufgaben abgeschlossen sind (erfolgreich oder nicht), wird eine Ergebnisdatei erstellt. Diese Datei kann über verschiedene Methoden zurückgeschickt werden.

- Wenn der Ersteller des Tests eine E-Mail-Adresse angegeben hat, kann die Ergebnisdatei zurückgeschickt werden.
- Wenn der Ersteller [dieses](https://github.com/Leonhard-Leopold/usability-testing-german/blob/master/server/storeResults.php) PHP-Skript hochlädt und bei der Erstellung des Tests die korrekte URL zu dem Skript angibt, können die Testergebnisse auf einem Server gespeichert werden.
- Wenn keine dieser beiden Optionen gewünscht wird, hat der Tester auch die Möglichkeit, die Ergebnisdatei herunterzuladen, um sie auf einem anderen Weg zu versenden.

## Visualisierung der Ergebnisse
Wenn der Ersteller des Tests alle Ergebnisdateien gesammelt hat, können diese mit dieser Erweiterung visualisiert werden, wobei die Erfolgsrate, die durchschnittliche Zeitdauer und alle von den Testern hinterlassenen Kommentare berechnet und angezeigt werden. Dies kann verwendet werden, um festzustellen, wo Benutzer Schwierigkeiten hatten, das gewünschte Ziel zu finden, um die Webanwendung zu verbessern.

## Andere Informationen
Es ist auch möglich, einen Test [hier](http://leoleo.at/usabilityTest/) in einem größeren Fenster als in der Browser-Erweiterung zu erstellen und die Ergebnisse zu visualisieren.

Diese Implementierung ist in zwei Sprachen - Deutsch und [Englisch](https://github.com/Leonhard-Leopold/usability-testing/) verfügbar.
