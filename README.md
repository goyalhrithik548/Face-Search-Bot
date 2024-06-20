# Face Search Bot

## Overview
This repository contains the code for a Telegram bot that allows users to search the internet for images that match a face in a photo they provide. The bot uses the FaceCheck API to perform the search and returns the most matching image along with a similarity score and URL.

## Features
- Start the bot with a welcome message.
- Provide information about the bot and its functionalities.
- Send a photo to the bot and receive:
  - The similarity score
  - The URL of the most matching image
  - A thumbnail of the most related image
- User-friendly commands for interaction.

## Requirements
- Python 3.x
- Telegram Bot API Key
- FaceCheck API Token

## Installation
Configure the bot by setting your API keys in the script:
    - `APITOKEN`: Your FaceCheck API token
    - `API_KEY`: Your Telegram bot API key

## Usage
Interact with the bot on Telegram:
    - `/start`: Initiates the bot and gives a welcome message.
    - `/help`: Provides a help menu with available commands.
    - `/content`: Displays information about the bot.
    - `/contact`: Provides contact information for the bot creator.
    - Send a photo: Simply send a photo to the bot, and it will search the internet for similar images.

## Commands
- `/start`: Start the bot and receive a welcome message.
- `/help`: Get a help menu with available commands.
- `/content`: Information about the bot and its usage.
- `/contact`: Contact information for the bot creator.

## Example Usage
1. Start the bot by typing `/start` to get a welcome message.
2. Send a photo of a face.
3. Receive the search results including the similarity score, the URL of the most matching image, and a thumbnail of the most related image.

## Project Structure
- `bot.py`: Main script to run the Telegram bot.
- `photo.jpg`: Local file to save the downloaded image temporarily.
- `README.md`: Documentation providing an overview of the project, installation steps, usage, and more.

## Contact
Hello! This is Hrithik, the creator of this bot. You can reach out to me via email at (goyalhrithik548@gmail.com).

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Created By
Hrithik Kumar

[GitHub Profile](https://github.com/goyalhrithik548)
