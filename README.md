# The TorqueTuner
This repository is meant to link all repositories and literature related to the TorqueTuner.
## Description
The TorqueTuner (TT) was first developped in 2020 by Kirkegaard, Bredholt, Frisson and Wanderley as an embedded haptic module for DMIs like the T-Stick. It's main focuse was simulation of haptic effects associated with turning a knob, affordability and portability of force feedback devices.
    
Afterwards, it was further developped to be a prototyping and authoring tool of 1-DOF haptic effects for the IDMIL, replacing the initial motor with a more powerful one.

It is wifi capable and can run OSC and Libmapper over the local network thanks to the esp32.
You can learn more about it in the links provided below.
## Future Work
This is an open source-project, as such all documents and information is made available to anyone who wished to replicate the TorqueTuner. Any future development is meant to furhter the project but not replace what has currently been done.

* There is in the works the idea to replace the ESP32 with a Bela beagle board or a raspberry pi for added computational power and data transfer speeds.
* Improvement to the haptic authoring tool
* Better integration with authoring tools like Feelix or ForceHost
* Improvement on haptic respones, removal of Aliasing in the haptic effect


## Related Projects
* https://www.idmil.org/project/torquetuner/
* https://www.idmil.org/project/sustainable-haptic-development/
* https://github.com/Maxw3llGM/TorqueTuner_Reed-Model_DMI
* https://github.com/Maxw3llGM/TorqueTuner_Score_Animation
* https://github.com/Maxw3llGM/TorqueTuner_Template_project
* https://feelix.xyz/
* https://sat-mtl.gitlab.io/collaborations/google-summer-of-code/posts/2023-contributions/maxw3llgm/work-product-maxw3llgm-audio-to-haptic-interaction-design-with-feelix-supporting-torquetuner/
## Related Literature

* [TorqueTuner: A self contained module for designing rotary
haptic force feedback for digital musical instruments](https://www.nime.org/proceedings/2020/nime2020_paper52.pdf) (Kirkegaard et al., 2020)

* [Designing for Haptic and Embodied Interaction with Feelix](https://dl.acm.org/doi/pdf/10.1145/3569009.3571842) (van Oosterhout et al., 2023)

* [ForceHost: an open-source toolchain for generating firmware embedding the authoring and rendering of audio and force-feedback haptics](https://www.researchgate.net/publication/361591242_ForceHost_an_open-source_toolchain_for_generating_firmware_embedding_the_authoring_and_rendering_of_audio_and_force-feedback_haptics) (Frisson et al., 2022)

    

