# Gemini Chatbot

A modern AI chatbot built using React, Vite, and the Google Gemini API. The application provides an interactive conversational experience with real-time AI responses, animated typing effects, chat history management, and a responsive UI inspired by modern AI assistants.

---

# Features

- Google Gemini API integration
- Real-time AI-generated responses
- Animated typing effect for responses
- Chat history and recent prompt tracking
- New chat session support
- Responsive sidebar navigation
- Prompt suggestion cards
- Keyboard support (Enter to send)
- Dynamic markdown-style text formatting
- Context-based global state management
- Clean and modern UI design
- Fast development environment using Vite

---

# Tech Stack

## Frontend
- React
- Vite
- JavaScript
- CSS

## State Management
- React Context API

## AI Integration
- Google Gemini API

## Tooling
- ESLint
- npm

---

# Project Structure

```bash
.
├── public/
├── src/
│   ├── assets/
│   ├── components/
│   │   ├── Main/
│   │   └── Sidebar/
│   ├── context/
│   │   └── Context.jsx
│   ├── config/
│   │   └── gemini.js
│   ├── App.jsx
│   └── main.jsx
├── .env
├── .gitignore
├── package.json
├── vite.config.js
└── README.md
```

---

# Installation

## Clone the Repository

```bash
git clone https://github.com/Rajlaxmi111/Gemini-Chatbot.git
cd Gemini-Chatbot
```

---

# Install Dependencies

```bash
npm install
```

---

# Environment Variables

Create a `.env` file in the root directory.

```env
VITE_GEMINI_API_KEY=your_api_key_here
```

---

# Run the Development Server

```bash
npm run dev
```

The application will start locally on:

```bash
http://localhost:5173
```

---

# Build for Production

```bash
npm run build
```

---

# Core Functionalities

## AI Chat System
- Sends prompts to the Gemini API
- Receives and renders AI-generated responses
- Supports dynamic response formatting

## Chat History
- Stores previously entered prompts
- Allows reopening previous conversations

## Typing Animation
- Simulates streaming response behavior
- Displays words sequentially for smoother UX

## Prompt Suggestions
- Displays predefined prompt cards for quick interaction

## Context-Based State Management
Handles:
- Current input
- Loading states
- Chat responses
- Previous prompts
- Active conversation state

---

# Future Improvements

- Persistent database-backed chat history
- Markdown rendering support
- Multi-chat conversations
- Voice input support
- Image upload support
- Authentication system
- Streaming API responses
- Dark/light theme toggle

---

# Applications

- AI assistant interfaces
- Conversational AI systems
- Gemini API experimentation
- Frontend AI integration learning
- Personal productivity assistants

---

# Conclusion

Gemini Chatbot demonstrates how modern frontend technologies can be combined with generative AI APIs to create responsive conversational interfaces. The project showcases state management, dynamic rendering, API integration, and interactive UI design within a scalable React architecture.