# MERN Stack Chatbot

A simple chatbot application built with the MERN stack (MongoDB, Express.js, React.js, Node.js) and OpenAI API.

## Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- OpenAI API key

## Setup

### Backend Setup

1. Navigate to the backend directory:
   ```bash
   cd backend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file in the backend directory with the following content:
   ```
   PORT=5000
   OPENAI_API_KEY=your_openai_api_key_here
   ```

4. Start the backend server:
   ```bash
   npm run dev
   ```

### Frontend Setup

1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the frontend development server:
   ```bash
   npm start
   ```

The application will be available at `http://localhost:3000`

## Features

- Real-time chat interface
- Integration with OpenAI's GPT-3.5 Turbo
- Modern Material-UI design
- Responsive layout
- Message history
- Loading states

## Technologies Used

- Frontend:
  - React.js
  - Material-UI
  - Axios
  - Emotion

- Backend:
  - Node.js
  - Express.js
  - OpenAI API
  - CORS
  - dotenv 