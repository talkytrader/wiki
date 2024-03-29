<br>
<br>

<img  alt="logo" src="https://i.imgur.com/Q7iDDyB.jpg" align="right" alt="talky" width="200" height="200">
<div align="left">


Connect CEX and DEX exchanges across multi messaging platforms.<br>
Place order, inquire your balance and more through plugins.<br>
Easily deploy via Docker on self-hosted platform or Paas.<br>
<br>
<p align="left">

<a href="https://talkytrader.github.io/wiki/"><img src="https://img.shields.io/badge/Wiki-%23000000.svg?style=for-the-badge&logo=wikipedia&logoColor=white"></a>
<a href="https://github.com/mraniki/tt/"><img src="https://img.shields.io/badge/github-%23000000.svg?style=for-the-badge&logo=github&logoColor=white"></a>
<a href="https://coindrop.to/mraniki"><img src="https://img.shields.io/badge/tips-000000?style=for-the-badge&logo=buymeacoffee&logoColor=white"></a><br>
<a href="https://hub.docker.com/r/mraniki/tt"><img src="https://img.shields.io/docker/pulls/mraniki/tt?style=for-the-badge"></a>
<a href="https://t.me/TTTalkyTraderChat/1"><img src="https://img.shields.io/badge/talky-blue?style=for-the-badge&logo=telegram&logoColor=white"></a><br>
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
<li><a href="https://support.metamask.io/hc/en-us/articles/360015289632-How-to-export-an-account-s-private-key">DEX wallet address and private key</a></li>
<li><a href="https://github.com/ccxt/ccxt">CEX API Keys</a></li>
</ul></li>
<li>Create your config file settings.toml or use env variables</li>

<details close>
<summary>settings example</summary>
   

<script src="https://emgithub.com/embed-v2.js?target=https%3A%2F%2Fgithub.com%2Fmraniki%2Ftt%2Fblob%2Fmain%2Fexamples%2Fexample_settings.toml&style=nnfx-dark&type=code&showBorder=on&showLineNumbers=on&showFullPath=on&showCopy=on"></script>

</details>

<li>Deploy via:
   <ul> 
<li>docker 
          <code>docker pull mraniki/tt:latest</code> or <code>docker pull ghcr.io/mraniki/tt:latest</code></li>
<li>locally 
          <code>git clone https://github.com/mraniki/tt:main</code> && <code>pip install -r .requirements/requirements.txt</code> </li>
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


<script src="https://emgithub.com/embed-v2.js?target=https%3A%2F%2Fgithub.com%2Fmraniki%2Ftt%2Fblob%2Fmain%2Ftt%2Ftalky_settings.toml&style=nnfx-dark&type=code&showBorder=on&showLineNumbers=on&showFileMeta=on&showFullPath=on&showCopy=on"></script>

</details>

</details>

<br>

<details close>
<summary>Plugins</summary>

<h4>Talky</h4>
<br>
<a href="https://talky.readthedocs.io/"><img src="https://img.shields.io/badge/Documentation-000000?style=for-the-badge&logo=readthedocs&logoColor=white"></a><br>

<table style="border: 1px solid transparent">

  <tr>
    <td>
<img src="https://img.shields.io/github/v/release/mraniki/tt?style=for-the-badge"><br>
<a href="https://talkytrader.github.io/wiki/"><img src="https://img.shields.io/github/actions/workflow/status/mraniki/tt/%F0%9F%91%B7Flow.yml?style=for-the-badge&logo=GitHub&logoColor=white"></a><br>
<a href="https://talky.readthedocs.io"><img src="https://readthedocs.org/projects/talky/badge/?version=latest&style=for-the-badge"></a><br>
<a href="https://codebeat.co/projects/github-com-mraniki-tt-main"><img alt="codebeat badge" src="https://codebeat.co/badges/94b328d7-777c-4d54-a0d9-ff4625c5e05d" /></a><br>
<a href="https://codecov.io/gh/mraniki/tt" ><img src="https://codecov.io/gh/mraniki/tt/branch/dev/graph/badge.svg?token=ILJTC0F4K1"/> </a>
    </td>
    <td align="center"> 
       Connect CEX and DEX exchanges <br>
       across multi messaging platforms <br>
       with plugin support.
    </td>
  </tr>
</table>
<br>

