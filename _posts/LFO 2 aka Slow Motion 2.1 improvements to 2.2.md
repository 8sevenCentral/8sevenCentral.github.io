---
tags: eurorack🎛️
dg-publish: true
---
update the power jack footprint
update the I/O jack footprint
LED indicator is missing
Overlapping footprints on the leds and pots
See if you can use 2n5089 instead of 2n3904. you have a lot of 5089s
add gnd via stitching
label top led as blue
label botton led as red
no value indicator for pots
no version on the footprint
make the diode footprints more clear
I have a bunch of 10k pots - can i use 10k instead of 100k? 
	- doesnt matter 10k pots work in the sim
the power jack is very close to the gnds of the cv jacks - shift the power jack up a bit
make the electrolytic cap pads bigger
make the I/O jacks oval pads with tighter tolerance
increase the width of the power trace
make vias as close as possible to component pad
add teardrops

debug: try pulling r26 or r25 to remove the cv control to see if it oscillates then

might need to use an LM324 instead of the TL074


![[LFO2.txt]]
![[LFO2-1 (1).txt]]
![[LFO2-2 (1).txt]]
![[LFO2-3 (1).txt]]


<https://www.reddit.com/r/synthdiy/comments/1hs24lw/oscillator_works_in_simulation_but_not_irl/>

<https://www.davidhaillant.com/simple-vco-update-1-0/>

![[Pasted image 20250103103724.png]]

<https://electro-music.com/wiki/pmwiki.php?n=Schematics.NicolasSuperSimpleVPerHzVCO>
![[Pasted image 20250103103737.png]]


- [ ] Use this chip for the LFO <https://cabintechglobal.com/ssi2140>
- [ ] Breaboard out lfo w diode clamping 
