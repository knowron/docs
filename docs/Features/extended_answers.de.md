# Erweiterte Antworten

Erweiterte Antworten ermöglicht dem KNOWRON-Assistenten, Fragen zu beantworten, die in der Dokumentation Ihrer Organisation nicht abgedeckt sind – auf Basis von allgemeinem Wissen, wie ein allgemeiner KI-Assistent es tun würde. Es handelt sich um eine optionale Funktion, die standardmäßig für alle Kunden deaktiviert ist.

!!! info "Wird von KNOWRON aktiviert"
    Erweiterte Antworten muss zunächst auf Kundenebene durch das KNOWRON-Team aktiviert werden, bevor die Funktion in Ihrer Umgebung verfügbar ist. Um die Aktivierung anzufordern, wenden Sie sich an Ihren KNOWRON-Ansprechpartner oder schreiben Sie an [support@knowron.com](mailto:support@knowron.com).

## Funktionsweise

Ihre Dokumentation hat immer Vorrang. Erweiterte Antworten wird nur aktiviert, wenn der Assistent keine relevanten Inhalte in der Wissensdatenbank findet. Wenn Ihre Organisation ein Konzept anders definiert als es allgemein üblich ist, wird Ihre Definition verwendet – und Erweiterte Antworten wird für dieses Thema nicht aktiviert.

Wenn ein Benutzer eine Anfrage stellt, läuft der Prozess wie folgt ab:

1. Der Assistent durchsucht zunächst die Wissensdatenbank.
2. Wenn relevante Dokumentation vorhanden ist, wird diese zur Antwortgenerierung genutzt – Erweiterte Antworten wird nicht aktiviert.
3. Wenn keine relevante Dokumentation gefunden wird und Erweiterte Antworten aktiviert ist, wird der Benutzer gefragt, ob er eine Antwort auf Basis von allgemeinem Wissen erhalten möchte.
4. Wenn der Benutzer bestätigt, wird die Antwort generiert und **eindeutig als nicht aus der Wissensdatenbank der Organisation stammend gekennzeichnet**.
5. Wenn der Benutzer ablehnt, wird keine Antwort generiert.

Diese Kennzeichnung ist bei allen Antworten aus Erweiterten Antworten immer sichtbar und kann nicht deaktiviert werden, sodass Benutzer nie im Zweifel über die Herkunft der Informationen sind.

<p align="center"><img src="https://i.imgur.com/Y3uLVL3.gif" width="80%"></p>

## Aktivierung und Zustimmung

Zwei unabhängige Bedingungen müssen erfüllt sein, bevor eine Erweiterte Antwort generiert werden kann:

**1. Aktivierung auf Kundenebene**

Die Funktion muss auf Kundenebene aktiviert sein, bevor sie für einen Benutzer verfügbar ist. Wenn sie nicht aktiviert ist, kann kein Benutzer in dieser Umgebung Erweiterte Antworten nutzen – unabhängig von seinen persönlichen Einstellungen.

**2. Benutzerbestätigung pro Anfrage**

Auch wenn die Funktion aktiviert ist, wird der Benutzer jedes Mal gefragt, wenn der Assistent eine Erweiterte Antwort generieren würde. Der Benutzer muss aktiv bestätigen, bevor eine Antwort erstellt wird.

## Benutzereinstellungen

Benutzer, die nicht bei jeder Anfrage gefragt werden möchten, können Erweiterte Antworten in ihrem Profilbereich im Native Assistant vorab autorisieren. Wenn diese Einstellung aktiviert ist, generiert der Assistent Erweiterte Antworten automatisch ohne Nachfrage, solange die Einstellung aktiv ist.

Diese Einstellung kann jederzeit im Profilbereich widerrufen werden. Danach fragt der Assistent bei jeder entsprechenden Anfrage wieder nach.

!!! note
    Einstellungen auf Kundenebene haben immer Vorrang vor persönlichen Präferenzen. Wenn Erweiterte Antworten auf Kundenebene deaktiviert ist, haben Benutzereinstellungen keine Auswirkung.

## Verwandte Seiten

- [KI-generierte Antworten](answers.de.md)
- [Assistent fragen](ask_assistant.de.md)
- [Suche](search.de.md)
