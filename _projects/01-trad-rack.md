---
name: Annex Trad Rack
tools: [SolidWorks, Python, Blender, 3D Printing]
image: /assets/images/trad_rack/render.png
description: Multimaterial system for FDM/FFF 3D printers with a focus on scalability at low cost.
---

# Annex Trad Rack

I designed Trad Rack, a scalable, modular multi-material handler for 3D
printers. A multi-material handler enables a single-nozzle 3D printer to print
with multiple colors/materials in the same print, automating the
filament-swapping process. In my design, the number of colors/materials is
easily expanded using low-cost modules without any disassembly.

{% include elements/figure-modal.html image="/assets/images/trad_rack/render.png" alt="Trad Rack" %}

[TL;DR: video of Trad Rack in action](#trad-rack-in-action)

## Design Process

I started the design by putting my thoughts into a sketch. Existing
multi-material unit (MMU) designs used either 2 hobbed drive gears for each
filament or 1 drive gear and 1 idler bearing. To reduce costs when expanding the
number of filaments, I initially proposed using a low-cost drive gear for each
filament, with a single idler bearing for the entire system. The final design
deviates from this sketch, but it retains some aspects:

{% include elements/figure-modal.html image="/assets/images/trad_rack/initial_sketch.png" caption="Initial Sketch" %}

I discussed this idea with other members of the
[Annex Engineering](https://annex.engineering) team, and I started on the CAD:

{% capture carousel_images %}
/assets/images/trad_rack/v1_01.png
/assets/images/trad_rack/v1_02.png
/assets/images/trad_rack/v1_03.png
/assets/images/trad_rack/v1_04.png
{% endcapture %}
{% include elements/carousel-figure.html images=carousel_images ride="carousel" caption="Version 1" %}

Dalegaard, another member of the Annex team, suggested swapping the drive gears
and the bearing: there would be 1 idler bearing for each filament and a single
drive gear that moves between the filaments, rather than the other way around.
This solution would reduce cost further while also eliminating the need for a
long shaft running through the drive gears, allowing for easier
assembly/disassembly and better scalability. I started work on a second design
that incorporated this idea:

{% capture carousel_images %}
/assets/images/trad_rack/v2_01.png
/assets/images/trad_rack/v2_02.png
/assets/images/trad_rack/v2_03.png
/assets/images/trad_rack/v2_04.png
/assets/images/trad_rack/v2_05.png
/assets/images/trad_rack/v2_06.png
/assets/images/trad_rack/v2_07.png
/assets/images/trad_rack/v2_08.png
{% endcapture %}
{% include elements/carousel-figure.html images=carousel_images ride="carousel" caption="Version 2" %}

## First Prototype

Once the CAD was mostly complete, I began building the first prototype of Trad
Rack:

{% capture carousel_images %}
/assets/images/trad_rack/prototype_01.png
/assets/images/trad_rack/prototype_02.jpg
/assets/images/trad_rack/prototype_03.jpg
/assets/images/trad_rack/prototype_04.jpg
{% endcapture %}
{% include elements/carousel-figure.html images=carousel_images ride="carousel" caption="First Prototype" %}

The following video shows the prototype in action, swapping which filament is
fed into the output bowden tube (which would connect to the printer when in
use):

{% include elements/video-figure.html id="hxGiJGAnO-A" provider="youtube" caption="Standalone Demo"%}

The brackets on the bottom of Trad Rack are used to attach it to a printer.
I mounted Trad Rack to the side of my [K3 printer](/projects/02-k3) as shown
below, with the bowden tube feeding into the chamber
from the back:

{% include elements/figure-modal.html image="/assets/images/trad_rack/trad_rack_on_k3.png" caption="Trad Rack Mounted to my K3 Printer" %}

## Further Progress

I wrote a module for the
[Klipper 3D printer firmware](https://www.klipper3d.org/) in Python to control
Trad Rack. Then I went back and forth between doing multicolor test prints with
Trad Rack, making changes in CAD, and reprinting parts to fix issues I
encountered. For example, the image below shows a few iterations of Trad Rack's
middle carriage, which houses a filament sensor and connects to a belt for
moving the selector between filaments:

{% include elements/figure-modal.html image="/assets/images/trad_rack/middle_carriage_iterations.jpg" caption="Middle Carriage Iterations" %}

Once most of the issues were resolved, I recorded Trad Rack printing a few
3-color lizards as a demonstration. We started a closed beta to get more testing
on Trad Rack and to make further improvements before a public release. The
closed beta is ongoing and currently has about 500 beta testers.

<div id="trad-rack-in-action"></div>

The video below shows Trad Rack and my [K3 printer](/projects/02-k3) completing
a filament change from silver to orange, as well as a timelapse of the lizard
print. In the top view of the printer, you can see trad rack's selector moving
up or down the screen whenever a filament change occurs:

{% include elements/video-figure.html id="wKoVyXH0DT4" provider="youtube" caption="Toolchange and Print Timelapse"%}

The completed print is shown below:

{% capture carousel_images %}
/assets/images/trad_rack/lizards_01.jpg
/assets/images/trad_rack/lizards_02.jpg
/assets/images/trad_rack/lizards_03.jpg
{% endcapture %}
{% include elements/carousel-figure.html images=carousel_images ride="carousel" caption="Lizard Print" %}

{% include elements/button.html link="https://github.com/Annex-Engineering/TradRack" text="GitHub Repository" block=true %}
