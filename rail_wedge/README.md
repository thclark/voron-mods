# Rail Wedge

This is a wedge designed for emergency use when a manufacturer has sent you voron profiles with a v slot instead of the square slot profile.

The problem with v slot frame extrusions is that the MGN9 rails have about the same width as the slot profile, making it impossible to stably bolt them down flat to the profile.

### Limitations

Using this approach does work, and it is possible to get a well sorted frame but you must bear in mind hte following drawbacks:

- Filling in this way makes it very difficult to align the rails, you have to take a lot of care
- It makes the build very finicky in terms of getting the nuts aligned under the strips
- If using two MGN9s (instead of the MGN12 mod) on the X axis, its nearly impossible to get the printhead well aligned.

A couple of extra fiddly hours in the build is one thing, but the alignment of the printhead so that it stays perfectly level int eh X direction is quite another and for that reason **I storngly recommend you do the MGN12 X Axis mod which will negate the need for these infills on that axis**.


### Saving money

Don't buy V slot profiles to save money. This is intended as an emergency fix for people (like me!) who've bought the wrong thing and can't return it.

Vorons are incredibly expensive machines, if you're in the territory of doing this to try and make your build cheaper, first consider whether a voron is actually affordable for you. I know this statement won't make me popular in the voron community, but a Prusas is half the cost and much more reliable, so if you're on the edge about whether you can afford it or not, please consider that carefiully.

If your heart is set on a VORON but your wallet is tight, **the frame is not the place to be saving**. Some other ways:

- Buy a full kit rather than self-sourcing, it always works out cheaper (**trust someone who self sourced!). The cheap blurolls style kits seem to be a bit of extra work but still be just fine and the chinese manufacturers now seem to have the correct frame profiles.
- Don't buy the perspex enclosure, instead make your own out of correx or card (this is a very easy thing to upgrade much later)
- Don't buy the front status touchscreen / dial control, it's not essential and you can use your laptop just fine
- Buy a limited amount of square slot for the frame members that host rails, and buy V for the rest (*although this will look like a dogs breakfast and require access to the tooling required to make your own frame, so I don;t recommend it*).
 
Any one of those tips should save more than the cost difference between V and square slot frame profiles!

### Printing

You may need 4-5 iterations to get the printing of these exactly right. They essentially need to be a precision component because they need to fit flush into the slot, so getting that right will be specific to your printer (e.g. how well Z calibrated it is makes a difference).

I iterated the geometry for this, printing at a constant 0.2mm layer height.

You won't iterate the geometry, but you can vary the flow rate multiplier, and/or make subtle variations of layer height, until you have a setup that prints a wedge that fits well.

By "fits well", I suggest aiming for the wedge to sit 0.01mm proud of the extrusion (with no rail present). A small amount of compression as the rail is tightened will provide a full bed for the rail.

There should be no gap - and certainly no plastic - visible once the rail is tightened.

PLA or ABS will be fine, they're not going to get warm. 

