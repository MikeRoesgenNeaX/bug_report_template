# :beetle: Bug Report Template

#### Verbessern Sie die Effizienz der Fehlerberichterstattung: Einführung unserer umfassenden Vorlage für Fehlerberichte

Durch das Sammeln und Präsentieren dieser Informationen in einem Bug-Ticket können Entwickler unnötige Ping-Pong-Kommunikation zur Klärung vermeiden. Dieser umfassende Ansatz ermöglicht es den Entwicklern, sich auf das Verständnis des Problems zu konzentrieren, den Fehler effizient zu beheben und ein hochwertiges Produkt zu liefern. Er fördert die effektive Zusammenarbeit zwischen dem QA-Testmanager/-berichterstatter und dem Entwicklungsteam, was zu einer schnelleren Fehlerbehebung und einem besseren Benutzererlebnis führt.

Aus diesem Grund haben wir wichtige Informationen in einem Bug report template zusammengefasst, um das Erfassen und Kommunizieren eines Bugs so schnell und effizient wie möglich zu gestalten.

:warning: <i>Dieses Template versteht sich als universeller Ansatz für verschiedene Kommunikationsplattformen wie Jira, Gitlab und Trello.</i>

[Button Bug template report]: ./bug_report_template.md https://img.shields.io/badge/Bug report template öffnen-37a779?style=for-the-badge&logo=data:image/svg%2bxml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iVVRGLTgiIHN0YW5kYWxvbmU9Im5vIj8+CjxzdmcKICAgeG1sbnM6ZGM9Imh0dHA6Ly9wdXJsLm9yZy9kYy9lbGVtZW50cy8xLjEvIgogICB4bWxuczpjYz0iaHR0cDovL2NyZWF0aXZlY29tbW9ucy5vcmcvbnMjIgogICB4bWxuczpyZGY9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkvMDIvMjItcmRmLXN5bnRheC1ucyMiCiAgIHhtbG5zOnN2Zz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciCiAgIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIKICAgeG1sbnM6c29kaXBvZGk9Imh0dHA6Ly9zb2RpcG9kaS5zb3VyY2Vmb3JnZS5uZXQvRFREL3NvZGlwb2RpLTAuZHRkIgogICB4bWxuczppbmtzY2FwZT0iaHR0cDovL3d3dy5pbmtzY2FwZS5vcmcvbmFtZXNwYWNlcy9pbmtzY2FwZSIKICAgdmlld0JveD0iMCAtMjU2IDE4NTAgMTg1MCIKICAgaWQ9InN2ZzMwMjUiCiAgIHZlcnNpb249IjEuMSIKICAgaW5rc2NhcGU6dmVyc2lvbj0iMC40OC4zLjEgcjk4ODYiCiAgIHdpZHRoPSIxMDAlIgogICBoZWlnaHQ9IjEwMCUiCiAgIHNvZGlwb2RpOmRvY25hbWU9ImV4dGVybmFsX2xpbmtfZm9udF9hd2Vzb21lLnN2ZyI+CiAgPG1ldGFkYXRhCiAgICAgaWQ9Im1ldGFkYXRhMzAzNSI+CiAgICA8cmRmOlJERj4KICAgICAgPGNjOldvcmsKICAgICAgICAgcmRmOmFib3V0PSIiPgogICAgICAgIDxkYzpmb3JtYXQ+aW1hZ2Uvc3ZnK3htbDwvZGM6Zm9ybWF0PgogICAgICAgIDxkYzp0eXBlCiAgICAgICAgICAgcmRmOnJlc291cmNlPSJodHRwOi8vcHVybC5vcmcvZGMvZGNtaXR5cGUvU3RpbGxJbWFnZSIgLz4KICAgICAgPC9jYzpXb3JrPgogICAgPC9yZGY6UkRGPgogIDwvbWV0YWRhdGE+CiAgPGRlZnMKICAgICBpZD0iZGVmczMwMzMiIC8+CiAgPHNvZGlwb2RpOm5hbWVkdmlldwogICAgIHBhZ2Vjb2xvcj0iI2ZmZmZmZiIKICAgICBib3JkZXJjb2xvcj0iI2ZmZmZmZiIKICAgICBib3JkZXJvcGFjaXR5PSIxIgogICAgIG9iamVjdHRvbGVyYW5jZT0iMTAiCiAgICAgZ3JpZHRvbGVyYW5jZT0iMTAiCiAgICAgZ3VpZGV0b2xlcmFuY2U9IjEwIgogICAgIGlua3NjYXBlOnBhZ2VvcGFjaXR5PSIwIgogICAgIGlua3NjYXBlOnBhZ2VzaGFkb3c9IjIiCiAgICAgaW5rc2NhcGU6d2luZG93LXdpZHRoPSI2NDAiCiAgICAgaW5rc2NhcGU6d2luZG93LWhlaWdodD0iNDgwIgogICAgIGlkPSJuYW1lZHZpZXczMDMxIgogICAgIHNob3dncmlkPSJmYWxzZSIKICAgICBpbmtzY2FwZTp6b29tPSIwLjEzMTY5NjQzIgogICAgIGlua3NjYXBlOmN4PSI4OTYiCiAgICAgaW5rc2NhcGU6Y3k9Ijg5NiIKICAgICBpbmtzY2FwZTp3aW5kb3cteD0iMCIKICAgICBpbmtzY2FwZTp3aW5kb3cteT0iMjUiCiAgICAgaW5rc2NhcGU6d2luZG93LW1heGltaXplZD0iMCIKICAgICBpbmtzY2FwZTpjdXJyZW50LWxheWVyPSJzdmczMDI1IiAvPgogIDxnCiAgICAgdHJhbnNmb3JtPSJtYXRyaXgoMSwwLDAsLTEsMzAuMzcyODgxLDE0MjYuOTQ5MikiCiAgICAgaWQ9ImczMDI3Ij4KICAgIDxwYXRoCiAgICAgICBkPSJNIDE0MDgsNjA4IFYgMjg4IFEgMTQwOCwxNjkgMTMyMy41LDg0LjUgMTIzOSwwIDExMjAsMCBIIDI4OCBRIDE2OSwwIDg0LjUsODQuNSAwLDE2OSAwLDI4OCB2IDgzMiBRIDAsMTIzOSA4NC41LDEzMjMuNSAxNjksMTQwOCAyODgsMTQwOCBoIDcwNCBxIDE0LDAgMjMsLTkgOSwtOSA5LC0yMyB2IC02NCBxIDAsLTE0IC05LC0yMyAtOSwtOSAtMjMsLTkgSCAyODggcSAtNjYsMCAtMTEzLC00NyAtNDcsLTQ3IC00NywtMTEzIFYgMjg4IHEgMCwtNjYgNDcsLTExMyA0NywtNDcgMTEzLC00NyBoIDgzMiBxIDY2LDAgMTEzLDQ3IDQ3LDQ3IDQ3LDExMyB2IDMyMCBxIDAsMTQgOSwyMyA5LDkgMjMsOSBoIDY0IHEgMTQsMCAyMywtOSA5LC05IDksLTIzIHogbSAzODQsODY0IFYgOTYwIHEgMCwtMjYgLTE5LC00NSAtMTksLTE5IC00NSwtMTkgLTI2LDAgLTQ1LDE5IEwgMTUwNywxMDkxIDg1NSw0MzkgcSAtMTAsLTEwIC0yMywtMTAgLTEzLDAgLTIzLDEwIEwgNjk1LDU1MyBxIC0xMCwxMCAtMTAsMjMgMCwxMyAxMCwyMyBsIDY1Miw2NTIgLTE3NiwxNzYgcSAtMTksMTkgLTE5LDQ1IDAsMjYgMTksNDUgMTksMTkgNDUsMTkgaCA1MTIgcSAyNiwwIDQ1LC0xOSAxOSwtMTkgMTksLTQ1IHoiCiAgICAgICBpZD0icGF0aDMwMjkiCiAgICAgICBpbmtzY2FwZTpjb25uZWN0b3ItY3VydmF0dXJlPSIwIgogICAgICAgc3R5bGU9ImZpbGw6I2ZmZmZmZiIgLz4KICA8L2c+Cjwvc3ZnPgo=

