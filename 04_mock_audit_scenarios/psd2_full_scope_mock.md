# Simulation: Umfassendes PSD2-Internal Audit (Mock Audit)

Dieses Szenario simuliert ein jährliches internes Audit, das den gesamten Umfang der regulatorischen Anforderungen der PSD2 und des ZAG abdeckt.



## 1. Szenario (Scenario)
Im Rahmen des jährlichen Prüfungsplans führt die interne Revision eine umfassende Prüfung der PSD2-Konformität durch. Ziel ist es, die Angemessenheit und Wirksamkeit des gesamten Kontrollsystems zu bewerten, das für die Einhaltung der Zahlungsdiensterichtlinie implementiert wurde.

## 2. Typische Feststellungen (Typical Findings)
Erfahrungsgemäß werden in diesem umfassenden Audit häufig folgende Schwachstellen identifiziert:

* **Übermäßige Nutzung von SCA-Ausnahmen:** Die Ausnahmeregelungen (Exemptions) werden zu breit angewendet, um die User Experience zu verbessern, wodurch das Sicherheitsniveau sinkt.
* **Schwache Dokumentation der XS2A-Tests:** Die technische Konformität der Schnittstellen für Drittanbieter (APIs) ist nicht ausreichend dokumentiert, oder die Testprotokolle sind unvollständig.



## 3. Umsetzungsplan (Remediation Plan)
Für festgestellte Mängel müssen Maßnahmenpläne erstellt werden:
* **Maßnahmen zur SCA-Optimierung:** Überarbeitung der Risikomodelle zur Anwendung von Ausnahmen.
* **Verbesserung der Dokumentationsprozesse:** Einführung automatisierter Test- und Dokumentationswerkzeuge für die API-Schnittstellen.
