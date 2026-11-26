# orch — real orchestral string recordings (CC0)

Every file here comes from **VSCO 2 Community Edition** by Versilian Studios (Samuel Gossner), https://github.com/sgossner/VSCO-2-CE, released under **CC0 1.0 Universal** (public domain dedication; the repo's LICENSE file is the full CC0 text). So they can be used in posted tracks and redistributed here.

Processing (strudel-studio, 2026-11-26, for tracks/connections v2): mono (L+R average), 44.1 kHz 16-bit, trimmed to start 10 ms before the note, cut to 6 s (8 s for the solo violin) with a 0.4 s fade-out, peak-normalised to −1 dBFS.

⚠ **VSCO names its section and contrabass files an octave low** (e.g. `VlnEns_susVib_A2` sounds A3; checked with pyin on every file). The keys in `strudel.json` and the file names here are the **true sounding pitch**. The solo violin files were already named correctly.

Load: `samples('github:oscarbeamish/samples')`, then `note("a4").s("vln")`; Strudel picks the nearest recorded note and repitches it.

| sound | what |
|---|---|
| `vln` | violin section, sustained with vibrato (VSCO "VlnEns_susVib", soft dynamic v1): a3, a4, b3, b5, c5, d4, e5, f#4, g5 |
| `vlntrem` | violin section, tremolo (VSCO "VlnEns_Trem", v1): a4, b3, b5, c5, d4, e5, f#4, g5 |
| `vla` | viola section, sustained with vibrato (VSCO "ViolaEns_susvib", v1): a4, b3, d3, d4, e3, f4, g3 |
| `vc` | cello section, sustained with vibrato (VSCO "susvib", v1): a3, b2, c2, c4, d3, e2, e4, f3, g2 |
| `vctrem` | cello section, tremolo (VSCO "trem", v1): a3, b2, c4, d3, e2, e4, f3, g2 |
| `vlnsolo` | solo violin, arco with vibrato, piano dynamic (VSCO "LLVln_ArcoVib", p): a4, a5, c5, c6, e5, e6, g5 |
| `cb` | solo contrabass, sustained with vibrato (VSCO "BKCtbss_SusVib", v1): a#1, a2, c2, d2, e2, f#1, f#2 |

## Files and sources

