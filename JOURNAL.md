---
title: "Banana Split"
author: "nandini"
description: "An ortholinear split 75% keeb"
created_at: "06-29-2025"
---

# July 3

~ 1.5 hours

Set up a preliminary layout. I think I’ll probably do something similar to the mistel barocco; so it’ll be 60% ish, tentable, and have a puzzle piece feel. Originally thought of using two separate pico’s but that would require two separate bluetooth modules for communication, increasing overall cost. I will most likely use nice!nano’s instead. Also worked a bit on the matrix today:

[ MATRIX IMAGE ]

For space conservation I’m thinking of creating an outward protrusion down and out in a slope to house mcus. Will likely cover this section with wood for wrist support.

# July 4

~ 4 hours

Today I created a tentative starter list of materials:
Nice!nano x 2
Cherry mx brown switches x 83
PBT OEM keycaps for mx style switches x 83
EC11 Rotary Encoder x 1 (might later look into a keycap set that includes the cap for the encoder)
Encoder Cap x 1 

Cool thought for later: a magnet in the hollow of the case for ease of use when the two halves of the keeb are connected.

[ SCHEMATIC IMAGE ]

Also! Schematic almost finished! I was a little worried about the difference between using the high frequency vs low frequency pins but there shouldn’t be too much of a difference in terms of firmware and performance.

# July 5

~ 3 hours

So due to some incorrect file paths I had to abandon hierarchical sheets :(( I ended up just splitting the two halves of the keeb into two separate kicad folders. It also took a little bit of time but I finalized all footprints. (links here) I also debated using a power switch, hoping to rely on ZMK for low power functions because I didn’t want to get rid of any more keys. But I ended up using one anyway because it seemed like a more direct method for power control.

# July 6

~ 3 hours

RAAAHH got started on pcb finally. I finished the left side first, aligning everything from the dxf file given from kle. I’ve heard a lot of ppl mention the use of ground pours, especially for keeb pcbs. However, since they are heat sinks, it’ll probably mess with me when I go to solder my tht components, so I opted to just fully route the whole thing. I ended up actually sacrificing keys for a minimalist design. So sad. I may add acrylic to make the section with mcu visible, so there isn’t any meaningless gap.

# July 7

~ 3.5 ish hours

Right half of keeb pcb finished! Worked on edge cuts so the two halves fit. 
