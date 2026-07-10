## Joaquin Alvarez

Self-taught engineer from Paraguay. Went from zero to the only frontend engineer at a YC startup in seven months. Now building real-time AI for learning languages, solo, end to end.

### Currently building [Talkeo](https://talkeo.ai)

Open-source, real-time AI for learning languages: a voice tutor you actually talk to, live subtitles, in-place translation, and a native macOS app. I build every layer myself:

- Real-time voice pipeline at **sub-900ms** voice-to-voice (WebRTC/LiveKit, STT, multi-provider LLM, TTS), with live language switching
- Multi-provider routing with automatic fallback and no vendor lock-in, at about 1.5 cents per minute of conversation
- Python/FastAPI backend deployed to AWS from scratch (ECS Fargate, Terraform, GitHub OIDC)
- Native macOS clients in Swift/SwiftUI: system audio capture, live subtitles, and real-time voice translation
- Trained the custom bilingual voices myself

### Before

Sole frontend engineer at **Notte (YC S25)**. Owned the entire product frontend (Console: 310K+ LOC, 47 pages, 600+ commits) and contributed across the stack in Python/FastAPI.

### How I work

AI-native: I architect the system and direct coding agents across the whole stack, which is how one person ships full products fast. Relentless about latency and cost. If a faster or cheaper way exists, I'll find it.

**Stack:** TypeScript · Next.js · React · Python · FastAPI · LiveKit/WebRTC · AWS · PostgreSQL · Swift

[joaquin-avf.dev](https://joaquin-avf.dev)
