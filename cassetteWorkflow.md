# Cassette Digitization Workflow
### (adapted from [Audio Tape Digitisation Workflow](https://musiikkiarkisto.fi/audio/))

### Allow for 2x to 3x the length of the program!!
**(i.e., allow *at least* two hours for a one-hour cassette)**

## 1. Inspect for damage
  * Broken shell
  * Contamination
  * Broken tape
  * Missing felt pad
  * Loose strands/windowing
## 2. Break tabs
## 3. [Determine cassette type](https://www.walkman-archive.com/articles/cassette-walkman-faq-01.html)
  * Normal: select "Type I" in deck
  * Chrome or metal: select "Type II" or "Type IV" in deck
## 4. Determine [noise reduction](https://www.avartifactatlas.com/artifacts/noise_reduction.html)
  * "NR": *Check with supervisor*
  * "Dolby": Select Dolby B
  * "Dolby C": Select Dolby C
  * "DBX": Do not digitize
## 5. Wind tape, then rewind tape
  * This is called "exercising" the tape
  * It halps with pack and print-through
## 6. [Create Archival Object in ArchivesSpace](https://rs4.reuther.wayne.edu/SuperManual/02_arrangement/02_04_archival_objects/#:~:text=A%20%22child%22%20Archival%20Object%20will,Objects%20to%20a%20given%20record.)
## 7. [Clean cassette deck](https://www.instructables.com/How-To-Clean-a-Cassette-Recorder/)
  1. Remove cassette cover
  2. Use qtip dipped in distilled water to clean pinch rollers
  3. Use qtip dipped in alcohol to clean head **in the direction of tape travel**
  4. Use qtip dipped in alcohol to clean capstan(s)
## 8. [Create new file in Adobe Audition](https://helpx.adobe.com/pl/audition/using/creating-opening-files.html)
  * Name file according to this pattern:
    ```
    CollCode_b000_f000_archObj00000_[YYYY-MM-DD or other text].wav
    ```
    For example,
    ```
    DCHA_b001_f001_archObj56731_1976-05-22FieldNotes.wav
    ```
  * WAVE file, Linear PCM, 96000 Hz, stereo
  * Open Window > metadata
    * choose "RIFF" tab
    * Enter ArchivesSpace URL in "Source supplier" field
    (e.g. `https://centroarchives.hunter.cuny.edu/repositories/2/archival_objects/56731`)
## 9. [Record in Audition](https://helpx.adobe.com/audition/using/recording-audio.html)
  * Open Window > phase analysis
    * choose [phase wheel](https://www.adobe.com/learn/audition/web/audition-phase-analysis-cc) at bottom left  
## 10. Set levels
  * [Load Preset 1](https://guides.sounddevices.com/mixpre-ii/#h.5st7cduhcazl) in MixPre-6 recorder
  * When levels on deck hit 0 dBVU on the deck, they should be around -20 dBFS in Audition
  * This should be preset, but as follows:
       * Max output level on deck
       * Channel 1 knob (level) at 1PM
       * Channel 2 knob (pan) at center
## 11. Adjust azimuth
  * [Phase wheel](https://youtu.be/JF0IofTEii0?t=212&si=PBbAUfiH0fjG7Miu) will waver but should be centered as a straight line up for mono programs
  * Stereo program: use your ear by listening to maximize high pitch 
  (e.g. sibilance) and getting maximum high frequency
## 12. Record again, with feeling
  * **Undo previous recording**
  * Rewind tape
  * Start over
  * Keep an eye on azimuth and adjust as needed
## 13. Enter metadata
  * In metadata window, go to BWF tab
  * In "Coding History" field, enter the following (on first line, if program is in stereo of course enter `M=stereo`):
    ```
    A=ANALOG,M=mono,T=Nakamichi Cassette Deck 1,
    A=PCM,F=96000,W=24,M=stereo,T=Sound Devices Mix Pre-6
    ```
followed by any [sound issues](https://www.avartifactatlas.com/tags.html#audio) you notice **but do not use commas**

## 14. Add [cue marker](https://helpx.adobe.com/audition/using/markers.html) for Side B
  * You can pause recording if you want
## 15. Finish recording
  * Make sure you keep the "Side B" marker!
