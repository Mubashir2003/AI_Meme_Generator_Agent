# AI_Meme_Generator_Agent
Uses Multiple LLM Models to generate Memes based on Prompt
AI Meme Generator Agent - Browser Automation

An AI-powered meme generator that uses browser automation to create memes based on your input. This app integrates multiple large language models (LLMs) to guide the meme creation process on ImgFlip automatically.

📌 Features

Generate memes from textual prompts.

Supports multiple AI models:

Claude

Deepseek

OpenAI GPT-4o

Browser automation to:

Search relevant meme templates.

Add top and bottom captions.

Generate meme image links.

Provides direct meme preview and URL.

🛠️ Requirements

Python 3.10+

Install dependencies using pip:

pip install streamlit asyncio re langchain_openai langchain_anthropic browser_use


API keys for selected LLM:

Claude: Anthropic Console

Deepseek: Deepseek Platform

OpenAI: OpenAI Platform
How It Works

Takes a user query describing the meme idea.

The AI LLM analyzes the query to:

Identify the main action verb.

Select an appropriate meme template from ImgFlip.

Generate Top Text (setup) and Bottom Text (punchline).

Automates browser actions to:

Search the template.

Fill captions.

Generate the meme.

Returns the final meme URL.

⚠️ Important Notes

Ensure your API key has access to the selected LLM.

The AI may retry generating the meme if the first attempt doesn’t make sense.

The app depends on the ImgFlip website’s structure. Any site changes may require code updates.
