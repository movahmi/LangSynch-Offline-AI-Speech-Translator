
# LangSynch: Offline AI Speech Translator

## Overview
LangSynch is a Rust-based offline speech translator designed for real-time multilingual conversations. The project is optimized for edge devices to ensure privacy and portability.

## Features
- **Speech-to-Text (STT)**: Converts spoken language into text using Whisper.
- **Translation**: Translates text into multiple languages.
- **Text-to-Speech (TTS)**: Converts translated text back into speech.

## Installation
1. Clone the repository:
   ```bash
   git clone <repo-url>
   cd langsynch
   ```
2. Install Rust:
   [Rust installation guide](https://www.rust-lang.org/tools/install)

3. Build the project:
   ```bash
   cargo build
   ```

## Usage
1. Place your input audio file as `input_audio.wav`.
2. Run the application:
   ```bash
   cargo run
   ```

## Models
- Whisper STT Model: Place the model file in `models/whisper_model.bin`.
- Vosk TTS Model: Place the model folder in `models/vosk_model`.

## Contribution
Feel free to fork this repository and make improvements! Pull requests are welcome.
