# evo_kawari_twist
PCB to rotate a Kawari large board to make the mini HDMI port more accessible. Intended for use with the EVO64

This board rotates your VIC-II Kawari large board through 90º such that the mini-HDMI connector is more accessible to the left of the Kawari rather than to the back.
It's a four-layer PCB, and most of the copper is ground planes to try to shield the composite video LUMA and CHROMA signals from the fast-switching digital signals - rmr and auro have both expended a lot of effort to keep the video as clean as possible. I don't want to undo all that by running the video signals alongside the clocks.

This was knocked together very quickly, and so has some shortcomings:
- If your VIC-II position is populated with a ZIF socket, it will be tough, or impossible, to install this board directly into the ZIF socket. The workaround is to put a regular socket in the ZIF socket, latch that in place, and then install the Kawari Twist.
- The mounting hole (intended for use with a shortened M3 nylon standoff) isn't in the best position.
- There is a clearance problem inside a C64 breadbin case - I ended up soldering the Kawari directly to the PCB rather than using a socket. If you don't have a ZIF socket, then you'll have more clearance and won't have to take this rather drastic step.

COPYRIGHT: There is no copyright. Knock yourselves out.
