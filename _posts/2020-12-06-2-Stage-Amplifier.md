<!___
---
title:  "2-Stage Operational Transconductance Amplifier using Miller Compensation"
layout: post
mathjax: true
categories: media
---

![2-Stage Architecture](/assets/images/2stageampsch.png)

## Summary

This project involved using Cadence Virtuoso and MATLAB to design by sizing the transistors of an existing architecture in a 180nm process using a 1.8V supply. The 2-stage operational transconductance amplifier is composed of a single-ended folded cascode amplifier and common source amplifier. The bias circuit consists of a constant-gm circuit that provides a current reference that is robust to PVT variantions for the cascode current mirrors to appropriately bias the transistors. Good stability was achieved by using miller compensation and a nulling resistor through pole-zero cancellation to improve the phase margin. 



| Parameter                  | Specification             | Result                     | 
|----------------------------|---------------------------|----------------------------|
| Supply Voltage             | 1.8 V                     | 1.8 V                      |
| Output Load                | 5 pF                      | 5 pF                       |
| Input Common-mode Range    | 0.2 V to 0.8 V            | Specification Met          |
| Output Common-mode Range   | 0.4 V to 1.4 V            | Specification Met          |
| Power Dissipation          | $$\le$$ 2.5 mW (Minimize) | 990 $$\mu$$W               |
| DC Gain                    | $$\ge$$ 70 dB             | 78.484 dB                  |
| Unity Gain Bandwidth       | $$\ge$$ 100 MHz           | 107.432 MHz                |
| Phase Margin               | $$\ge$$ 65°               | 68.83°                     |
| Gain Margin                | $$\ge$$ 15 dB             | 15.676 dB                  |
| Current Mirror "_m_" Factor| $$\le$$ 20                | Specification Met          |
| Gate Overdrive Voltage     | $$\ge$$ 150 mV            | Specification Met          |


-->



