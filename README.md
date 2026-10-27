## Amiga Kick Off 2 Graphics Restyle v2.1
![alt text](https://github.com/KONEY/ko2-gfx-restyle-adf-amiga/blob/main/imgs/splash_biglogo.png?raw=true)
##### Based on Kick Off 2 Competition Version v1.39 by Steve Camber
##### https://kickoff2.com/#ko2cv
##### https://github.com/KONEY/ko2-gfx-restyle-adf-amiga
##### https://ko-gathering.com/
##### https://koney-scanlines.tumblr.com/post/825115318581182464/amiga-kick-off-2-gfx-v20-by-koney-preview
---------------------------------------------

This HACK only involves edits to graphic assets; no changes were made to the game core with small exceptions. Changes made to the program were team colours palette, default kits, default team colours, pitch names and forcing on CV option "ALL PITCHES NORMAL"
It is BASED on but NOT SPECIFIC for CV 1.39.

#### v2.1 Update
8 new pitches, some new kits, a palette update, a new splash screen.
This skips v2.0 because it's already shipped with CV 1.39. When a new CV will be out v1.1 will become v1.2 and this, guess what, v2.2 ;)

---------------------------------------------
### KITS
We need to explain a bit how KO1 graphics are organised: the game runs on a 16-colour screen; 8 colours are reserved for the pitch and 8 for players + the ball. 
These 8 are assigned as follows:
1. Transparency
2. Player hair (Black)
3. Player skin (pink)
4. Team A primary colour (red)
5. Team B primary colour (blue)
6. Both teams' secondary colour + ball (white)
7. Goalkeeper main colour (light green)
8. Shadows (Dark Green)
   
In KO2, in order to add a secondary colour for each team, the luminosity of the ball and player skin colours were changed so that the skin was so bright and the ball so reddish their colours matched. Then the goalkeeper's light green shirt was darkened so that it matched the colour for the shadow. This way an extra colour for each team shirt was made available.  

Visually, this sucks. Every kit involving some white makes no sense, as everything is now white on white. But thinking about when this was done, it makes perfect sense from a commercial perspective. 1990 was the year of Italy WC and being able to mimic more closely any team colours was a game changer for a football game. This also opened the way to more expansion data discs, so a definitely a commercial goal. But today, we play mostly with yellow and blue shirts, so I think it’s time to restore graphics from KO1 era!

Basically player reskin logic is based on reverting back to somehow colours were managed in Kick Off 1 :) 

#### KITs are modified as follows. Ball gets its color form Team A secondary and keeper details from Team B secondary.
+ KIT 1: Original Kick Off 2 KIT
+ KIT 2: With pants forced black
+ KIT 3: A mixture of kits with stripes forced black
+ KIT 4: Monochromatic, standard competition default kit.
+ KIT 5: Pants use secondary colour
+ KIT 6: KIT 4 but with blue shadows, to match the blue pitch.
+ GOALKEEPERS: Kick Off 1 sprites

However these descriptions should not be taken as absolute because a lot of "creativity" was added to designs. Some kit may have a few differences between Team A and B. Use the following diagram as a reference.

#### KITS diagrams
![alt text](https://github.com/KONEY/ko2-gfx-restyle-adf-amiga/blob/v2.1/imgs/kits.png?raw=true)


---------------------------------------------
### TEAM COLORS
Available colours from which to choose have been updated. Some colours changed and others were replaced with new ones. 
v2 has some small updates.
#### new KIT colour palette
![alt text](https://github.com/KONEY/ko2-gfx-restyle-adf-amiga/blob/v2.1/imgs/Team_Colors.png?raw=true)


---------------------------------------------
### BALL
The original sprite from KO1 is used; no more spots. Old design was much cleaner and made better sense. On a second thought and after beta-tester's feedback I decided to re-enable the spots but just when the ball is in high in the air. If on ground level, we assume spots are too small to be seen. 
Colours working nicely for ball are canonical white, light grey, yellow, orange and brown (early soccer leather balls).  
It's technically possible to have a green ball, maybe not a good idea :)

![alt text](https://github.com/KONEY/ko2-gfx-restyle-adf-amiga/blob/main/imgs/new_ball2x.png?raw=true)


---------------------------------------------
### PITCHES
**CV Option ALL PITCHES NORMAL is _ENABLED_  by default.**  
New designs are for visuals only; different behaviours of pitches are unwanted. 

All designs were made on a real Amiga with CRT, to ensure the best visual results for the real world. Because you're not using an emulator, right?!!!

#### Normal pitches become: 
+ Pitch 13 (from KO2 online)
+ Squares (Player Manager based)
+ Pitch 18 (from KO2 online)
+ Dried (Soggy after a sunny Summer :)

#### Final Whistle pitches become:
+ Classic restyle
+ Muddy
+ Bright
+ Synturf (blue pitch)


![alt text](https://github.com/KONEY/ko2-gfx-restyle-adf-amiga/blob/v2.1/imgs/pitch_tiles.png?raw=true)


------------------------------------------------------------
### OTHER ASSETS
+ Corner selectors are taken from KO2. Again, the old design made much more sense.
+ A newly designed loading screen.


------------------------------------------------------------
### TOOLS USED
* KO2PitchEditor 1.0 by Steve Camber
* DINO DINI FILE SYSTEM TOOLS v1.1.0 (needed to compile to .ADF files from this repo)
* Online Tileset Extractor by André Michelle
* IRA V2.11 ReAssembler (Amiga)
* Cloanto Personal Paint (Amiga)
* IFF-Arranger (Amiga)
* Photoshop CS6
* Vasmm68k_mot
* rndPdat.py
* combine_iff.py
* addDefHeaders.py
* applySineSlice.py
* generateGrassTexture.py
* findUnusedTilesPdat.py
* generateUnusedTilesMask.py
* pp2copper.rexx
* WinUAE 6.0.3

------------------------------------------------------------
### THANKS TO
Alkis Polyrakis, which can be only described as a KickOff veteran, for betatesting the game and giving importat feedback.
Steve Camber, which can be only described as a KickOff hero, for all the collaboration and support.


------------------------------------------------------------

![alt text](https://github.com/KONEY/ko2-gfx-restyle-adf-amiga/blob/v2.1/imgs/188.png?raw=true)

![alt text](https://github.com/KONEY/ko2-gfx-restyle-adf-amiga/blob/v2.1/imgs/192.png?raw=true)

![alt text](https://github.com/KONEY/ko2-gfx-restyle-adf-amiga/blob/v2.1/imgs/200.png?raw=true)

![alt text](https://github.com/KONEY/ko2-gfx-restyle-adf-amiga/blob/v2.1/imgs/194.png?raw=true)








