# Tomarketod

Auto Claim for tomarket Telegram Bot

# Table of Contents

- [Tomarketod](#tomarketod)
- [Table of Contents](#table-of-contents)
- [Warning](#warning)
- [Features](#features)
- [Register](#register)
- [How to Use](#how-to-use)
  - [About Config](#about-config)
  - [About Proxy](#about-proxy)
  - [Windows](#windows)
  - [Linux](#linux)
  - [Termux](#termux)
- [How to Get Data](#how-to-get-data)
- [Run for 24/7](#run-for-247)
- [Discussion](#discussion)
- [Support My Work](#support-my-work)
- [Thank you \< 3](#thank-you--3)

# Warning

All Risks are borne by the user!

# Features

- [x] Auto Claim
- [x] Multi Account Support
- [x] Auto Play Game
- [x] Proxy Support

# Register

Click the following url to register : https://t.me/Tomarket_ai_bot/app?startapp=0000009G

# How to Use

## About Config

| Name            | Description                                                                                |
| --------------- | ------------------------------------------------------------------------------------------ |
| interval        | downtime between account                                                                   |
| play_game       | value must bool (true/false) set true for enable auto play game after claim                |
| game_point      | low : minimum earn from play game <br>high : maximum earn from play game                   |
| additional_time | min : minimum addition time for next claim <br> max : maximum addition time for next claim |

## About Proxy

Register on this site to get free proxy : [Here](https://www.webshare.io/?referral_code=dwj0m9cdi4mp)

You can add your proxy list in `proxies.txt` and proxy format is like example below :

Format :

```
http://host:port
http://user:pass@host:port
```

Example :

```
http://127.0.0.1:6969
http://user:pass@127.0.0.1:6969
socks5://127.0.0.1:6969
socks5://user:pass@127.0.0.1:6969
```

## Windows 

1. Make sure you computer was installed python and git.
   
   python site : [https://python.org](https://python.org)
   
   git site : [https://git-scm.com/](https://git-scm.com/)

2. Clone this repository
   ```shell
   git clone https://github.com/akasakaid/tomarketod.git
   ```

3. goto tomarketod directory
   ```
   cd tomarketod
   ```

4. install the require library
   ```
   python -m pip install -r requirements.txt
   ```

5. Edit `data.txt`, input you data token in `data.txt`, find you token in [How to Get Data](#how-to-get-data). One line for one data account, if you want add you second account add in new line!

6. execute the main program 
   ```
   python bot.py
   ```

## Linux

1. Make sure you computer was installed python and git.
   
   python
   ```shell
   sudo apt install python3 python3-pip
   ```
   git
   ```shell
   sudo apt install git
   ```

2. Clone this repository
   
   ```shell
   git clone https://github.com/akasakaid/tomarketod.git
   ```

3. goto tomarketod directory

   ```shell
   cd tomarketod
   ```

4. Install the require library
   
   ```
   python3 -m pip install -r requirements.txt
   ```

5. Edit `data.txt`, input you data token in `data.txt`, find you token in [How to Get Data](#how-to-get-data). One line for one data account, if you want add you second account add in new line!

6. execute the main program 
   ```
   python bot.py
   ```

## Termux

1. Make sure you termux was installed python and git.
   
   python
   ```
   pkg install python
   ```

   git
   ```
   pkg install git
   ```

2. Clone this repository
   ```shell
   git clone https://github.com/akasakaid/tomarketod.git
   ```

3. goto tomarketod directory
   ```
   cd tomarketod
   ```

4. install the require library
   ```
   python -m pip install -r requirements.txt
   ```

5. Edit `data.txt`, input you data token in `data.txt`, find you token in [How to Get Data](#how-to-get-data). One line for one data account, if you want add you second account add in new line!

You can edit the data.txt with `nano` / `vim` / `Visual Studio Code` 

6. execute the main program 
   ```
   python bot.py
   ```

# How to Get Data

How to enable dev tool on teelgram PC : [https://youtu.be/NYxHmck_GjE](https://youtu.be/NYxHmck_GjE)

Watch the following video to get data [https://youtu.be/fdbdt-fEoVg](https://youtu.be/fdbdt-fEoVg)

Javascript code for getting query (user= / query=)

```javascript
copy(decodeURIComponent(sessionStorage.SourceTarget).split('#tgWebAppData=')[1].split('&tgWebAppVersion=')[0]);console.log('data copied !\npaste ctrl + v')
```

# Run for 24/7 

You can run the script bot for 24/7 using vps / rdp. You can use `screen` application in vps linux to running the script bot in background process

# Discussion

If you have an question or something you can ask in here : [@sdsproject_chat](https://t.me/sdsproject_chat)

# Support My Work

To support me you can buy me a coffee via website in below

- Send IDR directly via QRIS : [https://s.id/nusanqr](https://s.id/nusanqr)
- [Indonesian] https://trakteer.id/fawwazthoerif/tip
- [Global] https://sociabuzz.com/fawwazthoerif/tribe

# Thank you < 3