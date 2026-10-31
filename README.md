# SCAMGUARD-AI
# SCAMGUARD AI – AI-Powered Scam Message Investigator

## Project Overview

SCAMGUARD AI is an AI-powered web application designed to analyze suspicious messages and identify potential scam indicators. It helps users recognize fraudulent communication across SMS, WhatsApp messages, emails, and online offers.

Built using Python, Streamlit, and Google's Gemini API, the application provides risk assessments, suspicious phrase detection, detailed explanations, and practical safety recommendations.

## Live Application

[Access SCAMGUARD AI](https://scamguard-ai-r9kpftgxwjajhgpxmhudc9.streamlit.app/)

SCREENSHOTS:
<img width="959" height="404" alt="Screenshot 2026-10-31 185306" src="https://github.com/user-attachments/assets/cdda0d45-bf55-4022-a12d-f603e4bea1c3" />
<img width="959" height="366" alt="Screenshot 2026-10-31 185257" src="https://github.com/user-attachments/assets/9e634f46-c065-4888-80a3-814e52a43a8c" />
<img width="959" height="335" alt="Screenshot 2026-10-31 185247" src="https://github.com/user-attachments/assets/f10b48d4-71cd-46b8-b319-310ab3c895ec" />
<img width="959" height="408" alt="Screenshot 2026-10-31 185228" src="https://github.com/user-attachments/assets/6644d0af-36a9-46ef-b87f-20b928934eb5" />
<img width="949" height="407" alt="Screenshot 2026-10-31 185216" src="https://github.com/user-attachments/assets/da877b38-bbc1-4a3f-80a0-fa46f188c080" />


## Features

- **AI-Powered Message Analysis:** Analyzes suspicious messages using Google Gemini.
- **Risk Score:** Generates a risk score between 0 and 100.
- **Risk Classification:** Categorizes messages into Low Concern, Medium Concern, and High Concern.
- **Suspicious Phrase Detection:** Identifies potentially fraudulent words and phrases.
- **Warning Signs:** Highlights common scam patterns and suspicious requests.
- **AI Explanation:** Explains why a message may be suspicious.
- **Safety Recommendations:** Provides practical steps to help users stay protected.
- **Investigation History:** Displays previously analyzed messages during the current session.
- **Clear History:** Allows users to clear their investigation history.

## Technologies Used

| Technology | Purpose |
|---|---|
| Python | Application development |
| Streamlit | Web application interface |
| Google Gemini API | AI-powered message analysis |
| JSON | Structured AI responses |
| GitHub | Version control and source code hosting |
| Streamlit Community Cloud | Application deployment |

## How It Works

1. The user enters a suspicious message into the application.
2. The message is submitted to the Gemini API for analysis.
3. The AI examines suspicious phrases, urgency, unusual payment requests, and other potential scam indicators.
4. The application generates a risk score and risk classification.
5. The results are displayed with explanations and safety recommendations.

## Project Structure

```text
SCAMGUARD-AI/
│
├── app.py
├── requirements.txt
├── README.md
└── .gitignore
```

## Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/SCAMGUARD-AI.git
```

### 2. Navigate to the Project Directory

```bash
cd SCAMGUARD-AI
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure the Gemini API Key

Create a `.streamlit/secrets.toml` file and add your API key:

```toml
GEMINI_API_KEY = "YOUR_GEMINI_API_KEY"
```

Never upload API credentials to a public GitHub repository.

### 5. Run the Application

```bash
streamlit run app.py
```

## Security and Privacy

- API credentials are managed using Streamlit Secrets.
- Sensitive credentials should never be committed to GitHub.
- Messages are sent to the configured Gemini API for analysis.
- Users should avoid entering passwords, OTPs, banking details, or other sensitive personal information.

## Limitations

- AI-generated risk scores are estimates, not verified fraud assessments.
- A low-risk classification does not guarantee that a message is legitimate.
- The application does not perform live URL reputation checks.
- AI predictions may occasionally produce incorrect classifications.
- Internet connectivity and Gemini API availability are required.

## Future Enhancements

- Malicious URL detection and reputation checking.
- Email header analysis.
- Multilingual scam message detection.
- Advanced scam pattern recognition.
- Downloadable investigation reports.
- Improved investigation history and analytics.

## Author

**HARI PRIYA .B**

B.Sc. Computer Science with Artificial Intelligence



                                         Stay Alert. Stay Protected.
