# build-the-strongest-chess-engine-in-4kb

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/ajidayubi/build-the-strongest-chess-engine-in-4kb/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/ajidayubi/build-the-strongest-chess-engine-in-4kb/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A 3,297-byte Python chess engine (LZMA-packed into main.py): negamax with alpha-beta pruning, quiescence search, a 2^17-entry transposition table, killer moves, null-move pruning, and piece-square-table evaluation, on a fixed 50,000-node budget per move. It plays the make.fun gauntlet over HTTP and scored Elo 1173 on practice trial-0 (2 wins, 1 draw, 5 losses).

## Run it

```sh
python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=cbk8hpf3&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
