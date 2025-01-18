Key Features
1. Facial & Nail Recognition
Facial Recognition: Uses AI to analyze facial features such as wrinkles, skin texture, and expression to detect dosha imbalances.
Nail Recognition: Analyzes the user’s nails (color, texture, shape) to assess overall health and dosha status.
2. Health Evaluation
Based on facial and nail analysis, the system evaluates the user’s dosha (Vata, Pitta, Kapha) and overall health.
Personalized recommendations (diet, lifestyle, herbs) are provided based on the analysis.
3. Expert Verification
Ayurvedic experts review and verify the AI-generated evaluation, ensuring personalized and authentic advice.
4. Video Capture or File Upload
Users can either record a video in real-time or upload a pre-recorded video/file of their face and nails for analysis.
5. WhatsApp Integration with Landbot.io
Landbot.io powers the WhatsApp bot integration, which interacts with users, providing health evaluations, personalized recommendations, and ongoing health guidance via WhatsApp.
6. Chatbot with Botpress
Botpress is used as the conversational AI backend, answering users' questions, guiding them through the evaluation process, and offering health tips.
7. Password Reset Functionality
Users can securely reset their password through a reset link sent to their email, which expires after a set time (1 hour). The reset flow does not require JWT tokens.
8. Dynamic Health Logs & Symptom Tracking
Health practitioners can log patient health data, track symptoms over time, and visualize them with interactive charts.
Recharts.js is used to dynamically display symptoms and health logs in graphical form, making it easier for experts to monitor trends and offer more accurate health advice.Ayurvedic experts review and verify the AI-generated evaluation, ensuring personalized and authentic advice.
4. Video Capture or File Upload
Users can either record a video in real-time or upload a pre-recorded video/file of their face and nails for analysis.
5. WhatsApp Integration with Landbot.io
Landbot.io powers the WhatsApp bot integration, which interacts with users, providing health evaluations, personalized recommendations, and ongoing health guidance via WhatsApp.
6. Chatbot with Botpress
Botpress is used as the conversational AI backend, answering users' questions, guiding them through the evaluation process, and offering health tips.
7. Password Reset Functionality
Users can securely reset their password through a reset link sent to their email, which expires after a set time (1 hour). The reset flow does not require JWT tokens.
8. Dynamic Health Logs & Symptom Tracking
Health practitioners can log patient health data, track symptoms over time, and visualize them with interactive charts.
Recharts.js is used to dynamically display symptoms and health logs in graphical form, making it easier for experts to monitor trends and offer more accurate health advice.
Tech Stack
Frontend:

React.js (for building the web app interface)
HTML/CSS for UI design
Axios for API calls
Recharts.js for data visualization
Backend:

Node.js (for handling requests)
Express.js (for creating REST APIs)
Python for facial and nail recognition model integration
Machine Learning:

TensorFlow/PyTorch (for AI facial and nail analysis)
OpenCV, MediaPipe (for facial feature detection and nail processing)
Database:

MongoDB Atlas (cloud-based storage for user data, health evaluations, expert feedback, and health logs)
WhatsApp Integration:

Landbot.io (for WhatsApp bot)
Twilio API (for WhatsApp communication)
Node.js for integrating Twilio and Landbot.io with the backend
Chatbot:

Botpress (for creating conversational AI chatbot)
How It Works
1. User Registration & Video Upload/Recording:
Users register on the web app and upload a video or image of their face and nails for analysis. They can either record a video in real-time or upload a pre-recorded video.
2. Facial and Nail Analysis:
The uploaded video or image is processed using AI models to detect dosha imbalances based on facial features and nail conditions.
3. Health Evaluation:
The system generates an evaluation of the user's dosha and provides health recommendations based on the analysis.
4. Expert Verification:
Ayurvedic health experts review the evaluation, providing additional personalized advice and verifying the accuracy of the AI model.
5. WhatsApp Integration:
Once the health evaluation is completed, Landbot.io sends the results to users through WhatsApp. The Botpress chatbot assists in answering any questions and guiding the user further.
6. Password Reset:
Users can reset their password through a secure reset link sent to their email. The link contains a unique token that expires after a set period (e.g., 1 hour).
7. Dynamic Health Logging & Symptom Tracking:
Health practitioners can log patient health data (including symptoms, treatments, and dosha evaluations) directly in the web app.
Recharts.js is used to visualize trends in symptoms and health logs over time, making it easy for experts to monitor patient progress.
Data Visualization with Recharts.js
Example of Symptom Tracking
Using Recharts.js, you can visualize the symptoms and health status of patients over time. Here's how you can dynamically add data and visualize it:

Major Dependency:- Python 3.10
(Note: Many of the Dependencies need force)

Make 2 folders
Frontend and Backend 
put each into their own

start both using their own commands and make sure that their ports are set up right