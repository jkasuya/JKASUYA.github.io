---
layout: project
type: project
image: images/Project1.png
title: Birdo Does a Fly
permalink: 
# All dates must be YYYY-MM-DD format!
date: 2016-12-04
labels:
  - Java
  - ICS 111
summary: My partner and I developed a "Temple Run" kind of game that follows a bird trying to escape a fox.
---

<div class="ui small rounded images">
  <img class="ui image" src="../images/micromouse-robot.png">
</div>

Birdo does a Fly is a "Temple Run" like game that involves a bird having to jump or duck under obstacles to avoid being captured by a fox. The game randomly selects either a rock or a vine that the player will have to jump over or slide under to avoid being captured by a fox. The player either has to press 'W' to jump or 'S' to slide. Each object has a specific hitbox that was calculated based on the dimensions of the image, so the keys have to be pressed at the correct time to avoid colliding with the hitboxes.

This was a group project. My parter for this project was Matthew Yamaguchi. My specific role on this project was to create the hitboxes for the objects and the bird. I was also responsible for randomizing the obstacles. It was a lot of trial and error, as the bird died too early in some cases, and didn't die at all in other cases.

Here is some code that illustrates how the hitboxes were calculated:

```js
byte ADCRead(byte ch)
{
    word value;
    ADC1SC1 = ch;
    while (ADC1SC1_COCO != 1)
    {   // wait until ADC conversion is completed   
    }
    return ADC1RL;  // lower 8-bit value out of 10-bit data from the ADC
}
```




