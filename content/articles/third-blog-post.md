---
title: Prototype Build
description: Assembling the various parts to a completed, working prototype.
img: /third-blog-post.jpg
alt: third blog banner image
date: Mar 2021,
author: Nik Paradis
order: 2
---

## TLDR

Our final prototype has been built. All of the mechanical components are complete, the electrical testing is complete and we are just working on tweaking our design.

## Mechanical Build

In terms of mechanical design, all initial design features and some have been added. Notable changes are two beams supporting the base. One through the middle that supports the base where the panel sits. The other beam attatched the back part of the base which reduces the amount of flexion that occurs at the pivot point of the hot knife. The flexion is especially evident when force is being exterted through the handle (cutting a panel).

We sharpened the blade as much as we could but likely had minimal impact. The big issue we have run into is that the shearing force required is spread across the whole panel, instead of just one point (like the curved blade of a paper cutter).

## Electrical Build

We have lethal amounts of current and voltage, which is great. Our design works. Obviously we need to package this safely under the machine still but that will come. Our target of 150C for blade temperature was reached. In fact, some areas got to 160C. However, as mentioned in the above section, the heat is not strong enough to cut the panel alone. This leads to far too much contact time with the panel and an unrealistic experience (>30s to cut one panel which should be <2s). With our current design, the only real thing we can do is increase the heat. So, that's what we are doing. Trying to up the voltage booster from 90V to 120V and get the blade temp from 150C to 200C. If that doesn't work, the entire design will likely need to be revisited.

In other electrical terms, the LEDs are installed, the software is being programmed on the microcontroller and e-stops are being added in. Working on getting the new boost converter to work and test the new load on the power supply and heating element to see what we get.

## Contraints & Critera

We achieved criteria with flying colours. The design is almost silent, leaves no mess and the edges are quite clean. However, the constraint of easily being able to cut a panel is not met, and thus the design need iterating. We're quite happy with where we are at and what we've done for the year, especially considering the whole pandemic situation. Would have been great to cut panels perfectly from day one, but I guess that's one learning that has stuck with us. Things never go as planned for a project at any meaningful scale and you need to accept that.

## Future Work

Although it might not be perfect to start, it's a prototype. Two of us got hired by Trusscore (John and Mitch), so there's potential that they will continue this project and iterate on the design to get something really smooth. Hoping our electrical power fix does something for that, but if not, there's at least some hope!
