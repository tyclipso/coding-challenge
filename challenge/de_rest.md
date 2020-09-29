# Tyclipso.net Coding Challenge

[Dupliziere][duplicate] dieses Repository in ein privates Repository und füge @tyclipso-gmbh und @MarauderXtreme als Mitwirkende hinzu.

> Entwirf eine einfache REST API, die Teil einer Online-Plattform sein könnte.
> Implementiere diese API in einem RESTful Webservice.
> Keine Erfahrungen mit der Entwicklung von REST APIs / Webservices? Kein Problem! Setze die Aufgabe soweit wie möglich mit deinem Kenntnisstand um. 

Der Webservice soll basieren auf:

- PHP 7.4
- optional: Doctrine für ORM  

## Datenmodell / Entitäten

### Nutzer

- Vorname
- Nachname

### Projekt

- Titel
- Beschreibung

Nutzer können mehreren Projekten zugeordnet sein.

## Anforderungen

- RESTful-API (RMM Level 2)
  - Nutzer anlegen
  - Nutzer bearbeiten
  - Nutzer löschen
  - Projekt anlegen
  - Projekt bearbeiten
  - Projekt löschen
  - alle Projekte eines Nutzers auslesen
- Dokumentation der API

## Optionale Anforderungen

Hier einige Anregungen, welche du zusätzlich noch umsetzen kannst:

- State-of-the-Art HTTP Authentifizierung und Löschen des eigenen Nutzers und seiner Projekte
- Unit Tests
- Internationalisierung/i18n der Projektdaten
- Einfaches Frontend für den Zugriff auf die API
- Applikation in einem Docker Container zur Verfügung stellen
- Implementierung als Microservice
- Weiterer API-Endpunkt in anderer Programmiersprache

[duplicate]: https://docs.github.com/de/free-pro-team@latest/github/creating-cloning-and-archiving-repositories/duplicating-a-repository
