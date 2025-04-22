# Voice Chat AI Assistant

A Python application that creates an interactive voice-based conversation with an AI assistant. The application records your voice, transcribes it using OpenAI's Whisper model, processes the text through GPT-4, and responds using text-to-speech.

## Features

- Voice recording and playback
- Speech-to-text transcription using OpenAI's Whisper
- AI chat responses using GPT-4
- Text-to-speech conversion using OpenAI's TTS
- Continuous conversation loop

## Prerequisites

- Python 3.x
- OpenAI API key
- Required Python packages (see Installation)

## Installation

1. Clone this repository:
```bash
git clone <your-repository-url>
cd <repository-name>
```

2. Install the required packages:
```bash
pip install -r requirements.txt
```

3. Set up your OpenAI API key:
```bash
export OPENAI_API_KEY='your-api-key-here'
```

## Usage

1. Run the application:
```bash
python app.py
```

2. When prompted, speak into your microphone
3. The application will:
   - Record your voice input
   - Transcribe it to text
   - Process it through the AI
   - Play back the AI's response

## Project Structure

- `app.py`: Main application file
- `utils.py`: Utility functions for audio recording and playback
- `requirements.txt`: Python package dependencies
- `test.wav`: Temporary file for voice recording
- `output.mp3`: Temporary file for AI response audio

## Dependencies

All dependencies are listed in `requirements.txt`. The main packages include:
- openai: OpenAI API client
- Additional audio processing libraries (see utils.py)

## Notes

- Make sure your microphone is properly configured
- The application requires an active internet connection
- Keep your OpenAI API key secure and never commit it to version control

## Contributing

Feel free to submit issues and enhancement requests! 