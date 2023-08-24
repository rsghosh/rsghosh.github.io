---
name: Zip Tie Installer
tools: [SolidWorks, 3D Printing]
image: /assets/images/zip_tie_installer/zip_tie_installer.jpg
description: Low-cost, rechargeable handheld device for automated zip tie installation (Mechanical Engineering senior project).
---

# Zip Tie Installer

For my Mechanical Engineering senior project, I was the design lead in a team of
4 for developing a low-cost, rechargeable handheld device for automated zip tie
installation.

I utilized SolidWorks to create the CAD model and 3D printed custom parts using
my [K3 printer](/projects/02-k3). We iteratively prototyped, tested, and refined
the design, culminating in a successful demonstration at the senior project
expo.

{% include elements/figure-modal.html image="/assets/images/zip_tie_installer/zip_tie_installer.jpg" alt="Zip Tie Installer" %}

## Demonstration

In the following video, my teammate demonstrates how to use the zip tie
installer:

{% include elements/video-figure.html id="1FGn_M0SpABBWSmrCcECfglYL0JOBHeVG" provider="google drive" caption="Demonstration" %}

## CAD

I used SolidWorks to create the CAD model for the zip tie installer.
We iterated on individual parts several times, but the main 3 revisions of the
overall device are shown below:

{% capture carousel_images %}
/assets/images/zip_tie_installer/cad/pdr/side_view_annotated.png,Full assembly: V1
/assets/images/zip_tie_installer/cad/cdr/side_view_annotated.png,Full assembly: V2
/assets/images/zip_tie_installer/cad/fdr/side_view_annotated.png,Full assembly: V3
/assets/images/zip_tie_installer/cad/pdr/magazine_annotated.png,Magazine: V1
/assets/images/zip_tie_installer/cad/cdr/magazine_annotated.png,Magazine: V2
/assets/images/zip_tie_installer/cad/fdr/magazine_annotated.png,Magazine: V3
{% endcapture %}
{% include elements/carousel-captioned.html images=carousel_images ride="carousel" caption="Main Zip Tie Installer Revisions" %}

I used a top-down modeling approach to create the CAD model. This allowed me to
make changes to the geometry of each mechanism quickly, while making sure all
the parts that made up that mechanism could (usually) update automatically so
that they still worked with each other. The main sketches I used to lay out the
geometry of the jaw, tightener, and magazine are shown below.

{% capture carousel_images %}
/assets/images/zip_tie_installer/cad/jaw_layout.png,Jaw overall layout
/assets/images/zip_tie_installer/cad/jaw_servo_layout.png,Jaw servo layout
/assets/images/zip_tie_installer/cad/tightener_layout.png,Tightener layout
/assets/images/zip_tie_installer/cad/magazine_layout.png,Magazine overall layout
/assets/images/zip_tie_installer/cad/magazine_pusher_layout.png,Magazine pusher layout
/assets/images/zip_tie_installer/cad/magazine_blocker_layout.png,Magazine blocker layout
/assets/images/zip_tie_installer/cad/magazine_follower_layout.png,Magazine follower layout
/assets/images/zip_tie_installer/cad/magazine_follower_spring_rear_layout.png,Magazine follower rear spring layout
/assets/images/zip_tie_installer/cad/magazine_follower_spring_front_layout.png,Magazine follower front spring layout
{% endcapture %}
{% include elements/carousel-captioned.html images=carousel_images ride="carousel" caption="Layout Sketches" %}

## Prototyping and Testing

We chose to use 3D printing for all of the custom parts of the zip tie installer
since it allowed us to create complex geometries and iterate quickly. We went
through several cycles of doing CAD design, printing a new prototype, testing
the prototype, and making improvements to the model based on our findings. All
custom parts were printed out of ABS or ASA plastic on my
[K3 printer](/projects/02-k3):

{% capture carousel_images %}
/assets/images/zip_tie_installer/k3_printing1.jpg
/assets/images/zip_tie_installer/k3_printing2.jpg
/assets/images/zip_tie_installer/k3_printing3.png
{% endcapture %}
{% include elements/carousel-figure.html images=carousel_images ride="carousel" caption="3D Printer" %}

Most of our testing was done on a test stand:

{% capture carousel_images %}
/assets/images/zip_tie_installer/testing1.png
/assets/images/zip_tie_installer/testing2.png
{% endcapture %}
{% include elements/carousel-figure.html images=carousel_images ride="carousel" caption="Testing" %}

## Senior Project Expo

We presented our zip tie installer at the senior project expo. In addition to
explaining our device, we walked attendees through the process of using it to
install a zip tie. All but around 5 of the zip ties on the test stand
shown below were installed that day by people attending the expo:

{% capture carousel_images %}
/assets/images/zip_tie_installer/senior_project_expo.jpg
/assets/images/zip_tie_installer/senior_project_expo2.jpg
/assets/images/zip_tie_installer/zip_tie_installer.jpg
{% endcapture %}
{% include elements/carousel-figure.html images=carousel_images ride="carousel" caption="Senior Project Expo Setup" %}

## More Info

- [Report and Supplemental Files](https://digitalcommons.calpoly.edu/mesp/701/)
- [Project Files](https://github.com/moffdude/Zip-Tie-Installer/)
