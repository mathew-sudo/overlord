# overlord

A Termux-based root security tool installer and environment setup script.

## Features

- Displays system, user, and environment information
- Detects and configures root/proot bypass automatically
- Alters Termux display to show Kali OS if installed
- Installs a wide range of exploit tools (SearchSploit, sqlninja, Routersploit, Commix, BeEF, Zphisher, etc.)
- Installs extra Ruby security gems (Metasploit, Wpscan, Arachni, Nokogiri, etc.)
- Provides a secondary test environment for safe experimentation
- Command-driven interface for modular usage

## Usage

Run the installer script in Termux:

```bash
bash "root security tool installer"
```

## Available Commands

- `show_commands` – Display available commands
- `get_user_info` – Show Termux user info
- `display_environment` – Show VM/environment info
- `display_config` – Show installer config and auto-setup status
- `auto_setup_root_bypass` – Setup root bypass if needed
- `alter_termux_display_kali` – Show Kali OS in Termux MOTD if detected
- `setup_test_environment` – Setup a secondary test environment
- `install_exploit_tools` – Install extra exploit tools
- `install_security_gems` – Install extra Ruby security gems

## Notes

- Designed for Termux on Android, but may work in other Linux-like environments with minor adjustments.
- Use the command functions individually for modular setup or run the script for full automation.

---
Not a game.
