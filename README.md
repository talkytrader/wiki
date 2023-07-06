<br>
<br>





<img  alt="logo" src="https://i.imgur.com/Q7iDDyB.jpg" align="right" alt="talky" width="200" height="200">
<div align="left">
<!-- <a href="https://github.com/mraniki/tt/"><img src="https://img.shields.io/github/stars/mraniki/tt?style=for-the-badge"></a>-->
<!-- <a href="https://github.com/mraniki/tt/issues"><img alt="GitHub issues" src="https://img.shields.io/github/issues/mraniki/tt?style=for-the-badge&color=blue"></a> -->
Connect CEX and DEX exchanges across multi messaging platforms.<br>
Place order, inquire your balance and more through plugins.<br>
Easily deploy via Docker on self-hosted platform or Paas.<br>
<br>
<p align="left">
<a href="https://talkytrader.github.io/wiki/"><img src="https://img.shields.io/badge/Wiki-%23000000.svg?style=for-the-badge&logo=wikipedia&logoColor=white"></a><br>
<a href="https://github.com/mraniki/tt/"><img src="https://img.shields.io/badge/github-%23000000.svg?style=for-the-badge&logo=github&logoColor=white"></a>
<a href="https://hub.docker.com/r/mraniki/tt"><img alt="Docker Pulls" src="https://img.shields.io/docker/pulls/mraniki/tt?style=for-the-badge"></a><br>
<a href="https://coindrop.to/mraniki"><img src="https://img.shields.io/badge/tips-000000?style=for-the-badge&logo=buymeacoffee&logoColor=white"></a>
<a href="https://t.me/TTTalkyTraderChat/1"><img alt="Static Badge" src="https://img.shields.io/badge/talky-blue?style=for-the-badge&logo=telegram&logoColor=white"></a> <a href="https://discord.gg/gMNERs5M9"><img alt="Discord" src="https://img.shields.io/discord/1049307055867035648?style=for-the-badge&logo=discord&logoColor=white&label=%20%20&color=blue"></a>
<br><br>
</p>

<img align="right" width="194" alt="screenshot" src="https://github.com/mraniki/tt/assets/8766259/14cb1653-f6b4-44e7-b07c-d930060c7363">

<details close>
<summary>Get started</summary>

<ol>
<li>Create your channel/room and your platform bot
<ul>
<li>Telegram via <a href="https://core.telegram.org/bots/tutorial">Telegram @BotFather</a> and <a href="https://docs.telethon.dev/en/stable/basic/signing-in.html">create an API key</a> </li>
<li>Discord via <a href="https://discord.com/developers/docs/intro">Discord Dev portal</a></li>
<li>Matrix via <a href="https://turt2live.github.io/matrix-bot-sdk/index.html">Matrix.org</a></li>
</ul></li>
<li>Get your
<ul>
<li>DEX wallet address and private key</li>
<li>CEX API Keys supported by <a href="https://github.com/ccxt/ccxt">CCXT</a></li>
</ul></li>
<li>Create your config file settings.toml or use env variables</li>

<details close>
<summary>settings example</summary>
   
<!-- https://github.com/mraniki/tt/blob/4a3e51032802ede12bd20cee12ed4a4396337575/examples/example_settings.toml#L2-->

<script src="https://emgithub.com/embed-v2.js?target=https%3A%2F%2Fgithub.com%2Fmraniki%2Ftt%2Fblob%2Fmain%2Fexamples%2Fexample_settings.toml&style=nnfx-dark&type=code&showBorder=on&showLineNumbers=on&showFullPath=on&showCopy=on"></script>

</details>

<li>Deploy via:
   <ul> 
<li>docker 
          <code>docker pull mraniki/tt:latest</code> or <code>docker pull ghcr.io/mraniki/tt:latest</code></li>
<li>locally 
          <code>git clone https://github.com/mraniki/tt:main</code> && <code>pip install -r requirements.txt</code> </li>
</ul></li>
<li>Start your container or if deployed locally use <code>python3 bot.py</code> to start </li>
<li>Try it now</li>
<a href="https://app.koyeb.com/deploy?type=docker&image=docker.io/mraniki/tt&name=tt-demo"><img src="https://img.shields.io/badge/Deploy%20on%20Koyeb-blue?style=for-the-badge&logo=koyeb"></a>
</ol>

