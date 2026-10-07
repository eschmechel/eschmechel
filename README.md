<a href="https://eschmechel.dev"><img src="assets/header.svg" alt="eschmechel — Elliott Schmechel, systems-focused builder. eschmechel.dev" width="100%"></a>

### `[1] whoami`

I ship end to end across Go, C++, TypeScript and Python, from GPU training infrastructure and
self-training AI agents to real-time apps at the edge.

Most recently: an on-device lip-reading pipeline at StormHacks, a loop that turns an agent's
repeated work into small fine-tuned specialists, and a summer as a Technical Content Engineer at
LicenseSpring writing SDK samples and developer education. Final-year CS at Langara. Daily driver: Arch.

```text
now
  building   the Langara CS Club website redesign
  building   a universal post-secondary Discord bot
  studying   final year of CS at Langara
```

### `[2] projects`

- **[heard](https://github.com/LMSAIH/stormhacks2026)** `StormHacks 2026 · team of 4`  
  Silent-speech app: reads your lips from a webcam and speaks for you. I built the on-device lip-reading pipeline (Auto-AVSR → ONNX, int8, 775 MB → 203 MB, in the browser) and the FastAPI GPU inference service on RunPod. · [devpost](https://devpost.com/software/heard-37hzow)

- **[hermes-apprentice](https://github.com/eschmechel/hermes-apprentice)** `winner · Hermes Agent Challenge`  
  A second learning loop for Hermes Agent: distills its recurring work into 18 MB QLoRA specialists on vLLM (~38 ms p50 local vs multi-second API calls), each gated by a held-out F1 test and a canary ramp. · [writeup](https://eschmechel.dev/blog/skills-are-prompts-heres-how-hermes-apprentice-turns-them-into-weights) · [devpost](https://devpost.com/software/hermes-apprentice)

- **[learnlm](https://github.com/LMSAIH/xhacks2026)** `Best Use of SFUCoursesAPI · XHacks 2026`  
  AI tutoring for SFU students. I built the Cloudflare Workers backend: a Vectorize RAG pipeline over 998 courses, voice tutoring over Durable Objects, and an MCP server with 21 tools. · [devpost](https://devpost.com/software/learn-lm)

- **[dataforall](https://github.com/LMSAIH/htc2026)** `HTC 2026 · infrastructure lead`  
  Distributed GPU training platform: Kubernetes backend, H100s provisioned via the Lambda Labs API, and worker lifecycle management that reclaims idle GPU spend. · [devpost](https://devpost.com/software/data-for-all)

- **[beepd](https://github.com/eschmechel/beepd)** `Lone Wanderer Award · JourneyHacks 2026 · solo`  
  Privacy-first friend radar, solo-built in 12 hours on Hono + D1 with geospatial queries and auto-expiring locations. · [devpost](https://devpost.com/software/beepd)

- **[mapd](https://github.com/LMSAIH/StormHacks2025)** `1st · StormHacks 2025 · Best Design`  
  Urban development intelligence for Vancouver: drop a pin and get a plain-language brief on how a project affects its neighbourhood. · [devpost](https://devpost.com/software/mapd-urban-development-intelligence)

### `[3] resume`

```text
2026 –       Vice President           Langara Computer Science Club
2026         Technical Content Eng.   LicenseSpring (summer)
2026         Volunteer                Web Summit Vancouver
2025 –       Fullstack dev (vol.)     United Nations Association — Vancouver
2025 – 2026  Founding member & dev    Student Software Association
2024 – 2025  Game tester              Riot Games
2024 –       CS, Associate of Sci.    Langara College · grad May 2027
```

Full history on [eschmechel.dev/resume](https://eschmechel.dev/resume) · [PDF](https://eschmechel.dev/Elliott-Schmechel-Resume.pdf)

### `[4] blog`

- [Protect Yourself, Mesh Yourself](https://eschmechel.dev/blog/protect-yourself-mesh-yourself) <sub>· Jul 2026</sub>
- [The most useful tool in my dev setup is a password manager](https://eschmechel.dev/blog/the-most-useful-tool-in-my-dev-setup-is-a-password-manager) <sub>· Jul 2026</sub>
- [Your AI slop bores me](https://eschmechel.dev/blog/your-ai-slop-bores-me) <sub>· Jun 2026</sub>
- [Skills are Prompts. Here's how Hermes Apprentice turns them into weights](https://eschmechel.dev/blog/skills-are-prompts-heres-how-hermes-apprentice-turns-them-into-weights) <sub>· May 2026</sub>

### `[5] ~/`

```text
languages   Go · C++ · Python · TypeScript · SQL · Bash
backend     Hono · FastAPI · Next.js · Drizzle · PostgreSQL
infra       Docker · Kubernetes · Proxmox · Firecracker · Cloudflare Workers/D1 · GitHub Actions
ml / ai     LoRA fine-tuning (Unsloth) · local LLMs · MCP servers · RAG (Vectorize)
homelab     3 Proxmox nodes, live status on eschmechel.dev/~
```

<sub>[eschmechel.dev](https://eschmechel.dev) · [email](mailto:elliottschmechel@gmail.com) · [linkedin](https://linkedin.com/in/eschmechel) · [dev.to](https://dev.to/eschmechel)</sub>

```text
       _                        /\=/\
      (_)                      (=o.o=)
     /|_|\___________________  /     \
      | |                    \|_______|
     _| |_                    (o)   (o)
  ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
```
