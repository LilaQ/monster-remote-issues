# Datenschutzerklärung für Monster Remote

Stand: 25. Oktober 2026

Monster Remote ist eine inoffizielle Begleit-App und ein Alexa-Skill für unterstützte Gym-Monster-Geräte. Monster Remote steht in keiner Verbindung zu Speediance und wird von Speediance weder unterstützt noch gesponsert.

Diese Erklärung beschreibt die Verarbeitung von Informationen und deine Wahlmöglichkeiten. Cloud-Synchronisierung, Apple Health, KI, Alexa und Spracherkennung sind optional. Die aktuelle Android-Version fordert keinen Zugriff auf Health Connect an und liest keine Health-Connect-Daten.

## Verarbeitete Informationen

Abhängig von den verwendeten Funktionen können folgende Informationen verarbeitet werden:

- **Konto:** Die private Kennung von „Mit Apple anmelden“ oder Google und gegebenenfalls ein Anzeigename. Monster Remote erhält keine Apple- oder Google-Passwörter. Dauerhafte Anbieter-Kontokennungen werden nur als Einweg-Hashes gespeichert. Apple-E-Mail-/Relay-Adressen und Google-E-Mail-Adressen werden von Monster Remote Intelligence nicht gespeichert; Konten werden nicht anhand der E-Mail-Adresse zusammengeführt.
- **Training:** Trainingsverlauf und Zusammenfassungen, etwa Übungsnamen oder Kennungen, Sätze, Wiederholungen, Widerstand, Volumen, Dauer, Entfernung, Muskelbelastung und zugehörige Gerätemesswerte.
- **Apple Health:** Nur ausdrücklich freigegebene Kategorien, etwa Schlafdauer, Ruhepuls, Herzfrequenzvariabilität und Trainingsherzfrequenz. Berechtigungen kannst du in den iOS-Einstellungen oder in Health ändern.
- **Health Connect:** Die aktuelle Android-Version verwendet diese Daten nicht. Vor einer späteren Einführung werden diese Erklärung und die Hinweise in der App aktualisiert.
- **Gerät und App:** Gerätekennungen oder Seriennummern, Firmware- und App-Versionen, Plattform, Zeitpunkte der ersten und letzten Erkennung, Verbindungsstatus, Testzeitraum und Premium-Berechtigung.
- **Training Buddies:** Freundescode, optionaler Anzeigename und Avatar-URL, Freundschaften und Anfragen, Freigabeeinstellung, aktueller Trainingsstatus, Übungs- oder Trainingstitel, Trainingsbeginn, Anfeuerungen und Zustellereignisse. Live-Aktivität wird nur bei aktivierter Freigabe und nur mit bestätigten Buddies geteilt.
- **Push-Nachrichten:** Ein Apple-Push-Gerätetoken und die Benachrichtigungsumgebung zur Zustellung von Buddy-Anfragen, Bestätigungen und Anfeuerungen. Das Token identifiziert eine App-Installation, nicht dein Apple-Passwort oder Zahlungsdaten.
- **AI Coach:** Von dir abgesendete Fragen oder Trainingswünsche sowie der dafür notwendige Trainingskontext und gegebenenfalls freigegebene Health-Kontext.
- **Abonnements:** Produktkennung, Transaktions-/Bestellkennung oder eine vom Kauftoken abgeleitete Kennung, Status, Bestätigung und Ablaufdatum. Zahlungsdaten verarbeitet Apple beziehungsweise Google; Monster Remote erhält keine Zahlungskartennummer. Für erneute serverseitige Prüfungen benötigte Google-Play-Kauftokens werden verschlüsselt gespeichert.
- **Alexa:** Vorübergehende Verknüpfungscodes und die Alexa-Kontokennung zur Zuordnung von Befehlen.
- **Diagnose:** Protokolle und Fehlerberichte, die du freiwillig für den Support teilst.
- **Optionales Firmware-Archiv:** Bei nicht unterstützter Gerätesoftware kann die App einen ausdrücklichen Upload anbieten, sofern noch kein Archiv vorliegt. Nur nach deiner Auswahl verpackt und verschlüsselt der Helper die installierte Firmware-Anwendung und überträgt das verschlüsselte Archiv mit Version, Build-Fingerabdruck, Größe und Integritäts-Hashes in privaten Cloudflare-Speicher. Eine serverseitige Reservierung verhindert gewöhnliche Mehrfachuploads. Das Archiv dient ausschließlich der Entwicklung von Kompatibilitätsunterstützung.

