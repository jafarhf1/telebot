# Telegram Chatbot

This is developed as one of [Algoritma Academy](https://algorit.ma/) Data Analytics Specialization Capstone Projects. The deliverable of this project is a Python script to create a Telegram chatbot using `telebot` package. We will also deploy the chatbot to [Railway](https://railway.app/) and use `Flask` to set up the backend application.

## Project File Structure

```
telebot
├── 📁 data_input
├── 📁 template_text
├── </> app.py
├── </> bot_local.py
├── 🚀 Procfile
├── 📝 requirements.txt
└── 📝 runtime.txt
```

Here are the chatbot functionalities:

1. Command `/start` or `/help`: send welcome message containing list of available commands.

2. Command `/about`: send information about the bot developer.

3. Command `/summary`: generate text report for selected campaign ID.

4. Command `/plot`: generate visualization and voice message report per age group for selected campaign ID.

5. Default message: handle messages other than the previous commands.

This bot is expected to run **continuously** on a server. A `Flask` application is deployed to Railway. 
