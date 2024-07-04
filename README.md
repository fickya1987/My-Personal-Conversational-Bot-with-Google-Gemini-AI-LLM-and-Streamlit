# My-Personal-Conversational-Bot-with-Google-Gemini-AI-LLM-and-Streamlit

Welcome to my project repository for "My Personal Conversational Bot with Google Gemini AI LLM and Streamlit". This project integrates Google Gemini AI for conversational responses and uses Streamlit to provide an interactive user interface. The bot maintains a chat history to ensure continuity and context-awareness during interactions.

## Project Overview

This project aims to create an intelligent conversational bot capable of providing real-time responses to user queries. By leveraging the Google Gemini AI language model, the bot can understand and respond to questions accurately. Streamlit is used to create a user-friendly interface for seamless interaction.

## Features

- **Real-Time Interaction**: Provides immediate responses to user queries.
- **Google Gemini AI Integration**: Utilizes advanced AI capabilities for accurate and context-aware responses.
- **Streamlit Interface**: Easy-to-use web interface for interacting with the bot.
- **Chat History**: Maintains a history of the conversation for continuity.
- **Secure API Management**: Uses environment variables to securely manage the API key.

## Installation

### Prerequisites

- Python 3.x
- Streamlit
- Google Gemini AI library

### Setup Instructions

1. **Clone the repository**:

   ```sh
   git clone https://github.com/yourusername/personal-conversational-bot.git
   cd personal-conversational-bot
   ```

2. **Install required libraries**:

   ```sh
   pip install streamlit google-generativeai
   ```

3. **Set up your Google Gemini API key**:

   Make sure you have your API key from Google Gemini AI. Set it as an environment variable:

   ```sh
   export GEMINI_API_KEY='your_api_key'
   ```

## Running the Application

1. **Start the Streamlit application**:

   ```sh
   streamlit run app.py
   ```

2. **Interact with the bot**:

   - Open your web browser and navigate to the local URL provided by Streamlit (usually `http://localhost:8501`).
   - Enter your question in the input box and click the "Ask the question" button.
   - View the bot's response and the chat history on the web page.

## Project Structure

- `app.py`: Main application file containing the Streamlit app and logic for interacting with Google Gemini AI.
- `requirements.txt`: List of required Python packages.

## Usage

### Importing Libraries and Setting Up Environment

Ensure that you have imported all necessary libraries including Streamlit and Google Gemini AI. Set your Google Gemini API key as an environment variable for secure access.

### Running the Application

After setting up the environment and installing dependencies, run the Streamlit app. This will open a web interface where you can interact with the bot. The application maintains a chat history, ensuring that the bot's responses are contextually relevant based on previous interactions.

### Handling User Queries

Enter your query in the provided input box and submit it. The bot processes the query using Google Gemini AI and returns a response. Both the query and the response are stored in the session state to maintain the chat history.

## Acknowledgements

Special thanks to KODI PRAKASH SENAPATI Sir for their invaluable mentorship and guidance throughout the development of this project.

## Future Enhancements

- Integration with additional APIs to expand the bot's knowledge base.
- Improvement of the user interface for better user experience.
- Advanced NLP techniques to enhance response quality.
- Deployment to a cloud platform for broader accessibility.

Feel free to explore the project, and don't hesitate to reach out if you have any questions or suggestions!

## License

---

Connect with me on LinkedIn and check out my other projects on GitHub.

#ConversationalBot #GoogleGemini #AI #Streamlit #Python #MachineLearning #ArtificialIntelligence #DataScience #Chatbot #TechInnovation #Coding #Programming #APIs #SessionManagement #ErrorHandling #RealTime #UserExperience #CareerJourney #Thankful #Mentorship
