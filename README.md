# 06-12-2022
WS 22 - Klassen und Objekte 2



Übungsaufgabe vom 06.12.2022 für die Studierenden des Java I Seminars der Universität zu Köln

### 📝 Aufgabe:

Das Java Projekt hat die Klasse ```EMail``` aus der letzten Stunde  implementiert.
Programmiert jetzt eine Klasse ```Outbox```:

- Die Klasse soll als Attribut ein ```EMail[] mails``` zur verwaltung gesendeter EMails beinhalten.
- Über einen  ```Outbox``` Konstruktor soll das ```EMail[] mails``` initialisiert werden
- Die Größe des ```EMail[]```  soll über einen ```int outboxSize``` als Argument im  ```Outbox``` Konstruktor bestimmbar sein.

-------------------------------

Programmiert eine Methode ```public void addMail(EMail mail)``` in der ```Outbox``` Klasse.
- Die Methode soll am ersten freien Platz im ```EMail[]``` eine ```EMail mail``` einfügen
- Wenn das Postfach voll ist soll eine Meldung in der Konsole ausgegeben werden 


-------------------------------

Erweitert die Methode ```public void addMail(EMail mail)``` so das sich das ```EMail[] mails``` dynamisch vergrößert, wenn eine ```EMail``` nicht mehr in das  ```EMail[] mails```passt.





  ### ℹ️ Resourcen:
Hier noch ein paar nützliche 📃Artikel, 🖊️Threads und 🎥Videos

- [ 🎥 GitHub Projekte in Eclipse importieren](https://drive.google.com/file/d/1IpwHADmwViEGQ7Pf4BgybUYpz7WBoMe5/view?usp=sharing)
