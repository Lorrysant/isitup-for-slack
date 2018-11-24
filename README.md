# whatis-for-slack

Custom slash command to use acronymn lookup functionality to check what an acronymn from within Slack

## REQUIREMENTS

* A custom slash command on a Slack team
* A web server running PHP5 with cURL enabled
* A valid SSL certificate for your web server (not self-signed)

## USAGE

* Place the `whatis.php` script on a server running PHP5 with cURL and a valid SSL certificate.
* Set up a new custom slash command on your Slack team: https://slack.com/apps/A0F82E8CA-slash-commands
* Under "Choose a command", enter whatever you want for the command. /whatis is easy to remember.
* Under "URL", enter the URL for the script on your server.
* Leave "Method" set to "Post".
* Decide whether you want this command to show in the autocomplete list for slash commands.
* If you do, enter a short description and usage hint.
* Update the `isitup.php` script with your slash command's token.

## DOWNLOAD 
This project was heavily based off the IsitUp For Slack project listed below.
You can download the completed script and a tutorial for writing your own at https://github.com/mccreath/isitup-for-slack/
Googlesheet funtionality based off Matt Northams recomendations found here https://www.mattnortham.com/blog/2016/a-google-docs-slackbot-tracker-thing/
