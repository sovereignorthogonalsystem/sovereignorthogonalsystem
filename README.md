# Sovereign Orthogonal System

Verification systems architecture for autonomous agents, crypto infrastructure, and pre-execution safety.

## Focus

I build infrastructure for systems that propose actions before execution.

Current focus:

- autonomous agent safety
- Solana transaction preflight
- AI-agent tool-call policy
- Jupiter route verification
- simulation-based risk checks
- Prometheus/Grafana observability
- audit trails for automated decisions

## Featured Projects

### AgentTxGuard

Non-custodial preflight verification API for autonomous Solana agents.

Checks route metadata, Jupiter quotes, simulation reports, and Solana RPC `simulateTransaction` results before an agent signs or broadcasts a transaction.

https://github.com/sovereignorthogonalsystem/agent-txguard

### Solana Observability Stack

Production-style monitoring stack for Solana RPC, AgentTxGuard, and autonomous transaction infrastructure.

Includes FastAPI metrics, Prometheus config, alert rules, Grafana dashboard provisioning, Docker Compose, runbooks, and a postmortem template.

https://github.com/sovereignorthogonalsystem/solana-observability-stack

### AI Agent Action Firewall

Policy and audit middleware for autonomous AI-agent actions and tool calls.

Checks external side effects, sensitive data, destructive actions, financial tools, cost ceilings, request IDs, and audit lookup before execution.

https://github.com/sovereignorthogonalsystem/ai-agent-action-firewall

### Orthogonal Verifier Core

Lightweight verifier framework for scoring proposed actions before execution.

https://github.com/sovereignorthogonalsystem/orthogonal-verifier-core

## Role

Verification Systems Architect.

## Direction

Building infrastructure for autonomous systems that need:

- PASS / BLOCK / REVIEW decisions
- safety scoring
- preflight verification
- policy enforcement
- usage metering
- request tracing
- audit lookup
- operational observability
