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
League, Botball, and FIRST Robotics Competition. In high school I learned to use
SolidWorks, which I have been using for about 7 years now for projects both
inside and outside of school. I also learned to use Fusion 360 so I could use it
at home to design my first micro racing drone for fun.

<!-- I have always been interested in building things, particularly in fields such as
robotics that involve moving components...(mention robotic team stuff, solidworks, etc.) -->

During my first year of college, I designed a 2nd micro racing drone as a
personal project. I bought and assembled a 3D printer (the Prusa MK3S) so that I
could print the camera and antenna mounts out of TPU and do a test print of the
other frame parts before getting them cut from a carbon fiber sheet.

After spending some time with the printer, I started looking into ways to
improve the speed and print quality. I learned about
[Klipper](https://www.klipper3d.org/), an alternative firmware for 3D printers
that had better motion planning and other useful features. However, the Prusa
MK3S still could not run with very high acceleration values since it is a
"bedslinger" (it moves the entire mass of the bed when moving in the y-axis). I
started looking at other printer designs and learned of
[Annex Engineering](annex.engineering). Annex's K-series printers focused on
speed while maintaining high print quality, with specific design decisions to
increase performance such as using shorter and wider belts to increase rigidity.

Annex started the closed beta for their [K3 printer](/projects/02-k3) in
November 2020, and I joined as a beta tester. I contributed feedback and also
designed a new toolhead for the printer, which became the official toolhead. I
was added to the Annex development team in December. I have continued as one of
the main devs working on K3, further improving the toolhead and helping with
mechanical design in a few other areas as well.

Besides K3, my other main project with Annex Engineering so far is
[Trad Rack](/projects/01-trad-rack). When I originally bought my Prusa MK3S, I 
considered getting the MMU2S upgrade so I could print with multiple colors (and
possibly multiple materials) in a single print. However, I could not justify the
price at the time, and I would have wanted something that could be expanded to
more than 5 filaments. The SMuFF V5, another design based on the same
filament-swapping process, nearly had the expandability I wanted; I just wished
the cost per filament lane was lower. Eventually, I started on Trad Rack as an
alternative solution with a focus on scalability at low cost.

### outline (will delete)

- robotics - FLL, botball, FRC
- solidworks for ~7 years (FRC, high school engineering classes, college classes, drone stuff, annex)
- designing micro racing drone frames -> got a Prusa
- wanted improved speed and print quality -> looked into klipper, found out about annex
- drawn to annex - designed to be fast and rigid with specific design decisions such as stiffer frames and shorter/wider belts,
pushing extruders to be lighter by experimenting with nema14 motors on the ascender and later the sherpa
- k3
    - joined the k3 closed beta when it began in Nov 2020, became a member of the dev team in Dec 2020
    - redesigned the toolhead to accomplish remaining objectives
    - nozzle wiper
    - continued as one of the main devs on the k3, maintaining it and making updates
- trad rack
    - ever since I got my prusa mk3s and saw the mmu2, I wanted something similar but cheaper
    (especially wanted to be able to have as many filament lanes as I wanted without worrying about cost)
    - saw the smuff v5 but wanted something with a cheaper cost per filament lane
    - mechanical and software design
    - ran the closed beta, almost done and preparing to transition to open beta



- mention solidworks flow sim stuff?
- mention mechatronics concentration, classes I took for computer science minor?
- mention lego GBC?
- mention cadence internship?
- mention senior project?

- rc car racing -> drone racing *as a hobby*
    - before: tie into this after talking about how I like building stuff that moves
    - after: tie into 3D printer (as it is already)
- 

## Skills

- CAD - SolidWorks, Fusion 360
- Prototyping using laser cutter and 3D printer, basic soldering, electrical and mechanical assembly, rendering images with Blender
- Programming - Python, Java, C, C++, MATLAB, Simulink, Git/GitHub, Perforce, Review Board

<!-- <div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>

<div class="row">
{% include about/timeline.html %}
</div> -->