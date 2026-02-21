# [TRACK_TITLE] — Suno-Ready Version (v4.5)

**Version Note:** This file uses BRACKET annotations `[like this]` instead of parentheses for delivery cues. v4.5 interprets parentheses as ad-libs/backing vocals and will SING them. Use this file for v4.5 generation.

**See also:** `[Track_Name]_Suno_Ready.md` for v5 formatting

---

## Style Prompt (copy to Style field)

```
[GENRE_TAGS], [PRODUCTION_TAGS], [MOOD_1], [MOOD_2], [INSTRUMENTATION], [VOCAL_STYLE], [STRUCTURE_TAG], BPM: [XX]
```

## Alternate Style Prompt ([VARIATION])
```
[ALTERNATE_PROMPT]
```

---

## Slider Recommendations (v4.5)

| Slider | Setting | Rationale |
|--------|---------|-----------|
| **Weirdness** | [X]% | [RATIONALE — v4.5 often benefits from slightly higher weirdness] |
| **Style Influence** | [X]% | [RATIONALE — v4.5 may need lower style influence for creative freedom] |

---

## Lyrics (copy to Lyrics field)

```
[Intro] [PRODUCTION_CUE: description, X bars]

[Verse 1] [PRODUCTION_CUE: arrangement] [delivery cue in brackets]
[LYRIC_LINE]
[LYRIC_LINE]
[LYRIC_LINE]
[LYRIC_LINE]

[delivery shift cue in brackets]
[LYRIC_LINE]
[LYRIC_LINE]
[LYRIC_LINE]
[LYRIC_LINE]

[Chorus] [PRODUCTION_CUE: instrumentation change] [delivery cue]
[LYRIC_LINE]
[LYRIC_LINE]
[LYRIC_LINE]
[LYRIC_LINE]

[Verse 2] [PRODUCTION_CUE: arrangement] [delivery cue]
[LYRIC_LINE]
[LYRIC_LINE]
[LYRIC_LINE]
[LYRIC_LINE]

[delivery shift cue]
[LYRIC_LINE]
[LYRIC_LINE]
[LYRIC_LINE]
[LYRIC_LINE]

[Chorus] [PRODUCTION_CUE: repeat or variation] [delivery cue]
[LYRIC_LINE]
[LYRIC_LINE]
[LYRIC_LINE]
[LYRIC_LINE]

[Bridge] [PRODUCTION_CUE: stripped/shifted] [delivery change cue]
[LYRIC_LINE]
[LYRIC_LINE]
[LYRIC_LINE]
[LYRIC_LINE]

[Final Chorus] [PRODUCTION_CUE: full intensity] [peak delivery cue]
[LYRIC_LINE]
[LYRIC_LINE]
[LYRIC_LINE]
[LYRIC_LINE]

[Outro] [PRODUCTION_CUE: resolution] [final delivery cue]
[LYRIC_LINE]
[LYRIC_LINE]
[End]
```

---

## Runtime Target

**Target:** [X:XX-X:XX] at [BPM] BPM

---

## v4.5 Generation Notes

### Why v4.5 for This Track
- [REASON_1 — e.g., "Need rawer emotional delivery"]
- [REASON_2 — e.g., "Want more adventurous interpretation"]
- [REASON_3 — e.g., "Track benefits from slight imperfection"]

### v4.5 Strengths to Leverage
- More emotional, human-feeling vocal delivery
- Better lyric-to-rhythm adaptation
- More imaginative with genre fusion
- Better for desperate, cracking, strained vocals
- More "surprised" results when prompts are vague

### v4.5 Considerations
- Negative prompts less reliable (~70% vs v5's ~90%)
- May have slight "shimmer" artifacts in mix
- Less precise prompt adherence
- Consider generating both v5 and v4.5, compare results

### Annotation Reminder
All delivery cues use `[brackets]` — they will NOT be sung:
- `[whispered]` — direction, not sung
- `[building intensity]` — direction, not sung
- `[spoken, raw]` — direction, not sung

If you WANT actual backing vocals or ad-libs, use `(parentheses)` intentionally:
- `(ooh, yeah)` — WILL be sung as ad-lib
- `(background harmonies)` — WILL be sung

---

## When to Use v4.5 vs v5

| Use v4.5 When... | Use v5 When... |
|------------------|----------------|
| Need raw emotional vocal | Need clean precision |
| Want unpredictable interpretation | Want strict prompt adherence |
| Cracking/desperate delivery | Controlled, clinical delivery |
| Experimental genre fusion | Mainstream, polished sound |
| Longer tracks (5-8 min) | Shorter, tight arrangements |

### Hybrid Approach
Consider generating both and mixing stems:
1. Generate with v5 for clean instrumental
2. Generate with v4.5 for raw vocal
3. Combine stems in DAW

---

## Quick Reference

| Field | Value |
|-------|-------|
| BPM | [XX] |
| Key | [KEY] (optional) |
| Version | v4.5 |
| Weirdness | [X]% |
| Style Influence | [X]% |
| Runtime | [X:XX-X:XX] |

---

*Design doc: `[Track_Name]_Design.md`*
*v5 version: `[Track_Name]_Suno_Ready.md`*
