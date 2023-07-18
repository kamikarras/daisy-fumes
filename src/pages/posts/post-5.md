---
layout: ../../layouts/MarkdownPostLayout.astro
title: "Interface Lab: Input, Output, and State Change"
author: Daisy Fumes
description: "Exploring basics in input and output with the ardiuno nano 33 and state "
image: 
    url: '/assets/post5/img01.jpg'
    alt: "breadboard, LEDS, wires"
pubDate: 2023-07-16
tags: ["interface lab", "arduino", "nano 33"]
---
In our first lab with our arduinos we explored connecting our microcrollers to the arduino IDE.

In class we had already installed the IDE and the SAMD board manager, so really all that was left was the fun parts. By "the fun parts" what I mean is being directly handed schematics for our boards and code to use, but still finding ways to mess it up.

<img width=49% src='/assets/post5/img02.jpg'>
<img width=49% src='/assets/post5/img03.png'>

Luckily, the first parts were pretty straight forward as seen above. Connect to power, ground, and an input pin. Throw in a button and a pulldown resistor and we're be ready to party. Cue the electric slide.

But wait...

It's not actually party time. STOP THE MUSIC. While we have mostly prepped for our party, there are no lights. What kind of party has no lights? A dark one I guess...

Let's have a lit party by adding some LEDS connected to some output pins and the general flow electricty.

<img width=100% src='/assets/post5/img04.jpg'>

Wow, that's great. We have all the things. 

Time for the Arduion IDE to add the magic we've all been waiting for. With the board connected to the computer it is availble in the port list to read and write to.

We just had to label some pins as input and some as output appropriately so we could digitally read and write to them. The button is what we are reading and the LEDS are what we write to.

<img width=49% src='/assets/post5/img05.jpg'>
<img width=49% src='/assets/post5/img06.jpg'>

Once we had the code and the pieces on the breadboard, we had the largest party by pressing the buttons and seeing the lights change. This brought me so much joy I stood up and danced.

Further exploring we interacted with the IDE to read and print to the serial monitor with button and force sensors.
I ran into a few problems here because I had miss places some of the wires and had not opened the serial monitor.

At first, I sat and spun on these issues, but luckily we have a really great community here and merely asking for help from those around me quickly solved the issues once I took a moment to ask.

While, these projects are pretty basic right now. I'm so excited to see where it takes me.