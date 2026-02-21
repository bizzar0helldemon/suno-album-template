# [ARTIST_NAME] — [ALBUM_TITLE]

## Project Overview

[TRACK_COUNT]-track [GENRE_DESCRIPTION] album. Suno [VERSION] for generation.

**Sonic Reference:** [ERA_DESCRIPTION]
**Goal:** [PROJECT_GOAL]
**Listener Experience:** [DESIRED_LISTENER_RESPONSE]
**Suno Subscription:** [SUNO_SUBSCRIPTION]

*Subscription options: Suno v5 Pro AI | Suno v5 Premier AI*

## Key Documentation

| File | Purpose |
|------|---------|
| `docs/ALBUM_BIBLE.md` | Master reference — track worksheets, prompts, status, sonic DNA |
| `docs/suno_mastery_guide.md` | Suno technical guide — GMIV formula, meta tags, sliders |
| `suno-studio-guide.md` | Studio Mode (Premier) — multitrack workflow, stem generation, DAW integration |
| `docs/AUDIT_CHECKLIST.md` | Pre-generation audit — repetition, variety, gaps (run when all tracks complete) |
| `docs/PROJECT_VISION.md` | Thematic vision, vocal profiles, what to avoid |
| `docs/MEMORY.md` | Project context and working patterns |
| `docs/Tracks/[Track_Name]_*.md` | Individual track design docs and Suno-ready lyrics |

## Current Status

**Lyrics Complete ([X] tracks):**
- [List completed tracks here]

**In Progress ([Y] tracks):**
- [List tracks currently being developed]

**To Develop ([Z] tracks):**
- [List remaining tracks]

## Track Development Workflow

### 1. Concept Development
Use brainstorming approach. Ask one question at a time:
- What does the title evoke?
- Narrator's stance (predator/prey/observer/complicit)?
- Sonic approach (heavy/ambient/experimental/driving)?
- Vocal arc?
- Key imagery territories?

### 2. Lyric Writing
- Maintain [NARRATOR_VOICE_DESCRIPTION]
- Use sensory imagery: [IMAGERY_KEYWORDS]
- [CONTENT_GUIDELINES]

### 3. Design Document
Create `docs/Tracks/[Track_Name]_Design.md` with:
- Core concept and role on album
- Structure and vocal arc
- Imagery territories
- Full lyrics with section headers
- Production notes and recommended prompts
- Connections to other tracks

### 4. Suno-Ready Version
**IMPORTANT:** Before creating Suno-ready files, ALWAYS read `docs/suno_mastery_guide.md` for:
- GMIV formula (Genre, Mood, Instruments, Vocals)
- Meta tag formatting and placement
- Slider recommendations
- v5 vs v4.5 differences

Create `docs/Tracks/[Track_Name]_Suno_Ready.md` with:
- Style prompt using GMIV formula (copy/paste ready)
- Lyrics with meta tags: `[Verse 1]`, `[Chorus]`, etc.
- Parenthetical delivery cues: `(whispered, desperate)` — v5 only
- Embedded production cues: `[sparse, pulsing bass only]`
- Slider recommendations (Weirdness, Style Influence)
- BPM specification
- Runtime target

### 4b. Studio Mode Alternative (Premier Only)
For tracks requiring precise control over individual elements, use Studio Mode workflow.
**Read `suno-studio-guide.md` before using Studio Mode.**

**Two Studio Approaches:**

**Approach A: Standard → Studio Refinement**
1. Generate full track using Suno-Ready prompt
2. Import to Studio, extract stems (up to 12)
3. Mute/replace problem stems
4. Generate replacement stems with specific prompts
5. Export multitracks to DAW for finishing

**Approach B: Build-from-Stems**
1. Start with foundation (drums or uploaded reference)
2. Layer bass, synths, textures — each generated contextually
3. Add vocals last (adapts to full arrangement)
4. Use Remake/Rewrite/Extend for section editing
5. Export multitracks to DAW

**When to use Studio:**
- Track is 80% right but one element is wrong
- Building signature sounds to reuse across album
- Maximum control over individual elements needed
- Album cohesion is critical (reuse stems across tracks)

