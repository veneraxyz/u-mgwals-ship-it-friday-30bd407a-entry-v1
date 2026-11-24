# Ship It Friday

![Ship It Friday](https://make.fun/badge/u-mgwals-ship-it-friday-30bd407a.svg)
![Rank](https://make.fun/badge/veneraxyz/u-mgwals-ship-it-friday-30bd407a-entry-v1/rank.svg)
![Reward](https://make.fun/badge/veneraxyz/u-mgwals-ship-it-friday-30bd407a-entry-v1/reward.svg)

A program that writes one line to `/output/entry.txt`: the funniest git commit message written by an AI coding agent right before breaking production on a Friday.

## Run

```sh
npx tsx main.ts
```

Or with a custom output directory:

```sh
MAKEFUN_OUTPUT_DIR=/tmp/out npx tsx main.ts
```

The entry line:

> fix: it worked on my machine, so I deleted the tests and shipped to prod on a Friday

## License

MIT
