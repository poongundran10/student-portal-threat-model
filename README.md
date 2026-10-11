# Student Login Portal — Threat Model

## Project purpose
A beginner defensive-security exercise that models a fictional student login portal, identifies STRIDE threats, ranks risks, and recommends security hardening controls.

## Files
- `Threat_Model_Report.pdf` — overview, diagram, STRIDE analysis, risk register, checklist, and verification plan.
- `threat-model.png` — threat-model diagram with a trust boundary and data flows.
- `hardening-checklist.md` — editable prioritized checklist.

## Important scope note
This is a design exercise for a fictional application. Risk scores are illustrative assumptions. No real application was tested, and no implementation controls are claimed as verified.

## Priorities
1. Server-side authorization and administrator privilege boundaries.
2. Password storage, authentication rate limits, and secure sessions.
3. Safe audit logging, monitoring, and resilience.

## Suggested verification
Use only a local application you own or are explicitly authorized to test. Record actual outcomes and evidence before marking any control as tested.
