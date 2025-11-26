AI-Powered Healthcare Chatbot — Frontend

React • Voice UI • Real-Time Text Animation • REST API Integration

This is the frontend interface for the AI healthcare assistant. It allows users to record voice inputs, view generated diagnoses, and listen to real-time TTS responses.

The UI is designed to feel natural, interactive, and medical assistant–like.


Features:

⦁	Automatic microphone activation
   Begins recording when user starts speaking.

⦁	Silence detection
   Auto-stops recording when user finishes.

⦁	Typewriter-style animated text output
   Diagnosis is displayed character-by-character.

⦁	TTS speech playback
   Plays the diagnosis audio returned by the backend.

⦁	Section toggles
	    Follow-up Questions
	    Recommended Next Steps

⦁	UI auto-reset
   Mic icon reactivates after speech playback ends.

⦁	Persistent keyword history
   Displays extracted clinical keywords per session.



Tech Stack: React (Hooks), Axios, Web Speech API (initial version), Coqui TTS (backend-generated responses), JavaScript / HTML / CSS, Tailwind (optional)


System Workflow:

1.	User speaks → audio recorded in browser
2.	Audio uploaded to backend
3.	Backend returns:
            Symptoms
		        Diagnosis
		        Next steps
		        TTS audio

4. UI displays typewriter animation
5. TTS audio plays
6. UI resets automatically
7. Keyword history appears on screen


Project Structure:

chatbot-frontend/
│── src/
│   ├── components/
│   ├── utils/
│   ├── pages/
│   ├── App.js
│   └── index.js
│── public/
│── package.json
└── README.md

How to Run the Frontend:

npm install
npm start

The app will start at:

http://localhost:3000


Deployment:

This frontend was deployed on "Render" and connected to the live backend through REST APIs. The application demonstrated real-time voice interaction, diagnosis display, and TTS feedback in a live environment.



Future Improvements:

⦁	Improved UI design
⦁	Dark/light mode toggle
⦁	User authentication
⦁	Session history export
⦁	Live streaming animation synced with partial backend responses



Author:
Hiya Desai
Embedded & Software Engineer
⦁	Persistent keyword history
   Displays extracted clinical keywords per session.
