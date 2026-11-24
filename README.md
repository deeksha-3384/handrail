# Handrail
### The Trust Infrastructure for Autonomous AI Agents

**Team Code Stack | wHACKiest 2026**

> Every AI agent can propose. Only trusted actions execute.

## Problem

AI agents can manage emails, calendars and everyday tasks. However, malicious instructions hidden inside emails, webpages and other untrusted content can manipulate agents into attempting unauthorized actions.

Users need greater visibility and control over what their AI agents execute.

## Our Solution

Handrail is a security and authorization gateway that sits between AI agents and connected applications such as Gmail and Google Calendar.

It intercepts proposed actions, tracks the origin of their arguments, evaluates deterministic security policies and controls execution.

## Key Features

- **Proposal Inbox:** Review, approve, edit or reject AI-generated actions.
- **Argument-level Taint Tracking:** Identify the origin and trust level of individual action arguments.
- **Rails & Risk Tiers:** Apply deterministic security policies using T0–T3 risk levels.
- **Untrusted Content Quarantine:** Keep data from untrusted sources identifiable throughout processing.
- **Controlled Execution:** Validate actions before execution and prevent duplicate operations.
- **Audit Logging:** Maintain a traceable record of security decisions.
- **Conditional Undo:** Reverse supported actions when safe and technically possible.

## Technical Architecture

1. AI Agent receives a user request.
2. Handrail Gateway intercepts the proposed action.
3. Provenance Engine tracks argument origins.
4. Policy Engine evaluates security rules.
5. User approval is requested when necessary.
6. Execution Controller performs permitted actions.
7. Audit Log records the outcome.

## Technology Stack

- Frontend: Next.js, TypeScript, Tailwind CSS
- Backend: Python FastAPI
- Agent Integration: Model Context Protocol (MCP)
- Database: PostgreSQL
- AI: LLM-based extraction and planning
- Visualization: React Flow and Recharts

## Evaluation Metrics

- Attack success rate
- Blocked malicious actions
- Legitimate-task completion
- False blocking rate
- Execution latency

## Project Status

Hackathon prototype in development. Features and integrations are being implemented and tested.

## Team

**Team Name:** Code Stack  
**Project:** Handrail  
**Event:** wHACKiest 2026
