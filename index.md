---
title       : Zombie Simulation
subtitle    : An Introduction to Epidemiology
author      : Helen Totterdell
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---
# Why use this application?
- In most middle and high school classrooms, subjects are taught separately
and rarely are integrated together.
- As a way to combine both statistics and biology, this applet simulates a
zombie apocalypse as an allegory for an infectious disease.
- This applet runs a simulation to estimate the number of days until a
population has completely become zombies or dead.

---
# Applet Inputs
-  This applet takes in 3 inputs:
  * Population Size - The initial number of both humans and zombies at the
  beginning of Day 1.
  * Probability of Zombie Bite - The probability of being bit by a zombie on
  any given day.
  * Probability of Death from a Zombie Bite (as opposed to becoming a Zombie)

---
# Applet output

<img src="Plot.PNG" alt="Population Statistics" align="center">

The applet will output the daily population proportions of zombies and humans
and graph them on a line chart.

---
# Future additions to this applet

- An intervention (such as a treatment for an infectious disease) to eliminate zombies.
  * The simulation will then end when there are either no zombies or no alive humans.
- Running the simulation for some large number of times to figure out the average time it would take for the human population to be eradicated during a zombie apocalypse with no intervention treatment.


publish(title = 'mytitle', 'index.html', host = 'rpubs')
