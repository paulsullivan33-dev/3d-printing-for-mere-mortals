# How 3D Printing Works

A 3D printer builds objects by stacking thin layers of melted plastic.
Think of a precise robot holding a hot glue gun, drawing one layer,
moving up a fraction of a millimeter, and drawing the next — hundreds
or thousands of times until the object stands complete.

The common home method is called **FDM** (fused deposition modeling).
Almost everything in these guides assumes FDM.

## The parts that matter

**Filament** is the raw material: a spool of plastic string, usually
1.75 mm thick. The printer pulls it in, melts it, and pushes it out.
Different plastics behave differently — see
[Filament in Plain Language](filament-guide.md).

**The extruder** grips the filament and feeds it forward. Two styles:
*Bowden* (the motor sits on the frame and pushes filament through a
tube) and *direct drive* (the motor rides on the print head). Direct
drive handles flexible filament better; Bowden is lighter and common on
budget printers.

**The hot end and nozzle** melt the plastic (around 200°C for common
plastics) and squeeze it out through a tiny hole — usually 0.4 mm wide.
That hole size sets the detail level: smaller nozzle, finer detail,
slower print.

**The build plate** is the surface the object sticks to while printing.
It is usually heated (around 60°C for common plastics) to help the first
layer grip. A clean, level plate is the difference between a print that
works and a pile of spaghetti — see [Your First Print](first-print.md).

## Layers and orientation

Because objects are built bottom-up in layers, **orientation matters**.
A part printed standing up is weaker between layers than the same part
printed lying down — layers can separate under stress along the layer
lines. When something needs strength, orient it so the stress runs
*along* the layers, not *across* them.

**Overhangs** are parts of the model that stick out sideways with
nothing underneath. Plastic can't print on air past about 45 degrees,
so steep overhangs need temporary **supports** — thin scaffolding the
slicer adds and you snap off afterward. Designing or orienting to avoid
supports saves time and filament.

## From file to object

1. You get a **model** — a 3D file, usually `.stl` or `.3mf`, downloaded
   or designed yourself.
2. A **slicer** program converts it into **G-code**: the literal
   move-by-move instructions for your printer (temperatures, speeds,
   paths). See [Slicing Basics](slicing-basics.md).
3. The printer follows the G-code, layer by layer, until done.

That's the whole pipeline: model → slicer → printer → object. Every
guide here is about making one of those steps go smoothly.

## Sources

- [Prusa: 3D printing handbook concepts](https://help.prusa3d.com/)
- [All3DP: beginner guides](https://all3dp.com/)
