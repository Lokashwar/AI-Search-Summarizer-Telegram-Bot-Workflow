# AI-Search-Summarizer-Telegram-Bot-Workflow
---
## Overview

- A user sends a message to a Telegram bot.  
- The workflow:  
  1. **Triggers** from Telegram.  
  2. **Searches** the web using Tavily API with the user’s query.  
  3. **Processes & formats** results using a Code node.  
  4. **Summarizes** the findings via an AI Agent connected to Groq’s `deepseek-r1-distill-llama-70b` model.  
  5. **Sends back** the summarized response to the same Telegram chat.
---
---
## Setup: 

1. Import the JSON workflow into your n8n instance.  
2. Configure credentials:  
   - Go to **Credentials** in n8n.  
   - Add your **Telegram account** (bot token).  
   - Add your **Tavily account** (API key).  
   - Add your **Groq account** (API key).  
3. Enable the workflow in n8n.  
4. Start chatting with your Telegram bot
---   
