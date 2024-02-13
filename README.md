# Erfassung Rohrleitungen

Das Bundesamt für Energie hat den Auftrag eine Übersicht über die Rohrleitungsanlagen und Schutzbereiche zu erstellen. Die Geodaten werden von den Anlagebetreibenden gemäss minimalem Geodatenmodell erfasst. Hier finden Sie nützliche Informationen welche bei der Erfassung der Geodaten helfen können.

* [Minimales Geodatenmodell](https://github.com/SFOE/ErfassungRohrleitungen/tree/main#minimales-geodatenmodell)
* [INTERLIS - Allgemeine Informationen](https://github.com/SFOE/ErfassungRohrleitungen/tree/main#interlis---allgemeine-informationen)
* [INTERLIS - Geodaten erfassen](https://github.com/SFOE/ErfassungRohrleitungen/tree/main#interlis---geodaten-erfassen)
* [INTERLIS - Geodaten validieren](https://github.com/SFOE/ErfassungRohrleitungen/tree/main#interlis---geodaten-validieren)
* [Geodaten publizieren](https://github.com/SFOE/ErfassungRohrleitungen/tree/main#geodaten-publizieren)

Bei Fragen oder Unklarheiten erstellen Sie einen [Issue](https://github.com/SFOE/ErfassungRohrleitungen/issues) oder schreiben Sie eine [E-Mail](mailto:geoinformation@bfe.admin.ch)



## Minimales Geodatenmodell
Das minimale Geodatenmodell (MGDM) und die Dokumentation finden Sie hier:
* [Minimales Geodatenmodell](https://models.geo.admin.ch/BFE/PipelinesystemUnderSupervisionByFederalGovernment_V1.ili)
* [Dokumentation minimales Geodatenmodell](https://www.bfe.admin.ch/bfe/de/home/versorgung/statistik-und-geodaten/geoinformation/geodaten/leitungen/rohrleitungsanlagen.html)
* Kataloge
  * [PipelineStatusCatalogue](https://models.geo.admin.ch/BFE/PipelinesystemUnderSupervisionByFederalGovernment_PipelineStatusCatalogue_V1.xml)
  * [MediumTypeCatalogue](https://models.geo.admin.ch/BFE/PipelinesystemUnderSupervisionByFederalGovernment_MediumTypeCatalogue_V1.xmll)
  * [ContainerTypeCatalogue](https://models.geo.admin.ch/BFE/PipelinesystemUnderSupervisionByFederalGovernment_ContainerTypeCatalogue_V1.xml)
  * [AttendantPlantTypeCatalogue](https://models.geo.admin.ch/BFE/PipelinesystemUnderSupervisionByFederalGovernment_AttendantPlantTypeCatalogue_V1.xml)

## INTERLIS - Allgemeine Informationen
Die Geodaten müssen in INTERLIS erstellt werden. Hier finden Sie allgemeine Informationen zu INTERLIS:
* [Referenzhandbuch](https://www.interlis.ch/dokumentation/interlis-2)

## INTERLIS - Geodaten erfassen
Folgende Werkzeuge eignen sich für die Erstellung von INTERLIS-Geodaten:

### QGIS Model Baker
* Das Model Baker Plugin kann direkt in QGIS über *Erweiterungen verwalten und installieren* installiert werden.
* [Dokumentation](https://opengisch.github.io/QgisModelBaker/de/)

### FME mit dem Plugin ili2fme
* Mit dem Plugin *ili2fme* können INTERLIS-Daten in FME gelesen und geschrieben werden.
* [Download](https://www.interlis.ch/downloads/ili2fme)
* [Dokumentation](https://www.geo.admin.ch/de/geodatenmodelle/)
* FME-Template (folgt)

### ili2db - Ladeprogramm für Datenbanken (PostgrSQL/PostGIS, GeoPackage oder ESRI FileGDB)
* Mit ili2db kann ein modellkonformes Datenbankschema erstellt werden. Aus diesem Datenbankschema können anschliessend valide INTERLIS-Daten exportiert werden.
* [Download](https://www.interlis.ch/downloads/ili2db)
* [Dokumentation](https://github.com/claeis/ili2db/blob/master/docs/ili2db.rst)

## INTERLIS - Geodaten validieren
INTERLIS-Geodaten können mit folgenden Werkzeugen validiert werden:
* [ilicop.ch](https://ilicop.ch/)
* [ilivalidator](https://www.interlis.ch/downloads/ilivalidator)
* [iGCheck](https://www.interlis.ch/downloads/igcheck)

## Geodaten publizieren
Valide Geodaten können Sie dem Bundesamt für Energie über die [Geodatenschnittstelle](https://github.com/SFOE/GeodatenschnittstelleDokumentation) übermitteln.
