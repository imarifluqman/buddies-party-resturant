# Buddies-party-resturant
A Buddies party restaurant fully automations 

# Autonomous Voice-Driven Restaurant Assistant System

## Project Overview

This repository contains the implementation of a fully autonomous AI-driven system designed to enhance customer service in a restaurant setting. The system automates the entire dining experience, from greeting customers to handling billing, using voice and visual interactions.

### Key Features
- **Greeting Agent**: Welcomes customers with voice-based greetings.
- **Menu Agent**: Presents the menu via voice and visual display.
- **Order Agent**: Takes customer orders through voice input and converts them to structured JSON.
- **Dispatch Agent**: Forwards orders to the desk officer in real-time.
- **Kitchen Agent**: Sends orders to the chef's terminal.
- **Entertainment Agent**: Engages customers with media (e.g., YouTube/Spotify) while they wait.
- **Billing Agent**: Generates QR/UPI invoices and provides a voice summary of the bill.

## Technical Stack

| Layer                | Tools/Technologies                     |
|----------------------|---------------------------------------|
| Voice Input          | OpenAI Whisper, SpeechRecognition      |
| Voice Output         | gTTS, ElevenLabs                      |
| AI Logic             | LangChain, OpenAI Functions, CrewAI   |
| Backend              | Python + FastAPI                      |
| Frontend             | Next.js / React.js                    |
| Realtime Messaging   | WebSockets, Socket.io                 |
| Database             | MongoDB                               |
| Optional Hardware    | Raspberry Pi, USB Microphone, Tablet Screen |

## Architecture Overview

The system is modular, with distinct agents handling specific tasks:
1. **Greeting Agent**: Voice-based customer welcome.
2. **Menu Agent**: Displays and explains the menu (JSON-based).
3. **Order Agent**: Processes voice orders into structured JSON.
4. **Dispatch Agent**: Real-time order forwarding to the desk officer.
5. **Kitchen Agent**: Communicates orders to the chef's terminal.
6. **Entertainment Agent**: Plays media during wait times.
7. **Billing Agent**: Handles invoice generation and voice-based billing summary.

## Implementation Roadmap

| Phase                     | Description                              | Duration       |
|---------------------------|------------------------------------------|----------------|
| Phase 1                   | Core voice greeting and menu display      | -              |
| Phase 2                   | Voice-based order processing             | -              |
| Phase 3                   | (Details incomplete in document)         | -              |
| Phase 4                   | -                                        | 4 days         |
| Phase 5                   | -                                        | 4 days         |
| Phase 6                   | -                                        | 5 days         |
| Final Review & Revisions  | Final testing and adjustments            | 3 days         |
| **Total Estimated Time**  |                                          | **4-5 weeks**  |

*Note*: Some phase details are incomplete in the provided document.

## Future Enhancements
- Multilingual support for broader accessibility.
- Facial recognition for personalized customer greetings.
- Mobile app version for remote interaction.
- Data analytics dashboard for restaurant insights.

## Getting Started

### Prerequisites
- Python 3.x
- Node.js (for frontend)
- MongoDB
- Optional: Raspberry Pi, USB Microphone, Tablet Screen

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/[your-username]/autonomous-restaurant-assistant.git
