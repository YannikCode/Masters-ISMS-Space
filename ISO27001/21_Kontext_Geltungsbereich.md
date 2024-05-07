# Kontext und Interessierte Parteien

Zusätzlich zu den in *11_Informationsverbund.md* erhobenenen Assets/Zielobjekten werden für den ISO-Ansatz folgende Informationen beim Geltungsbereich berücksichtigt.  

## Externer und interner Kontext

### Externer Kontext
Kontextbereich | Beschreibung 
--- | ---
Gesellschaftlich | Stellenwert der Informationssicherheit wird generell immer wichtiger - Gesellschaft erwartet Maßnahmen zur Prävention.
Politisch | Die Politik intensiviert Bestrebungen in der Informationssicherheit und hat insbesonders KRITIS Unternehmen und dessen Dienstleister verstärkt im Augenmerk.
Finanziell | Durch Informationssicherheit entstehen Kosten, diese sollten aber die Kosten eventueller Informationssicherheitsvorfälle reduzieren.
Regelung | Zurzeit werden Regulierungen bezüglich der Informationssicherheit in der Branche für Bodenstationen durchgesetzt. Man muss damit rechnen, dass sich dies in der Zukunft weiter ausdehnt. 
Recht | Unterschiedlichste Gesetze und Vorgaben sind für Satellitenmission im Forschungskontext relevant.
Wettbewerb | Gewissenhafte Informationssicherheit ist im Wettbewerb von großen Vorteil. Der Trend geht im Sektor zu Security by Design.
Natürliche Umgebung | Der Standort befindet sich in einer nicht nachteiligen natürlichen Umgebung. Es sind keine besonderen standortbezogenen Faktoren bekannt, die das ISMS beeinflussen.
Ukraine-Krise | Durch den Krieg wurde auch der Allgemeinheit offengelegt, dass Satellitensysteme vulnerabel sind und einem effektivem Schutz bedarf.

### Interner Kontext
Kontextbereich | Beschreibung 
--- | ---
Governance | Die Universität und dessen Fachgebiete möchten Informationssicherheit aus strategischen und taktischen Gründen vorantreiben.
Organisationsstruktur | Durch die hierarchische Struktur der Universität bilden sich Schnittstellen, die außerhalb des Verantwortungsbereichs der Forschungsgruppe liegen.
Richtlinien | Bestehende Richtlinien sollen, soweit vorhanden, berücksichtigt werden.
Ziele und Strategien | Für das Forschungsprojekt ist eine adäquate Absicherung ein Ziel. Eine Zertifizierung wird für das zu prüfende Explorationsprojekt nicht angestrebt. Möglicherweise aber für ein Folgeprojekt.
Vertragsbeziehungen | Vertragsbeziehungen fordern für ein Produktivsystem teilweise eine Informationssicherheitszertifizierung. Es wird erwartet, dass diese Forderung zukünftig vermehrt von Kunden gestellt wird.

## Interessierte Parteien und Anforderungen
Interessierte Parteien | Anforderungen 
--- | ---
Gesetzgeber | Konformität zu geltenden Gesetzen
TU Berlin | Reputationssicherung, Risikominimierung, Partnerbindung in der Forschung, Erhöhung des Sicherheitsniveaus, Sicherung zukünftiger Forschungsaufträge
Mitarbeiter Forschungsprojekt | Sicherung des Unternehmens durch Schutz gegen Informationssicherheitsvorfälle, Verminderung möglicher Risiken, Sicherung der Reputation, Sicherheit für die eigenen Handlungen, Geringe Beeinträchtigung des eigenen Aufgabengebiets
Deutsches Luft- und Raumfahrtzentrum | Unterstützung Forschungsprojekte zur Erhöhung der Sicherheit im KRITIS-Sektor durch Verwendung von Weltrauminfrastruktur
Deutsches Zentrum für Satelliten-Kommunikation | Partner für Bodenstationen, Nationales Kommunikationsnetzwerk, Forschungs voran treiben
bdew/Vattenfall | KRITIS Dienstleister, Gewährleistung eigener IT-Sicherheit
Ruhr-Universität Bochum | Teilnahme am Projekt - Technische IT-Sicherheit
CISPA | Teilnahme am Projekt - Technische IT-Sicherheit
QuantiCor | Teilnahme am Projekt - Entwicklung und Erprobung quantensichere Verschlüsselungssysteme
Berlin Nanosatellite Alliance | Teilnahme am Projekt - CyBEEsat Entwicklung

