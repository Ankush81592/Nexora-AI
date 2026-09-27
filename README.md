# NEXORA AI — "One AI. Every Task."

**NEXORA AI** is a next-generation AI super-app platform combining conversational intelligence, deep research, coding studio, website builder, document intelligence, presentation maker, creative studios, and automation agents into a single operating system.

---

## 🌟 Key Capabilities & Studios

1. **Core AI Chat**
   - 9 specialized operational modes: *Smart*, *Deep Research*, *Coding*, *Writing*, *Study*, *Creative*, *Business*, *Image*, *Video*.
   - Multimodal file uploads: PDF, DOCX, XLSX, CSV, images, and raw code.
   - Conversation management: Search, favorite, rename, delete, and export (Markdown, JSON, TXT).
   - "Explain like I'm a beginner" toggle for intuitive conceptual analogies.
   - Text-to-speech audio reader and browser speech recognition.

2. **AI Image Studio & Editor**
   - High-fidelity visual synthesis with aspect ratio (`1:1`, `16:9`, `9:16`, `4:3`, `3:4`) and resolution controls (`512px` to `4K`).
   - 12 artistic style presets: Realistic, Cinematic, Anime, 3D, Product Photography, Architecture, Cyberpunk, etc.
   - Natural language image editor with an interactive Before / After split comparison slider.

3. **Text-to-Video & Image-to-Video Studio**
   - Cinematic advertisement, reel, and explainer scenes generator.
   - Dynamic camera motion controls (Dramatic Zoom In, Slow Pan, Orbit 360, Crane Shot, Dolly Track).
   - Video player with interactive timeline scrub, scene storyboard keyframes, synced subtitles, and download.

4. **AI Voice Studio**
   - Real-time conversational voice assistant with pulsating visualizer.
   - Neural Text-to-Speech across 5 personas (Kore, Puck, Charon, Zephyr, Fenrir) and 7 global languages.
   - Real-time speech-to-text dictation and voice notes archive.

5. **Document AI & PDF Utilities**
   - Ingests PDF, Word (DOCX), and Excel spreadsheets.
   - Executive summaries, key insights extraction, and table parsers.
   - Semantic Q&A directly against attached documents.

6. **AI Coding Studio & Sandbox**
   - Multi-file in-browser IDE (`index.html`, `styles.css`, `app.js`).
   - Live sandboxed runnable preview in isolated iframe.
   - Integrated terminal emulator for simulated shell commands (`npm test`, `git status`).
   - AI code generation, bug fixing, and performance optimization.

7. **AI Website Builder**
   - Generates full single-page responsive websites from plain text prompts.
   - Responsive viewport preview switcher: Desktop (100%), Tablet (768px), and Mobile (375px).
   - Conversational AI tweaking: "Change primary color to emerald", "Add pricing table", "Add FAQ section".
   - One-click production HTML bundle download.

8. **AI Presentation Maker**
   - Synthesizes keynote decks with slide titles, structured bullet points, highlight metrics, and speaker notes.
   - Theme styling: Cyberpunk, Corporate Navy, Minimal Light, Emerald Luxury, and Sunset Glow.
   - Fullscreen slideshow presenter and exportable HTML keynote file.

9. **Career & Resume Studio**
   - ATS resume audit score meter with strength & weakness diagnostics.
   - Job description keyword gap matcher.
   - Custom tailored cover letter generator.
   - Interactive AI mock interview simulator with real-time feedback.

10. **AI Study Assistant**
    - Step-by-step topic explainer with "Beginner Simplifier" mode.
    - Interactive multiple-choice quizzes with instant grading and explanations.
    - Active recall 3D flip flashcards with progress tracking.
    - High-yield exam revision cheat sheets.

11. **AI Data Analysis**
    - CSV & spreadsheet parser with schema quality check and missing value detection.
    - Interactive SVG bar charts and trend visualization.
    - Natural language data querying ("Show monthly sales", "Detect unusual anomalies").

12. **Deep Research Engine**
    - Multi-stage investigation pipeline: Query crawling -> Claim reading -> Fact vs Opinion synthesis.
    - Grounded primary source citations with credibility badges.
    - Exportable strategic research dossiers.

13. **Automation Multi-Step Agents**
    - Goal decomposition pipeline: **Planning -> Researching -> Processing -> Creating -> Completed**.
    - Live sub-task execution logs and downloadable deliverables (e.g. CSV spreadsheets, audit checklists).

14. **Workspace Projects & Admin Telemetry**
    - Group assets inside isolated workspaces (*OmniAI Startup Launch*, *CyberStore UI*).
    - Admin panel with real-time API latency monitoring, provider status checks, user directory, and generation logs.

15. **Landing Page & Navigation**
    - Hero showcase ("One AI. Every Task.") with interactive playground previews.
    - Global Cmd+K / Ctrl+K Command Palette quick launcher.
    - Membership pricing tiers (Free, Pro, Creator, Business) with monthly/annual discount toggle.

---

## 🏗️ Architecture

- **Frontend**: React 19, TypeScript, Tailwind CSS, Lucide Icons, Motion.
- **Backend**: Node.js + Express with server-side `@google/genai` SDK (`gemini-3.8-flash`).
- **Telemetry & Security**: Strictly server-side API key handling, User-Agent header `'aistudio-build'` telemetry, rate limiting, and zero-leakage client architecture.
- **Demo Mode**: Built-in instant fallback engine ensuring 100% operational functionality with or without external API keys.

---

## 🚀 Setup & Running

```bash
# 1. Install dependencies
npm install

# 2. Configure environment (optional, demo mode works out-of-the-box)
cp .env.example .env

# 3. Start development server on port 3000
npm run dev

# 4. Compile & build production bundle
npm run build
```
