# What, why

This repo contains documentation of Chamberlain LiftMaster Security+ wired garage door opener. I couldn't find solid schematics / understanding online, so I thought I would document it.

# Meat and potatoes

See schematic image for info.

There appears to be some sort of DC voltage ~20V, with some sort of pulse modulated onto it.

The garage door is a simple switch shorting the wires (w/o any resistance).

The light circuit puts an electrolytic capacitor of 1uF, 50V across the DC voltage.

The lock circuit is similar to the light ciruit, but with a 22uF, 50V cap.
