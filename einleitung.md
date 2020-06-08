# Einleitung

Das hier beschriebene [Edoweb](https://www.edoweb-rlp.de) (Elektronische Dokumente im WEB) ist eine gemeinsame Neuentwicklung des Landesbibliothekszentrum Rheinland-Pfalz (LBZ) und Hochschulbibliothekszentrum des Landes Nordrhein-Westfalen (hbz). Das vorliegende Handbuch richtet sich an die Benutzerinnen von Edoweb und beschreibt die verschiedenen Geschäftsgänge und Anwendungsmöglichkeiten. Die Nutzungsmöglichkeiten hängen dabei jeweils von der Rolle ab, die eine Anwenderin hat. Folgende Nutzungsrollen werden vom System unterstützt.

* `Systemadmin` - uneingeschränkte Berechtigungen im Frontend und Backend - hbz
* `Backend_Admin` - uneingeschränkte Rechte zur Inhaltsbearbeitung im Backend, eingeschränkte Konfigurationsrechte im Backend
* `Backend_Bearbeiter` -  uneingeschränkte Rechte zur Inhaltsbearbeitung im Backend
* `Backend_Reader` -  uneingeschränkte Leserechte im Backend, keine Rechte zur Inhaltsbearbeitung im Backend
* `Gastnutzer` - auf den öffentlichen bereich eingeschränkte Leserechte im Frontend

Das Handbuch behandelt Themen für die Rollen `Backend_Bearbeiter` und `Backend_Admin`. Die System-Administration ist in den öffentlichen Dokumenten zu Regal, Regal-API und Regal-Drupal zu finden.


|Rolle |Systemadministration |Konfiguration<br>des Backends|Inhalte in das Backend<br>übernehmen und Bearbeiten|Auf Inhalte im<br>Backend zugreifen|Auf öffentlich zugängliche<br>Inhalte zugreifen|Wer?|
|----------------------|---|---|---|---|---|--------------|
|Systemadministrator   | + | + | + | + | + | hbz          |
|Backend_Administrator | - | + | + | + | + | (hbz), (LBZ) |
|Backend_Bearbeiter    | - | - | + | + | + | hbz, LBZ     |
|Backend_Reader        | - | - | - | + | + | -            |
|Gastnutzer            | - | - | - | - | + | öffentlich   |
