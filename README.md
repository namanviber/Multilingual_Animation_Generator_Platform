# Multilingual Animation Generator Platform

A sophisticated multimedia generation platform that converts stories into animated videos with multilingual support. Leverages LLMs and generative AI models to automate the entire process from script writing to video synthesis.

## 🚀 Overview

This platform focuses on generating multilingual scripts from stories using the **Gemma LLM**, fine-tuned on a custom dataset. It supports **Hindi**, **English**, and **Punjabi**, automatically generating scripts, scene breakdowns, background descriptions, and dialogues. These are then transformed into multimedia content using state-of-the-art generative models.

## ✨ Key Features

- **Multilingual Support**: Fine-tuned model for script generation in Hindi, English, and Punjabi.
- **Story to Script Conversion**: Automated generation of detailed scene breakdowns, character actions, and dialogues.
- **AI-Driven Asset Generation**:
  - **Images**: Generated using **SDXL** based on scene descriptions.
  - **Audio**: Generated using **BarkTTS** for narration and sound effects.
- **Automated Video Synthesis**: Seamlessly combines generated images and audio into a final video with transitions and effects.

## 🛠️ Project Structure

```text
Multilingual_Animation_Generator_Platform/
├── public/                 # Static assets and HTML template
├── src/
│   ├── components/         # React components for the UI
│   ├── output/             # Directory for generated files
│   ├── App.js              # Main React application logic
│   ├── index.js            # Entry point
│   └── App.css             # Component styling
├── server.js               # Node.js backend server
├── package.json            # Project dependencies and scripts
└── README.md               # Project documentation
```

## 💻 Tech Stack

- **Frontend**: React.js, Styled Components, CoreUI Icons
- **Backend**: Node.js, Express
- **AI Models**: Gemma LLM (Scripting), SDXL (Images), BarkTTS (Audio)
- **Utilities**: Axios, File-saver, React Player

## ⚙️ Installation & Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/namanviber/Multilingual_Animation_Generator_Platform.git
   cd Multilingual_Animation_Generator_Platform
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Start the development server**:
   ```bash
   npm start
   ```

4. **Start the backend server**:
   ```bash
   node server.js
   ```

## 🔄 Workflow

1. **Input**: User provides a story and selects a language.
2. **Scripting**: LLM processes the story into a structured JSON script.
3. **Generation**:
   - Audio model generates narration for each scene.
   - Image model generates visuals based on background prompts.
4. **Synthesis**: Images and audio are merged into the final video output.

---
*Note: Backend for the project involves research-restricted components and is in the process of being published.*
