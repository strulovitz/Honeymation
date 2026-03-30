# Video 1 — Clip Generation Progress

## Settings

### Video Clips (remind Nir of these settings the FIRST time we switch to Video each session)
- **Tool:** https://openart.ai/generator/lego → switch to **Video** → select **Elements to Video**
- **Select Model:** Kling 3.0 Omni
- **Aspect Ratio:** Cinema 16:9 (for YouTube)
- **Quality Mode:** Pro (1080p)
- **Audio:** Off
- **Duration:** 5s
- **IMPORTANT:** Upload character images as **reference images** (NOT "start frame"!) — this tells the AI what the characters look like, not what the first frame should be

### Reference Images
- **Tool:** https://openart.ai/generator/lego → Image
- **Model:** ChatGPT Image 1.5
- **Proportions:** 1:1 (1024x1024)
- **Quality:** Medium
- **Number of images:** 4
- **Omni Reference:** ALWAYS upload the closest existing reference image so new variants stay visually consistent with what we already have

## Completed Clips

| # | Scene | Clip File | Status |
|---|-------|-----------|--------|
| 1 | The Hook | `scene01_hook/take01_businessman_walking.mp4` | DONE |
| 2 | The Project | `scene02_project/take01_architect_cabin_build.mp4` | DONE |
| 3a | Big AI — smiling | `scene03_big_ai_problem/take01_smiling_green_arrows.mp4` | DONE |
| 3b | Big AI — frowning | `scene03_big_ai_problem/take01_frowning_red_arrows.mp4` | DONE |
| 4a | Anonymization — before | `scene04_anonymization/take01_patients_before.mp4` | DONE |
| 4b | Anonymization — after | `scene04_anonymization/take01_blank_patients_conveyor.mp4` | DONE |
| 5a | De-anonymization | `scene05_deanonymization/take01_attacker_snaps_identities.mp4` | DONE |
| 5b | Doctor shocked | `scene05_deanonymization/take01_doctor_shocked.mp4` | DONE |
| 6 | Lightbulb idea | `scene06_lightbulb/take01_architect_idea.mp4` | DONE |
| 7a | Bad Way 1 part 1 (CrewAI) | `scene07_bad_way1_crewai/take01_head_transfer_foreman_worker.mp4` | DONE |
| 7b | Bad Way 1 part 2 (CrewAI) | - | TODO |
| 8a | Bad Way 2 part 1 (Petals/Exo) | - | TODO |
| 8b | Bad Way 2 part 2 (Petals/Exo) | - | TODO |
| 9 | Good Way (BeehiveOfAI) | - | TODO |
| 10 | Boardroom | - | TODO |
| 11 | Phone call | - | TODO |
| 12 | Thumbs up + end card | - | TODO |

## Before Scenes 7-9: New Reference Images Needed

The fairy tale trio (Bad Way 1, Bad Way 2, Good Way) requires helmet/head variants for ALL 5 crew members — not just workers. In competitor systems (CrewAI, Petals/Exo), the planning and coordination layers also block and wait, not just the execution layer. So the architect and foreman must also be shown headless (Scene 7) or with red helmets (Scene 8).

### Full Reference Image Checklist (15 images: 5 characters × 3 variants)

**GREEN helmet (for Scene 9 — BeehiveOfAI, the Good Way):**
| # | Character | Omni Reference (upload this) | Status |
|---|-----------|------------------------------|--------|
| 1 | Worker 1 (hammer) | `characters/images/03_worker1_hammer.jpg` | DONE → `33_worker1_hammer_green.jpg` |
| 2 | Worker 2 (saw) | `characters/images/04_worker2_saw.jpg` | DONE → `34_worker2_saw_green.jpg` |
| 3 | Worker 3 (axe) | `characters/images/05_worker3_axe.jpg` | DONE → `35_worker3_axe_green.jpg` |
| 4 | Foreman | `characters/images/02_foreman.jpg` | DONE → `36_foreman_green.jpg` |
| 5 | Architect | `characters/images/01_architect.jpg` | DONE → `37_architect_green.jpg` |

