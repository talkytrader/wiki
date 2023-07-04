# TalkyUniverse
[![Logo](https://i.imgur.com/Q7iDDyB.jpg)](https://github.com/mraniki/tt)

ℹ️ Information is available on the different talky module on the sidebar

🐛 If you find an issue you'd like to report, or otherwise have feedback, please file a new Issue <a href="https://github.com/mraniki/tt/issues"><img src="https://badgen.net/github/open-issues/mraniki/tt" /></a>

🧑‍💻 If you'd like to contribute, please start by filing or commenting on an Issue so we can track the work. 

💬 Share your feedback and connect on <a href="https://discord.gg/vegJQGrRRa"><img src="https://badgen.net/badge/icon/discord/purple?icon=discord&label" /></a> <a href="https://t.me/TTTalkyTraderChat/1"><img src="https://badgen.net/badge/icon/telegram?icon=telegram&label" /></a>

🍩 If you like it, feel free to <a href="https://coindrop.to/mraniki"><img src="https://badgen.net/badge/icon/coindrop/6F4E37?icon=buymeacoffee&label"/></a>

⚠️ This is an education tool and should not be considered professional financial investment system nor financial advice. Use a testnet account or USE AT YOUR OWN RISK. For DEX, Never share your private keys. NEVER use your main account for automatic trade

## Get started
<details>
  <summary><h2>Quick Start</h2> </summary>
  1) Create your channel/room and your platform bot
  
      - Telegram via [Telegram @BotFather](https://core.telegram.org/bots/tutorial) and [create an API key](https://docs.telethon.dev/en/stable/basic/signing-in.html) 
      - Discord via [Discord Dev portal](https://discord.com/developers/docs/intro)
      - Matrix via [Matrix.org](https://turt2live.github.io/matrix-bot-sdk/index.html)
  
  2) Get your
  
      - CEX API Keys supported by [CCXT](https://github.com/ccxt/ccxt) or
      - DEX wallet address and private key
  
  3) Create your config [/app/settings.toml](https://github.com/mraniki/tt/blob/main/examples/example_settings.toml) or prepare your env variable
  
  4) Deploy via:
      - docker `docker pull mraniki/tt:latest` or `docker pull ghcr.io/mraniki/tt:latest`
      - locally `git clone https://github.com/mraniki/tt:main` && `pip install -r requirements.txt`
  
  5) Start your container or if deployed locally use `python3 bot.py` to start

</details>

<details>
  <summary><h2>Module</h2> </summary>



### Talky
  Submit trading order to CEX & DEX with multi messaging platform and plugin support

### FindMyOrder
find that order

### DXSP
Swap made easy

### IamListening
Build a chat listener bot

### TalkyTrend
  Get the trend

</details>



<details>
  <summary><h2>Env Variables</h2> </summary>


<script src="https://emgithub.com/embed-v2.js?target=https%3A%2F%2Fgithub.com%2Fmraniki%2Ftt%2Fblob%2Fmain%2Fexamples%2Fexample.env&style=default&type=markdown&showLineNumbers=on&showCopy=on&fetchFromJsDelivr=on"></script>


</details>
