# i3/Sway Installation Script

**Updated: April 14, 2025**

This repository contains Bash scripts for installing the i3 or Sway window manager on Debian 12 (Bookworm) or Sid (Unstable) systems.

###### Note: A minimal install is recommended.

## Features

- Easy installation of i3 or Sway
- Select additional packages to install
- Option to install a user-preferred display manager
- Designed specifically for Debian 12 and Sid

## Prerequisites

- A Debian 12 (Bookworm) or Sid (Unstable) Linux distribution
- Bash shell
- Internet connection

## Installation

1. Download the script:
   ```bash
   wget https://raw.githubusercontent.com/pegasus-pulse/TWM_Scripts/main/install.sh
   ```

2. Make the script executable:
   ```bash
   chmod +x install.sh
   ```
3. Run the script:
   ```bash
   ./install.sh
   ```
4. Follow the prompts to select your desired window manager, additional packages, and display manager.

#### Other Scripts Included:
* picom.sh: Install/update/remove picom-git or picom (apt).
* neovim.sh: Install/update/remove the newest Neovim package from GitHub.
* discord.sh: Install/update/remove Discord from binary files.
* nerdfonts-installer.sh: Install your preferred Nerd Fonts.
* betterlockscreen.sh: Installs the Betterlockscreen lockscreen package.
* lydm.sh: Can be used to update the Ly Display Manager if you installed it.

## Usage

After the installation is complete, you can start using i3 or Sway by logging out and selecting your preferred window manager from the login screen.

## Contributing

Contributions are welcome! If you have suggestions for improvements or additional features, feel free to open an issue or submit a pull request.

### Acknowledgments

- Thanks to the i3 and Sway communities for their amazing work on these window managers.
- Inspired by various scripts and resources available online.
