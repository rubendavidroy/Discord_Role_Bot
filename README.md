# Discord Role Bot

> [!NOTE]
> This is a really old project and I do not recommend using it unless you are trying to learn

## Installation

1. **Clone repo**
    ```bash
    git clone https://github.com/rubendavidroy/Discord_Role_Bot.git
    cd Discord_Role_Bot
    ```

2. **Install dependencies**
    ```bash
    pip install -r requirements.txt
    ```

3. **Set up `config.json`**
   Edit `config.json` to configure the `ROLE_ID`, `CHANNEL_ID`, and `PREFIX` according to your server
   `ROLE_ID`: The role ID of the admins on the server
   `CHANNEL_ID`: The channel ID of the announcements channel where it will announce the promotions & demotions
5. **Set up environment variables**
   Edit `.env` and change `your_bot_token_here` with your actual bot token

## Configuration

- **config.json**: Here you set your server and channel configs.
  - `ROLE_ID`: The ID of the role required to use the promote/demote commands
  - `CHANNEL_ID`: The ID of the channel where the bot will announce promotions/demotions
  - `PREFIX`: The prefix for bot commands (e.g., `!`)

- **.env**: Contains the environment variables
  - `BOT_TOKEN`: The token of your Discord bot

## Bot Usage

1. **Run the bot**
   Run the bot via:
    ```bash
    python main.py
    ```

2. **Bot Commands**

   - `!promote`: Promotes the user to a designated role.
   - `!demote`: Demotes the user from a designated role.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for more information.
