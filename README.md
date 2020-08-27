# KeepMeBot
Keep me running bot

## Support platform
* docker hub

## run and deployment
It's strongly recommend to use docker to run this bot 
because we're about to running some system commands from untrusted sources.

```shell script
git clone https://github.com/BennyThink/KeepMeBot
cd KeepMeBot
# change your token here, you may also add other environment variables such as `http_proxy`
vim config.env
docker-compose up -d

```

## License
MIT