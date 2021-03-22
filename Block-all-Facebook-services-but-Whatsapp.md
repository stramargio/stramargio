# How to block all Facebook services but WhatsApp

### Use one of these apps/services to blacklist some DNS queries

Depending on what device you want to protect, you can choose a different app/service:

- [AdBlock](https://adguard.com/)
- [Blockada](https://blokada.org)
- [ReThink DNS](https://www.bravedns.com)
- [PiHole](https://pi-hole.net)
- [NextDNS](https://nextdns.io)

### Then, block Facebook-verse

Add all facebook related hosts to your blocking list:

- [Facebook Extended](https://www.github.developerdan.com/hosts/lists/facebook-extended.txt)

### Then, whitelist 4 domains (and subdomains) to let WhatsApp work

Whitelisting these hosts in order to use WhatsApp (+ Web) without privatestats, graph, etc.:

```
*.cdn.whatsapp.net
*.mmg.whatsapp.net
*.g.whatsapp.net
*.web.whatsapp.com
```

-----

You're welcome.

🐣 [@stramargio](https://twitter.com/stramargio)

✉️ [stramargio@icloud.com](mailto:stramargio@icloud.com)
