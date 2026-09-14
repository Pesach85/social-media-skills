# Hub integration (do not dump this pack into .cursor/skills)

This clone is a **vendor module** for ollama-kb-market-engine.

## Voice SoT (mandatory)

All drafting must read hub brand voice only:

- `config/brand_voice/about-me.md`
- `config/brand_voice/voice.md`

Do **not** write `about-me.md` / `voice.md` into this vendor tree.
Do **not** auto-publish Meta/TikTok.

Adapter: `src.agents.cross_agent_media.draft_release_posts`
Fork: https://github.com/Pesach85/social-media-skills
