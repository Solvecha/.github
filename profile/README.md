<p align="center">
  <a href="https://solvecha.com"><img src="https://solvecha.com/site/static/apple-touch-icon.png" width="72" height="72" alt="Solvecha logo"></a>
</p>

<h1 align="center">Solvecha</h1>

<p align="center">
  <b>Captcha recognition API for developers and AI agents.</b><br>
  NopeCHA-compatible. Pay per use from $0.10 per 1,000 solves. Free tier with 100 solves per day.
</p>

<p align="center">
  <a href="https://solvecha.com">Website</a> ·
  <a href="https://solvecha.com/docs">Docs</a> ·
  <a href="https://solvecha.com/pricing">Pricing</a> ·
  <a href="https://solvecha.com/ai-agents">AI agents</a> ·
  <a href="https://solvecha.com/llms.txt">llms.txt</a>
</p>

---

### What it does

Send the pictures of a captcha, get back the answer: which tiles to click, which text to type, how far to slide.

| | |
|---|---|
| **reCAPTCHA v2 image grids** | 3x3, 4x4 and dynamic 1x1 tiles |
| **Text captchas** | distorted letters and digits |
| **GeeTest slider** and **FunCAPTCHA** | positions and tile picks |
| **Accuracy** | 99.7 % of reCAPTCHAs solved within 3 tries ([how we measured](https://solvecha.com/compare)) |

### Switch from NopeCHA in one line

```diff
- BASE = "https://api.nopecha.com"
+ BASE = "https://api.solvecha.com"
```

Same paths, fields, answers and error codes. See the [migration guide](https://solvecha.com/docs/migrate-from-nopecha).

### Built for AI agents

- **MCP server** at `https://api.solvecha.com/mcp` for Claude, Cursor, OpenClaw and Hermes Agent
- **Agent skills** and **Python tools** for LangChain, CrewAI, LlamaIndex, OpenAI Agents and Browser Use: [solvecha-skills](https://github.com/Solvecha/solvecha-skills)
- **Browser extension** for Chrome, Playwright, Puppeteer and Selenium: [download](https://solvecha.com/extension)

### Pricing

| Plan | Price |
|---|---|
| Free | 100 solves per day, no card |
| Pay per use | $0.10 per 1,000 successful solves, top up any amount from $5 |
| Monthly | from $2.49 per month for 2,000 solves per day |

Prices exclude VAT. Only successful solves are charged.

<sub>Solvecha is a product of Marin Solutions UG (haftungsbeschränkt), Berlin, Germany. Not affiliated with NopeCHA, CapSolver or 2Captcha.</sub>
