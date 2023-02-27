## Google Dorks

The following dorks can be used to find C2 panels of HTTP-based botnets:

- intitle:"BlackNET" intext:"Login"

## Shodan Dorks

The following ports are commonly used by remote access trojans to communicate with their C2 servers:
- port:31337 (used by Back Orifice)
- port:4444 (used by Metasploit)
- port:5555 (used by APT trojans)
- port:6667 (used by IRC botnets)
- port:8080 (used by HTTP-based botnets)
- port:8443 (used by HTTP-based botnets)
- port:8888 (used by HTTP-based botnets)

These dorks can be used to find servers with open ports and identify potential RAT C2s  Note that using these dorks may reveal sensitive information about potential targets. Always use them with caution and only for lawful purposes
