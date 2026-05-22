# nichemaxx v2 — Coherence Engine Design
*2026-05-22*

## Problem

The user has taste but no pipeline. They have feelings, moods, fragments — but can't collapse them into one clear, niche-coherent creative direction. They also can't film themselves, so everything is pure mashcut (sourced footage).

The existing `/nichemaxx` skill has two structural failures:
1. **Wrong brain paths** — references files that don't exist (`music-palette.md`, `manifesto.md`, etc.) and ignores the real brain files. Falls back to generic knowledge.
2. **Expects clean input** — built for someone who knows what they want. The user doesn't always know. They have "bullshit" — vague feelings, half-formed references, a mood word.

## What the Skill Needs to Do

**Core job:** Take whatever the user brings → distill it into one niche thing → produce a brief that feels like thinking together, not filling a form.

The output is always a committed creative direction. The skill never hedges, never asks for clarification, never presents options. It picks the strongest interpretation and goes.

## Design

### 1. Brain File Fix

Update skill.md to read the actual files:
- `./brain/taste_logic.md` — manifesto, north star, grammar rules, contradiction resolutions
- `./brain/community.md` — 36-video breakdown, creator analysis, community DNA
- `./brain/icp.md` — the person: 17, European, gay/undecided, what he feels, what he saves
- `./brain/aesthetic_codes.md` — 7 aesthetic clusters with technical specs
- `./brain/references/music.md` — 13 confirmed tracks with deep analysis + secondary palette
- `./brain/references/film.md` — scene-level references with sourcing directions

If any file is missing, flag it. Never silently fall back.

### 2. Distillation Opening

Before the structured brief, two committed lines:

> **What I heard:** [honest, specific reading of the raw input — even if vague]
> **What it becomes:** [one sentence that names the concept with precision]

This is the distillation step. It takes scattered → singular. The skill commits to an interpretation here and doesn't revisit it.

### 3. Tone: Thinking Partner, Not Form

The brief feels like a smart person thinking out loud with you, not a template being filled. Specifically:
- Each cultural reference includes a *why it fits* — not just the citation
- Music recommendation includes what it does emotionally, not just BPM
- The brief has a voice. It can say "this is the right track because..." or "the danger here is..."

### 4. Anti-Pattern Line

Every brief includes one explicit failure mode:
> **What would make this basic:** [specific, concrete thing to avoid]

This is inside the brief, not a footnote. The niche is partially defined by what it isn't.

### 5. Mode Changes

**Mode 1 (`/nichemaxx [anything]`)** — primary use case
- Accepts: vague mood words, half-sentences, a feeling, a reference, a track name, "something like X but..."
- Runs distillation step first
- Commits to one direction
- Produces full brief in conversational tone

**Mode 2 (`/nichemaxx`)** — random brief
- No change from current behavior
- Must use real brain files for references

**Mode 3 (`/nichemaxx check [description]`)** — taste check  
- No change from current behavior
- Still outputs YES/MAYBE/NO + direction

## Brief Format Changes

### Remove
- Nothing structural — the format is good

### Add
- Distillation header (two lines before the brief)
- "What would make this basic" line in the brief
- "Why it fits" annotation on each cultural reference (1 sentence)
- Music: add "What it does" line (emotional effect, not technical description)

### Tone
- Convert stiff template language to thinking-partner voice
- The brief can have an opinion. It can commit. It can say "this is the one."

## What This Doesn't Cover

- Footage sourcing (not needed — the user's sourcing is their own hunt)
- Auto-download pipeline (not needed at this stage)
- Multi-platform briefs (this is TikTok/CapCut only)

## Success Criterion

User types something vague and messy → gets back a brief that feels like it was written by someone who understood them better than they understood themselves, and gives them references they wouldn't have found on their own.
