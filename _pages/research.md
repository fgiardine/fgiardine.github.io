---
layout: archive
permalink: /research/
title: "Research"
author_profile: true
---

{% include base_path %}

This page has some details about my previous research in capacitor-based power converters. I look forward to updating it with my postdoctoral research soon!

Electromagnetic Interference for High-Performance Converters
======
Electromagnetic interference (EMI) is critical in all applications where power converters are connected to other equipment. In my work, I have explored how EMI can be improved through variable frequency control in FCML converters. I have additionally analyzed fundamental EMI generation for FCML converters and developed analytical models describing this.

<div style="display: flex; gap: 20px; justify-content: center; align-items: flex-start; text-align: center; flex-wrap: wrap; margin: 1.5em 0;">
  <div style="flex: 1; min-width: 250px; max-width: 48%;">
    <img src="{{ base_path }}/images/emi_bench.png" style="width: 100%; height: auto; display: block; margin: 0 auto 8px;" />
    <span style="font-size: 0.9em; line-height: 1.3; display: block;">EMI test bench.</span>
  </div>
  
  <div style="flex: 1; min-width: 250px; max-width: 48%;">
    <img src="{{ base_path }}/images/emi_results.png" style="width: 100%; height: auto; display: block; margin: 0 auto 8px;" />
    <span style="font-size: 0.9em; line-height: 1.3; display: block;">EMI scan results showing the reduction in switching-frequency harmonic peaks as a result of variable frequency control.</span>
  </div>
</div>

Flying Capacitor Multilevel Converters in DC-AC/AC-DC Applications
======
The flying capacitor multilevel (FCML) converter is a type of hybrid switched-capacitor converter that is known for high efficiencies and volumetric power densities. This is accomplished through the use of lower voltage, high figure-of-merit switching devices. The FCML converter performs much of its energy conditioning via energy-dense capacitors that enable higher volumetric power densities, which is essential in volume-sensitive applications such as electrified transportation. In some of my work, I have explored how variable switching frequencies can be used to improve converter efficiency without violating key component current and voltage ripple constraints.

<div style="text-align: center; margin: 1.5em 0;">
  <img src="{{ base_path }}/images/blue_6lvl.png" style="width: 50%; height: auto; display: block; margin: 0 auto 8px;" />
  <span style="font-size: 0.9em; line-height: 1.3; display: block;">6-level gallium-nitride based FCML inverter used in a 2-stage microinverter solution.</span>
</div>

<div style="display: flex; gap: 20px; justify-content: center; align-items: flex-start; text-align: center; flex-wrap: wrap; margin: 1.5em 0;">
  <div style="flex: 1; min-width: 250px; max-width: 48%;">
    <img src="{{ base_path }}/images/yayun_fcml.jpg" style="width: 100%; height: auto; display: block; margin: 0 auto 8px;" />
    <span style="font-size: 0.9em; line-height: 1.3; display: block;">A 3.3 kW, 98.9% efficient DC-AC FCML converter designed by Yayun Zhao.</span>
  </div>
  
  <div style="flex: 1; min-width: 250px; max-width: 48%;">
    <img src="{{ base_path }}/images/jack_yayun.png" style="width: 100%; height: auto; display: block; margin: 0 auto 8px;" />
    <span style="font-size: 0.9em; line-height: 1.3; display: block;">A picture of Yayun Zhao, Jack Armstrong, and myself after our last day of testing the 3.3 kW converter.</span>
  </div>
</div>