</details>

<br>

<details close>
<summary>Config</summary>

<details close>
<summary>env vars list</summary>

<!-- https://github.com/mraniki/tt/blob/4a3e51032802ede12bd20cee12ed4a4396337575/examples/example.env#L2-->

<script src="https://emgithub.com/embed-v2.js?target=https%3A%2F%2Fgithub.com%2Fmraniki%2Ftt%2Fblob%2F4a3e51032802ede12bd20cee12ed4a4396337575%2Fexamples%2Fexample.env&style=nnfx-dark&type=code&showLineNumbers=on&showFileMeta=on&showFullPath=on&showCopy=on"></script>

</details>

</details>

<br>

<details close>
<summary>Plugins</summary>

<h4>Talky</h4>

<table style="border: 1px solid transparent">
  <tr>
    <td><a href="https://talkytrader.github.io/wiki/"><img src="https://img.shields.io/badge/Wiki-%23000000.svg?style=for-the-badge&logo=wikipedia&logoColor=white"></a><br>
<a href="https://github.com/mraniki/tt/"><img src="https://img.shields.io/badge/github-%23000000.svg?style=for-the-badge&logo=github&logoColor=white"></a>
<a href="https://hub.docker.com/r/mraniki/tt"><img alt="Docker Pulls" src="https://img.shields.io/docker/pulls/mraniki/tt?style=for-the-badge"></a><br>
<a href="https://coindrop.to/mraniki"><img src="https://img.shields.io/badge/tips-000000?style=for-the-badge&logo=buymeacoffee&logoColor=white"></a>
<a href="https://t.me/TTTalkyTraderChat/1"><img alt="Static Badge" src="https://img.shields.io/badge/talky-blue?style=for-the-badge&logo=telegram&logoColor=white"></a> <a href="https://discord.gg/gMNERs5M9"><img alt="Discord" src="https://img.shields.io/discord/1049307055867035648?style=for-the-badge&logo=discord&logoColor=white&label=%20%20&color=blue"></a></td>
    <td align="center"><img width="200" alt="Logo" src="https://i.imgur.com/Q7iDDyB.jpg"></td>
  </tr>
  <tr>
    <td>
   <a href="https://codebeat.co/projects/github-com-mraniki-tt-main"><img alt="codebeat badge" src="https://codebeat.co/badges/94b328d7-777c-4d54-a0d9-ff4625c5e05d" /></a><br>
   <a href="https://talkytrader.github.io/wiki/"><img src="https://github.com/mraniki/tt/actions/workflows/%F0%9F%91%B7Flow.yml/badge.svg"></a><br>
   <a href="https://codecov.io/gh/mraniki/tt"><img src="https://codecov.io/gh/mraniki/tt/branch/main/graph/badge.svg?token=ILJTC0F4K1"></a><br>
   <a href="https://hub.docker.com/r/mraniki/tt"><img src="https://badgen.net/docker/pulls/mraniki/tt"></a><br>
   <a href="https://talkyuniverse.readthedocs.io/projects/iamlistening/"><img src="https://readthedocs.org/projects/talkytrend/badge/?version=latest"></a><br>
    </td>
    <td> <br>Connect CEX and DEX exchanges across multi messaging platforms and plugin support.</td>
     
  </tr>
</table>

<h4>FindMyOrder</h4>

<table style="border: 1px solid transparent">
  <tr>
    <td><a href="https://talkytrader.github.io/wiki/"><img src="https://img.shields.io/badge/Wiki-%23000000.svg?style=for-the-badge&logo=wikipedia&logoColor=white"></a><br>
