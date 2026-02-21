# [TRACK_TITLE] — Suno-Ready Version (v5)

**Version:** v5 optimized (uses parentheses for delivery cues)
**See also:** `[Track_Name]_Suno_Ready_v45.md` for v4.5 formatting

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

## Slider Recommendations

| Slider | Setting | Rationale |
|--------|---------|-----------|
| **Weirdness** | [X]% | [RATIONALE] |
| **Style Influence** | [X]% | [RATIONALE] |

---

## Lyrics (copy to Lyrics field)

```
[Intro]
[PRODUCTION_CUE: description of instrumental intro, X bars]

[Verse 1]
[PRODUCTION_CUE: arrangement notes]
(delivery cue: vocal direction)
[LYRIC_LINE]
[LYRIC_LINE]
[LYRIC_LINE]
[LYRIC_LINE]

(delivery shift cue)
[LYRIC_LINE]
[LYRIC_LINE]
[LYRIC_LINE]
[LYRIC_LINE]

[Chorus]
[PRODUCTION_CUE: instrumentation change]
(delivery cue)
[LYRIC_LINE]
[LYRIC_LINE]
[LYRIC_LINE]
[LYRIC_LINE]

[Verse 2]
[PRODUCTION_CUE: arrangement notes]
(delivery cue)
[LYRIC_LINE]
[LYRIC_LINE]
[LYRIC_LINE]
[LYRIC_LINE]

(delivery shift cue)
[LYRIC_LINE]
[LYRIC_LINE]
[LYRIC_LINE]
[LYRIC_LINE]

[Chorus]
[PRODUCTION_CUE: repeat or variation]
(delivery cue)
[LYRIC_LINE]
[LYRIC_LINE]
[LYRIC_LINE]
[LYRIC_LINE]

[Bridge]
[PRODUCTION_CUE: stripped/shifted arrangement]
(delivery cue: change in vocal approach)
[LYRIC_LINE]
[LYRIC_LINE]
[LYRIC_LINE]
[LYRIC_LINE]

[Final Chorus]
[PRODUCTION_CUE: full intensity]
(delivery cue: peak intensity)
[LYRIC_LINE]
[LYRIC_LINE]
[LYRIC_LINE]
[LYRIC_LINE]

[Outro]
[PRODUCTION_CUE: resolution/continuation]
(final delivery cue)
[LYRIC_LINE]
[LYRIC_LINE]
[END_INSTRUCTION: fade/hard cut/etc.]
```

---

## Runtime Target

**Target:** [X:XX-X:XX] at [BPM] BPM

---

## Production Notes

### Key Elements to Listen For
- [ ] [ELEMENT_1]
- [ ] [ELEMENT_2]
- [ ] [ELEMENT_3]
- [ ] [ELEMENT_4]

### If Results Are Off
- **Too polished/clean:** Try v4.5 instead, or add "raw, analog" to prompt
- **Wrong energy:** Adjust BPM or mood tags
- **Vocal issues:** Check delivery cues, adjust weirdness slider
- **Missing instrument:** Specify more explicitly in prompt
- **[TRACK_SPECIFIC_ISSUE]:** [SOLUTION]

---

## v4.5 Adaptation Note

If generating with v4.5, replace all `(delivery cues)` with `[delivery cues]` to prevent them being sung as ad-libs.

**CRITICAL:** v4.5 interprets parentheses as backing vocals/ad-libs and will SING them.

Create separate `[Track_Name]_Suno_Ready_v45.md` if v4.5 is preferred for this track.

**When to use v4.5:**
- Need rawer, more emotional vocal delivery
- Want more unpredictable interpretation
- Tracks requiring desperate, cracking, strained vocals
- Experimental or genre-fusion pieces

---

## Quick Reference

| Field | Value |
|-------|-------|
| BPM | [XX] |
| Key | [KEY] (optional) |
| Version | v5 |
| Weirdness | [X]% |
| Style Influence | [X]% |
| Runtime | [X:XX-X:XX] |

---

*Design doc: `[Track_Name]_Design.md`*
*v4.5 version: `[Track_Name]_Suno_Ready_v45.md`*
