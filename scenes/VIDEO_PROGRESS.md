# Video 1 — Clip Generation Progress

## Settings

### Video Clips
- **Tool:** https://openart.ai/generator/lego → Video → Elements to Video
- **Model:** Kling 3.0 Omni
- **Aspect:** 16:9
- **Quality:** Pro (1080p)
- **Duration:** 5 seconds per clip
- **Audio:** Off

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
| 7 | Bad Way 1 (CrewAI) | - | TODO — needs new reference images first |
| 8 | Bad Way 2 (Petals/Exo) | - | TODO — needs new reference images first |
| 9 | Good Way (BeehiveOfAI) | - | TODO — needs new reference images first |
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
| 2 | Worker 2 (saw) | `characters/images/04_worker2_saw.jpg` | TODO |
| 3 | Worker 3 (axe) | `characters/images/05_worker3_axe.jpg` | TODO |
| 4 | Foreman | `characters/images/02_foreman.jpg` | TODO |
| 5 | Architect | `characters/images/01_architect.jpg` | TODO |

**RED helmet (for Scene 8 — Petals/Exo, Bad Way 2 — idle/waiting):**
| # | Character | Omni Reference (upload this) | Status |
|---|-----------|------------------------------|--------|
| 6 | Worker 1 (hammer) | `characters/images/03_worker1_hammer.jpg` | TODO |
| 7 | Worker 2 (saw) | `characters/images/04_worker2_saw.jpg` | TODO |
| 8 | Worker 3 (axe) | `characters/images/05_worker3_axe.jpg` | TODO |
| 9 | Foreman | `characters/images/02_foreman.jpg` | TODO |
| 10 | Architect | `characters/images/01_architect.jpg` | TODO |

**NO HEAD — empty neck peg (for Scene 7 — CrewAI, Bad Way 1 — waiting for the shared brain):**
| # | Character | Omni Reference (upload this) | Status |
|---|-----------|------------------------------|--------|
| 11 | Worker 1 (hammer) | `characters/images/03_worker1_hammer.jpg` | TODO |
| 12 | Worker 2 (saw) | `characters/images/04_worker2_saw.jpg` | TODO |
| 13 | Worker 3 (axe) | `characters/images/05_worker3_axe.jpg` | TODO |
| 14 | Foreman | `characters/images/02_foreman.jpg` | TODO |
| 15 | Architect | `characters/images/01_architect.jpg` | TODO |

Generate these as reference images first (use Image mode, not Video), then use them as elements for the video clips.

## Lessons Learned
- Use **symbols not text** — AI can't render text. Use padlock/vault/shield icons instead of words
- Upload **ALL relevant character references** — don't skip any
- **Elements to Video** is better than Image to Video (reference vs starting frame)
- Results are good enough — text overlays and editing will polish them later
