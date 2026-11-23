# Chord Roulette

Tap the pick and get a random guitar chord, with everything about it:

- **Notes and formula**: each note spelled correctly for the chord (so C dim7 is C E♭ G♭ B♭♭, not "A"), its interval from the root, and how the chord stacks up in 3rds.
- **Every inversion**: the slash-chord name (C/E, C/G…), which note is in the bass, the notes from bottom to top, figured bass for triads and 7ths, a keyboard view, and what that inversion is used for.
- **Guitar shapes for each inversion**: up to four playable fingerings per inversion across the neck, with dots labelled by interval or note name. Tap any shape to hear it.
- **Sound and use**: what the chord sounds like and where you'll hear it.
- **Keys it belongs to**: its roman numeral in every major, natural minor, harmonic minor and melodic minor key.
- **Same notes, different name**: for example C6 = Am7, Csus2 = Gsus4, and the symmetric dim7 and augmented chords.

There are 34 chord types × 12 roots (408 chords): triads, sus and power chords, 6ths and add9s, 7ths, 9ths/11ths/13ths, and altered and Lydian chords. **Options** lets you limit the chord types, lock the root note, and turn auto-play on or off.

It's one self-contained `index.html` file with no build step and no libraries. The sound is synthesised in the browser (a plucked-string model), so there are no audio files either.

## Live site

**https://dreadcaptjames.github.io/chord-randomizer/**

If that link doesn't load yet, turn on GitHub Pages: **Settings → Pages → Build and deployment**, set **Source** to *Deploy from a branch*, choose **main** and **/ (root)**, then **Save**. It goes live a minute or two later.

## Tips

- **No sound on iPhone?** Turn off the silent switch. iOS mutes web audio when the phone is on silent.
- Every chord has its own link, for example `https://dreadcaptjames.github.io/chord-randomizer/#C_maj7` or `…/#Fs_m7b5`. The **Share** button sends the current one.
- On a computer, press **Space** for a new chord.
