# SMDrumsWithSalamander

255 samples that answer all **26 inputs** of the electronic drum kit LARG plays: SM Drums
(Scott McLean) and the Salamander Drumkit (Alexander Holm), under their own names from the
two mirrors this kit is assembled out of.

**This is a remix, assembled for [LARG](https://github.com/michalslonina/lustiger)** — the
drum engine loads one directory and every pad of the kit answers. It is not a release of
either pack, the selection is not the authors', and it carries no endorsement from them.
Every sample was recorded by the people credited below; what this repository adds is a
choice of which ones and a name for each.

## Why this repository exists

The layout these were selected for is a 26-input electronic kit: kick, snare, snare rim,
seven hi-hat states, splash, four toms with rims, a two-zone ride and two two-zone crashes.
No free pack covers it whole. This kit does, at a fixed depth, so a sampler can load a
directory and have every pad make a sound.

It is a **selection**, not a new recording: not one byte of audio was altered. It is not the
authors' work and not their repository; the two mirrors below are the canonical copies of the
packs, and the authors' own downloads are more canonical still.

- [drum-samples-smdrums](https://github.com/michalslonina/drum-samples-smdrums) — 3,614 samples
- [drum-samples-salamander](https://github.com/michalslonina/drum-samples-salamander) — 536 samples

## Coverage

Four velocity layers and up to four round robins per input — 4×4 where the source is that
deep, fewer only where the source is thinner. `vl` is the source's own layer index, so
gaps in the numbering are the layers this pool did not take.

| code | input | files | vl×rr | source |
|---|---|---|---|---|
| 36 | Kick | 16 | 4×4 | smdrums `kick1_hit` |
| 38 | Snare | 8 | 4×2 | smdrums `snare1_hit` |
| 40 | Snare rim | 8 | 4×2 | smdrums `snare1_rimshot` |
| 42 | Hi-hat | 16 | 4×4 | smdrums `hihat_closed` |
| 22 | Hi-hat half-open | 16 | 4×4 | smdrums `hihat_half` |
| 23 | Hi-hat 3 | 16 | 4×4 | smdrums `hihat_loose` |
| 24 | Hi-hat 4 | 16 | 4×4 | smdrums `hihat_open` |
| 44 | Hi-hat pedal | 16 | 4×4 | smdrums `hihat_foot` |
| 46 | Hi-hat open | 16 | 4×4 | smdrums `hihat_open` |
| 26 | Hi-hat open 2 | 16 | 4×4 | smdrums `hihat_open` |
| 21 | Splash | 8 | 2×4 | salamander `splash1_hit` |
| 48 | Tom 1 | 16 | 4×4 | smdrums `tom1_hit` |
| 50 | Tom 1 rim | 16 | 4×4 | smdrums `tom1_hit` |
| 51 | Ride | 16 | 4×4 | smdrums `ride1_bow` |
| 53 | Ride bell | 16 | 4×4 | smdrums `ride1_bell` |
| 59 | Ride edge | 7 | 2×4 | salamander `ride2_edge` |
| 45 | Tom 2 | 16 | 4×4 | smdrums `tom2_hit` |
| 47 | Tom 2 rim | 16 | 4×4 | smdrums `tom2_hit` |
| 49 | Crash | 16 | 4×4 | smdrums `crash1_edge` |
| 55 | Crash edge | 16 | 4×4 | smdrums `crash1_edge` |
| 43 | Tom 3 | 16 | 4×4 | smdrums `tom3_hit` |
| 58 | Tom 3 rim | 16 | 4×4 | smdrums `tom3_hit` |
| 41 | Tom 4 | 16 | 4×4 | smdrums `tom4_hit` |
| 39 | Tom 4 rim | 16 | 4×4 | smdrums `tom4_hit` |
| 57 | Crash 2 | 16 | 4×4 | smdrums `crash2_edge` |
| 52 | Crash 2 edge | 16 | 4×4 | smdrums `crash2_edge` |

18 distinct recordings serve those 26 inputs. Six inputs are deliberately **substituted**,
because the sample they would need was never recorded; `KIT.csv` marks each row:

| input | what it plays | why |
|---|---|---|
| Tom 1–4 rim | that tom's head | SM Drums records no tom rim; a rim hit is a head hit |
| Crash edge | the crash body | SM Drums records one articulation per crash |
| Hi-hat open 2 | Hi-hat open | SM Drums records one open position |

The pad still answers — it sounds like the head, the crash body, the single open position.
Substitution is a manifest fact, not a silent duplicate, and a sampler that wants a distinct
sound for those six must source it elsewhere.

## Licence

Two grants, one per origin; `PROVENANCE.csv` names the one that applies to each file. No
licence is claimed over this repository as a whole.

**SM Drums — 240 files.** The authors publish **no licence document**: the upstream
repository has no `LICENSE` file and none accompanies the download. The grant relied on is
the project announcement:

> ALL of the content on this website is for FREE royalty free use by anyone for anything.

Source: <https://www.kvraudio.com/forum/viewtopic.php?p=6072198>

This repository does not claim SM Drums is in the public domain and does not relicense it.

**Salamander Drumkit — 15 files — CC BY-SA 3.0.**
<https://creativecommons.org/licenses/by-sa/3.0/> — full text in [`LICENSE`](LICENSE).

The two origins sit side by side unmodified, which CC BY-SA 3.0 calls a *Collection* and
explicitly does not treat as an Adaptation, so the ShareAlike term stays with the salamander
files and does not reach the smdrums ones. [`NOTICE.md`](NOTICE.md) quotes the definitions
and spells out the split.

## Attribution

Everything audible here was recorded by someone else. This repository adds no authorship of
its own: it selects, copies and renames. Which grant a given file is under is stated per
file in [`PROVENANCE.csv`](PROVENANCE.csv), and both grants are set out in
[`NOTICE.md`](NOTICE.md).

**SM Drums** — 240 of the 255 files

| | |
|---|---|
| Title | SM Drums |
| Authors | **Scott McLean** — drums; engineered and recorded every drum and cymbal sample. **Tod Stillwell** — edited the SMDrum samples; co-authored the Sforzando user guide. **Suleiman Ali** — created the SM Drums web site. **D. Smolken** — SFZ programming; co-authored the Sforzando user guide. |
| Source | <https://github.com/sfzinstruments/SMDrums> · <https://smmdrums.wordpress.com/> |
| Announcement | <https://www.kvraudio.com/forum/viewtopic.php?p=6072198> |
| Licence | **None published.** The project states: "ALL of the content on this website is for FREE royalty free use by anyone for anything." |

**Salamander Drumkit** — 15 of the 255 files

| | |
|---|---|
| Title | Salamander Drumkit |
| Author | **Alexander Holm** — built and recorded the kit in 2009. The upstream README names no other author or contributor. |
| Source | <https://archive.org/details/SalamanderDrumkit> |
| Licence | **CC BY-SA 3.0** — <https://creativecommons.org/licenses/by-sa/3.0/> · full text in [`LICENSE`](LICENSE) |

The SM Drums names came from the pack's own credits; the Salamander attribution follows the
TASL quartet — title, author, source, licence — that CC BY-SA 3.0 requires.

## Links

- SM Drums site: <https://smmdrums.wordpress.com/>
- SM Drums announcement: <https://www.kvraudio.com/forum/viewtopic.php?p=6072198>
- SM Drums upstream: <https://github.com/sfzinstruments/SMDrums>
- Salamander Drumkit: <https://archive.org/details/SalamanderDrumkit>
- The packs these were selected from: [smdrums](https://github.com/michalslonina/drum-samples-smdrums), [salamander](https://github.com/michalslonina/drum-samples-salamander)

## What is here

| | |
|---|---|
| samples | 255 (18 distinct recordings, 26 inputs) |
| source | 347.4 MiB — 24-bit stereo; 44.1 kHz from SM Drums, 48 kHz from Salamander |
| Opus | 25.9 MiB — 7.4 % of the source |
| decoded as i16 | 231.5 MiB |
| decoded as f32 | 463.0 MiB |
| audio | 1,367.6 s across the 255 files |
| longest sample | 13.00 s (a cymbal tail) |

The decoded figures are the whole pool held in memory as PCM, which is the cost of a
sampler that keeps every layer resident. A streaming consumer needs only the Opus side.

### The tails are not trimmed

Cymbals ring. 103 of the 255 samples run past 4 s, and those 103 hold 174.4 MiB of the
231.5 MiB. Cutting them to 3 s would take the pool to 103.5 MiB — a 55 % saving — and cost
the decay that makes a crash a crash. This repository does not do it: the audio here is the
upstream audio, and a trimmed file is no longer it.

The engine bounds the same cost without touching the files. A kit patch declares
`length_secs` per drum and is baked to exactly `length_secs × sample_rate` frames, so a 13 s
ride can ship here and occupy 3 s in memory. **Cut the tail in the patch, not in the
sample** — a number in the kit is reversible and leaves the recordings intact; a shorter file
is neither.

## Layout

```
source/<name>.wav      the upstream bytes, unmodified
opus/<name>.opus       the Opus twin of every source file, same stem
KIT.csv                input code → sample, one row per input file, with substitutions marked
PROVENANCE.csv         every sample's origin mirror, upstream path, licence and measurements
LICENSE                CC BY-SA 3.0 — the salamander files' licence
NOTICE.md              which grant covers what, and why this is a collection
```

`source/**` is in Git LFS; `opus/**` is committed as ordinary git objects.

## Naming

The pack mirrors' grammar, unchanged:

```
<pack>_<piece>_<articulation>_<perspective>_vl<NN>_rr<N>[_<take>].<codec>
```

`<pack>` is the origin mirror — `smdrums` or `salamander` — so every file in this pool
traces back to the exact sample in the exact mirror, and `vl` and `rr` mean what they mean
there. The grammar is described in full in either mirror's README.

## How it was made

Nothing was re-encoded: the Opus files are the mirrors' own Opus twins, copied. Each source
file was copied and its byte count checked against the mirror's manifest.

The selection is 4 layers × 4 round robins per input, choosing layers evenly across the
source's range so the softest and loudest are always kept, and the first four round robins of
each. Where a sample serves several inputs — a tom head and its rim, a crash body and its
edge — it appears in `source/` once and `KIT.csv` maps both inputs to it.

## Removal

Ask for removal by opening an issue at
<https://github.com/michalslonina/SMDrumsWithSalamander/issues>, or by contacting
`michalslonina` on GitHub. Removal is immediate.
