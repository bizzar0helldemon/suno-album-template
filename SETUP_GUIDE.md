# Suno Album Template - Setup Guide

## Quick Start

### Step 1: Copy the Template Folder
Rename `suno-album-template` to your project name (e.g., `MyNewAlbum`).

### Step 2: Customize CLAUDE.md (5-10 minutes)
Open `CLAUDE.md` and replace all `[PLACEHOLDER]` values:
- `[ARTIST_NAME]` → Your artist/band name
- `[ALBUM_TITLE]` → Album title
- `[TRACK_COUNT]` → Number of tracks
- Set your genre tags, sonic DNA, and vocalists

### Step 3: Customize PROJECT_VISION.md (15-30 minutes)
Define your creative direction:
- Thematic territory and core themes
- Sonic palette and tag libraries
- Vocalist profiles
- What to avoid

### Step 4: Initialize ALBUM_BIBLE.md (10 minutes per track)
Create blank worksheets for each planned track, or start with titles and add details as you develop.

### Step 5: Customize AUDIT_CHECKLIST.md (5 minutes)
Adjust target ranges based on your track count and add genre-specific checks.

### Step 6: Start Developing Tracks
1. Copy track templates from `docs/Tracks/_TRACK_TEMPLATE/`
2. Rename to your track name (e.g., `My_Song_Design.md`)
3. Follow the workflow in CLAUDE.md

---

## Variable Track Count Guide

The template supports different album sizes. Adjust audit thresholds accordingly:

### EP (5-7 tracks)
- Audit thresholds: Lower sensitivity
  - "More than 2 tracks" = potential repetition concern
  - "More than 1 track" = potential vocal concentration
- Sequencing: Opener → 3-5 body tracks → Closer
- Each track carries significant weight in the arc
- Consider: Tighter thematic focus, less variety needed

### Standard LP (10-14 tracks)
- Audit thresholds: Default template settings work well
  - "More than 4 tracks" = repetition concern
  - "More than 3 tracks" = vocal/structural concentration
- Room for 2-3 distinct movements or thematic clusters
- One clear "single" + deeper album tracks
- Standard verse-chorus structures can dominate

### Double Album / Extended (18+ tracks)
- Audit thresholds: Higher tolerance for repetition
  - "More than 6 tracks" = repetition concern
  - Consider disc/side breaks in sequencing
- Multiple potential singles across the runtime
- More room for experimental deep cuts
- Interstitials/interludes become useful for pacing

---

## Placeholder Reference

Find and replace these placeholders across all documents:

### Project Identity

| Placeholder | Replace With | Example |
|-------------|--------------|---------|
| `[ARTIST_NAME]` | Your artist or band name | "Yesterday's Weekend" |
| `[ALBUM_TITLE]` | Album title | "Neon Decay" |
| `[TRACK_COUNT]` | Number of tracks planned | "12" |
| `[VERSION]` | Suno version (v5 or v4.5) | "v5 Pro" |
| `[SUNO_SUBSCRIPTION]` | Your Suno subscription tier | "Suno v5 Pro AI" or "Suno v5 Premier AI" |
| `[CREATOR_NAME]` | Your name for credits | "S. Ralph Harrow" |

### Sonic Identity

| Placeholder | Replace With | Example |
|-------------|--------------|---------|
| `[GENRE_DESCRIPTION]` | Primary genre(s) | "industrial/darkwave" |
| `[ERA_DESCRIPTION]` | Sonic era reference | "Late 80s analog grit" |
| `[GENRE_TAG_1]` through `[GENRE_TAG_5]` | Core genre tags | "industrial, darkwave, goth synth" |
| `[PRODUCTION_TAG_1]` through `[PRODUCTION_TAG_5]` | Era/production tags | "analog synths, tape saturation" |
| `[MOOD_TAG_1]` through `[MOOD_TAG_8]` | Atmosphere tags | "paranoid, claustrophobic, dread" |
| `[INSTRUMENT_1]` through `[INSTRUMENT_4]` | Key instruments | "808 drums, synth bass, strings" |
| `[STRUCTURE_1]` through `[STRUCTURE_4]` | Structure approaches | "building, looping, no resolution" |

