# VeinCV
## Motivation
Peripheral Difficult Venous Access (PDVA) is a commonplace problem in clinical practice which results in repetitive punctures, damaged veins, and significant discomfort to the patients. Nowadays, the poor visibility of subcutaneous vasculature in the visible part of the light spectrum is overcome by near-infrared (NIR) imaging and a returned projection of the recognized vasculature back to the arm of the patient. We introduce the first “smart” engine to govern the components of such imagers in a mixed reality setting. Namely, we introduce a closed-loop hardware system that optimizes cross-talk between the virtual mask generated from the NIR measurement and the projected augmenting image. Such real-virtual image translation is accomplished by several steps. First, the NIR vein segmentation task is solved using U-Net-based network architecture and the Frangi vesselness filter. The generated mask is then transformed and translated into the visible domain by a projector that adjusts for distortions and misalignment with the true vasculature using the paradigm of Reinforcement Learning (RL). We propose a new class of mixed reality reward functions that guarantees proper alignment of the projected image regardless of angle, translation, and scale offsets between the NIR measurement and the visible projection.
![Experimental setup scheme](https://github.com/cviaai/NIR-VISIBLE-IMAGING-WITH-CNN-RL/blob/master/img/Experimental_setup_scheme.png)
## Segmentation pipeline
Segmentation pipeline featuring Frangi vesselness filter, attention U-Net and clDICE loss.
![Segmentation pipeline](https://github.com/cviaai/NIR-VISIBLE-IMAGING-WITH-CNN-RL/blob/master/img/Segmentation_pipeline.png)
## Maintainers
Aleksandr Rubashevskii (main contributor) @rubaha96
Vito Michele Leli @vitomichele
Oleg Rogov @olegrgv
