# Troubleshooting

Prints fail. That's normal — even experienced owners get failures.
Nearly every failure is one of the handful below. Match the symptom,
try the fix, change one thing at a time.

## First layer won't stick

The most common failure. The plastic curls up or drags behind the
nozzle instead of lying flat.

- **Bed isn't clean.** Fingerprints kill adhesion. Wash with soap and
  water, then wipe with isopropyl alcohol.
- **Nozzle gap wrong** (mostly older printers — modern ones set this
  automatically). Too high and plastic can't grip; re-do the paper-drag
  test from [Your First Print](first-print.md).
- **Bed too cool.** Make sure it's actually reaching the filament's
  bed temperature (60°C for PLA).
- **Drafts.** A breeze across the bed (AC vent, open window) cools the
  plastic mid-layer. Shield the printer or move it.

## Stringing (thin hairs between parts)

The nozzle oozes while traveling. Usually temperature or retraction:

- Drop nozzle temperature 5–10°C.
- Check that retraction is enabled in the slicer (it pulls filament
  back during travel moves).
- Damp filament also strings — dry the spool if stringing appears
  suddenly on a previously fine setup.

## Layer shifts (print suddenly offsets sideways)

Something moved that shouldn't have:

- **Loose belts** are the usual cause — re-tension them.
- Something blocking the print head's path (a curled-up print, a tool
  left on the frame).
- Printing far too fast for the printer's mechanics.

## Clogged nozzle (thin or no extrusion)

- Do a **cold pull**: heat the nozzle, push filament in, cool to ~90°C,
  then yank it out — it drags debris with it.
- If that fails, swap the nozzle. Nozzles are cheap wear items; don't
  mourn them.

## Warping (corners lift off the bed)

The plastic shrinks as it cools and pulls the corners up. Common with
ABS/ASA, rare with PLA:

- Enclosure or at least draft protection.
- Brim for more grip area.
- Right bed temperature for the filament.

## Spaghetti (a bird's nest of plastic)

The print detached mid-print and the nozzle kept extruding into air.
Cause is usually one of the adhesion issues above — the spaghetti is
the symptom, not the disease. Clean up, fix adhesion, reprint.

## When to stop and ask

If the same failure survives three rounds of fixes, stop changing
settings and get a second pair of eyes: a photo on r/3Dprinting or a
maker forum, with your printer model, filament type, and temperatures.
"PLA, 200/60, first layer won't stick" gets useful answers;
"printer broken pls help" doesn't.

Related: [Slicing Basics](slicing-basics.md),
[Filament in Plain Language](filament-guide.md).
