## Tethered Trust

Checks that AI agents run before they act: will this part fit what someone owns, and will this agent tool actually work and get paid.

### For shopping agents
Ask "will this work with what I own?" and get a decision with the rules checked, manufacturer sources and a signed receipt. Fit, compatibility and recall checks **before they buy**.

- **MCP server:** `https://tetheredtrust.com/mcp` (Claude, ChatGPT, Cursor, VS Code): [setup](https://tetheredtrust.com/agents)
- **JavaScript:** [`tethered-trust`](https://github.com/tetheredtrust/tethered-trust-js) · **Python:** [`tethered-trust`](https://github.com/tetheredtrust/tethered-trust-python)
- **Open spec:** [Agent Purchase Decision Record](https://tetheredtrust.com/spec/decision-record)

### For builders of MCP servers and paid agent APIs
Get found, get paid, stay working: [tetheredtrust.com/builders](https://tetheredtrust.com/builders)

- **[`launch-action`](https://github.com/tetheredtrust/launch-action):** on every release, verify your MCP server, publish it to the official MCP Registry, check x402 payments and ping search engines
- **[`verify-action`](https://github.com/tetheredtrust/verify-action):** fail the deploy if the live page or MCP server isn't actually working
- **MCP server for builders:** `https://tetheredtrust.com/mcp/builders` (launch checks, registry publishing, x402 payment checks, listing watch)
- **[Agent Tool Reliability Index](https://tetheredtrust.com/reliability):** which paid agent APIs would accept an agent's payment, with [open data](https://tetheredtrust.com/reliability.json)
- **[Launch playbook](https://tetheredtrust.com/launch/playbook):** every place an agent tool needs to be, in order

Pay per answer with USDC (x402) or prepaid credits. [Pricing](https://tetheredtrust.com/pricing) · [Trust](https://tetheredtrust.com/trust) · Operated by Chimes In LLC
