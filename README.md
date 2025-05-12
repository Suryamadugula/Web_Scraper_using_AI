# AI Web Scraper Tool 🤖

This project is a web scraping and parsing tool built with Python. It allows users to scrape content from a website, clean the extracted data, and parse specific information using AI-powered natural language processing.

## Features

- **Web Scraping**: Extracts content from a given website URL.
- **Content Cleaning**: Cleans and processes the extracted HTML content.
- **AI-Powered Parsing**: Uses a language model to parse specific information based on user-provided descriptions.
- **Streamlit Interface**: Provides an interactive web interface for ease of use.

## Project Structure

- `main.py`: The Streamlit app that serves as the user interface.
- `parse.py`: Contains the logic for parsing content using the `OllamaLLM` language model.
- `scrape.py`: Handles web scraping and content extraction.
- `requirements.txt`: Lists the dependencies required for the project.

# Dependencies
The project requires the following Python libraries:

python-dotenv |
streamlit |
langchain |
langchain_ollama |
selenium |
beautifulsoup4 |
lxml |
html5lib |
