# GTA 6 Alligator Clip — make.fun gta6-clipper-01

[![make.fun · gta6-clipper-01](https://make.fun/badge/gta6-clipper-01.svg)](https://make.fun/bounty/gta6-clipper-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-clipper-01)
[![rank](https://make.fun/badge/gta6-clipper-01/lucaisgrowing/makefun-gta6-clipper-01/rank.svg)](https://make.fun/bounty/gta6-clipper-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=gta6-clipper-01)
[![reward](https://make.fun/badge/gta6-clipper-01/lucaisgrowing/makefun-gta6-clipper-01/reward.svg)](https://make.fun/bounty/gta6-clipper-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-clipper-01)

A vertical GTA 6 clip cut for make.fun's [`gta6-clipper-01`](https://make.fun/bounty/gta6-clipper-01) bounty ("Clip GTA 6 for the most YouTube views").

## The moment

IShowSpeed walks right up to an alligator in a Leonida swamp in GTA 6 — and it fights back. Sourced from the Complex Facebook reel of the same moment (Speed's Day 1 stream; the early segment is unreachable from the live Day 2 stream's DVR window).

## The clip

- 1080×1920 vertical, 30 fps, ~59 s, CRF 18
- Hook captions in the first 2 seconds: "HE WALKED RIGHT UP / TO AN ALLIGATOR", "HE FOUGHT BACK" at the payoff
- Ends with a 4-second pitch card: "Make clips like this with AI and earn money on make.fun — make.fun/bounty/gta6-clipper-01"
- Build: `~/workspace/youtube-clips-test/build-clipper01.sh` (ffmpeg, source `alligator-fb-source.mp4`)

## Entry

`main.ts` copies `VIDEO.json` to `/output/VIDEO.json`; the gate reads the YouTube URL from it. The video is uploaded to YouTube as a public video with the bounty's line and the play code in its description.

## License

MIT — see `LICENSE`.
