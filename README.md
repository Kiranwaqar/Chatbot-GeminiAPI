# Chatbot-GeminiAPI

This project is a simple AI-powered chatbot built using **Google's Gemini API** (Generative AI model). It allows users to interact with the chatbot by asking questions or making requests, and the chatbot responds with generated content based on the user's input.

The project uses **Gradio** to create an interactive user interface for easy interaction with the model. Users can input their queries, and the chatbot will respond accordingly.

## Features

- AI-powered chatbot powered by **Google Gemini API**.
- Provides real-time responses to user input.
- Built with Python, utilizing libraries like `google-generativeai`, `dotenv`, and `gradio`.
- Simple interface for seamless user interaction.

## Requirements

To run this project, you need the following:

- Python 3.x
- Google API key to access **Gemini AI**.
- Required Python libraries: `google-generativeai`, `dotenv`, and `gradio`.

## Setup

### 1. Clone the repository

git clone https://github.com/yourusername/Chatbot-GeminiAPI.git

cd Chatbot-GeminiAPI

### 2. Install dependencies
Create a virtual environment (optional but recommended) and install the required dependencies:

pip install -r requirements.txt

### 3. Set up your Google API key
Sign up or log in to Google Cloud.

Create a new project and enable the Gemini API (or any relevant API depending on the current API offerings).

Obtain your Google API key.

Create a .env file in the root of the project and add the following line (replace your_google_api_key_here with your actual API key):

GOOGLE_API_KEY=your_google_api_key_here

### 4. Run the Chatbot
Once the setup is complete, you can run the chatbot with the following command:

python app.ipynb

This will launch the Gradio interface, where you can start chatting with the AI model!

## Usage
After running the chatbot, the Gradio interface will open in your browser.

Type a query in the input box, and the chatbot will provide a response based on the Gemini model.

## Example:
User Input: "Tell me a joke about a bear."

Chatbot Response: "Why don’t bears make good friends? Because they always bear a grudge!"

## Project Structure
app.ipynb: Main script where the chatbot's logic resides.

.env: Stores sensitive information like the Google API key.

requirements.txt: Lists the Python packages required for the project.

## Libraries Used
google-generativeai: For accessing Google's Gemini AI model.

dotenv: To load environment variables (API key).

gradio: To create a user interface for the chatbot.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements
Google for providing the Gemini API.

Gradio for making it easy to create interactive UIs.

