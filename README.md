# AyoBaca

AyoBaca is a browser-based early literacy app for children learning letters and beginning to read in Indonesian or English. It combines letter-sound practice, syllables, word blending, handwriting practice, and a gentle quiz in one responsive page.

## Features

- **Alphabet and phonics:** Explore A-Z, uppercase and lowercase letters, letter names, sounds, vowel/consonant labels, illustrated example words, syllable breaks, and example sentences. Play individual sounds or read through the alphabet.
- **Open syllables:** Choose a consonant to hear and practice its combinations with the vowels A, I, U, E, and O, with an example word for each selection.
- **Blend words:** Practice words by tapping their syllable or sound boxes, then hear the complete word. Browse the available word examples.
- **Trace letters:** Draw letters on a touch-friendly canvas, choose a brush color, track drawing progress, replay the letter sound, and earn stars.
- **Sound quiz:** Listen to a prompt and choose the matching letter from three options. Correct answers earn stars; incorrect answers get a friendly retry prompt.
- **Indonesian and English:** Switch the interface, examples, and speech prompts between ID and EN.
- **Configurable speech:** Choose phonetic device speech or cloud Indonesian text-to-speech, select an available Indonesian device voice, and adjust speech speed. The phonetic mode is the default.
- **Progress and preferences:** Stars, speech mode, speech speed, and the selected Indonesian voice are saved in the browser's local storage.
- **Parent and teacher guide:** An in-app guide describes the learning approaches and includes references.

## Run locally

No build tools, package installation, or backend are required. Open `index.html` in a modern browser, or serve the project directory locally:

```sh
python3 -m http.server 8000
```

Then visit <http://localhost:8000>.

## Connectivity and audio

The app is a static HTML page. Tailwind CSS, Google Fonts, Twemoji illustrations, and confetti are loaded from external CDNs, so an internet connection is needed for those assets. Device speech depends on the browser and installed voices. The optional cloud Indonesian voice requires an internet connection; the default phonetic speech mode uses the browser's speech engine.

## Project files

- `index.html` contains the app interface, styles, learning content, and JavaScript behavior.
- `LICENSE` contains the GNU General Public License, version 3.

## License

This project is distributed under the GNU GPL v3. See [LICENSE](LICENSE) for the full text.