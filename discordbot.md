# discordbot
### [home](index)

### Features implemented so far:

1. `on_message`: Whenever a message is sent, the bot may perform some action depending on the contents of the message. 
    1. Moderation: Variety of moderation things, like blocking certain words. 
    2. Self awareness: If a message has the bot's name in it, the bot will respond "no u <3" to the message. 
    3. Happy birthday: If a message has "happy birthday" in it, the bot will send a message also saying "Happy birthday!"
2. `roll`: Takes one input: The number for the upper limit of the die. For example, `!roll 6` would roll a number between one and six (inclusive.)
3. `create`: Takes two arguments: One for type of channel to be created (text or voice) and the second for the new channel's name. For example, `!create voice newvoice` would create a new voice channel called newvoice. 
4. `mute`: Takes one argument: The user to be muted. For example, `!mute rckymntn` would mute the user rckymntn.
5. `nickname`: Takes one argument: The nickname the user wants to have. For example, `!nickname rockymountain` would change my nickname to rockymountain.
999. And some more easter eggs not documented here!