# Slicing Basics

A **slicer** turns your 3D model into G-code — the step-by-step
instructions your printer follows. You don't need to learn every
setting; a handful of them decide nearly everything about a print.

## The settings that actually matter

**Layer height.** How thick each layer is. 0.2 mm is the everyday
default — a good balance of speed and looks. 0.12 mm for visible detail
(slower), 0.28 mm for fast drafts. Thinner layers look smoother but
every halving roughly doubles print time.

**Infill.** The interior structure — the slicer doesn't print parts
solid. 15–20% infill is plenty for most things; going to 100% rarely
makes parts meaningfully stronger and wastes time and plastic. For
strength, add **walls** (perimeters) instead — 3–4 walls beat extra
infill for most functional parts.

**Supports.** Temporary scaffolding for overhangs steeper than about
45°. The slicer generates them; you snap them off after. Orienting the
model to minimize overhangs beats printing lots of supports.

**Temperatures.** Nozzle and bed temperatures come from the filament,
not the printer — start with the range printed on the spool (PLA:
~200°C nozzle / 60°C bed) and adjust in 5° steps if you have adhesion
or stringing trouble.

**Print speed.** Defaults are sane. Slow down for detailed or small
parts; don't chase the manufacturer's maximum speed until your basic
prints are clean.

**Brim / raft / skirt.** Helpers for bed adhesion. A **brim** (a flat
rim around the part's base) is the useful one — it gives small parts
more grip area. A **raft** (a plastic mat under everything) is rarely
needed on a modern printer. A **skirt** (an outline that doesn't touch
the part) just primes the nozzle.

## Habits that save filament

- **Preview before printing.** The slicer's layer preview shows
  supports, infill, and first-layer placement. A 30-second look catches
  floating models and missing supports.
- **Change one thing at a time.** If a print fails, adjust a single
  setting and reprint. Changing five things teaches you nothing about
  which one fixed it.
- **Keep a note of what works.** Filament brand, temperatures, and the
  profile name that printed well. Future you will thank present you.

## Common slicers

OrcaSlicer, PrusaSlicer, Bambu Studio, and Cura are all free and
capable. They share the same concepts above — learning one teaches you
the vocabulary for all of them. Start with whichever your printer's
maker recommends.

Related: [Your First Print](first-print.md),
[Troubleshooting](troubleshooting.md).
