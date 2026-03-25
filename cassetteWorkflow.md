# Cassette workflow
# (adapted from [Audio Tape Digitisation Workflow](https://musiikkiarkisto.fi/audio/))

## 1. Inspect for damage
  * Broken shell
  * Contamination
  * Broken tape
  * Missing felt pad
  * Loose strands/windowing
## 2. Break tabs
## 3. Determine cassette type
  * Normal: select "Type I" in deck
  * Chrome or metal: select "Type II" or "Type IV" in deck
## 4. Determine noise reduction
  * "NR", "Dolby", "dbx"
## 5. Wind tape
## 6. Generate Archival Object in ArchivesSpace
## 7. Clean cassette deck
  1. Use qtip dipped in distilled water to clean pinch rollers
  2. Use qtip dipped in alcohol to clean head **in the direction of tape travel**
  3. Use qtip dipped in alcohol to clean capstan(s)
## 8. Create new file in Adobe Audition
  * Name file according to this pattern: `CollCode_b000_f000_archObj00000_[YYYY-MM-DD or other text].wav`
  E.g. `DCHA_b001_f001_archObj56731_1976-05-22FieldNotes.wav`)
  * WAVE file, Linear PCM, 96000 Hz, stereo
  * Open Window > metadata
    * choose "RIFF" tab
    * Enter ArchivesSpace URL in "Source supplier" field
    (e.g. `https://centroarchives.hunter.cuny.edu/repositories/2/archival_objects/56731`)
## 9. Record
  * Open Window > phase analysis
    * choose "phase wheel" at bottom left  
## 10. Set levels
  * When levels on deck hit 0 dBVU, it should be around -21 dBFS in Audition
  (mostly this is preset)
## 11. Adjust azimuth
  * Phase wheel will waver but should be centered for mono
  * Stereo program: use your ear by listening to high pitch 
  (e.g. sibilance) and getting maximum high frequency
## 12. Record again, with feeling
  * Undo previous recording
  * Rewind tape
  * Start over
  * Keep an eye on azimuth and adjust as needed
## 13. Enter metadata
  * In metadata window, go to BWF tab
  * In "Coding History" field, enter the following:
    `A=ANALOG,M=mono,T=Nakamichi Cassette Deck 1,
A=PCM,F=96000,W=24,M=stereo,T=Sound Devices Mix Pre-6,
` followed by any sound issues you notice **but do not use commas**
## 14. Add cue marker for Side B
  * You can pause recording if you want
## 15. Finish recording
  * Get rid of long silent packages
  * Make sure you keep the "Side B" marker
