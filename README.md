# BlahBlahBlah

**Claude's last long response, compressed into an emoji-tagged list you can scan in five
seconds.**

[![Download the skill](https://img.shields.io/badge/Download%20the%20skill-BlahBlahBlah%2Eskill-2ea44f?style=for-the-badge)](https://github.com/idea2go2go/blahblahblah-skill/raw/main/BlahBlahBlah.skill)

---

**When Claude tediously BlahBlahBlahs at you, just BlahBlahBlah right back.** Easy to remember,
and emotionally satisfying!

Claude wrote you six paragraphs. You need the three things in it that actually matter. Reply
**blah blah blah** and you get them — ten minutes of tedious reading turned into one glance:

```
❓ Postgres or SQLite for the cache layer?
⚠️ Rate limiter untested past 500 req/s
🔒 Old session tokens still valid until Friday
✅ Migrated auth module to the new session store
📄 migration-notes.md
➡️ Run the load test before merging
```

No preamble, no "here's a quick summary," no closing paragraph. Just the list.

## Say it however it comes out

The phrase means nothing else in any other context, so Claude never mistakes it for ordinary
chatter — and you never have to remember exact phrasing. Spaced or unspaced, any capitalization,
punctuation entirely up to your mood. `blah blah blah`, `blahblahblah`, and `BLAHBLAHBLAH!!` all
work.

## What it pulls out

Five recurring kinds of line cover almost every long response, ordered so that what blocks
you comes first:

| | |
|---|---|
| ❓ | **Needs your input** — a decision or open question left for you |
| ⚠️ | **Heads up** — a caveat, risk, limitation, or something that didn't go to plan |
| ✅ | **Done** — an action that was completed |
| 📄 | **Produced** — a file or artifact created |
| ➡️ | **Suggested next** — what's recommended from here |

Empty categories are omitted rather than padded — most digests use two or three of the five.
When a line's real character isn't one of these, it takes its own glyph: 🔒 for a security
concern, 💰 for cost, 🐛 for a bug, ⏳ for something pending, 🚫 for something blocked. Sparingly,
so the unfamiliar glyph keeps the attention it earns.

## Install

**Claude desktop app / Cowork**

[**Download BlahBlahBlah.skill**](https://github.com/idea2go2go/blahblahblah-skill/raw/main/BlahBlahBlah.skill), then either double-click it, or
open Claude → **Settings → Skills** and upload the file.

**Claude Code**

```
/plugin marketplace add idea2go2go/blahblahblah-skill
/plugin install blahblahblah@blahblahblah
```

Then `/reload-plugins`. The first command registers the catalog; the second installs.

## It handles the awkward cases

- **Asked twice in a row?** It skips past its own previous digest and summarizes the last
  substantive response instead — summarizing a summary produces nothing new.
- **First message of a brand-new chat?** You almost certainly meant your *last* conversation,
  so it goes and finds that one, and tells you which one it used.
- **The original was already short?** It says so in one line rather than manufacturing five
  bullets out of three sentences.

## License

This skill is prose only, licensed **CC BY 4.0** — see [LICENSE](LICENSE). © 2026 Paul Hess.
