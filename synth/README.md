
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
