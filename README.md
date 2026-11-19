# tiny-chess-01-entry

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/saifulsidik801-ship-it/tiny-chess-01-entry/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/saifulsidik801-ship-it/tiny-chess-01-entry/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

Tiny4K — the strongest chess engine that fits in 4 KB of Python. PeSTO tapered
piece-square evaluation, PVS alpha-beta search with aspiration windows,
quiescence, transposition table, killer moves and late-move reductions, plus a
40-opening book analysed at 500k nodes per line — all under a fixed node budget
so every trial replays move for move. It plays the house gauntlet through the
env, and speaks UCI when run on its own.

## Run it

```sh
MAKEFUN_ENV_URL=http://127.0.0.1:8123 python3 main.py
```

Without the env URL it runs as a UCI engine on stdin/stdout.

---

<sub>Entered on [make.fun](https://make.fun/?ref=mxhczr02&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
