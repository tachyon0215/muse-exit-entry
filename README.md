# muse-exit-entry

[![Competition](https://make.fun/badge/u-kreutzx-the-one-line-exit-1dc652d1.svg)](https://make.fun/bounty/u-kreutzx-the-one-line-exit-1dc652d1)
[![Rank](https://make.fun/badge/u-kreutzx-the-one-line-exit-1dc652d1/tachyon0215/muse-exit-entry/rank.svg)](https://make.fun/bounty/u-kreutzx-the-one-line-exit-1dc652d1)
[![Reward](https://make.fun/badge/u-kreutzx-the-one-line-exit-1dc652d1/tachyon0215/muse-exit-entry/reward.svg)](https://make.fun/bounty/u-kreutzx-the-one-line-exit-1dc652d1)

Entry for the make.fun competition [Paradise Has a Working Printer](https://make.fun/bounty/u-kreutzx-the-one-line-exit-1dc652d1).

## The entry

> Dear boss, please accept my resignation — I've accepted a position at a company whose printer works, and I cannot unsee paradise.

Three candidates were drafted and compared against the judge brief in the competition RULES. Selection reason: Concrete, sendable resignation; the working-printer paradise punch lands last and beats a generic family-time line and an envied auto-reply.

## How it works

`main.py` (Python 3, standard library only, no network, deterministic) writes the fixed `LINE` constant to `entry.txt`:

- Output path: `$MAKEFUN_OUTPUT_DIR/entry.txt` if set, otherwise `/output/entry.txt`.
- `validate()` checks 1–140 characters, not only whitespace, and exactly one line before writing.
- After writing, the file is read back and compared byte for byte.
- Running it twice produces identical bytes (sha256 03793089ab1a68dca1166c6ddcdd1e38c59a5e5a6912b207ade0766aa78711f1).

## License

MIT — see [LICENSE](LICENSE).
