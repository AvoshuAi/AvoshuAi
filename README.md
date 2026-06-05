<!-- Intro  -->
<div align="center">
<pre>
    ___  ___  ________          ___       __   _______   ___          ________   ________     
   |\  \|\  \|\   __  \        |\  \     |\  \|\  ___ \ |\  \        |\   ___  \|\   ____\    
   \ \  \ \  \ \  \|\  \       \ \  \    \ \  \ \   __/|\ \  \       \ \  \\ \  \ \  \___|    
 __ \ \  \ \  \ \   __  \       \ \  \  __\ \  \ \  \_|/_\ \  \       \ \  \\ \  \ \  \  ___  
|\  \\_\  \ \  \ \  \ \  \       \ \  \|\__\_\  \ \  \_|\ \ \  \       \ \  \\ \  \ \  \|\  \ 
\ \________\ \__\ \__\ \__\       \ \____________\ \_______\ \__\       \ \__\\ \__\ \_______\
 \|________|\|__|\|__|\|__|        \|____________|\|_______|\|__|        \|__| \|__|\|_______|
</pre>
</div>

<div align="center">

[![Website](https://shieldcn.dev/badge/website-jiaweing.com-black.png?logo=googlechrome)](https://jiaweing.com) [![Email](https://shieldcn.dev/badge/email-hey@jiaweing.com-blue.png?logo=gmail)](mailto:hey@jiaweing.com) [![GitHub Followers](https://shieldcn.dev/github/followers/jiaweing.png?logo=github)](https://github.com/jiaweing) [![GitHub Stars](https://www.shieldcn.dev/github/user-stars/jiaweing.svg?variant=secondary&size=sm)](https://github.com/jiaweing?tab=repositories) ![Made in Singapore](https://shieldcn.dev/badge/made%20in-Singapore-red.png)
</div>

<details>
<summary>Source Code</summary>

```python
from typing import List, Dict, Tuple


class jiaweing:
    """
    software engineer · designer · founder
    creating unique and original digital experiences
    """

    def __init__(self):
        self.name      = "Jia Wei Ng"
        self.alias     = "Jay"
        self.age       = 26
        self.location  = "Singapore"
        self.website   = "https://jiaweing.com"
        self.education = "BSc Computing Science · SIT + University of Glasgow"
        self.stack     = ["TypeScript", "Rust", "Python", ".NET", "Next.js", "Tauri", "React Native", "Postgres", "SQLite"]

    @property
    def bio(self) -> str:
        return (
            "just an ordinary guy building software.\n"
            "a designer and software engineer crafting unique, and original digital experiences.\n"
            "drawn to psychology, space, quantum mechanics, and the strange phenomena that shape the universe."
        )

    @property
    def achievements(self) -> List[str]:
        return [
            "Google APAC Solution Challenge 2025 — Top 10",
            "Dell InnovateFest 2025 — Finalist",
            "Dell Cloud Native Awards — 1st Place (x2)",
            "built titan.tf at 15 — 460k+ players, 20k+ Steam members",
            "founded 18 startups, shipped 17 apps",
            "top 25% Unsplash contributor — 460k+ views, 4.3k+ downloads",
            "87+ blog posts published",
        ]

    @property
    def setup(self) -> Dict[str, object]:
        return {
            "workstation": {
                "processor": "i7-14700KF",
                "gpu"      : "RTX 4070 Ti SUPER",
                "ram"      : "32GB DDR5",
            },
            "laptop"     : "MacBook Air M2 Midnight",
            "peripherals": [
                "Yunzii AL75 Keyboard",
                "AULA F75 Pro",
                "Shure SM7B + Focusrite Scarlett 2i2",
                "Fujifilm X-T50 + Sigma 18-50mm f2.8",
            ],
        }

    @property
    def contact(self) -> Tuple[str, str, str, str, str]:
        github   = "github.com/jiaweing"
        linkedin = "linkedin.com/in/jiaweing"
        twitter  = "x.com/jiaweihq"
        youtube  = "youtube.com/@jiaweihq"
        email    = "hey@jiaweing.com"

        return github, linkedin, twitter, youtube, email


jay = jiaweing()
```

</details>

## Current Projects

### AI & Memory

* 🌐 **[layer0](https://github.com/amajorai/layer0)** - self-hosted AI memory and RAG layer with local LLM support, vector embeddings, knowledge graph, and hybrid search

### Desktop

* 🎭 **[backstage](https://github.com/amajorai/backstage)** - open-source YouTube thumbnail studio with AI background removal and Gemini image generation
* ⛩️ **[torii](https://github.com/amajorai/torii)** - production-ready Tauri v2 + React 19 desktop app shell with licensing, analytics, auto-updates, and secure storage baked in

### Skills

* 🌼 **[amajor.md](https://github.com/amajorai/amajor.md)** - master skill directory. one install, discover every A Major skill. built for agents to find the right tool for any task.
* 👻 **[spec.md](https://github.com/amajorai/spec.md)** - spec-driven development. break any task into atomic, agent-ready github issues. the first step before shipping.
* 📦 **[ship.md](https://github.com/amajorai/ship.md)** - a thin, structured workflow for shipping features. simple, minimal, lean. one interview, one plan, ship the thing.
* 🪅 **[vibe.md](https://github.com/amajorai/vibe.md)** - spin up a 24/7 production-ready full-stack dev and deploy environment. one interview, one clean pass.
* 🎉 **[party.md](https://github.com/amajorai/party.md)** - GitHub Projects as the interface. drop in issues, it ships them while you sleep.
* 🎬 **[replay.md](https://github.com/amajorai/replay.md)** - record a live video of your running app and share the link, straight from chat.
* 🔎 **[fix.md](https://github.com/amajorai/fix.md)** - systematic bug-fixing. explore first, instrument strategically, read the logs, fix surgically, verify clean.
* 🧪 **[sandbox.md](https://github.com/amajorai/sandbox.md)** - self-hosted cloud sandbox environment. choose daytona, docker+bun, or firecracker. spawn isolated exec sandboxes or long-lived dev workspaces from chat.
* 📋 **[context.md](https://github.com/amajorai/context.md)** - write and maintain claude.md and agents.md for any workspace. explores the codebase, interviews for gaps, gives every agent full orientation in one read.
* ⚡ **[skills](https://github.com/amajorai/skills)** - 30+ smaller skills for the things developers overlook when shipping. edge cases, E2E, auth, payments, SEO, CI, and more.

### Web & UI

* 📥 **[dropdrawer](https://github.com/jiaweing/DropDrawer)** (201 stars) - responsive shadcn/ui dropdown-to-drawer component
* 📂 **[portfolio-dex](https://github.com/jiaweing/portfolio-dex)** (5 stars) - personal portfolio site
* 🪟 **[ui](https://github.com/jiaweing/ui)** - beautifully designed components inspired by iOS 26 and macOS 26, built on shadcn/ui

### Browser Extensions & Tools

* 🔲 **[altq-qr-reader-extension](https://github.com/jiaweing/altq-qr-reader-extension)** (7 stars) - offline browser extension for reading QR codes directly from web pages
* 🖼️ **[Unsplash-Multiple-Download](https://github.com/jiaweing/Unsplash-Multiple-Download)** (12 stars) - instantly download all images on a page on Unsplash
* 🗑️ **[YouTube-Playlist-Delete-Video](https://github.com/jiaweing/YouTube-Playlist-Delete-Video)** - Stylus style that restores double-click to remove videos from YouTube playlists
* 🔍 **[center-google-search](https://github.com/jiaweing/center-google-search)** - Stylus style for centered Google search results

## Legacy Work

### AI & Agents

* 🌎 **[lemon8-travel-research-agent](https://github.com/jiaweing/lemon8-travel-research-agent)** (7 stars) - multi-agent system that scrapes Lemon8 and generates comprehensive travel guides
* 🤖 **[GeminiTelegramBot](https://github.com/jiaweing/GeminiTelegramBot)** (5 stars) - Telegram bot powered by Gemini 2.0 Flash for natural conversations and AI image generation
* 🛩️ **[copilot-chat-api](https://github.com/jiaweing/copilot-chat-api)** (6 stars) - OpenAI-compatible HTTP API interface for GitHub Copilot with native GitHub authentication
* 🌙 **[updatenight-agent](https://github.com/jiaweing/updatenight-agent)** - automated Update Night newsletter generation using crewAI agents
* 🏨 **[agoda-agent](https://github.com/jiaweing/agoda-agent)** - multi-agent system that analyzes Agoda hotel listings and generates accommodation guides
* 🔍 **[localRAG-api](https://github.com/jiaweing/localRAG-api)** (3 stars) - local RAG API, superseded by layer0
* 🤖 **[localLLM-api](https://github.com/jiaweing/localLLM-api)** - local LLM API, superseded by layer0
### APIs & Boilerplates

* 🔐 **[dotnet8-jwt-api-boilerplate](https://github.com/jiaweing/dotnet8-jwt-api-boilerplate)** - barebones .NET 8 API with JWT auth and MySQL, zero abstractions, full control
* ✅ **[verify.supply.tf](https://github.com/jiaweing/verify.supply.tf)** - blockchain-based verification system for product authenticity and ownership tracking

### Web & Projects

* 🏢 **[base7-landing](https://github.com/jiaweing/base7-landing)** - landing page for Base7
* ✏️ **[telequill](https://github.com/jiaweing/telequill)** - transform public Telegram channels into elegant blog-style websites

## Skills & Technologies

![TypeScript](https://www.shieldcn.dev/badge/-TypeScript-3178C6.svg?logo=typescript&variant=branded&size=sm) ![Python](https://www.shieldcn.dev/badge/-Python-3776AB.svg?logo=python&variant=branded&size=sm) ![JavaScript](https://www.shieldcn.dev/badge/-JavaScript-F7DF1E.svg?logo=javascript&variant=branded&size=sm) ![Radix UI](https://www.shieldcn.dev/badge/-Radix_UI-000000.svg?logo=radixui&variant=branded&size=sm) ![Next.js](https://www.shieldcn.dev/badge/-Next.js-000000.svg?logo=nextdotjs&variant=branded&size=sm) ![React](https://www.shieldcn.dev/badge/-React-61DAFB.svg?logo=react&variant=branded&size=sm) ![ESLint](https://www.shieldcn.dev/badge/-ESLint-4B32C3.svg?logo=eslint&variant=branded&size=sm) ![Tailwind CSS](https://www.shieldcn.dev/badge/-Tailwind_CSS-06B6D4.svg?logo=tailwindcss&variant=branded&size=sm) ![TanStack Query](https://www.shieldcn.dev/badge/-TanStack_Query-FF4154.svg?logo=reactquery&variant=branded&size=sm) ![Zod](https://www.shieldcn.dev/badge/-Zod-3E67B1.svg?logo=zod&variant=branded&size=sm) ![Biome](https://www.shieldcn.dev/badge/-Biome-60A5FA.svg?logo=biome&variant=branded&size=sm) ![Husky](https://www.shieldcn.dev/badge/-Husky-3B82F6.svg?logo=husky&variant=branded&size=sm)

## Connect

[![X](https://shieldcn.dev/badge/X-jiaweihq-black.png?logo=x)](https://x.com/jiaweihq) [![LinkedIn](https://shieldcn.dev/badge/LinkedIn-jiaweing-0A66C2.png?logo=linkedin)](https://linkedin.com/in/jiaweing) [![Instagram](https://shieldcn.dev/badge/Instagram-jiaweihq-E4405F.png?logo=instagram)](https://instagram.com/jiaweihq) [![Threads](https://shieldcn.dev/badge/Threads-jiaweihq-black.png?logo=threads)](https://threads.net/@jiaweihq) [![TikTok](https://shieldcn.dev/badge/TikTok-jiaweihq-black.png?logo=tiktok)](https://tiktok.com/@jiaweihq) [![YouTube Subscribers](https://shieldcn.dev/youtube/subscribers/UCOReq1qWCsrNRvlq8S1n57Q.svg?variant=branded)](https://youtube.com/@jiaweihq) [![YouTube Channel Views](https://shieldcn.dev/youtube/channel-views/UCOReq1qWCsrNRvlq8S1n57Q.svg?variant=secondary)](https://youtube.com/@jiaweihq) [![Twitch](https://shieldcn.dev/badge/Twitch-jiaweihq-9146FF.png?logo=twitch)](https://twitch.tv/jiaweihq) [![Kick](https://shieldcn.dev/badge/Kick-jiaweing-53FC18.png?logo=kick)](https://kick.com/jiaweing)

## 🌙 Update Night

An AI-native media platform and catalog for builders. Newsletter, Telegram, Discord, podcast, and a curated catalog of AI and dev tools — covering what's shipping in the AI and developer ecosystem before it hits the headlines.

[![Update Night](https://shieldcn.dev/badge/Update%20Night-subscribe-orange.png?variant=secondary&logo=substack)](https://updatenight.com) [![Podcast](https://shieldcn.dev/badge/Podcast-listen-1DB954.png?logo=spotify)](https://open.spotify.com/show/4ynkzghYMkJDlw9lMxEdfy)
