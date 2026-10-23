ULTRA STREET FIGHTER II — EASY INSTALL INSTRUCTIONS 
**MAME ONLY BUILD: .289 Recommended**
**CONFIRMED DARKSOFT COMPATIBLE**

Full Audit completed. Optimized repeated intro calculations, changing only 21 ROM bytes. 
All 1,042 reference frames, timing, and audio remain identical. Passed nine MAME 0.289 regression checks 
and extended attract and two-player tests. Physical CPS2 hardware remains untested.

**CONVERTED FROM STRYGO'S USF2 BUILD KIT w/CORRECTED INTRO**

https://arcadepatches.com/usf2-backport/

You need this UltraSF2 patch kit and the matching World version of ssf2t.zip (non-merged).

INSTRUCTIONS:

WINDOWS 10/11 (64-BIT)

1. Right-click this ZIP and choose "Extract All".
2. Open the extracted folder.
3. Double-click "UltraSF2-Patcher.exe".
4. Drag your "ssf2t.zip" onto the box in the browser window.
5. Wait for "Complete", then click "Save hsf2.zip".
6. Put the saved hsf2.zip in your emulator's ROM folder.

Keep the small console window open until patching finishes.
Click "Close patcher" when done.

Internet is required on the first run. Later runs can use the encrypted
cache in the Data folder. You can delete Data to clear that cache.

Use the complete Super Street Fighter II Turbo World set. If the patcher
rejects the input, check that you selected the correct, undamaged set.
Your original ssf2t.zip is never changed.

**REVISION 2 UPDATES**

UltraSF2 – Dev (CPS2, Native): Combined Update Notes

This cumulative list combines our build’s corrections with Strygo’s latest integrated hsf2alt fixes.

Evil Ryu and Violent Ken gameplay:

•	Corrected super-meter checks so supers require and consume a full meter.

•	Fixed conflicts between normal kicks, custom dashes and super moves.

•	Corrected Violent Ken’s close-range six-hit super sequence.

•	Restored Violent Ken’s dash trails and victory animations.

•	Restored purple fist flames and orange burn reactions.

•	Corrected Evil Ryu’s pose orientation.

•	Restored Evil Ryu’s white background during the Demon combo.

•	Restored Demon super-finish effects and the 10,000-point bonus.

•	Added both characters to Random character selection.

Character selection, portraits and HUD:

•	Fixed the swapped Dee Jay and Balrog character selections.

•	Updated Evil Ryu and Violent Ken’s character portraits, selected faces and animated defeated portraits.

•	Corrected both characters’ Continue portraits and revival animations.

•	Fixed portrait colors after character selection and Continue.

•	Restored missing portrait blocks.

•	Corrected HUD lettering and Guile/Cammy HUD colors.

•	Corrected Zangief’s portrait shading.

•	Restored the correct CPU opponents and portraits after another player challenges.

Stages and travel:

•	Fixed Cammy’s thin horizontal scrolling-line glitch.

•	Corrected background gaps in Cammy, Claw, Dee Jay and Fei Long’s stages.

•	Removed stray player markers during travel.

•	Smoothed the stage-selection airplane movement.

•	Corrected the mirrored Spain flag.

•	Restored Guile’s Sonic Boom and Dee Jay’s Air Slasher colors across costume selections.

Audio

•	Rebuilt ordinary character voices, announcer cues, effects and music around the native Hyper Street Fighter II sound banks.

•	Corrected sound routing, sample addresses, pitch and loop settings.

•	Cleared unused old audio slots and unused exception-bank data.

•	Corrected gameplay sound routing that could trigger the title announcement during rounds or round transitions.

•	Evil Ryu and Violent Ken now use their dedicated hsf2alt gameplay voices, including heavy attacks, projectile calls, multipart supers, damage and death sounds.

•	Removed the standard Ryu/Ken voice fallbacks from those two characters’ corrected voice routes.

•	Applied the appropriate variant winner announcements and ending-audio mappings.

•	Preserved standard Ryu and standard Ken’s corrected Hyper audio.

•	Preserved the correct ULTRA intro voices, including Violent Ken’s intro voice.

•	Restored the exact original ULTRA CAPCOM and 30th Anniversary splash recordings.

•	Increased only the 30th Anniversary clip by 50%.

•	Preserved the supplied title-announcer recording at its corrected playback speed and pitch.

•	Removed the unwanted second “THE FINAL CHALLENGERS” announcement beneath the title recording.

Intro and title presentation:

Existing corrections, retained in the combined build:

•	Removed the lighter box behind the FBI warning lettering.

•	Corrected Ryu’s intro fireball graphics and placement between his palms.

•	Prevented the ULTRA logo from appearing over warning and service screens.

•	Fixed the broken animation and vertical alignment of the A in ULTRA.

•	Removed the extra white flash after the logo’s white transition.

•	Doubled the speed of the STREET FIGHTER II title slide.

•	Restored the subtitle lettering’s colors and completed the colored bar above it.

•	Corrected the ULTRA logo’s coin-in transition to fade in smoothly.

•	Made the complete title fade out together.

•	Restored the ULTRA logo’s progressive color-fill effect.

•	Optimized native intro animation and palette handling.

•	Preserved the corrected cinematic sprites, frame timing and title presentation during the Strygo integration.

Game flow and service menus:

•	Restored the normal Insert Coin and Free Play positions outside the title screen.

•	Restored the return to attract mode after endings and credits.

•	Cleared ending-specific state when credits finish so it cannot affect the next game.

•	Fixed INPUT and OUTPUT service-menu navigation and return controls.
•	Set Demo Sound to ON by default in every factory preset.

The combined build also retains NEONBitchi intro/title presentation and existing standard-character audio. Strygo’s intro/Japanese title-copyright changes and standard Ken/Chun-Li ending-music changes were excluded (because they’d already been implemented). Evil Ryu and Violent Ken’s ending audio is included.
