# TLOU Cinema — Screenwriting Prompt for Post-Apocalyptic Stories

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![Version](https://img.shields.io/badge/version-1.2-blue.svg)
![Claude Optimized](https://img.shields.io/badge/Claude-Optimized-8A2BE2)

## 📖 About

**TLOU Cinema** is a specialized prompt for generating post-apocalyptic screenplays in the style of *The Last of Us*. It creates characters, dialogues, scenes, and plot twists while maintaining a gritty, grounded, survival-focused atmosphere.

The prompt is designed to:
- **Avoid clichés** (no "wise old mentor dies to motivate the hero")
- **Focus on survival** — no moralizing, no ideological messaging
- **Maintain consistency** — tracks characters, timeline, world rules
- **Output in Russian** (cinematic language), with English industry terms (INT./EXT.)

## 🎬 What You Can Generate

| Type | Description |
|------|-------------|
| **Synopsis** | Logline + 1-page summary from a story concept |
| **Characters** | Name, age, appearance, backstory, motivation, flaw, survival role |
| **Structure** | 3 acts with key plot points, turning points, climax |
| **Scenes** | Full screenplay format (slug line, action, dialogue) |
| **Dialogues** | Exchanges between characters about specific topics |

## 🎯 Perfect For

- Screenwriters exploring post-apocalyptic stories
- Game developers working on narrative-driven games
- Writers battling creative block
- Fans of TLOU who want to create their own stories

## 🚀 How to Use

1. **Choose your language version:**
   - [English prompt](prompts/TLOU-Cinema-V1.2-EN.md) (instructions in English, output in Russian)
   - [Русский промпт](prompts/TLOU-Cinema-V1.2-RU.md) (инструкции на русском, вывод на русском)

2. **Copy the prompt** and paste it at the beginning of your chat with Claude (Opus recommended)

3. **Add your request** inside `<user_data>` tags

4. **Get your screenplay** — the prompt handles the rest!

### Example request format:
<user_data>
Create a protagonist for a post-apocalyptic story.
Name: Korin. Age: 17. She's a scavenger who lost her brother.
</user_data>

## 📋 Prompt Structure
BLOCK 1: CONTEXT — AI screenwriter role
BLOCK 2: OBJECTIVE — 6 possible actions (synopsis, characters, scenes...)
BLOCK 9: CONSTRAINTS — hard rules (no clichés, consistency lock, tone lock)
BLOCK 7: FORMAT — exact output templates for each action
BLOCK 4: ASSUMPTIONS GUARD — model states assumptions before answering
BLOCK 3: EXAMPLES — good & bad examples with explanations
BLOCK 5: STYLE & TONE — gritty, cinematic, Russian output
BLOCK 6: PRIORITIES — safety > completeness > format compliance
BLOCK 8: SELF-CHECK — silent verification before output
BLOCK 11: MULTI-TURN — maintains consistency across conversation
BLOCK 12: VARIABLES — {{STORY_CONCEPT}}, {{CHARACTER_NAMES}}, etc.

## 📂 Examples

Check out these example outputs generated with the TLOU Cinema prompt:

- [Dialogue Example](examples/dialogue-example.md) — survivors debating a risky night crossing
- [Character Example](examples/character-example.md) — creating a lone scavenger protagonist
- [Scene Example](examples/scene-example.md) — an opening scene in an abandoned mall
- [Synopsis Example](examples/synopsis-example.md) — a full story summary about crossing a frozen lake
- [Structure Example](examples/structure-example.md) — 3-act breakdown of a sibling journey

## ⚠️ Important Notes

- **Output language:** Russian (for all generated content)
- **Industry terms:** INT./EXT., slug lines remain in English
- **Best with:** Claude Opus (strong reasoning), but works with Claude Sonnet/Haiku
- **Token budget:** ~2000 tokens for prompt + your input
- **Consistency:** The prompt maintains a running internal record of all established facts

## 📖 Behind the Scenes

Curious why I built this? Read the story here: [WHY-I-MADE-THIS.md](WHY-I-MADE-THIS.md)

## 📜 License

MIT — free to use, modify, and improve. If you create something awesome, a shoutout to **Shilov** would be appreciated!

## ⭐ Support

- **Star** this repo if you find it useful
- **Fork** to customize for your needs
- **Share** with fellow writers and developers

## 📬 Contact

- GitHub: [ren10-14](https://github.com/ren10-14)

---

**Craft your post-apocalyptic stories like a pro.** 
No clichés. Just survival.

## 🌐 Language versions

- [English](README-EN.md)
- [Русский](README-RU.md)