## Zwecke

Wir verwenden Informationen für Trainingsauswertungen und Verlaufssynchronisierung, MCP-Zugriff, AI-Coach-Antworten, Trainingsentwürfe und Buddies; für die Verfügbarkeit deines Kontos und Abonnements auf angemeldeten Geräten; für Kaufprüfungen und Nutzungsgrenzen; für die lokale Geräteverbindung und Alexa-Befehle; für Buddy-Nachrichten und freigegebene Aktivität; für ausdrücklich hochgeladene Firmware-Analysen sowie zur Missbrauchsabwehr, Zuverlässigkeit und Fehlerbehebung.

Regelbasierte Trainingsauswertungen benötigen keine KI-Anfrage. Daten für den AI Coach werden erst gesendet, wenn du eine Frage oder einen Trainingswunsch absendest.

## Spracheingabe

iOS verwendet Apples Speech-Framework, Android die ausgewählte Spracherkennungs-Engine. Android kann die Offline-Erkennung mit Vosk oder einen Systemanbieter verwenden. Ein Systemanbieter kann Audio nach seinen eigenen Datenschutzbedingungen online verarbeiten. Monster Remote speichert keine rohen Mikrofonaufnahmen. Im AI Coach erkannter Text wird erst nach dem Absenden an den KI-Dienst übertragen. Der lokale Live Coach wurde aus den aktuellen App- und Helper-Versionen entfernt.

Bei Alexa verarbeitet Amazon die Aufnahme und Spracherkennung nach seinen Datenschutzbedingungen. Monster Remote erhält nur den erkannten Befehl und gegebenenfalls den Zahlenwert.

## Cloud, MCP und KI

Monster Remote Intelligence wird auf Cloudflare betrieben. Synchronisierte Trainings- und freigegebene Health-Zusammenfassungen gehören zu deinem privaten Konto. Der Zugriffsschlüssel liegt im iOS-Schlüsselbund oder in Android-Keystore-gestütztem verschlüsseltem Speicher. App und MCP verwenden getrennte, widerrufbare Schlüssel; der Server speichert nur deren Einweg-Hashes. Behandle den MCP-Schlüssel wie ein Passwort.

Bei einer abgesendeten AI-Coach-Anfrage verarbeitet OpenAI die Anfrage und den relevanten Kontext. Die API-Anwendungsspeicherung ist deaktiviert; API-Daten werden standardmäßig nicht zum Modelltraining verwendet. Nach den standardmäßigen API-Datenregeln von OpenAI können Inhalte bis zu 30 Tage in Missbrauchsschutzprotokollen verbleiben, sofern keine längere gesetzliche Aufbewahrung erforderlich ist. Monster Remote speichert Betriebsmetadaten wie Status, Tokenverbrauch, Latenz und einen Einweg-Hash der Anfrage zur Diagnose und Durchsetzung von Nutzungsgrenzen, keine zweite vollständige Prompt-Kopie im Anfragenprotokoll. Gesprächsnachrichten bleiben für das Fortsetzen von Gesprächen gespeichert und werden mit dem Cloud-Konto gelöscht.

Für einen von dir verbundenen externen MCP-kompatiblen KI-Client gelten die Datenschutzbedingungen seines Anbieters. Monster Remote kontrolliert dessen Datenverarbeitung nicht.

## Speicherung und Löschung

Synchronisierte Trainingszusammenfassungen und zugehörige Kontodaten werden während der Nutzung grundsätzlich bis zu 1.095 Tage aufbewahrt, soweit keine längere gesetzliche Pflicht besteht. App-Sitzungen laufen nach 180 Tagen ab; MCP-Schlüssel bleiben bis zum Austausch oder Widerruf aktiv. Buddy-Beziehungen, Freigaben, Gerätetokens und Ereignisse bleiben so lange gespeichert, wie die Funktion sie benötigt, und werden mit dem Cloud-Konto gelöscht; begrenzte betriebliche Aufbewahrung für Sicherheit und Zustellung bleibt vorbehalten.

