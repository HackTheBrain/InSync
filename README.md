# InSync

##Who?

- Pieter Wackers
- Mirco Piccin
- Giulio Pilotto
- Sjors Suijkerbuijk
- Olof van der Werf

##Why?
We want people to be in synchrony with themselves and others. In some situations, this synchrony is distorted. For example, ADHD children are shown to have a theta/beta ratio that is significantly higher than normal. To restore this ratio, we designed a system that can bring one’s brainwaves back in sync. Another situation where synchrony is important is in social interaction. Studies have shown that people’s brainwaves start synchronising when they are mimicking each others movements. To increase synchrony even further, we want to bring the brainwaves of person A to person B and vice versa.

##What?
To achieve the aforementioned within-person and interpersonal synchrony we designed a mobile system consisting of a pair of goggles and an Emotiv EPOC. The goggles are equipped with speakers and LEDs, to induce the right brainwave frequency. If our system notices that the brain is not ‘in sync’ (for example, if the theta/beta ratio is too high), we aim to restore this through auditory and visual stimulation on the goggles. Also, if person B puts on the goggles, then that person’s brain waves can be influenced by inducing a set of frequencies based on the brainwaves of person A, who wears the Emotiv. 

##How?
We measure the EEG signal with Emotiv EPOC on two electrodes on the occipital cortex (O1 and O2) and extract the amplitude of a certain frequency (in the case of the demo, alpha, since it can be influenced easily by closing the eyes). This number is streamed to the buffer and a Processing script reads the amplitude information. Then, through the speakers and LEDs we respectively present binaural beats and flashing light, in, respectively, volume and intensity that corresponds with the amplitude of the desired frequency. Binaural beats work as such: the left ear and the right ear are presented with different frequencies, of which the difference is the frequency that you are aiming for (i.e. a 140Hz tone in the left ear and a 164Hz tone in the right ear induces a 24Hz (beta) brain oscillation). The LEDs create a fast-acting steady-state visually evoked potential (SSVEP), which also is studied to robustly influences brain rhythms. 

##Scientific resources
Efficacy of binaural beats in ADHD:

- http://sincspain.com/wp-content/uploads/2011/08/HS-y-el-d%C3%A9ficit-de-atenci%C3%B3n_2.pdf
- http://www.sciencedirect.com/science/article/pii/S0882596308003321

Interpersonal synchronisation:

- http://www.ncbi.nlm.nih.gov/pmc/articles/PMC3518815/pdf/srep00959.pdf

## Other information:
*This repository was made by specific group members and uploaded to a temporary environment. This temporary environment has been manually transferred to a a more permanent Hack the Brain Github account. If any of the former team members wish to administer this repository and manage the master branch, then they can contact the current administrator of the repository to gain the proper acces privileges to do so.*

## Video on Project InSync:
[![Video image](http://handledmovie.com/get/player01.gif)](https://vimeo.com/177943251)