<a href="https://github.com/mraniki/tt/"><img src="https://img.shields.io/badge/github-%23000000.svg?style=for-the-badge&logo=github&logoColor=white"></a>
<a href="https://hub.docker.com/r/mraniki/tt"><img alt="Docker Pulls" src="https://img.shields.io/docker/pulls/mraniki/tt?style=for-the-badge"></a><br>
<a href="https://coindrop.to/mraniki"><img src="https://img.shields.io/badge/tips-000000?style=for-the-badge&logo=buymeacoffee&logoColor=white"></a>
<a href="https://t.me/TTTalkyTraderChat/1"><img src="https://img.shields.io/badge/talky-blue?style=for-the-badge&logo=telegram&logoColor=white"></a>
<a href="https://discord.gg/gMNERs5M9"><img src="https://img.shields.io/discord/1049307055867035648?style=for-the-badge&logo=discord&logoColor=white&label=%20%20&color=blue"></a></td>
    <td align="center"><img width="200" alt="Logo" src="https://user-images.githubusercontent.com/8766259/233823991-cceaa05a-ff15-4796-a6bb-bcb3ee0d8859.jpg"></td>
  </tr>
  <tr>
    <td>
   <a href="https://pypi.org/project/findmyorder/"><img src="https://badgen.net/badge/icon/findmyorder?icon=pypi&label"></a>
   <a href="https://pypi.org/project/findmyorder/"><img src="https://img.shields.io/pypi/v/findmyorder"></a><br>
   <a href="https://pypi.org/project/findmyorder/"><img src="https://img.shields.io/pypi/dm/findmyorder"></a><br>
   <a href="https://codebeat.co/projects/github-com-mraniki-findmyorder-main"><img src="https://codebeat.co/badges/9b113098-d22d-498d-9c61-eb1e96c1311a"/></a><br>
   <a href="https://talkytrader.github.io/wiki/"><img src="https://github.com/mraniki/findmyorder/actions/workflows/%F0%9F%91%B7Flow.yml/badge.svg"></a><br>
   <a href="https://codecov.io/gh/mraniki/findmyorder"><img src="https://codecov.io/gh/mraniki/findmyorder/branch/main/graph/badge.svg?token=4838MSZNCC"/> </a><br>
<!--      <a href="https://hub.docker.com/r/mraniki/tt"><img src="https://badgen.net/docker/pulls/mraniki/tt"></a><br> -->
   <a href="https://talkyuniverse.readthedocs.io/projects/fyndmyorder/"><img src="https://readthedocs.org/projects/talkytrend/badge/?version=latest"></a><br>
    </td>
    <td> <br>Find My order, a python parsing package to find trading order</td>
     
  </tr>
</table>

<h4>DXSP</h4>

<table style="border: 1px solid transparent">
  <tr>
    <td><a href="https://talkytrader.github.io/wiki/"><img src="https://img.shields.io/badge/Wiki-%23000000.svg?style=for-the-badge&logo=wikipedia&logoColor=white"></a><br>
<a href="https://github.com/mraniki/tt/"><img src="https://img.shields.io/badge/github-%23000000.svg?style=for-the-badge&logo=github&logoColor=white"></a>
<a href="https://hub.docker.com/r/mraniki/tt"><img alt="Docker Pulls" src="https://img.shields.io/docker/pulls/mraniki/tt?style=for-the-badge"></a><br>
<a href="https://coindrop.to/mraniki"><img src="https://img.shields.io/badge/tips-000000?style=for-the-badge&logo=buymeacoffee&logoColor=white"></a>
<a href="https://t.me/TTTalkyTraderChat/1"><img src="https://img.shields.io/badge/talky-blue?style=for-the-badge&logo=telegram&logoColor=white"></a><a href="https://discord.gg/gMNERs5M9"><img src="https://img.shields.io/discord/1049307055867035648?style=for-the-badge&logo=discord&logoColor=white&label=%20%20&color=blue"></a></td>
    <td align="center"><img width="200" alt="Logo" src="https://user-images.githubusercontent.com/8766259/231213427-63ea2752-13d5-4993-aee2-90671b57fc6e.png"></td>
  </tr>
  <tr>
    <td>
   <a href="https://pypi.org/project/dxsp/"><img src="https://badgen.net/badge/icon/dxsp?icon=pypi&label"></a>
   <a href="https://pypi.org/project/dxsp/"><img src="https://img.shields.io/pypi/v/dxsp"></a><br>
   <a href="https://pypi.org/project/dxsp/"><img src="https://img.shields.io/pypi/dm/dxsp"></a><br>
   <a href="https://codebeat.co/projects/github-com-mraniki-dxsp-main"><img src="https://codebeat.co/badges/b1376839-73bc-4b41-bfc1-2fb099f1fc2a"/></a><br>
   <a href="https://talkytrader.github.io/wiki/"><img src="https://github.com/mraniki/dxsp/actions/workflows/%F0%9F%91%B7Flow.yml/badge.svg"></a><br>
   <a href="https://codecov.io/gh/mraniki/dxsp"><img src="https://codecov.io/gh/mraniki/dxsp/branch/main/graph/badge.svg?token=39ED0ZA6IH"/> </a><br>
