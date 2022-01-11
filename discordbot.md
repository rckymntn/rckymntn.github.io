# discordbot
### [home](index)

### Features implemented so far:

1. `on_message`: Whenever a message is sent, the bot may perform some action depending on the contents of the message. 
    1. Moderation: If a message has a blocked word in it, the message is deleted. 
    2. Self awareness: If a message has the bot's name in it, the bot will respond "no u <3" to the message. 
    3. Happy birthday: If a message has "happy birthday" in it, the bot will send a message also saying "Happy birthday!"
2. `roll`: Rolls a multifaced die from one to the user specified limit. For example, `!roll 6` would roll a number between one and six (inclusive.)
3. `create`: Takes two arguments. One for type of channel to be created (text or voice) and the second for the new channel's name. For example, `!create voice newvoice` would create a new voice channel called newvoice. 
999. And some more easter eggs not documented here!