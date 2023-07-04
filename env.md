# code-reference-in-readme

This is a sample repo meant to show that you can reference code snippets in markdown files that are rendered on GitHub.

https://github.com/mraniki/tt/blob/main/examples/example.env#L2


<script src="https://emgithub.com/embed-v2.js?target=https%3A%2F%2Fgithub.com%2Fmraniki%2Ftt%2Fblob%2Fmain%2Fexamples%2Fexample.env&style=default&type=markdown&showLineNumbers=on&showCopy=on&fetchFromJsDelivr=on"></script>


## DYNACONF ######
## To load specific env from setting.toml if you have multiple env 
    # ENV_FOR_DYNACONF=DEFAULT
    # TT_LOGLEVEL=INFO

## FASTAPI #######
    # TT_HOST=0.0.0.0
    # TT_PORT=8080
    # TT_WEBHOOK_SECRET = 123abc

## APPRISE #######
    # TT_APPRISE_API_ENDPOINT=""
    # TT_APPRISE_CONFIG=""
    # TT_APPRISE_URL="tgram://TOKEN/CHAT_ID"

## IAMLISTENING ##
    # TT_IAMLISTENING_ENABLED=True
    # TT_BOT_TOKEN=
    # TT_BOT_CHANNEL_ID=
    # TT_TELETHON_API_ID=
    # TT_TELETHON_API_HASH=
    # TT_MATRIX_HOSTNAME=
    # TT_MATRIX_USER=
    # TT_MATRIX_PASS=
