# ofxBoidsSinger
---
by s373.net/x art codex studios
***


Ported from boids package for max/msp/jitter 051219

Using version with attraction points addendum insertion by a.sier
___
Licensed under Gnu GPL License.

Refer to the accompanying COPYING file.

---
ofxBoidsSinger is free for non-commercial use.

Developed by a.sier / jasch, adapted from boids by eric singer

(c) 1995-2003 Eric L. Singer

Free for non-commercial use.
***
![boids-singer](documentation/boidsDSC01963.jpg)
___
```
/*
	boids package for max/msp/jitter 051219
	(universal binary version 060828)


	  Boids............................................. by eric singer
	  boids2d, boids3d.................................. by jasch & andré sier
	  jit.boids3d, jit.boids2d, xray.jit.boidsrender.... by wesley smith

	(c) 1995-98 Eric L. Singer (eric@ericsinger.com)
	3d adaptation 08/2005 by a. sier / jasch
	jitter adaptation 12/2005 by w. smith

	boids package released under Gnu GPL license.
	please refer to the accompanying COPYING file.
*/



Based on Simon Fraser's implementation of Craig Reynolds' Boids algorithm.
Boids is free for non-commercial use

Boids is a bird flight and animal flock simulator. It is based on the same algorithm which was used in Jurassic Park for the herding dinosaurs.
Boids takes an integer argument which is the number of boids. Each time Boids receives a bang, it calculates and outputs the new positions of the boids. The output consists of thew coordiantes for each boid, the number and type depending on the mode.

The flight parameters can be changed with messages. Use the 'dump' message to output a list of the current parameter settings.

For more information about the Boids algorithm, see Craig Reynolds' Web site at "http://reality.sgi.com/employees/craig/boids.html".


UB notes (version 1.1 / 20070125):
	- changed flock structure to bflock. conflicts with fcntl.h:398
	- added set messages to externals (set pos, set dir, set speed, set invert speed)
```
---
It's easy to distinguish between generic Boids, Singer Boids. Refrain from using Singer Boids commercially.

Use this repository or email astronaut at s373 dot net.

Issues, example patches and programs are welcomed.

---

2020.3107671 / somewhere in GMTz
