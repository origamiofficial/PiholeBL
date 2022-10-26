# PiholeBL - Domain BlockList
![GitHub file size in bytes](https://img.shields.io/github/size/origamiofficial/PiholeBL/ApexBLPihole.txt?label=ApexBLPihole) ![GitHub file size in bytes](https://img.shields.io/github/size/origamiofficial/PiholeBL/PublicBLPihole.txt?label=PublicBLPihole) [![Hits-of-Code](https://hitsofcode.com/github/origamiofficial/piholebl?branch=main)](https://github.com/origamiofficial/PiholeBL)

What is DomainBL?
* A periodically updated list of malicious domains first observed on a given day.
* We create two lists
  * [ApexBLPihole.txt](https://raw.githubusercontent.com/origamiofficial/PiholeBL/main/ApexBLPihole.txt) - malicious apex domains | Domains that are involved directly
  * [PublicBLPihole.txt](https://raw.githubusercontent.com/origamiofficial/PiholeBL/main/PublicBLPihole.txt) - malicious full qualified domains hosted on public hosting domains | Subdomains that used publicly available services
  * [Whitelist.txt](https://github.com/origamiofficial/PiholeBL/blob/main/Whitelist.txt) - if you found any necessary domains being blocked, add them here & create a pull request. They'll be unblocked in the next day's update | No need to add them in your Pi-hole

How do we create DomainBL?
* We utilize state of the art ML/AI technologies to identify malicious domains.

Why malicious domains instead of malicious URLs?
* Most of the blocklists out there focus on malicious URLs, but our goal is one step beyond to provide better protection by identifying malicious domains (i.e. domains created by attackers to launch attacks) with minimal collerateral damage (i.e. malicious domains due to benign domains being compromised). Knowing such domains makes the blocking easier as all future URLs under the same domains are blocked.

Who can use these malicious domains?
* We make them available for non-commercial consumption. Please contact upstream if you'd like to have premimum access with a fee.

Blacklist Upstream:
* [DomainBL](https://github.com/nabeelxy/domainBL): A Proactive Malicious Domain Blocklist

```
@misc {domainbl,
  title = {DomainBL: A Proactive Malicious Domain Blocklist},
  author = {Mohamed Nabeel},
  year = {2022},
  url = {https://github.com/nabeelxy/domainBL}
}
```
[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https://github.com/origamiofficial/PiholeBL&icon=github.svg&icon_color=%23FFFFFF&title=hits&edge_flat=false)](https://github.com/origamiofficial/PiholeBL)