<!--      <a href="https://hub.docker.com/r/mraniki/tt"><img src="https://badgen.net/docker/pulls/mraniki/tt"></a><br> -->
   <a href="https://talkyuniverse.readthedocs.io/projects/dxsp/"><img src="https://readthedocs.org/projects/dxsp/badge/?version=latest"></a><br>
    </td>
    <td> <br>Swap made easy</td>
     
  </tr>
</table>

<h4>IamListening</h4>

<table style="border: 1px solid transparent">
  <tr>
    <td>
<a href="https://talkytrader.github.io/wiki/"><img src="https://img.shields.io/badge/Wiki-%23000000.svg?style=for-the-badge&logo=wikipedia&logoColor=white"></a><br>
<a href="https://github.com/mraniki/tt/"><img src="https://img.shields.io/badge/github-%23000000.svg?style=for-the-badge&logo=github&logoColor=white"></a>
<a href="https://hub.docker.com/r/mraniki/tt"><img alt="Docker Pulls" src="https://img.shields.io/docker/pulls/mraniki/tt?style=for-the-badge"></a><br>
<a href="https://coindrop.to/mraniki"><img src="https://img.shields.io/badge/tips-000000?style=for-the-badge&logo=buymeacoffee&logoColor=white"></a>
<a href="https://t.me/TTTalkyTraderChat/1"><img alt="Static Badge" src="https://img.shields.io/badge/talky-blue?style=for-the-badge&logo=telegram&logoColor=white"></a> <a href="https://discord.gg/gMNERs5M9"><img alt="Discord" src="https://img.shields.io/discord/1049307055867035648?style=for-the-badge&logo=discord&logoColor=white&label=%20%20&color=blue"></a></td>
    <td align="center"><img width="200" alt="Logo" src="https://user-images.githubusercontent.com/8766259/242846519-f76331f6-8821-49eb-8f1c-06aedd8557be.jpeg"></td>
  </tr>
  <tr>
    <td>
   <a href="https://pypi.org/project/talkytrend/"><img src="https://badgen.net/badge/icon/talkytrend?icon=pypi&label"></a>
   <a href="https://pypi.org/project/talkytrend/"><img src="https://img.shields.io/pypi/v/talkytrend"></a><br>
   <a href="https://pypi.org/project/talkytrend/"><img src="https://img.shields.io/pypi/dm/talkytrend"></a> <br>
   <a href="https://codebeat.co/projects/github-com-mraniki-iamlistening-main"><img src="https://codebeat.co/badges/4085334e-4590-41f6-a70c-69e9a2641c79"/></a><br>
   <a href="https://talkytrader.github.io/wiki/"><img src="https://github.com/mraniki/tt/actions/workflows/%F0%9F%91%B7Flow.yml/badge.svg"></a><br>
   <a href="https://codecov.io/gh/mraniki/iamlistening"> <img src="https://codecov.io/gh/mraniki/iamlistening/branch/main/graph/badge.svg?token=QZ55U6KQFN"/></a>
        <br>
<!--      <a href="https://hub.docker.com/r/mraniki/tt"><img src="https://badgen.net/docker/pulls/mraniki/tt"></a><br> -->
        <a href="https://talkyuniverse.readthedocs.io/projects/iamlistening/"><img src="https://readthedocs.org/projects/talkytrend/badge/?version=latest"></a><br>
    </td>
    <td> <br>Build a chat listener bot</td>
     
  </tr>
</table>

<h4>TalkyTrend</h4>

