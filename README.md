Gemini API Call
A simple Python project demonstrating how to make an API call to Google Gemini and generate an AI response.

Technologies
Python
Google GenAI SDK
python-dotenv
Gemini API
Setup
Create a virtual environment:

python -m venv venv
Activate it on Windows:

.\venv\Scripts\Activate.ps1
Install the required packages:

pip install google-genai python-dotenv
Create a .env file:

GEMINI_API_KEY=your_api_key_here
Run
python app.py
Example
The program sends a prompt to a Gemini model and displays the generated response in the terminal.

Security
Never upload your actual .env file or API key to GitHub
