## Overview

`gemini.py` is a Python script that uses the Streamlit library to create an interactive web application. You can chat with Gemini Pro and Gemini Pro Vision (for images).

## Dependencies

- Python 3.9 or higher
- Streamlit
- Google Generative AI
- Gemini API key - [Get it here.](https://ai.google.dev).
- PIL (Python Imaging Library)
- python-dotenv

## Setup

1. Install the required Python packages:
```pip install streamlit google-generativeai pillow python-dotenv```

2. Create a .env file in the same directory as `gemini.py` and add your Gemini API key:
```GEMINI_API_KEY=your_api_key_here```

## Local usage

To start the Streamlit app, run the following command in your terminal:
```streamlit run gemini.py```

Once the app is running, you can interact with it in your web browser. You can type messages to the AI model and it will respond. If you choose to use the Image-Chat model, you can also upload an image, and the AI model will generate a response based on both the image and your text input.

## Download Peek AI

Looking for an all-in-one AI app with multiple AI (ChatGPT, Bard, Perplexity, Poe, and more) support? [Download Peek AI](https://prateekkeshari.gumroad.com/l/peek).
