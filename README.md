# Splunk SOC Analyst Portfolio

A hands-on, dataset-based portfolio documenting my learning and practical work with Splunk Enterprise for SOC Analyst workflows.

> **Project status: In Progress**
>
> This repository is a starter structure. Practical work, findings, screenshots, detections and dashboards will be marked complete only after they have been performed and verified.

## Learning workflow

1. Find and download a security dataset.
2. Record its source, license, format and scenario.
3. Ingest it into Splunk.
4. Validate the index, sourcetype, timestamps and fields.
5. Develop and test SPL searches.
6. Investigate the activity and document evidence-based findings.
7. Develop detection logic and test it against the available data.
8. Build dashboards from validated searches.
9. Publish sanitized screenshots and documentation.

## Repository map

| Folder | Purpose |
|---|---|
| `01-splunk-fundamentals/` | Splunk concepts, architecture and search basics |
| `02-datasets-and-ingestion/` | Dataset register, provenance and ingestion notes |
| `03-spl-queries/` | Reusable SPL learning and query library |
| `04-investigations/` | Evidence-based security investigation reports |
| `05-detections/` | Detection logic, testing and tuning |
| `06-dashboards/` | Dashboard requirements, panels and searches |
| `07-alert-management/` | Alert configuration and triage notes |
| `08-evidence/` | Sanitized screenshots and supporting evidence |
| `09-learning-log/` | Learning progress and next steps |

## Planned practical scenarios

- Authentication activity and failed logons
- Brute-force / password-spraying hypotheses
- Suspicious process and PowerShell activity
- Account creation and group membership changes
- Network connection analysis
- Web access log analysis

These are **planned scenarios**, not claims that the work has already been completed.

## Tools

- Splunk Enterprise
- Search Processing Language (SPL)
- Public security datasets (source and license recorded per dataset)
- MITRE ATT&CK (for technique references where supported by evidence)

## Evidence and integrity

- Do not upload confidential, personal, proprietary or licensed data unless redistribution is permitted.
- Do not publish credentials, tokens, private customer data or sensitive IP information.
- Distinguish observed facts from hypotheses.
- Do not claim an attack occurred merely because a query returned matching events.
- Record dataset limitations, time range, timezone, index and sourcetype.
- Label screenshots and exercises as `Planned`, `In Progress` or `Completed`.

## Status legend

- **Planned:** not started
- **In Progress:** currently being worked on
- **Completed:** tested and supported by evidence
- **Needs Review:** completed once but requires validation or improvement

## Getting started

Start with `02-datasets-and-ingestion/dataset-register.md`, then follow `02-datasets-and-ingestion/ingestion-notes-template.md`.

See `09-learning-log/progress.md` for the current progress tracker.
