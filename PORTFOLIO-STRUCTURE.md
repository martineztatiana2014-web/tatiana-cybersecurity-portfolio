# Portfolio Structure Guide

This guide explains the intended organization of the portfolio. It is a plan for gradual cleanup, not a requirement to move every file immediately.

## Recommended structure

```text
.
├── README.md
├── learning-roadmap.md
├── notes.md
├── commands.txt
├── report.md
├── labs/
│   ├── recon-scanme/
│   │   └── README.md
│   ├── packet-analysis/
│   │   └── README.md
│   └── log-monitoring/
│       └── README.md
├── templates/
│   └── lab-report-template.md
├── profile/
│   └── github-profile-draft.md
└── brand/
    └── phoenix-x-bio.md
```

## What belongs where

- `labs/` contains individual learning exercises.
- `templates/` contains reusable blank documents.
- `profile/` contains drafts for public professional profiles.
- `brand/` contains Phoenix identity and public bio drafts.
- Root-level files provide the quick overview and current learning record.

## Safe migration plan

1. Keep the original files until their contents have been reviewed.
2. Create a README inside each new lab folder before moving material.
3. Check every file for passwords, API keys, wallet phrases, tokens, private addresses, and personal information.
4. Copy only safe educational material into the new folders.
5. Review the result before deleting or archiving any old file.

## Current legacy material

The file named `Portfolio Folder` describes an earlier planned layout. It is being kept as a reference while the simpler structure above is adopted gradually.
