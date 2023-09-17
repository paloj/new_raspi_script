# new_raspi_script

[![Issues Badge](https://img.shields.io/github/issues/paloj/new_raspi_script)](https://github.com/paloj/new_raspi_script/issues)
[![Pull Requests Badge](https://img.shields.io/github/issues-pr/paloj/new_raspi_script)](https://github.com/paloj/new_raspi_script/pulls)
[![Contributors Badge](https://img.shields.io/github/contributors/paloj/new_raspi_script)](https://github.com/paloj/new_raspi_script/graphs/contributors)
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/dwyl/esta/issues)

Welcome to the **new_raspi_script** repository! This bash script is designed to install useful programs and settings on a new Raspberry Pi. It's a handy tool to get your Raspberry Pi up and running with essential programs and configurations.

## Purpose and Functionalities :innocent:

The **new_raspi_script** serves the purpose of setting up a new Raspberry Pi with the following functionalities:

- Installs essential programs:
  - rsync: A utility for efficiently transferring and synchronizing files across computer systems.
  - log2ram: This program reduces wear on your SD card by logging to RAM and only periodically writing to the SD card.
  - fail2ban: A log-parsing application that protects the Raspberry Pi from brute-force attacks.
  
- Sets up useful configurations:
  - Adds useful aliases to your system.
  - Modifies .bashrc to print Raspberry Pi CPU temperature and the last apt update date upon login.

## Installation :sweat_smile:

To install this script on your Raspberry Pi, follow these steps:

1. Clone this repository to your Raspberry Pi.
2. Navigate to the directory containing the script.
3. Make the script executable with the command `chmod +x new_raspi_script`.
4. Run the script with the command `./new_raspi_script`.

## Dependencies :blush:

This script requires the following dependencies:

- rsync
- log2ram
- fail2ban

These dependencies will be installed by the script.

## Usage :smiley:

Once the script is installed and run, it will automatically install the necessary programs and apply the configurations. There is no need for additional input from the user.

## Contributing :grinning:

We welcome contributions from the community! If you'd like to contribute, you can start by forking the repository and making your changes. When you're ready, submit a pull request with your changes.

If you encounter any issues or have suggestions for improvements, please submit an issue on the GitHub page.

For any other inquiries or commercial support, please contact the maintainer via email.

## Authors and Maintainers :laughing:

This script was created and is maintained by the GitHub user paloj. For any questions or support, please contact them directly.

## Support and Donations :upside_down_face:

If you find this script useful and would like to show your support, please consider making a donation. For details on how to do this, please contact the maintainer via email.

Thank you for your interest in **new_raspi_script**! We hope you find it useful for setting up your Raspberry Pi.