### 5. Update Album Bible
In `docs/ALBUM_BIBLE.md`:
- Update track worksheet with full details
- Update track development log
- Add to completed tracks when generated

### 6. Update All Project Documents (when track is complete)
**IMPORTANT:** When a track is fully complete (design doc + Suno-ready file created), update ALL of these:
- `CLAUDE.md` — Move track from "To Develop" to "Lyrics Complete" list
- `docs/MEMORY.md` — Update "Current state" section
- `docs/ALBUM_BIBLE.md` — Complete track worksheet, update Track Development Log
- `docs/AUDIT_CHECKLIST.md` — Add style prompt, tempo, vocal approach

### 7. Pre-Generation Audit (when all tracks complete)
**TRIGGER:** When "To Develop" list is empty and all tracks show "Lyrics Complete"

Run full audit using `docs/AUDIT_CHECKLIST.md`:
- Compare all style prompts side-by-side for variety
- Check imagery/word frequency across all lyrics
- Verify thematic and structural balance
- Identify gaps and make adjustments before generation
- Do NOT proceed to audio generation until audit is complete

## Suno Formatting Quick Reference

**Style Prompt Format:**
```
[Genre], [Production/Era], [Mood], [Instrumentation], [Vocal Style], [Structure], BPM: XX
```

**Lyric Meta Tags:**
- Section: `[Verse 1]`, `[Chorus]`, `[Bridge]`, `[Outro]`
- Production: `[sparse, industrial drums enter]`
- Delivery: see version differences below

**Album Sonic DNA (use in every prompt):**
```
[GENRE_TAG_1], [GENRE_TAG_2], [GENRE_TAG_3], [PRODUCTION_TAG_1], [PRODUCTION_TAG_2]
```

## v5 vs v4.5 Annotation Differences

**CRITICAL:** v4.5 interprets parentheses as ad-libs/backing vocals and will SING them.

| Format | v5 Behavior | v4.5 Behavior |
|--------|-------------|---------------|
| `[Brackets]` | Structure/cues — NOT sung | Structure/cues — NOT sung |
| `(Parentheses)` | Delivery cues — NOT sung | Ad-libs/backing — SUNG |
| `[*Asterisks*]` | Not needed | Workaround — NOT sung |

**Workflow:**
- Create main `_Suno_Ready.md` with parentheses (optimized for v5)
- Create `_Suno_Ready_v45.md` with brackets for delivery cues if needed
- Or use `[brackets]` for all delivery cues if targeting both versions

**When to use each version:**
- **v5:** Cleaner production, strict prompt adherence, clinical/controlled vocals
- **v4.5:** Rawer emotional delivery, more adventurous interpretation, desperate/cracking vocals

## Vocalists

**[PRIMARY_VOCALIST_NAME] (default):** [VOCALIST_1_DESCRIPTION]
**[SECONDARY_VOCALIST_NAME]:** [VOCALIST_2_DESCRIPTION]

## What to Avoid

- [AVOID_1]
- [AVOID_2]
- [AVOID_3]
- [AVOID_4]

## Session Start Checklist

1. Read this file (automatic)
2. Check `docs/ALBUM_BIBLE.md` for current status
3. If developing a track, use brainstorming approach
4. **REQUIRED before creating Suno-ready files:** Read `docs/suno_mastery_guide.md` for GMIV formula, meta tags, and slider recommendations
5. **IF using Studio Mode (Premier):** Read `suno-studio-guide.md` for multitrack workflow, stem generation, and DAW integration
6. Update Album Bible when work is complete
7. Update `docs/AUDIT_CHECKLIST.md` with new track's prompt/tempo/vocals
8. **IF all tracks complete:** Run full pre-generation audit before proceeding

## Generation Mode Decision

| Scenario | Recommended Mode |
|----------|------------------|
| First draft / rapid exploration | Standard Mode |
| Track needs one element fixed | Studio Mode |
| Building signature sound for album | Studio Mode |
| Credit efficiency is priority | Standard Mode |
| Maximum control needed | Studio Mode |
| Reusing stems across multiple tracks | Studio Mode |
