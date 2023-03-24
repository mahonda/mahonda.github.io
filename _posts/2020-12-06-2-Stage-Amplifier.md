---
title:  "2-Stage Operational Transconductance Amplifier using Miller Compensation"
layout: post
mathjax: true
categories: media
---

![2-Stage Architecture](/assets/images/2stageampsch.png)

## Abstract

This project involved using Cadence Virtuoso and MATLAB to design by sizing the transistors of an existing architecture in a 180nm process using 1.8V supply rails. 

Improved the stability through pole-zero cancellation using a miller compensation capacitor and a nulling resistor to achieve a phase margin of 68 degrees and a gain margin of 15.6dB.
![image](https://user-images.githubusercontent.com/46824860/227656479-d6aa9dfe-7962-4a06-bfc2-00820f247b87.png)

The 2-stage operational transconductance amplifier is composed of a single-ended folded cascode amplifier and common source amplifier. The bias circuit consists of a constant-gm circuit that provides a current reference that is robust to PVT variantions for the cascode current mirrors to appropriately bias the transistors. Good stability was achieved by using miller compensation and a nulling resistor through pole-zero cancellation to improve the phase margin. 



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






