# POCKET AUDITION
Pocket Audition may allow users to quickly and simply build instruments using the GBA's four PSG channels and test their sounds wihtin a limited range. Instruments may be able to play sounds in octaves [2,8] using keys {C , C#, D , D#, E , F , F#, G, G#, A , A#, B}. The aplication features four main secxtions: Keys, Scales, Controls, and Settings. Key bindings can be found in the settings area's right hand side. These key bindings will change as you employ them. The Gba festures four PSG channels: Duty+Sweep, Duty, Wave, and Noise. This application follows the same order acceppt the channels are offset by one. The Gba produces frequencies from user provided rates. The rate tunings are not c=alculated in app instead they are looked up in a table. Calculations were made on the entrire number then ceiled before differing with 2048. The tunings for C2 are: RATE octave_2 {43,156,262,363,457,546,631,710,785,856,922,986}. The GBA's noise channel four seems to feature only 60 distinct states so their is key ovelap past the greatest state. From the notes it seems high A higher frequency will make the noise to appear 'softer'.    Depending on the frequency the noise will appear 'harder' or 'softer'. it does not use rate calculations.  though output is non discrete the inputs are not. and may be easily visulaized draw pictures. 

# IT IS RECOMMENDED THAT USERS BE FAMILIAR WITH GBADOC AND TONC AND GBATEK AND PANDOCS SECTIONS ON THE GBA SOUND HARDWARE BEFORE USING THE APPLICATION. 

## Keys
The key section features 8 keys, each with an asignable instrament. their range, regardless of channel or instrument, are octaves [2,8] * keys {C , C#, D , D#, E , F , F#, G, G#, A , A#, B}, whether a particlular channel or instrument construction can play those frequencies, is another matter.
- Change Ocrtave\Key hold Left-Button
- Change Control assignment hold B-Button
- Navigate left and right using L\R Arrow-Buttons
- Press A-Button to play Key
## Scales
The Scales Section fetures an 8 degree scale with individually assignable degrees that correspond to the 8 keys in the key section
- Assign key hold Left-Button and press up or down
- Navigate hold Left-Button and L\R Arrow-Buttons
- Play scale hold Left-Button and press Start-Button
## Controls
The Controls Section fetures an 24 assignable controls that will only assign to tyhe currently selcted key
- Navigatiopn hold the Left-Button
  - Navigate hold Left-Button and L\R Arrow-Buttons
  - Load press the A-Button
- Copy Control settins hold the Right-Button
  - copy all settings hold A Buton + up
  - copy only settings hold A Buton + left
  - copy only 0x hold A Buton + right
  - copy only name hold A Buton + down
  - Uncopy hold A Buton + select-Button
  - Paste Start-Buton +
## Settings
The settings Section fetures five navigabvle areas. At the upper left is the channel  next to it the instrument name. below that are the settings to the left of them are the key bindings. bellow that are the 0x entries on the far right is the color pallete. The GBA has two modes for it Wave chanel three the application uses the mode 0 whjich utilizes a 128 bit arbitrary wave sample hence the 8 sections of hex values. order is starting top left 0,1,2,3 then bottom left 4,5,6,7
