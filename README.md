# RB Anticheat logs
# Date: 2023-02-26 20:00:00 GMT
# Version: 1.0.0

## How to relay

1. When the bot joins it automatiacally assigns the tag "rb1337" to the bot, use this tag to relay the logs to the bot.

2. Using the following command you can relay the logs to the bot:

`/titleraw @a[tag=rb1337] subtitle {"rawtext": [{"text": "RB1337: RBAC_ANTICHEATNAMENOSPACE DATA"}]}`

3. The bot will automatically parse the logs and send them to the channel via a webhook.

## Data format

To add a description to the data you can use the following format:
`description:description here`

To then follow that with a custom url you can use the following format:
`description:description here;url:https://example.com`

For nested fields use the following format:
`description:description here;url:https://example.com;footer.text:hello`

## Example

`/titleraw @a[tag=rb1337] subtitle {"rawtext": [{"text": "RB1337: RBAC_anticheatname data;description:This is a description;url:https://example.com;footer.text:hello"}]}`
<img src=
"https://i.ibb.co/jrDmHh9/image.png">

## Colors

`color:ff3377`

## Fields

`fields[0].title:Title;fields[0].value:Value;fields[0].inline:true`
