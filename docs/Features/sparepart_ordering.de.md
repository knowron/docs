# Ersatzteilbestellung

Mit der Ersatzteilbestellung können Ihre Benutzer Ersatzteile direkt aus KNOWRON heraus anfordern — ohne das System wechseln zu müssen. Benutzer durchsuchen die bereits einer Maschine zugeordneten Teile, legen die benötigten Teile in den Warenkorb und senden eine Anfrage ab. KNOWRON leitet diese Anfrage per E-Mail an die zuständige Person in Ihrer Organisation weiter.

Die Funktion ist sowohl in der Control Suite als auch im Native Assistant verfügbar.

---

## So funktioniert es

Eine Ersatzteilanfrage wird in drei Schritten eingereicht:

1. **Durchsuchen** Sie die für die betreffende Maschine verfügbaren Ersatzteile
2. **Fügen Sie** ein oder mehrere Teile zum Warenkorb hinzu
3. **Senden** Sie die Anfrage ab, wenn Sie fertig sind

<p align="center"><img src="https://i.imgur.com/ySkoAM1.png" width="80%"></p>

<p align="center"><img src="https://i.imgur.com/vwvuGBZ.png" width="40%"></p>

!!! note "Teile müssen zuerst eingerichtet werden"
    Ersatzteile müssen hochgeladen und einer Produktlinie zugeordnet werden, bevor Benutzer sie bestellen können. Weitere Informationen finden Sie unter [Ersatzteilbestand](partsinventory.md).

---

## Eine Anfrage ist kein Kauf

Wenn ein Benutzer eine Ersatzteilanfrage einreicht, **findet keine Kauftransaktion statt**. KNOWRON erstellt eine Anfrage und sendet diese als E-Mail an einen vordefinierten Empfänger — nicht mehr.

Dies ist so beabsichtigt. Unternehmen handhaben Preisgestaltung, Einkaufsabläufe und Beschaffungsberechtigungen sehr unterschiedlich. Anstatt ein einheitliches Einkaufsmodell vorzuschreiben, leitet KNOWRON die Anfrage an die richtige Person weiter und überlässt die Auftragsabwicklung Ihren internen Prozessen.

---

## Was nach dem Absenden passiert

Wenn eine Anfrage abgesendet wird, sendet KNOWRON eine E-Mail an eine vorkonfigurierte Empfängeradresse. Diese Adresse kann auf drei Arten festgelegt werden:

- **Admin Panel** — Administratoren können die Empfängeradresse jederzeit festlegen und aktualisieren. Dies gilt für Anfragen interner Benutzer.
- **Pro Client Space** — Die Empfängeradresse für Anfragen externer Benutzer in einem Client Space kann ebenfalls im Admin Panel konfiguriert werden — separat pro Client Space.
- **Regionale Supportkontakte** — Wenn regionale Support-E-Mail-Adressen gemeinsam mit Ihrem Customer-Success-Team hinterlegt wurden, können Anfragen stattdessen an diese Adressen weitergeleitet werden.

→ Unter [Admin Panel](adminpanel.md) können Sie die Empfängeradresse konfigurieren.

---

## Umfang einer Anfrage

Jede Ersatzteilanfrage ist auf **eine einzige Maschine oder Produktlinie** beschränkt. Benutzer können keine Teile aus mehreren Maschinen in einer Anfrage kombinieren.

---

## Was die E-Mail enthält

Die generierte E-Mail enthält:

- Wer die Anfrage erstellt hat
- Auf welche Maschine oder Produktlinie sich die Anfrage bezieht
- Welche Ersatzteile angefordert wurden, einschließlich der Mengen

Die Auftragsabwicklung übernimmt Ihre Organisation anschließend gemäß ihrem eigenen Beschaffungsprozess.

---

## Externe Benutzer über Client Spaces

Externe Benutzer — wie Kunden oder Partnertechniker — können über ihren Client Space Ersatzteilanfragen einreichen. Sie sehen nur die Teile, die explizit für sie freigegeben wurden, beschränkt auf ihre Maschinen. Das eliminiert den typischen Hin-und-Her-Aufwand bei Ersatzteilanfragen: keine Unklarheiten über Teilenummern, Maschinenvarianten oder Kompatibilität. Was der Kunde einreicht, ist von vornherein korrekt.

→ Unter [Client Spaces](../Admin%20Documentation/client_spaces.md) erfahren Sie mehr darüber, wie der externe Benutzerzugriff funktioniert.

---

## Verwandte Seiten

- [Ersatzteilbestand](partsinventory.md) — Ersatzteile hochladen und verwalten, bevor Bestellungen möglich sind
- [Admin Panel](adminpanel.md) — Empfänger-E-Mail-Adresse für Ersatzteilanfragen konfigurieren
- [Client Spaces](../Admin%20Documentation/client_spaces.md) — externen Benutzern Zugriff auf die Ersatzteilbestellung ermöglichen
- [Workspace-Verwaltung](workspace_management.md) — steuern, welche Benutzer auf welche Produktlinien und die zugehörigen Teile zugreifen können
