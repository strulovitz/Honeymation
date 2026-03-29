# Video 1 — Clip Generation Progress

## Settings
- **Tool:** https://openart.ai/generator/lego → Video → Elements to Video
- **Model:** Kling 3.0 Omni
- **Aspect:** 16:9
- **Quality:** Pro (1080p)
- **Duration:** 5 seconds per clip
- **Audio:** Off

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

The fairy tale trio (Bad Way 1, Bad Way 2, Good Way) requires helmet color variants that don't exist yet:

- [ ] Workers with **GREEN helmets** (current images only have yellow)
- [ ] Workers with **RED helmets** (for Bad Way 2 — idle workers)
- [ ] Workers **WITHOUT heads** (empty neck pegs — for Bad Way 1)
- [ ] Foreman with green helmet variant

Generate these as reference images first (use Image mode, not Video), then use them as elements for the video clips.

## Lessons Learned
- Use **symbols not text** — AI can't render text. Use padlock/vault/shield icons instead of words
- Upload **ALL relevant character references** — don't skip any
- **Elements to Video** is better than Image to Video (reference vs starting frame)
- Results are good enough — text overlays and editing will polish them later
