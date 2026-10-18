# Hi, I'm Abhilash 👋

### Python backend and AI engineer: I build LLM systems that are tested, measured and safe to trust

📍 Bengaluru · open to remote · 📧 [abhilashyaragal570@gmail.com](mailto:abhilashyaragal570@gmail.com) · [LinkedIn](https://linkedin.com/in/abhilashyaragal)

**Open to:** remote junior backend or AI engineering roles, and freelance AI automation projects.

## What I do

I build LLM-powered backends in Python, test them properly, and deploy them. I like projects I can finish, measure and explain, and I add human-escalation paths so the AI doesn't guess when it's unsure.

- 🧪 **I test AI agents, not just write them.** AgentProbe, my own testing tool, caught a deliberate change at 100% to 0% and a partial drop at 100% to 54% on a real agent.
- 🛡️ **I design for safety.** In Nova, read-only tools run freely, anything that changes things waits for human approval, and every call has a timeout.
- 🚀 **I ship.** Four of my projects have live demos, and the tools have CI on GitHub Actions.
- 📝 **I say what I didn't test.** My READMEs have honest limitations sections.

## Featured projects

### 🔬 [AgentProbe](https://github.com/abhilashyaragal570-del/agentprobe) · [PyPI](https://pypi.org/project/agentprobe-eval/) · `pip install agentprobe-eval`
*Python, pytest, GitHub Actions · published package*

Evaluation and regression testing for AI agents. LLM agents answer differently on every run, so it repeats each test case, flags flaky cases, leaves rate-limited and timed-out runs out of the results, and compares two runs with a Fisher exact test so random noise isn't reported as a regression.

- Tested live against Nova: it caught a deliberate no-tools change on every affected case, and a partial drop from 100% to 54% on one case.
- Calculates how many runs you need to catch a drop of a given size.
- 171 unit tests, CI on Python 3.11 and 3.12, MIT licensed.

### 🤖 [Nova](https://github.com/abhilashyaragal570-del/nova) · [Live demo](https://nova-wwn8.onrender.com)
*Python, FastAPI, Gemini, PostgreSQL, Docker, GitHub Actions*

Multi-agent AI assistant where every tool call goes through one policy layer: read-only tools run freely, anything that changes things waits for approval, and every call has a timeout.

- Workflow engine: plan → approve → run → retry → resume.
- RAG document search that names its source, plus long-term memory.
- Usage and latency reports, optional OpenTelemetry tracing.
- Docker, with CI that tests the image on Linux.

The demo is password-protected, so contact me through my GitHub profile for access.

### 🎫 [SupportOps Copilot](https://github.com/abhilashyaragal570-del/supportops-copilot) · [Live demo](https://supportops-copilot-yy34.onrender.com)
*Python, FastAPI, Gemini embeddings, SQLite*

Support-ticket triage with RAG answers that cite their source, and human escalation for security reports, refund disputes and low-confidence tickets. 28/28 correct on a small hand-written evaluation set.

### ⚙️ [Automation Studio](https://github.com/abhilashyaragal570-del/automation-studio) · [Live demo](https://automation-studio-w921.onrender.com)
*Python, FastAPI, Gemini, SQLite*

Email-processing service with a restart-safe job queue, background worker, retries, token-secured webhook, dashboard and CSV export.

### 📓 [Notes Assistant API](https://github.com/abhilashyaragal570-del/notes-assistant-ap) · [Live demo](https://notes-assistant-ap.onrender.com)
*Python, FastAPI, Gemini*

Answers questions only from retrieved notes, using embeddings-based retrieval.

## Stack

**Languages and frameworks:** Python · FastAPI · Flask
**AI:** Gemini API · RAG / embeddings · agent evaluation
**Data:** PostgreSQL · SQLite
**Testing and delivery:** pytest · GitHub Actions · Docker · Render

## Get in touch

Message me on [LinkedIn](https://linkedin.com/in/abhilashyaragal570) or at [abhilashyaragal570@gmail.com](mailto:abhilashyaragal570@gmail.com).
