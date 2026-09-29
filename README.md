# Harness, Skills and MCP Demo

An interactive walkthrough of how an agent harness uses skills and MCP servers to answer one request: "Book the cheapest SFO to Seattle flight Friday morning. Do I need an umbrella there?"

Open `dist/index.html` in a browser. Click any of the 13 steps, or press **Play all**, to see which parts talk to each other and the message they pass.

- **Harness**: runs the loop, routes tool calls, and asks you before risky actions
- **Skills**: instructions for a kind of task, loaded only when needed
- **MCP servers**: one per vendor (weather, flights, booking), each doing the real work

All data is made up; nothing calls a real service.

Live page: https://router-gao.github.io/harness-skills-mcp-demo/ (deployed from `dist/` by `.github/workflows/pages.yml`).
