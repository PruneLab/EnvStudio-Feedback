# EnvStudio Feedback

<p align="right">
  <a href="README.md">English (US)</a>
  |
  <a href="README.zh-Hans.md">简体中文</a>
  |
  <a href="README.zh-Hant.md">繁體中文</a>
  |
  <a href="README.ja.md">日本語</a>
  |
  <a href="README.fr.md">Français</a>
  |
  <a href="README.es.md">Español</a>
  |
  <a href="README.pt.md">Português</a>
  |
  <a href="README.ru.md">Русский</a>
  |
  <a href="README.ko.md">한국어</a>
</p>

## Über EnvStudio

**EnvStudio** ist ein moderner Windows-Umgebungsvariablen-Manager auf Basis von WinUI 3. Er ersetzt den 20 Jahre alten "Systemeigenschaften → Umgebungsvariablen"-Dialog durch eine native Windows 11-Erfahrung.

<p align="center">
  <img src="https://prunelab.net/products/envstudio/covers/de/cover1.png" width="48%" />
  <img src="https://prunelab.net/products/envstudio/covers/de/cover2.png" width="48%" />
</p>

## Herunterladen

<p align="center">
  <a href="https://apps.microsoft.com/detail/9nl5scxw3320" target="_blank">
    <img src="https://get.microsoft.com/images/en-us%20dark.svg" width="200" alt="Download from Microsoft Store"/>
  </a>
</p>

## Kernfunktionen

- **Intuitiver visueller Editor** — Umgebungsvariablen mit moderner WinUI 3-Oberfläche hinzufügen, bearbeiten, löschen und neu anordnen.
- **PATH-Listenverwaltung** — Drag-and-Drop-Sortierung, Duplikaterkennung und Erkennung toter Links.
- **EXE-Konflikterkennung** — Scannt alle Verzeichnisse im PATH nach ausführbaren Dateien und zeigt, welche von früheren Einträgen überdeckt werden, mit einem Klick zum Konflikteintrag.
- **Gültigkeitsbereich-Konflikterkennung** — Wenn eine Benutzervariable eine gleichnamige Systemvariable überdeckt, wird Durchgestrichen mit Warnsymbol angezeigt — Sie wissen immer, welcher Wert tatsächlich gilt.
- **Nicht-destruktiver Schalter** — Variable deaktivieren ohne Löschen. Benennt den Registrierungswert stillschweigend um und bewahrt die Originaldaten. Jederzeit mit einem Klick wieder aktivieren.
- **Löschsicherheitsprüfung** — Vor dem Löschen einer Variablen werden alle anderen Variablen auf `%VARNAME%`-Referenzen gescannt und vor möglichen Schäden gewarnt.
- **Variablenexpandierungs-Vorschau** — Über Werte mit `%VAR%`-Referenzen hovern, um den vollständig aufgelösten Pfad in einem Tooltip zu sehen.
- **Externe Änderungserkennung** — Überwacht die Registrierung in Echtzeit. Wenn ein anderes Programm Umgebungsvariablen ändert, während EnvStudio geöffnet ist, erhalten Sie sofort eine Aktualisierungsbenachrichtigung.
- **Profilsystem** — Variablenprofile für verschiedene Entwicklungsumgebungen speichern, wechseln und anwenden (z. B. "Java 8", "Node.js", "AI/ML").
- **Snapshot & Rollback** — Automatische Snapshots vor jeder Änderung mit Git-Stil-Diff-Ansicht und One-Click-Rollback.
- **Suche & Filter** — Variablen über Benutzer- und Systembereiche hinweg mit Regex-Unterstützung schnell finden. Übereinstimmende PATH-Untereinträge werden automatisch mit Trefferanzahl-Badge erweitert.
- **Export** — Variablen in PowerShell-, Batch- oder .env-Dateiformate exportieren, für Team-Sharing oder Systemwiederherstellung.
- **UAC-Rechteerweiterung** — Nahtlose Administratorrechte zum Bearbeiten von Systemvariablen.
- **Sofortige Übertragung** — Änderungen werden sofort über `WM_SETTINGCHANGE` systemweit übertragen.

## 100% Offline · Vollständig kostenlos

EnvStudio arbeitet **vollständig offline ohne Telemetrie oder Datenerfassung.** Ihre Umgebungskonfiguration bleibt streng auf Ihrem eigenen Rechner.

Alle Funktionen sind **vollständig kostenlos**, ohne Werbung oder Paywalls. Eine Spendenoption wird möglicherweise in Zukunft hinzugefügt, aber keine Funktionen werden jemals eingeschränkt.

Weitere Informationen finden Sie in unserer [Datenschutzerklärung](https://prunelab.net/de/products/envstudio/privacy).

---

## Feedback

> **Hinweis:** Dieses Repository enthält **nicht** den Quellcode von EnvStudio. Es dient ausschließlich dem Sammeln von Benutzerfeedback und der Problemverfolgung.

| Aktion | Link |
|------|------|
| Fehler melden | [Fehlerbericht erstellen](https://github.com/PruneLab/EnvStudio-Feedback/issues/new?template=bug_report.yml) |
| Funktion vorschlagen | [Funktionswunsch einreichen](https://github.com/PruneLab/EnvStudio-Feedback/issues/new?template=feature_request.yml) |
| Alle Issues | [Issues](https://github.com/PruneLab/EnvStudio-Feedback/issues) |

## Vor dem Melden

Bitte durchsuchen Sie zuerst die [bestehenden Issues](https://github.com/PruneLab/EnvStudio-Feedback/issues), um Duplikate zu vermeiden.

Bei Fehlerberichten bitte angeben:
- **EnvStudio-Version** (unter Einstellungen → Über)
- **Windows-Version** (z. B. Windows 11 23H2)
- **Schritte zur Reproduktion**
- **Erwartetes Verhalten** vs **tatsächliches Verhalten**
- Screenshots (falls zutreffend)

## Funktionsideen

Wir freuen uns über Ihre Ideen! Vor dem Einreichen:
- Prüfen Sie, ob der Vorschlag bereits existiert
- Beschreiben Sie den Anwendungsfall — welches Problem würde dies lösen?
- Mockups oder Referenzen sind jederzeit willkommen
