BharatStandards-AI 
An AI-powered platform for discovering, understanding, and working with Indian Standards.
📌 Overview

BharatStandards-AI is an AI-powered web application designed to make Indian Standards easier to discover, understand, and use.

The platform combines a modern web interface with an AI-powered backend to help users interact with standards and obtain useful information in a simpler and more accessible way.

✨ Features
🤖 AI-powered assistance for understanding Indian Standards
🔎 Search and discovery of relevant standards
📚 Standards-focused information in an easy-to-understand format
💬 Interactive user experience for asking questions and exploring information
🖥️ Modern frontend for a responsive web experience
⚙️ Backend API for application logic and AI functionality
🐳 Docker support for easier local development and deployment
🏗️ Project Structure
BharatStandards-AI/
│
├── backend/             # Backend API and application logic
│
├── frontend/            # Frontend web application
│
├── .env.example         # Example environment variables
├── .gitignore
├── docker-compose.yml   # Docker services configuration
└── netlify.toml         # Netlify deployment configuration

🛠️ Tech Stack
Frontend
Modern JavaScript/TypeScript-based web application
Responsive UI
API integration with the backend
Backend
REST/API-based backend
AI integration
Data processing and application logic
DevOps
Docker
Docker Compose
Netlify deployment configuration
🚀 Getting Started
Prerequisites

Make sure you have the following installed:

Git
Node.js
npm
Docker & Docker Compose
1. Clone the repository
git clone https://github.com/Sanju-B123/codecrafters.git
cd codecrafters/BharatStandards-AI

2. Configure environment variables

Create your local environment file from the provided example:

cp .env.example .env


Then update .env with the required configuration and API keys.

Never commit your .env file or expose API keys publicly.
3. Run with Docker

The project includes a docker-compose.yml file, so you can start the application using:

docker compose up --build


To run the services in the background:

docker compose up -d --build

4. Run manually

If you prefer to run the frontend and backend separately, navigate into each directory and install the required dependencies.

Backend
cd backend
npm install


Start the backend using the project's configured start command.

Frontend
cd frontend
npm install


Start the frontend using the project's configured development command.

🔐 Environment Variables

The project provides an .env.example file containing the environment variables required by the application.

Create your own .env file:

cp .env.example .env


Then configure the required values.

Example:

# Add your application configuration here
# API keys and other secrets should be stored locally

🐳 Docker

Docker Compose can be used to run the application services together.

docker compose up --build


Stop the services with:

docker compose down

📖 Use Cases

BharatStandards-AI can be useful for:

Students researching Indian Standards
Engineers and developers working with standards
Businesses looking for standards-related information
Researchers and academics
Anyone who needs a simpler way to explore Indian Standards
🔄 Application Flow
                ┌──────────────────┐
                │      User        │
                └────────┬─────────┘
                         │
                         ▼
                ┌──────────────────┐
                │    Frontend      │
                │   Web Interface  │
                └────────┬─────────┘
                         │
                         ▼
                ┌──────────────────┐
                │     Backend      │
                │     API / AI     │
                └────────┬─────────┘
                         │
                         ▼
                ┌──────────────────┐
                │ Standards/Data   │
                │   & AI Services  │
                └──────────────────┘

🌱 Future Improvements

Potential improvements include:

Advanced semantic search
Better document and standards retrieval
Multi-language support
Voice-based interaction
Improved AI-generated explanations
User accounts and personalized history
Standards comparison
Document upload and analysis
Improved analytics and monitoring
🤝 Contributing

Contributions are welcome!

Fork the repository.
Create a new branch:
git checkout -b feature/your-feature

Make your changes.
Commit your changes:
git commit -m "Add your feature"

Push the branch:
git push origin feature/your-feature

Open a Pull Request.
🔒 Security

Please do not commit:

API keys
Passwords
Access tokens
.env files
Other sensitive credentials

If you discover a security vulnerability, please report it privately rather than exposing it publicly.

📄 License

Please refer to the repository for the applicable license.

👨‍💻 Author

Sanju-B123

GitHub:
https://github.com/Sanju-B123

⭐ Support

If you find this project useful, consider giving the repository a ⭐ on GitHub.

BharatStandards-AI — Making Indian Standards easier to understand with AI. 🇮🇳🤖
