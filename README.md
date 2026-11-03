**REQUIRES THE MERGED MAME VERSION OF SSF2T.ZIP / REQUIRES THE MERGED MAME VERSION OF SSF2T.ZIP / REQUIRES THE MERGED MAME VERSION OF SSF2T.ZIP**

*Extract the single file from qsound_hle.zip, and add it into your SSF2T.ZIP (MERGED SET)*

<img width="820" height="614" alt="image" src="https://github.com/user-attachments/assets/c21cd651-4170-4c2a-b44e-86b0ae2c3607" />

https://github.com/user-attachments/assets/cd63b14f-da15-4fb3-8cf1-a26d393ce70c
-
ULTRA STREET FIGHTER II (NATIVE CPS2) — EASY INSTALL INSTRUCTIONS 
**MAME BUILD: .289 Recommended**
**CONFIRMED DARKSOFT / CPS2 COMPATIBLE**

**SHOUT-OUT TO DUEY0x0 FOR ALL THE BUG HUNTING!**

**I WILL NO LONGER BE UPDATING THIS BUILD FOR PUBLIC NOTIFICATION**

Full Audit completed. Optimized repeated intro calculations, changing only 21 ROM bytes. 
All 1,042 reference frames, timing, and audio remain identical. Passed nine MAME 0.289 regression checks 
and extended attract and two-player tests. Physical CPS2 hardware remains untested.

## **CONVERTED FROM STRYGO'S USF2 BUILD KIT. THIS IS A MORE VISUALLY REFINED & FINE-TUNED RELEASE**

Source of Original Backport toolkit: https://arcadepatches.com/usf2-backport/

What you need for this UltraSF2 patch kit: matching World version of ssf2t.zip (non-merged).

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

# Ultra Street Fighter II: The Final Challengers
**CPS2 Native Development | Revision 6 | Combined Changelog**

## **REVISION 6 UPDATES**

- Fully repaired the title screen and restored correct color patterns.
- Custom pixel-art remake of Evil Ryu intro art.
- Corrected additional Violent Ken palette issues.
- Removed the ULTRA logo from the Sound Test menu.
- Completed full debugging and gameplay playthrough audits.
- Corrected remaining title-screen and intro issues.
- Fixed an additional Violent Ken palette bug affecting background graphics.
- Integrated Strygo's latest HSF2 fixes with Bitchi's existing corrections.

## ADDITIONAL BITCHI FIXES

- Repaired Evil Ryu's and Violent Ken's corrupted losing and Continue portraits.
- Fixed both characters' selected portrait colors reverting after Continue.
- Corrected Evil Ryu mirror matches so each player retains their independently selected portrait color.
- Eliminated interference between character-style icon palettes and Evil Ryu's portrait colors.
- Restored the native Hyper QSound "PERFECT" announcement for full-health victories.
- Restored the complete PERFECT banner, properly centered beneath the winner text with accurate lettering and colors.
- Ensured the PERFECT banner clears before score tallying and that ordinary victories trigger neither the announcement nor the banner.

## EVIL RYU & VIOLENT KEN GAMEPLAY

- Corrected super-meter checks so special supers require and consume a full meter.
- Resolved conflicts between normal kicks, custom dashes, and super moves.
- Corrected Violent Ken's close-range six-hit super sequence.
- Restored Violent Ken's dash trails and victory animations.
- Restored purple fist flames and orange burn reactions.
- Corrected Evil Ryu's pose orientation.
- Restored Evil Ryu's white background during the Demon combo.
- Restored Demon super-finish effects and the 10,000-point bonus.
- Added Evil Ryu and Violent Ken to Random character selection.

## CHARACTER SELECTION, PORTRAITS & HUD

- Fixed the swapped Dee Jay and Balrog character selections.
- Updated Evil Ryu's and Violent Ken's character portraits, selected faces, and animated defeated portraits.
- Corrected both characters' Continue portraits and revival animations.
- Fixed portrait colors after character selection and Continue.
- Restored missing portrait blocks.
- Corrected HUD lettering and Guile/Cammy HUD colors.
- Corrected Zangief's portrait shading.
- Restored the correct CPU opponents and portraits after another player challenges.

## STAGES & TRAVEL

- Fixed Cammy's thin horizontal scrolling-line glitch.
- Corrected background gaps in Cammy's, Claw's, Dee Jay's, and Fei Long's stages.
- Removed stray player markers during travel.
- Smoothed stage-selection airplane movement.
- Corrected the mirrored Spain flag.
- Restored Guile's Sonic Boom and Dee Jay's Air Slasher colors across costume selections.

## AUDIO & QSOUND

- Rebuilt standard character voices, announcer cues, sound effects, and music around the native Hyper Street Fighter II sound banks.
- Corrected sound routing, sample addresses, pitch, and loop settings.
- Cleared unused legacy audio slots and exception-bank data.
- Fixed gameplay sound routing that could incorrectly trigger the title announcement during rounds or transitions.
- Integrated Evil Ryu's and Violent Ken's dedicated `hsf2alt` gameplay voices, including heavy attacks, projectile calls, multipart supers, damage, and death sounds.
- Removed standard Ryu/Ken voice fallbacks from Evil Ryu's and Violent Ken's corrected audio routes.
- Applied appropriate character-variant winner announcements and ending-audio mappings.
- Preserved standard Ryu's and Ken's corrected Hyper audio.
- Preserved the correct ULTRA intro voices, including Violent Ken's introduction.
- Restored the exact original ULTRA CAPCOM and 30th Anniversary splash recordings.
- Increased only the 30th Anniversary recording's volume by 50%.
- Preserved the supplied title-announcer recording at its corrected playback speed and pitch.
- Removed the unwanted secondary "THE FINAL CHALLENGERS" announcement beneath the title recording.

## INTRO & TITLE PRESENTATION

- Removed the lighter background box behind the FBI warning lettering.
- Corrected Ryu's intro fireball graphics and positioning between his palms.
- Prevented the ULTRA logo from appearing over warning and service screens.
- Fixed the broken animation and vertical alignment of the "A" in ULTRA.
- Removed the extra white flash following the logo's white transition.
- Doubled the speed of the STREET FIGHTER II title slide.
- Restored subtitle lettering colors and completed the colored bar above it.
- Corrected the ULTRA logo's coin-in transition for a smooth fade-in.
- Ensured the complete title fades out together.
- Restored the ULTRA logo's progressive color-fill effect.
- Optimized native intro animation and palette handling.
- Preserved corrected cinematic sprites, frame timing, and title presentation during Strygo's integration.

## GAME FLOW & SERVICE MENUS

- Restored the normal Insert Coin and Free Play prompt positions outside the title screen.
- Restored the return to attract mode following endings and credits.
- Cleared ending-specific states after credits to prevent interference with subsequent games.
- Fixed INPUT and OUTPUT service-menu navigation and return controls.
- Set Demo Sound to ON by default across all factory presets.

---

**Revision 6 Summary:** Cumulative integration of Bitchi's native CPS2 development fixes and Strygo's latest HSF2 corrections, covering character gameplay, palettes, portraits, audio, stage rendering, intro presentation, title-screen behavior, and service-menu functionality.

The combined build also retains NEONBitchi intro/title presentation and existing standard-HYPER-character audio. Evil Ryu and Violent Ken’s ending audio is included.
