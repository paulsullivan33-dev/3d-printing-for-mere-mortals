# Multicolor Printing: The Gotchas

Multicolor printing is how you get a red-and-white logo or a
multi-part assembly in one job instead of several. It works — but it
has real costs that the product photos don't show. Here's the honest
version.

## How it works

A filament changer (Bambu AMS, Prusa MMU, and similar) holds several
spools and swaps between them mid-print. Each swap goes: retract the
old color, load the new one, and **purge** — extrude a blob of plastic
to flush the old color out of the nozzle so it doesn't streak into the
new one.

Tool changers (a printer with multiple independent print heads) skip
the purge by keeping each color in its own nozzle. They're faster and
cleaner but cost much more.

## Gotcha 1: purge waste is real

Every color change throws away plastic. On a print with a few swaps
per layer, the **purge block** — the sacrificial tower the printer
builds to flush colors — can outweigh the actual object. A small
multicolor keychain can eat more filament in purge than in the part.

What helps: purge *into the infill* (the slicer can hide purge inside
the object's interior), reduce purge volumes once you've verified
colors are clean, and design with fewer color changes per layer.

## Gotcha 2: time multiplies

Each swap takes real time — retract, load, heat-stabilize, purge,
resume. A print with hundreds of swaps can take three to five times
longer than the same object in one color. An overnight print becomes a
two-day print. Plan accordingly.

## Gotcha 3: color bleed vs. waste is a tradeoff

Purge too little and the old color streaks into the new one
(pink where you wanted white). Purge more and the waste pile grows.
There is no setting that gives you zero bleed and zero waste — you're
always choosing where on that line to sit. Light-to-dark transitions
need less purge than dark-to-light.

## Gotcha 4: more spools, more jams

Every spool is another filament path that can tangle, jam, or run out
mid-print. Cardboard spools and odd-sized spools jam in some changer
units — respooling onto compatible spools is a chore you'll do more
than once. Keep spools dry and neatly wound; a tangled spool ruins a
print at 2 a.m. just as effectively as a clogged nozzle.

## Gotcha 5: different plastics don't always bond

Multicolor usually means one plastic type in several colors (all PLA,
for example). Mixing *materials* — PLA with PETG, say — in one print
is a different game: they don't bond well to each other, and the part
can split along the material boundary. Multi-material is possible but
it's expert territory, not a checkbox feature.

## Gotcha 6: design for fewer swaps

The real skill isn't the hardware — it's the design. Group same-color
regions together, keep color changes at the same height when you can,
and ask whether that tiny accent color is worth fifty extra swaps.
Sometimes printing parts separately in different colors and gluing
them is faster, cleaner, and cheaper than one multicolor job. Painting
is also a legitimate answer.

## Is it worth it?

For display pieces, logos, and gifts: yes, the results look great and
nothing else does quite the same thing. For functional parts: usually
not — single color is faster, cheaper, and just as strong. Go in
expecting the waste and the time, design around the swaps, and
multicolor earns its keep.

Related: [Slicing Basics](slicing-basics.md),
[Filament in Plain Language](filament-guide.md).