<h4>FindMyOrder</h4>
<a href="https://talky.readthedocs.io/projects/findmyorder/en/latest/"><img src="https://img.shields.io/badge/Documentation-000000?style=for-the-badge&logo=readthedocs&logoColor=white"></a><br>
<table style="border: 1px solid transparent">
  <tr>
    <td>
             <a href="https://pypi.org/project/findmyorder/"><img src="https://img.shields.io/pypi/v/findmyorder?style=for-the-badge&logo=PyPI&logoColor=white"></a><br>
      <a href="https://pypi.org/project/findmyorder/"><img src="https://img.shields.io/pypi/dm/findmyorder?style=for-the-badge&logo=PyPI&logoColor=white&label=pypi&labelColor=grey"></a><br>
      <a href="https://github.com/mraniki/findmyorder"><img src="https://img.shields.io/github/actions/workflow/status/mraniki/findmyorder/%F0%9F%91%B7Flow.yml?style=for-the-badge&logo=GitHub&logoColor=white"></a><br>
   <a href="https://talkyuniverse.readthedocs.io/projects/fyndmyorder/"><img src="https://readthedocs.org/projects/talkytrend/badge/?version=latest&style=for-the-badge"></a><br>
   <a href="https://codebeat.co/projects/github-com-mraniki-findmyorder-main"><img src="https://codebeat.co/badges/9b113098-d22d-498d-9c61-eb1e96c1311a"/></a><br>
   <a href="https://codecov.io/gh/mraniki/findmyorder"><img src="https://codecov.io/gh/mraniki/findmyorder/branch/main/graph/badge.svg?token=4838MSZNCC"/> </a><br>
    </td>
     <td align="left"> 
        Find My order,<br>
       a parsing package to find trading order
     </td>
  </tr>
</table>


<h4>DXSP</h4>
<br>
<a href="https://talky.readthedocs.io/projects/dxsp/en/latest/"><img src="https://img.shields.io/badge/Documentation-000000?style=for-the-badge&logo=readthedocs&logoColor=white"></a><br>
<table style="border: 1px solid transparent">

  <tr>
    <td>
      <a href="https://pypi.org/project/dxsp/"><img src="https://img.shields.io/pypi/v/dxsp?style=for-the-badge&logo=PyPI&logoColor=white"></a><br>
      <a href="https://pypi.org/project/dxsp/"><img src="https://img.shields.io/pypi/dm/dxsp?style=for-the-badge&logo=PyPI&logoColor=white&label=pypi&labelColor=grey"></a><br>
      <a href="https://github.com/mraniki/dxsp/"><img src="https://img.shields.io/github/actions/workflow/status/mraniki/dxsp/%F0%9F%91%B7Flow.yml?style=for-the-badge&logo=GitHub&logoColor=white"></a><br>
   <a href="https://talkyuniverse.readthedocs.io/projects/dxsp/"><img src="https://readthedocs.org/projects/dxsp/badge/?version=latest&style=for-the-badge"></a><br>
   <a href="https://codebeat.co/projects/github-com-mraniki-dxsp-main"><img src="https://codebeat.co/badges/b1376839-73bc-4b41-bfc1-2fb099f1fc2a"/></a><br>
   <a href="https://codecov.io/gh/mraniki/dxsp"><img src="https://codecov.io/gh/mraniki/dxsp/branch/main/graph/badge.svg?token=39ED0ZA6IH"/> </a><br>
    </td>
    <td align="left"> 
Swap made easy<br>
Trade on any blockchains with uniswap based router or 0x protocol.
    </td>
     
  </tr>
</table>

<h4>IamListening</h4>
<br>
<a href="https://talky.readthedocs.io/projects/iamlistening/en/latest/"><img src="https://img.shields.io/badge/Documentation-000000?style=for-the-badge&logo=readthedocs&logoColor=white"></a><br>
<table style="border: 1px solid transparent">

  <tr>
    <td>
      <a href="https://pypi.org/project/iamlistening/"><img src="https://img.shields.io/pypi/v/iamlistening?style=for-the-badge&logo=PyPI&logoColor=white"></a><br>
      <a href="https://pypi.org/project/iamlistening/"><img src="https://img.shields.io/pypi/dm/iamlistening?style=for-the-badge&logo=PyPI&logoColor=white&label=pypi&labelColor=grey"></a><br>
      <a href="https://github.com/mraniki/iamlistening/"><img src="https://img.shields.io/github/actions/workflow/status/mraniki/iamlistening/%F0%9F%91%B7Flow.yml?style=for-the-badge&logo=GitHub&logoColor=white"></a><br>
   <a href="https://talky.readthedocs.io/"><img src="https://readthedocs.org/projects/iamlistening/badge/?version=latest&style=for-the-badge"></a><br>
   <a href="https://codebeat.co/projects/github-com-mraniki-iamlistening-main"><img src="https://codebeat.co/badges/4085334e-4590-41f6-a70c-69e9a2641c79"/></a><br>
   <a href="https://codecov.io/gh/mraniki/iamlistening"> <img src="https://codecov.io/gh/mraniki/iamlistening/branch/main/graph/badge.svg?token=QZ55U6KQFN"/></a><br>
    </td>
    <td align="left"> 
       A python package to listen to messaging platforms,<br>
       such as discord, telegram and matrix 
    </td>
     
  </tr>
</table>

