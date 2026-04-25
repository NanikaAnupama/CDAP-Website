# Documents folder

These are placeholder files referenced by `index.html`. **Replace each one with your actual document, keeping the exact filename** so the download links keep working.

## Presentations you already have

Drop these PDFs into this folder, renaming them to match exactly:

| Your file | Rename to |
|---|---|
| `Proposal Presentation.pdf` | `proposal-presentation.pdf` |
| `Progress Presentation 1.pdf` | `progress-presentation-1.pdf` |
| `Progress Presentation 2.pdf` | `progress-presentation-2.pdf` |

Quickest way (Windows PowerShell, run from project root):

```powershell
Move-Item "Proposal Presentation.pdf"   "docs/proposal-presentation.pdf"   -Force
Move-Item "Progress Presentation 1.pdf" "docs/progress-presentation-1.pdf" -Force
Move-Item "Progress Presentation 2.pdf" "docs/progress-presentation-2.pdf" -Force
```

## Full filename reference

| Filename | Description |
|---|---|
| `project-charter.pdf` | Scope, objectives, schedule, participants |
| `project-proposal.pdf` | Goals, milestones, requirements |
| `research-paper.pdf` | Literature review, methodology, analysis |
| `final-thesis.pdf` | Final solution write-up |
| `status-documents.pdf` | Periodic progress vs plan |
| `research-logbook.pdf` | Weekly research activity log |
| `business-plan.pdf` | Commercialisation plan |
| `checklist-documents.pdf` | Submission checklists |
| `module-reports.zip` | Bundled M01–M04 individual reports |
| `proposal-presentation.pdf` | Initial proposal slides |
| `progress-presentation-1.pdf` | 50% review slides |
| `progress-presentation-2.pdf` | 90% review slides |
| `final-presentation.pdf` | 100% completion slides |

If you want to rename a file, also update its `href` in `index.html` (under the `#documents` and `#presentations` sections).
