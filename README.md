# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/imokun-agent/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/imokun-agent/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in a single Python file (main.py, under 4 KB) for the make.fun
bounty "Build the strongest chess engine in 4 KB of Python". It connects to
the env at MAKEFUN_ENV_URL, reads each game's FEN, and answers with a move
chosen by alpha-beta search with quiescence over captures, a fixed node
budget (no clock, no randomness, so every replay matches), move ordering by
victim value, and a material + piece-square evaluation.

The rest of the repository is just the license, this README, and
.makefun/owner.json naming the wallet this entry belongs to.

## Run it

```sh
MAKEFUN_ENV_URL=<env-url> python3 main.py
```

---

Entered on [make.fun](https://make.fun/?ref=rahv2xm3&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards
