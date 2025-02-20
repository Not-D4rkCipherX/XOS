# XOS BOT
XOS BOT

- Register Here : [XOS](X.ink/TLK7VU)

## Features

  - Auto Get Account Information
  - Auto Run With [Monosans](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/all.txt) Proxy - Choose 1
  - Auto Run With Private Proxy - Choose 2
  - Auto Run Without Proxy - Choose 3
  - Auto Claim Daily Check-In
  - Multi Accounts

## Requiremnets

- Make sure you have Python3.9 or higher installed and pip.

## Instalation

1. **Clone The Repositories:**
   ```bash
   git clone https://github.com/Not-D4rkCipherX/XOS.git
   ```
   ```bash
   cd XOS
   ```
   
2. **Install Requirements:**
   ```bash
   pip install -r requirements.txt #or pip3 install -r requirements.txt
   ```

## Configuration
 ```bash
nano accounts.txt
```
***Make sure `accounts.txt` contains data that matches the format expected by the script. Here are examples of file formats:
  ```bash
    your_private_key_1
    your_private_key_2
  ```
## Proxy
```bash
nano proxy.txt
```
- **Make sure `proxy.txt` contains data that matches the format expected by the script. Here are examples of file formats:
  ```bash
    ip:port # Default Protcol HTTP.
    protocol://ip:port
    protocol://user:pass@ip:port
  ```

## Run The BOT :

```bash
python bot.py #or python3 bot.py
```
