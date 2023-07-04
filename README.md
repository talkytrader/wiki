# 🗿 TalkyUniverse
<img src="https://i.imgur.com/Q7iDDyB.jpg" align="right"
     alt="talky" width="400" height="400">

ℹ️ Information is available on the different talky modules

🐛 If you find an issue you'd like to report, or otherwise have feedback, please add a new Issue <a href="https://github.com/mraniki/tt/issues"><img src="https://badgen.net/github/open-issues/mraniki/tt" /></a>

🧑‍💻 If you'd like to contribute, please start by creating or commenting on an <a href="https://github.com/mraniki/tt/issues">issue</a> so we can track the work. 

💬 Share your feedback and connect on <a href="https://discord.gg/vegJQGrRRa"><img src="https://badgen.net/badge/icon/discord/purple?icon=discord&label" /></a> <a href="https://t.me/TTTalkyTraderChat/1"><img src="https://badgen.net/badge/icon/telegram?icon=telegram&label" /></a>

🍩 If you like it, feel free to <a href="https://coindrop.to/mraniki"><img src="https://badgen.net/badge/icon/coindrop/6F4E37?icon=buymeacoffee&label"/></a>

⚠️ This is an education tool and should not be considered professional financial investment system nor financial advice. Use a testnet account or USE AT YOUR OWN RISK. For DEX, Never share your private keys. NEVER use your main account for automatic trade

<details close>
<summary><h2>Get started</h2></summary>
<ol>

<li>Create your channel/room and your platform bot</li>

    - Telegram via [Telegram @BotFather](https://core.telegram.org/bots/tutorial) and [create an API key](https://docs.telethon.dev/en/stable/basic/signing-in.html) 
    - Discord via [Discord Dev portal](https://discord.com/developers/docs/intro)
    - Matrix via [Matrix.org](https://turt2live.github.io/matrix-bot-sdk/index.html)

<li>Get your 
     
    - DEX wallet address and private key
    - CEX API Keys supported by [CCXT](https://github.com/ccxt/ccxt) or

</li>

<li>Create your config [/app/settings.toml](src/example_settings.toml) or prepare your env variable</li>

<li>Deploy via:
    
     - docker 
          `docker pull mraniki/tt:latest` or `docker pull ghcr.io/mraniki/tt:latest`
     - locally 
          `git clone https://github.com/mraniki/tt:main` && `pip install -r requirements.txt` 
</li>

<li>Start your container or if deployed locally use `python3 bot.py` to start</li>

<li>Documentation available on <a href="https://talkytrader.github.io/wiki">wiki</a>

</ol>
</details>

<h2>Try it</h2>

[![Deploy to Koyeb](https://www.koyeb.com/static/images/deploy/button.svg)](https://app.koyeb.com/deploy?type=docker&image=docker.io/mraniki/tt&name=tt-demo)


<h2>Config</h2>

 
```Dotenv
     https://github.com/mraniki/tt/blob/dc394d42d18e3718e0062f32cdfccb006b9c716a/examples/example.env
```

```Dotenv:env.md
```


<details>
<summary><h2>Modules</h2></summary>

<h3>Talky</h3>
  
Submit trading order to CEX & DEX with multi messaging platform and plugin support

<h3>FindMyOrder</h3>

Find that order

<h3>DXSP</h3>

Swap made easy
<h3>IamListening</h3>

Build a chat listener bot

<h3>TalkyTredn</h3>

  Get the trend

</details>




