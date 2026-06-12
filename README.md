Kevin Horst
AI Implementation Engineer · Local LLM Deployment · Chrome Extensions · Private AI Tooling
I build production-ready AI tooling for privacy-sensitive environments — local LLM pipelines, browser extensions, and deployment utilities for clients who can't afford cloud AI data exposure.
Background: Hardware roots → IT support → training → instructional design → Microsoft → AI implementation  
Location: Tri-Cities, WA  
Available for: W2 contract and fractional AI implementation roles
---
How I Work
I use AI as a production tool — not just for code generation, but for structured data creation at scale. I built original multilingual datasets across 10+ writing systems (Hiragana, Katakana, Kanji, Simplified Chinese, Cyrillic, Armenian, Georgian, Ethiopic, Hebrew, Korean) through iterative prompt engineering, validation, and correction. I know where LLMs fail on non-Latin scripts, structured output, and consistency at volume — because I hit every one of those walls building these projects.
SDLC-fluent. Vibe codes effectively with Claude, Gemini, and Devin.
---
AI & Local LLM Tooling
Ai-Chat-Navigator
Chrome side-panel extension that scrapes full chat history from Claude and Gemini. Navigate to any past conversation, distill it via a tested two-tier prompt pipeline into a new chat window, and optionally deep dive the distillation. Built on Manifest V3 with multi-platform content scripts and merge-on-save caching.
LLM-Tester
Chrome extension that discovers locally running LLMs and benchmarks them against Ollama and LM Studio backends. TPS testing, RAG stress testing, model comparison, and history tracking.
tps-meter
Standalone Chrome extension for real-time tokens-per-second measurement against local LLM endpoints.
LLMParametizer (in development)
Desktop tool for authoring llama-server INI configs with built-in TPS testing, RAG evaluation, and autotuning. Exports ready-to-deploy configs for client-site model selection and tuning sessions.
---
Automation Pipelines
Online Identity Self-Check (closed source)
End-to-end lead funnel: HTML form → Google Apps Script → Brevo → personalized PDF report delivered via Gmail → next-step CTA. Sales funnel entry point for local LLM consulting at kchorst.com.
Daily Language Email Suite (closed source)
Three automated daily emails — Kanji of the Day, Phrase of the Day (7 languages), and Letter of the Day (15+ scripts) — driven by original language datasets built for Android APKs, now running as Google Sheets → Apps Script → Brevo pipelines.
---
Apps
mylangapp-web · mylangapp
Everyday vocabulary across 9 languages. Built as a React Native / Expo Android APK, then redeployed as a Vercel PWA.
kanji-web · kanji
Browse and learn Japanese Kanji with readings and examples. Android APK + Vercel PWA.
alphabets
React Native / Expo — explore 6 world writing systems.
SLPR-The-Sleep-App
Cognitive shuffle sleep aid — reads random words aloud at intervals to drift you to sleep.
---
Media & Audio Tools
youtube-movie-creator-toolkit
Python pipeline for producing and publishing travel videos to YouTube.
audio-prep-suite
Modular Python toolkit: BPM detection, key finding, silence trimming, normalization, and audio conversion.
---
Stack
Languages: Python · JavaScript · TypeScript · React Native
AI/LLM: Ollama · llama-server · llama.cpp · Qwen · Claude API · Gemini API
Chrome Extensions: Manifest V3 · content scripts · side panel · service workers · chrome.storage
Deployment: Vercel · Expo PWA · Google Apps Script · Brevo
Tools: VS Code · Continue · Cline · Git
---
📫 kchorst.com · catsoftravels@gmail.com
