# tiny-chess-01

A chess engine in at most 4,096 bytes of Python, entered in the make.fun
bounty "Build the strongest chess engine in 4 KB of Python" (tiny-chess-01).

`main.py` is the whole engine: a tapered PeSTO evaluation, PVS alpha-beta
search with transposition table, killer/history move ordering and a
quiescence search, all under a fixed node budget (deterministic — no clock,
no unseeded randomness). It plays the house gauntlet through the env at
`MAKEFUN_ENV_URL`.

## License

MIT — see LICENSE.
