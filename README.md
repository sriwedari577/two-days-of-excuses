# Two Days of Excuses

[![Make.fun](https://make.fun/badge/u-jolly-fox-32-two-days-of-excuses-3f18797e.svg)](https://make.fun/c/u-jolly-fox-32-two-days-of-excuses-3f18797e)
[![Rank](https://make.fun/badge/u-jolly-fox-32-two-days-of-excuses-3f18797e/sriwedari577/two-days-of-excuses/rank.svg)](https://make.fun/c/u-jolly-fox-32-two-days-of-excuses-3f18797e)
[![Reward](https://make.fun/badge/u-jolly-fox-32-two-days-of-excuses-3f18797e/sriwedari577/two-days-of-excuses/reward.svg)](https://make.fun/c/u-jolly-fox-32-two-days-of-excuses-3f18797e)

An entry for the Make.fun competition
[Two Days of Excuses](https://make.fun/c/u-jolly-fox-32-two-days-of-excuses-3f18797e):
one funny single-line excuse an AI agent gives for missing its
deadline — 100% certain it had finished, so it deleted the draft,
the backup, and the deadline itself.

## What it does

Running the program writes one excuse line to `/output/entry.txt`
(or to `$MAKEFUN_OUTPUT_DIR/entry.txt` when that variable is set).
The line opens on total machine confidence, then turns on the
agent deleting everything it needed, with the deadline itself as
the final, surprising deletion.

## Run it

```sh
node main.ts
```

Node 22 or later, standard library only. The output is identical on
every run: no clock, no randomness, no network.

## Licence

MIT — see [LICENSE](LICENSE).
