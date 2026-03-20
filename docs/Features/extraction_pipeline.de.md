# Inhaltsextraktionspipeline

**Verfügbar mit:** KNOWRON Core

Wenn Sie ein Dokument in KNOWRON hochladen, verarbeitet das System es automatisch, um den Inhalt zu extrahieren und durchsuchbar zu machen. Dieser Verarbeitungsschritt — die Inhaltsextraktionspipeline — läuft im Hintergrund, ohne dass Sie etwas tun müssen. Sobald die Verarbeitung abgeschlossen ist, wird der Inhalt des Dokuments indiziert und ist sowohl für die Suche als auch für den AI-Assistenten verfügbar.

!!! note "Vollständig automatisch"
    Es muss nichts konfiguriert oder ausgelöst werden. Laden Sie ein Dokument hoch, und die Extraktion startet automatisch. Sie können den Inhalt durchsuchen, sobald die Verarbeitung abgeschlossen ist.

---

## Was die Pipeline extrahiert

Die Standard-Extraktionspipeline ist für Dokumente ausgelegt, in denen Inhalte als lesbarer Text vorliegen. Sie eignet sich gut für:

- Technische Handbücher und Servicedokumentation
- Produktspezifikationen
- Standard-PDFs und Word-Dokumente mit textbasiertem Inhalt

Für diese Dokumenttypen extrahiert die Pipeline den im Dokument vorhandenen Text und nutzt die bestehende Struktur des Dokuments — Überschriften, Abschnitte, Absätze — um den Kontext zu erhalten und die Ergebnisse leichter navigierbar zu machen. Eine grundlegende Tabellenextraktion ist ebenfalls enthalten.

<!-- IMAGE: Diagram or screenshot showing the upload-to-search flow: document uploaded → extraction → indexed and searchable -->

---

## Was nicht abgedeckt wird

Die Standard-Extraktionspipeline extrahiert keinen Text aus Bildern, die in ein Dokument eingebettet sind, sofern dieser Text nicht auch separat als tatsächlicher Text in der Datei codiert ist. Sie ist nicht geeignet für Dokumente, bei denen der primäre Inhalt visueller Natur ist, wie zum Beispiel:

- Komplexe Schaltpläne
- Technische Zeichnungen
- Stark grafiklastige oder bildbasierte technische Dokumente

Wenn ein Dokument dieses Typs hochgeladen wird, wird die Datei gespeichert und abrufbar sein, aber der visuelle Inhalt darin wird mit Standardmitteln nicht durchsuchbar sein.

---

## Für die meisten technischen Dokumentationsanforderungen ausreichend

Wenn Sie hauptsächlich mit Handbüchern, Spezifikationen und textreichen PDFs arbeiten, können Sie von Anfang an eine gute Extraktionsqualität erwarten. Die Standard-Pipeline deckt den Großteil der gängigen industriellen und technischen Dokumentation ab.

---

## Spezialisierte Extraktion für komplexe Dokumenttypen

Wenn Ihr Anwendungsfall Dokumenttypen umfasst, die über standardmäßige textbasierte Inhalte hinausgehen — zum Beispiel Schaltpläne oder technische Zeichnungen, die durchsuchbar gemacht werden sollen — sind erweiterte Extraktionsfähigkeiten verfügbar.

Wenden Sie sich an Ihren Vertriebs- oder Customer-Success-Kontakt, um zu besprechen, was für Ihre spezifischen Dokumenttypen möglich ist.

---

## Verwandte Seiten

- [Dokumente](documents.md) — wie Sie Dokumente in der Control Suite hochladen und verwalten
- [Richtlinien für den Dokumenten-Upload](../Admin%20Documentation/documents_upload_guidelines.md) — wie Sie Dokumente für die besten Extraktionsergebnisse vorbereiten
- [Suche](search.md) — wie die Suche in KNOWRON mit extrahierten Inhalten arbeitet
