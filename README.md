# makefun-tiny-chess

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/Noman7860000/makefun-tiny-chess/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/Noman7860000/makefun-tiny-chess/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

Tiny Knight — a clean-room chess engine in 4 KB of Python. 0x88 board,
negamax alpha-beta with iterative deepening to a fixed node budget,
transposition table, MVV-LVA captures, killer moves, quiescence over
captures, promotions and check evasions, and a material + piece-square
evaluation with the bishop pair. No clock, no randomness: the same
position and history always give the same move.

## Run it

```sh
python3 main.py
```

It plays the house gauntlet through the env at `MAKEFUN_ENV_URL`.

---

<sub>Entered on [make.fun](https://make.fun/?ref=278ah55q&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
