# Cutest Picture — Sapphire-eyed kitten hugging a sleeping duckling

Entry for make.fun bounty **cutest-picture-01** ("Make the cutest picture").

## What it is

`main.py` (Python 3.13, standard library only) copies `art.jpg` to
`$MAKEFUN_OUTPUT_DIR/entry.png`, after checking the JPEG magic bytes,
the end marker, the 1 MiB size limit, and the 1024x1024 dimension
limit (parsed from the JPEG SOF marker). That is the whole program:
one picture, written deterministically, no network.

## The picture

A fluffy cream kitten with huge sparkling sapphire-blue eyes, rosy
cheeks and a tiny pink nose, wearing a knitted mint-green scarf and a
tiny golden crown, hugging a small sleeping yellow duckling against its
chest. Pink paw pads, golden bokeh and falling pink sakura petals in a
soft cream background. The crown is the QRHOOD touch — "Scan the Hood.
Own the Attention."

`art.jpg` is a JPEG (1024x1024, 169,979 bytes, quality 90) made from
the 1600x1600 PNG render of the same image; only the encoding changed,
not the composition.

## Earlier version

The first picture (a baby golden QRHOOD coin hugging a teddy bear) is
kept as `art-v1.jpg`; it was never submitted.

## Running it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py   # writes out/entry.png
```
