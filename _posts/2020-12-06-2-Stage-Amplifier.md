---
title:  "2-Stage Amplifier using 180nm CMOS Technology"
layout: post
mathjax: true
categories: media
---

![2-Stage Architecture](/assets/images/2stageampsch.png)

## Abstract

This project involved using Cadence Virtuoso and MATLAB to design by sizing the transistors of an existing architecture. The 2-stage operational transconductance amplifier is composed of a single-ended folded cascode amplifier and common source amplifier. The bias circuit consists of a constant-gm circuit that provides a current reference that is robust to PVT variantions for the cascode current mirrors to appropriately bias the transistors. Good stability was achieved by using Miller Compensation to split the dominant and non-dominant poles to improve the phase margin. As a consequence of the compensation capacitor, a RHP zero was introduced and was converted to a LHP zero by using a nulling resistor in series with the compensation capacitor.



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






