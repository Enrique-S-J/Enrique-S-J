# Enrique Sanchez

**AI Engineer · LLM Infrastructure · Agents & Automation · Software Engineering**

I run the AI stack at a managed services provider end to end: a private GPU inference platform serving 50+ daily users, a RAG triage engine over 30,000+ support tickets, production MCP servers across the business toolstack, and n8n pipelines generating a seven-figure sales pipeline.

**[enrique-s-j.github.io](https://enrique-s-j.github.io/)** has the case studies · [Resume (PDF)](https://enrique-s-j.github.io/assets/Enrique_Sanchez_Resume.pdf) · [LinkedIn](https://www.linkedin.com/in/enrique-sanchez326)

## Open source

The production systems belong to my employer, so these repositories show the same patterns built fresh from public documentation, on synthetic data.

| Repository | What it is |
|---|---|
| [mcp-guardrail-proxy](https://github.com/Enrique-S-J/mcp-guardrail-proxy) | Policy and audit middleware for MCP. It wraps any MCP server, passes read-only tools through, and holds write-capable tools behind an approval step, with every call in an audit log. Python, 155 tests, CI on Linux and macOS. |
| [llm-automation-evals](https://github.com/Enrique-S-J/llm-automation-evals) | A small eval harness for LLM-powered automations: golden test cases, pluggable scorers, regression reports, and safe-failure checks, with a worked ticket-classification example run against three local models. Python, 314 tests, CI on Linux and macOS. |
| [sysops-mcp](https://github.com/Enrique-S-J/sysops-mcp) | An MCP server giving AI assistants safe, read-only visibility into a host: CPU, memory, disk, processes, network, ports, and logs. Python, 37 tests, CI on Linux and macOS. |
| [nws-mcp](https://github.com/Enrique-S-J/nws-mcp) | An MCP server for US weather from the National Weather Service API: forecasts, alerts, and observations, with no API key. TypeScript, 53 tests. |
| [n8n-ops-workflows](https://github.com/Enrique-S-J/n8n-ops-workflows) | Three importable n8n workflows for lead handling, alert digestion, and ticket summarization, each with its own documentation. |
| [Enrique-S-J.github.io](https://github.com/Enrique-S-J/Enrique-S-J.github.io) | The site itself: plain HTML and CSS with no framework, built to score 100 across all four Lighthouse categories. |

## What I work with

- **AI/LLM:** RAG and retrieval, agent orchestration, MCP server development, model evaluation and guardrails, voice agents, on-prem inference, quantization
- **Infra:** Kubernetes (Talos), Docker, GitLab CI/CD, Ansible, Linux, AWS
- **Code:** Python, JavaScript/TypeScript, Java, C/C++, SQL

B.S. Computer Science, University of Arizona. Bilingual (English/Spanish). Based in Tucson, AZ, and remote-ready.

sanchezenriquejunior01@gmail.com