| file | sounds | original file (VSCO-2-CE) | author | licence |
|---|---|---|---|---|
| `vln/a3.wav` | A3, 6.0 s | [Strings/Violin Section/susVib/VlnEns_susVib_A2_v1.wav](https://github.com/sgossner/VSCO-2-CE/blob/master/Strings/Violin%20Section/susVib/VlnEns_susVib_A2_v1.wav) | Versilian Studios (Samuel Gossner) | CC0 1.0 |
| `vln/a4.wav` | A4, 6.0 s | [Strings/Violin Section/susVib/VlnEns_susVib_A3_v1.wav](https://github.com/sgossner/VSCO-2-CE/blob/master/Strings/Violin%20Section/susVib/VlnEns_susVib_A3_v1.wav) | Versilian Studios (Samuel Gossner) | CC0 1.0 |
| `vln/b3.wav` | B3, 6.0 s | [Strings/Violin Section/susVib/VlnEns_susVib_B2_v1.wav](https://github.com/sgossner/VSCO-2-CE/blob/master/Strings/Violin%20Section/susVib/VlnEns_susVib_B2_v1.wav) | Versilian Studios (Samuel Gossner) | CC0 1.0 |
| `vln/b5.wav` | B5, 6.0 s | [Strings/Violin Section/susVib/VlnEns_susVib_B4_v1.wav](https://github.com/sgossner/VSCO-2-CE/blob/master/Strings/Violin%20Section/susVib/VlnEns_susVib_B4_v1.wav) | Versilian Studios (Samuel Gossner) | CC0 1.0 |
| `vln/c5.wav` | C5, 6.0 s | [Strings/Violin Section/susVib/VlnEns_susVib_C4_v1.wav](https://github.com/sgossner/VSCO-2-CE/blob/master/Strings/Violin%20Section/susVib/VlnEns_susVib_C4_v1.wav) | Versilian Studios (Samuel Gossner) | CC0 1.0 |
| `vln/d4.wav` | D4, 6.0 s | [Strings/Violin Section/susVib/VlnEns_susVib_D3_v1.wav](https://github.com/sgossner/VSCO-2-CE/blob/master/Strings/Violin%20Section/susVib/VlnEns_susVib_D3_v1.wav) | Versilian Studios (Samuel Gossner) | CC0 1.0 |
| `vln/e5.wav` | E5, 6.0 s | [Strings/Violin Section/susVib/VlnEns_susVib_E4_v1.wav](https://github.com/sgossner/VSCO-2-CE/blob/master/Strings/Violin%20Section/susVib/VlnEns_susVib_E4_v1.wav) | Versilian Studios (Samuel Gossner) | CC0 1.0 |
| `vln/fs4.wav` | F#4, 6.0 s | [Strings/Violin Section/susVib/VlnEns_susVib_F#3_v1.wav](https://github.com/sgossner/VSCO-2-CE/blob/master/Strings/Violin%20Section/susVib/VlnEns_susVib_F%233_v1.wav) | Versilian Studios (Samuel Gossner) | CC0 1.0 |
| `vln/g5.wav` | G5, 6.0 s | [Strings/Violin Section/susVib/VlnEns_susVib_G4_v1.wav](https://github.com/sgossner/VSCO-2-CE/blob/master/Strings/Violin%20Section/susVib/VlnEns_susVib_G4_v1.wav) | Versilian Studios (Samuel Gossner) | CC0 1.0 |
| `vlntrem/a4.wav` | A4, 6.0 s | [Strings/Violin Section/Trem/VlnEns_Trem_A3_v1.wav](https://github.com/sgossner/VSCO-2-CE/blob/master/Strings/Violin%20Section/Trem/VlnEns_Trem_A3_v1.wav) | Versilian Studios (Samuel Gossner) | CC0 1.0 |
| `vlntrem/b3.wav` | B3, 6.0 s | [Strings/Violin Section/Trem/VlnEns_Trem_B2_v1.wav](https://github.com/sgossner/VSCO-2-CE/blob/master/Strings/Violin%20Section/Trem/VlnEns_Trem_B2_v1.wav) | Versilian Studios (Samuel Gossner) | CC0 1.0 |
| `vlntrem/b5.wav` | B5, 6.0 s | [Strings/Violin Section/Trem/VlnEns_Trem_B4_v1.wav](https://github.com/sgossner/VSCO-2-CE/blob/master/Strings/Violin%20Section/Trem/VlnEns_Trem_B4_v1.wav) | Versilian Studios (Samuel Gossner) | CC0 1.0 |
| `vlntrem/c5.wav` | C5, 6.0 s | [Strings/Violin Section/Trem/VlnEns_Trem_C4_v1.wav](https://github.com/sgossner/VSCO-2-CE/blob/master/Strings/Violin%20Section/Trem/VlnEns_Trem_C4_v1.wav) | Versilian Studios (Samuel Gossner) | CC0 1.0 |
| `vlntrem/d4.wav` | D4, 6.0 s | [Strings/Violin Section/Trem/VlnEns_Trem_D3_v1.wav](https://github.com/sgossner/VSCO-2-CE/blob/master/Strings/Violin%20Section/Trem/VlnEns_Trem_D3_v1.wav) | Versilian Studios (Samuel Gossner) | CC0 1.0 |
| `vlntrem/e5.wav` | E5, 6.0 s | [Strings/Violin Section/Trem/VlnEns_Trem_E4_v1.wav](https://github.com/sgossner/VSCO-2-CE/blob/master/Strings/Violin%20Section/Trem/VlnEns_Trem_E4_v1.wav) | Versilian Studios (Samuel Gossner) | CC0 1.0 |
| `vlntrem/fs4.wav` | F#4, 6.0 s | [Strings/Violin Section/Trem/VlnEns_Trem_F#3_v1.wav](https://github.com/sgossner/VSCO-2-CE/blob/master/Strings/Violin%20Section/Trem/VlnEns_Trem_F%233_v1.wav) | Versilian Studios (Samuel Gossner) | CC0 1.0 |
| `vlntrem/g5.wav` | G5, 6.0 s | [Strings/Violin Section/Trem/VlnEns_Trem_G4_v1.wav](https://github.com/sgossner/VSCO-2-CE/blob/master/Strings/Violin%20Section/Trem/VlnEns_Trem_G4_v1.wav) | Versilian Studios (Samuel Gossner) | CC0 1.0 |
| `vla/a4.wav` | A4, 6.0 s | [Strings/Viola Section/susvib/ViolaEns_susvib_A3_v1_1.wav](https://github.com/sgossner/VSCO-2-CE/blob/master/Strings/Viola%20Section/susvib/ViolaEns_susvib_A3_v1_1.wav) | Versilian Studios (Samuel Gossner) | CC0 1.0 |
| `vla/b3.wav` | B3, 6.0 s | [Strings/Viola Section/susvib/ViolaEns_susvib_B2_v1_1.wav](https://github.com/sgossner/VSCO-2-CE/blob/master/Strings/Viola%20Section/susvib/ViolaEns_susvib_B2_v1_1.wav) | Versilian Studios (Samuel Gossner) | CC0 1.0 |
| `vla/d3.wav` | D3, 6.0 s | [Strings/Viola Section/susvib/ViolaEns_susvib_D2_v1_1.wav](https://github.com/sgossner/VSCO-2-CE/blob/master/Strings/Viola%20Section/susvib/ViolaEns_susvib_D2_v1_1.wav) | Versilian Studios (Samuel Gossner) | CC0 1.0 |
| `vla/d4.wav` | D4, 6.0 s | [Strings/Viola Section/susvib/ViolaEns_susvib_D3_v1_1.wav](https://github.com/sgossner/VSCO-2-CE/blob/master/Strings/Viola%20Section/susvib/ViolaEns_susvib_D3_v1_1.wav) | Versilian Studios (Samuel Gossner) | CC0 1.0 |
| `vla/e3.wav` | E3, 6.0 s | [Strings/Viola Section/susvib/ViolaEns_susvib_E2_v1_1.wav](https://github.com/sgossner/VSCO-2-CE/blob/master/Strings/Viola%20Section/susvib/ViolaEns_susvib_E2_v1_1.wav) | Versilian Studios (Samuel Gossner) | CC0 1.0 |
| `vla/f4.wav` | F4, 6.0 s | [Strings/Viola Section/susvib/ViolaEns_susvib_F3_v1_1.wav](https://github.com/sgossner/VSCO-2-CE/blob/master/Strings/Viola%20Section/susvib/ViolaEns_susvib_F3_v1_1.wav) | Versilian Studios (Samuel Gossner) | CC0 1.0 |
| `vla/g3.wav` | G3, 6.0 s | [Strings/Viola Section/susvib/ViolaEns_susvib_G2_v1_1.wav](https://github.com/sgossner/VSCO-2-CE/blob/master/Strings/Viola%20Section/susvib/ViolaEns_susvib_G2_v1_1.wav) | Versilian Studios (Samuel Gossner) | CC0 1.0 |
| `vc/a3.wav` | A3, 6.0 s | [Strings/Cello Section/susvib/susvib_A2_v1_1.wav](https://github.com/sgossner/VSCO-2-CE/blob/master/Strings/Cello%20Section/susvib/susvib_A2_v1_1.wav) | Versilian Studios (Samuel Gossner) | CC0 1.0 |
| `vc/b2.wav` | B2, 6.0 s | [Strings/Cello Section/susvib/susvib_B1_v1_1.wav](https://github.com/sgossner/VSCO-2-CE/blob/master/Strings/Cello%20Section/susvib/susvib_B1_v1_1.wav) | Versilian Studios (Samuel Gossner) | CC0 1.0 |
| `vc/c2.wav` | C2, 6.0 s | [Strings/Cello Section/susvib/susvib_C1_v1_1.wav](https://github.com/sgossner/VSCO-2-CE/blob/master/Strings/Cello%20Section/susvib/susvib_C1_v1_1.wav) | Versilian Studios (Samuel Gossner) | CC0 1.0 |
| `vc/c4.wav` | C4, 6.0 s | [Strings/Cello Section/susvib/susvib_C3_v1_1.wav](https://github.com/sgossner/VSCO-2-CE/blob/master/Strings/Cello%20Section/susvib/susvib_C3_v1_1.wav) | Versilian Studios (Samuel Gossner) | CC0 1.0 |
| `vc/d3.wav` | D3, 6.0 s | [Strings/Cello Section/susvib/susvib_D2_v1_1.wav](https://github.com/sgossner/VSCO-2-CE/blob/master/Strings/Cello%20Section/susvib/susvib_D2_v1_1.wav) | Versilian Studios (Samuel Gossner) | CC0 1.0 |
| `vc/e2.wav` | E2, 6.0 s | [Strings/Cello Section/susvib/susvib_E1_v1_1.wav](https://github.com/sgossner/VSCO-2-CE/blob/master/Strings/Cello%20Section/susvib/susvib_E1_v1_1.wav) | Versilian Studios (Samuel Gossner) | CC0 1.0 |
| `vc/e4.wav` | E4, 6.0 s | [Strings/Cello Section/susvib/susvib_E3_v1_1.wav](https://github.com/sgossner/VSCO-2-CE/blob/master/Strings/Cello%20Section/susvib/susvib_E3_v1_1.wav) | Versilian Studios (Samuel Gossner) | CC0 1.0 |
| `vc/f3.wav` | F3, 6.0 s | [Strings/Cello Section/susvib/susvib_F2_v1_1.wav](https://github.com/sgossner/VSCO-2-CE/blob/master/Strings/Cello%20Section/susvib/susvib_F2_v1_1.wav) | Versilian Studios (Samuel Gossner) | CC0 1.0 |
| `vc/g2.wav` | G2, 6.0 s | [Strings/Cello Section/susvib/susvib_G1_v1_1.wav](https://github.com/sgossner/VSCO-2-CE/blob/master/Strings/Cello%20Section/susvib/susvib_G1_v1_1.wav) | Versilian Studios (Samuel Gossner) | CC0 1.0 |
| `vctrem/a3.wav` | A3, 6.0 s | [Strings/Cello Section/trem/trem_A2_v1_1.wav](https://github.com/sgossner/VSCO-2-CE/blob/master/Strings/Cello%20Section/trem/trem_A2_v1_1.wav) | Versilian Studios (Samuel Gossner) | CC0 1.0 |
| `vctrem/b2.wav` | B2, 6.0 s | [Strings/Cello Section/trem/trem_B1_v1_1.wav](https://github.com/sgossner/VSCO-2-CE/blob/master/Strings/Cello%20Section/trem/trem_B1_v1_1.wav) | Versilian Studios (Samuel Gossner) | CC0 1.0 |
| `vctrem/c4.wav` | C4, 6.0 s | [Strings/Cello Section/trem/trem_C3_v1_1.wav](https://github.com/sgossner/VSCO-2-CE/blob/master/Strings/Cello%20Section/trem/trem_C3_v1_1.wav) | Versilian Studios (Samuel Gossner) | CC0 1.0 |
| `vctrem/d3.wav` | D3, 6.0 s | [Strings/Cello Section/trem/trem_D2_v1_1.wav](https://github.com/sgossner/VSCO-2-CE/blob/master/Strings/Cello%20Section/trem/trem_D2_v1_1.wav) | Versilian Studios (Samuel Gossner) | CC0 1.0 |
| `vctrem/e2.wav` | E2, 6.0 s | [Strings/Cello Section/trem/trem_E1_v1_1.wav](https://github.com/sgossner/VSCO-2-CE/blob/master/Strings/Cello%20Section/trem/trem_E1_v1_1.wav) | Versilian Studios (Samuel Gossner) | CC0 1.0 |
| `vctrem/e4.wav` | E4, 6.0 s | [Strings/Cello Section/trem/trem_E3_v1_1.wav](https://github.com/sgossner/VSCO-2-CE/blob/master/Strings/Cello%20Section/trem/trem_E3_v1_1.wav) | Versilian Studios (Samuel Gossner) | CC0 1.0 |
| `vctrem/f3.wav` | F3, 6.0 s | [Strings/Cello Section/trem/trem_F2_v1_1.wav](https://github.com/sgossner/VSCO-2-CE/blob/master/Strings/Cello%20Section/trem/trem_F2_v1_1.wav) | Versilian Studios (Samuel Gossner) | CC0 1.0 |
| `vctrem/g2.wav` | G2, 6.0 s | [Strings/Cello Section/trem/trem_G1_v1_1.wav](https://github.com/sgossner/VSCO-2-CE/blob/master/Strings/Cello%20Section/trem/trem_G1_v1_1.wav) | Versilian Studios (Samuel Gossner) | CC0 1.0 |
| `vlnsolo/a4.wav` | A4, 8.0 s | [Strings/Solo Violin/Arco Vib/LLVln_ArcoVib_A4_p.wav](https://github.com/sgossner/VSCO-2-CE/blob/master/Strings/Solo%20Violin/Arco%20Vib/LLVln_ArcoVib_A4_p.wav) | Versilian Studios (Samuel Gossner) | CC0 1.0 |
| `vlnsolo/a5.wav` | A5, 8.0 s | [Strings/Solo Violin/Arco Vib/LLVln_ArcoVib_A5_p.wav](https://github.com/sgossner/VSCO-2-CE/blob/master/Strings/Solo%20Violin/Arco%20Vib/LLVln_ArcoVib_A5_p.wav) | Versilian Studios (Samuel Gossner) | CC0 1.0 |
| `vlnsolo/c5.wav` | C5, 8.0 s | [Strings/Solo Violin/Arco Vib/LLVln_ArcoVib_C5_p.wav](https://github.com/sgossner/VSCO-2-CE/blob/master/Strings/Solo%20Violin/Arco%20Vib/LLVln_ArcoVib_C5_p.wav) | Versilian Studios (Samuel Gossner) | CC0 1.0 |
| `vlnsolo/c6.wav` | C6, 8.0 s | [Strings/Solo Violin/Arco Vib/LLVln_ArcoVib_C6_p.wav](https://github.com/sgossner/VSCO-2-CE/blob/master/Strings/Solo%20Violin/Arco%20Vib/LLVln_ArcoVib_C6_p.wav) | Versilian Studios (Samuel Gossner) | CC0 1.0 |
| `vlnsolo/e5.wav` | E5, 8.0 s | [Strings/Solo Violin/Arco Vib/LLVln_ArcoVib_E5_p.wav](https://github.com/sgossner/VSCO-2-CE/blob/master/Strings/Solo%20Violin/Arco%20Vib/LLVln_ArcoVib_E5_p.wav) | Versilian Studios (Samuel Gossner) | CC0 1.0 |
| `vlnsolo/e6.wav` | E6, 8.0 s | [Strings/Solo Violin/Arco Vib/LLVln_ArcoVib_E6_p.wav](https://github.com/sgossner/VSCO-2-CE/blob/master/Strings/Solo%20Violin/Arco%20Vib/LLVln_ArcoVib_E6_p.wav) | Versilian Studios (Samuel Gossner) | CC0 1.0 |
| `vlnsolo/g5.wav` | G5, 8.0 s | [Strings/Solo Violin/Arco Vib/LLVln_ArcoVib_G5_p.wav](https://github.com/sgossner/VSCO-2-CE/blob/master/Strings/Solo%20Violin/Arco%20Vib/LLVln_ArcoVib_G5_p.wav) | Versilian Studios (Samuel Gossner) | CC0 1.0 |
| `cb/as1.wav` | A#1, 6.0 s | [Strings/Solo Contrabass/SusVib/BKCtbss_SusVib_A#0_v1_rr1.wav](https://github.com/sgossner/VSCO-2-CE/blob/master/Strings/Solo%20Contrabass/SusVib/BKCtbss_SusVib_A%230_v1_rr1.wav) | Versilian Studios (Samuel Gossner) | CC0 1.0 |
| `cb/a2.wav` | A2, 6.0 s | [Strings/Solo Contrabass/SusVib/BKCtbss_SusVib_A1_v1_rr1.wav](https://github.com/sgossner/VSCO-2-CE/blob/master/Strings/Solo%20Contrabass/SusVib/BKCtbss_SusVib_A1_v1_rr1.wav) | Versilian Studios (Samuel Gossner) | CC0 1.0 |
| `cb/c2.wav` | C2, 6.0 s | [Strings/Solo Contrabass/SusVib/BKCtbss_SusVib_C1_v1_rr1.wav](https://github.com/sgossner/VSCO-2-CE/blob/master/Strings/Solo%20Contrabass/SusVib/BKCtbss_SusVib_C1_v1_rr1.wav) | Versilian Studios (Samuel Gossner) | CC0 1.0 |
| `cb/d2.wav` | D2, 6.0 s | [Strings/Solo Contrabass/SusVib/BKCtbss_SusVib_D1_v1_rr1.wav](https://github.com/sgossner/VSCO-2-CE/blob/master/Strings/Solo%20Contrabass/SusVib/BKCtbss_SusVib_D1_v1_rr1.wav) | Versilian Studios (Samuel Gossner) | CC0 1.0 |
| `cb/e2.wav` | E2, 6.0 s | [Strings/Solo Contrabass/SusVib/BKCtbss_SusVib_E1_v1_rr1.wav](https://github.com/sgossner/VSCO-2-CE/blob/master/Strings/Solo%20Contrabass/SusVib/BKCtbss_SusVib_E1_v1_rr1.wav) | Versilian Studios (Samuel Gossner) | CC0 1.0 |
| `cb/fs1.wav` | F#1, 6.0 s | [Strings/Solo Contrabass/SusVib/BKCtbss_SusVib_F#0_v1_rr1.wav](https://github.com/sgossner/VSCO-2-CE/blob/master/Strings/Solo%20Contrabass/SusVib/BKCtbss_SusVib_F%230_v1_rr1.wav) | Versilian Studios (Samuel Gossner) | CC0 1.0 |
| `cb/fs2.wav` | F#2, 6.0 s | [Strings/Solo Contrabass/SusVib/BKCtbss_SusVib_F#1_v1_rr1.wav](https://github.com/sgossner/VSCO-2-CE/blob/master/Strings/Solo%20Contrabass/SusVib/BKCtbss_SusVib_F%231_v1_rr1.wav) | Versilian Studios (Samuel Gossner) | CC0 1.0 |
