---
layout: page
title: About
permalink: /about/
weight: 3
---

# About Me

Hi I am **{{ site.author.name }}**

I am a mechanical and software engineer with a passion for designing innovative
solutions that integrate mechanical components, electronics, and software.

I graduated from California Polytechnic State University, San Luis Obispo in
2023 with a B.S. in Mechanical Engineering (concentration in Mechatronics) and a
minor in Computer Science.

I am proficient in SolidWorks for designing parts and assemblies, and FDM/FFF 3D
printers for rapid prototyping and iterative development.

## Background

I have always been interested in building things that move. From 4th grade
through high school, I participated in robotics teams including FIRST Lego
League, Botball, and FIRST Robotics Competition. In high school I learned
SolidWorks, which I have been using for about 7 years, for projects both inside
and outside of school. I also learned to use Fusion 360 so I could use it at
home to design my first micro racing drone for fun.

When I started college, I designed a second micro racing drone as a personal
project. I bought and assembled my first 3D printer (the Prusa MK3S) to print
the camera and antenna mounts out of TPU and do a test print of the other frame
parts before getting them cut from a carbon fiber sheet.

After spending some time with the printer, I wanted better speed and print
quality, and started looking into tweaks. I learned about
[Klipper](https://www.klipper3d.org/), an alternative firmware for 3D printers
that had better motion planning and other useful features. However, the Prusa
was still held back by its “bedslinger” design - it moves the entire mass of the
bed instead of the print head for y-axis motion, so it could not run with very
high acceleration values. My quest for faster and better led me to
[Annex Engineering](annex.engineering). Annex’s K-series printers focused on
speed without sacrificing high print quality by making specific design decisions
like using shorter and wider belts to increase rigidity.

Annex started the closed beta for their [K3 printer](/projects/02-k3) in
November 2020, and I enthusiastically joined as a beta tester. I contributed
feedback and also designed a new toolhead for the printer, which became the
official toolhead. I was added to the Annex development team that December. I
have continued as one of the main developers working on K3, further improving
the toolhead and helping with mechanical design in a few other areas.

Besides K3, my other main project with Annex Engineering currently is
[Trad Rack](/projects/01-trad-rack). When I originally bought my Prusa MK3S, I
considered getting the MMU2S upgrade to print with multiple colors (and possibly
multiple materials) in a single print. However, I couldn’t justify the price at
the time, and the limitation to no more than 5 filaments. An alternative I
considered, the SMuFF V5, based on the same filament-swapping process, nearly
had the expandability I wanted; I just wished the cost per filament lane was
lower. Eventually, I decided to come up with my own solution, the Trad Rack
which is focused on scalability (adding lots of filaments) at low cost.

## Skills

- CAD - SolidWorks, Fusion 360
- Prototyping using laser cutter and 3D printer, basic soldering, electrical and mechanical assembly, rendering images with Blender
- Programming - Python, Java, C, C++, MATLAB, Simulink, Git/GitHub, Perforce, Review Board
