# Agent: A2A-SIN-SMS

**Team:** OpenSIN-AI
**Protocol:** A2A (Agent-to-Agent)
**Status:** Active
**Repository:** https://github.com/OpenSIN-AI/A2A-SIN-SMS

## Capabilities

A2A agent for SMS integration within the OpenSIN ecosystem.

## Communication

- **Input:** A2A messages from orchestrator
- **Output:** A2A messages to other agents
- **MCP:** Standard OpenSIN MCP servers

## Security

- All operations logged to OpenSIN-Ledger
- Requires authorization token
- Guardrails enforced on all inputs/outputs

## Setup

```bash
git clone https://github.com/OpenSIN-AI/A2A-SIN-SMS.git
cd A2A-SIN-SMS
npm install
npm start
```

## License

MIT

---

## 📚 Documentation

Full documentation: **[docs.opensin.ai](https://docs.opensin.ai)**

| Section | Link |
|---------|------|
| Getting Started | [Guide](https://docs.opensin.ai/guide/getting-started) |
| API Reference | [API](https://docs.opensin.ai/api/overview) |
| Tutorials | [Tutorials](https://docs.opensin.ai/tutorials/agent-basics) |
| Integrations | [Integrations](https://docs.opensin.ai/integrations/telegram) |
| Architecture | [Architecture](https://docs.opensin.ai/architecture/overview) |
| Community | [Discord](https://discord.gg/opensin) |

## Boundary Guidance for Agents

When modifying this repo:

- Prefer SMS integration work.
- Keep claims scoped to this integration surface.
- Do not redefine broader messaging, product, ops, or docs canon from here.
