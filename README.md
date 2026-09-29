# Harness, Skills and MCP Demo

An interactive walkthrough of how an agent harness uses skills and MCP servers to answer one request: "Book the cheapest SFO to Seattle flight Friday morning. Do I need an umbrella there?"

Click any of the 13 steps, or press **Play all**, to see which parts talk to each other and the message they pass.

- **Harness**: runs the loop, routes tool calls, and asks you before risky actions
- **Skills**: instructions for a kind of task, loaded only when needed
- **MCP servers**: one per vendor (weather, flights, booking), each doing the real work

All data is made up; nothing calls a real service.

## How to view it

**Online:** https://router-gao.github.io/harness-skills-mcp-demo/

**On your computer:**

1. Clone the repo, or click **Code → Download ZIP** and unzip it.
2. Double-click `dist/index.html`. It opens in your browser; no server or install needed.

## Publishing

Every push to `main` redeploys `dist/` to GitHub Pages through `.github/workflows/pages.yml`.

One-time setup: in the repo's **Settings → Pages**, set **Source** to **GitHub Actions**.
