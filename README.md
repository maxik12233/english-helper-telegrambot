
# English Helper Telegram Bot

This project provides an application that hosts a server to communicate with telegramAPI using long polling

### Technology or what I learned
I used a third-party library to work with telegramAPI.\
In the project I implemented a clean code architecture.\
I used MongoDB to store the required records\
I wrote my own simple SDK for communicating with GoogleAPI\
I tested this SDK (The rest of the application cannot be tested due to the lack of interfaces in the library that I used to communicate with telegram)

### How to use
1. Clone this repository to your local machine
2. You have to create all environmental variables that needed: MongoDB URI String, Telegram Bot API Key, Google Translate API Key
3. Build binary file with cmd/bot/main.go file and run it
4. Now your local machine handling bot's chat events

### What this bot can do?
If you write a message to the bot with text, it will translate it into the language of the user’s config.\
The bot will remember this translation in the database.\
In the future, by writing the /repeat command, the bot will begin to write to the user the words that he once translated and wait for the user’s response.
If the answer is correct, the bot will continue to give words to repeat 

You can use this bot to learn new words and repeat these learned words in the future!