<h4>TalkyTrend</h4>
<br>
<a href="https://talky.readthedocs.io/projects/talkytrend/en/latest/"><img src="https://img.shields.io/badge/Documentation-000000?style=for-the-badge&logo=readthedocs&logoColor=white"></a><br>
<table style="border: 1px solid transparent">
  <tr>
    <td>
      <a href="https://pypi.org/project/talkytrend/"><img src="https://img.shields.io/pypi/v/talkytrend?style=for-the-badge&logo=PyPI&logoColor=white"></a><br>
      <a href="https://pypi.org/project/talkytrend/"><img src="https://img.shields.io/pypi/dm/talkytrend?style=for-the-badge&logo=PyPI&logoColor=white"></a><br>
      <a href="https://github.com/mraniki/talkytrend/"><img src="https://img.shields.io/github/actions/workflow/status/mraniki/talkytrend/%F0%9F%91%B7Flow.yml?style=for-the-badge&logo=GitHub&logoColor=white"></a><br>
      <a href="https://talkyuniverse.readthedocs.io/projects/talkytrend/"><img src="https://readthedocs.org/projects/talkytrend/badge/?version=latest&style=for-the-badge"></a><br>
      <a href="https://codebeat.co/projects/github-com-mraniki-talkytrend-main"><img src="https://codebeat.co/badges/24c90aab-02d7-4cd1-9ad8-5907e180c9e6"/></a> <br>
      <a href="https://codecov.io/gh/mraniki/talkytrend"><img src="https://codecov.io/gh/mraniki/talkytrend/branch/main/graph/badge.svg?token=WAHUEMAJN6"/></a><br>
    </td>
    <td align="left"> 
Retrieve asset trend and economic data.<br>
Trading view connectivity with signal<br>
News connectivity<br>
       FOMC reminder<br>
    </td>
  </tr>
</table>


<h4>MyLLM</h4>
<br>
<a href="https://talky.readthedocs.io/projects/myllm/en/latest/"><img src="https://img.shields.io/badge/Documentation-000000?style=for-the-badge&logo=readthedocs&logoColor=white"></a><br>

<table style="border: 1px solid transparent">
  <tr>
    <td>
      <a href="https://pypi.org/project/myllm/"><img src="https://img.shields.io/pypi/v/myllm?style=for-the-badge&logo=PyPI&logoColor=white"></a><br>
      <a href="https://pypi.org/project/myllm/"><img src="https://img.shields.io/pypi/dm/myllm?style=for-the-badge&logo=PyPI&logoColor=white"></a><br>
      <a href="https://github.com/mraniki/myllm/"><img src="https://img.shields.io/github/actions/workflow/status/mraniki/myllm/%F0%9F%91%B7Flow.yml?style=for-the-badge&logo=GitHub&logoColor=white"></a><br>
      <a href="https://talky.readthedocs.io/projects/myllm/"><img src="https://readthedocs.org/projects/myllm/badge/?version=latest&style=for-the-badge"></a><br>
      <a href="https://codebeat.co/projects/github-com-mraniki-myllm-main"><img src="https://codebeat.co/badges/0567b9d9-3cbb-4263-80ec-8ac8043332ea"/></a> <br>
      <a href="https://codecov.io/gh/mraniki/myllm"><img src="https://codecov.io/gh/mraniki/myllm/branch/main/graph/badge.svg?token=WAHUEMAJN6"/></a><br>
    </td>
    <td align="left"> 
Interact with LLM in simple way.<br>
  </td>   
  </tr>
</table>


</details>

<br><br>
<img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54"><br>
<a href="https://github.com/dynaconf/dynaconf"><img src="https://img.shields.io/badge/⚙️dynaconf-005571?style=for-the-badge&logo=settings&logoColor=ffdd54"></a>
<a href="https://github.com/caronc/apprise"><img src="https://img.shields.io/badge/💬apprise-005571?style=for-the-badge&logo=none"></a>
<a href="https://fastapi.tiangolo.com"><img src="https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi"></a>
<a href="https://www.uvicorn.org"><img src="https://img.shields.io/badge/uvicorn-005571?style=for-the-badge&logo=fastapi"></a><br>
<a href="https://github.com/ccxt/ccxt"><img src="https://img.shields.io/badge/CCXT-black?style=for-the-badge&logo=librariesdotio&logoColor=white"></a>
<a href="https://github.com/mraniki/dxsp"><img src="https://img.shields.io/badge/dxsp-black?style=for-the-badge&logo=librariesdotio&logoColor=white"></a>
<a href="https://github.com/mraniki/findmyorder"><img src="https://img.shields.io/badge/findmyorder-black?style=for-the-badge&logo=librariesdotio&logoColor=white"></a>
<a href="https://github.com/mraniki/iamlistening"><img src="https://img.shields.io/badge/iamlistening-black?style=for-the-badge&logo=librariesdotio&logoColor=white"></a><br>
<a href="https://github.com/mraniki/talkytrend"><img src="https://img.shields.io/badge/talkytrend-black?style=for-the-badge&logo=librariesdotio&logoColor=white"></a>
<a href="https://github.com/tarsil/asyncz"><img src="https://img.shields.io/badge/asyncz-black?style=for-the-badge&logo=librariesdotio&logoColor=white"></a>
<a href="https://github.com/mraniki/MyLLM"><img src="https://img.shields.io/badge/myLLM-black?style=for-the-badge&logo=librariesdotio&logoColor=white"></a>
<br><br>

<HR>
⚠️ <em>This is an education tool and should not be considered professional financial investment system nor financial advice.<br>Use a testnet account or USE AT YOUR OWN RISK. Never share your private keys or API secrets.<br>Never use your main account for automatic trade.<br>DYOR.</em>

</div>
