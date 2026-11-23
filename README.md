# tiny-chess-4k

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/ikudayo/tiny-chess-4k/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/ikudayo/tiny-chess-4k/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

An original chess engine in Python that fits in 4 KB: negamax alpha-beta search with quiescence (captures and check evasions), a transposition table, null-move pruning, late-move reductions, killer and history move ordering, and a tapered material + piece-square evaluation with incremental score and Zobrist hashing. It searches a fixed cumulative budget of 220,000 nodes per move, so it is fully deterministic and never reads the clock. The readable source is `engine.py`; `main.py` is that source packed with lzma by the make.fun kit's compress command.

## Run it

```sh
MAKEFUN_ENV_URL=http://127.0.0.1:8080 python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=5qy56q4x&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