# Geltungsbereich
Alle Prozesse und Verfahren, die während des gesamten Lebenszyklus für die zu entwickelnde Satellitennutzlast direkt oder über Schnittstellen relevant sind.  
Dazu gehöre auch alle Bestandteile (Anwendungen, IT-Systeme, Netze und physische Infrastruktur), die für die Erfüllung der Prozesse und Verfahren unterstützend benötigt werden.  

# Profil der Forschungsgruppe in Relation zur TU Berlin
Das RACCOON-Projekt des Fachgebiets Raumfahrttechnik der Technischen Universität Berlin ist Teil einer seit langer Zeit erfolgreich forschender Einrichtung. Das vierköpfige Team hinter dem Projekt entwickelt eine Nutzlast für einen Kleinsatelliten. Die Nutzlast soll eine globale Übertragung von Sicherheitsschlüsseln ermöglichen, um in der Folge eine quantensichere und interferenzunempflindliche Kommunikation zu gewährleisten. Zunächst wird in dem zu sichernden Vorprojekt ein Proof of Concept erstellet, ehe es sich in einem möglichen Folgeprojekt um eine Erprobung im Weltall dreht. Bei erfolgreicher Erprobung der Nutzlast wäre diese als sicherheitskritisch zu betrachten und im Rahmen eines vollwertigen ISMS mit Zertifizierung abzusichern.  
Die elementaren Geschäftsprozesse des Forschungsprojektes werden anhand des Lifecycles der zu entwickelnden Nutzlast modelliert, um eine vollumfängliche Sicht auf die sich ändernden Bedingungen über alle Lebensphasen hinweg abzudecken:  
ID | Prozess  
--- | --- 
G00 | Gemeinsame IT-Infrastruktur
G01 | Konzeption und Design 
G02 | Herstellung
G03 | Test
G04 | Transporte
G05 | Inbetriebnahme
G06 | Betrieb
G07 | Außerbetriebnahme

# Abgrenzung des Geltungsbereichs
Alle Bestandteile, die für die Erfüllung der Prozesse und Verfahren zwar benötigt, aber nicht berücksichtigt werden können. Generell werden die Bestandteile für die Betrachtung ausgeschlossen, die nicht im Verantwortungsbereich der Forschungsgruppe liegen.  
1. Bodensegment mit Kontrollzentrum und Supportinfrastrukturen
2. Mögliche Plattform für eine In-Orbit-Demonstration wie der TUBiX-5 oder TUBiX-20
3. Systeme, die über die TU Berlin oder einen Dienstleister bezogen und nicht selbst gehosted werden

Benötigte Schnittstellen zu den genannten Bestandteilen werden aus Sicht der Forschungsgruppe berücksichtigt.  

# Schnittstellen und Abhängigkeiten

## Interne Schnittstellen und Abhängigkeiten
- TU Berlin
    - Die Dachorganisation ist selber im Prozess ein ISMS einzuführen. Dies muss bei vollständiger Ausgestaltung berücksichtigt werden
    - Die gestellte Infrastruktur der TU unterliegt den Sicherheitstandards der Universität
- Fachbereiche und Projekte der TU angrenzend zum RACCON-Projekt, die nicht direkt im Geltungsbereich sind, jedoch eine gewisse gegenseitige Abhängigkeit zum Geltungsbereich aufweisen

## Externe Schnittstellen und Abhängigkeiten
Sicherheitsmaßnahmen der Schnittstellen und Abhängigkeiten zu allen Dienstleistern im Kontext des ISMS sollten einzeln begutachtet werden:  
- Ruhr-Universität Bochum und CISPA für Entwicklung des RACCOON OS
- QuantiCor's Q-Toolkit als quantensichere Bibliothek für Verschlüsselungspraktiken
- Anwendungen und Tools des Test/Launch-Centers (vermutlich SpaceX)
- Finanzierung durch Projektpartner bdew, Vattenfall, DeSK, DLR
