# ALX DEBUG notes

https://scheduler.apps.okd.skyteams.info/webhook/openai/v1

https://api.openai.com/v1

ghcr.io/open-webui/open-webui
harbor.apps.okd.skyteams.info/localai/open-webui:1.0.0

## aiohttp proxy
Contrary to the requests library, it won’t read environment variables by default. But you can do so by passing trust_env=True into aiohttp.ClientSession constructor.: