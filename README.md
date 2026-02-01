![Workflow thumbnail](assets/thumbnail.webp)

![Workflow thumbnail](assets/thumbnail.svg)

![n8n](https://img.shields.io/badge/n8n-workflow-0EA5E9)
![license](https://img.shields.io/badge/license-MIT-green)
![status](https://img.shields.io/badge/status-ready-brightgreen)

# Detect AWS Orphaned Resources & Send Cost Reports to Slack, Email, and Sheets

Advanced n8n automation for Detect AWS Orphaned Resources & Send Cost Reports to Slack, Email, and Sheets.

## Overview
- Category: DevOps
- Complexity: advanced
- Source: n8n workflow template export

## What This Automation Does
Eliminate AWS cloud waste with automated multi-region scanning, cost impact reports, compliance validation, and instant alerts. Boost savingslearn more!

## Included Files
- `workflow.json`
- `metadata.json`

## Setup
1. Import `workflow.json` into n8n.
2. Configure required credentials for the services used in the workflow nodes.
3. Update any environment variables or static values inside nodes (API keys, URLs, IDs).
4. Run a test execution and then activate the workflow.

## Tech Stack

- `n8n-nodes-base.aggregate`
- `n8n-nodes-base.awsLambda`
- `n8n-nodes-base.code`
- `n8n-nodes-base.gmail`
- `n8n-nodes-base.googleSheets`
- `n8n-nodes-base.if`
- `n8n-nodes-base.scheduleTrigger`
- `n8n-nodes-base.set`
- `n8n-nodes-base.slack`
- `n8n-nodes-base.stickyNote`

## Author

Murtaza Baig

## License
MIT License. See `LICENSE`.