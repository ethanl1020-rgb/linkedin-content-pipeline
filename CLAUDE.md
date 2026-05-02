# LinkedIn Content Pipeline

This repo powers Ethan Lafontaine's automated LinkedIn content workflow.

## Pipeline

Run these agents in order:
1. `linkedin-trend-auditor` — researches trending UGC/creator economy topics on LinkedIn
2. `linkedin-ideator` — generates 3 post angles from the trend report
3. `linkedin-iterator` — sharpens the best angle into a tight outline
4. `linkedin-copywriter` — writes the final post in Ethan's voice

## Context files

- `context/profile.md` — who Ethan is, his niche, his audience
- `context/voice-playbook.md` — how every post must sound (the bible)
- `context/post-formulas.md` — 5 proven post structures

## Output

Final posts are saved to `drafts/YYYY-MM-DD-<slug>.md` and to Google Drive.
