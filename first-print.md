# Your First Print

Go from a boxed printer to a finished object. Use PLA — it's the most
forgiving plastic. Budget an unhurried hour or two; rushing the setup
is how first prints fail.

## 1. Assemble and check

Follow the manufacturer's assembly steps. Then check the physical
basics before powering on:

- Frame screws are snug, nothing wobbles.
- Belts are taut — they should twang faintly when plucked, not sag.
- The print head moves smoothly by hand along all axes (power off).

**Check:** nothing loose, nothing grinding. Most "mystery" print
defects trace back to a wobbly frame or a slack belt.

## 2. Load filament

Heat the nozzle to the filament's temperature (about 200°C for PLA —
your printer's menu has a preheat option). Feed the filament in until
melted plastic flows from the nozzle, then stop. A little ooze is
normal; wipe it off.

**Check:** a steady thin strand comes out, not curls or nothing.
If nothing flows, the nozzle may be too cold or the filament isn't
seated in the extruder gears.

## 3. Level the bed and set the gap

Run the printer's auto bed leveling if it has it. Then set the nozzle
gap (z-offset): the nozzle should just barely grip a sheet of paper
slid underneath — you feel slight drag. Too high and the first layer
won't stick; too low and the nozzle drags through the plastic.

**Check:** the paper-drag test at several points on the bed. This one
adjustment decides more first prints than anything else.

## 4. Slice a starter model

Open your slicer, load a simple calibration model (a calibration cube
or the classic benchy boat — both free on Printables and Thingiverse),
keep every setting at the defaults for PLA, and export the G-code to
the printer (SD card, USB, or Wi-Fi depending on your machine).

**Check:** the slicer's preview shows the model sitting flat on the
build plate, not floating or sunk into it.

## 5. Print and watch the first layer

Start the print and watch the first layer go down. It should lay flat,
even lines that merge into a solid sheet. If it's not sticking, stop
the print now — a bad first layer never recovers.

**Check:** the first layer is smooth and stuck. If it peels up, clean
the bed (soap and water, then isopropyl alcohol), re-check the gap,
and try again. See [Troubleshooting](troubleshooting.md) if it keeps
failing.

## 6. Let it finish, then remove

Don't touch the printer mid-print — vibrations show up as layer lines.
When it finishes and the bed cools, the part usually pops off with a
gentle flex or a scraper. If it won't budge, wait for full cooldown;
forcing it can damage the build surface.

**Check:** your finished object. Compare it to the model — clean
layers, no spaghetti, no warping off the bed. Small imperfections on a
first print are normal and fixable.

## What to try next

- [Slicing Basics](slicing-basics.md): the settings worth learning.
- [Troubleshooting](troubleshooting.md): when a print goes wrong.
- [Filament in Plain Language](filament-guide.md): what to try after PLA.
