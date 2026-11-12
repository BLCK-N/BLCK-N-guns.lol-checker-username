# BLCK-N guns.lol Username Checker

A command-line tool for checking guns.lol usernames. It uses Selenium and Google Chrome and supports custom username lists, optional result saving, and Discord webhook notifications.

> Please use this project responsibly and follow guns.lol's terms and rules. Avoid excessive requests.

## Creator

Created by **/@ (0v1)**.

- guns.lol: [guns.lol/0.v1](https://guns.lol/0.v1)
- Discord server: [Join the server](https://discord.gg/hvJA7EBRx)
- GitHub: [BLCK-N](https://github.com/BLCK-N)
- Project repository: [BLCK-N-guns.lol-checker-username](https://github.com/BLCK-N/BLCK-N-guns.lol-checker-username)

## Features

- Check randomly generated usernames or entries from `customlist.txt`.
- Optionally filter usernames that require Premium.
- Optionally save available usernames to `unclaimed.txt`.
- Optionally send notifications to a Discord webhook.
- Clean up Chrome and ChromeDriver when the program exits.

## Requirements

- Python 3.8 or newer
- Google Chrome

## Installation

Clone the repository and install its dependencies:

```bash
git clone https://github.com/BLCK-N/BLCK-N-guns.lol-checker-username.git
cd BLCK-N-guns.lol-checker-username
pip install -r requirements.txt
```

On Windows, you can alternatively run `install.bat`. On Linux or macOS, run:

```bash
chmod +x install.sh
./install.sh
```

## Usage

Start the program from the project directory:

```bash
python "blck-n sniper.py"
```

Follow the prompts to choose the username length, checking interval, and optional features. To check a specific list, put one username per line in `customlist.txt`.

## Project files

- `blck-n sniper.py` — main program
- `customlist.txt` — optional usernames to check, one per line
- `unclaimed.txt` — optional output file for available usernames
- `proxies.txt` — optional proxy configuration
- `requirements.txt` — Python dependencies

## License

No license file is currently included in this repository. All rights remain with their respective owners.
