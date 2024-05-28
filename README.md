***
- 👋 Hi, I’m @sahildesai07

<div align="center" style="border: 2px solid #e94560; border-radius: 10px;">
  <img src="https://yt3.googleusercontent.com/p9g9i5N55WgCn1mFFjl8iut4BOd0O4RRjn7WB_Silj9JmJ42tE-yhdZ0oR_7m-F4kGHT22Br=s176-c-k-c0x00ffffff-no-rj" alt="Bot" width="150" style="border-radius: 10px;">
</div>

<p align="center">
  <a href="https://t.me/ultroid_official">
    <img src="https://img.shields.io/badge/Ultroid%20%F0%9D%95%8F%20Official-Channel-blue?style=for-the-badge&logo=telegram" alt="Ultroid Official Channel">
  </a>
  <a href="https://t.me/ultroidofficial_chat">
    <img src="https://img.shields.io/badge/Ultroid%20%F0%9D%95%8F%20Official-Group-blue?style=for-the-badge&logo=telegram" alt="Ultroid Official Group">
  </a>
</p>

***


## Features

- **Streamlined Code**: Unnecessary features and code have been removed for a more efficient and minimalistic bot.
- **Heroku Deployment**: Fully configured for easy deployment on Heroku.
- **Enhanced Functionality**: Includes additional features from various sources, improving the bot's overall capabilities.


## Heroku Deployment Instructions

1. **Fork and Star the Repository**
   - Start by forking and starring this repository.
   - When forking, ensure that the option "Copy the default branch only" is unchecked before forking the repository.

2. **Navigate to Your Forked Repository**
   - Once the repository is forked, navigate to your forked repository.

3. **Access the Settings**
   - Go to the settings of your forked repository.
   - Enable all actions in the settings.

4. **Run Action Workflow**
   - Go to the **Actions** tab.
   - Select the `Deploy to Heroku` action from the list of workflows.
   - Click on **Run workflow**.
   - Fill in the following variables in the form:
     - `BOT_TOKEN`
     - `OWNER_ID`
     - `DATABASE_URL`
     - `TELEGRAM_API`
     - `TELEGRAM_HASH`
     - `HEROKU_APP_NAME`
     - `HEROKU_EMAIL`
     - `HEROKU_API_KEY`
   - Run the action workflow.

5. **Finalize the Deployment**
   - After the deployment is complete, finalize the remaining variables.
   - Upload sensitive files like `token.pickle` using the `/botsettings` command.


## Contributing

Feel free to submit pull requests and open issues for any bugs or feature requests. Contributions are always welcome!


## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


## Acknowledgements

- Thanks to the original developers of the Mirror-Leech-Telegram-Bot.
- Contributions and feature integrations from various repositories.
