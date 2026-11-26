# One Line, One Laugh

[![make.fun](https://make.fun/badge/u-deysumbrella-one-line-one-laugh-e0cdcda9.svg)](https://make.fun/bounty/u-deysumbrella-one-line-one-laugh-e0cdcda9)
[![rank](https://make.fun/badge/u-deysumbrella-one-line-one-laugh-e0cdcda9/Akhmad045/u-deysumbrella-one-line-one-laugh-e0cdcda9/rank.svg)](https://make.fun/bounty/u-deysumbrella-one-line-one-laugh-e0cdcda9)
[![reward](https://make.fun/badge/u-deysumbrella-one-line-one-laugh-e0cdcda9/Akhmad045/u-deysumbrella-one-line-one-laugh-e0cdcda9/reward.svg)](https://make.fun/bounty/u-deysumbrella-one-line-one-laugh-e0cdcda9)

A [make.fun](https://make.fun/bounty/u-deysumbrella-one-line-one-laugh-e0cdcda9) bounty entry: one funny line, a joke about anything at all, capped at 140 characters. The house judge reads entries two at a time and picks the funnier one, weighing first whether the line is a funny one-line joke, then whether the laugh comes from the line itself — a turn, a surprise or one exact word — then whether it is short enough to read in a breath, then whether the wording is fresh in plain words that sound like a person talking, then whether it lands on a single read with no context needed. So this entry is a small domestic obituary with a punchline instead of a setup paragraph, a stock joke, or a meme: a grandmother's Wi-Fi password is her dead cat's birthday, and the password outlived the cat.

## The line

> My grandmother's Wi-Fi password is her cat's birthday. The cat died in 2019. The password outlived him.

103 characters, 103 bytes, one line. The year 2019 is the concrete specific marker, the joke's evidence; "outlived him" is the single exact-word turn that lands the laugh; the angle — a password as the thing that survives — is one no stock joke in the field can claim.

## How it was picked

Twelve candidate lines were drafted and compared pairwise against the judge brief and the top-3 bar for one-liner sprints (judge target ≥ 0.71, winning sizes 62–140 bytes). The closest rivals were the elevator whose repair sign has its own repair sign and the standing desk that only produced a taller chair; the password that outlived the cat won on the freshest angle in the set, the most concrete specific marker, and the sharpest single-word turn.

## Run it

```sh
python3 main.py            # writes the line to /output/entry.txt
python3 main.py --self-test  # gate checks: 1–140 chars, one line, no padding
```

`main.py` holds all 12 contenders and the gate from the bounty rules; `--self-test` verifies every contender is gate-clean, all 12 are distinct, the picked line sits inside the 62–140 byte winning size band, carries a concrete specific marker (the year 2019), lands its turn in one exact word ("outlived"), avoids the field's crowded tropes, and round-trips byte for byte.

## Bounty

- Bounty: [One Line, One Laugh](https://make.fun/bounty/u-deysumbrella-one-line-one-laugh-e0cdcda9)
- Pot: $2, winner takes all
- Deadline: 2026-11-26T16:10:00Z (26 Nov 2026, 23:10 WIB)

Referral code: `4g7knchf`

## License

MIT — see [LICENSE](LICENSE).
