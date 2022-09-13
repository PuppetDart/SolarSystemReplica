## View Live on: [Codepen](https://codepen.io/puppetdart/full/poVbvKK)

This CSS project intends to bring to represent an approximated replica of the planets of our sun-system.

### Description:

#### 1. Scaled-down metrics:
The numbers & inputs used in this project, are a relative approximation of the values mentioned here: [`NASA`](https://nssdc.gsfc.nasa.gov/planetary/factsheet/planet_table_ratio.html)   
It must be noted that the values of mass, volume, diameter, etc. in the referenced article do not depend on any units/metrics. Rather they are ratios of different planets with respect to earth. These ratios have further been scaled down & adjusted to make them representable.
For example  ---
* **Orbital Period** for respective planets have been scaled down to equivalent seconds:
-- --- -- `1 unit orbital period`  = `10 seconds`
* **Diameter** for respective planets have been scaled down to equivalent pixels:
-- --- -- `1 unit diameter`  = `3.33px`
(& similar scales have been used to determine, **distance from sun** & **speed of rotation.**)

#### 2. Scaled-down sun:
By default, the sun is scaled down to 2/3^rd^ its relative size for better comprehension. Yet to include even more space & planets into the visible area, one may scale down the sun to 1/6^th^ its relative size using the upper left controls.

### Features:

#### 1. Change solar-system size scale:
Besides the option to change the size of the sun, one may also choose to scale down the size of the solar system to 60%, a feature also provided in the upper left controls alongside animation-play/pause controls.

#### 2. Play/Pause animation:
One may choose to pause the animation and freeze the planets at their current position & also continue from the same when played.

#### 3. Planet Spotting menu:
At the centre bottom of the page is a list of planets on display. One may click any number of names & spot them in motion as well as pause state. This becomes particularly helpful when the sun & the solar system have been scaled down to the max making small planets like mercury & pluto almost invisible.

### How may I replicate this?
It's just a 1-day job. One may concentrate on the following CSS topics:
1. `box-shadows`: for planetary rings & suns' glowing animations
2. `before/after pseudo elements`: subjective to your personal use
3. `transform properties` + basic `key-frame animations`: for revolution/rotation of all planetary objects
4. `CSS variables`: for making key-frame animations reusable for each planet