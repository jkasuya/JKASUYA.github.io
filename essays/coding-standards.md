---
layout: essay
type: essay
title: Coding for the Green Checkmark
# All dates must be YYYY-MM-DD format!
date: 2018-02-07
labels:
  - Coding Standards
  - Software Engineering
  - ESLint
---
  <img class="ui medium right floated rounded image" src="../images/Greencheck.jpg">

## Coding Standards: An Introduction
Everyone loves seeing a green checkmark on something. Usually, that signifies a type of accomplishment and people feel a lot of personal satisfaction. In terms of programming, a green checkmark appears in the IntelliJ IDE when all the coding standards are met. Imagine a beginning programmer seeing a green checkmark saying that their code is great. It would give a lot of reassurance to them. However, most beginning programmers often aren't taught the importance of coding standards. At that stage in time, all they really want is for their code to work properly. In fact, even for me, all I really cared about up until this point in my coding career was getting my code to run properly. What these beginning programmers don't realize however, is that coding standards are very useful when trying to analyze their code for bugs. Coding standards offer easy readability, and (depending on the software used) might even give hints to some of the bugs in your code. In that way, as much of a pain as it may be, coding standards offer very important insights into your code.

## Initializing and Using ESLint
From personal experience, I've only really paid attention to coding standards for about a week. Specifically, I've been using ESLint in IntelliJ as the coding standard. Using IntelliJ with ESLint isn't necessarily the easiest thing to do, although it is helpful to understanding the code. To begin using ESLint, one must first change around some of the default preferences of IntelliJ. As of this writing, I have not yet found a way to change the default settings so I don't have to change them every time I start coding a new project. Unfortunately, this means that starting a project is often a very long and tedious process. Once this process has completed, IntelliJ will show a green checkmark when all of the code meets the standards. Therefore, while the code still needs to work, a green checkmark in the top right corner also has to show, otherwise some kind of standard hasn't been met. While most of the standards are very self explanatory, some of them are a little hard to get used to if there was no prior emphasis on coding standards. For me, it was a little hard to get the green checkmark on my first use, as there were a few standards that I was not used to (spaces after parenthesis, no extra lines at the end of code, etc.). However, doing enough of the practice WODs for my class enough times was enough to emphasize these standards for me. 

## Impressions on ESLint
My first experience with ESLint was an interesting one. While ESLint used a lot of the same coding standards that I was used to from ICS 111 and ICS 211 (in Java), there were some very confusing aspects to it. One standard that I particularly had a hard time with at the start was that you are only allowed to have one extra line at the end of your code. The first time I programmed using ESLint, I had no idea why I had this error and found that just deleting a couple of extra lines at the end of my code actually fixed it. Otherwise, I haven't really found anything else that has really stumped me about ESLint's standards. Talking to some of my friends, one of their biggest difficulties was the spaces in between parenthesis and curly brackets. For me however, as I always thought it would be easier for me to read, this was not a big difficulty.

## Final Verdict on Coding Standards
Coding for standards is not only important for readability, but also provides key insights into potential errors in the code. They may tell you that you have a dangling variable that hasn't been used, or you may have assigned a value to a variable before actually declaring it, or maybe you haven't actually used a method you wrote in your code. Coding standards actually helps me to see these errors. In one of the practice WODs, I actually created a variable I planned on returning, but after realizing that it would be simpler to return a result instead of a variable I never ended up using it. ESLint actually caught that for me and helped make my code a little nicer. Seeing code written "nicely" such that spacing and indentations are all equal, also make the code much easier to look back on and search through. Therefore, coding standards should be heavily emphasized, especially in beginning programming courses. So, while coding for a green checkmark might take a little while to set up and to get used to, seeing that green checkmark at the end symbolizes a very big accomplishment: that your code fits the standard. 

