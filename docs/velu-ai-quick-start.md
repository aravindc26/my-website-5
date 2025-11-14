---
id: velu-ai-quick-start
title: Velu AI Quick Start Guide
sidebar_position: 2
---

Kick off Velu AI with a single onboarding cycle that connects your documentation stack, ingests context, and publishes your first AI-assisted update.

## 1. Prerequisites

- **Velu AI workspace access:** Make sure you have signup credentials for your organizations Velu AI instance.
- **GitHub account with repository access:** Required to connect Velu AI to the documentation repository where updates will be proposed.
- **Source system permissions:** Ensure you can authorize Velu AI to read from contextual systems such as Google Drive and other product knowledge tools included in your pilot.

## 2. Sign Up and Complete Guided Onboarding

1. **Create or join your Velu AI workspace.** The onboarding flow walks you through the initial configuration after signup.
2. **Connect GitHub.** When prompted, authorize Velu AI to access the repository that houses your documentation. This enables the platform to open pull requests with proposed edits.
3. **Add context sources.** Use the guided steps to connect Google Drive and other knowledge repositories (for example, Slack exports, Linear, Jira, or Confluence as described in the PRD). Velu AI will ingest these signals to build its context graph.

## 3. Seed Context and Let Velu Observe

- Allow Velu AI to run its initial ingestion pass. It will gather product requirements, support tickets, specs, and existing documentation to establish a baseline understanding.
- Confirm that the ingest status shows success for each connector before moving on. Healthy connectors improve automation coverage and freshness goals outlined in the PRD (e.g., keeping fewer than 5% of docs older than the latest release).

## 4. Prompt Velu to Draft an Article

1. **Open the Velu AI interface** (Slack command, web app, or the in-product prompt field).
2. **Request a new or updated article.** Provide a concise instruction such as, Draft updated onboarding steps for the new billing workflow.
3. **Velu AI searches connected context sources.** It pulls relevant signals from GitHub, Google Drive, product tickets, and other ingested inputs to ground its draft.

## 5. Review and Create a Pull Request

1. **Inspect the generated draft.** Use the diff view to compare suggested changes against the existing documentation. Confirm that the draft aligns with your style rules and product intent.
2. **Leave inline feedback if needed.** Adjust wording, add clarifications, or request a redraw. Velu AIs approval workflow supports role-based reviews.
3. **Publish via GitHub pull request.** Once approved, trigger Velu AI to open a PR in the connected documentation repository. The PR captures the AI-generated edits alongside your review history for governance and audit trails.

## 6. Iterate and Expand Coverage

- Repeat the prompt-and-review loop for additional documentation gaps or stale pages.
- Continue connecting new context sources (support tickets, design files, transcripts) to raise automation confidence.
- Track outcomes against the PRD success metricsautomation rate, doc freshness, and turnaround timeas you scale Velu AI across teams.

With these steps complete, your organization is set up to let Velu AI act as the documentation brain: continuously monitoring product changes, drafting updates, and shipping reviewed documentation with minimal manual overhead.
