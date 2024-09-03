# VCV2_PATCH - TETRIX
Patches, Sound Design, Motion Control, MIDI, Modular & More
by **[Max Deadroom](https://maxedonia.myportfolio.com)**

# textrix VCV Rack 2 Patch

### About this patch:  

***textrix** uses the CV outputs from the RackNES module and alternating probability switches to 'play' a .nes file recursively, wherein the CV outputs of the RackNES module and probability settings determine movement, positioning, and interaction with the game until the end of each cycle. Upon 'losing', the end of cycle triggers the .nes to reload it's original state to be performed again with different playback/probability. In addition to providing gameplay, the probability switch sends triggers to a kick and a snare drum (the Vult modules), creating an alternating beat as the game is played. The third (and optional) element of the patch design is bass tones that are generated from playing a small portion of a sample (or sample bank) using Lomas Sampler. Samples are fed through a low-pass filter to create bass/low end textures that will also have random probability. All outputs from RackNES and Lomas are fed via FM modulation into the drums, and with the EOC of the samples from Lomas triggering tom fills. Finally, the hi-hat module is set to a 1/4 clock divider for listening orientation, as the output of the alternating beat changes timbres and interdependency when continuously sequenced at random by a network of inter-deterministic CV values.*


**This patch was made in VCV Rack 2 Pro 2.5.2 on Windows 10, 48kHz sample rate, 8 processing threads.**


## **Installation**:

- Download and register for a free or paid version of VCV Rack 2 from www.vcvrack.com


- Install recommended module libraries: [Recommended Module Libraries](https://github.com/maxedonia/VCV2_PATCH_TETRIX/blob/main/README.md#recommended-module-libraries)


- Clone **textrix** repo:


   `git clone https://github.com/maxedonia/VCV2_PATCH_TETRIX.git`



- Open *tetrixxx_8.31.2024_v2.5.vcv* (or latest version) to launch **tetrix** in VCV RACK 2.
  
- Start JW Module Clock for playback!
  

**Depending on your VCV Rack 2 settings, you may need to do the following in order to hear playback:**


- Load *.nes* file into kautenjaDSP RackNES module
  
- Load *AW samples* (or your sample bank) into Lomas Sampler

- Check for any missing module libraries

- Change audio output module settings in VCV and/or your computer's native I/O settings.


## Video Demonstration [Here](https://youtu.be/acnlVYxxT5I)


![tetrixxx example image](https://github.com/user-attachments/assets/b0250c32-173d-43fb-a236-9c0c02f5a525)

  *As shown, the variability of output can significantly change due to the recursive nature of CV output from one module to that other(s). This variability can be most easily observed by changing the Lomas sample bank, altering the length of the sample start/end window, or by controlling RackNEs directly to create changes to the gameplay or .nes file loaded into the module.*


![toms and texture](https://github.com/user-attachments/assets/a5d03bf2-a8a6-4acf-a2d1-c303b61c637b)

  *Tip: A larger start/stop playback window will generate more bass tones, whereas a shorter window will trigger more tom fills throughout pattern. Import your own samples and attenuate them with OCT module for entirely different bass tones and tom patterns.*




## **Recommended Module Libraries**:

[JW](https://github.com/jeremywen/JW-Modules)

[Hetrick](https://github.com/mhetrick)

[KautenjaDSP](https://github.com/Kautenja)

[Lomas](https://github.com/DISTRHO/Cardinal/issues/652)

[Vult](https://github.com/vult-dsp/vult)

[Bog Audio](https://github.com/bogaudio/BogaudioModules)

[MindMeld](https://github.com/MarcBoule/MindMeldModular)

[Count Modula](https://github.com/countmodula/VCVRackPlugins)



### Additional Info: 

*Max Deadroom is Max Lewis, a music programmer, designer, audio engineer, professor, and lecturer at UC Denver.*


*Patch author does not seek nor have developer credit for Tetris™. Tetris is copyrighted by Tetris Holding, LLC, 1996 et. al.*

*Included samples for Lomas Sample Module were recorded by **[max_Deadroom](https://maxedonia.myportfolio.com)** from *Another World, 20th Anniversary Edition* for PC. 

*[Another World](https://www.moma.org/collection/works/162458) is copyrighted by Éric Chahi, 1991, 2024.*

*This synthpatch is for demonstration purposes only.*

