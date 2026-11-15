# Agenda

## CI/CD-Pipeline

Stand: 2026-11-15

- Keine Workflows behalten: kein Test-, Release- oder Tag-Workflow.
- Entfernt: `.github/workflows/github-stats.yml` (scheduled Stats-Update, monatlich). Grund: nicht nötig, kein Test-, Release- oder Tag-Workflow. Damit ist `.github/workflows` leer und wurde entfernt.
- Regel: Vor jedem PR lokal alle Pipeline-Schritte ausführen.
