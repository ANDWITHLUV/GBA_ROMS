# POCKET AUDITION
Pocket Audition may allow users to quickly and simply build instruments using the GBA's four PSG channels and test their sounds wihtin a limited range. Instruments may be able to play sounds in octaves [2,8] using keys {C , C#, D , D#, E , F , F#, G, G#, A , A#, B}. The GBA festures four PSG channels: Duty+Sweep, Duty, Wave, and Noise. This application follows the same ordering, except the channels are offset by one. While the GBA produces frequencies from user provided rates, this application does not calculate them, instead it looks them up in a table. The formula for calculating rates can be found within various guides. The calculations this application uses in its LUT were ceiled before differing with 2048. The tunings for C2 are: RATE octave_2 {43,156,262,363,457,546,631,710,785,856,922,986}. Users may need to take note that the GBA's noise channel four seems to feature only 60 distinct states. The application features four main sections: Keys, Scales, Controls, and Settings. 

# IT IS RECOMMENDED THAT USERS BE FAMILIAR WITH GBADOC AND TONC AND GBATEK AND PANDOCS SECTIONS ON THE GBA SOUND HARDWARE BEFORE USING THE APPLICATION. ALSO, THOUGH OUTPUT IS NON-DISCRETE THE INPUTS ARE NOT, AND MAY BE EASILY VISUALIZED. IT MAY BE TO THE USERS GREATEST BENEFIT TO DRAW PICTURES TO AIDE THEIR INTUITIONS.

## Keys
The key section features 8 keys, each with an assignable instrument. Their range, regardless of channel or instrument, are octaves [2,8] * keys {C , C#, D , D#, E , F , F#, G, G#, A , A#, B}. Whether a particular channel or instrument construction can play those frequencies, is another matter.
- Change Octave\Key hold Left-Button
- Change Control assignment hold B-Button
- Navigate left and right using L\R Arrow-Buttons
- Press A-Button to play Key

## Scales
The Scales Section features an 8 degree scale with individually assignable degrees that correspond to the 8 keys in the key section
- Assign key hold Left-Button and press up or down
- Navigate hold Left-Button and L\R Arrow-Buttons
- Play scale hold Left-Button and press Start-Button

## Controls
The Controls Section features 24 assignable controls that map only to the currently selected key
- Navigation hold the Left-Button
  - Navigate L\R Arrow-Buttons
  - Load press the A-Button
- Copy Control settings hold the Right-Button
  - copy all hold A Button + up
  - copy only settings hold A Button + left
  - copy only 0x hold A Button + right
  - copy only name hold A Button + down
  - Un-copy hold A Button + select-Button
  - Paste Start-Button

## Settings
The Settings Section features five navigable areas. At the settings Section's upper left is the channel indicator. Next to the channel indicator is the instrument name. Below channel indicator and instrument name are the instrument settings. To the left of instrument settings are the key bindings. To the left of key bindings is the color palette selector. Bellow the instrument settings are the 0x entries that correspond to a 128 bit arbitrary wave sample, ordered starting from the top left 0,1,2,3 then bottom left 4,5,6,7.

  
