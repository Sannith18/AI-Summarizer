AI Summarizer Chrome Extension
------------------------------
The AI Summarizer Chrome Extension helps users quickly summarize any web content using advanced AI models like OpenAI GPT or Google Gemini.
It extracts the main points from articles, blogs, or research papers, making it easier to read and understand content in seconds.

Project Overview
----------------
Reading long articles online can be time-consuming. This Chrome Extension automatically summarizes text from any web page using AI.
It was built with a focus on simplicity, speed, and accuracy, ideal for students, researchers, and professionals who read a lot of content daily.

Key Features
------------
Summarizes any selected text or webpage content in one click
Supports OpenAI GPT and Google Gemini API
Simple popup UI with a clean and modern design
Real-time loading indicator while generating summaries
Displays concise and structured summaries
Works offline after installation (except during API calls)

Tech Stack 
----------
Languages and Tools
HTML, CSS, JavaScript
Chrome Extensions API (Manifest V3)
OpenAI API / Gemini API integration
JSON for API response handling

Concepts
--------
API Integration
Asynchronous JavaScript (Promises, Fetch API)
DOM Manipulation
Chrome Storage and Permissions
CORS handling and background messaging

How It Works
------------
User selects text on a webpage or opens the extension popup
The extension sends the content to the AI API (OpenAI or Gemini)
The model processes the text and returns a concise summary
The summary is displayed instantly in the popup interface

Project Structure
-----------------
AI-Summarizer/
│
├── manifest.json
├── popup.html
├── popup.js
├── popup.css
├── background.js
├── icons/
│ ├── icon16.png
│ ├── icon48.png
│ └── icon128.png
└── README.md

Installation Steps
------------------
Download or clone this repository:

git clone https://sannith18.github.io/AI-Summarizer/
Open Google Chrome and go to chrome://extensions/
Turn on Developer Mode (top-right corner)
Click Load unpacked
Select your project folder (AI-Summarizer)
The extension icon will appear in your Chrome toolbar

API Setup
---------
Open popup.js
Replace the API key placeholder with your own:
const OPENAI_API_KEY = "your_api_key_here";

For Gemini users, configure:
---------------------------
const GEMINI_API_KEY = "your_gemini_api_key_here";

Save and reload the extension in Chrome.
