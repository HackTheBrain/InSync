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

This could either be in the way of choosing a mood (rest i.e) and having our headgear adjust to it (within one person), or by synchronizing the mood of 'Person A' with 'Person B'

###Synchronisation within the brain
We want the various parts of the brain to work together, resonating at the same frequencies and in this way causing neural pathways.

- Gamma waves: have frequencies from 27 Hz and up and are responsible for the formation of ideas, language, learning and memory processing.
- Beta waves: ranges from 14 Hz to 30 Hz. These brainwaves occur when we are wide awake and this is where we spend most of our waking hours.
- Alpha waves: the frequency of these waves range from 7 Hz to 13 Hz and it is at this state that learning and processing of information are thought to be extremely optimized.
- Theta waves: when someone is in extreme state of relaxation, their brain is most likely in the range from 4 Hz to 8 Hz in frequency
- Delta waves: where frequencies range from 0.2 Hz to 3 Hz. The brain produces delta waves during sleep, when a person is in the deepest part of their sleep and not dreaming.

Source: http://www.mindbodyvortex.com/brainwave-frequencies/

It has been shown that the theta/beta ratio is higher in children with attention deficits than healthy children (Arns et al., 2011). If we play binaural beats in the beta frequency, adjusted by continuous feedback to the system through EEG about the theta/beta ratio, we can try to restore this ratio to the normal range again.

Synchronisation between brains
To create synchronisation between two people, one can think about two footsteps slowly starting to get into the same rhythm. Based on this idea, Yun et al. (2012) showed in a study that there was increased inter-brain-synchronisation (in the beta and theta ranges) after they cooperatively interacted through arm movements. We try to enhance this interpersonal communication even more by stimulating Person B's brain rhythms through light and sound based on Person A's brain rhythms (and vice versa).

##How?
We measure the EEG signal with Emotiv EPOC on two electrodes on the occipital cortex (O1 and O2) and extract the amplitude of a certain frequency (in the case of the demo, alpha, since it can be influenced easily by closing the eyes). This number is streamed to the buffer and a Processing script reads the amplitude information. Then, through the speakers and LEDs we respectively present binaural beats and flashing light, in, respectively, volume and intensity that corresponds with the amplitude of the desired frequency. Binaural beats work as such: the left ear and the right ear are presented with different frequencies, of which the difference is the frequency that you are aiming for (i.e. a 140Hz tone in the left ear and a 164Hz tone in the right ear induces a 24Hz (beta) brain oscillation). The LEDs create a fast-acting steady-state visually evoked potential (SSVEP), which also is studied to robustly influences brain rhythms. 

Specific Actions:

- Use programming language 'Processing'
- Use the Emotiv EPOC headgear
- Connect 2 potentiometers to an Arduino
- Connect 2 LEDs to the potentiometers
- Connect 2 sliders to the Arduino
- Make sure the LEDs can be controlled individually by each slider
- Attach the 2 LEDs to the glasses, make sure the light faces towards the glasses
- The sliders allow you to change the Herz frequency ranging from 1 - 40 Hz

##Scientific resources
Efficacy of binaural beats in ADHD:

- http://sincspain.com/wp-content/uploads/2011/08/HS-y-el-d%C3%A9ficit-de-atenci%C3%B3n_2.pdf
- http://www.sciencedirect.com/science/article/pii/S0882596308003321

Interpersonal synchronisation:

- http://www.ncbi.nlm.nih.gov/pmc/articles/PMC3518815/pdf/srep00959.pdf

## Other information:
*This repository was made by specific group members and uploaded to a temporary environment. This temporary environment has been manually transferred to a a more permanent Hack the Brain Github account. If any of the former team members wish to administer this repository and manage the master branch, then they can contact the current administrator of the repository to gain the proper acces privileges to do so.*

## Video on Project InSync:
[![Video image](http://handledmovie.com/get/player01.gif)](https://vimeo.com/177943249)
