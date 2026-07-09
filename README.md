# Quick-AI

## Overview
Quick-AI is a full-stack AI-powered web application that brings multiple AI tools together in a single platform. It enables users to generate text, create AI images, edit images, analyze resumes, and interact with a community gallery through an intuitive and responsive interface.

---

## Features

- 🤖 AI-powered text generation
- 📝 Blog title and content generation
- 🎨 AI image generation from text prompts
- 🖼️ Background removal from images
- ✂️ Object removal from images
- 📄 AI resume review and analysis
- 👥 Community gallery for sharing AI-generated images
- 🔐 Secure user authentication with Clerk
- 💎 Free and Premium user access
- 📱 Responsive and modern user interface

---

## Tech Stack

### Frontend
- React.js
- Vite
- Tailwind CSS
- React Router
- Axios

### Backend
- Node.js
- Express.js

### Database
- Neon PostgreSQL

### Authentication
- Clerk Authentication

### AI & Cloud Services
- OpenAI / Gemini API
- ClipDrop API
- Cloudinary

---

## Installation

1. Clone the repository

```bash
git clone https://github.com/your-username/Quick-AI.git
```

2. Navigate to the project

```bash
cd Quick-AI
```

3. Install dependencies

```bash
cd client
npm install

cd ../server
npm install
```

4. Configure environment variables

Create a `.env` file in the server directory and add your API keys.

5. Start the backend

```bash
npm start
```

6. Start the frontend

```bash
cd ../client
npm run dev
```

---

## Project Structure

```
Quick-AI/
│
├── client/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── server/
│   ├── controllers/
│   ├── routes/
│   ├── middlewares/
│   ├── configs/
│   └── package.json
│
└── README.md
```

---

## Future Enhancements

- Voice-based AI assistant
- AI chatbot integration
- Multi-language support
- Image history and favorites
- Team collaboration
- Mobile application

---

## Author

Harish R
