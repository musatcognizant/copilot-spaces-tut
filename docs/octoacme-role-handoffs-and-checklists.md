# Role Handoffs & Checklists

This doc contains actionable checklists and recommended handoffs between personas. Use these checklists to reduce handoff friction and clarify ownership.

## Purpose
- Standardize handoffs across planning, build, test, and release phases.
- Provide checklists that make roles' responsibilities concrete and auditable.

## Handoff: Initiation -> Planning
Owner: Project Manager (PM) / Product Manager (PdM)

Checklist:
- [ ] Project one-pager completed (PM + PdM)
- [ ] Stakeholder list and communication plan created
- [ ] High-level timeline and milestones defined
- [ ] Initial resource needs (roles identified)
- [ ] Decision recorded to progress to planning

Notes: BA or UX should be engaged at this point for discovery work.

## Handoff: Planning -> Execution
Owner: Product Manager & Project Manager

Checklist:
- [ ] Backlog prioritized with acceptance criteria and estimates
- [ ] Definition of Done documented
- [ ] Test plan/QA approach drafted
- [ ] UX designs or mockups attached to backlog items (if applicable)
- [ ] DevOps/Platform notified of upcoming releases and RFCs (if infra changes required)
- [ ] Sprint/iteration goals agreed with team

## Handoff: Execution -> Release
Owner: DevOps / Project Manager

Checklist:
- [ ] PRs merged and CI passing
- [ ] Security scans and automated tests green
- [ ] Release notes drafted
- [ ] Rollback plan and runbook reviewed
- [ ] Smoke tests defined for post-deploy checks
- [ ] Stakeholders notified of scheduled release window

## Handoff: Release -> Support / Operations
Owner: DevOps / Project Manager

Checklist:
- [ ] Post-deploy verification completed
- [ ] Monitoring and alerts validated
- [ ] On-call and support briefed
- [ ] Post-release retrospective scheduled (if high-impact)

## Process health & continuous improvement
- Each retrospective must include at least one item that checks whether handoffs and roles are working as intended.
- Track action items in project backlog and assign owners.

## RACI-inspired quick reference (example)
- Responsible: Developer, QA, DevOps (do the work)
- Accountable: Product Manager / Project Manager (owns decision)
- Consulted: UX, BA, Stakeholders (advise on design/requirements)
- Informed: Support, Security, Legal (notified as needed)

Use this doc as a living checklist and adapt to your team’s workflow.
