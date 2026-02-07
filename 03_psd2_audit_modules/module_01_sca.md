# Audit-Modul 01 – Starke Kundenauthentifizierung (SCA)

## 1. Zielsetzung (Objective)
Überprüfung der Konformität der implementierten Verfahren zur Starken Kundenauthentifizierung (SCA) gemäß den Anforderungen der PSD2 und der Technischen Regulierungsstandards (RTS) (EU) 2018/389.



## 2. Zentrale Risiken (Key Risks)
* **Unzulässige SCA-Ausnahmen:** Falsche Anwendung oder zu weite Auslegung der Ausnahmeregelungen (Exemptions), die zu erhöhtem Betrugsrisiko führen.
* **Schwache Authentifizierungsmechanismen:** Einsatz von Faktoren, die nicht den Anforderungen an Unabhängigkeit und Vertraulichkeit entsprechen (z.B. zu schwache Verschlüsselung, Wiederverwendung von PINs).
* **Mangelhafte dynamische Verknüpfung:** Fehlende oder fehlerhafte Verknüpfung der Authentifizierung mit dem spezifischen Betrag und Empfänger einer Transaktion.



## 3. Prüfungshandlungen (Audit Procedures)

### A. Richtlinien und Governance
* **Review der SCA-Richtlinie:** Prüfung der internen Vorgaben auf Übereinstimmung mit der PSD2/ZAG.
* **Bewertung der Ausnahmepolitik:** Überprüfung der Prozesse zur Festlegung und Überwachung von SCA-Ausnahmen (z.B. transaktionsrisikobasierte Analysen).

### B. Technische Implementierung und Tests
* **Test der Authentifizierungsflüsse:** Simulation von Transaktionen zur Überprüfung der Zwei-Faktor-Authentifizierung (Wissen, Besitz, Sein).
* **Überprüfung der Dynamischen Verknüpfung (Dynamic Linking):** Nachweis, dass der Authentifizierungscode nur für die initiierte Transaktion gültig ist.

### C. Compliance-Bewertung
* **Abgleich mit RTS-Anforderungen:** Prüfung der Dokumentation gegen die spezifischen Artikel der RTS (EU) 2018/389.
