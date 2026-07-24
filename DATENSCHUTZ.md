# Datenschutzerklärung für die "MYPROMPT" Erweiterung

**Letzte Aktualisierung:** 24. Juli 2026

Diese Datenschutzerklärung erläutert, wie "MYPROMPT" (im Folgenden "die Erweiterung") personenbezogene Daten erhebt, verwendet und schützt.

## 1. Verantwortlicher Entwickler

arnollldas  
E-Mail: studio.tablet657@slmail.me

## 2. Welche Daten werden erfasst?

Wenn Sie sich über Ihr Google-Konto anmelden, erfasst die Erweiterung die folgenden Daten von Google, um die Funktionalität zu gewährleisten:

*   **Ihre Google ID:** Eine eindeutige Kennung, um Ihre Prompts Ihrem Konto zuzuordnen.
*   **Ihre E-Mail-Adresse:** Zur Anzeige in Ihrem Nutzerprofil innerhalb der Erweiterung.
*   **Ihr Name:** Zur Anzeige in Ihrem Nutzerprofil.
*   **Ihr Profilbild:** Zur Anzeige in Ihrem Nutzerprofil.

Darüber hinaus werden die von Ihnen erstellten Prompts (Titel, Inhalt, Icon, Tags) in der Cloud gespeichert und mit Ihrer Google ID verknüpft.

**Es werden keine Passwörter gespeichert.** Die Authentifizierung erfolgt ausschließlich über den sicheren OAuth 2.0-Dienst von Google.

## 3. Wie werden die Daten verwendet?

Ihre Daten werden ausschließlich für die folgenden Zwecke verwendet:

*   Um Ihre Identität nach dem Login zu bestätigen.
*   Um Ihre Prompts sicher in der Cloud zu speichern und mit Ihrem Konto zu verknüpfen.
*   Um Ihnen die Synchronisierung Ihrer Prompts über verschiedene Geräte zu ermöglichen.
*   Um Ihr Profil (Name, Bild) innerhalb der Erweiterung anzuzeigen.

Ihre Daten werden **nicht** an Dritte weitergegeben, verkauft oder für Werbezwecke verwendet.

## 4. KI-Funktionen (Prompt-Verbesserung & Synthese)

Die Erweiterung bietet optionale KI-Funktionen (Prompt verbessern, Prompt generieren, Arena-Synthese). Wenn Sie diese Funktionen nutzen, wird der von Ihnen eingegebene Text zur Verarbeitung an eine serverlose Funktion (gehostet bei Vercel) weitergeleitet, die ihn verschlüsselt an den KI-Dienst Groq (groq.com) überträgt.

*   Es werden keine Eingaben dauerhaft gespeichert.
*   Die Nutzung der KI-Funktionen ist optional und setzt eine Google-Anmeldung voraus (um den KI-Zugang vor Missbrauch zu schützen).
*   Groq verarbeitet die Anfragen gemäß den eigenen Datenschutzbestimmungen: [https://groq.com/privacy-policy/](https://groq.com/privacy-policy/)

**Drittlandübermittlung:** Groq, Inc. ist ein US-amerikanisches Unternehmen (Mountain View, CA, USA). Die Übermittlung Ihrer Eingaben in die USA erfolgt auf Grundlage von Standardvertragsklauseln (Standard Contractual Clauses, SCC) gemäß Art. 46 Abs. 2 lit. c DSGVO. Rechtsgrundlage für die Verarbeitung ist Art. 6 Abs. 1 lit. f DSGVO (berechtigtes Interesse an der Bereitstellung der KI-Funktionen).

## 5. Datenspeicherung

*   **Prompts und Profildaten** werden in Google Firebase Firestore (Cloud-Datenbank) gespeichert, verknüpft mit Ihrer Google ID. Die Daten werden ausschließlich in der EU gespeichert (Region: `eur3`, EU-Multi-Region — europäische Rechenzentren). Mit Google besteht ein Auftragsverarbeitungsvertrag (AVV) gemäß Art. 28 DSGVO.
*   **Sitzungsdaten** (Login-Status/Anmelde-Token) werden lokal in Ihrem Browser gespeichert (`chrome.storage.local`). Die Erweiterung greift zum Speichern/Laden der Prompts direkt auf Google Firestore zu.
*   **Anmeldung und KI-Proxy** laufen über serverlose Funktionen bei Vercel (stellen das Anmelde-Token aus und leiten KI-Anfragen weiter, damit der KI-Schlüssel serverseitig bleibt).

## 6. Ihre Rechte

Sie haben jederzeit das Recht:

*   **Auskunft** über Ihre gespeicherten Daten zu verlangen.
*   **Löschung** Ihrer Daten zu beantragen — alle zugehörigen Prompts und Profildaten werden dauerhaft entfernt.
*   Sich bei der zuständigen **Datenschutzbehörde** zu beschweren (in Deutschland: der jeweilige Landesbeauftragte für Datenschutz und Informationsfreiheit).

Kontakt für Datenanfragen: studio.tablet657@slmail.me

## 7. Änderungen an dieser Erklärung

Diese Datenschutzerklärung kann von Zeit zu Zeit aktualisiert werden. Die jeweils aktuelle Version ist stets unter dieser URL abrufbar.

---
