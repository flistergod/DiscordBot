# DiscordBot
Discord Bot created using typescript.

For now, it only runs locally. It requires a vps and maybe a db (maybe mongodb).
It only does reply messages. It needs a few node modules to create commands.
Check the dependencies on the package.json file.

When deploying to the server, convert your ts code to js with "npm run tsc". "tsc" has to be on the package.json file
Configure a middleware to always deploy the code to the server when committing in github (continuous integration)

Create the ".env" file that will have the bot token and maybe the token of your vps
