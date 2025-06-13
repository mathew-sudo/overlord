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

Or, if you have made the script executable:

```bash
./root\ security\ tool\ installer
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
- `install_superuser_tools` – Install superuser/rooting tools
- `mk_user_rootsuperuser` – Create root superuser environment
- `ensure_rootsuperuser_access` – Test and ensure root/superuser access
- `auto_configure_advanced_user` – Auto-configure user and grant advanced access
- `install_web_tools` – Install web security tools
- `install_android_tools` – Install Android/mobile security tools
- `install_password_crackers` – Install password cracking tools
- `install_network_tools` – Install network analysis tools
- `install_fuzzing_tools` – Install fuzzing tools
- `install_enum_tools` – Install enumeration tools
- `install_extra_gems` – Install more Ruby gems
- `install_more_exploits_tools_gems` – Install more exploits, tools, and gems with error handling
- `install_even_more_tools_exploits_gems` – Install even more exploits, tools, and gems
- `show_linenum` – Show LinEnum usage/help
- `show_peass` – Show PEASS-ng usage/help
- `show_cmsmap` – Show CMSmap usage/help
- `show_sn1per` – Show Sn1per usage/help
- `show_feroxbuster` – Show feroxbuster usage/help
- `show_mitm6` – Show mitm6 usage/help
- `show_responder` – Show Responder usage/help
- `show_awesome_waf` – Show Awesome-WAF usage/help
- `show_empire` – Show Empire usage/help
- `show_exploitdb` – Show ExploitDB usage/help
- `show_pspy` – Show pspy usage/help
- `show_gobuster` – Show Gobuster usage/help
- `show_bloodhound` – Show BloodHound usage/help
- `show_crackmapexec` – Show CrackMapExec usage/help
- `show_enum4linux` – Show enum4linux usage/help
- `show_powerup` – Show PowerUp usage/help
- `show_powersploit` – Show PowerSploit usage/help
- `show_kerbrute` – Show Kerbrute usage/help
- `show_kerberoast` – Show Kerberoast usage/help
- `show_rubeus` – Show Rubeus usage/help
- `show_sharphound` – Show SharpHound usage/help
- `show_impacket` – Show Impacket usage/help

## Notes

- Designed for Termux on Android, but may work in other Linux-like environments with minor adjustments.
- Use the command functions individually for modular setup or run the script for full automation.

---
Not a game.
