Powershell plugin for wakatime
=======================

[![time tracker](https://wakatime.com/badge/github/Gravifer/posh-wakatime.svg)](https://wakatime.com/badge/github/Gravifer/posh-wakatime)

Automatic time tracking for commands in Powershell using [wakatime](http://wakatime.com/).

Installation
------------

Make sure you have configured wakatime API key in your [~/.wakatime.cfg](https://github.com/wakatime/wakatime#configuring) file.

1. `pip install wakatime` to install wakatime CLI, with 4.1 or higher. See more [here](https://github.com/wakatime/wakatime) for wakatime CLI.

2. For PSGallery users:
  - [Install directly from PSGallery](https://www.powershellgallery.com/packages/posh-wakatime); import this in your `$profile`.

3. For GitHub users:
  - git clone https://github.com/Gravifer/posh-wakatime.git
  - include the "Powershell-wakatime.sh" file in your `$profile` file.
  - But if you already have a PROMPT_COMMAND variable set,
    just merge yout own pre_prompt_command with the following one.
    And don't forget to create and configure your "~/.wakatime.cfg" file.

4. Open a new terminal and type commands

5. Visit https://wakatime.com/project/Terminal

Attribution
------------

Codes and ideas are integrated from bash-wakatime, pwshwaka, posh-git, code(powershell).
