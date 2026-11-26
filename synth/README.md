
## location_loop2.wav (`locsynth`) — ours, CC0
A 2-bar loop synthesised in Python (no sample audio inside) with the chord timing measured from the start of Playboi Carti's "Location"
(F# -> E -> D#m, 63 BPM, 7.619 s): additive voices, 12 harmonics rolled off above ~2.6 kHz, a detuned twin for chorus, a 5 Hz warble,
60 ms attacks, the chord voiced an octave up so its band balance matches the record's loop (150-400 / 400-2k Hz: 44 / 45 % vs the record's 36 / 51 %). A postable stand-in for the record's loop in tracks/location-glitch.

### location_loop3.wav (v3, the one `locsynth` now points to)
Rebuilt from measurement: the record's loop is Allan Holdsworth's "Endomorph" from 1:30.65, resampled up one semitone (matched at r = 0.91;
the remake videos say the same: "pitch up the sample 100 cents"). Its voicings, read from CQT peaks with harmonics removed, are wide SynthAxe
chords: F#2 C#3 A#3 D#4 (+C#6) | E2 B2 D#3 E3 F#3 B3 D#4 | D#2 A#2 F#3 C#4 G#4 (+F#6), with the measured relative levels; a 5.9 Hz warble
(±14 cents per voice, a ±6 cent chorus pair); then the long-term spectrum matched to the record's loop with a 1/6-octave linear-phase EQ.
Synthesised; no sample audio inside (the EQ curve is a smoothed spectrum, not audio).

## dread_block_a / dread_block_b / dread_drone (`dsyn:0-2`) — ours, CC0
Synthesised in Python from measurements of A. G. Cook's "Dread" at 2:05 (stems; no sample audio inside): the "chord" is one Bb2 (116.7 Hz)
saw, 3 voices ±8 cents, with a resonant peak at its 8th harmonic (933 Hz, the loudest partial on the record), over an Eb2 (77.8 Hz) that dips
on every beat (the 2.33 Hz sidebands); the gallop is a shallow gate (quick attack, ~4-5 dB sag, x x . x for 5 beats, then 3 beats off;
2 bars at 140 BPM). Block b is the brighter one (blocks 5-8 of the record, the filter more open). The drone is a 3-voice cluster at a
quarter-flat B (476 / 490 / 506 Hz on the record), 4 bars high then 4 bars an octave down. Each part's long-term spectrum is matched to its
stem with a 1/6-octave linear-phase EQ.

## dread7_* (`dsyn7:0-2`) — ours, CC0
The same resynthesis as dsyn at 137.14 BPM (one bar = 1.75 s, so 4 bars = 7.000 s) for a 7-second TouchDesigner loop; the drone is 4 bars with no fades so it loops seamlessly.

### dread7_hold_a / dread7_hold_b (dsyn7:0-1 now)
The chord held steady for its 5 beats (the record's level is flat within ~1 dB across each beat), no gallop dips and no per-beat pump: the gallop on the record is a separate low thump on each step (its drum stem: ~110 -> 70 Hz in 25 ms, -15 dB in 50 ms, 9.4 dB under the chord), played by Strudel in tracks/dread/loop7.strudel.

`locsynth7` = `location_loop3_7s.wav`: location_loop3 time-stretched (pitch kept) to 7.000 s (2 bars at 68.57 BPM). Ours, CC0.

## agony_piano7.wav — ours (Salamander Grand Piano, CC-BY 3.0, Alexander Holm)
Our own render, made in Strudel with its built-in "piano" (the Salamander Grand Piano samples by Alexander Holm, CC-BY 3.0: credit him if you post it). 2 bars at 102.86 BPM (4.667 s, one bar = 7/3 s) for the 7-second TouchDesigner loop in strudel-studio tracks/agony-glitch: the B | C#m → E chords of Yung Lean's "Agony" as left-hand block chords in 8ths, with our own right-hand line (not the record's melody), a 12-cent detuned double and a little room. No audio from the record inside. Source: tracks/agony-glitch/piano7-source.strudel; peak normalised to -1 dBFS, 48 kHz 16-bit stereo.

- `agony_chords7.wav`: the same 2-bar render as `agony_piano7.wav` with the right hand muted, chords only (B, C#m to E) for the Agony glitch loop (strudel-studio `tracks/agony-glitch/`). Our own Strudel render; the piano is Salamander Grand Piano by Alexander Holm, CC-BY 3.0.
