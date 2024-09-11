# RockyRabbitBot
🖱️ clicker for [https://t.me/rocky_rabbit_bot](https://t.me/rocky_rabbit_bot/play?startapp=frId558455838)

## Recommendation before use
# 🔥🔥 Use PYTHON 3.10 🔥🔥

## Features  
| Feature                                                     | Supported  |
|---------------------------------------------------------------|:----------------:|
| Multithreading                                                |        ✅        |
| Proxy binding to session                                      |        ✅        |
| Auto tap                                                      |        ✅        |
| Specify number of taps                                        |        ✅        |
| Auto do tasks                                                 |        ✅        |
| Claim daily combo                                             |        ✅        |
| Claim daily enigma                                            |        ✅        |
| Claim daily rewards                                           |        ✅        |
| Claim daily easter eggs                                       |        ✅        |
| Auto apply boosts                                             |        ✅        |
| Auto upgrade boosts                                           |        ✅        |
| Random sleep time between taps                                |        ✅        |
| Auto upgrade cards                                            |        ✅        |
| Auto init new account                                         |        ✅        |
| Support for tdata / pyrogram .session / telethon .session     |        ✅        |


## [Settings](https://github.com/sizifart/RockyRabbitBot/blob/main/.env-example)
| Settings | Description |
|----------------------------|:-------------------------------------------------------------------------------------------------------------:|
| **API_ID / API_HASH**      | Platform data from which to run the Telegram session (default - android)                                      |
| **AUTO_TAP**               | Automatically tapping (default: True)                                                                         |                                
| **TAP_COUNT**              | How many taps will be clicked (default: [50, 125])                                                            |
| **DELAY_BETWEEN_TAPS**     | Random delay between taps (default: [15, 20])                                                                 |
| **AUTO_BOOST**             | Auto apply boosts (turbo or full energy) (default: True)                                                      |
| **AUTO_UPGRADE_BOOST**     | Auto upgrade (multi-tap, max-energy, passive-income) (default: True)                                          |
| **MAX_ENERGY_BOOST_LVL**   | Max level to upgrade max-energy (default: 5)                                                                  |
| **MULTI_TAP_LVL**          | Max level to upgrade multi-tap (default: 5)                                                                   |
| **PASSIVE_INCOME_LVL**     | Max level to upgrade passive-income (default: 3)                                                              |
| **AUTO_TASK**              | Auto clear tasks (default: True)                                                                              |
| **AUTO_ENIGMA**            | Auto apply daily enigma (default: True)                                                                       |
| **AUTO_SUPERSET**          | Auto apply daily superset (default: True)                                                                     |
| **AUTO_EASTER**            | Auto apply daily easter eggs (default: True)                                                                  |
| **AUTO_UPGRADE_CARDS**     | Auto upgrade cards if possible and claim cards (default: True)                                                |
| **USE_PROXY_FROM_FILE**    | Whether to use a proxy from the bot/config/proxies.txt file (True / False)                                    |


## 📕 Profiles
Possible to create a profile with unique data for each session:
```json
{
  "session1": {
    "proxy": "socks5://yGow3a:uBro3wL@58.195.21.83:9715",
    "headers": {"...": "..."},
    "fingerprint": {"...": "..."}
  },
  "session2": {
    "proxy": "socks5://yGow3a:uBro3wL@58.195.21.83:9715",
    "headers": {"...": "..."},
    "fingerprint": {"...": "..."}
  },
  "...": {}
}
```
> ❕ **Note**:  `session1` и `session2` - are examples of session names.


## Prerequisites
Before you begin, make sure you have the following installed:
- [Python](https://www.python.org/downloads/) **version 3.10**
- Telegram API_ID and API_HASH (you can get them [here](https://my.telegram.org/auth))

## Obtaining API Keys
1. Go to my.telegram.org and log in using your phone number.
2. Select "API development tools" and fill out the form to register a new application.
3. Record the API_ID and API_HASH provided after registering your application in the .env file.

## Auto Install/Run
- Click on RUN.bat to automatically install the required dependencies and run the project

## Menual Install/Run
1. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Please edit the name file .env-example to .env and add your API_ID and API_HASH:
   
## Usage
1. Run the bot:
   ```bash
   python main.py
   ```

## Install/Run into Phone
# Termux Setup 

[Link about python and pip on Termux](https://wiki.termux.com/wiki/Python) that comes with the pkg python

```bash
git clone https://github.com/sizifart/RockyRabbitBot.git
cd RockyRabbitBot
pip3 install -r requirements.txt
chmod +x main.py
```
 
# Telegram Channel

✅ Channel for information and training on Telegram airdrop bots 🔷 Follow us on Telegram : [SIZIFAIRDROP](https://t.me/sizifairdrop)
   
# Discussion

If you have an question or something you can ask in here : [F.Davoodi](https://t.me/sizifart)