## Welche Informationen benötigen Entwickler, um einen Bug zu lösen?

Die Bereitstellung der folgenden Informationen in einem Fehlerticket ist für Entwickler von entscheidender Bedeutung, um den gemeldeten Fehler effektiv untersuchen und beheben zu können:

1. **Zusammenfassung:**
Die Zusammenfassung bietet einen schnellen Überblick über den Fehler, sodass Entwickler das Problem auf einen Blick erfassen können. Es legt den Kontext für das gesamte Ticket fest und hilft dabei, den Fehler im Verhältnis zu anderen Aufgaben zu priorisieren.

2. **Schritte zum Reproduzieren:**
Die Schritt-für-Schritt-Beschreibung, wie der Fehler reproduziert werden kann, ist einer der wichtigsten Aspekte eines Fehlertickets. Entwickler benötigen klare Anweisungen, um das gleiche Verhalten wie der Reporter zu beobachten. Ohne ordnungsgemäße Reproduktionsschritte kann es für Entwickler schwierig sein, das Problem zu identifizieren und effektiv zu beheben.

3. **Erwartetes Ergebnis vs. tatsächliches Ergebnis:**
Das Verständnis des erwarteten Verhaltens der Funktion hilft Entwicklern, die Abweichung oder den Fehler genauer zu erkennen. Wenn Entwickler wissen, wie das Ergebnis aussehen soll, können sie die Schwere des Problems einschätzen und sich darauf konzentrieren, dass die Funktion ordnungsgemäß funktioniert.

