# Landmark Information AI Assistant

> **Note:** This project is still a work in progress and I plan to enhance it in the future.

This is a Streamlit web application that uses OpenAI's GPT-4o model and LangChain to identify landmarks from images and answer questions about them using external tools like Wikipedia and web search.

## Features
- Upload an image of a landmark to identify it.
- Ask questions about the identified landmark.
- Uses AI agents and external tools (Wikipedia, DuckDuckGo search) for information retrieval.
- Powered by OpenAI and LangChain.

## Requirements
- Python 3.8+
- [Streamlit](https://streamlit.io/)
- [LangChain](https://python.langchain.com/)
- [langchain-openai](https://python.langchain.com/docs/integrations/llms/openai)
- [langchain-community](https://python.langchain.com/docs/integrations/community)
- [python-dotenv](https://pypi.org/project/python-dotenv/)

## Setup
1. **Clone the repository**
2. **Install dependencies:**
   ```bash
   pip install streamlit langchain langchain-openai langchain-community python-dotenv
   ```
3. **Create a `.env` file** in the project root with your OpenAI API key:
   ```env
   OPENAI_API_KEY=your_openai_api_key_here
   ```
4. **Run the app:**
   ```bash
   streamlit run landmark_helper.py
   ```

## Usage
- Upload a landmark image (JPG, JPEG, or PNG).
- Enter a question about the landmark.
- The app will identify the landmark and answer your question using AI and external tools.
