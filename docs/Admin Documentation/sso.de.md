# Single Sign-On (SSO)

!!! info "KNOWRON Add-on"
    Single Sign-On ist als Add-on für alle KNOWRON-Pakete verfügbar. [Kontaktieren Sie unser Sales-Team](mailto:sales@knowron.com) für weitere Informationen.

Single Sign-On ermöglicht es Ihrer Belegschaft, sich mit denselben Unternehmensanmeldedaten bei KNOWRON anzumelden, die sie bereits für andere Tools verwenden. Anstatt ein separates KNOWRON-Passwort zu verwalten, authentifizieren sich Benutzer über den Identity Provider (IdP) Ihrer Organisation — und KNOWRON lässt sie automatisch herein.

**Warum Organisationen SSO aktivieren:**

- **Eine Anmeldung für alles** — Benutzer greifen auf KNOWRON neben anderen Tools zu, ohne zusätzliche Anmeldedaten zu benötigen
- **Höhere Sicherheit** — weniger Passwörter bedeuten weniger Phishing-Risiko, Passwort-Wiederverwendung und Credential-Sprawl
- **Zentralisierte Zugriffsverwaltung** — MFA, bedingter Zugriff und das Deaktivieren ausscheidender Mitarbeiter werden an einer Stelle verwaltet (Ihrem IdP), und Änderungen werden automatisch in KNOWRON übernommen
- **Audit-Trail** — Authentifizierungsereignisse fließen in Ihre bestehenden Identitätsprotokolle und SIEM-Systeme ein

---

## Wie KNOWRON SSO funktioniert

### Benutzerbereitstellung

Wenn SSO aktiviert ist, authentifizieren sich Benutzer über Ihren IdP — benötigen aber weiterhin ein bestehendes KNOWRON-Konto, um sich anzumelden.

**Standardmäßig gilt das Pre-Provisioning-Modell.** KNOWRON-Konten müssen erstellt werden, bevor sich ein Benutzer zum ersten Mal per SSO anmeldet. Ihr Customer-Success-Kontakt kann Konten vor dem Rollout in Bulk anlegen. Dies ist bewusst so konzipiert: Es stellt sicher, dass Personen in Ihrem Verzeichnis, die sich per SSO authentifizieren *könnten*, nicht versehentlich Lizenzen verbrauchen, die sie nicht benötigen.

**Just-in-time (JIT) Benutzeranlage** ist auf Anfrage verfügbar. Mit aktiviertem JIT wird beim ersten erfolgreichen SSO-Login eines Benutzers automatisch ein KNOWRON-Konto erstellt — ohne vorherige Bereitstellung. Wenden Sie sich an Ihren Customer-Success-Kontakt oder an [support@knowron.com](mailto:support@knowron.com), um dies zu aktivieren.

### Rollen und Berechtigungen

Standardmäßig werden **Rollen in KNOWRON unabhängig von Ihrem IdP verwaltet**. Gruppen oder Rollen eines Benutzers in Ihrem Verzeichnis haben keinen Einfluss auf seine KNOWRON-Rolle — diese werden manuell im KNOWRON Admin Panel nach der Kontoerstellung vergeben.

!!! note "Kommen Sie von einem Tool, das Gruppenmitgliedschaften synchronisiert?"
    Dies ist ein häufiger Überraschungsmoment. KNOWRON ordnet IdP-Gruppen nicht automatisch KNOWRON-Rollen zu. Die Rollenvergabe liegt weiterhin in den Händen Ihrer KNOWRON-Admins, sofern keine individuelle Integration vereinbart wird.

### Verzeichnissynchronisierung (SCIM)

Automatisiertes Benutzer-Lifecycle-Management via SCIM — die Synchronisierung von KNOWRON-Konten mit Ihrem IdP, wenn Benutzer hinzukommen, die Rolle wechseln oder ausscheiden — ist **kein Bestandteil des Standard-SSO-Setups**. Es ist auf spezifische Anfrage verfügbar. Kontaktieren Sie [support@knowron.com](mailto:support@knowron.com), wenn dies eine Anforderung ist.

---

## Unterstützte Identity Provider

KNOWRON unterstützt SSO mit jedem **OIDC-kompatiblen Identity Provider**, darunter:

- **Microsoft Entra ID** (ehemals Azure Active Directory)
- **Keycloak**
- Weitere OIDC/OAuth2-konforme Anbieter

SAML wird ebenfalls auf Anfrage unterstützt.

---

## Erste Schritte

Die SSO-Konfiguration wird vollständig vom KNOWRON-Team übernommen. Um zu beginnen, wenden Sie sich an Ihren Customer-Success-Manager oder schreiben Sie an [support@knowron.com](mailto:support@knowron.com).

Vor dem Setup-Gespräch ist es hilfreich, folgendes bereitzuhalten:

- Ihren Identity Provider (Microsoft Entra ID, Keycloak oder ein anderer OIDC-kompatibler IdP)
- Ob Sie Pre-Provisioning oder JIT-Benutzeranlage wünschen
- Eine Liste der Benutzer oder Gruppen, die Zugang zu KNOWRON erhalten sollen

---

## Verwandte Seiten

- [Rollen und Berechtigungen](Security and Access/roles_and_permissions.md) — Benutzerrollen nach dem SSO-Setup zuweisen und verwalten
- [Admin-Panel](../Features/adminpanel.md) — Benutzerverwaltung in der Control Suite
