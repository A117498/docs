# CRAI Documentation

Documentation repository for the CRAI platform (Centro de Respuesta a Alertas de Igualdad).

## Contents

- **agents/**: VS Code Copilot and Cursor agent definitions for CRAI ecosystem
  - `crai-architect.agent.md` - Backend/frontend architecture agent
  - `crai-functional.agent.md` - Functional analysis and business rules agent
  - `crai-dba.md` - PostgreSQL 15.5 database architecture reference

## Architecture Agents

### crai-architect
Specialized in CRAI monolithic modular architecture (Java 17 + Angular 16 Nx).
- Code generation and refactoring
- Event-driven patterns (RabbitMQ, Camel)
- Backend modules and frontend libraries
- IoT integration (ThingWorx)

### crai-functional
Domain analysis for judicial protection platform.
- User stories and business workflows
- CRAI-specific terminology and business rules
- Alert/incident/protocol state machines
- Impact analysis across systems

### crai-dba
PostgreSQL 15.5 database administration reference.
- 12 databases catalog
- Table partitioning strategy (pg_partman 5.0.1)
- Database design patterns
- Query examples and monitoring

## Setup

To use these agents in VS Code Copilot or Cursor:

1. Copy agent files to your IDE's prompts directory
2. Reference agent names in agent-selection mode
3. Or configure in `.vscode/mcp.json` / `.cursor/prompts/`

## Connection

Database access via MCP: `postgresql://postgres:****@34.175.46.140:6432/{database}`
