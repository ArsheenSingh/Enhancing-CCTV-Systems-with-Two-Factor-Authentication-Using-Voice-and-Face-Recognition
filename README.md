# Enhancing-CCTV-Systems-with-Two-Factor-Authentication-Using-Voice-and-Face-Recognition
Enhances CCTV security with 2FA using facial recognition and voice authentication. Prevents spoofing via eye-blink detection and passphrase verification. Built with OpenCV, Dlib, and Google SpeechRecognition API, it reduces false acceptance rates compared to traditional single-factor methods. <br>
Face Recognition + Voice Verification <br>
A robust security system combining facial recognition with liveness detection (eye-blink analysis) and voice-based password verification to prevent unauthorized access in high-risk environments. Designed for CCTV/doorbell systems, this project demonstrates modern biometric authentication using Python, OpenCV, and machine learning.
<hr>
🔍 Key Techniques
Facial Landmark Detection: Uses dlib's 68-point model to track eye movements for liveness checks. (MDN: Computer Vision Basics)<br>
Voice-to-Text Conversion: Leverages Google’s Speech Recognition API for real-time audio processing. <br>
Anti-Spoofing: Implements eye-blink detection to differentiate live users from static images/videos.<br>
Secure Notifications: Integrates Mailgun API for email alerts with image attachments during unauthorized access attempts. <br>
<hr>
🛠 Notable Technologies<br>
Non-Obvious Libraries:<br>
dlib for facial landmark detection (lightweight and precise).<br>
face-recognition for GPU-accelerated face embeddings.<br>
pydub for audio preprocessing in voice recognition.<br>
Security: AES encryption for biometric data storage and TLS for secure email alerts.<br>
<hr>
📂 Project Structure<br>
.
├── 2FA Security for CCTV Report.pdf      # Full project report with methodology & results <br>
├── 2FA CCTV Research Paper # Technical paper for academic audiences <br> 
├── Poster 2FA CCTV.pdf              # Visual summary for presentations <br>
├── Two_Factor_Authentication_FinalCode.ipynb  # Google Colab notebook (core implementation) <br>
<hr>
🎯 Why This Stands Out<br>
Dual-Layer Security: Combines two independent biometric factors (face + voice) to minimize spoofing risks.<br>
Real-World Relevance: Tested under low-light, noise, and impersonation scenarios (85%+ accuracy).<br>
Scalable Design: Modular architecture allows integration with existing CCTV systems.<br>
