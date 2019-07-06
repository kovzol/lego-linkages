# Introduction

This is a collection of simple LEGO linkages that can follow a prescribed motion
created with the [LEGO Digital Designer (LDD)](https://www.lego.com/en-us/ldd) 4.3,
a free application for Windows and Mac. (Linux users may want to use [CrossOver](https://www.codeweavers.com/products/crossover-linux)
to run LDD with emulation.) After installing LDD, in case you have problems with the Hinge tools,
consider checking [this page](https://steamcommunity.com/sharedfiles/filedetails/?id=455735233).

The linkages are built from a minimal set of LEGO parts. The focus is on the requirement that all
linkages could be built quickly and their movement could be traced on a piece of
paper. See *author's presentation* with title [Teaching algebra and geometry with LEGO and linkages](https://www.researchgate.net/publication/332303931_Teaching_algebra_and_geometry_with_LEGO_and_linkages)
on further details on the topic.

In LDD one will want to set *View* > *New themes* > *LDD Extended* to make it possible to use
a much wider set of colors for each part.

## The linkages

In all models there is a long red
beam with 15 holes (actually its practicable size is just 14 units) which will be
used to firmly hold the model with the one hand (for right-handed persons this
is the left hand), and a G2 type pen refill which will be inserted in a certain connector
peg, and hold and moved with the other hand, on a sheet of paper. This sheet of
paper will be pressed down by the whole construction, practically by the force
of the one hand.

In some linkages an A2 type refill should be used. It ensures a longer distance between
the sheet of paper and the beam than the G2 type, but assembling the linkage should be performed more carefully.
It may be useful to insert the refill first in the connector peg as deeply as possible,
and only then put the peg in the beam downside-up.

### Compass

The simplest linkage is a compass. It produces a regular circular curve.

![compass](html/Building%20Instructions%20%5Bcompass%5D-images/Step1.png)

[Building Instructions](http://htmlpreview.github.io/?https://github.com/kovzol/lego-linkages/blob/master/html/Building%20Instructions%20%5Bcompass%5D.html).

### Watt's linkage

It is somewhat more difficult... a straight motion to produce. Watt's linkage is an attempt to do that,
with an almost success.

![Watt's linkage](html/Building%20Instructions%20%5BWatt%5D-images/Step6.png)

[Building Instructions](http://htmlpreview.github.io/?https://github.com/kovzol/lego-linkages/blob/master/html/Building%20Instructions%20%5BWatt%5D.html).

### Parallelograms

Parallelograms can give a better understanding on the algebraic properties of the movements. Use the A2 refill to draw with them.

#### 8-5

A circle and a lemniscate will be produced, the latter occurs when the parallelogram turns into an anti-parallelogram.

![Parallelogram-8-5](html/Building%20Instructions%20%5BParallelogram-8-5%5D-images/Step7.png)

[Building Instructions](http://htmlpreview.github.io/?https://github.com/kovzol/lego-linkages/blob/master/html/Building%20Instructions%20%5BParallelogram-8-5%5D.html).

#### 4-8

A circle and an almost-circle (a Cassini-oval) will be produced, the latter occurs when the parallelogram turns into an anti-parallelogram.

![Parallelogram-4-8](html/Building%20Instructions%20%5BParallelogram-4-8%5D-images/Step6.png)

[Building Instructions](http://htmlpreview.github.io/?https://github.com/kovzol/lego-linkages/blob/master/html/Building%20Instructions%20%5BParallelogram-4-8%5D.html).
This linkage will automatically turn into an anti-parallelogram when the pen refill reaches a critical point.

#### Rhombus

Three circles will be produced. This linkage is actually just a sketch, so the pen refill cannot be used to draw anything.

![Rhombus](html/Building%20Instructions%20%5BRhombus%5D-images/Step3.png)

[Building Instructions](http://htmlpreview.github.io/?https://github.com/kovzol/lego-linkages/blob/master/html/Building%20Instructions%20%5BRhombus%5D.html).

### Chebyshev's linkage

This is a kind of generalization of the parallelograms (similarly to Watt's linkage). Use a G2 refill.

#### First approach

Chebyshev's linkage seems to produce a circular arc.

![Chebyshev's linkage](html/Building%20Instructions%20%5BChebyshev%5D-images/Step6.png)

[Building Instructions](http://htmlpreview.github.io/?https://github.com/kovzol/lego-linkages/blob/master/html/Building%20Instructions%20%5BChebyshev%5D.html).

When its grey bars are crossed, the linkage seems to produce a linear motion.

![Chebyshev's linkage, crossed bars](html/Building%20Instructions%20%5BChebyshev-crossed%5D-images/Step6.png)

#### Second approach

Chebyshev's lambda linkage is equivalent to the previous one, but it can create its path
in one movement as well.

![Chebyshev's lambda linkage](html/Building%20Instructions%20%5Blambda%5D-images/Step3.png)

[Building Instructions](http://htmlpreview.github.io/?https://github.com/kovzol/lego-linkages/blob/master/html/Building%20Instructions%20%5Blambda%5D.html).

### Peaucellier's linkage

#### First approach

Peaucellier's linkage provides a linear motion when putting a pen refill in the top-right position.

![Peaucellier's linkage](html/Building%20Instructions%20%5BPeaucellier%5D-images/Step8.png)

See also [Building Instructions](http://htmlpreview.github.io/?https://github.com/kovzol/lego-linkages/blob/master/html/Building%20Instructions%20%5BPeaucellier%5D.html).
A [GeoGebra applet](https://www.geogebra.org/m/dhpbsjdB) is also available that can be changed a little bit
to get exactly the same motion: *l<sub>1</sub>* has to be set to 8 and *l<sub>2</sub>* to 4 units. Then,
by showing the output labelled with *a* we learn that radius of the circle needs to be 3 units.

Unfortunately there exists no LEGO beam with 3 units (that is, with 4 holes), so we need to use a bigger one.
Here a 4 units long beam is used (with 5 holes). The standard kit (explained in the author's presentation
on page 93 in the Shopping list slide) has to be extended by two blue long pins, one white 5 holes beam
and one black 5 holes beam.

Alternatively a 3 units long beam with 4 holes could be printed with a 3D printer instead of the black 5 holes beam,
see [Andreas Kiener](https://www.uni-salzburg.at/index.php?id=205610)'s [contribution](3d-printing/technic-4m.openjscad.txt) as an
[OpenJSCAD](https://openjscad.org/) file.
In addition, instead of the 11-long beam two halves of 6-long beams may also be used (see a
[photo](3d-printing/Peaucellier.jpg)).

#### Second approach

If we omit a possible requirement that the ball pen point needs to intersect the line of the red beam in the same
distance as the two long beams are, then we can build a Peaucellier-type linkage with the standard set as well.
In this case we need only an extra long pin that is a minimal extra cost and no 3D printing is required.
Another benefit is that the drawn line is quite long (about 12 cm).

![Peaucellier's linkage, second approach](html/Building%20Instructions%20%5BPeaucellier2%5D-images/Step4.png)

See also [Building Instructions](http://htmlpreview.github.io/?https://github.com/kovzol/lego-linkages/blob/master/html/Building%20Instructions%20%5BPeaucellier2%5D.html).

### Hart's A-frame

Another linear motion that requires an A2 pen refill. It is the same linkage that is shown in the author's
presentation on page 88 and [was announced in his blog](https://kovz0l.blogspot.com/2018/08/harts-frame-revisited.html).
There is one minor modification, however. There are two 1x1 parts used to get the linkage more fixed,
according to Andreas' idea.

![Hart's A-frame](html/Building%20Instructions%20%5BHartA2b%5D-images/Step7.png)

A big advantage of an earlier version of this linkage is that a much longer straight line can be drawn with it.
However, usually a G2 pen refill is used in most linkages in this project. Another possibility is to use
the black 5 holes beam from the extended set (see Peaucellier's linkage above) instead of the two half 6 holes beam.

Here are the [Building Instructions](http://htmlpreview.github.io/?https://github.com/kovzol/lego-linkages/blob/master/html/Building%20Instructions%20%5BHartA2b%5D.html).

### Hart's inversor

Another element of the kit that produces a linear motion (again, with a G2 pen refill).

![Hart's inversor](html/Building%20Instructions%20%5BHartI%5D-images/Step4.png)

[Building Instructions](http://htmlpreview.github.io/?https://github.com/kovzol/lego-linkages/blob/master/html/Building%20Instructions%20%5BHartI%5D.html).

## Suggested LEGO set to use

Author's presentation suggests the *standard set* (version 2 in the table below). To build the second approach of the Peaucellier cell, one
also needs to have another long pin. Two 1x1 parts can be very useful to minimize vertical movement of the linkage,
that is, to take up the slack. Here is an up-to-date list of the parts of the suggested LEGO set:

| Version | Date     | Beam 15 red 32278 | Beam 11 gray 32525 | Beam 9 yellow 40490 | Half beam 6 gray 32063 | Beam 5 white 32316 | Beam 3 gray 32523 | Beam 1x1 gray 18654 | Long pin blue 6558 | Pin black 2780 | G2 refill | A2 refill | 
|:-------:|:--------:|:-----------------:|:------------------:|:-------------------:|:----------------------:|:------------------:|:-----------------:|:-------------------:|:------------------:|:--------------:|:---------:|:---------:|
| 1       | Dec 2017 |         1         |         2          |         2           |           4            |         3          |         1         |          -          |         2          |     9     |     1     |     -     |
| 2       | Feb 2019 |         1         |         2          |         2           |           4            |         3          |         1         |          -          |          2          |     9     |     1     |     1     |
| 3       | Jun 2019 |         1         |         2          |         2           |           4            |         3          |         1         |          2          |         3          |     9     |     1     |     1     |

# Acknowledgements

* Tomás Recio (for the idea)
* Benedek Kovács (for constructing some of the linkages in LDD)
* Alex Mittermayr (for several ideas on the method how the linkages should be built)
* Andreas Kiener (for minor improvement ideas)
* Chris Sangwin (for several mathematical ideas and concepts from his book [How round is your circle?](https://press.princeton.edu/titles/8624.html))

Many thanks for additional support to:
* Georg Grasegger
* Markus Hohenwarter
* Barbara Lichtenegger
* M. Pilar Vélez
