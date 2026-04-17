# BioGraph Pro
### Ein KI-generiertes Werkzeug für die digitale Biografiearbeit

Dieses Projekt ist im Rahmen des Projektstudiums im Studiengang **Soziale Arbeit** an der **Ostfalia Hochschule für angewandte Wissenschaften** entstanden. Es dient als Demonstration für **Vibe Coding**, die Erstellung funktionaler Software durch gezieltes Prompt-Engineering. 

---

## Das Vibe-Coding-Konzept
Der gesamte Programmcode dieses Tools wurde nicht manuell geschrieben, sondern mittels KI-Dialogen entwickelt. Konkret hat der Dozent in einem sokratischen Dialog mit einem Large Language Model (**Gemini 3.0 Think**) einen Meta-Prompt entwickelt, der anschließend mehreren LLMs zur Ausführung übergeben wurde (**Gemini 3.0, ChatGPT 5.2, Claude Sonnet 4.6**). 

Ziel war es, Studierenden zu zeigen, dass die Erstellung funktionaler Software-Prototypen für die soziale Praxis mittels natürlicher Sprache durch KI für jede Person möglich ist.

## Technisches Verständnis
Der Dozent ist Sozialarbeiter, kein Informatiker. Der Code konnte also keiner umfassenden technischen Prüfung unterzogen werden. Zum besseren Verständnis des Codes wurde dieser an die oben genannten LLMs übergeben, um die Funktionsweise an den Dozenten rückzuspiegeln (**Rubber Duck Debugging**). So konnten fehlerhafte Funktionen aufgedeckt und technische Begriffe im Prozess erlernt werden.

## Funktionen
- **Interview-Transkript:** In einem Textfeld können User ein Interview-Transkript einfügen.
- **Jahr ermitteln:** Das Programm sucht im Text nach vierstelligen Zahlen, die mit 19 oder 20 beginnen.
- **Ereignis ermitteln:** Sobald eine Jahreszahl gefunden wurde, extrahiert das Programm den Text, der unmittelbar auf diese Zahl folgt.
- **Druckfertig:** Erstellt Zeitstrahlen für die Biografiearbeit und ermöglicht einen PDF-Export.
- **Datenhoheit:** Lokale Sicherung als `.json`-Datei zur Weiterverwendung in anderen Kontexten.
- **Offline-First:** Läuft als einfache HTML-Datei in jedem Browser.
  
## Iterative Weiterentwicklung (Problemlösungen)
Im Sinne des Vibe Codings wurde das Tool Schritt für Schritt weiterentwickelt:
- **Daten bearbeiten:** Es wurde nachträglich eine Funktion zur Bearbeitung der Jahreszahlen und Ereignistexte eingebaut.
- **Daten hinzufügen:** Eine manuelle Weiterführung des Zeitstrahls durch das Hinzufügen weiterer Ereignisse wurde implementiert.
- **Import-Button:** Neben dem Datei-Export als `.json` wurde ein Re-Import gespeicherter Zeitstrahlen ermöglicht, um die Arbeit fortzusetzen.
- **Titel der Ereignisse:** Es besteht nun die Möglichkeit mit Eingabe eines eigenen API-Key's die Titel präziser auszugeben.
## Ausstehende Weiterentwicklungen
- **Abfragung eines eigenen API-Key's**
- **Anleitung zur Generierung eines API-Key's**
- **Löschfunktion des API-Key's**

---

## Lizenz & Namensnennung
Veröffentlicht unter der **MIT-Lizenz**. 
Bei Verwendung im akademischen oder praktischen Kontext wird um Nennung des Ursprungsprojekts gebeten:
*Projekt BioGraph Pro / Weseloh Software AI Edition.*
