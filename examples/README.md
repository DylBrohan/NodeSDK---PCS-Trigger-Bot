# Running The Sample Apps

- [Close Conversation Bot](#close-conversation-bot)


## Close Conversation Bot
The social bot is an example SDK implementation in which the bot accepts incoming conversations as the assigned agent. It listens for all open conversations and closes then sequentially.

Pre-requisites:
- A LivePerson Account with Messaging
- A user with Agent Manager permissions

To run the [close conversation bot example](https://github.com/LivePersonInc/node-agent-sdk/tree/master/examples/close-conversation-bot)

- Provide the following `env` variables:
    - `LP_ACCOUNT` - Your LivePerson account ID
    - `LP_USER` - Your LivePerson agent username
    - `LP_PASS` - Your LivePerson agent password

- Run:
    - Unix Shell
        ```sh
       LP_ACCOUNT=1234567 LP_USER=BotUserName LP_PASS=b0tpa55word node examples/close-conversation-bot/main.js
        ```
    - Windows Shell
       ```sh
       set LP_ACCOUNT=1234567
       set LP_USER=BotUserName
       set LP_PASS=b0tpa55word
       node examples/social-bot/main.js
       ```
