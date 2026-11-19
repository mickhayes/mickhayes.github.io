+++
title = 't → て, in chrome'
date = 2026-11-19
tags = ['3d', 'blender']
summary = 'A Gaelic lowercase t flowing into the hiragana て (te) and back, in polished chrome with water beaded on it.'
cover.image = 't-te-morph.jpg'
cover.alt = 'Chrome 3D Gaelic lowercase t with water beads'
cover.hiddenInSingle = true
+++

The Gaelic lowercase t, a bar over a curve, looks remarkably like the hiragana て
(*te*). Here one flows into the other and back, in polished chrome with water beaded
on it like a freshly waxed car, turning slowly at 0.3 turns per second.

{{< loopvideo src="t-te-morph.mp4" poster="t-te-morph.jpg" caption="Gaelic t → て → t, two turns per loop" >}}

Made in [Blender](https://www.blender.org/) 5.3 and rendered with Cycles. The t is
from Uncial Antiqua and the て from Noto Sans CJK JP. Each letter's outline is turned
into a distance field, and blending the two fields gives a shape that changes smoothly
from one letter to the other while staying in one piece. The water beads keep their
places on the surface, shrinking away where an edge passes and swelling where the
shape arrives.
