---
layout: post
title: "Moving away from chat"
tags: tech
---

So I wanted to move away from chat to a terminal-based interface to run more agents and eventually give control to my computer.

Options were:

| Tool | Style | Models | Open source? | My take |
| --- | --- | --- | --- | --- |
| OpenCode | Terminal/TUI | GPT, Claude, Gemini, local models, etc. | ✅ | Best fit for what you're describing |
| Aider | Terminal | Many providers/local models | ✅ | Excellent if you want a very Git-centric workflow |
| Codex CLI | Terminal | OpenAI models | ✅ | Very capable, but less model-agnostic |
| Claude Code | Terminal | Claude | ❌ | Excellent agent, but not open source |
| Cline | VS Code | Many models | ✅ | Better if you still want an IDE |

I wanted to try the open-source models, so I decided to go ahead with OpenCode.

## Quick setup instructions

1. Ensure you have npm and Node.js installed.

   To check:

   ```
   node --version
   npm --version
   ```

2. Next, install OpenCode:

   ```
   npm install -g opencode-ai
   ```

   This means:

   - `npm` → Node's package manager
   - `install` → install something
   - `-g` → install it globally, so `opencode` is available from any directory
   - `opencode-ai` → the OpenCode CLI package

   To check:

   ```
   opencode --version
   ```

3. Once you have it installed, you can close PowerShell and open a new one.

4. Launch OpenCode:

   ```
   opencode
   ```

5. This should open the OpenCode interface.

6. To connect to the model:

   ```
   /connect
   ```

7. Again, we have multiple options now:

   1. You can try ChatGPT if you already have Plus or Pro
   2. Since I wanted to try open-source models, I decided to set up OpenRouter:

   | Provider | Top Models | Quota / Limit | RPM | Context Window | Best For |
   | --- | --- | --- | --- | --- | --- |
   | Google AI Studio | Gemini 3.6 Flash | 1,500 req/day | 15 | 1M tokens | Long-context analysis & massive codebases |
   | Groq | Llama 3.3 70B, Mixtral | 1,000 req/day | 30 | 128K tokens | Real-time apps & fast agentic loops |
   | Cerebras | Llama 3.3 70B | ~1M tokens/day | 30 | 1M tokens | Batch processing & high throughput |
   | GitHub Models | GPT-4o, Claude 3.5 Sonnet, DeepSeek R1 | 50-1,000 req/day | 15 | 8K-128K tokens | Occasional frontier model access |
   | Mistral | Codestral | ~1B tokens/month | Varies | 32K-256K tokens | Heavy coding workloads & high volume |
   | OpenRouter | Space Bunny, Laguna, North Mini Code | 50 req/day | 20 | Varies | Model routing & experimentation |

8. I decided to create an OpenRouter account and get the API key to use it in the OpenCode setup.

9. Now, if you do not have any credits, you will be restricted to 50 requests per day, which I exhausted pretty soon, so I recommend adding $10 in credits so that you do not have this restriction.

You should be all set up!

I started with commands like cleaning up my disk space, setting up my git repo locally, etc.! Will add more things soon!

*Originally published on [Substack](https://aparanagupta.substack.com/p/moving-away-from-chat).*