### Creative Direction

| Placeholder | Replace With | Example |
|-------------|--------------|---------|
| `[PROJECT_GOAL]` | What you're trying to achieve | "Cohesive album that sounds like one session" |
| `[DESIRED_LISTENER_RESPONSE]` | Target experience | "Unsettled, uncomfortable, hypnotized" |
| `[NARRATOR_VOICE_DESCRIPTION]` | How narrator sounds/feels | "Despondent, worn down, not angry" |
| `[IMAGERY_KEYWORDS]` | Recurring visual/sensory | "oil, machinery, wet surfaces, heat" |
| `[CONTENT_GUIDELINES]` | Tone/content approach | "Keep erotica charged but ambiguous" |

### Thematic Elements

| Placeholder | Replace With | Example |
|-------------|--------------|---------|
| `[THEME_1]` through `[THEME_4]` | Core album themes | "Paranoia", "Corporate control", "Shame" |
| `[EXCLUSION_1]` through `[EXCLUSION_3]` | Themes to avoid | "Redemption", "Hope", "Happy endings" |
| `[IMAGE_CATEGORY_1]` through `[IMAGE_CATEGORY_4]` | Imagery banks | "Mechanical/industrial", "Body/skin" |

### Vocalists

| Placeholder | Replace With | Example |
|-------------|--------------|---------|
| `[PRIMARY_VOCALIST_NAME]` | Lead vocalist identifier | "Male Lead" |
| `[VOCALIST_1_DESCRIPTION]` | Voice characteristics | "Baritone, can be clean/distorted/whispered" |
| `[SECONDARY_VOCALIST_NAME]` | Featured vocalist (if any) | "Ana-Mai" |
| `[VOCALIST_2_DESCRIPTION]` | Secondary voice traits | "Smoky, haunting, detached female vocals" |

### Avoidance Lists

| Placeholder | Replace With | Example |
|-------------|--------------|---------|
| `[AVOID_1]` through `[AVOID_3]` | What NOT to do | "Pop structure", "Major key", "Uplifting" |
| `[AVOID_TAG_1]` through `[AVOID_TAG_3]` | Sonic elements to exclude | "happy, bright, commercial pop" |

### Track-Level

| Placeholder | Replace With | Example |
|-------------|--------------|---------|
| `[TRACK_TITLE]` | Track name | "Trust Thrust" |
| `[TRACK_TYPE]` | Song category | "Industrial rock single" |
| `[BPM]` | Tempo | "118" |
| `[RUNTIME]` | Target length | "3:15-3:45" |

### Release Credits

| Placeholder | Replace With | Example |
|-------------|--------------|---------|
| `[SUNO_SUBSCRIPTION]` | Your Suno tier for credits | "Suno v5 Pro AI" or "Suno v5 Premier AI" |
| `[CREATOR_NAME]` | Your name for credits | "S. Ralph Harrow" |
| `[ARTWORK_CREDIT]` | Album artwork credit | "HarrowVision" |
| `[MASTERING_CREDIT]` | Mastering credit (or N/A) | "N/A" |
| `[DEDICATION]` | Album dedication (optional) | "For Earl" |
| `[YEAR]` | Release year | "2026" |
| `[ALBUM_LINK]` | Streaming/purchase link | "https://..." |
| `[SOCIAL_LINKS]` | Social media handles | "@yesterdaysweekend" |

**Standard Credit Format:**
```
Music composed and generated using [SUNO_SUBSCRIPTION]
Lyrics, concept, and production direction by [CREATOR_NAME]
```

---

## Genre-Specific Considerations

### Industrial / Darkwave / Goth
**Sonic DNA examples:**
```
industrial, darkwave, goth synth, analog synths, 80s production, tape saturation
```

