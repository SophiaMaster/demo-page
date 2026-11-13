# KursPortal – lokale Demonstration

## Start

`index.html` per Doppelklick in einem aktuellen Browser öffnen. Ein Server, Build-Schritt, Benutzerkonto bei Dritten oder eine Internetverbindung wird nicht benötigt.

## Umfang

Startseite, Kurskatalog (Textsuche, Kategorie, Niveau, Format, Sortierung), zehn dynamische Kursdetailseiten, Merkliste, dreistufige simulierte Buchung mit Bestätigung, lokales Benutzerprofil und Einstellungen, Service mit FAQ und lokalem Kontaktformular, Neuigkeiten und Veranstaltungen.

## Datenhaltung

Kurs- und Nachrichteninhalte liegen fest in `js/app.js`. Merkliste, Demo-Buchungen, Profil, Einstellungen und Kontaktanfragen werden nur im Local Storage des jeweiligen Browsers gespeichert (`kursportal.*`). Es werden keinerlei Requests, Bezahlvorgänge, E-Mails oder echte Buchungen ausgelöst.

Das Löschen der Browser-Website-Daten entfernt auch die lokal gespeicherten Demo-Inhalte. Die Buchungsübersicht enthält ausschließlich Beispielbuchungen. Für eine frische Demonstration ist im Benutzerkonto die Schaltfläche **Demodaten zurücksetzen** vorhanden.

## Hinweis

Dieses Projekt ist eine eigenständige, fiktive Offline-Demo. Namen, Veranstaltungsorte, Termine und Kontakte sind Beispieldaten. Bitte keine echten vertraulichen Informationen eingeben.
