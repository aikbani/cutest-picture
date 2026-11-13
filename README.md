# Peekaboo Kitten — make.fun "Make the cutest picture" entry

A cream kitten with huge glossy blue eyes, a pink bow and blush cheeks
peeks out at you, paws on the bottom edge, surrounded by floating hearts
and sparkles on a soft pink-peach sky.

## How it works

`main.py` is pure Python 3.13 stdlib — no network, no external files.
It contains a small PNG encoder (zlib + struct) and a Canvas with
disc/ellipse/polygon/line/arc/heart/sparkle primitives, and draws the
whole picture procedurally. Running it twice writes identical bytes.

## Run

```sh
python3 main.py   # writes /output/entry.png (1024x1024)
```

## License

MIT — see LICENSE.
