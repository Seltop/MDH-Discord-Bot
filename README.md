# Seltop bot

Let's go over the config...

## Config

First off, we need the discord bot token. This is the token that you get from the discord developer portal. You can get it by creating a new application and then creating a bot. Once you have the bot created, you can copy the token and paste it into the `config.js` file.

- `debugMode`: This is a boolean value that determines if the bot will print debug messages to the console. This is useful for debugging the bot.

- `database`: This is the connection settings for the database. The bot uses a MySQL database to store data. You will need to create a database and a user for the bot to use. You can then paste the connection settings into the `config.js` file.

- `syncDatabase` & `resetDatabase`: These two options MUST be on for the first time running the bot, then turn them off unless you want to reset the database again.

- `guildId`: This is the ID of the discord server that the bot will be running on. You can get this by right-clicking on the server and clicking "Copy ID".

- `paypal`: This is the PayPal API credentials. You can get these by creating a new app on the PayPal developer portal.

- `stripe`: This is the Stripe API credentials. You can get these by creating a new account on the Stripe website.

- `wallet`: Includes the server % of the payments done in the server and the withdrawal requests channel ID.

- `support`: You can add questions, put the support categories, staff roles, ping roles, and transcripts channel.

- `departments`: These are the freelancing departments you're offering. An example is provided in the `dist/config.js` file.

- `commissions`: This has a `staffRoles` option which are the roles that can see all the tickets. It also includes a reviews channel for the reviews, freelancer role, showcase channel, and completed tickets category.

- `vc`: This is the voice chat settings. You can set the category and the roles that can join the voice chat.

- `staffQuestions`: This is for the staff application process.

- `channels`: Just a channel list for the channels needed by the bot.

- `eloTiers`: This is for the elo system. You can set the roles for each role.

- `roles`: Just a role list for the roles needed by the bot.

- `embeds` & `buttons`: These are the embeds and buttons for the bot. You can change the colors, titles, etc.

## Commands

- `add`: Add a user to the ticket.

- `addtowallet`: Add money to a user's wallet.

- `admin`: Includes a lot of useful management commands for the freelancing system.

- `announce`: Announce a message to a channel.

- `application`: Manage an application.

- `ban`: Ban a user.

- `clientprofile`: View a client's profile.

- `close`: Close a ticket.

- `elo-top`: View the top elo players.

- `elo`: View a user's elo.

- `embed`: Create an embed.

- `follow`: Follow someone on social media.

- `freelancerpanel`: For the freelancer application process.

- `getpaypal`: Get a user's PayPal.

- `giveaway`: Manage a giveaway.

- `invoice`: Create an invoice.

- `kick`: Kick a user.

- `leaderboard`: View the levels leaderboard.

- `level`: View a user's level.

- `mute`: Mute a user.

- `panel-all`: Send all the panels.

- `profile`: View a freelancer's profile.

- `punishments`: View a user's punishments.

- `remove`: Remove a user from the ticket.

- `review`: Review a freelancer.

- `schedule`: Schedule a message.

- `set`: For freelancers to set their profile.

- `staffpanel`: For the staff application process.

- `start-competition`: Start a competition.

- `suggest`: Suggest something.

- `suggestion`: Manage a suggestion.

- `ticketspanel`: For the tickets system.

- `unfollow`: Unfollow someone on social media.

- `wallet`: Manage your wallet.
