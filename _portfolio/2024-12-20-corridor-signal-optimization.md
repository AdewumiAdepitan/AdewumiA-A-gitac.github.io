---
title: "Corridor Signal Optimization Near George Mason University (TransModeler)"
collection: portfolio
permalink: /project/gmu-corridor-signal-optimization/
date: 2025-12-20
excerpt: "Simulated and optimized peak-hour signal timing at two critical intersections near GMU, cutting delay at the worst intersection by 63.7% without adding lanes."
author: "Name Name"
paperurl: "/files/Adewumi_Augustine_Adepitan_CEIE767_Final_Project.pdf"
---

## Project summary
This project evaluated **peak-hour congestion** along a corridor near **George Mason University (Fairfax, VA)**, focusing on two critical signalized intersections (**Node 3 and Node 1**) identified through public feedback as major delay points. The goal was to **reduce delay and improve traffic progression** using **signal timing and coordination strategies**—without adding lanes due to **right-of-way constraints**. 

## What I did
- Built and calibrated a **TransModeler** simulation representing existing conditions and signal control.
- Tested **three timing iterations**, adjusting:
  - green splits (reallocating time toward high-demand movements),
  - limited-to-stronger coordination between intersections,
  - phase structure (simplifying phasing where beneficial).
- Evaluated performance using **intersection delay, LOS, stops, and control delay**.

## Key results (peak hour)
- **Node 3 (worst intersection):** average delay reduced from **181.7 sec/veh → 65.9 sec/veh** (**63.7% reduction**), improving LOS from **F → E**.
- **Node 1:** delay improved slightly (**69.1 sec/veh → 64.7 sec/veh**) while maintaining **LOS E**.
- Best-performing plan came from the final iteration, which emphasized **green time efficiency, shorter effective cycles via split tuning, and improved coordination**. 

## Deliverable
[Download the full report (PDF)]({{ "/files/Adewumi_Augustine_Adepitan_CEIE767_Final_Project.pdf" | relative_url }})
