#Das RC Auto vorbereiten
Das Ferngesteuerte Auto *sollte* ein 1:10 Modelauto sein. Es existieren auch Spielzeug-Ferngesteuerte Autos, allerdings wird deren
Motor **nicht** nicht von einem **Servomotor** gesteuert. Um ein RC Auto mit einem Raspberry Pi möglichst einfach zu verbinden.
So ein Spielzeug Auto hat 4Pins mit einem servo-ähnlichen Verhalten. Es wäre prinzipiell möglich auch das mit einem RaspberryPI
zu verbinden, allerdings ist so etwas dann eher im Elektrotechnik Fachgebiet.

## Der Servomotor
Der Servomotor eines Modellautos hat 3 Pins. Die 3 Pins sind
* Versorgungspannung
* Masse
* Signal/PWM





##Kameramodul und Webserver

![Alt-Text](camera_works.jpg)
* Über die [IP-Adresse 192.168.2.125  und den Port 8887](http://192.168.2.125:8887) kann ein Webinterface aufgerufen werden, über dieses kann das Auto später bewegt werden und die Kamera eingesehen werden.

##Steuerung

* Das Auto kann über das [Webinterface](http://192.168.2.125:8887) gesteuert werden. Ist aber noch sehr schlecht kalibriert.
    * sfsdfs