4. **Visuelle Hilfe:**
Ein Bild sagt mehr als tausend Worte und visuelle Beweise wie Screenshots oder Videos helfen Entwicklern, die Manifestation des Fehlers zu visualisieren. Es bietet zusätzlichen Kontext und verdeutlicht, was dem Reporter begegnet ist, und hilft Entwicklern dabei, das Problem effektiv zu reproduzieren und zu lösen.

5. **Quell-URL:**
Durch die Angabe der URL der betroffenen Seite können Entwickler schnell auf den relevanten Code und die entsprechenden Ressourcen zugreifen. Es dient als direkter Bezugspunkt für Untersuchungen und Lösungen.

6. **Umgebung:**
Informationen über die Umgebung (Browser, Betriebssystem, Zoomstufe und Bildschirmgröße), in der der Fehler aufgetreten ist, helfen Entwicklern, das Problem unter ähnlichen Bedingungen zu reproduzieren. Fehler können manchmal umgebungsspezifisch sein, und die Kenntnis dieser Details hilft erheblich dabei, die Grundursache einzugrenzen.

7. **Konsolenprotokolle:**
Konsolenprotokolle enthalten oft wertvolle Fehlermeldungen und Debugging-Informationen. Die Bereitstellung dieser Protokolle hilft Entwicklern dabei, den Codefluss zu verstehen und den genauen Ort des Fehlers zu lokalisieren. Dies beschleunigt den Debugging-Prozess erheblich.

## Wie können wir sicher stellen, dass dieses Template ständig aktualisiert und weiterentwickelt wird?

Um sicherzustellen, dass die Bug-Ticket-Vorlage ständig aktualisiert und weiterentwickelt wird, befolgen Sie diese Best Practices:

