# kits — curated, measured, clearly licensed drum sounds

Every pack here is CC0 (public domain dedication), so it can live in this public repo and be used in posted tracks. Each folder has a `SOURCE.md`.

Load everything: `samples('github:oscarbeamish/samples')`. strudel.cc caches this repo's map, so in tracks it's safer to list files directly:
`samples({ k808: ['kits/tr808/bd5050.wav'] }, 'github:oscarbeamish/samples')`

## tr808 — Michael Fischer's Roland TR-808 set (1994, CC0)
The real machine, 116 one-shots. Kicks are the point: **78–93 % of their energy sits below 60 Hz** and the long ones ring for up to 3 s. (The built-in `RolandTR909` kick has 0.4 % sub.)

| name | count | index meaning |
|---|---|---|
| `k808` | 25 | kick. Index = decay × tone: `0–4` 0.25 s (30 % sub), `5–9` 0.5 s (55 %), `10–14` 1.5 s (80 %), `15–19` 2 s (87 %), `20–24` 3 s (93 %). Within each group tone goes 0 → 100 % (brighter click). Fundamental ≈ 53 Hz (≈ G♯1/A1). |
| `s808` | 25 | snare, same decay × tone grid (0.25–0.5 s) |
| `cy808` | 25 | cymbal, same grid |
| `oh808` | 5 | open hat, decay 0 → 100 % |
| `ch808` `cp808` `cb808` `cl808` `rs808` `ma808` | 1 each | closed hat, clap, cowbell, clave, rimshot, maracas |
| `hc808` `mc808` `lc808` | 5 each | high / mid / low conga, tuning 0 → 100 % |
| `ht808` `mt808` `lt808` | 5 each | high / mid / low tom, tuning 0 → 100 % |

On a 4x4 beat a long kick overlaps the next one: use `.clip(.95).release(.03)` so each kick ends just before the next.

## sub808 — 808 bass tones (Boochi44/free-drum-samples, CC0)
8 pitched 808 bass hits, 0.6–1.2 s, **92–98 % sub**, fundamental 49–56 Hz (G1–A1). `sub808:0–1` bounce (clean, 1 s), `2–3` hard trap (distorted, 1.2 s), `4–5` soulful (lo-fi), `6–7` punchy. Pitch them with `.note()` (they sit at C2 = 36 like any sample).

## xkick — synthesised kicks (xyproto/synth, CC0)
15 generated kicks, 0.4–0.9 s. `808_classic` / `deephouse_*` are 98 % sub at 40–47 Hz; `909_*` are 60 % punch; `videogame_*` and `experimental_*` are clicky. Names in `strudel.json` are index order (alphabetical): 0 `606_classic`, 1 `606_varied_1`, 2 `707_classic`, 3 `707_varied_1`, 4 `808_classic`, 5 `808_varied_1`, 6 `909_classic`, 7 `909_varied_1`, 8 `deephouse_classic`, 9 `deephouse_varied_1`, 10 `deephouse_varied_2`, 11 `experimental_classic`, 12 `experimental_varied_1`, 13 `videogame_kick_1`, 14 `videogame_kick_2`.

## Not included (licence unclear)
`smpldsnds/drum-machines` (LinnDrum LM-2, Drumtraks, CR-8000, MFB-512…) and the "Drum Abuse" archives say "public domain" without naming a source, so they stay out of this public repo.

## gabber — synthesised hardcore kicks matched to the records (ours, CC0)
`gkick:0–2`, 300–450 ms one-shots synthesised in Python (`strudel-studio/tools/kick_match.py`): a sine with an exponential pitch sweep, a click, soft/diode drive, **then** a low-pass and a resonant bump (the distortion-then-EQ chain Strudel can't do), chosen from 1200–1500 candidates by log-mel distance to isolated kicks cut from the records' drum stems. No sample audio inside.
- `gkick:0` (`penta1`): matched to Pentagramm + 9mm + Gewalt Gewalt together: 839 → 56 Hz over 26 ms (the records' high "tongue"), body A1, 435 ms, diode drive 5.9, low-pass 1.7 kHz. One-shot 75 % sub / 16 % at 60–150.
- `gkick:1` (`penta2`): matched to Pentagramm alone: 97 → 56 Hz, diode 5.2, low-pass 1.1 kHz, 300 ms. 47 / 48 / 5.
- `gkick:2` (`penta3`): the three-record search's #3: 708 → 48 Hz over 35 ms, body 48 Hz, 352 ms, diode 3, low-pass 970 Hz. 77 / 20 / 3.
