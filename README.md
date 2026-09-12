# AI Chatbot (/aicg/) Notes

Notes distilled from `/aicg/` (AI Chatbot General, 4chan `/g/`-style) —
roleplay/character-chat frontends, character-card hosting sites, and model
API references.

See [LINKS.md](LINKS.md) for the raw link list.

## A flag before the summary

This thread links a **"jailbreak listing"** (`rentry.org/jb-listing`) — a
collection of prompts designed to bypass AI providers' safety guidelines
(OpenAI's, Anthropic's, Google's, etc., including the guidelines I operate
under). I've listed that it exists in LINKS.md since it's part of the
thread, but I'm not summarizing, cataloging, or evaluating its actual
content — that would mean documenting safety-circumvention techniques,
which isn't something I'll do regardless of the request framing. Everything
else below (frontends, character-card sites, official API docs) is
genuinely neutral tooling.

## Frontends (roleplay/character chat UIs)

- **SillyTavern** — the dominant frontend in this space: a local web UI
  that connects to basically any backend (OpenAI/Claude/Gemini/local
  models/etc.) and layers character cards, world info, and chat-formatting
  features on top. If you only try one, this is it.
- **RisuAI** — an alternative frontend with its own character/bot
  ecosystem (`realm.risuai.net`) and format.
- **Agnai** — another frontend, with a separate guide rentry
  (`agnai_guides_`) for setup specifics.

## Character card sites

`chub.ai`, `realm.risuai.net`, plus several archive/mirror sites
(`char-archive.evulid.cc`, `chararc.bernkastel.pictures`,
`archive.cardbox.moe`, `botbooru.com`) host user-made character cards
(persona + world-info files) for use in the frontends above. The mirror
naming pattern (archive/cardbox/botbooru) mirrors what's seen in the
Stable Diffusion model-hosting space — these exist partly because
primary sites periodically remove content, so mirrors serve as backup
sources for cards at risk of deletion.

## Model references (legitimate API docs)

- **OpenAI**: platform.openai.com/docs
- **Claude**: docs.anthropic.com, plus a community "how2claude" rentry
- **Gemini**: ai.google.dev/docs, plus a community "gemini-qr" (quick
  reference) rentry
- **DeepSeek**: api-docs.deepseek.com
- **Grok**: docs.x.ai/overview
- **Local models**: points to `/lmg/` (see this series'
  [local-models-notes](https://github.com/abdussamikhan1999-stack/local-models-notes)
  repo), Hugging Face, and OpenRouter (a unified API/billing layer in front
  of many hosted models — useful if you want to try several providers
  through one API key rather than signing up separately with each).

## News (09/2026 model releases)

Overlaps substantially with what [local-models-notes](https://github.com/abdussamikhan1999-stack/local-models-notes)
already covers for the open-weight side (DeepSeek V4.1 Flash, GLM 5.3,
Qwen 3.8 Max, Kimi K3). The additional closed/hosted releases named here:
GPT-6 Astra (OpenAI), Gemini 3.8 Flash/Flash-Cyber (Google), Claude Fable
5.1 and Claude Opus 5 (Anthropic), Grok 4.6 (xAI). As with the other
"News" sections in this series, these are dated snapshots — check each
provider's own release notes for current status rather than trusting this
later.

## Meta / community resources

- **Lore** (`rentry.org/aicg_chronicles`) — the general's own running
  community history/lore document — a "how this community got here" doc,
  analogous to the alt.cyberpunk FAQ covered in the cyberpunk-privacy-notes
  repo, but for this specific thread's community rather than a whole genre.
- **Log reader** (`sprites.neocities.org/l/r`) — a tool for viewing/sharing
  exported chat logs from these frontends.
