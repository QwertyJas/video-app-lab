# video-app (code root)

Own video-generator capability, free-first. Plan: PROJECTS/2026-10-17_video-app/PLAN.md

- runner/   job queue + model adapters + free-tier scheduler
- director/ prompt compiler (shot list -> prompts), camera vocabulary, seeds
- post/     ffmpeg stitch, upscale, captions, audio
- guard/    cost guard (blocks paid endpoints), quota logging
- studies/  one study card per model repo

Rule: zero spend. Every capability claim comes from a logged run.
