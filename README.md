# PiholeBL - Domain BlockList

What is DomainBL?
* A periodically updated list of malicious domains first observed on a given day.
* We create two lists
  * [ApexBLPihole](https://raw.githubusercontent.com/anjumrafidofficial/PiholeBL/main/ApexBLPihole.txt) - malicious apex domains
  * [PublicBLPihole](https://raw.githubusercontent.com/anjumrafidofficial/PiholeBL/main/PublicBLPihole.txt) - malicious full qualified domains hosted on public hosting domains

How do we create DomainBL?
* We utilize state of the art ML/AI technologies to identify malicious domains.

Why malicious domains instead of malicious URLs?
* Most of the blocklists out there focus on malicious URLs, but our goal is one step beyond to provide better protection by identifying malicious domains (i.e. domains created by attackers to launch attacks) with minimal collerateral damage (i.e. malicious domains due to benign domains being compromised). Knowing such domains makes the blocking easier as all future URLs under the same domains are blocked.

Who can use these malicious domains?
* We make them available for non-commercial consumption. Please contact upstream if you'd like to have premimum access with a fee.

Blacklist Upstream:
* [DomainBL](https://github.com/nabeelxy/domainBL): A Proactive Malicious Domain Blocklist
