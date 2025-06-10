## Umbrellas

Umbrellas is a secure, web-based mental health journaling app that provides AI-powered therapeutic reflections. It allows users to log their emotions and journal entries, and receive supportive feedback using the OpenAI API. This project was created for the course "CMSC 335: Web Application Development with JavaScript" at the University of Maryland during the Fall 2024 semester.

### ✨ Features

- 📓 Record and store private journal entries
- 🧠 Choose from a list of emotions to tag your entries
- 🤖 Receive AI-generated reflections offering empathy, encouragement, and guidance
- 🔐 User authentication with sign-up/sign-in flow
- 🗂️ View past journal entries in a clean, card-based layout

### 🛠️ Tech Stack

- **Frontend**: HTML, CSS
- **Backend**: Node.js, Express
- **Database**: MongoDB
- **AI Integration**: OpenAI GPT-4o-mini via API
- **Templating**: EJS

## 🚀 Installation

### Prerequisites

- Node.js (v16+)
- MongoDB URI
- OpenAI API Key

### Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/spanhornet/umbrellas.git
   cd umbrellas

2. Install dependencies:
   ```bash
   npm install

3. Create a `.env` file in the project root directory:
   ```bash
   touch .env

4. Add the following environment variables to `.env`:
   ```bash
   PORT=3000
   MONGO_URI=your_mongodb_connection_string
   OPEN_AI_API_KEY=your_openai_api_key
   SESSION_SECRET=your_session_secret

5. Start the server:
   ``` bash
   node index.js

6. Open your browser and visit http://localhost:3000

## 🎥 Demo

Want to see how it works before diving in?

👉 [Watch the full walkthrough](https://www.youtube.com/watch?v=IgSHxN1Q5Gc&feature=youtu.be)

The video demonstrates:
- Signing up and logging in
- Creating a journal entry
- Receiving an AI-generated reflection
- Viewing saved entries