1. **Regelmäßige Überprüfungen und Feedback:** Überprüfen Sie die Bug-Ticket-Vorlage regelmäßig mit dem QA-Team, den Entwicklern und anderen Beteiligten. Sammeln Sie Feedback zur Wirksamkeit und zu Verbesserungsmöglichkeiten.

2. **Iterative Verfeinerung:** Behandeln Sie die Vorlage als lebendiges Dokument, das sich im Laufe der Zeit weiterentwickelt. Kontinuierliche Verfeinerung und Aktualisierung basierend auf Feedback und Erkenntnissen aus früheren Fehlerberichten.

3. **Dokumentationsstandards:** Legen Sie klare Dokumentationsstandards innerhalb der Organisation fest. Stellen Sie sicher, dass alle Bug-Tickets der Struktur der Vorlage entsprechen und wesentliche Informationen enthalten.

4. **Schulung und Onboarding:** Informieren Sie neue Teammitglieder während der Onboarding- und Schulungssitzungen über die Bug-Ticket-Vorlage und ihre Bedeutung. Betonen Sie die Notwendigkeit einer konsistenten und umfassenden Fehlerberichterstattung.

5. **Kooperativer Ansatz:** Fördern Sie die Zusammenarbeit zwischen QA-Testmanagern und Entwicklern bei der Verfeinerung der Vorlage. Der Input der Entwickler kann hilfreich sein, um sicherzustellen, dass die Vorlage relevante technische Details enthält.

6. **Versionskontrolle:** Wenn Sie ein freigegebenes Dokument oder Wiki verwenden, implementieren Sie eine Versionskontrolle, um an der Vorlage vorgenommene Änderungen zu verfolgen. Dies ermöglicht bei Bedarf ein einfaches Rollback auf frühere Versionen.

7. **Automatisierte Tools:** Entdecken Sie die Möglichkeit der Verwendung automatisierter Bug-Reporting-Tools, die sich in Jira oder andere Bug-Tracking-Systeme integrieren lassen. Solche Tools können die Struktur der Vorlage durchsetzen und bestimmte Informationserfassungsprozesse automatisieren.

8. **Wissensaustauschsitzungen:** Organisieren Sie Wissensaustauschsitzungen oder Workshops, um Best Practices für die Fehlerberichterstattung zu besprechen. Teilen Sie Erfolgsgeschichten darüber, wie gut dokumentierte Fehlertickets zu schnelleren Lösungen führten.

9. **Metriken zur Vorlagennutzung verfolgen:** Verfolgen Sie Metriken in Bezug auf die Fehlerbehebungszeiten und die Qualität von Bug-Tickets. Analysieren Sie, wie sich die Einhaltung der Vorlage auf diese Kennzahlen auswirkt, und nutzen Sie die Daten, um kontinuierliche Verbesserungen voranzutreiben.

10. **Kultureller Schwerpunkt auf Qualität:** Fördern Sie eine Kultur, die die Bedeutung der Fehlerberichterstattung und Qualitätssicherung schätzt. Erkennen und belohnen Sie Teammitglieder, die regelmäßig gut dokumentierte Fehlerberichte bereitstellen.

11. **Community of Practice:** Richten Sie eine Community of Practice für Qualitätssicherung und Fehlerberichterstattung ein. Ermutigen Sie die Mitglieder, Erkenntnisse, Herausforderungen und Verbesserungen im Zusammenhang mit der Bug-Ticket-Vorlage auszutauschen.

12. **Flexible Vorlage:** Stellen Sie unter Beibehaltung wichtiger Informationen sicher, dass die Vorlage flexibel genug bleibt, um Änderungen in den Projektanforderungen oder sich entwickelnden Berichtsanforderungen Rechnung zu tragen.

Durch die Implementierung dieser Strategien wird sich die Bug-Ticket-Vorlage weiterentwickeln und an die sich ändernden Anforderungen des Entwicklungsprozesses anpassen, was zu einer besseren Fehlerberichterstattung und letztendlich zu einer verbesserten Produktqualität führt.