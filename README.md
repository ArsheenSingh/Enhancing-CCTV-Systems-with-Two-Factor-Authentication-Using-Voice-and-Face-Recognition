# Enhancing-CCTV-Systems-with-Two-Factor-Authentication-Using-Voice-and-Face-Recognition
Enhances CCTV security with 2FA using facial recognition and voice authentication. Prevents spoofing via eye-blink detection and passphrase verification. Built with OpenCV, Dlib, and Google SpeechRecognition API, it reduces false acceptance rates compared to traditional single-factor methods.
Face Recognition + Voice Verification

A robust security system combining facial recognition with liveness detection (eye-blink analysis) and voice-based password verification to prevent unauthorized access in high-risk environments. Designed for CCTV/doorbell systems, this project demonstrates modern biometric authentication using Python, OpenCV, and machine learning.

🔍 Key Techniques
Facial Landmark Detection: Uses dlib's 68-point model to track eye movements for liveness checks. (MDN: Computer Vision Basics)

Voice-to-Text Conversion: Leverages Google’s Speech Recognition API for real-time audio processing.

Anti-Spoofing: Implements eye-blink detection to differentiate live users from static images/videos.

Secure Notifications: Integrates Mailgun API for email alerts with image attachments during unauthorized access attempts.

🛠 Notable Technologies
Non-Obvious Libraries:

dlib for facial landmark detection (lightweight and precise).

face-recognition for GPU-accelerated face embeddings.

pydub for audio preprocessing in voice recognition.

Security: AES encryption for biometric data storage and TLS for secure email alerts.

📂 Project Structure
bash
Copy
.
├── 2FA_Security_Report.docx       # Full project report with methodology & results
├── research_paper_updated_2.docx  # Technical paper for academic audiences
├── Poster_Final.pdf               # Visual summary for presentations
├── Two_Factor_Authentication_FinalCode.ipynb  # Jupyter notebook (core implementation)
├── data/                          # Sample face/voice datasets (not included in repo)
├── media/                         # Figures/diagrams from the report
└── content/                       # Generated outputs (saved frames, audio files)
Notable Directories:

media/: Contains architecture diagrams and testing results (e.g., Figure 1.3 in the report).

data/: Expected location for authorized user face images and voice samples (see code).

🎯 Why This Stands Out
Dual-Layer Security: Combines two independent biometric factors (face + voice) to minimize spoofing risks.

Real-World Relevance: Tested under low-light, noise, and impersonation scenarios (85%+ accuracy).

Scalable Design: Modular architecture allows integration with existing CCTV systems.