**Key considerations:**
- Emphasize: mechanical drums, analog synths, distortion, tape saturation
- Structure options: loops, no resolution, building dread, hard cuts
- Vocal range: whispered to shouted, distorted, processed
- Mood tags: paranoid, claustrophobic, dread, unsettling, menacing
- What to avoid: clean pop production, bright sounds, happy vibes

### Pop / Synth-Pop / Indie Pop
**Sonic DNA examples:**
```
synth-pop, indie pop, dream pop, 80s production, bright synths, polished
```

**Key considerations:**
- Emphasize: hooks, chorus structure, bright production, clean vocals
- Structure options: verse-chorus-verse-bridge-chorus
- Vocal range: clean, layered harmonies, intimate to powerful
- Mood tags: euphoric, nostalgic, romantic, bittersweet
- What to avoid: harsh distortion, chaotic structures, aggressive vocals

### Metal / Rock / Alternative
**Sonic DNA examples:**
```
alternative metal, hard rock, grunge, distorted guitars, live drums, aggressive
```

**Key considerations:**
- Emphasize: guitar prominence, live drums, dynamics, power
- Structure options: riff-based, breakdowns, solos, build-drop
- Vocal range: clean to aggressive, screams, harmonies
- Mood tags: intense, aggressive, raw, powerful, cathartic
- What to avoid: over-polished production, synth-heavy arrangements

### Ambient / Electronic / Experimental
**Sonic DNA examples:**
```
ambient, electronic, experimental, atmospheric, textural, soundscape
```

**Key considerations:**
- Emphasize: texture, space, minimal arrangement, evolution
- Structure options: evolving, through-composed, soundscape, non-traditional
- Vocal range: often minimal, heavily processed, spoken word
- Mood tags: ethereal, hypnotic, meditative, unsettling, vast
- What to avoid: traditional verse-chorus, prominent vocals, busy arrangements

### Hip-Hop / Trap / R&B
**Sonic DNA examples:**
```
trap, hip-hop, R&B, 808s, hi-hats, modern production, vocal-forward
```

**Key considerations:**
- Emphasize: 808s, hi-hats, rhythmic vocals, groove
- Structure options: verse-hook-verse, features, ad-libs
- Vocal range: rap, sung hooks, layered ad-libs, autotune options
- Mood tags: confident, moody, introspective, hypnotic, hard-hitting
- What to avoid: live band sounds, rock instrumentation

### Folk / Acoustic / Singer-Songwriter
**Sonic DNA examples:**
```
folk, acoustic, singer-songwriter, fingerstyle guitar, intimate, organic
```

**Key considerations:**
- Emphasize: acoustic instruments, natural sound, intimate production
- Structure options: storytelling, verse-heavy, minimal chorus
- Vocal range: intimate, vulnerable, honest, close-mic
- Mood tags: intimate, honest, melancholic, hopeful, warm
- What to avoid: heavy production, electronic elements, distortion

---

## Workflow Tips

### 1. Start with PROJECT_VISION.md
Nail your sonic DNA before writing tracks. This prevents drift and ensures cohesion across the album. Spend real time here.

### 2. Develop Tracks in Clusters
Work on thematically related tracks together:
- Maintains voice consistency
- Prevents sonic drift
- Makes connections easier to build
- Example: Write all "aggressive" tracks in one session, all "atmospheric" tracks in another

### 3. Update PROGRESS_TRACKER.md After Each Session
Prevents confusion when returning to the project:
- Note what you worked on
- Update track statuses
- Log any decisions made
- Add to "Next Actions"

### 4. Run Mini-Audits Periodically
Don't wait until all tracks are done:
- Check every 4-5 tracks for emerging patterns
- Flag potential repetition early
- Identify gaps while you still have tracks to develop
- Adjust direction if needed

### 5. Log Successes Immediately
Add to GENERATION_LOG.md right after successful Suno generation:
- Include what worked AND what didn't
- Note slider settings
- Record the exact prompt used
- This becomes invaluable reference material

### 6. Use Both v5 and v4.5
Different tracks may benefit from different versions:
- v5: Cleaner, more precise, clinical
- v4.5: Rawer, more emotional, more adventurous
- Consider generating both and comparing
- You can mix stems from different versions

