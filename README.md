# LightningChart JS Trader Agent Skill

An Agent Skill for building with LightningChart JS Trader accurately in AI coding
agents.

The skill teaches agents to start every LightningChart JS Trader task from the
official LLM-friendly documentation indexes, then follow the exact
task-specific documentation and API URLs found there. This helps prevent
hallucinated method names, stale package names, wrong option shapes, and API
patterns copied from unrelated charting libraries.

**For latest user guides on LightningChart JS Trader and AI, please refer to the [Developer Documentation](https://lightningchart.com/js-charts/trader/docs/lightningChart-and-ai/)**

## Installation

Copy the `lightningchart-js-trader` folder into a skills directory supported by your
agent.

Project-local Agent Skills location:

```text
.agents/skills/lightningchart-js-trader/
```

OpenAI Codex local skills location:

```text
~/.codex/skills/lightningchart-js-trader/
```

Windows PowerShell example for Codex:

```powershell
Copy-Item -Recurse .\lightningchart-js-trader $env:USERPROFILE\.codex\skills\
```

VS Code and other Agent Skills compatible tools can also use this skill from a
project-local `.agents/skills/lightningchart-js-trader/` directory.

## Example Prompts

```text
Use $lightningchart-js-trader to add a trading chart to this React component.
```

```text
Use $lightningchart-js-trader to review this chart implementation for outdated or hallucinated LightingChart JS Trader APIs.
```

```text
Use $lightningchart-js-trader to migrate this existing chart to LightningChart JS Trader and verify the API usage with local type checks if possible.
```

That said, it seems that many agents are capable of automatically picking up locally installed skills even if your prompt doesn't explicitly mention them.

## License

This Agent Skill is licensed under the MIT License.

LightningChart JS Trader is separate proprietary software with its own licensing terms:
https://lightningchart.com/js-charts/trader/
