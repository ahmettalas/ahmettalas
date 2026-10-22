## Ahmet Talaş

Software Engineer working on real-time voice systems, distributed backends and LLM integrations.

I am the core engineer behind **PureEngine** at Pure Input — an AI-driven, fully automated phone survey platform that brings STT, TTS, LLM and telephony infrastructure together into a single real-time pipeline. I designed it and took it from zero to production.

### What it runs today

- **500+ concurrent calls** on a 6-server distributed architecture
- Horizontally scalable dialer/worker architecture — capacity grows linearly as workers are added
- A production race condition causing 25-30% slot over-allocation, resolved with atomic Redis + Lua operations
- 80%+ of answers resolved locally through a three-layer resolution pipeline, cutting LLM API cost
- Zero-downtime migration from Supabase to self-hosted PostgreSQL

### Working with

- **Backend** — Node.js · TypeScript · Python · Express · REST · WebSocket / SSE
- **Data & distributed** — PostgreSQL · Redis (Pub/Sub, Streams, atomic Lua) · worker architecture · circuit breaker · caching
- **Voice AI & telephony** — FreeSWITCH (ESL) · SIP / RTP · IVR · AMD · Deepgram · ElevenLabs
- **Applied AI** — OpenAI API · LLM integration · Turkish NLP · fuzzy matching
- **Infrastructure** — Linux · Nginx · PM2 · systemd · AWS S3

### On the empty repository list

Most of what I build lives in private repositories — production systems belonging to my employer. The contribution graph is a better reflection of the actual work.

Istanbul, Türkiye · [LinkedIn](https://www.linkedin.com/in/ahmettalas)
