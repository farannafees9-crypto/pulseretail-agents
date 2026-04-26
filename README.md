# PulseRetail Agentic Organisation
### H9CEAI Final Project | National College of Ireland 2026

A fully agentic organisation powered by five specialised AI agents collaborating in a sequential pipeline to solve PulseRetail's customer re-engagement crisis.

## Live Demo
- **Loyalty Portal:** https://farannafees9-crypto.github.io/pulseretail-agents
- **Pipeline Runner:** https://farannafees9-crypto.github.io/pulseretail-agents/pipeline.html

## The Five Agents

| Agent | Role | Superpower |
|-------|------|------------|
| ARIA | Researcher | Deep analysis & pattern recognition |
| ZARA | Designer | Creative problem-solving & design thinking |
| FORGE | Maker | Technical craftsmanship & rapid prototyping |
| LYRA | Communicator | Persuasion & storytelling |
| CODA | Manager | Leadership & orchestration |

## Free AI APIs

This project supports **free AI APIs** (no credit card required):

1. **Groq** (Recommended) - Fast, free inference with Llama 3.3 70B
   - Get free key: https://console.groq.com/keys
2. **OpenRouter** - Free tier with various models
   - Get free key: https://openrouter.ai/keys
3. **Anthropic** - Claude API (paid)
   - Get key: https://console.anthropic.com

## How to Deploy to Your GitHub Pages

1. **Create a new GitHub repository** (e.g. `pulseretail-agents`)
2. **Upload all files** from this folder to the repo root
3. Go to **Settings → Pages → Source: Deploy from branch → main → / (root)**
4. Your site will be live at `https://YOUR-USERNAME.github.io/pulseretail-agents`

## How to Run the Pipeline (Browser)

1. Open `pipeline.html` in your browser (or visit the GitHub Pages URL above)
2. Select **Groq** (free) or **OpenRouter** from the dropdown
3. Enter your free API key from the provided link
4. Click **Launch Agentic Pipeline**
5. Watch ARIA → ZARA → FORGE → LYRA → CODA run in real time

## How to Run the Pipeline (Python)

```bash
pip install groq
export GROQ_API_KEY=your_key_here
python pipeline.py
```

## Project Structure

```
├── index.html          # PulsePass loyalty portal (working prototype)
├── pipeline.html       # Live agentic pipeline runner interface
├── pipeline.py         # Python orchestrator (run locally with API key)
├── agents/
│   ├── 1_ARIA_researcher_output.md
│   ├── 2_ZARA_designer_output.md
│   ├── 3_FORGE_maker_output.md
│   ├── 4_LYRA_communicator_output.md
│   └── 5_CODA_manager_output.md
└── docs/
    └── H9CEAI_PulseRetail_Submission.pdf
```

## AI Usage
Built with Groq API (free) using Llama 3.3 70B model.
All agents run on the Groq/OpenRouter API with streaming.
