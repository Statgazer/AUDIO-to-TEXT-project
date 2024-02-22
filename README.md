# GitHub Repository README

Welcome to our GitHub repository! This repository is dedicated to a streamlined audio-to-text transcription project utilizing OpenAI's Whisper model and PyDub for audio manipulation. Our aim is to provide an efficient and accurate method for converting audio files into text, making it easier to work with long audio sessions like podcasts, interviews, and lectures.

## Features

- **Audio Splitting:** Utilizes PyDub to split large audio files into manageable chunks, ensuring the transcription process is both efficient and effective.
- **Transcription:** Leverages the powerful Whisper model from OpenAI to transcribe audio to text with high accuracy, supporting a wide range of languages and dialects.
- **Ease of Use:** Simple command-line interface for both splitting audio files and performing transcriptions, suitable for users with varying levels of technical expertise.

## Getting Started

### Prerequisites

- Python 3.6+
- Pip for installing Python packages

### Installation

Clone the repository and install the required Python packages:

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
pip install -r requirements.txt
```

### Usage

1. **Split Audio Files:**

```bash
python audio_splitter.py --input your_audio_file.mp3 --output_dir ./chunks
```

2. **Transcribe Audio Files:**

```bash
python transcription.py --chunks_dir ./chunks --output_file transcriptions.txt
```

## Contributing

We welcome contributions from the community! If you have suggestions for improvements or new features, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- OpenAI for the Whisper model
- PyDub for audio file manipulation capabilities

Thank you for visiting our repository. We hope this project assists you in your audio transcription tasks!
