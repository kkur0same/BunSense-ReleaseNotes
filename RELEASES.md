# Release Notes - v1.1.0

[简体中文](RELEASES_zh_CN.md) · [繁體中文](RELEASES_zh_TW.md)

## Highlights

New AI Voice (TTS) feature with multiple providers, redesigned floating bar with tooltip navigation, and improved overlay behavior.

---

## Voice (BETA)

### New
- **AI Voice** — Listen to selected Japanese text read aloud with natural AI voices
- **Providers** — OpenAI TTS, Google Gemini, and Azure Speech Service
- **Default voice** — Built-in browser speech synthesis
- **Voice settings** — Dedicated Voice section in sidebar to choose provider, voice, and model
- **Play / Pause / Resume** — Full playback control from the floating bar voice panel

---

## Floating Bar

### Redesigned
- **Tooltip navigation** — Hover over icons to see feature labels; clean icon-only look when idle
- **Persistent bar** — Floating bar stays visible while overlays (Translate, Grammar, Dictionary, Voice) or Settings are open
- **Toggle overlays** — Click a feature button again to close its overlay (consistent across all features)

### Fixes
- **No more flash** — Fixed the bar briefly flashing when closing overlays or clicking sidebar icons
- **Branding icon** — Fixed floating bar disappearing after clicking the branding icon
- **Password autofill fix** — API key inputs no longer trigger browser password manager popups on websites

---

## Overlays & UI

- **Voice panel** — Inline overlay for switching between Default / AI speech with a close button
- **Visual polish** — Improved icon sizing, spacing, padding, and overall floating bar balance

---

# Release Notes - v1.0.1

[简体中文](RELEASES_zh_CN.md) · [繁體中文](RELEASES_zh_TW.md)

## Highlights

Improvements to AI API speed, floating bar behavior, furigana robustness, and overlays.

---

## AI Chat

### Performance
- **API speed** — Faster responses from AI providers with streaming mode

### New & Updated
- **Models** — Updated to newer AI models

---

## Floating Bar & Selection

- **Japanese-only activation** — Bar shows only on Japanese text/sites; Users can also choose to enable/disable Floating Bar in Settings

---

## Furigana

### Fixes
- **Furigana showing up twice** — Fixed re-applying furigana when it was already applied
- **Toggle furigana off** — Re-select text that already has furigana and click Furigana again to remove it

### New & Updated
- **Chunk-by-sentence processing** 
- **Reading corrections** 

---

## Overlays & UI

- **Window cut off** — Fixed dictionary and other overlays being cut off at the viewport edge

---

# Release Notes - v1.0.0

## Highlights

Initial release of BunSense: a Chrome extension to learn Japanese with translation, furigana, grammar analysis, dictionary lookup, and AI-assisted chat.

---

## Translation

- **Translate** — Default translation for selected Japanese text (free tier)
- **AI Translation** — Optional: use OpenAI, DeepSeek, or Claude for translations
- **Target languages** — English, 简体中文, 繁體中文

---

## Furigana

- **In-page annotations** — Hiragana readings above kanji 
- **Customizable color** — Set furigana color in Settings
- **Furigana size** — Adjust reading size above kanji

---

## Grammar & Dictionary

- **Grammar analysis** — Analyze verb forms, parts of speech, transformations
- **JLPT grammar database** — Bundled JLPT grammar patterns with meanings
- **Key Grammar (AI)** — AI extracts key grammar points from the selected sentence
- **Dictionary lookup** — Display word definitions, readings, JLPT Level and pitch accents

---

## Floating Bar & Sidebar

- **Floating bar** — Appears on text selection: Translate, Furigana, Dictionary, Grammar, Explore Icon
- **Sidebar** — Chat, Notebook, Settings with configurable position (left/right) and panel width
- **Explore Icon** — Opens sidebar with selected text as context for AI chat

---

## AI Chat

- **Providers** — OpenAI, DeepSeek, Claude
- **Contextual prompts** — "What does this mean?", "Key grammar", "More casual", "More formal"
- **Free chat** — Ask anything about Japanese

---

## Notebook

- **Save items** — Vocabulary, grammar, or sentences from selected text
- **Sort options** — Recently Added, Reading Order, JLPT Level

---

## Settings & Localization

- **Theme color** — Accent color for floating bar and overlays
- **Furigana color** — Color for hiragana readings
- **Languages support** — English, 简体中文, 繁體中文 