### 7. Consider Studio Mode (Premier Only)
For tracks needing precise control, use Studio Mode:
- Import generated tracks, extract up to 12 stems
- Replace problem elements without affecting what works
- Build from scratch: drums → bass → synths → vocals
- Create signature stems to reuse across album for cohesion
- See `suno-studio-guide.md` for complete workflow
- **When to use:** Track is 80% right, one element is wrong; building album-wide signature sounds; need maximum control over mix

---

## Common Customization Patterns

### Adding a Third Vocalist
1. Add to `CLAUDE.md` vocalists section
2. Add to `PROJECT_VISION.md` with full vocal tags
3. Add column to `AUDIT_CHECKLIST.md` Section 6 (Vocal Approach Distribution)
4. Update track worksheet template in `ALBUM_BIBLE.md`

### Concept Album with Narrative Arc
1. Add "Story Arc" section to `ALBUM_BIBLE.md` Part 6
2. Track character appearances in worksheets
3. Add narrative coherence check to `AUDIT_CHECKLIST.md` Section 9
4. Consider adding a "Character Reference" appendix
5. Use connections section in each Track Design doc to map story beats

### Collaborative Project (Multiple Writers)
1. Add contributor credits to track worksheets
2. Note who handles which development stages
3. Consider version control (git) for the docs folder
4. Add "Author" field to track templates
5. Document style guide to maintain consistency across writers

### EP Instead of Full Album
1. Reduce `[TRACK_COUNT]` to 5-7
2. Adjust audit thresholds in `AUDIT_CHECKLIST.md`:
   - Change "more than X tracks" to lower numbers
   - Simplify variety targets
3. Simplify sequencing workspace in `ALBUM_BIBLE.md`
4. Focus on tighter thematic scope

### Instrumental Album (No Vocals)
1. Remove vocalist sections from templates
2. Adjust prompts to include "instrumental only, no vocals"
3. Replace vocal approach sections with "lead instrument" sections
4. Update audit checklist to focus on instrumental variety
5. Add sections for melodic themes/motifs instead of lyrics

---

## File Organization

### Recommended Naming Conventions

**Track files:**
```
[Track_Name]_Design.md          # Creative blueprint
[Track_Name]_Suno_Ready.md      # v5-optimized generation file
[Track_Name]_Suno_Ready_v45.md  # v4.5 variant (if needed)
[Track_Name]_Suno_Ready_SHORT.md # Shortened version (if needed)
```

**Examples:**
```
Trust_Thrust_Design.md
Trust_Thrust_Suno_Ready.md
Trust_Thrust_Suno_Ready_v45.md
```

### Folder Structure After Setup

```
YourProjectName/
├── CLAUDE.md                    # AI assistant instructions (start here)
├── SETUP_GUIDE.md              # This file (can delete after setup)
├── suno-studio-guide.md        # Studio Mode reference (Premier only)
└── docs/
    ├── PROJECT_VISION.md       # Thematic vision, sonic DNA
    ├── ALBUM_BIBLE.md          # Master track worksheets
    ├── AUDIT_CHECKLIST.md      # Pre-generation quality audit
    ├── PROGRESS_TRACKER.md     # Status dashboard
    ├── GENERATION_LOG.md       # Success pattern logging
    ├── MEMORY.md               # Working context snapshot
    ├── suno_mastery_guide.md   # Technical Suno reference (Standard Mode)
    └── Tracks/
        ├── Track_1_Design.md
        ├── Track_1_Suno_Ready.md
        ├── Track_2_Design.md
        ├── Track_2_Suno_Ready.md
        └── ...
```

---

## Ready to Start?

1. Copy this template folder
2. Rename it to your project name
3. Open `CLAUDE.md`
4. Start replacing `[PLACEHOLDERS]`
5. Define your sonic DNA in `PROJECT_VISION.md`
6. Develop your first track

Good luck with your album!

---

*Template Version: 1.0*
*Based on: FMFMFM Project Structure*
