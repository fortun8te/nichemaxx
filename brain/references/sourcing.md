# SOURCING TOOLKIT

The practical everything-you-need-to-make-work guide. Every tool, every link, every decision tree for creating videos in this aesthetic. Copy this directly into your production workflow.

---

## EDITING APPS

### Mobile
- **CapCut** (free, limited pro features)
  - Best for: Beat sync, template + adjustment workflow
  - Built-in transitions, effects, text
  - Music library (be careful of copyright — use Epidemic Sound or Uppbeat through CapCut)
  - Strength: Speed, ease of export
  - Weakness: Limited color grading, motion blur less refined

- **Alight Motion** (free, $30+ pro)
  - Best for: Blend modes, masking, effect layering
  - Strength: Advanced blending (Screen, Overlay, Multiply, Add) for LUT application and grain
  - Weakness: Slower than CapCut, steeper learning curve, less intuitive beat sync

### Desktop
- **DaVinci Resolve** (free, Studio version $295 one-time)
  - Best for: Color grading (the entire foundation of your aesthetic)
  - The tool used by professional colorists; this is where LUTs are applied properly
  - Free version has: Color page, editing, audio, basic effects
  - Studio has: Fusion (motion graphics), Fairlight (audio), advanced plugins
  - Essential for: Navy/stone palette perfection, film grain addition, final color pass
  - Strength: Industry standard, free version is robust
  - Workflow: Edit in Premiere, color grade in DaVinci

