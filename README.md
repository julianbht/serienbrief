Alle für das Programm benötigten Dateien befinden sich in dem Ordner Serienbrief. 
Dort sind die Unterordner "bin" und "lib" (für javafx benötigten Dateien) sowie die von mir erstellen Dateien "Serienbrief.jar", "studenten.csv" und "studenten.ser" enthalten. 
Das Herz der Anwendung befindet sich in der Datei "Serienbrief.jar". Die Dateien "studenten.csv" und "studenten.ser" sind zum Einlesen von Beispiel Studenten vorhanden.   

Das Programm lässt sich über die Befehlszeile aus dem Ordner "Serienbrief" mit folgendem Befehl ausführen:
java --module-path "./lib" --add-modules javafx.controls,javafx.fxml -jar "./Serienbrief.jar"

Hier einmal eine Beispiel Ausführung des Programms um die Funktionalität darzustellen: 

Nach Ausführung des obigen Befehls startet das von mir entwickelte Interface.
Es empfiehlt sich zuerst über den Menüpunkt "File" -> "Load" -> "csv" ein paar Beispiel Studenten aus "studenten.csv" einzulesen.
Nun kann man über den grünen Button oben rechts noch eigene Studenten hinzufügen. Es öffnet sich eine Eingabemaske bei der man die Daten des neuen Studenten einträgt. 
Ist man fertig klickt man auf "Speichern" und schließt das Fenster.  
Über den hell blauen Button unten rechts kann man nun den Serienbrief an alle vorhandenen Studenten absenden.
Natürlich wird kein echter Brief abgesendet. Angelehnt an die Serienbrief Übung aus der Prog 1 Übung wird eine Text Datei im Serienbrief Ordner erstellt. 

Das war's! Man könnte sich vorstellen, dass die Studierendenverwaltung mit einem solchem Programm Briefe an Studenten verschickt. 



