# A BIT BIZAARE — the complete site

Every project by [**fenix_the_producer** (`abitbizaaare`)](https://github.com/abitbizaaare),
merged into one cohesive website. Pure static HTML/CSS/JS — no build step, no dependencies.

## Run it locally

Any static server works. For example:

```bash
cd site
python -m http.server 8099
# open http://localhost:8099
```

## Structure

```
site/
├── index.html              # the hub / landing (matrix rain, worlds grid, passcode easter egg)
├── music/                  # fenix_the_producer — bio, links, playable track archive
├── marketplace/            # Q@W@RD — identity marketplace app   (from: manhattan)
├── fashion/                # Q@W@RD × ZenGriffeyJR fashion engine (from: PROJECTMANHATTAN)
├── buddha/                 # .buddha — final archive / whale AI    (from: .buddha)
├── archive/                # the Samue jacket / streetwear lookbook
├── shop/                   # Nick Knacks — neon shop               (from: nickknacks)
├── arcade/
│   ├── index.html          # arcade hub
│   ├── matrixman/          # Code Storm — falling-code platformer  (from: matrixman)
│   └── sudoku/             # Matrix Sudoku Gate                    (from: sudoku)
└── assets/
    ├── img/                # all shared images
    └── audio/              # all shared tracks & sounds
```

## Source repos merged

`manhattan`, `.buddha`, `PROJECTMANHATTAN`, `fenix`, `Fenix_the_producer`,
`nickknacks`, `sudoku`, `matrixman`, `Q-w-rd`, `qaward`, `A-Bit-Bizarre`.

## Notes

- The three flagship apps (marketplace, fashion, .buddha) are kept intact with a floating
  **← a bit bizaare** home button added. Their "enter loop" buttons now loop between each other.
- The marketplace passcode gate is preserved (passcode: `suchness`) with an on-screen hint so
  nobody gets locked out.
- Easter eggs from the originals are kept: the hub passcode (`who is the teacher without the hat`,
  `suchness`, `42`), and the sudoku magic word (`6 * 7 = 42`).
