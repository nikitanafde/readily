# readily[README.md](https://github.com/user-attachments/files/33631504/README.md)
# Readily

**Read. Easily. Readily.**

Readily is a reading tool that lets you set up long text the way your eyes like it, then read at your own pace. It was built by a team of college students for the **Technica 2026 Hackathon** in 24 hours.

## Why we built it

School is a big part of our lives, and we wanted to make something people could use as a tool for their education. We have seen how hard it is for people with dyslexia, farsighted vision and ADHD to read long texts in small, hard-to-read fonts. Readily is our answer to that problem, and a step toward a more inclusive tech community.

## Features

- **Add your text:** paste or type it, or open a PDF or `.txt` file.
- **Make it easy:** change the font, italics, text size, text weight, line spacing, letter spacing and word spacing, with a live preview.
- **Dyslexia-friendly fonts:** Lexend, OpenDyslexic, Atkinson Hyperlegible, Andika and more.
- **Colours:** pick a page colour and a text colour from the presets, or save your own custom colours. A contrast readout tells you how readable your combination is.
- **Read aloud:** hear the text spoken while each word is highlighted, with voice speeds from 0.5x to 2x.
- **Reader view:** distraction-free reading with word highlighting and quick text size controls.
- **Focus line:** highlight one line at a time to help keep your place. Use the up and down arrow keys or tap a word to move it.
- **Accounts (prototype):** log in to save your custom colours. Accounts are stored only in your browser, not on a server.

## Getting started

Readily is a single self-contained HTML file with no build step.

1. Download `readily_final.html`.
2. Open it in a modern browser (Chrome, Edge, Safari or Firefox).

If you use VS Code, you can also right-click the file and use the **Live Server** extension.

### Internet connection

Most things work offline, because the main reading fonts are embedded in the file. A few things need a connection:

- Opening PDFs uses [PDF.js](https://mozilla.github.io/pdf.js/), loaded from a CDN.
- A few of the extra fonts and the page styling are loaded from Google Fonts.

## How to use it

1. **Add your text:** paste text into the box, or choose **Open PDF or text file**.
2. **Make it easy:** adjust the font, spacing and colours until the preview looks comfortable. To add your own colour, press **+**, pick a colour, then press **Save colour**.
3. **Listen & start:** optionally switch on **Read aloud** and choose a voice speed, then press **Start reading**.
4. In the reader, use **Listen** and **Stop** for audio, **Highlight** and **Focus line** to help you track, and **A−** and **A+** to resize the text. Press **← Edit** to go back to your settings.

## Built with

- HTML5, CSS3 and vanilla JavaScript (no frameworks)
- The browser's built-in Web Speech API for read aloud
- PDF.js for reading PDF files
- `localStorage` for saving your settings and prototype accounts

## Notes and limitations

- This is a hackathon prototype, not a finished product.
- Read aloud depends on the voices installed on your device and may not work in every browser.
- PDF text extraction works best with text-based PDFs. Scanned image PDFs may not produce any text.
- Settings and accounts live only in your browser. Clearing your browser data removes them.

## Team

Built for the Technica 2026 Hackathon.
