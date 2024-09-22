# ShowAllScreen (SAS)
This script helps you quickly access active `screen` sessions.

## Requirements
- `screen` must be installed on your system.

## Features
- Lists all active screen sessions.
- Allows you to select a session by number.
- Reattaches to the selected session.

## Installation
To install ShowAllScreen, run the following commands:
```bash
sudo wget https://s.id/ShowAllScreen -O /usr/local/bin/SAS && sudo chmod +x /usr/local/bin/SAS
```

On STB:
```bash
sudo wget https://s.id/ShowAllScreen -O /usr/bin/SAS && sudo chmod +x /usr/bin/SAS
```

On Termux:
```bash
wget https://s.id/ShowAllScreen -O $HOME/SAS && chmod +x $HOME/SAS && mv $HOME/SAS /data/data/com.termux/files/usr/bin/
```

## Usage
To use the script, simply run:
```bash
SAS
```

If you want to uninstall **SAS**, simply run:
```bash
sudo rm "/usr/local/bin/SAS"
```
Make sure to replace "/usr/local/bin/SAS" with the appropriate path for your operating system, as it may vary.
