# my-agent-playground
My personal space for working through the [OpenAI Agents Python SDK](https://github.com/openai/openai-agents-python) examples and building small experiments.
Forked the official repo to stay updated, but all my modifications, notes, and original mini-agents live here.

## Structure

- `basics/`          — first simple agents (hello world, streaming, basic config)
- `tools/`           — adding function tools
- `handoffs/`        — multi-agent routing and delegation
- `agent_patterns/`  — common workflow patterns (sequential, loops, etc.)
- `real_use_cases/`  — small practical bots I'm trying to build
- `notes/`           — what I learned, common errors, useful snippets

## Quick start 

```bash
python -m venv .venv
source .venv/bin/activate      # or .venv\Scripts\activate on Windows
pip install -r requirements.txt
cp .env.example .env           # then add your OPENAI_API_KEY
