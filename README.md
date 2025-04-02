# Speech Recognition App with Streamlit
This is the [streamlit](https://speechrecognition123.streamlit.app/) link 

A simple and interactive web app built with Streamlit and Speech Recognition that allows users to convert speech into text in real-time. This app uses Google's Speech Recognition API to transcribe spoken words into text.

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

The Speech Recognition App is a web application that leverages **Streamlit** for building interactive user interfaces and **SpeechRecognition** for converting speech to text. This project allows users to click a button, speak into their microphone, and get the transcribed text in real-time.

The app uses **Google's Speech Recognition API** for transcription and includes features to handle noisy environments and potential errors that might arise during the speech-to-text process.

## Features

- **Real-time Speech Recognition**: The app listens to your microphone and transcribes spoken words into text.
- **Error Handling**: Provides user-friendly messages when speech is unclear or when the service is unavailable.
- **Ambient Noise Adjustment**: It adjusts for background noise to enhance transcription accuracy.
- **Simple UI**: The interface is built with Streamlit for ease of use, allowing users to start recording with a simple button click.

## Installation

### Prerequisites
- Python 3.7 or above
- Microphone (ensure your device has a working microphone)

### Steps to Install

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/speech-recognition-streamlit.git
   cd speech-recognition-streamlit
   ```

2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   ```

3. Activate the virtual environment:
   - On Windows:
     ```bash
     venv\Scripts\activate
     ```
   - On MacOS/Linux:
     ```bash
     source venv/bin/activate
     ```

4. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

   The `requirements.txt` file should include:
   ```
   streamlit==1.7.0
   SpeechRecognition==3.8.1
   PyAudio==0.2.11
   ```

   > **Note**: `PyAudio` might require additional setup depending on your system. If you face installation issues, you can follow the [PyAudio installation guide](https://pypi.org/project/PyAudio/).

## Usage

1. Run the app:
   ```bash
   streamlit run app.py
   ```

2. Open your web browser and navigate to `http://localhost:8501`.

3. Click the "Start Recording" button to begin speaking. The app will transcribe your speech into text, which will appear below the button.

4. If the speech is unclear, the app will notify you, and if the service is unavailable, it will provide an error message.

## Technologies Used

- **Streamlit**: A Python framework used to build the app interface quickly.
- **SpeechRecognition**: A Python library used to convert speech to text.
- **Google Speech Recognition**

## Contributing

Contributions are welcome! If you'd like to contribute, follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to your branch (`git push origin feature/your-feature`).
6. Create a pull request.

### Issues
If you encounter any bugs or issues, feel free to create an issue in the repository. Provide as much detail as possible to help us resolve it.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

