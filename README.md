# AI Bible Quotation App Test

## Overview
Build an AI Bible Quotation App that listens live during sermons and displays Bible quotations in real time. When the user taps a button, the app streams voice to a server. The server transcribes the audio using OpenAI Whisper (tiny model), streams the transcription to Google Gemini Flash (or an equivalent model) to extract a Bible quote address (if detected), queries a Bible database for the full quotation, and returns it for display.

## Requirements
- **Frontend:**  
  - A simple interface (web or app) with a button to start/stop live voice streaming.  
  - Real-time display of the Bible quotation.

- **Backend:**  
  - Accept a continuous audio stream from the frontend.  
  - Transcribe the audio in real time using OpenAI Whisper (tiny).  
  - Process the transcription with Google Gemini Flash (or an alternative AI model) to extract a Bible quote address when one is detected.  
  - Query your Bible quotations database to retrieve the full quotation.  
  - Return the full Bible quotation for live display on the frontend.

- **Flexibility:**  
  - You may use alternative AI models, stacks, or additional enhancements as desired.  
  - The end product is what matters; no internal code documentation is required.
 
## Resources
- **Design Specification:**  
  Review the design and implementation guidelines at [https://www.figma.com/design/8ebbsZw1iDQVUKsCOxWgZV/Full-Stack-Dev-Test?node-id=3-1377&t=YgGx0fzn0VoNAiNR-1](https://www.figma.com/design/8ebbsZw1iDQVUKsCOxWgZV/Full-Stack-Dev-Test?node-id=3-1377&t=YgGx0fzn0VoNAiNR-1) (redirects to Figma).
- **Bible Translations Database:**  
  [BibleTranslations on GitHub](https://github.com/jadenzaleski/BibleTranslations)
  Extract this database into your own database schema

## Submission
- Host your project on GitHub.  
- Submit your project via the [gigsama.com talent portal](https://talent.gigsama.com/).

Good luck!
