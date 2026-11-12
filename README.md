## Hi, I'm Abheesht Tripathi 👋

**I find and fix security holes in AI apps and agents**, and build backends that hold up in production.
AI & Backend Engineer · Go · Python · Node.js · Postgres · Docker · Kubernetes · AWS · Azure

🎓 M.Tech, NIT Kurukshetra · B.Tech, NSUT West Campus

---

### 🛡️ Open-source security tools

Static checkers that print the exact fix and fail CI. Standard library only, MIT.

| Tool | Catches |
|---|---|
| [mcp-audit](https://github.com/abhi12337/mcp-audit) | MCP servers and configs: tool input reaching a shell, files, SQL, URLs or eval; leaked tokens; unpinned packages |
| [rules-file-audit](https://github.com/abhi12337/rules-file-audit) | Hidden instructions and invisible Unicode in `.cursorrules`, `CLAUDE.md`, `AGENTS.md`; auto-approve settings |
| [inject-test](https://github.com/abhi12337/inject-test) | Runs 57 prompt-injection attacks against your own LLM app in CI and reports which ones worked |
| [supa-launch-check](https://github.com/abhi12337/supa-launch-check) | Supabase: missing RLS, `using (true)` policies, leaked service_role keys, public buckets |
| [firebase-launch-check](https://github.com/abhi12337/firebase-launch-check) | Firebase: open rules, test mode left on, sign-in-only checks, service account keys |
| [key-leak-check](https://github.com/abhi12337/key-leak-check) | OpenAI / Anthropic / Stripe keys shipped to the browser via `NEXT_PUBLIC_`, `VITE_` and bundles |
| [route-auth-check](https://github.com/abhi12337/route-auth-check) | API routes with no auth, IDOR, open Server Actions, admin routes without role checks |
| [webhook-check](https://github.com/abhi12337/webhook-check) | Stripe, Razorpay, GitHub, Shopify webhooks that skip or break signature verification |
| [llm-cost-lint](https://github.com/abhi12337/llm-cost-lint) | LLM calls with no output cap or timeout, unbounded history, uncached prompts, retired models |
| [pg-launch-check](https://github.com/abhi12337/pg-launch-check) | Postgres: unindexed foreign keys, locking migrations, N+1, per-request pools, SQL injection |

📝 Writing: [Prompt injection meets your MCP server: 8 patterns to check](https://dev.to/abheesht_builds/prompt-injection-meets-your-mcp-server-8-patterns-to-check-and-a-tool-that-finds-them-593g)

---

### 💼 Work with me

- **Quick Review**: top 5 problems in your app with exact fixes, in 48 hours. $149 / ₹9,999
- **AI agent security check**: every tool, permission and data path tested against prompt injection, written report and fixes in 5 working days. $1,500
- **Backend and AI builds**: APIs, integrations, Postgres, queues, LLM features. Fixed price

📫 abheeshttripathi890@gmail.com
