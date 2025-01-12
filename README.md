# Text-to-Speech Web Application

## Overview
This project is a simple Text-to-Speech (TTS) web application that allows users to input any text and hear it spoken aloud. The application uses the built-in `SpeechSynthesis` API available in modern web browsers to convert text into speech.

## Features
- Input text using a text box.
- Click a button to convert the text to speech.
- Adjustable voice properties like rate, volume, and pitch (predefined in the script).
- Minimalist and responsive user interface.

## Live Demo
[Live Demo]((https://amal-rekshin.github.io/Text_To_Speech/))

## Getting Started

### Prerequisites
- A modern web browser (e.g., Chrome, Edge, Firefox) with support for the `SpeechSynthesis` API.

### Usage
1. Open the application in your browser.
2. Type any sentence into the text area.
3. Click the **Speak** button to hear the text spoken aloud.

## Technologies Used
- **HTML**: For structuring the web page.
- **CSS**: For styling and layout.
- **JavaScript**: For handling the Text-to-Speech functionality using the `SpeechSynthesis` API.

## File Structure
```
text-to-speech-app/
├── index.html   # Main HTML file
└── README.md    # Documentation
```

## Example Output
- Input: "Hello, world!"
- Speech Output: A voice reads "Hello, world!" aloud.

## Error Handling
- If the browser does not support the `SpeechSynthesis` API, the application will not function properly.
- Users need to ensure their device audio is enabled to hear the output.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments
- Built using the browser's native `SpeechSynthesis` API.