- **Premiere Pro** ($20/month Creative Cloud)
  - Best for: Timeline editing, organization, efficiency
  - Strength: Fast, intuitive, integrates with After Effects
  - Weakness: Color grading not as deep as DaVinci (that's fine, move to DaVinci for grading)
  - Workflow: Build the timeline here, export sequence to DaVinci for grading

---

## LUTs (Free)

These three LUT packs are the foundation of your color work. LUTs are lookup tables — mathematical transformations that adjust color. Download all three; you'll layer and blend them.

### Juan Melara — Kodak 2383/2393
- **URL:** demystify-color.com (search "Kodak LUTs")
- **What:** Archival film stock emulation (Kodak 35mm cinema film)
- **Why:** The starting point for your navy + warm aesthetic
- **How to Use in DaVinci:**
  - Color page → Generator (create blank node)
  - Drag LUT onto the node
  - Adjust in Curve Editor after application
  - Blend at 70-80% intensity (not full strength)

### IWLTBAP 99+ LUT Pack
- **URL:** luts.iwltbap.com
- **What:** Cinematic LUT collection (infrared, surrealist, vintage grades)
- **Why:** The deepest palette of options; includes cool/warm shift, saturation tones
- **Best in Set:** "Infrared No. 4" (cools down highlights), "Analog Warmth" (adds vintage feel)
- **How to Use:** Start with Kodak, then add IWLTBAP selectively (30-50% blend)

### CinematicX 30 Free LUTs
- **URL:** theresolve.store (search "CinematicX")
- **What:** Cinematic color grades in 30-LUT collection
- **Why:** Emergency backup; useful when other LUTs don't fit the mood
- **Best in Set:** The "Noir" range (deep shadows), "Film Stock" (warm archival)
- **How to Use:** Use sparingly; these are more pronounced than Kodak/IWLTBAP

---

## FILM GRAIN

Film grain is mandatory. Digital video looks too clean for your aesthetic. Grain is texture, not flaw.

### GrainX 4K Plates
- **URL:** theresolve.store (search "GrainX")
- **What:** Actual 4K film grain overlays (16:9 and square, multiple grain sizes)
- **Price:** Free with free account; pro version $15-30
- **How to Use in DaVinci:**
  - Import grain plate as video layer
  - Position above your graded footage
  - Blend mode: Screen or Overlay
  - Opacity: 20-30% (subtle, not visible)
  - The grain is now part of your image, not an effect
  - Advantage: Real grain texture, not synthetic

### DaVinci Built-In Film Grain
- **Location:** Color page → Effects → Texture → Film Grain
- **How to Use:**
  - Shadows: Increase grain (60-80%)
  - Highlights: Reduce grain (20-30%)
  - This creates realistic grain distribution (shadows are grainier in real film)
  - Adjust intensity to taste (usually 30-50%)
- **Advantage:** No additional files to import; integrated into the color pipeline

**Combined Approach (Professional):**
1. Color grade your footage (apply LUTs, adjust curves, nail the palette)
2. Add DaVinci Film Grain (shadows heavier)
3. Layer GrainX plate on top at 20-30% Overlay blend
4. This creates deep, dimensional grain that reads as intentional

---

## FONTS

All available on Google Fonts (free). Download and install locally for TikTok text overlays.

### Cormorant Garamond
- **Google Fonts:** fonts.google.com/specimen/Cormorant+Garamond
- **Why:** Old-money serif, razor-thin, elegant without being precious
- **Best for:** Titles, archival text, elegant typography
- **Usage:** 48-72pt for titles; thin weight for elegance

### IM Fell English
- **Google Fonts:** fonts.google.com/specimen/IM+Fell+English
- **Why:** Aged, antiquarian, looks like a historical document
- **Best for:** When you want "old"
- **Usage:** 36-60pt; pair with Cormorant for hierarchy

### Cinzel
- **Google Fonts:** fonts.google.com/specimen/Cinzel
- **Why:** Dark, Roman-inspired, architectural
- **Best for:** Bold statements, architecture sequences, title cards
- **Usage:** 48-80pt; Bold weight

### Bodoni Moda
- **Google Fonts:** fonts.google.com/specimen/Bodoni+Moda
- **Why:** High-fashion, high-contrast, sophisticated
- **Best for:** Luxury positioning, editorial feel
- **Usage:** 40-72pt; works best in high-contrast scenarios

### Brat Font Specification
- **Base:** Arial Narrow (system font on all devices)
- **Weight:** Regular (400)
- **Tracking:** Tight (90-95% of default spacing)
- **Blur:** 5-7px Gaussian blur in Photoshop/CapCut/Alight Motion
- **Size:** 5-8px for body text (small, hard to read intentionally)
- **Color:** #8ACE00 (acid green) on dark backgrounds only
- **Transform:** Lowercase, no caps
- **DPI:** 150dpi (higher resolution = softer blur when rasterized)

**How to Apply Brat Font in CapCut:**
1. Add text layer with Arial Narrow, lowercase
2. Set font size to 5-8px
3. In effects, apply Gaussian blur (5-7px)
4. Color: #8ACE00
5. Opacity: 100% (the blur already softens)
6. Position: Random placement, overlapping, sometimes cut off by frame edge

---

## TRANSITIONS

Use sparingly. The primary transition is the hard cut.

### Hard Cut on Beat (PRIMARY)
- **When to Use:** 90% of transitions; this is your default
- **How:** Cut exactly on a drum hit, bass drop, or vocal accent
- **Why:** Synchronization signals to the viewer that the cuts are *intentional*, not random
- **Beat Sync in CapCut/DaVinci:** Enable beat detection; cuts automatically align if you mark in-and-out points correctly

### Match Cut (SIGNATURE TECHNIQUE)
- **What:** Cut from one shape/color/motion to a *similar* element in the next shot
- **Example:** Eye close-up → archway (same shape, dark background)
- **Example:** Fabric folds → stone texture (similar geometry, similar light)
- **Why:** Creates flow without explicit transition; the viewer's eye follows naturally
- **Best for:** Connecting thematic or visual elements across different moments
- **Frequency:** 2-3 per 60-second video (high value, don't overuse)

### Slow Dissolve (12-20 frames / 0.5-0.8 seconds)
- **When to Use:** Between thematically connected moments, especially during music shifts
- **Why:** Slower than hard cut; signals contemplation or transition between states
- **Example:** A hand release → fade to black → new scene
- **Frequency:** 1-2 per video (transition markers, not default)

### Zoom into Shadow
- **Technique:** Slowly push/zoom into the darkest part of the frame, then cut to next scene
- **Duration:** 1-2 seconds of zoom before cut
- **Why:** Creates mystery, visual continuation, ties scenes together
- **Best for:** Ending a scene with danger, leading into something unknown
- **Frequency:** 1 per video (special effect, not default)

---

## ASPECT RATIO

### 2.35:1 Letterbox Within 9:16

This is the single clearest cinematic signal on TikTok.

**Technical Specs:**
- Video dimensions: 1080 x 1920 (9:16, vertical)
- Content area: 1080 x ~460 (2.35:1 letterbox centered)
- Black bars: Top and bottom, approximately 730px each
- The content never uses the full frame; the black bars frame the content

**How to Apply in CapCut:**
1. Start with 9:16 vertical canvas (default for TikTok)
2. Import horizontal footage (or reframe your vertical)
3. Add black bars top and bottom using rectangles or frame effects
4. Ensure the black bars are pure black (#000000)
5. Content area: centered, 1080px wide, approximately 460px tall

**How to Apply in DaVinci:**
1. Project settings: 1080 x 1920 (9:16)
2. Timeline: drag horizontal footage in
3. Inspector → Position/Scale: resize to 2.35:1 aspect
4. Add black solid above and below
5. Align to center

**Why It Works:**
- Black bars = instant cinema signal
- The viewer recognizes the format before they recognize the content
- 2.35:1 is the aspect ratio of cinema, not TV
- On a vertical platform, it's radical (everyone else is full-frame)

**Color Critical:**
- The black must be pure black (#000000), not dark grey
- If you use dark navy in the bars, it reads as content, not frame
- The bars must be symmetrical (same height top and bottom)

---

## EDITING CHECKLIST

Before exporting, verify:

- [ ] **Aspect Ratio:** 2.35:1 letterbox, black bars perfectly symmetrical
- [ ] **Duration:** 6-15 seconds (TikTok optimal range)
- [ ] **Cuts on Beat:** Every hard cut lands on music
- [ ] **Fade to Black:** Ending fades to black over 1-2 seconds, never hard stops
- [ ] **Color Grading:** Consistent palette across all clips (one LUT + adjustments)
- [ ] **Film Grain:** Added and blended appropriately
- [ ] **Text:** If present, is it *intentionally* wrong? (Blurred, small, wrong font, disappears fast)
- [ ] **No Fast Cuts:** Average clip duration 8-12 seconds (not 1-2 seconds)
- [ ] **Sound Sync:** Every clip aligns with music intention (still = silence; movement = sound)
- [ ] **Export Settings:** 1080 x 1920, H.264, 60fps (or 24fps for cinematic feel)

---

## ARCHIVAL SOURCES

All free, legally available, no copyright issues.

### Prelinger Archives
- **URL:** archive.org/details/prelinger
- **What:** 17,000+ public domain films, 1920s-1980s
- **Best for:** Architecture, cities, nature, people (period-accurate, real light, real film grain)
- **Search Strategy:** "1960s city," "brutalism," "European street," "industrial building"
- **Download:** Each video has a download option (varies by film, usually MP4)
- **Quality:** Varies, but often 480p-720p (grain is part of the charm)
- **Right to Use:** All Prelinger films are public domain (verify individual film's license)

### LIFE Photo Archive
- **URL:** images.google.com/search?tbm=isch&q=LIFE+magazine+archive (or go directly to gettyimages.com/photos/life-magazine)
- **What:** Millions of photos from LIFE magazine, 1930s-present
- **Best for:** Historical fashion, interiors, faces, moments
- **License:** Getty Images handles rights; individual images vary (some free, some paid)
- **Workflow:** Screenshot directly; use as color reference, not direct footage
- **Value:** Real light, real people, real fashion from specific eras

### Pexels / Mixkit
- **URL:** pexels.com / mixkit.co
- **What:** Free stock video and photos (Creative Commons or similar)
- **Best for:** Modern footage (city, landscapes, architecture) when Prelinger isn't era-specific enough
- **License:** Free to use, no attribution required
- **Advantage:** Modern quality, can be color-graded down to look older
- **Disadvantage:** Sometimes too clean; often needs heavy grain and LUT to fit the aesthetic

### Free Public Domain Film Search
- **URL:** archive.org (search "[subject] 1960s film")
- **Bonus:** Many educational films from the 1950s-1980s are public domain and have *amazing* lighting

---

## CREATORS TO STUDY

Study these creators — not to copy, but to understand how they solve problems you're solving.

| Creator | Handle | Why | What to Learn |
|---------|--------|-----|----------------|
| **Sam Youkilis** | @sam.youkilis | The euro summer template | iPhone, 10-second takes, ordinary over iconic, stillness |
| **Wisdom Kaye** | @wisdmkaye | Concept-first styling | Fashion as short film, narrative through clothing, minimal motion |
| **@theaestheticmediator** | @theaestheticmediator | Underground curation | Silence as editorial statement, community over algorithm |
| **@hausofdarkwah** | @hausofdarkwah | Androgynous fashion | Making construction visible, defying gender through silhouette |
| **@architecturehunter** | @architecturehunter | Architecture as emotional | Emotion of space, not documentation, scale and proportion |
| **Matthieu Venot** | @matthieuvenot | Radical cropping | Abstraction inside architecture, geometry, compression |
| **fakemink** | @fakemink (music/aesthetic) | Dirty luxury, archive | Deep-fried nostalgia, archive streetwear, cloud rap sonics |
| **LAUZZA** | @lauzza (director) | DIY-but-deliberate | Chaotic energy that is architected, not accidental direction |

**What to Extract from Each:**
1. **Screenshot every post** — study the color grade, the crop, the clip duration
2. **Listen to the music** — note the BPM, the instruments, the production style
3. **Time the cuts** — how long does each clip hold? When do they cut?
4. **Read the caption** — if there is one, what does it say? Is it text in the video or caption text?
5. **Note the aspect ratio** — are they using 2.35:1? Full frame? Cropped?

**Building Your Reference Folder:**
- Organize by aesthetic code (ENIGMA folder, LYNCH folder, etc.)
- Inside each, organize by creator
- Screenshot every post that fits, at full resolution
- Build a color palette folder (just the color grading, extracted as stills)
- Build a transitions folder (clipped examples of match cuts, fades, hard cuts)

---

## THE RICK RUBIN RULE (For Every Single Video)

> Film what you cannot stop noticing. Remove everything that wasn't already there. Trust the silence. Make it for yourself. Release it without checking.

**The Questions to Ask of Every Cut:**

1. **If I remove this clip, does the work stop being itself?**
   - If no: remove it
   - If yes: keep it

2. **If I remove this sound, does the work stop being itself?**
   - If the clip works in silence: remove the sound
   - If the sound is doing essential work: keep it

3. **If I remove this text, does the work stop being itself?**
   - Text should be exceptional, never default
   - If it's explanatory: remove it
   - If it's wrong/broken/mysterious: keep it

4. **Would I post this if I knew nobody else would ever see it?**
   - If no: it's a guess about someone else's taste
   - If yes: it's your taste, which is the only one that matters

---

## TROUBLESHOOTING COLOR GRADING

### Problem: Navy is turning blue
- **Cause:** LUT is shifting hue, not just saturation
- **Solution:** In DaVinci Color page, use Curves tool to isolate blue channel; pull down slightly
- **Alternative:** Blend the LUT at 50% instead of full strength

### Problem: Skin tones are blowing out too much
- **Cause:** Overexposure is intentional, but it's reading as digital noise
- **Solution:** Add grain to the highlights (DaVinci Film Grain → increase shadow grain, reduce highlight grain to 10-20%)
- **Alternative:** Use Curves to lift shadows only, let highlights stay blown

### Problem: The blacks are too gray
- **Cause:** LUT is reducing contrast
- **Solution:** In Curves, add a point at the bottom-left, pull slightly down (increases black point)
- **Alternative:** Use a second, darker LUT on a separate node, blend at 30%

### Problem: Stone color is turning yellow
- **Cause:** Tungsten white balance is too warm
- **Solution:** In Curves, slightly boost blue in midtones while keeping blacks cool
- **Alternative:** Choose a different LUT (IWLTBAP has cooler options)

---

## EXPORT SETTINGS

### For TikTok
- **Resolution:** 1080 x 1920 (9:16)
- **Frame Rate:** 24fps (cinematic) or 30fps (clean)
- **Codec:** H.264
- **Bitrate:** 8-12 Mbps (higher is better; TikTok re-encodes anyway)
- **Color Space:** Rec. 709
- **Audio:** 48kHz, stereo, -3dB to -6dB normalized

### For Upload to Portfolio / Archive
- **Resolution:** 1920 x 3840 (same ratio, 2x resolution) or 4K if you want future-proof
- **Frame Rate:** 24fps
- **Codec:** ProRes 422 HQ (preserves quality for future re-editing)
- **Bitrate:** N/A (ProRes uses frame-based compression)

---

## FINAL CHECKLIST BEFORE POSTING

- [ ] Video is between 6-15 seconds
- [ ] Aspect ratio is 2.35:1 letterbox with pure black bars
- [ ] All cuts are on beat
- [ ] Color grade is consistent (single LUT + adjustments)
- [ ] Film grain is subtle but present (20-30% opacity)
- [ ] No text OR text is intentionally broken
- [ ] Ending fades to black (no hard stop)
- [ ] No watermarks (your aesthetic doesn't need them)
- [ ] Sound is mixed to -6dB, no clipping
- [ ] Video is exported at correct settings for TikTok
- [ ] You would post this even if nobody would see it

If all boxes are checked: post it without overthinking.
