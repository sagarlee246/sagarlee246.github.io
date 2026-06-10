---
layout: page
title: Construction and Characterization of an Analog Lock-In Amplifier
description: A breadboard-built analog lock-in amplifier used to recover a weak optical signal from noise.
img: /assets/img/LockIn.png
importance: 3
category: Physics
pdf: /assets/pdf/Construction_and_characterization_of_an_analog_lock-In_amplifier.pdf
---

This project built an analog single-phase lock-in amplifier on a breadboard using operational amplifiers, passive filters, and square-wave mixing. A red LED and photodiode provided the weak optical signal, which was amplified, mixed with a reference signal, and low-pass filtered to recover a stable output.

The characterization showed the expected behavior across the five stages of the circuit. The pre-filtering and gain stages improved the signal-to-noise ratio, the mixer produced the reference-dependent sign changes, and the final filter converted the modulated signal into a clean DC output.

The project demonstrates how lock-in detection can recover weak signals buried in noise using a relatively simple analog circuit.

[Read the full report]({{ page.pdf | relative_url | uri_escape }})
