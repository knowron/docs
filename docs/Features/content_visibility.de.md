# Inhaltssichtbarkeit steuern

!!! info "Verfügbar mit KNOWRON Core — erweiterte Ebenen erfordern zusätzliche Module"
    Jeder KNOWRON-Kunde kann Inhalte auf **Intern** setzen. Die Ebene **Öffentlich** wird mit **KNOWRON View** verfügbar, die Ebene **Clients** mit **KNOWRON Connect**. [Kontaktieren Sie unser Sales-Team](mailto:sales@knowron.com) für weitere Informationen.

Wenn Sie ein Dokument, einen Artikel oder ein Tutorial in KNOWRON veröffentlichen, entscheiden Sie, wer es sehen kann. Mit der Inhaltssichtbarkeitskontrolle legen Sie dies für jeden Inhalt einzeln fest — direkt im Editor — und KNOWRON setzt diese Entscheidung einheitlich in der Control Suite und im Native Assistant durch.

Die zentrale Frage ist einfach: **Wer soll diesen Inhalt sehen können?** Jedes Inhaltsstück hat genau eine Sichtbarkeitsstufe, die aus drei Optionen gewählt wird.

<p align="center"><img src="https://i.imgur.com/1ETa9nL.png" width="80%"></p>

---

## Die drei Sichtbarkeitsstufen

| Stufe | Wer kann es sehen | Erforderliches Modul |
|---|---|---|
| **Öffentlich** | Jeder mit dem Link oder QR-Code — kein Login erforderlich | KNOWRON View |
| **Clients** | Authentifizierte externe Benutzer in einem Client Space | KNOWRON Connect |
| **Intern** | Authentifizierte Mitarbeiter Ihrer Organisation | KNOWRON Core |

Die Stufen sind **additiv**: Interne Inhalte sind für Ihre Mitarbeiter immer sichtbar, unabhängig davon, welche anderen Stufen aktiv sind. Das Hinzufügen der Stufen Öffentlich oder Clients zwingt nicht dazu, alle Inhalte öffentlich oder für Clients zugänglich zu machen — Redakteure wählen die Sichtbarkeitsstufe für jeden Inhalt individuell.

---

## Sichtbarkeit in der Control Suite festlegen

Beim Erstellen oder Bearbeiten eines Dokuments, Artikels oder Tutorials finden Sie im Editor ein Dropdown-Menü zur Sichtbarkeit. Wählen Sie die Stufe, die der vorgesehenen Zielgruppe entspricht.

<!-- IMAGE: https://i.imgur.com/pNhU8xs.png, place this one at 40% width -->

Die gewählte Sichtbarkeit wird einheitlich in beiden Produkten angewendet:

- **Öffentliche** Inhalte erscheinen auf öffentlich zugänglichen Landingpages, die per QR-Code erreichbar sind — ohne Login. Gesteuert durch das View-Modul.
- **Client**-Inhalte sind für externe Benutzer zugänglich, die in einem Client Space eingeloggt sind. Gesteuert durch das Connect-Modul.
- **Interne** Inhalte sind nur für Mitarbeiter sichtbar, die in der Control Suite oder im Native Assistant mit einem gültigen internen Konto eingeloggt sind.

!!! note "Kunden mit nur KNOWRON Core"
    Wenn Ihre Organisation nur KNOWRON Core hat, ist **Intern** die einzige verfügbare Sichtbarkeitsstufe. Die Stufen Öffentlich und Clients werden verfügbar, sobald die Module View und Connect hinzugefügt werden. Das Feature funktioniert von Anfang an vollständig — Sie wählen einfach aus der aktuell aktiven Stufe und erhalten mit wachsendem Setup Zugang zu weiteren.

---

## Interne Sichtbarkeit mit dem Workspace-Management steuern

Die Inhaltssichtbarkeitskontrolle bestimmt, **wer außerhalb Ihrer Organisation** Inhalte sehen kann. Um zu steuern, **wer innerhalb Ihrer Organisation** was sieht, verwendet KNOWRON das **Workspace-Management**.

Workspaces ermöglichen es, Benutzer und Inhalte in Gruppen zu organisieren, die die Struktur Ihres Unternehmens widerspiegeln — nach Abteilung, Region, Produktlinie oder Team. Ein einem Workspace zugewiesener Inhalt ist nur für Mitglieder dieses Workspaces sichtbar. Dies arbeitet zusammen mit den Sichtbarkeitsstufen: Ein Dokument kann intern (nur für Mitarbeiter) und zusätzlich auf einen bestimmten Workspace innerhalb dieser Gruppe beschränkt sein.

Wenn Sie KNOWRON Connect haben, bestimmt das Workspace-Management auch, welche internen Benutzer jeden Client Space verwalten und einsehen können.

→ Siehe [Workspace-Management](workspace_management.md) für eine vollständige Anleitung.

---

## Verwandte Seiten

- [Workspace-Management](workspace_management.md) — steuern, welche Mitarbeiter welche Inhalte sehen, nach Team oder Abteilung
- [Öffentliche Landingpages](public_landing_pages.md) — wie öffentliche Sichtbarkeit in der Praxis funktioniert, einschließlich QR-Codes und Assistent-Credits
- [Client Spaces](../Admin%20Documentation/client_spaces.md) — externen Kunden ihren eigenen authentifizierten Arbeitsbereich geben (KNOWRON Connect)
- [Admin-Panel](adminpanel.md) — Benutzerrollen und organisationsweiten Zugriff verwalten
