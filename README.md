<div align="center">

<img src="logo.svg" alt="Awesome AI Game" width="720">

# Awesome AI Game [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)

**A curated list of the hottest AI-powered games, playable world models, game-playing agents, and AI game development tools.**

*Games where artificial intelligence is not a buzzword — it is the gameplay.*

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](CONTRIBUTING.md)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](LICENSE)
[![Link Check](https://img.shields.io/badge/links-checked_weekly-blue?style=flat-square)](.github/workflows/link-check.yml)

</div>

---

AI is transforming games from static, hand-authored experiences into living systems: NPCs that genuinely converse, stories that write themselves around your choices, and entire game worlds generated frame-by-frame by neural networks. This list tracks the frontier.

**Legend:** 🔥 Trending · 🆓 Free to play · 💰 Paid / freemium · 🧪 Beta / research preview · 📜 Open source

## Contents

- [Hot Top 10 AI Games](#hot-top-10-ai-games)
- [AI-Native Games](#ai-native-games)
  - [Conversational & AI NPC Games](#conversational--ai-npc-games)
  - [AI Storytelling & Text Adventures](#ai-storytelling--text-adventures)
  - [AI Party & Social Games](#ai-party--social-games)
  - [Sandbox & Simulation](#sandbox--simulation)
- [Neural Game Engines & Playable World Models](#neural-game-engines--playable-world-models)
- [AI Agents That Play Games](#ai-agents-that-play-games)
- [Hall of Fame: Landmark Game AI](#hall-of-fame-landmark-game-ai)
- [Milestones: When AI Beat the Game](#milestones-when-ai-beat-the-game)
- [Building Games with AI](#building-games-with-ai)
  - [Games Built Entirely by AI](#games-built-entirely-by-ai)
  - [AI Game Creation Platforms](#ai-game-creation-platforms)
  - [NPC & Dialogue Middleware](#npc--dialogue-middleware)
  - [Asset Generation](#asset-generation)
- [Open Source Projects](#open-source-projects)
- [Research & Papers](#research--papers)
- [Communities & Resources](#communities--resources)
- [Contributing](#contributing)

## Hot Top 10 AI Games

The editor's shortlist — the ten AI games making the most noise right now. *(Updated June 2026)*

| # | Game | What it is | Why it's hot | Price |
|:-:|------|------------|--------------|:-----:|
| 🥇 | [Oasis](https://decart.ai/) | AI-generated open world | The first playable game rendered entirely by a neural network — no engine, no code, millions of players | 🆓 |
| 🥈 | [Whispers from the Star](https://www.anuttacon.com/) | Real-time AI survival drama | Talk a stranded astronaut through life-or-death decisions by voice; the most cinematic AI NPC experience yet | 💰 |
| 🥉 | [Project Genie (Genie 3)](https://deepmind.google/models/genie/) | Text-to-world model | Type a prompt, step into an explorable 3D world generated in real time — DeepMind's glimpse of gaming's future | 🧪 |
| 4 | [Death by AI](https://deathbyai.gg/) | AI party survival game | A viral phenomenon: an AI judge decides if your escape plan survives — chaotic fun with millions of players | 🆓 |
| 5 | [Infinite Craft](https://neal.fun/infinite-craft/) | LLM crafting sandbox | Four elements in, infinite internet culture out; the most shared browser AI game ever made | 🆓 |
| 6 | [Suck Up!](https://www.playsuckup.com/) | AI NPC comedy | The proof that talking to AI characters can be genuinely hilarious gameplay — charm villagers or stay outside | 💰 |
| 7 | [AI Dungeon](https://aidungeon.com/) | Infinite text adventure | The genre's pioneer, still the deepest pure AI storytelling sandbox after years of model upgrades | 🆓 |
| 8 | [Friends & Fables](https://fables.gg/) | AI dungeon master | D&D 5e campaigns with an AI GM, tactical battlemaps, and multiplayer — the most complete AI tabletop platform | 💰 |
| 9 | [Red Alert 2: Web Edition](https://sanwan.ai/articles/red-alert-fable.html) | AI-built RTS | A complete browser RTS planned, coded, tested, and shipped autonomously by Claude Fable 5 — a milestone for AI-made games | 🆓 |
| 10 | [AI Roguelite](https://store.steampowered.com/app/1889620/AI_Roguelite/) | LLM-everything RPG | The first Steam RPG where every entity, recipe, and combat outcome is LLM-generated | 💰 |

## AI-Native Games

Games where a generative model drives the core mechanic — remove the AI and the game ceases to exist.

### Conversational & AI NPC Games

Talk your way through the game. Every character listens, remembers, and answers in real time.

- [Whispers from the Star](https://www.anuttacon.com/) 🔥💰 - Guide Stella, an astrophysics student stranded on an alien planet, through real-time voice and text conversations. Your words decide whether she survives. By Anuttacon.
- [Suck Up!](https://www.playsuckup.com/) 🔥💰 - You are a vampire who must charm, deceive, and sweet-talk AI-powered villagers into inviting you inside their homes. By Proxima Enterprises.
- [Dead Meat](https://store.steampowered.com/app/2007010/Dead_Meat/) 💰 - An AI-driven murder-mystery interrogation game: question a suspect who lies, cracks, and confesses dynamically.
- [Vaudeville](https://store.steampowered.com/app/2240920/Vaudeville/) 💰 - A noir detective game where you interrogate AI-voiced characters with unscripted dialogue to solve the case.
- [Retail Mage](https://www.jamandtea.studio/) 💰 - A cozy improv-comedy RPG set in a magical furniture store, where AI improvises with whatever chaos you type. By Jam & Tea Studios.

### AI Storytelling & Text Adventures

Infinite narratives, generated as you play. The dungeon master is a language model.

- [AI Dungeon](https://aidungeon.com/) 🔥🆓 - The pioneer of AI-driven interactive fiction: limitless, player-steered adventures in any genre. By Latitude.
- [Friends & Fables](https://fables.gg/) 🔥💰 - An AI Game Master running D&D 5e-inspired campaigns with tactical battlemaps, persistent worlds, image generation, and multiplayer parties.
- [Hidden Door](https://www.hiddendoor.co/) 🧪 - Narrative AI platform that turns books and fictional worlds into social roleplaying adventures, co-authored with an AI narrator.
- [LoreKeeper](https://lore-keeper.com/) 💰 - AI dungeon master backed by a real server-side D&D 5e rules engine — actual dice, initiative, conditions, and spell mechanics.
- [AI Roguelite](https://store.steampowered.com/app/1889620/AI_Roguelite/) 💰 - The first RPG on Steam with entirely LLM-generated entities, crafting recipes, combat mechanics, and AI-illustrated scenes.
- [1001 Nights](https://www.1001nights.ai/) 🧪 - Award-winning AI-native game where you play Scheherazade, weaving tales with an AI king and turning story words into real weapons.
- [Infinite Worlds](https://infiniteworlds.app/) 💰 - Choose-your-own-adventure stories with persistent state, AI-generated art, and worlds shared by a creator community.

### AI Party & Social Games

Generative AI as the party host — chaotic, hilarious, and different every round.

- [Death by AI](https://deathbyai.gg/) 🔥🆓 - Party survival game where an AI judges whether your plan survives deadly scenarios. A viral hit with millions of players.
- [Infinite Craft](https://neal.fun/infinite-craft/) 🔥🆓 - Combine elements to discover an unbounded, LLM-generated crafting tree. Start with four elements; end up with philosophers, memes, and gods. By Neal Agarwal.
- [Player2](https://player2.game/) 🆓 - A platform of AI-powered multiplayer party games and companions, including AI-driven social deduction.

### Sandbox & Simulation

Living worlds populated by autonomous agents with goals, memories, and social lives.

- [AI People](https://www.goodai.com/) 🧪 - Life-simulation sandbox by GoodAI where every character is an LLM-driven agent that perceives, remembers, and schemes.
- [AI Town](https://github.com/a16z-infra/ai-town) 🆓📜 - A deployable virtual town where AI characters live, chat, and socialize — a production-ready take on the "Smallville" generative agents paper. By a16z infra.
- [Voyager](https://github.com/MineDojo/Voyager) 📜 - An LLM-powered lifelong learning agent that autonomously explores Minecraft, writes its own skill code, and never stops improving.

## Neural Game Engines & Playable World Models

No game engine, no hand-written rules — every frame is dreamed up by a neural network in real time. The most radical shift in how games are made since 3D.

- [Oasis](https://decart.ai/) 🔥🆓 - The first playable, real-time AI-generated open-world game. A Minecraft-like world rendered entirely via next-frame prediction. By Decart.
- [Project Genie (Genie 3)](https://deepmind.google/models/genie/) 🔥🧪 - Google DeepMind's frontier world model: type a prompt, get an interactive, explorable 3D world generated in real time.
- [Mirage](https://www.dynamicslab.ai/) 🧪 - Real-time generative game engine by Dynamics Lab — describe what you want mid-game and the world reshapes itself while you play.
- [Muse / WHAM](https://www.microsoft.com/en-us/research/blog/introducing-muse-our-first-generative-ai-model-designed-for-gameplay-ideation/) 🧪 - Microsoft's World and Human Action Model, trained on the game Bleeding Edge, generating coherent gameplay sequences for ideation. Published in Nature.
- [WHAMM](https://www.microsoft.com/en-us/research/articles/whamm-real-time-world-modelling-of-interactive-environments/) 🧪 - Microsoft's real-time follow-up to WHAM: an interactive, playable simulation of Quake II inside a generative model.
- [GameNGen](https://gamengen.github.io/) 🧪 - The research that started the wave: a diffusion model running DOOM at 20+ FPS with no game engine. By Google Research.

## AI Agents That Play Games

Watch frontier models play — and study how they reason.

- [SIMA](https://deepmind.google/discover/blog/sima-generalist-ai-agent-for-3d-virtual-environments/) - DeepMind's generalist agent that follows natural-language instructions across many commercial 3D games, from No Man's Sky to Goat Simulator 3.
- [Claude Plays Pokémon](https://www.twitch.tv/claudeplayspokemon) 🔥 - A live benchmark-as-entertainment: Anthropic's Claude reasoning its way through Pokémon Red, one badge at a time.
- [Cradle](https://baai-agents.github.io/Cradle/) 📜 - A general computer-control agent framework that plays AAA titles like Red Dead Redemption 2 through screenshots, keyboard, and mouse alone.
- [MineDojo](https://minedojo.org/) 📜 - Open-ended agent research platform built on Minecraft, with internet-scale multimodal knowledge for training embodied agents. NeurIPS 2022 Outstanding Paper.
- [ARC Prize / ARC-AGI](https://arcprize.org/) - The puzzle benchmark that resists brute force — abstract reasoning games designed to measure genuine fluid intelligence in machines.

## Hall of Fame: Landmark Game AI

Pre-LLM classics whose AI design still defines the craft. Know your history.

- [F.E.A.R.](https://store.steampowered.com/app/21090/FEAR/) - Goal-Oriented Action Planning (GOAP) gave its soldiers squad tactics that still get cited in every game AI talk two decades later.
- [Left 4 Dead](https://store.steampowered.com/app/500/Left_4_Dead/) - The "AI Director" invented adaptive pacing: dynamically orchestrating enemies, items, and tension based on player stress.
- [Alien: Isolation](https://store.steampowered.com/app/214490/Alien_Isolation/) - A two-brain stalker AI (director + alien) that learns from your hiding habits. Still the gold standard for horror AI.
- [Middle-earth: Shadow of Mordor](https://store.steampowered.com/app/241930/Middleearth_Shadow_of_Mordor/) - The Nemesis System: procedurally generated rivals that remember, recover, and hold grudges across an entire campaign.
- [Black & White](https://en.wikipedia.org/wiki/Black_%26_White_(video_game)) - Lionhead's creature learned by reinforcement and imitation from how you treated it — in 2001.
- [No Man's Sky](https://www.nomanssky.com/) - 18 quintillion procedurally generated planets; the high-water mark of algorithmic world generation at commercial scale.

## Milestones: When AI Beat the Game

The matches that made history.

- [AlphaGo](https://deepmind.google/research/projects/alphago/) - 2016 - Defeated Go world champion Lee Sedol 4–1, a feat predicted to be a decade away. Move 37 entered legend.
- [OpenAI Five](https://openai.com/index/openai-five/) - 2019 - Beat the reigning Dota 2 world champions (OG) in a full 5v5 match.
- [AlphaStar](https://deepmind.google/discover/blog/alphastar-grandmaster-level-in-starcraft-ii-using-multi-agent-reinforcement-learning/) - 2019 - Reached Grandmaster level in StarCraft II, ranking above 99.8% of human players.
- [Pluribus](https://www.science.org/doi/10.1126/science.aay2400) - 2019 - The first AI to beat elite professionals in six-player no-limit Texas hold'em poker.
- [Gran Turismo Sophy](https://www.gran-turismo.com/us/gran-turismo-sophy/) - 2022 - Out-raced the world's best Gran Turismo drivers, then shipped inside the retail game.
- [CICERO](https://ai.meta.com/research/cicero/) - 2022 - Meta's agent achieved human-level play in Diplomacy by negotiating with humans in natural language — and not getting caught.

## Building Games with AI

### Games Built Entirely by AI

Complete, playable games where an AI agent did the engineering — planning, coding, testing, and shipping.

- [Red Alert 2: Web Edition](https://sanwan.ai/articles/red-alert-fable.html) 🔥🆓 - A browser-playable real-time strategy homage to Red Alert 2, autonomously planned, built, tested (145 tests), and deployed end-to-end by Claude Fable 5 with no human intervention — [play it in your browser](https://peaceful-wave-530.fly.dev/).

### AI Game Creation Platforms

From prompt to playable.

- [Rosebud AI](https://rosebud.ai/) 🔥 - Vibe-code complete 2D/3D games from text descriptions; an AI assistant generates the code, assets, and logic.
- [Websim](https://websim.com/) 🆓 - Hallucinate entire interactive websites and browser games from a prompt; a playground for generative interactive media.
- [Ludo.ai](https://ludo.ai/) - AI research and ideation copilot for game studios: concept generation, market analysis, and trend tracking.
- [Unity AI](https://unity.com/products/ai) - Unity's integrated AI suite: in-editor assistants, generative texturing/animation, and on-device model inference via Sentis.
- [Roblox Cube & Studio AI](https://create.roblox.com/) - Generative 3D creation inside the world's largest UGC game platform, including text-to-3D-model.

### NPC & Dialogue Middleware

Plug living characters into your engine.

- [Inworld AI](https://inworld.ai/) - The most widely adopted character engine: personalities, goals, memory, and sub-200 ms voice for real-time NPCs.
- [Convai](https://convai.com/) - Conversational AI characters with spatial awareness and actions, with Unity, Unreal, and WebGL plugins.
- [NVIDIA ACE](https://developer.nvidia.com/ace) - Digital-human microservices for games: speech, face animation, and on-device small language models for NPCs.
- [Charisma.ai](https://charisma.ai/) - Story-first interactive character platform powering narrative experiences for entertainment IPs.

### Asset Generation

Art, models, voices, and music at the speed of iteration.

- [Scenario](https://www.scenario.com/) - Train custom generative models on your own art style for consistent, production-ready game assets.
- [Layer AI](https://layer.ai/) - AI asset pipeline for professional game studios with style-locked generation at scale.
- [Meshy](https://www.meshy.ai/) - Text-to-3D and image-to-3D model generation with PBR textures, rigging, and animation.
- [Tripo](https://www.tripo3d.ai/) - Fast, high-fidelity 3D asset generation from text or images.
- [ElevenLabs](https://elevenlabs.io/) - Industry-leading AI voice synthesis and real-time conversational voice for game characters.
- [Suno](https://suno.com/) - Generative music creation — adaptive scores and theme songs from a text prompt.

## Open Source Projects

Build your own AI game. 📜

- [Generative Agents](https://github.com/joonspk-research/generative_agents) - Stanford's "Smallville": the seminal codebase for believable LLM agents with memory, reflection, and planning.
- [AI Town](https://github.com/a16z-infra/ai-town) - MIT-licensed starter kit for hosting your own AI agent village (JavaScript/Convex).
- [Voyager](https://github.com/MineDojo/Voyager) - LLM-powered embodied agent for open-ended skill discovery in Minecraft.
- [Mindcraft](https://github.com/kolbytn/mindcraft) - Crafting LLM-driven Minecraft bots that build, fight, and collaborate via natural language.
- [SerpentAI](https://github.com/SerpentAI/SerpentAI) - Framework for turning any game into an experimentation sandbox for machine learning agents.
- [Griptape of Halt / TextWorld](https://github.com/microsoft/TextWorld) - Microsoft's learning environment for training RL agents on text-based games.
- [PettingZoo](https://github.com/Farama-Foundation/PettingZoo) - Standard API for multi-agent reinforcement learning environments, including classic and Atari games.
- [Godot LLM](https://github.com/Adriankhl/godot-llm) - Run local LLMs (text, embeddings, multimodal) directly inside the Godot engine.

## Research & Papers

The science behind playable AI.

- [Genie 3: A New Frontier for World Models](https://deepmind.google/discover/blog/genie-3-a-new-frontier-for-world-models/) - DeepMind, 2025 - Real-time interactive 3D world generation from text at 24 FPS.
- [Diffusion Models Are Real-Time Game Engines](https://arxiv.org/abs/2408.14837) - Google, 2024 - GameNGen: running DOOM entirely inside a diffusion model.
- [World and Human Action Models towards Gameplay Ideation](https://www.nature.com/articles/s41586-025-08600-3) - Microsoft, Nature 2025 - The WHAM/Muse paper.
- [Generative Agents: Interactive Simulacra of Human Behavior](https://arxiv.org/abs/2304.03442) - Stanford/Google, 2023 - The Smallville paper that launched a thousand agent sims.
- [Voyager: An Open-Ended Embodied Agent with LLMs](https://arxiv.org/abs/2305.16291) - NVIDIA et al., 2023 - Lifelong skill learning in Minecraft.
- [Human-Level Play in Diplomacy by Combining Language Models with Strategic Reasoning](https://www.science.org/doi/10.1126/science.ade9097) - Meta, Science 2022 - CICERO.
- [Outracing Champion Gran Turismo Drivers with Deep RL](https://www.nature.com/articles/s41586-021-04357-7) - Sony AI, Nature 2022 - GT Sophy.
- [Grandmaster Level in StarCraft II Using Multi-Agent RL](https://www.nature.com/articles/s41586-019-1724-z) - DeepMind, Nature 2019 - AlphaStar.

## Communities & Resources

- [AI and Games](https://www.aiandgames.com/) - The long-running YouTube channel and newsletter by Dr. Tommy Thompson on AI in game development.
- [Game AI Pro](http://www.gameaipro.com/) - Free professional book series on game AI techniques, from pathfinding to planners.
- [r/aigamedev](https://www.reddit.com/r/aigamedev/) - Reddit community for developers building games with generative AI.
- [machinations.io Blog](https://machinations.io/blog) - Game systems design and AI-assisted balancing.
- [IEEE Conference on Games](https://ieee-cog.org/) - The premier academic conference on AI and games.
- [Steam — AI Disclosure Games](https://store.steampowered.com/search/?tags=-1&category1=998) - Steam now requires AI usage disclosure; thousands of titles document how they use it.

## Contributing

Contributions are welcome and appreciated! Found a hot new AI game or tool? Please read the [contribution guidelines](CONTRIBUTING.md) first, then open a pull request.

Quality bar: entries must be **playable or usable today** (or a public research demo), **actively maintained**, and use AI as a **core feature** — not marketing garnish.

## License

Released under the [MIT License](LICENSE).
