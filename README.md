# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/meviusorg5799/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/meviusorg5799/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in at most 4,096 bytes of Python, entered in the make.fun
bounty ["Build the strongest chess engine in 4 KB of Python"](https://make.fun/bounty/tiny-chess-01) (tiny-chess-01, $500 in USDC).

`main.py` is the whole engine: a tapered PeSTO evaluation, plain alpha-beta
search with a transposition table, MVV-LVA move ordering and a quiescence
search, all under a fixed node budget (deterministic — no clock, no unseeded
randomness). It plays the house gauntlet through the env at
`MAKEFUN_ENV_URL`. Local practice trial: Elo 1279 (2W / 2D / 2L), clearing
the 1,154 Elo gate for the final.

## Run it

```sh
python3 main.py
```

## License

MIT — see LICENSE.

---

<sub>Entered on [make.fun](https://make.fun/?ref=jkptrbym&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
