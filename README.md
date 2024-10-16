
# Software for Agent301 telegram Bot

## Requirements
- Python 3.11 (you can install it [here](https://www.python.org/downloads/release/python-3110/))
- Telegram API_ID and API_HASH (you can get them [here](https://my.telegram.org/auth?to=apps))



1. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

2. Get your API_ID and API_HASH:
   - Go to [my.telegram.org](https://my.telegram.org/auth?to=apps)
   - Sign in with your Telegram account
   - Create a new application to get your API_ID and API_HASH

3. Configure the application:
   - Open `config.py` and add your `API_ID` and `API_HASH`:
     ```python
     API_ID = your_api_id
     API_HASH = 'your_api_hash'
     ```

   - If you want to use a proxy, set `USE_PROXY` in `config.py` to `True`, otherwise set it to `False`:
     ```python
     USE_PROXY = True  # or False
     ```

   - If `USE_PROXY` is `True`, open `proxy.txt` and fill it out using the example provided. Ensure there are no extra lines in the file.
   Proxy format : ip:port:login:password session_name, session name is which use this proxy (WITHOUT .session, only session name)
   ```txt
   192.168.1.1:1234:username:password session1
   192.168.1.2:2934:username:password session2
   192.168.1.3:3834:username:password session3
   192.168.5.1:2884:username:password session4
   ```
   And don't forget set proxy type in `config.py`
   ```python
   PROXY_TYPE = "socks5" # or http
   ```
   You can add your referral code in config.pyyou can take it from your referral link, (it comes after startapp=)
   ```python
   REF_CODE = 'onetime707649803'
   ```

   delay between task executions
   ```python
   TASK_SLEEP = [30,60] #[min,max]
   ```
  
   delay between cycles
   ```python
   BIG_SLEEP = [5*60*60,8*60*60]
   ```
5. IMPORTANT Create a `sessions` folder



## Usage

1. Run the bot:
   ```bash
   python main.py
   ```

2. The software will work with all accounts using the single `API_ID` and `API_HASH`. No need to change them for each account.

## Important Notes

- **Python Version:** The software runs on Python 3.11. Using a different version may cause errors.
- DONT USE MAIN ACCOUNT BECAUSE THERE IS ALWAYS A CHANCE TO GET BANNED IN TELEGRAM


---

DONATIONS 
```txt
ton   : UQCLxqnBscAH1i8WNU2qfqXrAKCd5AoNgbuNrvZHTZOLI3Yg

sol   : BKmvLTyW29Pkb1yixJrUh6q6JgCkyqY5VGAN5DwgLatK

ltc   : ltc1q4jxmwt2hrwz05jgplaxsx7ytdmyd06n9w43qtx

btc   : bc1qfhy5de2xmewzlyd8gct8e8lxxwkm33u359sxpe

evm   : 0xffD503AD80C9486D8588fD0DE2E129F2F0E1d618

trc20 : TN6qKhsbjB1WaetixdRigNrmUw1MCqAyh3

dash  : Xu4VUgxQTKk5URkbgMiZv6uLzJpHR4NH6y

zec   : t1aFA4poLSA6psJ1pbsK63MeXKQ6ECkqz5M
```

Don't forget to follow our [Telegram channel](https://t.me/petyasofts) for updates.



