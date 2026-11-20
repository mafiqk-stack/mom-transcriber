# KTMB Meeting Transcriber

A single web page that records a meeting on an iPad (or takes an audio file), sends the audio to OpenAI speech-to-text, and returns a transcript that keeps mixed Bahasa Melayu and English as spoken. The transcript is then pasted into the KTMB MoM Recorder to produce formal minutes in Word.

- Open: https://mafiqk-stack.github.io/mom-transcriber/
- The OpenAI API key is stored only in the browser on the device that uses it (localStorage). It is never committed here and is sent only to api.openai.com.
- Recordings are kept on the device (IndexedDB) until "Delete recordings" is tapped. Long recordings are split into 10-minute pieces before upload.
- This repository holds only the page's code, no meeting content.