Kurzlebige Verknüpfungscodes, Uploadreservierungen und Authentifizierungs-Nonces laufen automatisch ab. Betriebs- und Berechtigungsnachweise können für Sicherheit, Abrechnung, Betrugsabwehr und gesetzliche Pflichten aufbewahrt werden. Verschlüsselte Firmware-Archive können für fortlaufende Kompatibilitätsforschung erhalten bleiben; sie dienen weder Werbung noch Nutzerprofilen.

Lokale Informationen einschließlich sicher gespeicherter MCP-Schlüssel bleiben bis zur Entfernung der App-Daten oder zur Löschung über die entsprechenden App-Funktionen erhalten. Dein Cloud-Konto und verknüpfte Daten kannst du in den privaten Kontoeinstellungen dauerhaft löschen. Bei Fragen zur Löschung kannst du uns kontaktieren.

## Weitergabe

Wir verkaufen keine personenbezogenen Daten. Notwendige Informationen werden für die gewählten Funktionen an folgende Anbieter weitergegeben:

- Apple für Anmeldung, Health-Berechtigungen, Spracherkennung, Push-Nachrichten und App-Store-Käufe;
- Google für Google-Anmeldung und Google-Play-Käufe;
- den ausgewählten System-Sprachanbieter gemäß dessen Bedingungen;
- Cloudflare für Hosting, Datenbank, privaten Objektspeicher, Netzwerk und Sicherheit;
- OpenAI bei abgesendeten AI-Coach-Anfragen;
- Amazon bei Verwendung des Alexa-Skills.

Bestätigte Buddies erhalten nur freigegebene Live-Informationen wie Trainingsstatus, Übungs-/Trainingstitel und Startzeit. Sie erhalten über diese Funktion nicht deinen vollständigen Verlauf, Health-Daten, KI-Gespräche, Konto-E-Mail, Abonnementdaten oder Geräte-Zugangsdaten. Eine Offenlegung kann außerdem gesetzlich erforderlich sein oder dem Schutz von Nutzern, Dienst und rechtlichen Ansprüchen dienen.

## Deine Wahlmöglichkeiten

Lokale Kernfunktionen und regelbasierte Funktionen benötigen weder Apple Health noch AI Coach, Buddies, Alexa, Firmware-Upload oder einen externen MCP-Client. Du kannst Health- und Benachrichtigungsberechtigungen widerrufen, Spracheingabe beenden, Buddy-Freigaben ausschalten, Freundschaften entfernen oder ablehnen, externe Clients trennen und dein Cloud-Konto löschen. Die aktuelle Android-Version fordert keinen Health-Connect-Zugriff an.

## Sicherheit

Zu den Schutzmaßnahmen gehören verschlüsselte Netzwerkübertragung für Cloud-Dienste, Verschlüsselung von Cloudflare D1 und privaten R2-Objekten im Ruhezustand, gehashte Konto- und Zugriffsschlüssel, getrennte App-/MCP-Zugangsdaten, Replay-Schutz, kontogetrennte Datenbankzugriffe, Ratenlimits und serverseitige Berechtigungsprüfungen. Das Speediance-Kontotoken wird lokal vom Helper verwendet und ist von Netzwerk-Snapshots, Diagnosen, Cloud-Synchronisierung, MCP und Monster-Remote-Serverspeicherung ausgeschlossen. Vollständige Sicherheit kann kein internetverbundener Dienst garantieren.

## Kinder

Monster Remote richtet sich nicht an Kinder unter 13 Jahren. Wir erheben wissentlich keine personenbezogenen Daten von Kindern unter 13 Jahren.

## Änderungen und Kontakt

Änderungen dieser Erklärung werden hier mit aktualisiertem Datum veröffentlicht. Bei Datenschutzfragen oder Löschanfragen: **info@emudev.de**.