<table style="border: 1px solid transparent">
  <tr>
    <td><a href="https://talkytrader.github.io/wiki/"><img src="https://img.shields.io/badge/Wiki-%23000000.svg?style=for-the-badge&logo=wikipedia&logoColor=white"></a><br>
<a href="https://github.com/mraniki/tt/"><img src="https://img.shields.io/badge/github-%23000000.svg?style=for-the-badge&logo=github&logoColor=white"></a>
<a href="https://hub.docker.com/r/mraniki/tt"><img src="https://img.shields.io/docker/pulls/mraniki/tt?style=for-the-badge"></a><br>
<a href="https://coindrop.to/mraniki"><img src="https://img.shields.io/badge/tips-000000?style=for-the-badge&logo=buymeacoffee&logoColor=white"></a>
<a href="https://t.me/TTTalkyTraderChat/1"><img src="https://img.shields.io/badge/talky-blue?style=for-the-badge&logo=telegram&logoColor=white"></a>
<a href="https://discord.gg/gMNERs5M9"><img src="https://img.shields.io/discord/1049307055867035648?style=for-the-badge&logo=discord&logoColor=white&label=%20%20&color=blue"></a></td>
    <td align="center"><img width="200" alt="Logo" src="https://user-images.githubusercontent.com/8766259/226854338-e900f69e-d884-4a9a-90b1-b3dde7711b31.png"></td>
  </tr>
  <tr>
    <td>
      <a href="https://pypi.org/project/talkytrend/"><img src="https://badgen.net/badge/icon/talkytrend?icon=pypi&label"></a>
      <a href="https://pypi.org/project/talkytrend/"><img src="https://img.shields.io/pypi/v/talkytrend"></a><br>
      <a href="https://pypi.org/project/talkytrend/"><img src="https://img.shields.io/pypi/dm/talkytrend"></a><br>
      <a href="https://codebeat.co/projects/github-com-mraniki-talkytrend-main"><img src="https://codebeat.co/badges/24c90aab-02d7-4cd1-9ad8-5907e180c9e6"/></a> <br>
      <a href="https://talkytrader.github.io/wiki/"><img src="https://github.com/mraniki/tt/actions/workflows/%F0%9F%91%B7Flow.yml/badge.svg"></a><br>
      <a href="https://codecov.io/gh/mraniki/talkytrend"><img src="https://codecov.io/gh/mraniki/talkytrend/branch/main/graph/badge.svg?token=WAHUEMAJN6"/></a>
        <br>
<!--      <a href="https://hub.docker.com/r/mraniki/tt"><img src="https://badgen.net/docker/pulls/mraniki/tt"></a><br> -->
        <a href="https://talkyuniverse.readthedocs.io/projects/talkytrend/"><img src="https://readthedocs.org/projects/talkytrend/badge/?version=latest"></a><br>
    </td>
    <td> <br>A python package to retrieve asset trend and economic data.</td>
     
  </tr>
</table>

</details>

<br><br>
Built with<br>
<img src="https://img.shields.io/badge/fastapi-black?style=for-the-badge&logo=librariesdotio&logoColor=white">
<img src="https://img.shields.io/badge/uvicorn-black?style=for-the-badge&logo=librariesdotio&logoColor=white"><br>
<img src="https://img.shields.io/badge/apprise-black?style=for-the-badge&logo=librariesdotio&logoColor=white">
<img src="https://img.shields.io/badge/CCXT-black?style=for-the-badge&logo=librariesdotio&logoColor=white"><br>
<img src="https://img.shields.io/badge/findmyorder-black?style=for-the-badge&logo=librariesdotio&logoColor=white">
<img src="https://img.shields.io/badge/dxsp-black?style=for-the-badge&logo=librariesdotio&logoColor=white"><br>
<img src="https://img.shields.io/badge/iamlistening-black?style=for-the-badge&logo=librariesdotio&logoColor=white">
<img src="https://img.shields.io/badge/talkytrend-black?style=for-the-badge&logo=librariesdotio&logoColor=white">
<br><br>

<HR>
⚠️ <em>This is an education tool and should not be considered professional financial investment system nor financial advice.<br>Use a testnet account or USE AT YOUR OWN RISK. Never share your private keys or API secrets.<br>Never use your main account for automatic trade.<br>DYOR.</em>

</div>
