# IELTSPath capstone reports

Reports of the IELTSPath capstone project and the sources of their diagrams.

| Folder | Report | Diagrams |
|---|---|---|
| `report-1-project-introduction/` | Report 1: Project Introduction | |
| `report-2-project-management-plan/` | Report 2: Project Management Plan | |
| `report-3-software-requirement-specification/` | Report 3: Software Requirement Specification | `context`, `business-flows`, `use-cases`, `screen-flows`, `erd`, `wireframes` |
| `report-4-software-design-specification/` | Report 4: Software Design Specification | `architecture`, `packages`, `classes`, `sequences`, `erd` |
| `report-5-testing/` | Report 5.1 Unit Test, 5.2 Integration Test, 5.3 System Test | |

## Rules

- One report, one folder. Diagrams go in `<report folder>/diagrams/<type>/`, nothing loose.
- Keep the submission file names, for example `Report-3_Software Requirement Specification_IELTSPath_v1.docx`. Replace the file for a new revision; git keeps the old ones.
- `.docx` and `.xlsx` files cannot be merged. Pull before editing, tell the others which report you are editing, and close the file before committing.
- Do not commit credentials or real personal data. This repository is public.

## Diagram sources

Most diagrams have a `.drawio` or `.html` source next to the exported picture, and several folders have a `build_*.py` script that draws them. The grey screen mock-ups of Report 3 are described in `report-3-software-requirement-specification/diagrams/wireframes/mockup/README.md`.

The history of these files was carried over from `docs/rp` of the backend repository.
