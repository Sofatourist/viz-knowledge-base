CONTRIBUTING — Wie du Beiträge zur Viz Knowledge Base einreichst
Kurz: Danke, dass du beitragen willst! Diese Datei erklärt, wie du Vorschläge einreichst, welche Informationen wir brauchen und wie der Review‑Prozess funktioniert.

Grundprinzip
Wir sammeln kuratierte Ressourcen zu Data Visualization, Infographics und Visual Storytelling.
Qualität vor Quantität: Bitte nur hochwertige, relevante Ressourcen vorschlagen und eine kurze Annotation (1 Satz) beifügen.
Vorgehen (Schritt für Schritt)
Fork das Repository.
Erstelle einen Branch: feat/add-<name>-to-<category>
Füge eine neue Markdown‑Datei unter /kb/ hinzu oder bearbeite eine bestehende Liste in README nach dem Format:
Beispiel (in README oder kb/<slug>.md):
Name des Repos/Tools — 1 Satz Beschreibung (Warum relevant? Use‑case)
Commit & Push auf deinen Fork.
Erstelle einen Pull Request (PR) gegen main im Original‑Repo und fülle das PR‑Template vollständig aus.
Pflichtangaben im PR
Repo URL
Kategorie (z. B. Tools, Papers, Infographics, Dashboards)
Kurze Begründung (1–2 Sätze)
Tags / Keywords (z. B. d3, svg, interactive)
Qualitätsanforderungen (CI/Checks)
Links müssen erreichbar sein (keine toten Links).
Jeder Eintrag braucht eine kurze Annotation (1 Satz), sonst wird der PR zurückgewiesen.
PRs laufen automatisch durch Linter/Linkchecker (CI). Warte bis die Checks grün sind.
Review‑Prozess
Mindestens 1 Maintainer‑Approval erforderlich für Merge.
PRs ohne Aktivität werden nach 30 Tagen als stale markiert; du kannst sie nach einer Aktualisierung wiederbeleben.
Labels / Status
Wir nutzen Labels: suggestion, needs-review, accepted, declined, stale.
Benutze Issues für Diskussionen / größere Vorschläge (nicht direkt PRs für umfangreiche Umstrukturierungen).
Stil‑Hinweise für Einträge
Nutze klare, kurze Beschreibungen. Z. B.:
d3 — Low‑level JavaScript‑Library für datengetriebene Dokumente; sehr flexibel für interaktive Visuals.
Verwende vorhandene Kategorien; falls notwendig, schlage neue Kategorien via Issue vor.
Governance & Kontakt
Maintainer: (Trage hier später die Namen/Handles ein)
Bei Fragen öffne ein Issue mit dem Label question.
Danke für deinen Beitrag — jede hochwertige Ergänzung macht die Knowledge Base besser!

Ende CONTRIBUTING.md
