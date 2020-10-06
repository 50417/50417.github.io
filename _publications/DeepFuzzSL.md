---
title: "DeepFuzzSL: Generating models with deep learning to find bugs in the Simulink toolchain. "
collection: publications
permalink: /publications/DeepFuzzSL
venue: "DeepTest"
date: 2018-5-27
citation: '<b>Shrestha, Sohil L.</b>, Shafiul Azam Chowdhury and Christoph Csallner. "DeepFuzzSL: Generating models with deep learning to find bugs in the Simulink toolchain." Proc. 2nd Workshop on Testing for Deep Learning and Deep Learning for Testing (DeepTest), 2020.'
---
[Download paper here](http://ranger.uta.edu/~csallner/papers/Shrestha20DeepFuzzSL.pdf) 

## Abstract
Testing cyber-physical system (CPS) development tools such as MathWorks’ Simulink is very important as they are widely used
in design, simulation, and verification of CPS models. Existingrandomized differential testing frameworks such as SLforge leverages semi-formal Simulink specifications to guide random model generation. This approach requires significant research and engineering investment along with the need to manually update the tool, whenever MathWorks updates model validity rules. To address the limitations, we propose to learn validity rules automatically by learning a language model using our framework DeepFuzzSL from a existing corpus of Simulink models. In our experiments DeepFuzzSL consistently generated over 90% valid Simulink models and also found 2 bugs in Simulink version R2017b and R2018b confirmed by MathWorks Support.


