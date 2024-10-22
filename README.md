# Verwaltungsschale für den Leitungssatz (VWS4LS)
This repository hosts results from the research project [Asset Administration Shell for the Wiring Harness](https://arena2036.de/en/asset-administration-shell-for-wire-harness) (*VWS4LS*), funded by the German Federal Ministry of Education and Research.
A detailed description of the results of the various subprojects can be found here ([German only](https://github.com/VWS4LS/vws4ls-subproject-results/blob/main/README.md)).

Dieses Repository enthält Ergebnisse aus dem Forschungsprojekt [Asset Administration Shell for the Wiring Harness](https://arena2036.de/de/asset-administration-shell-for-wire-harness) (*VWS4LS*), das vom Bundesministerium für Bildung und Forschung gefördert wurde.

![image](https://github.com/user-attachments/assets/5af587f1-70ea-4852-8fba-e0884b340efd)

Detaillierte Beschreibungen der Ergebnisse der Teilprojekte finden sich [hier](https://github.com/VWS4LS/vws4ls-subproject-results/blob/main/README.md), ebenso der [Gesamtbericht als PDF](https://github.com/VWS4LS/vws4ls-subproject-results/blob/main/VWS4LS_Abschlussbericht_Gesamtprojekt.pdf). 

# Inhalt
- [Überblick](#überblick)
- [Projektpartner](#projektpartner)
- [Projektziel](#projektziel)
- [Projektgliederung](#projektgliederung)
- [Ergebnisse](#ergebnisse)
  - [Informationsmodelle für die Produktbeschreibung](#TP01)
  - [Dezentrale Datenhaltung für den Entwicklungsprozess](#TP02)
  - [Tools zur Anwendung der VWS für die Produktionsprozesse](#TP03)
  - [Semantische Grundlagen für die Montage in der Karosserie](#TP04)
  - [Konzept zur Integration der Verwaltungsschalen entlang der Wertkette](#TP05)
  - [Konzept für automatisierte Verhandlungsprozesse](#TP06)
  - [Rollen und Rechte in der Verwaltungsschale](#TP07)
  - [Anbindung an Catena-X: Lösungsansatz für die Verwaltungsschalen-basierte Zusammenarbeit im Datenraum](#TP08)
  - [Demonstrator zur Pilotierung und Erprobung](#TP09)
  - [Transfer und Koordination](#TP10)
- [Publikationen](#publikationen) 
- [Veranstaltungen](#veranstaltungen)
  
## Überblick
Der Leitungssatz (auch Kabelbaum oder Bordnetz genannt) ist eine der komplexesten und teuersten Einzelkomponenten im modernen Automobil. Durch die stetig steigende Anzahl an Sensoren, Funktionen und Variantenvielfalt wird die Komplexität des Bordnetzes zukünftig weiter ansteigen. Andererseits wird durch die stark manuell geprägte Produktion in „Best Cost Countries“ die Liefertreue und somit die Resilienz der gesamten Lieferkette gefährdet. Alle diese Faktoren weisen auf Verbesserungspotential durch Automatisierung und digitale Durchgängigkeit über die gesamte Wertkette hin und bieten damit einen konkreten Anwendungsfall für die Digitale Transformation der Automobil- und Fahrzeugindustrie.

![image](https://github.com/user-attachments/assets/33974f7f-5675-456b-9636-3886f0d75ce9)

_Abbildung: Der Leitungssatz im Fahrzeug (Foto: Mercedes-Benz AG, www.bordnetze.eu)_

Das Projekt "**Verwaltungsschale für den Leitungssatz**" ([VWS4LS](https://arena2036.de/de/vws4ls)) ist aus der "**Innovationsinitiative Leitungssatz**" ([IILS](https://arena2036.de/de/innovationsinitiative-leitungssatz)) hervorgegangen, als gefördertes Verbundvorhabens im Rahmen des Konjunkturpaketes 35c der Bundesregierung "**Zukunftsinvestitionen für Fahrzeughersteller und Zulieferindustrie**" ([Kopa 35c](https://www.bmwi.de/Redaktion/DE/Textsammlungen/Industrie/zukunftsinvestitionen-fahrzeughersteller-zulieferindustrie.html)).

Die Projektlaufzeit war von Dezember 2021 bis Ende November 2024 angesetzt, mit den hier aufgeführten Industriepartnern.

## Projektpartner
![image](https://github.com/user-attachments/assets/e5ec3a97-2130-4a49-a64d-dbc4d49ad079)

\- [Coroplast Fritz Müller GmbH & Co. KG](https://www.coroplast-group.com/de/wewire/)

\- [DilT GmbH](https://www.diit.de/)

\- [Lisa Dräxlmaier GmbH](https://www.draexlmaier.com/produkte/electrical-systems)

\- [Festo SE & Co. KG](https://www.festo.com/de/de/)

\- [Komax Testing Germany GmbH](https://www.komaxgroup.com/products/testing)

\- [Kostal Kontaktsysteme GmbH](https://www.kostal-kontakt-systeme.com/de-de/)

\- [Kromberg & Schubert Automotiv GmbH Co. KG](https://www.kromberg-schubert.de/loesungen/bordnetze)

\- [Wezag GmbH & Co. KG](https://www.wezag.de/wdt-crimpen-machinen/)

Die [Mercedes-Benz AG](https://group.mercedes-benz.com/de/) und [Siemens AG](https://www.siemens.com/de/de/produkte/automatisierung/industrie-software/automatisierungs-software.html) als assoziierte Partner engagieren sich aus der [Innovationsinitiative Leitungssatz](https://arena2036.de/de/innovationsinitiative-leitungssatz) heraus als OEM sowie Hersteller digitaler Tools.


## Projektziel
Ziel von VWS4LS ist die prototypische Implementierung der Verwaltungsschale in Entwicklung, Produktion und Montage des Leitungssatzes im Fahrzeug entlang von 5 wesentlichen Anwendungsfällen, die aus Sicht der Leitungssatz-Akteure besondere Herausforderungen, aber auch Potenziale für die Verwaltungsschale beinhalten.

| Use Case 1 | Kollaborative Entwicklung zwischen Original Equipment Manufacturer (OEM), Konfektionär, Komponentenlieferanten |
| --- | --- |
| Use Case 2 | Berücksichtigung der automatisierten Produktionsfähigkeit im Engineering |
| Use Case 3 | Automatisierung des Änderungsmanagements entlang der gesamten Wertkette |
| Use Case 4 | Automatisierung von flexiblen und modularen Produktionsabläufen |
| Use Case 5 | Rückverfolgung aller Komponenten, Produktions- und Qualitätsdaten |

## Durchführung
Bestehende Standards, einschlägige [DIN-Normen](https://www.dinmedia.de/de/norm/din-72036/376689255), Vorarbeiten der [Plattform Industrie 4.0](https://www.plattform-i40.de/), der [Industrial Digital Twin Association (IDTA)](https://industrialdigitaltwin.org) sowie diverser verbundener Projekte wie bspw. „[Verwaltungsschale vernetzt](https://vwsvernetzt.de/)“ wurden als Grundlage herangezogen. Die Gestaltungsfelder im Bereich Verwaltungsschale, wie Architektur, Informations- und Fähigkeitsmodelle, Verhandlungsprozesse und kollaborative Datengovernance, wurden bearbeitet. Als wesentlicher erfolgskritischer Punkt wurde die Integration der etablierten Branchenstandards „[Kabelbaumliste](https://ecad-wiki.prostep.org/specifications/kbl/)“ (KBL, PSI-19 / VDA 4964) und „[Vehicle Electric Container](https://ecad-wiki.prostep.org/specifications/vec/v210/release-notes/)“ (VEC , PSI-21 / VDA 4968) in die Verwaltungsschale analysiert.

Mit der IDTA wurden Teilmodelle zur Automatisierung der Leitungssatzproduktion standardisiert. Mit dem VDMA entstand eine OPC UA Companion Specification zur dynamischen Steuerung der Produktionsressourcen. Als Middleware wurde [BaSyx](https://eclipse.dev/basyx/) verwendet. Die Verwendung von Verwaltungsschalen in [Catena-X](https://catena-x.net/de/) wurde ebenfalls untersucht.

Der projektbegleitende Transfer erfolgte u. a. auf der Hannover Messe, eigenen Veranstaltungen sowie Transformations-Hubs; insbesondere [Transfer-X](https://transfer-x.de/) und dem [Trafo-Hub Leitungssatz](https://www.leitungssatz-hub.de/).

## Projektgliederung
Das Projekt untergliederte sich nach drei wesentlichen Prozessschritten, fünf Querschnittsthemen und zwei übergreifenden Themen: Die Vertikalen Teilprojekte (TPs) 2, 3 und 4 widmeten sich den wesentlichen Wertschöpfungsaktivitäten des Leitungssatzes (Entwicklungs-, Produktions- und Montageprozesse). Die Verwaltungsschalen-spezifischen TPs 1, 5, 6, 7 und 8 sind als fachliche Querschnittsprojekte definiert worden, die überwiegend die in den vertikalen TPs gewonnen Erkenntnisse in Lösungskonzepte überführen. TP 9 und 10 bilden übergreifende Arbeitsfelder ab, die eine TP-übergreifende Konsolidierung und Kohärenz bei der Demonstration und dem Transfer sicherstellen sollen. Detailinformationen zu den Inhalten und Ergebnissen der Teilprojekte finden sich unter „Ergebnisse“ in der jeweiligen Teilprojekt-Unterseite.

![image](https://github.com/user-attachments/assets/daaffbd9-a17f-4fbf-a28a-6c8362e34ffb)      
_Abbildung: Projektstruktur_

Die TPs orientieren ihre Inhalte dabei nicht nur an den Zielen des TPs selbst, sondern auch an den fünf Anwendungsfällen, die aus Sicht der Leitungssatz-Akteure besondere Herausforderungen, aber auch Potenziale für die Verwaltungsschale darstellen.

Die Rollen der verantwortlichen Teilprojektleiter wurden wahrgenommen von:
![image](https://github.com/user-attachments/assets/cb28ba76-865d-4c52-87c8-4db0e804cac2)
_Abbildung: Teilprojektleiter_

# Ergebnisse
Als wesentliche VWS4LS-Projektergebnisse im Bereich der Standardisierung sind die neuen Teilmodelle „[IDTA 02056-1-0 Data Retention Policies](https://github.com/admin-shell-io/submodel-templates/tree/main/published/Data%20Retention%20Policies/1/0)“, „IDTA 02031-1-0 Bill of Process“, sowie die OPC UA Companion Specification „OPC 40570: OPC UA for the Wire Harness Manufacturing Industry” (aktuell im Review) entstanden. Im [VEC 2.1.0](https://ecad-wiki.prostep.org/specifications/vec/v210/release-notes/) wurden zudem neue Features eingebracht.

![image](https://github.com/user-attachments/assets/64ef139b-2e4c-4e8c-a1a7-f405f16cbd7d)   
_Abbildung: Im Rahmen von VWS4LS erstellte neue Standards_

Projektbegleitende Veröffentlichungen, Präsentationen und Veranstaltungen sind über das Inhaltsverzeichnis auf dedizierten Unterseiten einsehbar.

Auf der [VWS4LS](https://github.com/VWS4LS)-Organisation auf GitHub sind im Rahmen des Projekts erzeugte Softwareartefakte abgelegt, wie bspw. ein [VWS4LS-Plugin](https://github.com/VWS4LS/vws4ls-aaspe-plugin) für den [Eclipse AASX Package Explorer(&trade;)](https://github.com/eclipse-aaspe/package-explorer).

![image](https://github.com/user-attachments/assets/4ba1eff8-ddf9-4581-986f-78415f7b334a)   
_Abbildung: AASX-Exporer Plugin-Actions_

Im Folgenden ist ein kompakter Überblick über die Teilprojekte und deren Ergebnisse zusammengestellt. Es sind jeweils [Links zur Detaildokumentation](https://github.com/VWS4LS/vws4ls-subproject-results/) hinterlegt.

## <a name="TP01"></a>Informationsmodelle für die Produktbeschreibung
Das [TP1 "Konzept, Informationsmodelle und Produktbeschreibung"](https://github.com/VWS4LS/vws4ls-subproject-results/blob/main/TP01/) fokussierte sich auf die Definition eines einheitlichen Ansatzes für die Beschreibung von Leitungssatz-Komponenten, mit dem Ziel, einen effizienten und kollaborativen Datenaustausch zwischen den unterschiedlichen Akteuren in der Fertigungskette zu ermöglichen. Durch die Standardisierung und Vereinheitlichung der Produktmodellierung soll sichergestellt werden, dass alle an der Leitungssatzherstellung beteiligten Unternehmen auf eine Datenbasis zugreifen und nahtlos zusammenarbeiten können. Dadurch soll auch die Optimierung von Entwicklungsprozessen und eine Verbesserung der Qualität des Endprodukts ermöglicht werden.

![image](https://github.com/user-attachments/assets/3d825e84-3cf1-4d24-902e-e177e3c41c2f)   
_Abbildung: Konstruktionszeichnung Leitungssatz-Komponente_

Hierzu wurden die in [TP3](https://github.com/VWS4LS/vws4ls-subproject-results/blob/main/TP03/) erfassten Anforderungen an die typischen Produktionsprozesse in der Leitungssatzindustrie systematisch analysiert und darauf aufbauend das Produkt-Prozess-Ressourcen (PPR) Modell zur systematisierten Erstellung von Datenmodellen für die hinreichend genaue Abbildung der Produktionsprozesse angewendet.

Gegen diese ermittelte Anforderungsbasis wurden dann vorhandene Standards wie [KBL](https://ecad-wiki.prostep.org/specifications/kbl/), [VEC](https://ecad-wiki.prostep.org/specifications/vec/), [ECLASS](https://eclass.eu/eclass-standard/content-suche/search) und [OPC UA](https://opcfoundation.org/developer-tools/documents) auf Anwendbarkeit und Eignung geprüft.

Nach dieser sorgfältiger Analyse der Gegebenheiten wurde die für das Gesamtprojekt grundlegenden Entscheidungen getroffen, für die Leitungssatzentwicklung neben VEC auch immer noch KBL (als historisch etabliertes Format) zu unterstützen und OPC UA als Standard für die dynamische Fertigungssteuerung vorzusehen. Für semantische Eindeutigkeit sollen, wo immer möglich, ECLASS-Referenzen verwendet werden.

Für die Leitungssatzmodellierung zur Überführung in die Produktionsphase wurden die notwendigen Informationen aus den KBL- und VEC-Standards abgeleitet und ein Informationsmodell für die „Bill-of-Material“ (BOM) des Leitungssatzes erstellt, wobei KBL bzw. VEC als Dateielemente in die VWS eingehängt bzw. verlinkt werden. Des Weiteren wurden in die VEC Rel. 2.10 diverse Verbesserungen eingebracht, um erkannte Lücken im Datenmodell zu schließen.

Die notwendige Reduktion des „150%“-Engineeringmodells eines Leitungssatzes auf das „100%“-Produktionsmodell der einzelnen zu produzierenden Leitungssatz-Variante wurde ebenfalls analysiert.

Als weiteres wesentliches Ergebnis des TP1 wurde beschlossen, gemeinsam mit dem VDMA die OPC UA Companion Specification «OPC 40570: OPC UA for the Wire Harness Manufacturing Industry» zu erarbeiten, um damit einen einheitlichen Standard für die Kommunikation und Interaktion zwischen verschiedenen Systemen in der Leitungssatzindustrie zu schaffen.

**[Detaildokumentation TP1](https://github.com/VWS4LS/vws4ls-subproject-results/blob/main/TP01/)**   


## <a name="TP02"></a>Dezentrale Datenhaltung für den Entwicklungsprozess
Das [TP2 "Entwicklungsprozesse des Leitungssatzes"](https://github.com/VWS4LS/vws4ls-subproject-results/blob/main/TP02/) fokussierte sich auf die Erfassung und Modellierung der komplexen und kollaborativen Entwicklungsprozesse sowie der dahinterstehenden Datenhaltungskonzepte. Bei der Entwicklung und Herstellung eines Leitungssatzes sind verschiedene Akteure in einem komplexen Prozess involviert. Der OEM als Fahrzeugentwickler und Auftraggeber für den Leitungssatz, der Konfektionär als Koordinator der Leitungssatzentwicklung sowie die unterschiedlichen Lieferanten-Abstufungen, die sog. „Tier“. Als Tier-1 werden typischerweise Systemlieferanten wie Hersteller von Steuergeräten oder eben auch Hersteller von Leitungssätzen bezeichnet. Tier-2 bezeichnet Lieferanten von einzelne Komponenten für das Gesamtsystem. Weitere Zulieferer von indirekten Gütern oder Ressourcen werden als Tier-3 bezeichnet. Zudem muss vor einem Einsatz von Komponenten deren Freigabe vom eigentlichen Auftraggeber (hier dem OEM) eingeholt und entsprechend dokumentiert werden. Diese Akteure verteilen sich dabei auf mehrere Unternehmen, die oft auch in verschiedenen Ländern ansässig sind. Darüber hinaus sind die Informationsflüsse zwischen den Akteuren situativ geprägt und lassen sich nicht allgemeingültig definieren, was Richtung und Reihenfolge anbelangt.

Als wesentliche Ergebnisse des TP2 ist das AP 2.5 mit den Betrachtungen zur dezentralen Speicherung der Verwaltungsschale zu nennen, bei der abhängig vom Anwendungsfall eines der beteiligten Repositories als Referenzpunkt, dem sog. „single-point-of-truth“ (SPoT) als verlässliche Datenquelle fungiert, dieses aber nicht alle Daten vorhält, sondern in die Repositories der anderen Stakeholder verlinkt. Die folgende Abbildung zeigt den schematischen Aufbau einer solchen dezentralen Datenhaltung.

![image](https://github.com/user-attachments/assets/76556a3e-bac9-4a3c-aee4-5320c1a50a9c)   
_Abbildung: Eingangs- und Ausgangsdaten im Entwicklungsprozess im Überblick_

Es wurde auch erkannt, dass die VWS sowohl für die Bereitstellung der Stammdaten durch die Tiers als auch für das laufende Änderungsmanagement im Entwicklungsprozess einen echten Mehrwert bietet, nicht nur in Bezug auf Rückverfolgbarkeit, sondern auch bei der eigentlichen Diskussion und Einpflegen von Änderungen. Anstatt vieler verschiedener Dateien in unterschiedlichen Formaten ist nun eine strukturierte Verfügbarkeit der Daten gegeben, die nahtlos über standardisierte Schnittstellen ausgetauscht werden können. Daraus ergeben sich enorme Möglichkeiten der Optimierung und Zeitersparnis.

Bei der Prozessbetrachtung wurden die beteiligten Organisationsrollen unterteilt nach OEM, LS-Entwickler und Komponenten-Entwickler, wobei letztere neben Stecker auch Gehäuse, Abdeckungen, angepasste Kabelkanäle und weitere Komponenten umfassen.

![image](https://github.com/user-attachments/assets/a182bc65-7a56-4aba-bfb5-741a5eacd887)   
_Abbildung: Referenzprozess Leitungssatzentwicklung_

Jede LS-Komponente und jeder Prozessschritt wurde mit einbezogen und die dafür notwendigen Teilmodell-Typen wie folgt definiert:

![image](https://github.com/user-attachments/assets/9c88a7c1-8fab-419d-a65c-86e371def710)   
_Abbildung: VWS-Typen und deren Stakeholder_

Die resultierenden Anforderungen an die Prozess-Schritte in der Fertigung und die dort notwendigen automatischen Verhandlungsprozesse zwischen Produkt und Maschinen (Interaktion VWS – MES) wurden erfasst und in [TP6](https://github.com/VWS4LS/vws4ls-subproject-results/blob/main/TP06/) auf Basis von I4.0-Nachrichten definiert, um damit eine Automatisierung der Fertigungsabläufe umsetzen zu können.

**[Detaildokumentation TP2](https://github.com/VWS4LS/vws4ls-subproject-results/blob/main/TP02/)**   


## <a name="TP03"></a>Tools zur Anwendung der VWS für die Produktionsprozesse
Das [TP3 "Produktionsprozesse des Leitungssatzes"](https://github.com/VWS4LS/vws4ls-subproject-results/blob/main/TP03/) fokussierte sich auf die systematische Erfassung, Gliederung und digitale Beschreibung der Produktionsprozesse und Produktionsmittel, sowohl als „Bill-of-Process“ (BoP) Submodell der VWS, als auch der Definition von Konzepten und Mechanismen zur dynamischen Prozessteuerung und zur Interaktion über einen Cloud Dataspace (IDS).

Als ein wesentliches Ergebnis wurde die in [TP1](https://github.com/VWS4LS/vws4ls-subproject-results/blob/main/TP01/) definierte neue OPC UA Companion Specification „OPC 40570: OPC UA for the Wire Harness Manufacturing Industry“ in einem Demonstrator zur Anbindung proprietärer Produktionsmaschinen über die [Eclipse BaSyx Data Bridge](https://github.com/eclipse-basyx/basyx-databridge) verwendet.

![image](https://github.com/user-attachments/assets/e00c0a19-3466-4ceb-b2f5-643e6d9a2b88)   
_Abbildung: Produktionsprozesse_

Darüber hinaus wurde ein Referenzbeispiel für das Mapping eines Fertigungsauftrags in das Teilmodell "Bill of Process" erstellt.

![image](https://github.com/user-attachments/assets/51536b0e-cfeb-48b0-9462-b91f82458245)   
_Abbildung: Referenzbeispiel "Bill of Process"_

**[Detaildokumentation TP3](https://github.com/VWS4LS/vws4ls-subproject-results/blob/main/TP03/)**   


## <a name="TP04"></a>Semantische Grundlagen für die Montage in der Karosserie
Im [TP4 "Montageprozesse des Leitungssatzes"](https://github.com/VWS4LS/vws4ls-subproject-results/blob/main/TP04/) wurden Möglichkeiten untersucht, die Montageprozesse beim OEM über Verwaltungsschalen als standardisierte Digitale Zwillinge abzubilden und zu automatisieren. Dazu wurden die einzelnen Teilprozesse der Montage eines Leitungssatzes in der Fahrzeugkarosserie analysiert, relevante Informationen abgeleitet und semantisch beschrieben, um diese in einem Teilmodell der Verwaltungsschale zu hinterlegen und für die Prozesse automatisiert abrufbar bereitzustellen.  Ein Konzept zur Übernahme von CAD-Daten und weiteren Parametern, die einen starken Einfluss auf eine spätere Automatisierung in der Wertschöpfungskette haben, wurde erstellt. Im speziellen wurden Gehäuse und Kontakte betrachtet.

![image](https://github.com/user-attachments/assets/7121822a-39ec-42e2-b064-d9480c6f1c5b)   
_Abbildung: Der Leitungssatz im Fahrzeug_

Das angestrebte Ziel war, ein Daten-bezogene Voraussetzungen dafür zu schaffen, um die Montage des Leitungssatzes im Fahrzeug möglichst vollständig mithilfe von Robotern zu automatisieren. Das bedeutet, dass alle Informationen zur Bahnplanung, Geometrie etc. semantisch beschrieben, digital bereitgestellt, abgerufen und bei Bedarf aktualisiert werden müssen. Als Startpunkt wurde die Anlieferung der Packtasche inklusive des Leitungssatzes an der Montagezelle beim OEM angenommen.

Zusammenfassend wurde als Ergebnis von TP4 festgestellt, dass für eine vollständige automatisierte Montage des Leitungssatzes aus heutiger Sicht noch technische Hürden zu lösen sind. Die Losgröße 1 bei hoher Produktvielfalt und das komplexe Design der Karosserie erschweren eine automatisierte Montage erheblich. Eine Verbesserung könnte jedoch durch eine grundlegende Neugestaltung der Architektur des Leitungssatzes erfolgen, um eine einfachere und kosteneffizientere Automatisierung zu ermöglichen.

**[Detaildokumentation TP4](https://github.com/VWS4LS/vws4ls-subproject-results/blob/main/TP04/)**   


## <a name="TP05"></a>Konzept zur Integration der Verwaltungsschalen entlang der Wertkette
Das Ziel des [TP5 "Integration von Verwaltungsschalen (Verbundkomponente)"](https://github.com/VWS4LS/vws4ls-subproject-results/blob/main/TP05/) bestand darin, ausgehend vom Prinzip der Verbundkomponente der Plattform Industrie 4.0, Umsetzungskonzepte zu definieren, wie die Verwaltungsschale einer Teilkomponente, z.B. Steckverbinder, in die Verwaltungsschale des gesamten Leitungssatz einfließt, fokussierte sich auf Architekturfragen rund um die Verwaltungsschalen-Infrastruktur, um nach dem Konzept der Verbundkomponenten die beteiligten VWS zu Produkt und Produktionsmittel in einer vernetzten IT-Welt einander integrieren zu können. Hierfür notwendige Konzepte zu Versions- und Änderungsmanagement

![image](https://github.com/user-attachments/assets/7bc67abe-fcaf-4afa-9b50-446b22714605)   
_Abbildung: Vernetzte Verwaltungsschalen (Bild: Plattform Industrie 4.0)_

Die Ableitung und Definition der Verbundkomponente (VBK) „Produkt“, d.h. des Leitungssatzes. Der Anwendungsfall der virtuellen Inbetriebnahme (VIBN) von Produktionsmaschinen unter Einsatz der VWS wurde untersucht.

Grundlage für die VBK sind dabei zunächst die relevanten Beziehungen zwischen den beteiligten Verwaltungsschalen bzw. zwischen Elementen dieser Verwaltungsschalen.

![image](https://github.com/user-attachments/assets/033a1d8f-c818-4e1e-82ad-41fd60d82e9b)   
_Abbildung: Beziehungen zwischen den VWS_

**[Detaildokumentation TP5](https://github.com/VWS4LS/vws4ls-subproject-results/blob/main/TP05/)**   


## <a name="TP06"></a>Konzept für automatisierte Verhandlungsprozesse auf Basis der Verwaltungsschalen von Produkt und Maschine
Das [TP6 "Automatisierte Verhandlungsprozesse"](https://github.com/VWS4LS/vws4ls-subproject-results/blob/main/TP06/) fokussierte sich auf die Entwicklung eines Konzepts, um eine automatisierte Verhandlung zwischen verschiedenen Systemen zu ermöglichen (z.B. Maschine zu Maschine, Leitungssatz zu Maschine oder Leitstand (MES) zu Maschine). Diese Verhandlungen sollen autonom durch den jeweiligen Systemen zugehörige I4.0-Kompenten geführt werden, die anhand von Daten und Informationen Entscheidungen treffen.

![image](https://github.com/user-attachments/assets/11b2bfa0-0dac-45ac-8815-c8688a7a34f3)   
_Abbildung: VWS-Kommunikationsschema_

In dem Konzept wurden Randbedingungen für das eigenständige Entscheiden definiert und Wege für die Kommunikation und Interaktion zwischen autonomen I4.0-Komponenten aufgezeigt. Hierzu wurden I4.0-Nachrichten für eine VWS Typ 3 definiert, um Synchronisation von Werten und Verhandlungsprozessen zwischen Leitungssatz-VWS zu ermöglichen.

![image](https://github.com/user-attachments/assets/903e6e14-475e-426e-9d8e-85b18a235744)   
_Abbildung: Sequenzdiagramm Verhandlungsszenario_

**[Detaildokumentation TP6](https://github.com/VWS4LS/vws4ls-subproject-results/blob/main/TP06/)**   


## <a name="TP07"></a>Rollen und Rechte in der Verwaltungsschale: Leitfaden zur Interoperabilität unter Wahrung von IP und Vertraulichkeit
Das [TP7 "Data Business Policy, Data Governance, Monetarisierung"](https://github.com/VWS4LS/vws4ls-subproject-results/blob/main/TP07/) befasste sich mit Datenrichtlinien als Leitfaden und Orientierung für die Verwendung und den Umgang mit vertraulichen Daten der Stakeholder in der Wertschöpfungskette des Leitungssatzes. Zur Gewährleistung der kollaborativen Arbeit zwischen den Akteuren der Wertschöpfungskette durch den Austausch von Informationen und Diensten unter Verwendung des standardisierten Digitalen Zwillings (VWS) sind Rollen- und Rechtemanagementkonzepte erforderlich. In diesem TP wurden konzeptionelle Lösungsvorschläge für das Rollen- und Rechtemanagement im Bereich des Leitungssatz entwickelt, mit besonderem Schwerpunkt auf Zugangskontrollen zu Informationen und Diensten. Dabei war abzuwägen, ob ein attributbasierter oder ein rollenbasierter Zugangskontrollansatz zielführend ist.

![image](https://github.com/user-attachments/assets/c0f77e26-9337-4f2e-97a8-228ea392063f)   
_Abbildung: Security-Architektur_

Mögliche Geschäftsmodelle wurden betrachtet, um festzustellen, wie eine Monetarisierung basierend auf der VWS umgesetzt werden kann. Dabei wurden die wesentlichen Aspekte aus Sicht der Teilnehmer der LS-Wertschöpfungskette berücksichtigt.

**[Detaildokumentation TP7](https://github.com/VWS4LS/vws4ls-subproject-results/blob/main/TP07/)**   


## <a name="TP08"></a>Anbindung an Catena-X: Lösungsansatz für die Verwaltungsschalen-basierte Zusammenarbeit im Datenraum
Das [TP8 "Data Storage, Policy, Sicherheit, Anbindung an Catena-X"](https://github.com/VWS4LS/vws4ls-subproject-results/blob/main/TP08/) fokussierte sich auf die Entwicklung eines Lösungsansatzes zur interoperablen Nutzung von Daten über unterschiedliche Ablagestrukturen hinweg. Ziel ist die Grundlage zur gemeinsamen Nutzung der Daten in den unterschiedlichen Verwaltungsschalen über unternehmensspezifische Datenquellen hinweg mittels des [Catena-X-Datenökosystems](https://catena-x.net/de/benefits) als sichere und verlässliche Infrastruktur.

![image](https://github.com/user-attachments/assets/4c1652d9-9668-4001-97a1-79259ae4ea2d)   
_Abbildung: Catena-X Lösungsportfolio (Quelle: https://catena-x.net/de/offers)_

**[Detaildokumentation TP8](https://github.com/VWS4LS/vws4ls-subproject-results/blob/main/TP08/)**   


## <a name="TP09"></a>Demonstrator zur Pilotierung und Erprobung
Das [TP9 "Pilotierung, Erprobung, Demonstrator"](https://github.com/VWS4LS/vws4ls-subproject-results/blob/main/TP09/) fokussierte sich der Konzeptionierung und Umsetzung eines Demonstrators in mehreren Ausbaustufen über die gesamte Projektlaufzeit hinweg. Der Demonstrator enthält dabei sowohl physische als auch digitale Anteile. Insgesamt wurden 4 Demonstratorprojekte durchgeführt, wobei sich der physische Aufbau des Demonstrators seit Fertigstellung von Stufe 2 kaum mehr veränderte. Der Hauptteil der Veränderung erfolge dann vor allem [softwareseitig](https://github.com/orgs/VWS4LS/repositories). 

![image](https://github.com/user-attachments/assets/d53e0b39-82ea-48ca-a812-a8bb65df2492)   
_Abbildung: Übersicht Demonstrator_

**[Detaildokumentation TP9](https://github.com/VWS4LS/vws4ls-subproject-results/blob/main/TP09/)**   


## <a name="TP10"></a>Transfer und Koordination
Das [TP10 "Transfer und Koordination"](https://github.com/VWS4LS/vws4ls-subproject-results/blob/main/TP10/) umfasste alle Aktivitäten zur Sicherstellung des Transfers und der Koordination der Projektergebnisse. Im Fokus standen der kontinuierliche Basistransfer, die Entwicklung und Bereitstellung von allgemeinen und leitungssatzspezifischen Implementierungspaketen sowie die Ergebnisintegration und Koordination. Damit konnten die Ergebnisse des Projekts effektiv verbreitet und nachhaltig in den industriellen und öffentlichen Raum überführt werden. Zu VWS4LS und weiteren relevanten Begleitthemen (z.B. Catena-X) wurden über [Transfer-X](https://transfer-x.de/) hochwertige Lernmodule bereitgestellt:

![image](https://github.com/user-attachments/assets/639b3b30-e143-4685-8307-ab0dc49a32e9)

[<img src="[https://github.com/user-attachments/assets/639b3b30-e143-4685-8307-ab0dc49a32e9">](https://ilias.fraunhofer.de/ilias.php?baseClass=ilrepositorygui&ref_id=29387)   
_Abbildung: Transfer-X Lernmodule](https://ilias.fraunhofer.de/ilias.php?baseClass=ilrepositorygui&ref_id=29387)_  

**[Detaildokumentation TP10](https://github.com/VWS4LS/vws4ls-subproject-results/blob/main/TP10/)**   


# Publikationen

**Folgende Publikationen erfolgten im Rahmen des Projekts VWS4LS:**

-   M. Angos-Mediavilla, M. Gorenzweig, L. Beil, C. Kosel, A. Pomp, M. Freund und T. Meisen, „**Enabling Value Chain Interoperability: Integrating and evaluating robust Data Governance aspects into the Asset Administration Shell**“ in *Springer Lecture Notes in Computer Science*, 2025. 
-   Salinas Segura, A., Angos Mediavilla, M., Braun, L., Freund, M., Kosel, C., Rodriguez, M. (2024). “**A Process Model for Deriving Asset Administration Shells for Inter-company Collaboration – A Practical Approach**”; In: Yilmaz, M., Clarke, P., Riel, A., Messnarz, R., Greiner, C., Peisl, T. (eds) Systems, Software and Services Process Improvement. EuroSPI 2024. Communications in Computer and Information Science, vol 2180. Springer, Cham. <https://doi.org/10.1007/978-3-031-71142-8_16> 
-   Melanie Stolze, Alexander Belyaev, Christian Kosel, Christian Diedrich, Alfred Barnard, "**Realizing automated production planning via proactive AAS and Business Process Models**", 2024 29th IEEE International Conference on Emerging Technologies and Factory Automation (ETFA), Padua, Italy, 2024. 
-   Melanie Stolze, Gustavo Cainelli, Christian Kosel, Alexander Belyaev, Christian Diedrich (2024); **Entwurf komplexer Automatisierungssysteme: Konzepte zur Realisierung proaktiver Verwaltungsschalen und deren Kommunikation;** In *EKA 2024 - Entwurf komplexer Automatisierungssysteme, 18. Fachtagung (Jumar, Ulrich et al.)*. [Link](http://dx.doi.org/10.25673/116045)
-   Angos-Mediavilla, M.; Gorenzweig, M.; Pahnke, G.; Pomp, A.; Freund, M. and Meisen, T. (2024). **Advancing Industry 4.0: Integrating Data Governance into Asset Administration Shell for Enhanced Interoperability**. In *Proceedings of the 26th International Conference on Enterprise Information Systems - Volume 1: ICEIS*; ISBN 978-989-758-692-7; ISSN 2184-4992, SciTePress, pages 128-140. <https://doi.org/10.5220/0012632900003690> [PDF](https://arena2036depeterfroeschle.sharepoint.com/sites/IILS35c-ProjektVerwaltungsschale/Freigegebene%20Dokumente/General/TP_Uebergreifend/files/downloads/Projekte/VWS4LS/Ergebnisse/IntegratingDataGovernanceintoAASforEnhancedInteroperability.pdf)
-   Bernd Kärcher (2024), **VWS4LS: Datengetriebene Leitungssatzproduktion mit OPC UA**; Fachartikel VDMA. [Link](https://www.vdma.org/viewer/-/v2article/render/91564893)
-   Mario Angos Mediavilla, Michele Lagnese, André Pomp, Tobias Meisen (2023); **Asset administration shell-based engineering change management process: Challenges and ways forward;** Procedia CIRP, Volume 120, 2023, Pages 1010-1015; ISSN 2212-8271; <https://doi.org/10.1016/j.procir.2023.09.116>. [Link](https://www.sciencedirect.com/science/article/pii/S221282712300848X)
-   Schnauffer, G., Görzig, D., Kosel, C., Diemer, J. (2022). **Asset Administration Shell for the Wiring Harness System**. In: *Kiefl, N., Wulle, F., Ackermann, C., Holder, D. (eds)* In *Advances in Automotive Production Technology – Towards Software-Defined Manufacturing and Resilient Supply Chains*. SCAP 2022. ARENA2036. Springer, Cham. <https://doi.org/10.1007/978-3-031-27933-1_30> 


# Veranstaltungen
**Folgende Veranstaltungen waren im Rahmen des Projekts VWS4LS relevant:**

| **Datum**         | **Veranstaltung**                                                                                                                                                     | **Kurzbeschreibung/Tätigkeiten**                                                                                                                                                                                                                               |
|-------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 07.03.2022        | Schulungsveranstaltung                                                                                                                                                | Virtuelle Verwaltungsschalen-Schulung durch University4Industry im Verbund mit dem Projekt „SDM4FZI“                                                                                                                                                           |
| 26.- 27.04.2022   | [D3con Hamburg](https://d3con.de/download/2022)                                                                                                                       | Kooperation mit dem Veranstalter zur Sondierung der Potenziale von Programmatic Advertising-Ansätzen für automatisierte Verhandlungsprozesse auf einer der weltweit führenden Online Adverising Konferenzen                                                    |
| 30.5.- 02.06.2022 | [Hannover Messe 2022](https://www.hannovermesse.de/de/news/news-fachartikel/hannover-messe-2022-findet-anfang-juni-statt)                                             | Projektvorstellung auf dem Stand der Plattform Industrie 4.0 mit VWS4LS-Demonstrator. Zusätzliche Vorträge:  Projektvorstellung auf der Konferenzstage der Plattform Industrie 4.0  Projektvorstellung auf der Bühne des BMWK                                  |
| 30.5.- 02.06.2022 | [Bordnetzkongress Ludwigsburg](https://www.bordnetze-kongress.de/fileadmin/user_upload/bordnetze-kongress/2022/programm_download/Agenda_de_2106.pdf)                  | Vortrag mit Projektvorstellung auf dem wichtigsten Fachkongress für das Bordnetz in Europa                                                                                                                                                                     |
| 28.06.2022        | 1. Transferkonferenz                                                                                                                                                  | Öffentliche virtuelle Projektvorstellung von VWS4LS, Dauer: 3 Stunden, die Aufzeichnung wurde veröffentlicht.                                                                                                                                                  |
| 20.- 21.07.2022   | Digital Product Forum (Mercedes-Benz)                                                                                                                                 | Projektvorstellung mit eigenem Messestand und VWS4LS-Demonstrator auf der globalen Zulieferer-Messe der Mercedes-Benz AG auf der Messe Stuttgart                                                                                                               |
| 12.09.2022        | [Pitchday Datenraum Industrie 4.0](https://www.plattform-i40.de/IP/Redaktion/DE/Kurzmeldungen/2022/Pitchday%202022-Videos.html)                                       | Vorstellung des Zusammenhangs zwischen Datenräumen und dem Projekt VWS4LS in Form eines neuen Projektansatzes basierend auf der Integration von Datenraum-basierter Kollaboration (Schwerpunkt des TP 8)                                                       |
| 20.09 2022        | [Bordnetzkongress Landshut](https://www.elektroniknet.de/automotive/wirtschaft/bordnetz-kongress-2022-in-landshut.194812.html)                                        | Vortrag zum Projekt auf dem Fachkongress für das Bordnetz an der Hochschule Landshut                                                                                                                                                                           |
| 25.- 26.10.2022   | [Klausur der Plattform Industrie 4.0](https://www.plattform-i40.de/IP/Redaktion/DE/Veranstaltungen/2023/10_Klausur-2023.html)                                         | Teilnahme und Austausch mit Experten und Vernetzung mit Experten der Plattform Industrie 4.0, insbesondere der AG 1                                                                                                                                            |
| 16.- 18.11.2022   | [Stuttgarter Conference on Automotive Production](https://scap-stuttgart.de/)                                                                                         | Teilnahme und Vorstellung des Projektes auf der wissenschaftlichen Konferenz SCAP in Stuttgart mit Fachpublikation im Tagungsband                                                                                                                              |
| 22.11.2022        | [2. Transferkonferenz](https://arena2036.de/de/vws4ls/veranstaltungen-der-vws4ls)                                                                                     | Öffentliche virtuelle Projektvorstellung von VWS4LS, Dauer: 3 Stunden, die Aufzeichnung wurde veröffentlicht.                                                                                                                                                  |
| 08.- 09.12.2022   | [AAS-Techdays der IDTA](https://industrialdigitaltwin.org/en/news-dates/aas-tech-days-for-automotive-and-supplier-industry-kopa35c-4561) und Plattform Industrie 4.0  | Teilnahme und Austausch mit Experten und Vernetzung zu Herausforderungen zur Verwaltungsschale mit anderen 35c-Vertertern                                                                                                                                      |
| 17.-21.04.2023    | [Hannover Messe 2023](https://www.bordnetze-kongress.de/fileadmin/user_upload/bordnetze-kongress/2023/bordnetze_programm_20230421.pdf)                                | Eigener Stand von VWS4LS in Halle 8, Vorstellung des Projektes mit erweiterten VWS4LS-Demonstratoren zusammen mit Vertretern der Partner als Standpersonal                                                                                                     |
| 09.- 10.5.2023    | [Bordnetzkongress Ludwigsburg](https://www.bordnetze-kongress.de/fileadmin/user_upload/bordnetze-kongress/2023/bordnetze_programm_20230505.pdf)                       | Vortrag mit Projektvorstellung sowie eigener Ausstellungsstand mit VWS4LS Demonstrator auf dem wichtigsten Fachkongress für das Bordnetz in Europa                                                                                                             |
| 25.05.2023        | [3. Transferkonferenz](https://arena2036.de/de/vws4ls/veranstaltungen-der-vws4ls)                                                                                     | Öffentliche virtuelle Projektvorstellung von VWS4LS, Dauer: 3 Stunden, die Aufzeichnung wurde veröffentlicht.                                                                                                                                                  |
| 13.06.2023        | [Halbzeit Meilensteintreffen](https://arena2036.de/de/vws4ls/veranstaltungen-der-vws4ls)                                                                              | Aufbereitung und Vorstellung bisheriger Projektergebnisse zur Fortsetzung der 2. Projekthälfte                                                                                                                                                                 |
| 21.09.2023        | [Bordnetzkongress Landshut](https://www.leitungssatz-hub.de/termine-veranstaltungen/bordnetz-kongress-2/)                                                             | Teilnahme auf dem Fachkongress für das Bordnetz an der Hochschule Landshut                                                                                                                                                                                     |
| 09.11.2023        | [AAS-Expertenworkshop](https://arena2036.de/de/vws4ls/veranstaltungen-der-vws4ls)                                                                                     | Kick-off Event des Netzwerktreffens mit der SmartFactory Kaiserslautern, mehreren anderen KoPa35c-Projekten, dem und Vorstellung einiger Projektergebnisse                                                                                                     |
| 14. -17.11.2023   | [VWS4LS auf der productronica](https://www.leitungssatz-hub.de/termine-veranstaltungen/productronica/)                                                                | Eigener Stand von VWS4LS in Halle B4, Vorstellung des Projektes mit erweitertem VWS4LS-Demonstrator                                                                                                                                                            |
| 23.11.2023        | [4. Transferkonferenz](https://arena2036.de/de/vws4ls/veranstaltungen-der-vws4ls)                                                                                     | Öffentliche virtuelle Projektvorstellung von VWS4LS, Dauer: 3 Stunden, die Aufzeichnung wurde veröffentlicht                                                                                                                                                   |
| 21.3.2024         | [AAS-Expertenworkshop](https://arena2036.de/de/vws4ls/veranstaltungen-der-vws4ls)                                                                                     | Ausrichtung des zweiten Netzwerktreffens in der ARENA2036 wieder gemeinsam mit PT und der SmartFactory Kaiserslautern und mehreren KoPa35c-Projekten                                                                                                           |
| 11.04.2024        | [Innovationsforum Leitungssatz 2024](https://www.leitungssatz-hub.de/termine-veranstaltungen/innovationsforum-leitungssatz-2024/)                                     | Teilnahme auf dem Fachkongress für das Bordnetz in der ARENA2036                                                                                                                                                                                               |
| 22.-26.04.2024    | [VWS4LS auf der Hannover Messe 2024](https://www.leitungssatz-hub.de/termine-veranstaltungen/hannover-messe/)                                                         | Eigene Standfläche auf dem Gemeinschaftstand der ARENA2036. Darstellung neuer Projektergebnisse und Vorstellung eines Demonstrators, sowie der Projektvorstellung auf der Conference-Stage Industry 4.0 zusammen mit Vertretern der Partner als Standpersonal. |
| 23.05.2024        | [5. Transferkonferenz](https://arena2036.de/de/vws4ls/veranstaltungen-der-vws4ls)                                                                                     | Öffentliche virtuelle Projektvorstellung von VWS4LS, Dauer: 3 Stunden, die Aufzeichnung wurde veröffentlicht                                                                                                                                                   |
| 25.09.2024        | [AAS-Expertenworkshop](https://arena2036.de/de/vws4ls/veranstaltungen-der-vws4ls)                                                                                     | Drittes Netzwerktreffens mit der SmartFactory Kaiserslautern und Vorstellung einiger Projektergebnisse                                                                                                                                                         |
| 26.09.2024        | [Bordnetze Digital 2024](https://www.leitungssatz-hub.de/termine-veranstaltungen/bordnetze-digital-2024/)                                                             | Projektvortrag im Rahmen des Fachkongresses zum Thema „Anbindung VWS4LS an Catena-X“                                                                                                                                                                           |
| 15.10.2024        | VWS4LS Ergebnistagung                                                                                                                                                 | Vorstellung der Projekthighlights der Öffentlichkeit                                                                                                                                                                                                           |


