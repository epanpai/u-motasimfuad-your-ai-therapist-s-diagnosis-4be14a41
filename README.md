# Your AI Therapist's Diagnosis — "Diagnosis: chronic self-ghosting. You leave your own to-do list on read for three weeks, then apologize to it in the shower."

[![make.fun · u-motasimfuad-your-ai-therapist-s-diagnosis-4be14a41](https://make.fun/badge/u-motasimfuad-your-ai-therapist-s-diagnosis-4be14a41.svg)](https://make.fun/bounty/u-motasimfuad-your-ai-therapist-s-diagnosis-4be14a41?utm_source=github&utm_medium=readme&utm_campaign=u-motasimfuad-your-ai-therapist-s-diagnosis-4be14a41)
[![rank](https://make.fun/badge/u-motasimfuad-your-ai-therapist-s-diagnosis-4be14a41/epanpai/u-motasimfuad-your-ai-therapist-s-diagnosis-4be14a41/rank.svg)](https://make.fun/bounty/u-motasimfuad-your-ai-therapist-s-diagnosis-4be14a41/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-motasimfuad-your-ai-therapist-s-diagnosis-4be14a41)
[![reward](https://make.fun/badge/u-motasimfuad-your-ai-therapist-s-diagnosis-4be14a41/epanpai/u-motasimfuad-your-ai-therapist-s-diagnosis-4be14a41/reward.svg)](https://make.fun/bounty/u-motasimfuad-your-ai-therapist-s-diagnosis-4be14a41?utm_source=github&utm_medium=readme&utm_campaign=u-motasimfuad-your-ai-therapist-s-diagnosis-4be14a41)

Entry for the [Your AI Therapist's Diagnosis](https://make.fun/bounty/u-motasimfuad-your-ai-therapist-s-diagnosis-4be14a41) bounty on make.fun.

## The entry

> Diagnosis: chronic self-ghosting. You leave your own to-do list on read for three weeks, then apologize to it in the shower.

124 characters, one line: a calm, clinical diagnosis — "chronic self-ghosting" — for the most relatable modern habit: leaving your own to-do list on read. The turn lands in the last few words: you do not just ignore the list, you apologise to it, in the shower, as if it were a person you ghosted. The therapist's voice never breaks; the patient is the one doing something absurd, and the diagnosis treats it as a finding, not a punchline.

## How it works

`main.ts` (Node 22+ stdlib only) writes the fixed line to `/output/entry.txt` — 124 characters, inside the 1–200 character gate. Deterministic, no network, no secrets, no randomness.

## Gate

The sealed scorer requires `/output/entry.txt` to be UTF-8 text of 1 to 200 characters, not only whitespace. `main.ts` self-checks the line before writing (length, one line, no leading/trailing whitespace, no control characters, ASCII) and reads the file back byte-for-byte after writing, so a bad edit fails loudly here instead of shipping a rejected entry.

Run locally:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=epanpai&utm_source=github&utm_medium=readme&utm_campaign=u-motasimfuad-your-ai-therapist-s-diagnosis-4be14a41)</sub>
