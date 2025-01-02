# Pulse - Simplifying Server Function 📘
Pulse is a multifunctional bot for discord with a wide variety of commands.

The commands range from basic utility commands to server wide settings.

Welcome to our introduction on how to use Pulse as efficiently as possible!

All commands  marked with a `⚙️` require the User to have the `manage_guild` permission.

# Settings
In order to use Pulse at its maximum potential, it's a great idea to set up all of the settings features first.
- `/setmodlogs [channel] ⚙️` Enable Moderation Logging for your Server
- `/setwelcomechannel [channel] ⚙️` Enable Welcome Messages in your Server
- `/setwelcomemessage [description] ⚙️` Set a custom Welcome Message

# Utility
In order to ensure smooth and efficient running of your Server, we have integrated several commands.
- `/purge [amount]` Clear a  desired number of messages in one go
- `/slowmode [delay]` Enable a slowmode counter on a channel
- `/lock [reason]` Lock the current channel that you are in
- `/unlock [reason]` Unlock the current channel that you are in
- `/codename [user] [name]` Give a User or yourself a codename
- `/assignrole [user] [role]` Assign a role to a User
- `/removerole [user] [role]` Remove a role from a User
- `/embed` Create a personalised embed.

# Moderation
In order to keep your community safe, we have implemented some useful commands.
- `/kick [user] [reason]` Kick a User from the Server
- `/ban [user] [reason]` Ban a User from the Server
- `/warn [user] [reason]` Warn a User for bad behaviour
- `/warnings [user]` View all warnings that the User has received
- `/removewarning [user] [index]` Remove a warning from a User
- `/clearwarnings [user]` Clear all warnings from a User
- `/timeout [user] [duration] [reason]` Timeout a User

# Information
Knowing more information about your Server and who is in it can always be of best interest to you.
- `/serverinfo` Get information about your Server
- `/userinfo [user]` Get information about a specific User
- `/channelinfo [channel]` Get information about a specific Channel
- `/roleinfo [role]` Get information about a specific Role

# Levelling
A competitive way to ensure User engagement in your Server.
- `/level` Check your level and XP for the Server that you are in
- `/setlevelchannel [channel] ⚙️` Set a channel to receive levelling notifications

# Variables
In instances where customisable messages are integrated, you have the option to use different variables that point to certain things.
### Member Variables
- `{member.mention}` Mentions the activating User
- `{member.name}` Gives the name of the activating User
- `{member.id}` Gives the ID of the activating User
### Server Variables
- `{guild.name}` Gives the name of your Server
- `{guild.id}` Gives the ID of your Server
- `{guild.owner}` Gives the name of the owner of your Server
- `{guild.member_count}` Gives a total count of User's in your Server
