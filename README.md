# Dracula for Guacamole SSH Console
Port of [Dracula Theme](https://draculatheme.com) for [Apache Guacamole](https://guacamole.apache.org) SSH Console/Client

## Usage
Copy and paste the [color definitions](https://github.com/lonepie/dracula-guacamole-ssh/raw/main/dracula-guacamole-ssh.md) under Display/Color scheme/Custom/Defails:
![settings]
More detailed instructions are available in the [Guacamole Docs](https://guacamole.apache.org/doc/gug/configuring-guacamole.html#terminal-display-settings)

## Screenshot
![screenshot]

## Bonus: Custom Fonts
In order to use a custom/patched font, it must be installed on the server running Guacd. For the [guacamole/guacd](https://hub.docker.com/r/guacamole/guacd) container, simply mount the .ttf file in `/usr/share/fonts/`

[settings]: https://github.com/lonepie/dracula-guacamole-ssh/raw/main/images/settings.png "Guacamole SSH Display Settings"
[screenshot]: https://github.com/lonepie/dracula-guacamole-ssh/raw/main/images/screenshot.png "Dracula Theme in Guacamole SSH"

## Credits
[Dracula for kitty](https://github.com/dracula/kitty)
