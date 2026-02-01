# Gemini Browser AI Agent

A browser-based AI agent built using Python and Google Gemini that can autonomously control a real Chromium browser to perform web-based tasks such as searching, navigating pages, and extracting information.

This project was built as part of a GDG Cloud hands-on workshop to understand the fundamentals of agentic AI systems, browser automation, and LLM-driven task execution.

## Features

- Uses Google Gemini (gemini-2.0-flash) as the reasoning engine
- Controls a real Chromium browser session
- Executes natural-language tasks autonomously
- Extracts structured information from web pages
- Built with async Python for non-blocking execution

## Tech Stack

- Python
- Google Gemini API
- browser-use
- asyncio
- python-dotenv

## Project Structure

- main.py        Entry point for running the AI agent
- .env           Environment file for API keys (not committed)
- README.md      Project documentation

## Setup Instructions

1. Clone the repository

2. Create a virtual environment and activate it

3. Install dependencies

   pip install -r requirements.txt

4. Create a .env file in the project root and add your Google API key

   GOOGLE_API_KEY=your_api_key_here

5. Run the agent

   python main.py

A Chromium browser window will open and the agent will execute the defined task.

## Example Task

The agent performs the following actions:

- Opens google.com
- Searches for "GDG Cloud New Delhi"
- Identifies the first search result
- Returns the title text

The task can be modified directly in the code to perform more complex browser-based workflows.

## Learning Outcomes

- Understanding how agentic AI systems work
- Integrating LLMs with browser automation
- Designing prompt-driven autonomous tasks
- Working with asynchronous Python applications

## Future Improvements

- Support for headless browser execution
- Multi-step task chaining
- Structured output formats (JSON)
- Error handling and retry mechanisms
- Logging and performance tracking

## Acknowledgements

This project was developed during a GDG Cloud workshop for educational and learning purposes.

