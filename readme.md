# Discord Bot

A feature-rich Discord bot built to enhance your Discord server experience with a variety of commands and functionalities.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [Commands](#commands)
- [Contributing](#contributing)
- [License](#license)

## Features

- Moderation commands
- Fun commands
- Utility commands
- Customizable settings
- And more!

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/discord-bot.git
    cd discord-bot
    ```

2. Install the dependencies:

    ```bash
    npm install
    ```

3. Set up your environment variables. Create a `.env` file in the root directory of the project and add your Discord bot token:

    ```plaintext
    DISCORD_TOKEN=your-bot-token
    ```

## Configuration

Configure the bot settings in the `config.json` file. Here, you can customize various bot settings like command prefix, bot owner ID, etc.

```json
{
    "prefix": "!",
    "ownerID": "your-discord-id",
    "activity": "with code!"
}
