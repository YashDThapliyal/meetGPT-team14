# meetGPT - AI Meeting Assistant

meetGPT is a cutting-edge AI-powered meeting assistant designed to streamline your meeting workflows. Built with **Streamlit**, **Python** and powered by **OpenAI's GPT-3.5-turbo**, it provides an intuitive interface for interacting with meeting transcripts and generating actionable insights. 

Whether you need quick summaries, detailed analyses, or personalized email generation, meetGPT has you covered!

---

## Features

### 1. **Meeting Summary**
Generate concise or detailed summaries of meeting transcripts based on your selected level:
- **Quick**: High-level overview.
- **Normal**: Comprehensive yet concise.
- **Detailed**: Thorough analysis of the entire meeting.

### 2. **MeetChat**
Engage in an interactive, chat-like experience with GPT-3.5-turbo. Ask questions about the meeting transcript, and get contextual, insightful responses from the AI assistant.

### 3. **NameMention**
Easily locate mentions of specific names within the meeting transcript, along with precise timestamps, to find out where you were mentioned.

### 4. **EmailGen**
Effortlessly generate professional emails based on the meeting transcript. Input the recipient's name, subject, and content, and let meetGPT handle the rest.

---

## Technology Stack

### Frontend
- **Streamlit**: A fast, easy-to-use Python framework for building interactive web applications.

### Backend
- **OpenAI GPT-3.5-turbo**: Provides the core AI functionality for natural language processing and contextual understanding.

### File Handling
- **webvtt-py**: For parsing and handling WebVTT files, used in transcript processing.

---

## Setup

### Prerequisites
Make sure you have the following installed:
- **Python 3.8+**
- Required Python packages: `streamlit`, `openai`, `webvtt-py`

### Installation

```bash
pip install streamlit openai webvtt-py
```

### API Key
1. Create an OpenAI account and obtain your API key.
2. Save your OpenAI API key in a file named `api-key.txt` in the project directory.

---

## Usage

### Starting the Application
To launch meetGPT, simply run the following command in your terminal:

```bash
streamlit run app.py
```

This will start the Streamlit web application and open it in your default browser.

### Functionalities

#### **Meeting Summary**
1. Upload a meeting transcript file named `sample.txt`.
2. Select the desired summary level (Quick, Normal, Detailed).
3. Receive your summary instantly.

#### **MeetChat**
1. Upload a meeting video file (supported formats: `mp4`, `avi`, `mov`).
2. Interact with the AI by asking questions about the meeting.

#### **NameMention**
1. Ensure you have a WebVTT transcript file named `sample.vtt`.
2. Input the name you want to search for.
3. View all mentions of the name along with timestamps.

#### **EmailGen**
1. Input your name, the recipient's name, and the email subject/content.
2. Generate a polished, professional email using the meeting transcript as a source.

---

## Security
- **API Key Protection**: Ensure your `api-key.txt` is not shared publicly. Treat it like a password to secure your OpenAI access.

---

## Important Notes
- **Supported File Formats**:
  - Meeting transcript: `sample.txt`
  - WebVTT transcript: `sample.vtt`
  - Video formats: `mp4`, `avi`, `mov`
- **Dependencies**: Ensure all required Python packages are installed for smooth operation.
- **Model Access**: This project requires access to OpenAI's GPT-3.5-turbo model.

---

## Future Enhancements
- Add support for real-time meeting transcription.
- Integration with popular video conferencing platforms (e.g., Zoom, Microsoft Teams).
- Enhanced analytics for meeting performance metrics.

## Acknowledgments

This project won **2nd place** at the Cisco CCE Program BridgeHacks Hackathon, showcasing its innovative approach to AI-assisted meeting solutions.
Special thanks to CISCO, OpenAI and the Streamlit community for their incredible tools and support.