**RED helmet (for Scene 8 — Petals/Exo, Bad Way 2 — idle/waiting):**
| # | Character | Omni Reference (upload this) | Status |
|---|-----------|------------------------------|--------|
| 6 | Worker 1 (hammer) | `characters/images/03_worker1_hammer.jpg` | DONE → `38_worker1_hammer_red.jpg` |
| 7 | Worker 2 (saw) | `characters/images/04_worker2_saw.jpg` | DONE → `39_worker2_saw_red.jpg` |
| 8 | Worker 3 (axe) | `characters/images/05_worker3_axe.jpg` | DONE → `40_worker3_axe_red.jpg` |
| 9 | Foreman | `characters/images/02_foreman.jpg` | DONE → `41_foreman_red.jpg` |
| 10 | Architect | `characters/images/01_architect.jpg` | DONE → `42_architect_red.jpg` |

**NO HEAD — empty neck peg (for Scene 7 — CrewAI, Bad Way 1 — waiting for the shared brain):**
| # | Character | Omni Reference (upload this) | Status |
|---|-----------|------------------------------|--------|
| 11 | Worker 1 (hammer) | `characters/images/03_worker1_hammer.jpg` | DONE → `43_worker1_hammer_headless.jpg` |
| 12 | Worker 2 (saw) | `characters/images/04_worker2_saw.jpg` | DONE → `44_worker2_saw_headless.jpg` |
| 13 | Worker 3 (axe) | `characters/images/05_worker3_axe.jpg` | DONE → `45_worker3_axe_headless.jpg` |
| 14 | Foreman | `characters/images/02_foreman.jpg` | DONE → `46_foreman_headless.jpg` |
| 15 | Architect | `characters/images/01_architect.jpg` | DONE → `47_architect_headless.jpg` |

**STANDALONE HEAD with green helmet (for Scene 7 — the "brain" that gets passed between figures):**
| # | Character | Omni Reference (upload this) | Status |
|---|-----------|------------------------------|--------|
| 16 | Standalone head + green helmet | `characters/images/33_worker1_hammer_green.jpg` | DONE → `48_standalone_head_green.jpg` |

This is the "ball" that headless figures pass to each other in Scene 7 (CrewAI). Just a Lego head with green helmet, no body — shows the hollow socket underneath where it snaps onto a neck peg.

Generate all reference images first (use Image mode, not Video), then use them as elements for the video clips.

## Lessons Learned

### General
- Use **symbols not text** — AI can't render text. Use padlock/vault/shield icons instead of words
- Upload **ALL relevant character references** — don't skip any
- **Elements to Video** is better than Image to Video (reference vs starting frame)
- Results are good enough — text overlays and editing will polish them later
- **Max 7 reference images** per video generation on OpenArt

### Kling Video Prompt Rules (learned from Scene 7 trial and error)

**CRITICAL — follow these rules for ALL video prompts from now on:**

1. **NEVER say "helmet"** — Kling creates a loose helmet object. Always say "head" even though the head has a green helmet on it. The reference images already show what the head looks like.

2. **Only describe START state and END state** — Do NOT describe the mechanics of HOW things happen (no "bends down", "picks up", "places on"). Let Kling figure out the animation. Kling is creative (basketball throw!) when you let it decide HOW.

3. **Max 2 characters per clip** — Kling confuses character identities with 3+ characters. It merges traits between characters (e.g., gave foreman a hammer). Use 1 authority + 1 worker per clip. Split scenes into multiple 5-second parts.

4. **Upload BOTH states of each character** — For each character in the scene, upload the "with head" AND "without head" reference images. This is critical — Kling needs to see what each character looks like in both states. Formula: 2 images per character × 2 characters = 4, plus props.

5. **No action verbs for background elements** — Don't say "building a door" or "hammering." Background props just EXIST. Say "a door stands in a green field in the background."

6. **No timing words** — Don't say "after a few seconds" or "slowly." Just describe what happens in sequence.

7. **Keep prompts SHORT** — Fewer words = less confusion. Every extra sentence is a chance for Kling to misinterpret. The successful Scene 7 Part 1 prompt was only 6 sentences.

### Scene 7 Prompt That Worked (for reference)
```
Lego animation, 3D rendered Lego style. A wooden door frame stands alone in a green grassy field in the background. Two Lego figures stand in front of it. On the left, a hammer worker with a head. On the right, a female foreman in orange vest with no head, just an empty neck peg. The worker takes off his own head. His head transfers to the foreman and becomes her head. Now the worker has no head and the foreman has a head.
```

### Scene Structure for Complex Scenes
- Split each scene into **2 parts** with **2 characters each** (1 authority + 1 worker)
- Each part is a separate 5-second video clip
- Reuse prop images across scenes (door-only and scattered fragments)
- Part 1: Foreman + Hammer Worker
- Part 2: Architect + Saw Worker (or Axe Worker)
