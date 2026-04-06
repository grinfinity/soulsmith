# Data-Driven Path: Analyzing Existing Content

When the user has existing content (tweets, blog posts, essays, chat logs), analyze it BEFORE interviewing. The interview then becomes refinement, not cold start.

## Supported Data Sources

- **Social media:** Twitter/X archives (tweets.js), Bluesky, LinkedIn, Reddit history
- **Writing:** Blog posts, essays, Substack/Medium exports, newsletters
- **Messages:** Discord/Slack logs, Telegram exports
- **Notes:** Obsidian vaults, Notion exports, Roam Research
- **Transcripts:** Video/podcast transcripts, interview recordings
- **Code:** GitHub repos, Stack Overflow answers
- **Raw:** PDFs, text files, JSON exports, RSS feeds

## Expected Folder Structure

Ask the user to place content in a `data/` folder:

```
data/
├── x/           — Twitter/X archive
├── writing/     — Blog posts, essays, articles
├── messages/    — Chat logs (Discord, Telegram, Slack)
├── notes/       — Personal notes (Obsidian, Notion exports)
├── transcripts/ — Video/podcast transcripts
└── influences.md — Intellectual influences (optional)
```

## What to Extract

Read through content systematically. Look for:

**Topics & themes:** What do they write about repeatedly? What triggers their engagement?

**Opinion patterns:** What do they agree/disagree with? What makes them react? What positions do they hold consistently vs where do they shift?

**Writing patterns:**
- Sentence length (short and punchy? long and flowing? mixed?)
- Paragraph structure (one-liners? dense blocks? bullet lists?)
- Punctuation habits (em dashes? ellipses? exclamation marks?)

**Vocabulary fingerprint:**
- Words they overuse (catchphrases, verbal tics)
- Words they never use (what sounds wrong coming from them?)
- Domain jargon and how they deploy it

**Tone shifts:** How does their voice change across contexts?
- Formal writing vs casual chat
- Heated debate vs calm explanation
- Public posts vs private messages

**Rhetorical moves:**
- How they structure arguments (thesis first? build up?)
- How they handle disagreement (direct? diplomatic? sarcastic?)
- Analogy sources (what domains do they draw from?)

**Quick reactions:** How they express excitement, agreement, skepticism, confusion, frustration.

## Analysis Workflow

1. **Read the content** — Use the Read tool for local files. If the user provides a single file or a flat folder instead of the structured layout above, work with what's there. Don't inject wholesale; absorb patterns.
2. **Extract patterns** — Note the above categories as you go.
3. **Draft SOUL.md** — Worldview, opinions, influences from content patterns.
4. **Draft STYLE.md** — Voice, vocabulary, anti-patterns from writing analysis.
5. **Present drafts** — Show the user what you extracted. Ask:
   - "Does this sound like you?"
   - "What's missing? What's wrong?"
   - "What did I get right that surprised you?"
6. **Interview to fill gaps** — Worldview beliefs are rarely in tweets. Influences are rarely explicit. Character boundaries need asking. This is where the interview adds what data can't provide.
7. **Iterate** — Until the user says "yeah, that's me."

## Quality Notes

- **Quality > quantity.** 15 well-chosen samples beat 50 mediocre ones.
- **Curate for authenticity.** Content should represent their BEST and most genuine voice, not every throwaway tweet.
- **More is better up to a point.** Diminishing returns after ~100 samples. If they have thousands of tweets, sample strategically.
- **Platform diversity helps.** Twitter + long-form + DMs gives a fuller picture than just one platform.

## Output: data/_GUIDE.md

When generating the agent folder, include a `data/_GUIDE.md` explaining what the folder is for:

```markdown
# Data Directory

This folder contains raw source material. The agent browses it for grounding.

## What Goes Here
- Social media exports, blog posts, essays, chat logs
- Anything that represents the voice and positions

## How It's Used
1. **Grounding** — when asked about a topic covered in the data
2. **Tone calibration** — understanding voice in different contexts
3. **Position reference** — checking stated views on specific things

The agent browses, doesn't inject wholesale. It absorbs the vibe.
```
