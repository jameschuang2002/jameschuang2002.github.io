---
layout: page
permalink: /research/
title: Research
description: 
nav: true
nav_order: 6
---
#### **Research Overview**

My research focuses on identifying and exploiting microarchitectural vulnerabilities, with an emphasis on understanding how seemingly benign system optimizations can give rise to exploitable behaviors. At present, my work investigates classical keystroke timing attacks via cache-based side channels on both Intel and Apple processors. More generally, I am interested in the ways in which cache side-channel techniques can be composed with vulnerabilities stemming from other microarchitectural components, yielding more powerful and general classes of attacks.

#### **KeyTAR: Practical Keystroke Timing Attacks and Input Reconstruction**

In this work, we collected side-channel traces from 1.5 million typing samples to rigorously evaluate the assumption that timing intervals suffice for input reconstruction. Our results highlight both the strengths and inherent limitations of keystroke timing attacks, and demonstrate their applicability across diverse input scenarios. To facilitate future research in this area, we open-sourced our tools and datasets. This work establishes a foundation for the reconstruction of more complex secrets such as passwords, PINs, and pseudorandom strings.

#### **Current Work: Extending KeyTAR**

Building on KeyTAR, my current research extends keystroke timing attacks to Apple’s M-series processors, which introduce unique operating system and microarchitectural considerations. This effort seeks to evaluate the portability of keystroke timing attacks and its applicability to a wide range of typing behaviours. In parallel, we are hoping to develop a large password dataset and adapt large language models for password and pseudorandom string inference, with the goal of advancing the state of password reconstruction.

#### **Future Directions**

Looking ahead, I aim to investigate the broader landscape of interactions between cache side channels and other microarchitectural mechanisms. In particular, I am interested in how speculative execution, error handling, prefetchers, branch predictors, and page-walk side channels may interact in nontrivial ways to produce emergent vulnerabilities. My long-term objective is to characterize and systematize these cross-component interactions, thereby assessing the performance of existing attacks, revealing new classes of attacks, informing the design of more robust microarchitectural defenses.
