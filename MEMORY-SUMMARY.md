# M365 Copilot Knowledge Transfer Summary

This document is a sanitized, reusable summary of product-domain knowledge and working preferences. It intentionally excludes personal identity, reporting structure, team rosters, credentials, compensation, medical information, browsing history, and private conversation content.

## Working Preferences

- Keep responses concise and action-oriented.
- Lead with the executive summary, followed by implementation detail.
- Use clear separation between business value, product context, requirements, and technical implementation.
- Challenge assumptions and the status quo when useful.
- Prefer implementation-ready ADO work items.
- Use hypothesis-style feature descriptions.
- Structure user stories with: title, user story, Given/When/Then acceptance criteria, business value, product context, requirements/details, non-functional requirements, dependencies, Definition of Ready, Definition of Done, and assumptions.
- Release notes should use: What's Happening, What You Need to Know, and What You Need to Do. Omit a separate release-history section.

## Product and Delivery Knowledge

### ADLC and COMET

- Autonomous delivery lifecycle coverage includes story creation, development, test-story creation and execution, security and quality checks, pull-request creation, and knowledge-graph generation.
- COMET work includes product-owner and scrum-lead responsibilities, AI Adoption Day enablement, and human-in-the-loop governance.

### TTS and Crew Scheduling

- TTS is a pilot scheduling and bidding domain involving ballots, requests, choices, sequences, real-time actions, legality, seniority, and contractual limits.
- Key terminology includes OTL, PVD, QLA, RT, RTE, DOTC, RFW, sequence types, GAS, PROJ, and PPROJ.
- Relevant operational topics include ballot templates, batch timing, real-time trade and pickup behavior, partial-sequence removal, SBOA, pickup validation, CAP timing, obligation met, declined and self-repair outcomes, and hard OT limits.
- TTS behavior must account for QLA, FAR117, contractual limits, VMAX/IMAX and projection limits, training/rest buffers, OTL rules, premium handling, and seniority-in-turn optimization.

### RFW and Schedule Visibility

- RFW means Repair Flying Window.
- RFW work commonly concerns status display, calendar visibility, layover or overlay presentation, obligation state, and reuse of existing business logic and APIs.
- Display requirements should distinguish placement, status semantics, color treatment, accessibility, and responsive behavior.

### Related Airline Operations

- Domain knowledge includes AMOC BNE fatigue-risk-management considerations, FDP and rest requirements, FAA reporting, prior-day-off allocation, vacation-year implementation, premium tiers, CCA and OTL forecasting, surplus/deficit processing, aggregated OTL values, and day raise/lower behavior.
- Pilot Marketplace work includes shared sequence advertising, posted and unposted visibility, last-live-leg advertising, and capability gaps between external marketplace experiences and internal pilot-to-pilot workflows.

## Delivery Quality Checklist

- Preserve existing business rules unless the story explicitly changes them.
- Trace every feature acceptance criterion to test scenarios.
- Cover happy path, validation, exception, error, accessibility, responsive, performance, and security scenarios as appropriate.
- Identify cross-team dependencies early.
- Treat unclear or changing requirements and dependency contention as delivery risks.
- Keep auditability for critical scheduling, payment, or flight-change operations where applicable.
- Validate source data, protect sensitive information, and use environment-based configuration for software implementations.

## Use and Verification

This summary is a knowledge-transfer aid, not a substitute for the current pilot contract, approved product requirements, or authoritative operational documentation. Verify time-sensitive rules and implementation details against approved American Airlines sources before release or production decisions.
