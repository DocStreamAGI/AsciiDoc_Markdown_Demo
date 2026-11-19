# Werkzeuge

Für die verschiedenen Modellierungsprozesse stehen passende Werkzeuge zur Verfügung.

## UML/INTERLIS-Editor

Der [UML/INTERLIS-Editor](http://umleditor.org/) dient der Modellierung von INTERLIS-Modellen mittels UML-Diagrammen. Er benötigt Java und kann lokal installiert und verwendet werden. Die Lernkurve ist relativ steil und die Bedienung gewöhnungsbedürftig. Mit dem Verständnis von INTERLIS als Modellierungssprache wächst auch die Verständnis für die Bedienung des *UML/INTERLIS-Editors*.

## ili2c

Mittels [INTERLIS-Compiler](https://sourceforge.net/projects/umleditor/files/ili2c/) kann das INTERLIS-Modell syntaktisch geprüft werden. Die Software ist bereits im *UML/INTERLIS-Editor* eingebaut und muss nicht zwingend separat installiert werden.

Es sollte wenn immer möglich die gleiche Version, wie die in GRETL integrierte Version, verwendet werden.

## ili2pg

[Ili2pg](http://www.eisenhutinformatik.ch/interlis/ili2pg/) erstellt aufgrund eines INTERLIS-Modelles ein Schema mit leeren Tabellen in einer PostgreSQL/PostGIS-Datenbank. Es kann auch INTERLIS-Transferdateien importieren oder aus einer Datenbank Daten in eine Transferdatei exportieren.

Es sollte wenn immer möglich die gleiche Version, wie die in GRETL integrierte Version, verwendet werden.

Mit `ili2gpkg` und `ili2fgdb` stehen Derivate für GeoPackage und FileGeodatabase zur Verfügung.

## ilivalidator

Dank des [ilivalidators](https://github.com/claeis/ilivalidator>) kann eine INTERLIS-Transferdatei auf ihre Modellkonformität geprüft werden. Die Software ist ebenfalls in *ili2pg* eingebaut und ist standardmässig aktiviert und muss mit `--disableValidation` ausgeschaltet werden.

Es sollte wenn immer möglich die gleiche Version, wie die in GRETL integrierte Version, verwendet werden.

## QGIS Model Baker

Das QGIS-Plugin [QGIS Model Baker](https://opengisch.github.io/QgisModelBaker/) erstellt anhand eines INTERLIS-Modelles resp. der in der Datenbank angelegten Tabellen automatisch ein QGIS-Projekt mit bereits vorkonfigurierten und verknüpften Formularen.
