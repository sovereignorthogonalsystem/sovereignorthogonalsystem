# Sovereign Orthogonal System

Verification systems architecture for autonomous agents, crypto automation, and pre-execution safety.

## Focus

I build verifier-first systems that check proposed actions before execution.

Current focus:

- autonomous agent safety
- Solana transaction preflight
- Jupiter route verification
- simulation-based risk checks
- API middleware for crypto agents
- audit trails for automated decisions

## Featured Projects

### AgentTxGuard

Non-custodial preflight verification API for autonomous Solana agents.

AgentTxGuard checks proposed routes, Jupiter quotes, simulation reports, and Solana RPC `simulateTransaction` results before an agent signs or broadcasts a transaction.

Repo: https://github.com/sovereignorthogonalsystem/agent-txguard

### Orthogonal Verifier Core

Lightweight verifier framework for scoring proposed actions before execution.

Repo: https://github.com/sovereignorthogonalsystem/orthogonal-verifier-core

## Current Build Direction

AgentTxGuard is being developed as transaction safety middleware for agentic crypto systems.

The architecture includes:

- PASS / BLOCK / REVIEW decisions
- safety scoring
- risk policy profiles
- request IDs
- audit lookup
- API key authentication
- usage metering
- quota enforcement
- Python client SDK

## Role

Verification Systems Architect.
