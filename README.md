# tiny-chess

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/lycann666/tiny-chess/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/lycann666/tiny-chess/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in at most 4,096 bytes of Python for make.fun's tiny-chess-01 gauntlet. 0x88 board, alpha-beta search with PVS, quiescence search, transposition table, null-move pruning and late move reductions, material + piece-square evaluation, Zobrist hashing, and a fixed node budget per move. It plays the harness environment protocol (HTTP game/move endpoints) against eight house engines, from depth-2 alpha-beta up to 2,000,000 nodes a move.

## Run it

```sh
python3 main.py
```

The engine talks to the harness environment at `MAKEFUN_ENV_URL` (default `http://localhost:8000`).

---

<sub>Entered on [make.fun](https://make.fun/?ref=5f3j6jyb&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
