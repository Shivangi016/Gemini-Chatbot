# Gemini API Chatbot

## Overview
This project is a chatbot powered by Google's Gemini API. It enables interactive and intelligent conversations by leveraging natural language processing capabilities.

## Features
- AI-powered chatbot using Gemini API
- Supports text-based conversations
- Simple and intuitive user interface
- Easily customizable responses and behavior

## Prerequisites
Before running the chatbot, ensure you have the following:
- Python 3.7 or higher
- An active Google API key for Gemini API
- Required dependencies installed

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/gemini-chatbot.git
   cd gemini-chatbot
   ```
2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Setup API Key
1. Obtain your Gemini API key from Google Cloud Console.
2. Create a `.env` file in the root directory and add your API key:
   ```
   GEMINI_API_KEY=your_api_key_here
   ```

## Usage
Run the chatbot using the following command:
```bash
python chatbot.py
```
You can then start interacting with the chatbot via the terminal or UI.

## Customization
- Modify `config.py` to adjust chatbot settings.
- Update `responses.py` to customize chatbot replies.
- Integrate with external APIs for enhanced functionality.

## Troubleshooting
- Ensure your API key is valid and set up correctly.
- Check for missing dependencies and install them using `pip install -r requirements.txt`.
- Debug using logging features in `chatbot.py`.

## License
This project is licensed under the MIT License.

## Contributors
- [Your Name](https://github.com/yourusername)

## Acknowledgments
- Google for providing the Gemini API
- OpenAI for chatbot inspirations

