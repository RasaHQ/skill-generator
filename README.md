# Rasa Skill Generator

This project provides a web-based tool for generating Rasa CALM flows and domain YAML configurations using the Anthropic API. It consists of a Node.js backend server and a React frontend application.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js (v14.0.0 or later)
- npm (v6.0.0 or later)
- An Anthropic API key

## Installation

1. Install backend dependencies:
   ```
   cd backend
   npm install
   ```

2. Install frontend dependencies:
   ```
   cd ../frontend
   npm install
   ```

## Configuration

1. Create a `.env` file in the `backend` directory with the following content:
   ```
   PORT=3000
   ```

2. (Optional) If you want to restrict CORS to specific origins, modify the `cors` options in `backend/server.js`.

## Usage

1. Start the backend server:
   ```
   cd backend
   npm start
   ```

2. In a new terminal, start the frontend development server:
   ```
   cd frontend
   npm start
   ```

3. Open your browser and navigate to `http://localhost:3000` (or the port specified by your React app).
