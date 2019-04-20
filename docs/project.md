#Projekt

##Dokumentation
1. Installiere Python, Git und mkdocs
2. Klone das [Repository](https://github.com/bohniti/it_projekt_dokumentation)
3. Bearbeite die Dokumentation, indem du die .md Dateien unter /docs änderst (Text) oder die mkdocs.yml anpasst (Menü, Einstellungen).
4. Baue die Webseite mit dem Befehl mkdocs build
5. Push deine Änderungen in das Repository und aktuallisiere die Online-Dokumentation mit mkdocs gh-deploy
6. Rufe die aktuelle Version der [Dokumentation](https://bohniti.github.io/it-projekt) auf.

###Hilfe zur Dokumentation
* super einfache [Anleitung](https://rogerdudler.github.io/git-guide/index.de.html) und Übersicht für Git
* [Markdown Syntax](Markdown Syntax)
* [Noch mehr Markdown](https://support.squarespace.com/hc/de/articles/206543587-Markdown-Spickzettel)

##Initialisierung

###Fragen an die Mitglieder (DeadLine: Kick-Off am 04.04.19):
* Wie funktioniert ein neuronales Netz grundlegend?
* Welche Arten von neuronalen Netzen gibt es?
* Wodruch unterscheiden sich die neuronalen Netzte von einander?
* Welche Netz-Art eignet sich am besten für das Projekt?
* Was ist ein Layer, eine Epoche usw.?
* Welche Technologie (Netzart, API, Framework) wird von DonkeyCar verwendet?

###Kick-Off (04.04.19):

[PDF Version](/data/kick_off.pdf)

* Wie welches Ergebnis soll erzielt werden?

    * Bericht mit 20 Seiten (Ein gekennzeichneter Abschnitt pro Mitglied)
    * Vortrag über eine Stunde (Termin selbstständig im WS mit Prof. Trommler vereinbaren)

* Wie wird die Note gebildet?

    * Auf den jeweiligen Berichtsabschnitt (vor allem bei großen qualitativen Unterschieden)
    * Vortag
    * Gesamtprojektfortschritt

* Welche Anforderungen gibt es, neben den erwarteten Ergebnissen?

    * Hard- und Software bis zum Wintersemester fertig, Bericht bis zum Vortag fertig.

* Wie findet die Kommunikation statt? (fester Intervall, ...)

    * Mögliche Sprechstunde Donnerstag um 08:45

* Welche Meilensteine sollen erreicht werden?

    1. Supervised learning
    2. Reinforcment learning, für mindestens einen Parameter

* Wie lange haben wir Zeit?

    * Allgemein: 14.03.2020

* Wo arbeiten wir?

    * Medienlabor

##Kameramodul und Webserver

![Alt-Text](camera_works.jpg)
* Über die [IP-Adresse 192.168.2.125  und den Port 8887](192.168.2.125:8887) kann ein Webinterface aufgerufen werden, über dieses kann das Auto später bewegt werden und die Kamera eingesehen werden.

##Steuerung

* Das Auto kann über das [Webinterface](192.168.2.125:8887) gesteuert werden. Ist aber noch sehr schlecht kalibriert.
    * sfsdfs