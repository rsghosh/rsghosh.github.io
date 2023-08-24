---
name: K3 Nozzle Wiper
tools: [SolidWorks, 3D Printing]
image: /assets/images/k3/nozzle_wiper.png
description: Nozzle wiper and purge bucket for the K3 printer.
---

# K3 Nozzle Wiper

I designed a nozzle wiper and purge bucket system for the
[K3 printer](/projects/02-k3). The system uses a silicone sheet to wipe plastic
off of the nozzle, and it has a removeable bucket for collecting purged
material. An arm is used to mount both the nozzle wiper and a
[Quickdraw probe](https://github.com/Annex-Engineering/Quickdraw_Probe) dock to
the printer's frame.

{% capture carousel_images %}
/assets/images/k3/nozzle_wiper.png,Nozzle Wiper and Probe Dock Arm CAD
/assets/images/k3/nozzle_wiper_cross_section.png,Nozzle Wiper Cross Section
/assets/images/k3/nozzle_wiper_and_probe_dock_irl.png,Nozzle Wiper and Probe Dock Arm
{% endcapture %}
{% include elements/carousel-captioned.html images=carousel_images ride="carousel" caption="K3 Nozzle Wiper" %}

The nozzle wiper uses magnets to lift the wiper arm to the nozzle only when the
nozzle is near the wiper. On the toolhead, the same magnets that are used with
the Quickdraw probe are used to attract the wiper arm. The moveable arm allows
the silicone sheet to raise far enough to clean the entire tip of the nozzle,
but lower far enough when not in use to avoid colliding with the toolhead during
a print.

The following video shows the nozzle wiper and purge bucket in action:

{% include elements/video-figure.html id="1_mkQJJCB5xfOJh61v7KXC9KdCQPuyQVy" provider="google drive" caption="Nozzle Purge  and Wipe Routine" %}

{% include elements/button.html link="https://github.com/Annex-Engineering/Gasherbrum-K3" text="K3 GitHub Repository" block=true %}
