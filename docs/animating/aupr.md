---
title: Animating Items (WIP)
index: 1
---

## Introduction

There are 2 methods that work best to animate items, both involve [Blender](https://www.blender.org/).

This guide will (soon) showcase both methods and how to animateq using both methods.

### Getting started

To get started with animating, learning how to actually animate in Blender is pretty important, luckily however this is not too hard or complex.
To start, feel free to watch some youtube tutorials to get the very basics of it set up, as that is pretty important, as we will not be going over keyframing or using the timeline here.

## Animating with AUPR

Animating with AUPR is a breeze, and it's a great way to get started with animating in Unturned. This guide will help you get started with animating in Unturned using AUPR.

### Prerequisites

[AUPR (Der Ente's Rig)](https://github.com/DerEnte/Advanced-Unturned-Player-Rig)

[Blender](https://www.blender.org/)

### Actually animating

#### Item animation

When animating items, be sure your model is facing the Y axis, and is 0,0,0 on all axis while doing so. If not, move your model to the correct position, then use the apply menu (left ctrl + A) and select “All Transforms”.

Once that is done, copy the model to AUPR, and then you will want to go to the yellow box on the right side of the screen labeled "Object Properties", you'll then want to go to the "Relations" tab, and then select the "Parent" dropdown, and select the parent as to be "IDRight", the item should now appear in the right hand of the character, if that is not the case try again from the beginning.

From here on out you will be able to start animating your character, you can adjust what frame of the animation you are viewing by using the timeline, which by default will be in the lower window of Blender.

The animations you will be making will differ depending on the item you are making, but all items that can / should be held by players will require the same basic animations: `Equip` & `Use`.

Below will be a (now ***incomplete***) list of all the different animations you will be required to make for items.

***Useables*** (*Carjacks*, *drinks*, *foods*, etc.) : `Equip`, `Use`.

***Medicals*** (*Think bloodbags* and *medkits*.) : `Equip`, `Use`, `Aid`(The *Aid* animation is for using the healing item on another player.).

***Melee*** (*Anything that can be used to attack*) : `Equip`, `Weak`, `Strong`, `Inspect`.
