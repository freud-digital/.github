## Repo-Übersicht

### [frd-data](https://github.com/freud-digital/frd-data)

In diesem Repo werden mit Hilfe von via GitHub-Actions ausgeführten Skripten Daten aus dieversen Quellen extrahiert und in XML/TEI bzw. andere menschen- und maschinenlesbare Community-Standards überführt.

Konkret werden in diesem Repo Daten aus
* https://www.freud-edition.net/
* https://baserow.io/ 
* sowie [Zotero](https://www.zotero.org/groups/4690432/sigmund-freud/library)

verarbeitet. 

### [frd-working-data](https://github.com/freud-digital/frd-working-data)

In diesem Repo werden die in [frd-data](https://github.com/freud-digital/frd-data) automatisch generierten Daten manuell weiterbearbeitet. 

### [frd-static](https://github.com/freud-digital/frd-static)

In diesem Repo werden Daten aus [frd-data](https://github.com/freud-digital/frd-data) sowie [frd-static](https://github.com/freud-digital/frd-static) zusammengeführt, nachprozessiert und in (X)HTML Dokumente transformiert, welche dann via GitHub Pages die Präsentationswebsite der Freud-Daten dient.

### [collate-me](https://github.com/freud-digital/collate-me)

In diesem Repo können (Teile) von XML/TEI Dateien automatisiert kollationiert werden. Diese Repo dient als Arbeitsbehelf für [frd-working-data](https://github.com/freud-digital/frd-working-data).


### [freud_api_crawler](https://github.com/freud-digital/freud_api_crawler)

Dieses Repo enthält den Code eines gleichnamigen Python-Packages welches in [frd-data](https://github.com/freud-digital/frd-data) verwendet wird, um Daten aus https://www.freud-edition.net/ bzw. der entsprechenden JSONAPI-Schnittstelle zu exportieren und in TEI/XML Dokumente zu konvertieren.

### [frd-reporting](https://github.com/freud-digital/frd-reporting)

In diesem Repo werden zweimal täglich aktuelle Daten über den Fortschritt der (Transkrptions)Arbeiten aus https://www.freud-edition.net/ abgefragt in Form eines [Dashboards](https://freud-digital.github.io/frd-reporting/) dargestellt.
