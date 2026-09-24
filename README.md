# AI Property Agent

AI Property Agent is an open-source multi-agent system for automating parts of the real-estate lead qualification and sales workflow.

The project explores how specialized AI agents can work together to handle prospect conversations, qualification, follow-ups, property information retrieval, viewing coordination, CRM workflows, and human-agent escalation.

## Architecture

The system uses multiple specialized agents:

### Sarah — Lead Qualification
Handles inbound prospect conversations, qualification, property questions, and identification of buying intent.

### Milo — Follow-Up
Handles follow-up and re-engagement for prospects who require additional contact.

### Jason — Viewing & Booking
Handles viewing intent and coordinates property viewing/booking workflows.

### JARVIS — Supervisor
Provides system-level supervision and operational status across the agent system.

## Current Integrations

- WhatsApp Cloud API
- Instagram messaging
- n8n workflow automation
- CRM / lead management
- Property knowledge retrieval
- Calendar and viewing workflows
- Local AI model integration

## Design Goals

The project is designed around a human-in-the-loop sales model.

AI agents handle repetitive work such as:

- Lead qualification
- Initial conversations
- Follow-ups
- Property information retrieval
- Viewing coordination
- Lead routing

Human property agents remain responsible for high-value sales decisions, negotiations, and closing.

## Safety and Reliability

The system is being developed with safeguards around:

- Verified property information
- Hallucination prevention
- Customer opt-outs
- Human-agent handoff
- Messaging-channel isolation
- Credential protection
- Conversation-state management

## Project Status

AI Property Agent is currently in active early-stage development and production testing.

The project is being iteratively tested using real messaging infrastructure before broader deployment.

## Open Source

The goal of this repository is to document and develop reusable approaches for building reliable agentic automation for real-estate workflows.

Contributions, testing, feedback, and discussion are welcome.

## Security

Do not commit API keys, access tokens, customer information, production credentials, or other secrets to this repository.
