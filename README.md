# Categorized Web Filter Blocklists

This repository provides curated domain-based blocklists for web filtering.  
Designed for firewalls and DNS filtering platforms.

Tested with:
- pfSense (pfBlockerNG, Unbound)
- OPNsense (Unbound, DNSBL)
- FortiGate (URL Filter)
- MikroTik (Web proxy, DNS filtering)
- Sophos XGS (Web filter policies)
- Others supporting URL or DNS-based filtering

---

## Category Index

The blocklists are sorted into folders by category:

- `ads`
- `adult`
- `aggressive`
- `arjel`
- `associations_religieuses`
- `astrology`
- `audio-video`
- `bank`
- `bitcoin`
- `blog`
- `celebrity`
- `chat`
- `child`
- `cleaning`
- `cooking`
- `cryptojacking`
- `dangerous_material`
- `dating`
- `ddos`
- `dialer`
- `doh`  
- `download`
- `drugs`
- `drogue`
- `dynamic-dns`
- `educational_games`
- `examen_pix`
- `exceptions_liste_bu`
- `fakenews`
- `filehosting`
- `financial`
- `forums`
- `gambling`
- `games`
- `global_usage`
- `hacking`
- `jobsearch`
- `lingerie`
- `liste_blanche`
- `liste_bu`
- `mail`
- `malware`
- `manga`
- `marketingware`
- `mixed_adult`
- `mobile-phone`
- `phishing`
- `porn`
- `press`
- `proxy`
- `publicite`
- `radio`
- `reaffected`
- `redirector`
- `remote-control`
- `residential-proxies`
- `sect`
- `sexual_education`
- `shopping`
- `shortener`
- `social_networks`
- `special`
- `sports`
- `stalkerware`
- `strict_redirector`
- `strong_redirector`
- `translation`
- `tricheur`
- `tricheur_pix`
- `update`
- `vpn`
- `violence`
- `warez`
- `webhosting`
- `webmail`

---

## Format

- UTF-8 encoded text  
- One domain per line  
- No wildcard usage  
- Subdomains listed only if required

Example:
tracker.example.com
ads.network.io
subdomain.malicious.org


---

## Usage

Clone the repo or download from **releases** . Import lists as needed based on your firewall or DNS filter platform.

### pfSense / OPNsense  
Use with pfBlockerNG or Unbound's DNSBL.

### FortiGate  
Import as an external URL filter list or create a custom category.

### MikroTik  
Use in Web Proxy rules or with DNS static block entries.

### Sophos  
Upload as a custom web category in Firewall > Web Filter.

---

## Contribution

Submit an issue or pull request if:
- You want to report broken domains  
- Suggest new categories  
- Request format changes

---
---
## Credits ##
** IP Sets **  https://github.com/blocklist-ipsets
## License

MIT License. See `LICENSE` file.
