# AI Lead Qualification & Handoff System

An intelligent lead qualification system that replaces manual prospect screening with a structured BANT conversation flow, automatic scoring, and rep-ready handoff briefs.

## What it does

- Qualifies prospects through a 7-step structured conversation (Name → Company → Need → Budget → Timeline → Authority → Contact)
- Scores leads 0–100 across 4 dimensions: need fit, budget, urgency, decision authority
- Tags leads as Hot / Warm / Cold automatically
- Generates a rep-ready handoff brief with full score breakdown
- Exports CRM-ready rows with column headers — paste directly into Google Sheet
- Includes n8n automation workflow diagram for production deployment

## Why deterministic (no AI in scoring flow)

- Zero hallucination risk — every score is explainable with exact point values
- Works fully offline, no API key, no monthly cost
- Auditable — you can show a client exactly why a lead scored 68 vs 72
- Same architecture used in production Voice AI deployments

## Live demo

Open `index.html` in any browser. No installation needed.

## Production stack (n8n workflow included)

Webhook → Google Sheets → WhatsApp (WATI) → Slack → Gmail → CRM
All free tier tools. Zero manual data entry.

## Built by

Kaushal Raj — Applied AI & Solutions Engineer
https://linkedin.com/in/kaushal-raj-a83603380
