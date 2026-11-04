# Voice Notes

A browser-based speech-to-text page. Choose **Microphone** to use the browser's speech recognition, or **Computer/tab audio** to transcribe audio shared from a browser tab or screen. Computer-audio transcription runs locally in the browser; the speech audio is not uploaded. The transcription library and model are downloaded from public CDNs the first time that mode is used and cached by the browser.

For computer audio, use a recent Chrome or Edge browser on an HTTPS page or `localhost`. Select a tab or screen in the browser's sharing prompt and enable its audio-sharing option. The model may take time to download and initialize on first use. Microphone transcription continues to use the browser's built-in speech-recognition service and requires an internet connection.

## Deploy to Vercel

This is a static site with no build step. Import this repository into Vercel and use:

- Framework preset: **Other**
- Build command: leave blank
- Output directory: `.`

Vercel will serve `index.html` from the project root.
