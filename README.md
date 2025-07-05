# Camera & Computer Equipment Store Telegram Bot

A Telegram bot for a camera and computer equipment store that handles customer orders and inquiries.

## Features

- Browse product catalog by categories
- Place orders with delivery information
- Upload payment receipts
- Multi-language support (Russian, English, Tajik)
- Automatic email notifications for new orders
- FAQ system for common questions
- GitHub deployment for 24/7 operation

## Setup

1. Clone this repository
2. Install dependencies:
   ```
   npm install
   ```
3. Configure environment variables in `.env` file:
   - `TELEGRAM_BOT_TOKEN`: Your Telegram bot token
   - `EMAIL_USER`: Email for sending notifications
   - `EMAIL_PASS`: Email app password
   - `EMAIL_TO`: Email to receive order notifications
   - `PORT`: Port for the Express server

4. Start the bot:
   ```
   npm start
   ```

## Deployment

This bot is designed to be easily deployed on GitHub-friendly platforms:

### Deploying to GitHub + Render/Heroku/Railway

1. Push this repository to GitHub
2. Connect your GitHub repository to a service like Render, Heroku, or Railway
3. Configure the same environment variables on the hosting platform
4. The service will automatically deploy and run your bot 24/7

## Bot Commands

- `/start` - Start the bot and see the main menu
- Other commands are handled through the menu interface

## Customization

- Update the product catalog in `src/catalog.js`
- Modify FAQs in `src/questionHandler.js`
- Adjust translations in `src/i18n.js`

## License

MIT