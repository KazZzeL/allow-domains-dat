# allow-domains-dat
Сборщик геофайлов для [Xray](https://github.com/XTLS/Xray-core) на основе списков `ITDog` [itdoginfo/allow-domains](https://github.com/itdoginfo/allow-domains)  
Файлы генерируются в течение часа после обновления списков

Для сборки используются:
- **geosite**: [v2fly/domain-list-community](https://github.com/v2fly/domain-list-community)
- **geoip**: [v2fly/geoip](https://github.com/v2fly/geoip)

Также благодарность за вдохновение [unidcml](https://github.com/unidcml)

***!!! Для мобильных устройств iOS рекомендуется использование специальных, а не универсальных Geosite и Geoip***

## Ссылки для скачивания
### Универсальные Geosite и Geoip

- **allow-domains.dat** (содержит категории `anime`, `block`, `geoblock`, `hodca`, `news`, `porn`, `russia-inside`, `russia-outside`, `ukraine-inside`, `cloudflare`, `cloudfront`, `digitalocean`, `discord`, `google-ai`, `google-play`, `hdrezka`, `hetzner`, `meta`, `ovh`, `roblox`, `telegram`, `tiktok`, `twitter`, `youtube`): 
  - [https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/allow-domains.dat](https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/allow-domains.dat)
- **allow-categories.dat** (содержит категории доменов `anime`, `block`, `geoblock`, `hodca`, `news`, `porn`): 
  - [https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/allow-categories.dat](https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/allow-categories.dat)
- **allow-countries.dat** (содержит категории доменов `russia-inside`, `russia-outside`, `ukraine-inside`): 
  - [https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/allow-countries.dat](https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/allow-countries.dat)
- **allow-services** (содержит категории доменов `cloudflare`, `cloudfront`, `digitalocean`, `discord`, `google-ai`, `google-play`, `hdrezka`, `hetzner`, `meta`, `ovh`, `roblox`, `telegram`, `tiktok`, `twitter`, `youtube`)
  - [https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/allow-services.dat](https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/allow-services.dat)
- **allow-subnets.dat** (содержит `IPv4` и `IPv6` подсети для `cloudflare`, `cloudfront`, `digitalocean`, `discord`, `hetzner`, `meta`, `ovh`, `roblox`, `telegram`, `twitter`):
  - [https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/allow-subnets.dat](https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/allow-subnets.dat)


### Geosite по признаку, откуда будет совершаться доступ

- **russia-inside.dat** (содержит категорию `list`): 
  - [https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/russia-inside.dat](https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/russia-inside.dat)
- **russia-outside.dat** (содержит категорию `list`): 
  - [https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/russia-outside.dat](https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/russia-outside.dat)
- **ukraine-inside.dat** (содержит категорию `list`): 
  - [https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/ukraine-inside.dat](https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/ukraine-inside.dat)


### Geosite по признаку, к какой категории ресурсов будет совершаться доступ

- **anime-domains.dat** (содержит категорию `list`): 
  - [https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/anime-domains.dat](https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/anime-domains.dat)
- **block-domains.dat** (содержит категорию `list`): 
  - [https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/block-domains.dat](https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/block-domains.dat)
- **geoblock-domains.dat** (содержит категорию `list`): 
  - [https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/geoblock-domains.dat](https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/geoblock-domains.dat)
- **hodca-domains.dat** (содержит категорию `list`): 
  - [https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/hodca-domains.dat](https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/hodca-domains.dat)
- **news-domains.dat** (содержит категорию `list`): 
  - [https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/news-domains.dat](https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/news-domains.dat)
- **porn-domains.dat** (содержит категорию `list`): 
  - [https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/porn-domains.dat](https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/porn-domains.dat)


### Geosite по признаку, к какому ресурсу будет совершаться доступ

- **cloudflare-domains.dat** (содержит категорию `list`): 
  - [https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/cloudflare-domains.dat](https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/cloudflare-domains.dat)
- **cloudfront-domains.dat** (содержит категорию `list`): 
  - [https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/cloudfront-domains.dat](https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/cloudfront-domains.dat)
- **digitalocean-domains.dat** (содержит категорию `list`): 
  - [https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/digitalocean-domains.dat](https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/digitalocean-domains.dat)
- **discord-domains.dat** (содержит категорию `list`): 
  - [https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/discord-domains.dat](https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/discord-domains.dat)
- **google-ai-domains.dat** (содержит категорию `list`): 
  - [https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/google-ai-domains.dat](https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/google-ai-domains.dat)
- **google-play-domains.dat** (содержит категорию `list`): 
  - [https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/google-play-domains.dat](https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/google-play-domains.dat)
- **hdrezka-domains.dat** (содержит категорию `list`): 
  - [https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/hdrezka-domains.dat](https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/hdrezka-domains.dat)
- **hetzner-domains.dat** (содержит категорию `list`): 
  - [https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/hetzner-domains.dat](https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/hetzner-domains.dat)
- **meta-domains.dat** (содержит категорию `list`): 
  - [https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/meta-domains.dat](https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/meta-domains.dat)
- **ovh-domains.dat** (содержит категорию `list`): 
  - [https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/ovh-domains.dat](https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/ovh-domains.dat)
- **roblox-domains.dat** (содержит категорию `list`): 
  - [https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/roblox-domains.dat](https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/roblox-domains.dat)
- **telegram-domains.dat** (содержит категорию `list`): 
  - [https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/telegram-domains.dat](https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/telegram-domains.dat)
- **tiktok-domains.dat** (содержит категорию `list`): 
  - [https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/tiktok-domains.dat](https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/tiktok-domains.dat)
- **twitter-domains.dat** (содержит категорию `list`): 
  - [https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/twitter-domains.dat](https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/twitter-domains.dat)
- **youtube-domains.dat** (содержит категорию `list`): 
  - [https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/youtube-domains.dat](https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/youtube-domains.dat)


### Geoip по признаку, откуда будет совершаться доступ

- **ipv4-subnets.dat** (содержит `IPv4` подсети для `cloudflare`, `cloudfront`, `digitalocean`, `discord`, `hetzner`, `meta`, `ovh`, `roblox`, `telegram`, `twitter`): 
  - [https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/ipv4-subnets.dat](https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/ipv4-subnets.dat)
- **ipv6-subnets.dat** (содержит `IPv6` подсети для `cloudflare`, `cloudfront`, `digitalocean`, `discord`, `hetzner`, `meta`, `ovh`, `telegram`, `twitter`): 
  - [https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/ipv6-subnets.dat](https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/ipv6-subnets.dat)


### Geoip по признаку, к какому ресурсу будет совершаться доступ

- **cloudflare-subnets.dat** (содержит `IPv4` и `IPv6` подсети для `cloudflare`): 
  - [https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/cloudflare-subnets.dat](https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/cloudflare-subnets.dat)
- **cloudfront-subnets.dat** (содержит `IPv4` и `IPv6` подсети для `cloudfront`): 
  - [https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/cloudfront-subnets.dat](https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/cloudfront-subnets.dat)
- **digitalocean-subnets.dat** (содержит `IPv4` и `IPv6` подсети для `digitalocean`): 
  - [https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/digitalocean-subnets.dat](https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/digitalocean-subnets.dat)
- **discord-subnets.dat** (содержит `IPv4` и `IPv6` подсети для `discord`): 
  - [https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/discord-subnets.dat](https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/discord-subnets.dat)
- **hetzner-subnets.dat** (содержит `IPv4` и `IPv6` подсети для `hetzner`): 
  - [https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/hetzner-subnets.dat](https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/hetzner-subnets.dat)
- **meta-subnets.dat** (содержит `IPv4` и `IPv6` подсети для `meta`): 
  - [https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/meta-subnets.dat](https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/meta-subnets.dat)
- **ovh-subnets.dat** (содержит `IPv4` и `IPv6` подсети для `ovh`): 
  - [https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/ovh-subnets.dat](https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/ovh-subnets.dat)
- **roblox-subnets.dat** (содержит `IPv4` подсети для `roblox`): 
  - [https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/roblox-subnets.dat](https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/roblox-subnets.dat)
- **telegram-subnets.dat** (содержит `IPv4` и `IPv6` подсети для `telegram`): 
  - [https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/telegram-subnets.dat](https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/telegram-subnets.dat)
- **twitter-subnets.dat** (содержит `IPv4` и `IPv6` подсети для `twitter`): 
  - [https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/twitter-subnets.dat](https://github.com/KazZzeL/allow-domains-dat/releases/latest/download/twitter-subnets.dat)


## Примеры конфигураций

```jsonc
  "routing": {
    "domainStrategy": "IPIfNonMatch",
    "rules": [
      // При подключении внешних файлов
      {
        "domain": ["ext:allow-domains.dat:russia-inside"],
        "outboundTag": "proxy",
        "ruleTag": "russia-inside-proxy"
      },
      {
        "domain": ["ext:russia-outside.dat:list"],
        "outboundTag": "proxy",
        "ruleTag": "russia-outside-proxy"
      },
      {
        "ip": ["ext:allow-subnets.dat:discord"],
        "outboundTag": "proxy",
        "ruleTag": "discord-ips-proxy"
      }
      {
        "ip": ["ext:ipv6-subnets.dat:telegram"],
        "outboundTag": "proxy",
        "ruleTag": "telegram-ipv6-proxy"
      }
      // При подключении в ядро
      {
        "domain": ["geosite:russia-inside"],
        "outboundTag": "proxy",
        "ruleTag": "russia-inside-proxy"
      },
      {
        "domain": ["geosite:list"],
        "outboundTag": "proxy",
        "ruleTag": "domains-proxy"
      },
      {
        "ip": ["geoip:twitter"],
        "outboundTag": "proxy",
        "ruleTag": "twitter-ips-proxy"
      }
    ]
  }
```
