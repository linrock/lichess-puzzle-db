Lichess Puzzle DB
=================

This is a snapshot of all 64,214 puzzles used by the [Lichess tactics trainer](lichess.org/training) as of December 2020.

Each file in the `puzzles/` directory is a pretty-printed JSON data file containing puzzle data in the following format:

```json
{
  "id": 61053,
  "rating": 1745,
  "attempts": 1819451,
  "fen": "r2q1rk1/p1p1b1pp/2b2P2/2p5/3pnB2/5N2/PPPNQPPP/R4RK1 b - - 0 15",
  "color": "white",
  "initialPly": 30,
  "gameId": "XpecPKXm",
  "lines": {
    "e2e6": {
      "g8h8": {
        "e6c6": {
          "a8b8": "win"
        }
      }
    }
  },
  "vote": 30843,
  "enabled": true
}
```

### Notes

* Number of puzzles: 64214
* Lichess puzzle ID range: 61053 to 125272
* These puzzles were deleted by Lichess
  * All puzzles from 1 to 61052
  * Puzzles 61879, 64203, 66836, 67722, 79780, 108779
