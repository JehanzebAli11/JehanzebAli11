# Jehanzeb Ali

**Applied AI engineer: agents, evals and guardrails · game AI · native Urdu.**

I build AI agents that act in 3D worlds, plus the evals and guardrails that prove what they did.
Before AI, I spent 5+ years shipping Roblox and Unity VR games, including NFL Football Universe
(400k+ daily players) and 15+ VR titles on the Meta Store. Karachi, Pakistan · open to remote
work or relocation.

### AI work

| Project | What it is | Result so far |
| --- | --- | --- |
| [**worldsmith**](https://github.com/JehanzebAli11/worldsmith) | An AI architect fixes a broken game *room* so the same frozen player can finish it. Rooms are built in Roblox Studio over MCP from a bounded JSON recipe; a validator rejects patches that cheat. | On a room where the player fell 3 of 3 times, Claude Haiku, Sonnet and Opus each proposed one valid patch, and the rebuilt room was completed 3 of 3 (one run per model). |
| [**Autopilot** PRs](https://github.com/ramenvr/autopilot) | Contributions merged into an open-source AI agent that plays and tests games: [#40](https://github.com/ramenvr/autopilot/pull/40) Roblox Studio connector, [#38](https://github.com/ramenvr/autopilot/pull/38) model-free replay, [#39](https://github.com/ramenvr/autopilot/pull/39) `evolve` loop | Merged into `staging`, 6–7 Nov 2026 |
| [**agent-firewall**](https://github.com/JehanzebAli11/agent-firewall) | Checks an agent's action (send, pay, sign) against what the user actually asked for, before it runs | On attack styles held out of training: injection success 23.3% → 0.2% (8 of 5,000), 0.9% of legitimate actions blocked. Synthetic attacks, scripted agents. |
| [**lost-in-transliteration**](https://github.com/JehanzebAli11/lost-in-transliteration) | Do prompt-injection defences work in Urdu and Roman Urdu? | Meta Prompt Guard 2 catches 48.5% of English attacks but 11.5% of the same attacks in Roman Urdu (194/400 vs 46/399) |
| [**JzLab**](https://github.com/JehanzebAli11/JzLab) | The control room that starts and steers several Claude Code agents at once, on my Mac and an NVIDIA DGX Spark | Runs these projects |

Every number above comes from a result file in its repo, with its n.

### Building

[Valar](https://valar.digital), an AI traffic firewall that catches secrets, personal data and
prompt attacks before they reach LLMs, in English, Urdu and Roman Urdu ·
[TableSide](https://tableside.pk), photo-to-3D AR menus in Pakistani restaurants.

Also: [spark-lab](https://github.com/JehanzebAli11/spark-lab) (self-healing GPU job queue) ·
[scam-radar](https://github.com/JehanzebAli11/scam-radar) (on-device Roman Urdu scam checker) ·
[urdu-token-tax](https://github.com/JehanzebAli11/urdu-token-tax) ·
[cricket-shot-coach](https://github.com/JehanzebAli11/cricket-shot-coach)

### Stack

Python · TypeScript · PyTorch · Hugging Face (Transformers, PEFT, TRL) · vLLM · Unsloth/LoRA ·
MCP · Claude Agent SDK · evals and red-teaming · Luau · C# · Unity · Roblox Studio

[jz.business](https://jz.business) · [LinkedIn](https://www.linkedin.com/in/jehanzeb-ali-87b875187/) · jehanzebali111@gmail.com
