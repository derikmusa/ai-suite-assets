AI Educational Assistant for Uganda's CBC

A suite of specialized AI-powered tools for educators in Uganda, designed to assist with item writing, lesson planning, and more, all aligned with the National Curriculum Development Centre (NCDC) Competency-Based Curriculum (CBC) framework.

AI is here to enhance NOT take over jobs.... At least not yet

🚀 Live Application

Access the live tool here: https://cbc-ai-tool.netlify.app/

🎥 Demonstration & Guide

Before you begin, watch the full video tutorial and read the guide to understand how to get your API key and use the application effectively.

Watch the Video Guide: 🎥 https://youtu.be/KGplNQfdf_w

Read the PDF Guide: 📄 View PDF on Google Drive


✨ Core Features

Specialized AI Assistants: Access a growing list of AI assistants with custom-built prompts specifically designed for Uganda's CBC educational context.

Secure Prompt Management: All core prompts are stored securely on a Google Apps Script backend, ensuring they are not exposed to the client-side browser.

Multi-API & Model Support: Seamlessly switch between major AI providers and their models, including:

Google Gemini

Anthropic Claude

OpenAI GPT

Groq (Llama 3)

Qwen

DeepSeek

Real-time Streaming: AI responses are streamed in real-time, providing a fast and interactive user experience.

File Uploads: Attach syllabus pages, images, or documents to provide the AI with the necessary context for generating accurate materials.

Copy-Paste Friendly: All generated content is formatted with Markdown, making it easy to copy and paste directly into any word processor (like Microsoft Word or LibreOffice Writer) for final editing and formatting.

User Feedback: A built-in feedback form helps improve the tool by collecting user experiences after several generations.

Responsive Design: A clean, modern interface that works beautifully on both desktop and mobile devices.

🛠️ Assistants Available

Item Writer Assistant: Quickly generates sample scenario-based assessment items and structured scoring guides aligned with CBC principles.

Lesson Plan Generator (NCDC): Creates detailed lesson plans that follow the official NCDC template, saving educators hours of preparation time.

And more to come!

🔧 Technical Architecture

This application uses a modern, secure client-server architecture to protect the proprietary prompts and ensure a smooth user experience.

Frontend (Client-Side):

Built with React and styled with Tailwind CSS.

Contained within a single, clean index.html file.

Hosted on Netlify for fast, global delivery.

The frontend is "dumb" — it contains no prompt logic. It dynamically fetches the list of available assistants and their corresponding prompts from the backend.

Backend (Server-Side):

Powered by Google Apps Script (GAS), deployed as a Web App.

Acts as a secure API endpoint.

Stores and manages all confidential AI prompts.

Handles all communication with the various third-party AI APIs (Google, OpenAI, Anthropic, etc.).

🚀 Getting Started

Get an API Key: You must have an API key from an AI provider. The video and PDF guides above show a step-by-step process for getting a free key from Google AI Studio.

Open the Application: Navigate to https://cbc-ai-tool.netlify.app/.

Open Settings: Click the menu icon (☰) on the top-left to open the Settings sidebar.

Select Provider & Model: Choose the AI provider (e.g., Google Gemini) and the model you wish to use.

Enter API Key: Paste your API key into the designated input field. Your key is saved in your browser's local storage for your convenience and is not sent anywhere else.

Start Chatting: Select an assistant from the dropdown menu and begin your session!

👨‍💻 Project Creator

This project was conceptualized, designed, and developed by Derrick Musamali.

Email: musadrk2@gmail.com

Phone: +256750470234

📜 License

This project is licensed under the MIT License. See the LICENSE file for details.
