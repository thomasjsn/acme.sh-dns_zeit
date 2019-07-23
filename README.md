# acme.sh DNS API for ZEIT DNS
**Work in progress**

- [x] Add `_acme-challenge` records
- [ ] Remove `_acme-challenge` records when verification is done
- [ ] Clean up script
  - [ ] Remove commented out CF code
  
## Use
Copy to `acme.sh/dnsapi/`, use argument `--dns dns_zeit`

## Development
```
acme.sh --issue --staging --debug 2 -d domain --dns dns_zeit
```

## Resources
* Dev guide: https://github.com/Neilpang/acme.sh/wiki/DNS-API-Dev-Guide
* Zeit DNS API: https://zeit.co/docs/api#endpoints/dns
