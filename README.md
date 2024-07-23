# Pyla AI Discord Bot

Pyla AI is a Discord bot designed to assist users with questions about the Pyla AI bot in Brawl Stars. It uses natural language processing to provide helpful information about bot configuration, usage, and troubleshooting.

## Features

- Answer questions about Pyla AI bot and Brawl Stars
- Rate limiting to prevent spam
- User feedback system with voting buttons
- Usage statistics tracking

## Requirements

- Python 3.11 or newer
- Discord.py
- OpenAI API
- LangChain
- Other dependencies listed in `requirements.txt`

## Setup

1. Clone this repository
2. Install dependencies:
3. Set up environment variables:
- Create a `.env` file in the project root
- Add your Discord bot token and OpenAI API key:
  ```
  DISCORD_TOKEN=your_discord_token_here
  OPENAI_API_KEY=your_openai_api_key_here
  ```
4. Prepare your knowledge base:
- Add your Pyla AI and Brawl Stars information to `pyla.txt`

## Usage

1. Run the bot:
2. In Discord, use the following commands:
- `!question [your question]`: Ask a question about Pyla AI or Brawl Stars
- `!help`: Display available commands
- `!stats`: Show bot usage statistics

## Configuration

- Adjust rate limiting settings in `main.py`:
```python
RATE_LIMIT = 5  # messages
TIME_WINDOW = 60  # seconds

This README provides an overview of the project, its features, setup instructions, usage guide, and other relevant information for users and potential contributors on GitHub.
