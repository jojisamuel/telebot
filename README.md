# ChatGPT Telegram Integration

This repository demonstrates how to integrate ChatGPT, a powerful language model, with Telegram to create an interactive chatbot. By following the steps below, you'll be able to set up your own Telegram bot powered by ChatGPT.

## Prerequisites

- Python 3.7 or higher
- ChatGPT API credentials (API key or access token)

## Installation

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/jojisamuel/telebot.git
   cd telebot
   ```

2. Create a virtual environment (optional but recommended):

   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Configuration

1. Create `.env` file and add the following variables:

   - `OPENAI_API_KEY`: Replace with your ChatGPT API key or access token.
   - `TOKEN`: Obtain a Telegram bot token by following the [Telegram Bot documentation](https://core.telegram.org/bots#3-how-do-i-create-a-bot).
  

## Usage

1. Start the bot by running the following command:

   ```bash
   python tele_bot.py
   ```

2. Open your Telegram app and search for your bot.

3. Start a conversation with your bot and enjoy chatting with ChatGPT!

## Customization

- You can modify the behavior of the chatbot by updating the `handle_message` function in `bot.py`. Feel free to customize it according to your requirements.
- Explore the [ChatGPT API documentation](https://docs.openai.com/api/chat/create) to learn about the available options and parameters for interacting with the model.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
```

Feel free to modify and customize this README file according to your specific integration requirements.
