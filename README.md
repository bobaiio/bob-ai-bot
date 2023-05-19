# Bob AI Bot for Telegram


## Bob AI Introduction

Bob AI Bot can act as your Telegram contact. You can chat with it personally, share with a contact, and collabrate in a group chat. We attach great importance to privacy protection and make sure the Bot can't acquire any unrelated messages in group chats.

The Bot shares knowledge and inspires exciting new ideas. Many interesting features, such as **DALL·E** and **Whisper** are integrated together to make our Bot smarter and more usable.

We hope you enjoy it!

## Bob AI Features

The Telegram Bot features the following functions:

- **ChatGPT, the AI consultant**. You can customize the Bot's character according to preference.
- **DALL·E, the Image Generation AI Model**. Send a short prompt to the Bot and get your own painting.
- **Whisper, the Intelligent Speech Recognizer**. The Bot can read your voice messages.
- **Azure TTS, the Speech service feature that converts text to lifelike speech**. The Bot can reply with voice messages.
- **Comprehensive Privacy Protection**. The Bot is unable (and of course we won't) to collect any message in group chat except user prompts.

Additonal features:

- Bob AI role and temperature Customization.
- The Telegram _inline mode_ allows you to query the Bot privately in a chat with a contact or group, even if the Bot is not a member.
- User White-list to control who can use the Bot. You can also set `allow_all_users` to `true` to allow any users to use the Bot.
- Set the daily limitation of requirements to **DALL·E**.
- Grant more resources to _Super Users_.
- Docker deployment is supported.


### How to use Bob AI

The Bot works in both personal and group chat of Telegram.
In a personal chat, simply send a message to the Bot and it will reply to you.
In a group chat, use the `/ask` to invoke the Bot.

In a personal chat with a contact, use `@your_bot_name <your messages>` to invoke the Bot with Telegram inline mode. Both you and your contact can see the Bot's reply in the chat.

1. The following commands are supported:

- `/start`: Start the Bot.
- `/role <prompt>`: Set role for conversation. (e.g /role Note 1)
- `/ask` : Invoke the Bot in group chat.
- `/image <prompt>`: Generate image from prompt. (e.g /image Lion)
- `/clear`: Clear the conversation context.
- `/getid`: Get your Telegram user ID.
