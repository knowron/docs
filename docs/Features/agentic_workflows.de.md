# Agentic Workflows

Ein Agentic Workflow bringt dem KNOWRON-Assistenten bei, wie Ihr Team eine bestimmte Aufgabe erledigt: wann sie anfällt, was zu klären ist, wo gesucht wird und wie das Ergebnis aussehen soll.

Stellen Sie es sich wie den Leitfaden vor, den Sie neuen Teammitgliedern mitgeben. Der Assistent erkennt, wann eine Frage einen Workflow erfordert, und folgt ihm. Ihre Benutzer fragen wie gewohnt.

Teil von Assistant 3.0 und für alle Kunden ohne Aufpreis enthalten. Sie legen die Aufgabe fest, unser Customer-Success-Team baut den Workflow gemeinsam mit Ihnen.

## Funktionsweise

!!! example "Beispiel: Vor der Ersatzteilbestellung sicherstellen, dass es die richtige Maschine ist"

    Die Maschinen eines Kunden haben viele ähnliche Ersatzteile, sodass eine kurze Frage leicht anhand der falschen Maschine beantwortet werden könnte. Gemeinsam mit Customer Success hat der Kunde einen Workflow erstellt, der zuerst sicherstellt, dass es um die richtige Maschine geht, und dann nur deren Dokumente durchsucht.

<div class="kn-chat">
  <div class="kn-user"><p>Ersatzteilnummer für die Dosierpumpe?</p></div>
  <div class="kn-bot">
    <p class="kn-status"><span class="kn-num">1</span> Ersatzteilanfrage erkannt</p>
    <div class="kn-card">
      <p class="kn-question"><span class="kn-num">2</span> Die Ersatzteillisten unterscheiden sich je nach Maschine. Um welche geht es?</p>
      <ul class="kn-options">
        <li>MX-200</li>
        <li class="kn-selected">MX-300</li>
        <li>MX-350</li>
        <li class="kn-other">Etwas anderes…</li>
      </ul>
    </div>
  </div>
  <div class="kn-bot">
    <p class="kn-status"><span class="kn-num">3</span> Suche nur in MX-300</p>
    <p><strong>Dosierpumpe, MX-300</strong><br>Teilenummer: 30-4471-02</p>
    <p class="kn-source"><span class="kn-dot">●</span> 1 Quelle: Ersatzteilliste MX-300</p>
  </div>
</div>

1. **Erkennt die Aufgabe.** Eine Ersatzteilanfrage, keine allgemeine Frage.
2. **Fragt nur nach, wenn es darauf ankommt.** Eine Frage, drei Vorschläge, ein Klick.
3. **Durchsucht die richtigen Dokumente.** Die Antwort kommt mit ihrer Quelle.

Bei den echten Fragen eines Kunden aus einem ganzen Jahr hätte der Assistent in 4 von 100 Fällen nachgefragt.

## Was ein Workflow festlegt

| | Beispiel: Ersatzteile |
|---|---|
| **Wann er greift** | Jemand fragt nach einem Ersatzteil |
| **Was zu klären ist** | Die Maschine, falls unklar |
| **Wo gesucht wird** | Nur in den Ersatzteillisten dieser Maschine |
| **Das Ergebnis** | Teilenummer mit Quelle |
| **Was zu vermeiden ist** | Eine laufende Fehlersuche unterbrechen |

## Ideen

- **Service:** das genaue Modell identifizieren, wiederkehrende Störungen diagnostizieren, Teilenummern entschlüsseln
- **Produktion:** Schichtübergaben, Sicherheitsprüfungen vor der Wartung, Checklisten für Umrüstungen
- **Support:** Ersatzteilanfragen mit der genauen Teilenummer beantworten
- **Ihre Kunden:** das richtige Handbuch für ihr Modell finden

Gut geeignet sind Aufgaben, die häufig vorkommen, immer denselben Schritten folgen und von Details abhängen, die gerne vergessen werden.

## So kommen Sie zu Ihrem Workflow

1. Sie wählen eine Aufgabe aus und vereinbaren einen Termin mit Customer Success.
2. Wir bauen und testen den Workflow gemeinsam mit Ihnen. Rechnen Sie mit etwa einer Woche von Ihrer ersten Anfrage bis zum Go-live.
3. Ihre Benutzer finden ihn im Assistenten. Die Pflege übernehmen wir.

!!! tip "Was uns am meisten hilft"

    Schreiben Sie auf, wie jemand aus Ihrem Team die Aufgabe heute erledigt – Schritt für Schritt, in einfachem Text. Es muss nicht ausgefeilt sein. Den Rest übernehmen wir.

## Für Admins

**Wo sehe ich Workflows?** Im Chat, sobald der Assistent einen verwendet. Eine Übersicht Ihrer aktiven Workflows erhalten Sie von Customer Success.

**Wie ändere ich einen Workflow?** Sprechen Sie mit Customer Success. Workflows lassen sich nicht im Chat bearbeiten.

**Wer kann einen Workflow sehen?** Es gelten dieselben Sichtbarkeitsregeln wie für Ihre Dokumente: intern, Kunden oder öffentlich.

**Welches Wissen wird genutzt?** Ausschließlich Ihre KNOWRON-Wissensdatenbank, nicht das Internet.

**Welche Sprachen?** Alle. Benutzer können in jeder Sprache fragen, in der sie KNOWRON nutzen.

**Können Workflows mehr?** Sprechen Sie uns an, wenn Sie die Möglichkeiten erweitern möchten.

Wenden Sie sich an Ihren Customer-Success-Kontakt unter [support@knowron.com](mailto:support@knowron.com), um Ihre ersten Workflows zu finden.
