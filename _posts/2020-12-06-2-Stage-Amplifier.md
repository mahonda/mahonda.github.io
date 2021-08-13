---
title:  "Sensor Interfacing 2-Stage Amplifier using 180nm CMOS Technology"
layout: post
mathjax: true
categories: media
---

## Abstract

This project involved using Cadence Virtuoso and MATLAB to size the transistors of an existing architecture that is composed of a folded cascode amplifier, common source amplifier, and a bias circuit to meet the specifications as shown below. The primary goal was to minimize the power disspation of the architecture while still meeting the specifications.

---

| Parameter                  | Specification             | 
|----------------------------|---------------------------|
| Supply Voltage             | 1.8 V                     | 
| Output Load                | 5 pF                      |
| Input Common-mode Range    | 0.2 V to 0.8 V            | 
| Output Common-mode Range   | 0.4 V to 1.4 V            | 
| Power Dissipation          | $$\le$$ 2.5 mW (Minimize) |
| DC Gain                    | $$\ge$$ 70 dB             |
| Unity Gain Bandwidth       | $$\ge$$ 100 MHz           |
| Phase Margin               | $$\ge$$ 65°               |
| Gain Margin                | $$\ge$$ 15 dB             |
| Current Mirror "_m_" Factor| $$\le$$ 20                |
| Gate Overdrive Voltage     | $$\ge$$ 150 mV            |


![2-Stage Architecture](/assets/images/2stageampsch.png)





