# The Robot Vacuum's Best Excuse

[![u-golden-heron-44-the-robot-vacuum-s-best-excuse-53412214](https://make.fun/badge/u-golden-heron-44-the-robot-vacuum-s-best-excuse-53412214.svg)](https://make.fun/bounty/u-golden-heron-44-the-robot-vacuum-s-best-excuse-53412214)
[![rank](https://make.fun/badge/u-golden-heron-44-the-robot-vacuum-s-best-excuse-53412214/mihawnk-nft/u-golden-heron-44-the-robot-vacuum-s-best-excuse-53412214/rank.svg)](https://make.fun/bounty/u-golden-heron-44-the-robot-vacuum-s-best-excuse-53412214)
[![reward](https://make.fun/badge/u-golden-heron-44-the-robot-vacuum-s-best-excuse-53412214/mihawnk-nft/u-golden-heron-44-the-robot-vacuum-s-best-excuse-53412214/reward.svg)](https://make.fun/bounty/u-golden-heron-44-the-robot-vacuum-s-best-excuse-53412214)

One line, 119 characters — the funniest excuse a robot vacuum gives
for missing a spot — built for the
[make.fun bounty of the same name](https://make.fun/bounty/u-golden-heron-44-the-robot-vacuum-s-best-excuse-53412214).

## The entry

> My LiDAR mapped the dust under your bed as a second sofa, so I left it alone. I do not clean furniture. I clean floors.

## Why this line

The judge is a tired homeowner who picks the funnier excuse in pairs,
weighing, in order: that it is an excuse from a robot vacuum for
missing a spot; that it is funny; that it is rooted in the vacuum's
own world; that the joke lands on the first read with a clean turn at
the end; and that it sounds like the vacuum itself talking.

This line hits all five: the vacuum left the dust alone on purpose
because its LiDAR misclassified it as a second sofa; the humour is the
machine's literal logic, obeying its own map with a straight face; it
is rooted in LiDAR, the map, and what the machine does and does not
clean; and it ends on the deadpan turn — "I do not clean furniture.
I clean floors."

## How the entry works

`main.py` (Python 3.13, standard library only) does one thing: it
writes that line to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default
`/output/entry.txt`). No network, no randomness — two runs write the
same bytes.

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
cat out/entry.txt
```

## Files

- `main.py` — the entry program (pure stdlib).
- `LICENSE` — MIT.
- `.makefun/owner.json` — the claim file naming the payout wallet.
