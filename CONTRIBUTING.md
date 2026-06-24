# Contributing to Awesome AI Agents

Thanks for your interest in improving this list!

## How to Contribute

### Adding a New Tool or Framework

1. Fork the repository
2. Add the tool to the appropriate section in README.md
3. Follow the table format exactly:

| Repository | Description | Stack | Engine | Deployment | Link |
|---|---|---|---|---|---|
| **ToolName** | Brief, technical description | Language/Framework | Local Inference / API-based / Hybrid / N/A | CLI / Web UI / Docker / Library / IDE Extension / Document | [Link](https://url) |

4. Engine classification:
   - **Local Inference** — Runs models locally (Ollama, llama.cpp, etc.)
   - **API-based** — Requires external API calls (OpenAI, Anthropic, etc.)
   - **Hybrid** — Supports both local and API-based inference
   - **N/A** — Not applicable (guides, directories, documents)

5. Verify the link works before submitting
6. Submit a pull request

### Adding a New Section

1. Open an issue with the proposed section name and at least 5 tools that would fit
2. Wait for approval before submitting a PR
3. Follow the existing heading format: `## N. Section Name`

### Reporting Broken Links or Outdated Info

Open an issue with:

- Title: "Broken link: [tool name]" or "Outdated: [tool name]"
- The section number and the current entry

## Guidelines

- Only add tools that are actively maintained or historically significant
- Keep descriptions concise and technical — avoid marketing language
- Verify all links before submitting
- Do not duplicate entries across sections
- One tool per PR is preferred — bulk additions may take longer to review
- Respect the CC0-1.0 license — contributions are released into the public domain
