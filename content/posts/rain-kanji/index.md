+++
title = '雨 (rain), in chrome'
date = 2026-11-19
tags = ['3d', 'blender']
summary = 'The Japanese character for rain, modelled in polished chrome and spinning, with water beaded on it like a freshly waxed car.'
cover.image = 'rain-wet.jpg'
cover.alt = 'Chrome 3D rendering of the kanji 雨 with water beads'
cover.hiddenInSingle = true
+++

雨 (*ame*) is the Japanese character for rain. Here it is as polished chrome with
water beaded on it, the way rain sits on a freshly waxed car. It turns left to right
at 0.75 turns per second.

{{< loopvideo src="rain-wet.mp4" poster="rain-wet.jpg" caption="0.75 turns per second, with water beads" >}}

The first version was dry and spun twice as fast:

{{< loopvideo src="rain-dry.mp4" poster="rain-dry.jpg" caption="1.5 turns per second, dry" >}}

Both were made in [Blender](https://www.blender.org/) 5.3 and rendered with Cycles.
The character is the Noto Sans CJK JP Bold glyph, extruded and bevelled, lit by long
studio softboxes so the chrome picks up streaky highlights. The water is a few hundred
refracting beads in mixed sizes, placed so none overlap or hang off a stroke edge.
