# Greeting Bot
It is Telegram bot with the following two features:

1. Main goal is to provide the short greeting video for a person (owner of the bot) that could be shared by public link to the bot. 
2. And allow to users give the feedback for this person in the same format of short video.  

Actors:
1. user
2. admin (owner of the bot)

Admin use-cases:
1. load (update) the greeting videonote
2. get the count of new messages (any message or videonote from user)
3. show new message (FirstName LastName UserName <user_id> sent the message: ... or sent the videonote (file_id == ...): ... )
4. get the list of all users (FirstName LastName UserName <user_id>)
5. show all messages by user_id
6. [only after getting the list of all users] send message to user
7. jvm options

User use-cases:
1. see greeting videonote (owner's)
2. load own greeting videonote or message (user's)

