# Groq Chat Streamlit App

This [Streamlit](https://streamlit.io/) app integrates with the [Groq API](https://groq.com/) to provide a chat interface where users can interact with advanced language models. It allows users to choose between two models for generating responses, enhancing the flexibility and user experience of the chat application.

## Functionality

- **Model Selection**: Choose from various Groq models like `mixtral-8x7b-32768`, `llama2-70b-4096`, `Gemma-7b-it`, `llama2-70b-4096`, `llama3-70b-8192`, and `lama3-8b-8192` models to tailor the conversation according to each model's capabilities.
- **Chat History**: Keeps track of your chat with the AI for a smooth, ongoing conversation.
- **Real-time Responses**: Generates responses dynamically using Groq's API, creating a natural flow of conversation.

## Requirements

- Streamlit
- Groq Python SDK
- Python 3.7+

## Getting Started

- **Install Dependencies**:
  Use pip to install required libraries:

  ```bash
  pip install streamlit groq
  ```

- **Obtain Groq API Key**:

Get an API key from Groq.
Securely store it in a .streamlit/secrets.toml file:

```toml
# .streamlit/secrets.toml
GROQ_API_KEY="your_api_key_here"
```

- **Run the App**:
  Navigate to the app's directory and run:

```bash
streamlit run streamlit_app.py
```

## Usage

The application opens with a title and a dropdown menu for selecting the desired language model.
Users interact with the chosen model through a chat interface by entering prompts.
The interface displays both user input and AI responses.

## Customization(optional)

Language Models: Easily integrate new models from Groq as they become available.
User Interface: Modify the UI for a tailored experience.
Groq API: Extend functionality through additional interactions with the Groq API.
