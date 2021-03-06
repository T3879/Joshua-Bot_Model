# Build a  AI Chatbot that Speaks like Your Favorite Character!

<div align="center">
  <img src="https://github.com/RuolinZheng08/twewy-discord-chatbot/blob/main/gif-demo/icon.png" width=200>
</div>

This is a Discord AI Chatbot that uses the [Microsoft DialoGPT conversational model](https://huggingface.co/microsoft/DialoGPT-medium) fine-tuned on the game transcript of [The World Ends With You](https://en.wikipedia.org/wiki/The_World_Ends_with_You) (TWEWY).

I trained the model using the lines of my favorite quirky character, Joshua (left in the image below). He has about 700 lines in total in the entire game.

<img src="https://github.com/RuolinZheng08/twewy-discord-chatbot/blob/main/gif-demo/gameplay.png" width=400><br>

Here is a demo of the Discord bot in action.

<img src="https://github.com/RuolinZheng08/twewy-discord-chatbot/blob/main/gif-demo/discord.gif" width=500><br>

You can also directly chat with the model hosted on Hugging Face's Model Hub. **[Click Here](https://huggingface.co/r3cdhummingbird/DialoGPT-medium-joshua)** to chat with the bot

<img src="https://github.com/RuolinZheng08/twewy-discord-chatbot/blob/main/gif-demo/huggingface.gif" width=400><br>

## Structure of this Project

- `model_train_upload_workflow.ipyb`: Notebook to be run in Google Colab to train and upload the model to Hugging Face's Model Hub
- `discord_bot.js`: Script to be imported into a Repl.it [chattybot.js project](https://replit.com/@ThushalCH/ChattyBotjs#index.js)


