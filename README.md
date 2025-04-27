# VisionBot

VisionBot is an AI-powered vision bot that uses the Gemenai 2.0 model to facilitate live interactions through a webcam and microphone. The project is built with Python and includes a web interface written in HTML.

## Table of Contents
- Overview
- Features
- Installation
- Usage
- Configuration
- Contributing
- License

## Overview

VisionBot leverages the power of the Gemenai 2.0 model to enable real-time AI interactions using your webcam and microphone. This project is designed to demonstrate the capabilities of AI in processing and responding to live audio and visual inputs.

## Features

- Real-time video and audio processing
- Integration with the Gemenai 2.0 model
- Web interface for interaction
- Built with Python and HTML

## Installation

To get started with VisionBot, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Narayan-cpu/VisionBot.git
   cd VisionBot
   ```

2. **Set up a virtual environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. **Install the required dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

## Usage

To run VisionBot, execute the following commands:

1. Start a local server to serve the HTML page:
   ```bash
   python -m http.server 8000
   ```

2. In a separate terminal, run the main Python script:
   ```bash
   python main.py
   ```

This will start the application and open the web interface where you can interact with the AI using your webcam and microphone.

## Configuration

You can configure various aspects of VisionBot by editing the configuration file `config.json`. Below is an example configuration:
```json
{
  "model": "gemenai-2.0",
  "video_source": 0,
  "audio_source": "default"
}
```

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a pull request



---
Contact : naiknarayanp557@gmail.com
## Please Rate this repo 🤗
