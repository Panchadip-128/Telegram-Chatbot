# Telegram-Chatbot


# Telegram Chatbot Using Dialogflow

This repository contains a Telegram chatbot created using Dialogflow, a natural language understanding platform. The chatbot interacts with users on Telegram and provides responses based on predefined intents and machine learning models configured in Dialogflow.

## Features

- **Natural Language Processing**: Utilizes Dialogflow's NLP capabilities to understand user queries.
- **Integration with Telegram**: Communicates seamlessly with users via Telegram messenger.
- **Customizable Responses**: Easily customizable responses based on intents and entities defined in Dialogflow.
- **Webhook Integration**: Optionally integrates with a webhook for dynamic responses and data retrieval.

## Setup Instructions

To deploy and run the Telegram chatbot locally or on a server, follow these steps:

1. **Dialogflow Setup**:
   - Create a new Dialogflow agent.
   - Define intents, entities, and responses as per your chatbot's functionality.
   - Enable the Telegram integration and obtain the API token.

2. **Telegram Bot Setup**:
   - Create a new bot on Telegram using BotFather.
   - Obtain the bot token.

3. **Environment Variables**:
   - Create a `.env` file and add the following variables:
     
     TELEGRAM_TOKEN=<Telegram Bot Token>
     DIALOGFLOW_PROJECT_ID=<Dialogflow Project ID>
     GOOGLE_APPLICATION_CREDENTIALS=<Path to Service Account JSON>
     

4. **Deployment**:
   - Clone this repository:
     
     git clone https://github.com/yourusername/telegram-dialogflow-bot.git
     
   - Install dependencies:
     
     npm install
     
   - Start the application:
     
     node index.js
     
   - Your Telegram chatbot using Dialogflow should now be operational.

## Contributing

Contributions are welcome! If you have ideas for improvements, feel free to open an issue or submit a pull request.

